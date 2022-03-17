# References
[www.rexegg.com](https://www.rexegg.com/regex-quickstart.html)

# Characters 
| Character| Explanation| Example | Sample match |
| :---  | :---: | :---  | :--- | 
| . | Anything except a line break. | a.c | **abc**, **a2c** |
| \s | White space character | |
| \S | Not a white space character | |

 
# Character Classes
|Syntax | Explanation| Example | Sample match |
| :---  | :---: | :---  | :--- | 
| [ ... ]. | Anything except a line break. | [uU]ser | **user**, **User** |

# Quantifiers
| Quantifier | Explanation| Example | Sample match |
| :---  | :---: | :---  | :--- | 
| . | Anything except a line break. | a.c | **abc**, **a2c** | ? | Once or none | plurals?| **plurals**, **plural** |
| + | Once or more | A-\d+ | **A-1**, **A-24** |
| * | Zero or more | a*bc | **bc**, **abc**, **aabc** ...|
| {2,4} |From two to four | | |
| {2,} | Two or more | | |
| {5} | Five times | | |

# Logic
|Syntax | Explanation| Example | Sample match |
| :---  | :---: | :---  | :--- | 
| \| | Or | cat\|dog | **cat**, **dog** |
| ( ... ) | Frames a capture group. | (\S*)\sgroup| **Python** group|

# Anchors
|Syntax | Explanation| Example | Sample match |
| :---  | :---: | :---  | :--- | 
| ^ | Start of string or line. | ^P\.S\. .* | **P.S. I am sorry.** |
| $ | End of sting or line. | the end\.*$ | **the end** |


# Concepts

| Concept | Explanation| Example | Sample match |
| :---  | :---: | ---:  |---: | 
| [Greedy quantifier](https://javascript.info/regexp-greedy-and-lazy) | By default the engine first overshoots and then backtracks.| ".*"  |  He wanted **"Apples" and "Bananas"**.|
| [Lazy quantifier](https://javascript.info/regexp-greedy-and-lazy) | Adding ? after a quantifier stops the engine as soon as possible. | ".*?" | He wanted **"Apples"** and **"Bananas"**.| 
| Escape characters | Prefix special characters with \ to use them literally. | "\\.pdf" | myDoc<b>.pdf</b>|