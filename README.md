# crm_test
Setting Up Git

Using the unless Keyword
1
puts "Enter a number:"
number = gets.to_i
puts "The number is not positive." unless number > 0

2
puts "Enter a word:"
word = gets.chomp
puts "The word does not contain the letter 'a'." unless word.include?('a')

3
puts "Enter your age:"
age = gets.to_i
puts "You are not eligible to vote." unless age >= 18

4
puts "Enter a string:"
input = gets.chomp
puts "You entered: #{input}" unless input.empty?

5
puts "Enter a number:"
number = gets.to_i
puts "The number is odd." unless number.even?

6
puts "Are you logged in? (yes/no):"
logged_in = gets.chomp.downcase
puts "You need to log in." unless logged_in == "yes"

7
puts "Enter the current temperature (in °F):"
temperature = gets.to_i
puts "The temperature is above freezing." unless temperature < 32

8
puts "Enter a number:"
number = gets.to_i
puts "The number is not divisible by 5." unless number % 5 == 0

9
puts "Enter your password:"
password = gets.chomp
puts "Access denied." unless password == "12345"

10
puts "Enter your age:"
age = gets.to_i
puts "You are not an adult." unless age >= 18




Using the case Statement

1
puts "Enter a day of the week (1-7):"
day = gets.to_i
day_name = case day
           when 1 then "Monday"
           when 2 then "Tuesday"
           when 3 then "Wednesday"
           when 4 then "Thursday"
           when 5 then "Friday"
           when 6 then "Saturday"
           when 7 then "Sunday"
           else "Invalid day"
           end
puts day_name

2
puts "Enter a letter grade (A, B, C, D, F):"
grade = gets.chomp.upcase
message = case grade
          when "A" then "Excellent"
          when "B" then "Good"
          when "C" then "Average"
          when "D" then "Poor"
          when "F" then "Fail"
          else "Invalid grade"
          end
puts message

3
puts "Enter a t-shirt size (S, M, L, XL):"
size = gets.chomp.upcase
size_name = case size
            when "S" then "Small"
            when "M" then "Medium"
            when "L" then "Large"
            when "XL" then "Extra Large"
            else "Invalid size"
            end
puts size_name

4
puts "Enter a traffic light color (red, yellow, green):"
color = gets.chomp.downcase
action = case color
         when "red" then "Stop"
         when "yellow" then "Caution"
         when "green" then "Go"
         else "Invalid color"
         end
puts action

5
puts "Enter a month:"
month = gets.chomp.capitalize
season = case month
         when "December", "January", "February" then "Winter"
         when "March", "April", "May" then "Spring"
         when "June", "July", "August" then "Summer"
         when "September", "October", "November" then "Fall"
         else "Invalid month"
         end
puts season

6
puts "Enter the name of an animal:"
animal = gets.chomp.downcase
type = case animal
       when "dog", "cat", "elephant" then "Mammal"
       when "eagle", "sparrow", "penguin" then "Bird"
       when "snake", "lizard", "crocodile" then "Reptile"
       else "Unknown type"
       end
puts type

7
puts "Enter a movie genre (comedy, drama, action, horror):"
genre = gets.chomp.downcase
suggestion = case genre
             when "comedy" then "Watch 'The Office'"
             when "drama" then "Watch 'The Godfather'"
             when "action" then "Watch 'Mad Max: Fury Road'"
             when "horror" then "Watch 'The Conjuring'"
             else "Invalid genre"
             end
puts suggestion

8
puts "Enter your gender (male/female):"
gender = gets.chomp.downcase
puts "Enter your marital status (married/single):"
status = gets.chomp.downcase
title = case [gender, status]
        when ["male", "married"] then "Mr."
        when ["male", "single"] then "Mr."
        when ["female", "married"] then "Mrs."
        when ["female", "single"] then "Ms."
        else "Invalid input"
        end
puts title

9
puts "Enter a number:"
number = gets.to_i
message = case number
          when 0...10 then "The number is less than 10."
          when 10..20 then "The number is between 10 and 20."
          else "The number is greater than 20."
          end
puts message

10
puts "Enter the number of sides of a shape (3, 4, 5, 6):"
sides = gets.to_i
shape = case sides
        when 3 then "Triangle"
        when 4 then "Square"
        when 5 then "Pentagon"
        when 6 then "Hexagon"
        else "Invalid number of sides"
        end
puts shape














1
5.times { puts "Hello, World!" }

2
10.times { |i| puts i }

3
7.times { puts "I love Ruby!" }

4.
10.times { |i| puts (i + 1) ** 2 }

5
puts "Enter a number:"
number = gets.to_i
number.times { |i| puts "This is iteration number #{i + 1}" }

