# Regex Notes


## Meta Characters

 . [ { ( ) \ ^ $ | ? * + 

- If we want to find MetaCharacters like “.”
- We need **escape character** “\.”



## Matches



- **\d** Matches any digit character (0-9)
- **\D** Matches any character that is not an  digit (0-9)

- **\w** Matches any word character (A-Z, a-z, 0-9, _ ) (alphaNumeric and underScore)
- **\W** Matches anything that is not a word character (spaces, ?, *, + ...)

- **\s** White space (space, tab, newLine)
- **\S** Matches anything that is not White space (space, tab, newLine)

- **\b** Word Boundry
- **\B** Not a word Boundry

- **^** Beginning of the string

- **$** End of the string

- **.** Matches anything except lineBreaks



## Character Set

- **[1-7]** Numbers between 1 to 7
- **[1234567]** Numbers between 1 to 7

- **[a-z]** Lower case numbers
- **[A-Z]** Upper case numbers
- **[A-Za-z]** Lower case + upper case numbers


### Exact Numbers

- **\d{11}** Contains 11 digit

- **[]** Matches caharacter in brackets

- **[^]** Matches caharacter in brackets

- **|** Either Or

- **()** Group

## Quatifier

__*__    ==> 0 or More

**+**   ==> 1 or More

**?**   ==> 0 or One

**{3}**   ==> ExactNumber

**{3,4}**   ==> Range Of Number


## Look Ahead and Look Behind

**.(?=u)** ==> Choose a character continue with "u"

**.(?!u)** ==> Choose a character that is not continue with "u"

<b>(?<=q).</b> ==> Choose a character there is "q" before

**(?!=q).** ==> Choose a character there is not "q" before


