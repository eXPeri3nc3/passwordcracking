# passwordcracking
Password cracking intel &amp; repo

cat pass.txt | sed $'s/[^[:punct:][:digit:]\t]//g' > digitsymbol.txt
cat pass.txt | sed $'s/[^[:alpha:]\t]//g' > word.txt 
