# Design Idea

+ **comments** : Don't explain why you wrote it, the algorithm you use. Just tell how to use the things and example
+ Good code is just like a good joke: It needs no explanation.
+ **name**: Camels for Classes, Snakes Everywhere Else. `ALL_UPPERCASE` favor of constant.
+ **parenthese**: in most cases, still use parenthese though it is optical. But there are some exceptions:
    1. empty arguments list
    2. condition in control
+ one statement per line, though you can use `;` to fold them up.
+ **code blocks**: single statement, fold whole in single line with braces; multiple statement, spread block over a number of lines, use do/end form.
```
10.times { |n| puts "The number is #{n}" }

10.times do |n|
   puts "The number is #{n}"
   puts "Twice the number is #{n*2}"
end
```