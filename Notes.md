**Regular Expression (JavaScript)**

[YouTube - NetNinja](https://youtu.be/uaepGvA-iK4)

[RegEx - Website](https://regex101.com/)

**Lesson2: Flag Meaning**
1. Global: Not only first match
2. Insensative: Case sensitive ignorance

**Lesson3: Characterset**
- using the mark ``[]`` and inside putting all the characters that can be substituted inside
- it just occupries one space in the text
- ``[^]`` include everything exclude characters that ensures (exception)
- everything next each other symbolize *or*

**Lesson4: Range**
- ``[a-z]`` means include everything inside one character space

**Lesson5: Repeating Characters**
- ``+`` means repeating the previous characters at least once to the unlimited time
- ``{n}`` means repeating at n-times
- ``{n, m}`` means repeating between n and m times
    - leaving m to be blank means at least n times to the infinite times maximum

**Lesson6: Metacharacters**
1. ``\d`` means any digit character (same as [0-9])
2. ``\w`` means any word character (a-z, A-Z, 0-9 and 's)
3. ``\s`` means a whitespace character (space and tab, etc)
4. ``\t`` means a tab character only

- ``d`` match the character *d* only
- ``\d`` means any digit character
- uses together with the character of ``{}``

**Lesson7: Special Characters**
1. ``+`` means one-or-more quantifier
2. ``\`` means the escape character
    ``\*`` means you only accept ``*`` at that particular location
3. ``[]`` means the character set
4. ``[^]`` means the negate symbol in a character set
5. ``?`` means zero-or-one quantifier (makes a preceding char optional)
6. ``.`` any character whatsoever (except the newline character)
7. ``*`` means the 0-or-more quantifier (a bit like +)

**Lesson8: Starting & Ending Pattern**
1. ``^`` means starting with the character set after this symbol
2. ``$`` means ending with the character set after this symbol
- uses to limit redundant input when used in combination

**Lesson9: Alternate Character**
1. ``|`` means or
    - the or comparision is irrespective of the length of each alternate
2. ``()`` means evaluate satisfy relationship inside first as mini character set (separately)
    - everything inside will be evaluated and treated as one character set space