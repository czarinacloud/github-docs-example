# Github Docs Example

# Writting Good Documentation 

## Step 1 - Using Codeblocks
Code blocks in markdown make it *very* easy for tech people to copy, paste, share code. A good **Cloud Engineer** uses __Codeblocks__ whenever possible. 
Because it allows others to copy and paste their code to replicate or research issues. 



```
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number to calculate its factorial:"
number = gets.chomp.to_i

if number < 0
  puts "Factorial is not defined for negative numbers."
else
  result = factorial(number)
  puts "The factorial of #{number} is #{result}."
end
```

```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number to calculate its factorial:"
number = gets.chomp.to_i

if number < 0
  puts "Factorial is not defined for negative numbers."
else
  result = factorial(number)
  puts "The factorial of #{number} is #{result}."
end
```
