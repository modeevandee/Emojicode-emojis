# Emojicode Program
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
{🍿
  🔤Aaron Copland🔤 ➡️ 🔤Brooklyn🔤
  🔤Michael Jackson🔤 ➡️ 🔤Gary🔤
  🔤Falco🔤 ➡️ 🔤Vienna🔤
🍆}  | In a dictionary literal, keys are associated with a value
