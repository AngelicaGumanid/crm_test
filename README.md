# crm_test
Setting Up Git

21
print "Enter your height in centimeters: "
height_cm = gets.chomp.to_f
height_m = height_cm / 100

print "Your height in meters is #{height_m} m."

22
divisor = 7
quotient = 50 / divisor
remainder = 50 % divisor

print "50 divided by #{divisor} is #{quotient}, with a remainder of #{remainder}."

23
book_title = "The Great Gatsby"
author = "F. Scott Fitzgerald"

print "The book titled '#{book_title}' was written by #{author}."

24
print "Enter a number: "
number = gets.chomp.to_i
square = number ** 2

print "The square of #{number} is #{square}."

25
temperature_celsius = 25
temperature_fahrenheit = (temperature_celsius * 9/5) + 32

print "The temperature is #{temperature_celsius}°C, which is #{temperature_fahrenheit}°F."

26
string1 = "Angelica"
string2 = "Gumanid"

combined = string1[0, 3] + string2[-2, 2]

print "The concatenated result is '#{combined}'."

27
price_item1 = 30.5
price_item2 = 20.75
total = price_item1 + price_item2

print "The total is #{total}."

28
print "Enter a word: "
word = gets.chomp

print "The length of the word is #{word.length}."

29
print "Enter a sentence: "
sentence = gets.chomp

print "The sentence in uppercase is: #{sentence.upcase}"

30
print "Enter a word: "
word = gets.chomp

print "The first 5 characters are '#{word[0, 5]}'."

31
print "Enter a word: "
word = gets.chomp

print "The word reversed is '#{word.reverse}'."

32
print "Enter a number: "
number = gets.chomp.to_i
square = number ** 2

print "The square of the number is #{square}."

33
print "Enter your name: "
name = gets.chomp

print "Your name capitalized is '#{name.capitalize}'."

34
print "Enter a number: "
number = gets.chomp.to_f
square_root = Math.sqrt(number)

print "The square root of the number is #{square_root}."

35
sentence = "This Is A MIXED Case Sentence."
lowercase_sentence = sentence.downcase

print "The sentence in lowercase is: '#{lowercase_sentence}'."

36
sum = 12 + 8

print "The sum of 12 and 8 is #{sum}."

37
result = 45 - 20

print "45 minus 20 is #{result}."

38
product = 7 * 9

print "7 multiplied by 9 is #{product}."

39
quotient = 100 / 5

print "100 divided by 5 is #{quotient}."

40
remainder = 29 % 4

print "The remainder of 29 divided by 4 is #{remainder}."

41
result = 3 ** 4

print "3 raised to the power of 4 is #{result}."

42
number = 50
number += 30

print "The new value after adding 30 is #{number}."

43
number = 100
number -= 25

print "The new value after subtracting 25 is #{number}."

44
number = 8
number *= 5

print "The new value after multiplying by 5 is #{number}."

45
number = 64
number /= 8

print "The new value after dividing by 8 is #{number}."
