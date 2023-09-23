# Github Docs Example

# Writting Good Documentation 

## Step 1 - Using Codeblocks
Code blocks in markdown make it *very* easy for tech people to **copy, paste, share code**. A good **Cloud Engineer** uses __Codeblocks__ whenever possible. 
Because it allows others to copy and paste their code to replicate or research issues. 

- In order to create codeblocks in markdown you need to use three backticks (`) 
- Not to be confused with quotation (')

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
When you can you should attempt to apply syntax highlighting to your codeblocks

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

- Make note of where the backtick button is located. 
- But it may vary based on your keyboard.
<image width="200px" src= "https://github.com/czarinacloud/github-docs-example/assets/145864613/f4e9561a-739c-4a75-ae61-7916b00fc1c6" />

Good Cloud Engineers use codebloacks for both Code and Errors that appear in the console. 
```bash
# Define a custom error class
class CustomError < StandardError
end

# Raise a custom error with a message
begin
  raise CustomError, "This is a custom error message."
rescue CustomError => e
  puts "Caught a custom error: #{e.message}"
end
```
> Here is an example of using a codeblock for an error that appears in bash.

## Step 3 - Use Github Flavoured Markdown Task Lists 

Github extends Markdown where you have a list where you can check off items <sup>[1]</sup>

## References 
- [Github Flavoured Markdown Spec](https://github.github.com/gfm/) 
- [Basic writing and formatting syntax -(Github flavoured Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-text) 
- [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)<sup>[1]</sup>
  
