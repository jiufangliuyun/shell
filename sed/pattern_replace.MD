file:
111
222
333
>>>
444
555
<<<
666

sed '/>>>/,/<<</{//b;d}' file
111
222
333
>>>
<<<
666

// replace the pattern the beginning such as >>>and<<<
