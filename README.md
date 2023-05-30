# regex-cheat-sheet

Modifiers / flags :

 i => case-insensitive

 g => global

 m => Multilines

----------------------

Rages :
 
 /(X|Y|Z)/      => X or Y or Z

 /[0-9]/        => 0 to 9

 /[^0-9]/       => any character not 0 to 9
 
 /[a-zA-Z0-9]/  => match all alphabets (lowercase and uppercase) and also all numbers, but no special chars

----------------------

Character Classes

 /./   => matches all, expect new lines or other line terminators
 /\w/  => matches word characters. [ a-z, A-Z, 0-9 and underscore ]
 /\W/  => matches non word characters
 /\d/  => matches digits from 0 to 9
 /\D/  => matches non digits characters
 /\s/  => matches whitespace characters
 /\S/  => matches non whitespace characters

 /\b/  => matches at the beginning or at the end of a word
 /\B/  => matches not at the beginning / end of a word

----------------------

Quantifiers

n+ => one or more ( if more than one grap all of them ) <br />
n? => zero or one ( optional ) <br />
n* => zero or more ( optional but if you found more than one grap all of them ) <br />

n{x}    => number of x <br />
n{x,y}  => range x-y <br />
n{x,}   => at least x <br />

$    =>  End with something <br />
^    => start with something <br />
?=   => followed by somehting <br />
?!   => not followed by something