6
sum = 0
100.times { |i| sum += (i + 1) }
puts sum

7
puts "How many times to iterate?"
iterations = gets.to_i
puts "Enter a word:"
word = gets.chomp
iterations.times { puts word }

8
arr = ["apple", "banana", "cherry"]
arr.reverse.each { |str| puts str }

9
puts "Enter the number of rows:"
rows = gets.to_i
rows.times { |i| puts "*" * (i + 1) }

10
puts "Enter a number:"
number = gets.to_i
factorial = 1
number.times { |i| factorial *= (i + 1) }
puts "Factorial: #{factorial}"

11
10.times { puts rand(1..100) }

12
puts "Enter a number:"
number = gets.to_i
number.times { |i| puts "#{i + 1}" * (i + 1) }

13
10.times do
  die1 = rand(1..6)
  die2 = rand(1..6)
  sum = die1 + die2
  puts "Die 1: #{die1}, Die 2: #{die2}, Sum: #{sum} (#{sum.even? ? 'Even' : 'Odd'})"
end

14
random_string = ""
8.times { random_string += ('a'..'z').to_a.sample }
puts random_string

15
colors = ["red", "blue", "green"]
colors.each { |color| puts color }

16
numbers = [1, 2, 3, 4, 5]
numbers.each { |number| puts number }

17
numbers = [1, 2, 3, 4, 5]
numbers.each { |number| puts number + 2 }

18
words = ["apple", "banana", "grape"]
words.each { |word| puts word.length }

19
hash = { a: 1, b: 2, c: 3 }
hash.each { |key, value| puts "#{key}: #{value}" }

20
numbers = [2, 4, 6]
numbers.each { |number| puts number * 2 }

21
names = ["john", "jane", "doe"]
names.each { |name| puts name.capitalize }

22
numbers = [1, 2, 3, 4, 5]
sum = 0
numbers.each { |number| sum += number }
puts sum

23
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
numbers.each { |number| puts number if number.even? }

24
array1 = [1, 2, 3]
array2 = [4, 5, 6]
array1.each_with_index { |num, index| puts num * array2[index] }

25
nested_array = [[1, 2], [3, 4], [5, 6]]
nested_array.each { |sub_array| puts sub_array.inspect }

26
strings = ["apple", "banana", "cherry"]
strings.each { |str| puts str.reverse }

27
puts "Enter a string:"
input = gets.chomp
occurrences = Hash.new(0)
input.each_char { |char| occurrences[char] += 1 }
puts occurrences

28
keys = [:a, :b, :c]
values = [1, 2, 3]
hash = {}
keys.each_with_index { |key, index| hash[key] = values[index] }
puts hash

29
words = ["level", "apple", "radar"]
words.each { |word| puts "#{word} is #{word == word.reverse ? '' : 'not '}a palindrome" }

30
for i in 1..10
  puts i
end

31
sum = 0
for i in 1..100
  sum += i
end
puts sum

32
fruits = ["apple", "banana", "cherry"]
for fruit in fruits
  puts fruit
end

33
for i in 1..10
  puts "5 x #{i} = #{5 * i}"
end

34
for i in 1..20
  puts i if i.even?
end

35
words = ["apple", "banana", "cherry"]
for word in words
  puts word.reverse
end

36
person = { name: "Alice", age: 25, city: "New York" }
for key, value in person
  puts "#{key}: #{value}"
end

37
puts "Enter the number of rows:"
rows = gets.to_i
for i in 1..rows
  puts "*" * i
end

38
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
sum = 0
for number in numbers
  sum += number if number.even?
end
puts sum

39
puts "Enter a string:"
input = gets.chomp
vowels = %w[a e i o u]
count = 0
for char in input.chars
  count += 1 if vowels.include?(char)
end
puts count

40
numbers = [3, 7, 2, 8, 5, 10, 1]
max = numbers.first
min = numbers.first
for number in numbers
  max = number if number > max
  min = number if number < min
end
puts "Max: #{max}, Min: #{min}"

41
print "Enter a sentence: "
sentence = gets.chomp
words = sentence.split(" ")

for word in words
  puts word.reverse
end

42
print "Enter the number of rows: "
rows = gets.chomp.to_i

for i in 1..rows
  puts i.to_s * i
end

43
for i in 1..10
  puts i
end

44
sum = 0
for i in 1..100
  sum += i
end
puts sum

45
fruits = ["apple", "banana", "cherry"]

for fruit in fruits
  puts fruit
end

46
for i in 1..10
  puts "5 x #{i} = #{5 * i}"
end

47
for i in 1..20
  if i.even?
    puts i
  end
end

48
words = ["hello", "world", "ruby"]

for word in words
  puts word.reverse
end

49
person = { name: "Alice", age: 25, city: "New York" }

