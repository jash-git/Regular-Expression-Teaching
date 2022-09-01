正則表達式 影片+PDF 教學 [Regular Expression Teaching]

資料來源: https://www.youtube.com/watch?v=VFOj_sjuBmk

線上編譯器: https://regex101.com/

正規表示式/ 正規表達式文字摘要

. 點，匹配任何字符
^ 開始錨，匹配字符串的開頭
$ 結束錨，匹配字符串的結尾
* 星號，匹配零個或多個（貪婪）
+ 加號，匹配一個或多個（貪婪）
？ 問題，匹配零或一（非貪婪）
[abc] 字符類，如果{‘a’，’b’，’c’}中的一個匹配則匹配
[^abc] 反相的類，如果不是{‘a’，’b’，’c’}中的一個，則匹配。注意：此功能當前在某些字符範圍內無效！
[a-zA-Z] 字符範圍，範圍的字符集{a-z | A-Z}
\s 空格，\t \f \r \n \v和空格
\S 非空白
\w 字母數字，[a-zA-Z0-9_]
\W 非字母數字
\d 位數字，[0-9]
\D 非數字

. Dot, matches any character
^ Start anchor, matches beginning of string
$ End anchor, matches end of string
* Asterisk, match zero or more (greedy)
+ Plus, match one or more (greedy)
? Question, match zero or one (non-greedy)
[abc] Character class, match if one of {‘a’, ‘b’, ‘c’}
[^abc] Inverted class, match if NOT one of {‘a’, ‘b’, ‘c’} NOTE: This feature is currently broken for some usage of character ranges!
[a-zA-Z] Character ranges, the character set of the ranges { a-z | A-Z }
\s Whitespace, \t \f \r \n \v and spaces
\S Non-whitespace
\w Alphanumeric, [a-zA-Z0-9_]
\W Non-alphanumeric
\d Digits, [0-9]
\D Non-digits 