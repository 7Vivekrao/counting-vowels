# counting-vowels
This program helps to count the number of vowels in a given string.
The string considered here is represented by 's' and the program counts the number of vowels in s
count = 0
s = 'abacdefeuuinfbfisdci'
for char in s:    #char represents each character in s
  if char == 'a' or char == 'e' or char == 'i' or char == 'o' or char == 'u':
     count = count + 1  #increment the counter by 1
print("Number of vowels:" +""+str(counter))
