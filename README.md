# Hi, Welcome to my Perl doc :)

### In this repo I will be covering the main stuff in perl (like arrays, hashs, variables etc) and ofc other stuff also!

# Variables!

+ #### In perl we can't just write the variable name and assign a value to it instead there is a special character which tells perl that "hey this is a variable".

+ #### In perl whilst defining a variable you need to use `$` ( also known as a dollar sign ) before defining it.

__Usage__:
```perl
$age = 17; # Integer
$name = "Nick"; # String
$Salary = 1445.50; # Float
```

# Arrays!

+ #### Like Variables, Arrays in perl also have a special character before them, which is `@` ( also known as "at" ), the `@` looks more like a small "a" so you can remember it like `@` for array.

__Usage__:
```perl
@MyNumbersArray = (1, 2, 3, 4);
@MyNamesArray = ("Nick", "Lesli");
```

# Hashes and What are they?

+ #### A Hash is basically a set of `key` and `value` pair, like Variables and Arrays `%` ( also known as a percent sign ) defines a Hash.

__Usage__:
```perl
%data = ("John Paul", 20, "Lisa", 21);
```
**OR**, to make it look more clear:
```perl
%data = ("John Paul" => 20, "Lisa"=> 21);
```
Theres one more way I would like to show you but know that you can not use spaces if you're using hashes like this:
```perl
%data = (-JohnPaul => 20, -Lisa => 21);
```