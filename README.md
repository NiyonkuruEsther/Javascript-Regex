- [ ] * 0 or more matches
- [ ] + 1 or more matches
- [ ] ? 0 or 1 match
- [ ] ^ matches the start of the string or line (asserts that we are at the start of the string)
- [ ] $ matches the end of the string or line (asserts that we are at the end of the string)
- [ ] \ signifies an escape sequence, it is used to match the reserved symbols and it is put infront of them
- [ ] . matches any single character except newline
- [ ] ( ) capturing group. Save to reuse later
- [ ] | used as a logic OR inside a capturing group
- [ ] [abc] character set. Matches one of the things in the brackets
- [ ] [^abc] Negated character set. Matches anything except...
- [ ] [a-zA-Z] all upper and lowercase letters. You can specify any range.
- [ ] {1} exact number of matches. Comes after a set or group.
- [ ] {1,5} inclusive range for number of matches
- [ ] {1,} minimum number of matches
- [ ] {,5} maximum number of matches
- [ ] \s any whitespace character
- [ ] \S any NON whitespace character
- [ ] \d any digit. Same as [0-9]
- [ ] \D any NON digit
- [ ] \w any word character. Same as [a-zA-Z0-9_] which are the ASCII characters anyways
- [ ] \W any NON word character. Same as [^a-za-z0-9_]
- [ ] \b word boundary {things that can be put between words like th espaces or underscore or ~ etc}
- [ ] \B NON word boundary
- [ ] [\b] - escape sequence for a backspace character
- [ ] \u0404 - 4 digit unicode hex value for a character
