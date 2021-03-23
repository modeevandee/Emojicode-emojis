# Emojicode Program
Notes: 
<br>https://www.youtube.com/watch?v=gk6NL1pZi1M
<br>https://www.emojicode.org/docs/reference/variables.html
Emoji  | Description
------------- | -------------
🏁  | Part of the program that is executed when it is started
🏁 ➡️ 🔢 🍇  | Function will return an integer
↩️ 0  | Return 0
💭  | Comments begin with 💭 and end at the end of the line
💭🔜  🔚💭  | Multiline comments
📜 🔤path/to/a/file.emojic🔤  | Including Code

# Number Types
There are three numeric types in Emojicode:
Emoji  | Description
------------- | -------------
🔢  | represents integer in the interval [-263, 263-1], the default type for an integer literal.
💯  | represents real numbers (numbers with decimal place)
💧  | represents bytes, which are integers in the range of [-128,127] normally.

# Booleans
Emoji  | Description
------------- | -------------
👌  | type to represent Boolean values
👍  | Creates a true value
👎  | Creates a false value

# Strings
Emoji  | Description
------------- | -------------
🔡 type  | Strings are textual data that is represented by this type
🔤This is a string.🔤  | include strings in your code by surrounding the characters by a pair of 🔤
🔤This is a string.🔤 ➡️ aString  | Declaration of a string
🧲  | Interpolation in String Literals
🔤 The value of variable varA is 🧲varA🧲 and method ⚱️ returned 🧲⚱️a❗️🧲.🔤  | Interpolation in String Literals

# Escapes
Emoji  | Output
------------- | -------------
❌❌  | ❌
❌🔤  | 🔤
❌🧲  | 🧲
❌n  | New line (U+A0)
❌t  | Tab (U+09)
❌r  | Carriage return (U+0D)
❌e  | Escape (U+1B)

All other combinations of a ❌ and another character lead to a compiler error.

# Collections
Emoji  | Output
------------- | -------------
🍿 14 67 2434 🍆  | List literal with the values 14, 67, 2434
 list type 🍨  | default type of list literal
🍿<br>&nbsp;&nbsp;&nbsp;🔤Aaron Copland🔤 ➡️ 🔤Brooklyn🔤<br>&nbsp;&nbsp;&nbsp;🔤Michael Jackson🔤 ➡️ 🔤Gary🔤<br>&nbsp;&nbsp;&nbsp;🔤Falco🔤 ➡️ 🔤Vienna🔤<br>🍆  | In a dictionary literal, keys are associated with a value. <br>This example shows a dictionary literal that <br>associates artists with their birthplaces.
🍯 | type, a simple hash-table, storing key-value pairs

# Variables and Assignment
The variable name can consist of any sequence of characters but may not contain spaces or emojis and may not begin with a number. 
Emoji  | Output
------------- | -------------
Constant variables  | &nbsp;&nbsp;&nbsp;31 ➡️ daysInDecember<br>&nbsp;&nbsp;&nbsp;🔤Earth🔤 ➡️ thirdPlanet
Mutable Variables  | &nbsp;&nbsp;&nbsp;5300 ➡️ 🖍🆕 money<br>&nbsp;&nbsp;&nbsp;🖍🆕 catName 🔡
Assigning Values to variables  | &nbsp;&nbsp;&nbsp;5300 ➡️ 🖍 money<br>&nbsp;&nbsp;&nbsp;🔤Kitty🔤 ➡️ 🖍 catName
(everything between a 🍇 and 🍉)  | defines a separate scope.
❌🔤  | 🔤
❌🔤  | 🔤
