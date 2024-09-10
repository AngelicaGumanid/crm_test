# crm_test
Setting Up Git

10
countries = ["USA", "Canada", "Mexico", "Germany", "France"]
index = countries.index("Mexico")

puts "The index of 'Mexico' is #{index}."

11
family = ["John", "Alice", "Emma", "David"]
last_name = family[-1]

puts "The last name in the array is #{last_name}."

12
numbers = [3, 6, 9, 12, 15]
reversed_numbers = numbers.reverse

puts "The reversed array is #{reversed_numbers}."

13
animals = ["dog", "cat", "elephant", "giraffe", "lion"]
animals[2] = "tiger"

puts "The updated array of animals is #{animals}."

14
colors1 = ["red", "green", "blue"]
colors2 = ["yellow", "purple", "pink"]
combined_colors = colors1 + colors2

puts "The combined array is #{combined_colors}."

15
items = ["apple", "banana", "cherry", "date", "fig"]
items.each_with_index do |item, index|
  puts "Item #{index}: #{item}"
end

16
letters = ["a", "b", "c", "d", "e"]
if letters.include?("f")
  puts "f is found."
else
  puts "f is not found."
end

17
random_numbers = [4, 7, 1, 9, 3]
random_numbers.unshift(8, 2)

puts "The updated array with two new numbers is #{random_numbers}."

18
numbers = [1, 2, 3, 4, 5, 3, 1]
unique_numbers = numbers.uniq

puts "The unique values are #{unique_numbers}."

19
book = { title: "koda", author: "mark", pages: 100 }

puts "The book's title is '#{book[:title]}'."

20
fruit_prices = { apple: 2, banana: 1, cherry: 3 }
fruit_prices[:orange] = 4

puts "The updated fruit prices hash is #{fruit_prices}."

21
grades = { math: 90, english: 85, science: 88 }
grades[:english] = 95

puts "The updated grades hash is #{grades}."

22
shopping_cart = { shoes: 50, bag: 30, watch: 20 }
shopping_cart.delete(:watch)

puts "The updated shopping cart hash is #{shopping_cart}."

23
favorite_books = { 
  first: { title: "Book One", author: "Author One" }, 
  second: { title: "Book Two", author: "Author Two" }, 
  third: { title: "Book Three", author: "Author Three" } 
}

puts "The author of the second book is '#{favorite_books[:second][:author]}'."

24
person = { name: "John", age: 25, city: "New York" }
person[:job] = "developer"

puts "The updated hash is #{person}."

25
car = { maker: "Toyota", model: "Corolla", year: 2015 }
car[:year] = 2020

puts "The updated car details are #{car}."

26
numbers_hash = { one: 1, two: 2, three: 3 }
puts "The keys in the hash are #{numbers_hash.keys}."

27
colors_hash = { red: "#FF0000", green: "#00FF00", blue: "#0000FF" }
puts "The values in the hash are #{colors_hash.values}."

28
favorite_movie = { title: "Inception", director: "Christopher Nolan", year: 2010, rating: 8.8 }
puts "Favorite movie details: #{favorite_movie}."

29
people = {
  person1: { name: "Alice", age: 30 }, 
  person2: { name: "Bob", age: 25 }
}

puts "The name of person 2 is #{people[:person2][:name]}."

30
countries = {
  usa: { capital: "Washington", population: 331 }, 
  france: { capital: "Paris", population: 67 }
}

puts "The capital of France is #{countries[:france][:capital]}."

31
students = {
  student1: { math: 85, english: 90 }, 
  student2: { math: 78, english: 92 }
}

puts "The English grade of the second student is #{students[:student2][:english]}."

32
cars = { 
  car1: { make: "Toyota", model: "Corolla" }, 
  car2: { make: "Ford", model: "Mustang" }
}

puts "The model of car1 is #{cars[:car1][:model]}."

33
teams = {
  team_a: { player_1: "John", player_2: "Paul" }, 
  team_b: { player_1: "Sarah", player_2: "Lucy" }
}

puts "The name of player2 in Team B is #{teams[:team_b][:player_2]}."

34
numbers = { numbers: [10, 20, 30, 40] }
puts "The second number in the array is #{numbers[:numbers][1]}."

35
fruits = { red: ["apple", "cherry"], yellow: ["banana", "lemon"] }
puts "The second red fruit is #{fruits[:red][1]}."

36
stores = {
  store_1: { products: ["apples", "oranges"] }, 
  store_2: { products: ["bananas", "grapes"] }
}

puts "The second product from Store 2 is #{stores[:store_2][:products][1]}."

37
students = Array.new(10) { |i| { name: "Student#{i+1}", age: 20, grade: "A" } }

puts "The name of the 10th student is #{students[9][:name]}."

38
array = [
  [1, 2, 3],
  [4, 5, 6],
  [7, 8, 9],
  ['-', 0]
]

birthday = "#{array[2][1]}#{array[3][0]}#{array[0][0]}#{array[1][2]}-#{array[1][1]}#{array[1][2]}-#{array[0][1]}#{array[2][2]}"

puts "Your birthday is #{birthday}."