for key, value in person
  puts "#{key}: #{value}"
end

50
print "Enter the number of rows: "
rows = gets.chomp.to_i

for i in 1..rows
  puts "*" * i
end

51
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
sum_even = 0

for number in numbers
  if number.even?
    sum_even += number
  end
end

puts sum_even

52
print "Enter a string: "
str = gets.chomp
vowel_count = 0

for char in str.downcase.chars
  if "aeiou".include?(char)
    vowel_count += 1
  end
end

puts vowel_count

53
numbers = [10, 3, 45, 67, 23, 89, 2]
min_num = numbers[0]
max_num = numbers[0]

for number in numbers
  if number < min_num
    min_num = number
  end
  if number > max_num
    max_num = number
  end
end

puts "Min: #{min_num}"
puts "Max: #{max_num}"

54
print "Enter the number of rows: "
rows = gets.chomp.to_i

for i in 1..rows
  puts i.to_s * i
end














1
number = 10
while number > 0
  puts number
  number -= 1
end

2
total_sum = 0
number = nil

while number != 0
  print "Enter a number (0 to stop): "
  number = gets.chomp.to_i
  total_sum += number unless number == 0
end

puts "Total sum: #{total_sum}"

3
password = ""

while password != "secret"
  print "Enter the password: "
  password = gets.chomp
end

puts "Password correct!"

4
print "Enter a number: "
number = gets.chomp.to_i
multiplier = 1

while number * multiplier <= 50
  puts "#{number} x #{multiplier} = #{number * multiplier}"
  multiplier += 1
end

5
target = rand(1..100)
guess = nil

while guess != target
  print "Guess the number (1-100): "
  guess = gets.chomp.to_i
  if guess < target
    puts "Too low!"
  elsif guess > target
    puts "Too high!"
  end
end

puts "Correct! The number was #{target}."

6
number = 1

while number <= 20
  puts number if number.even?
  number += 1
end

7
input = ""

while input != "exit"
  print "Enter something (type 'exit' to quit): "
  input = gets.chomp
  puts input unless input == "exit"
end

8
original_array = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
even_numbers = []
index = 0

while index < original_array.length
  even_numbers << original_array[index] if original_array[index].even?
  index += 1
end

puts "Even numbers: #{even_numbers}"

9
array = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
count = 0
index = 0

while index < array.length
  count += 1 if array[index].odd?
  index += 1
end

puts "Number of odd numbers: #{count}"

10
array = [5, 12, 7, 18, 9, 15, 3]
index = 0

while index < array.length
  array.delete_at(index) if array[index] > 10
  index += 1
end

puts "Filtered array: #{array}"

11
array = [10, 20, 30, 40, 50]
target = 30
index = 0
found_index = nil

while index < array.length
  if array[index] == target
    found_index = index
    break
  end
  index += 1
end

puts "Index of #{target}: #{found_index.nil? ? 'Not found' : found_index}"

12
array = [1, 2, 3, 4, 5]
index = 0
all_positive = true

while index < array.length
  if array[index] <= 0
    all_positive = false
    break
  end
  index += 1
end

puts "All elements are positive: #{all_positive}"







1
number = 1

while number <= 20
  next if number.even?
  puts number
  number += 1
end

2
number = 1

until number % 7 == 0
  puts number
  number += 1
end

puts number # Print the number that is divisible by 7

3
target = rand(1..10)
guess = nil

while true
  print "Guess the number (1-10): "
  guess = gets.chomp.to_i

  if guess < target
    puts "Too low!"
  elsif guess > target
    puts "Too high!"
  else
    puts "Correct! The number was #{target}."
    break
  end
end

4
number = 2

while number <= 50
  puts number if number.even?
  break if number == 30
  number += 2
end

5
password = ""

while true
  print "Enter the password: "
  password = gets.chomp
  break if password == "ruby123"
end

puts "Password correct!"

6
def prime?(number)
  return false if number < 2
  (2..Math.sqrt(number)).each do |i|
    return false if number % i == 0
  end
  true
end

while true
  print "Enter a number to check if it's prime (or 'exit' to quit): "
  input = gets.chomp

  break if input == "exit"

  number = input.to_i
  next if number < 2

  if prime?(number)
    puts "#{number} is a prime number."
  else
    puts "#{number} is not a prime number."
  end
end

7
number = 1

until number > 20
  next if number % 5 == 0
  puts number
  number += 1
end

8
number = 1

while true
  square = number * number
  if square > 1000
    break
  end
  puts square
  number += 1
end

9
total = 0

while total <= 50
  print "Enter a number: "
  number = gets.chomp.to_i

  next if number % 4 == 0

  total += number
end

puts "Total: #{total}"


