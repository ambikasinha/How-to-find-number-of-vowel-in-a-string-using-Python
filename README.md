# How-to-find-number-of-vowel-in-a-string-using-Python
#code to calculate vowel count
a="Kanika loves to sing and dance!" # input string
vowel="aeiouAEIOU" # declaring vowel in lower and upper case
v_count={} # initializing vowel count - data type is list
for v in vowel: # for loop to check every charater of the string list
 count=a.count(v) # counter to check and tally vowel count in the string
 v_count[v]=count # total count against individual vowel charater
print(v_count) # prints character wise counts - {'a': 4, 'e': 2, 'i': 2, 'o': 2, 'u': 0, 'A': 0, 'E': 0, 'I': 0, 'O': 0, 'U': 0}
counts=v_count.values() # to count vowel characters in a string
totalvowel=sum(counts) # total sum of vowel
print("Total Vowel Count",totalvowel) # prints total vowel - Total Vowel Count 10
