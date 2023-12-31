# Writing Good Documentation


## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocjs whenever possible.

Because it allows others to copy and paster their code to replicate or research issues.

- In order to create codeblocks in markdown you need to use three backticks ( ` )
- Not to be confised with quotation ( ' )

```
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Example usage:
number = 5
result = factorial(number)
print(f"The factorial of {number} is {result}")
```

- When you can you should attempt to apply syntax highlighting to your code

``` python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Example usage:
number = 5
result = factorial(number)
print(f"The factorial of {number} is {result}")
```
- Make note of where the backtick key is located. 
- It should appear above the tab key.
- It may vary based on your keyboard layout.
  
![backtick](assets/backtick.png)

Good Cloud Engineers use codeblocks for both code and errors that appear in the console
 
```bash
$ python bad_code.py
Traceback (most recent call last):
  File "bad_code.py", line 6, in <module>
    result = divide(numerator, denominator)
  File "bad_code.py", line 2, in divide
    return a / b
ZeroDivisionError: division by zero
```
> Here is an example of using a codeblock for an error that appears in bash

 When you can, always provide a codeblock instead of a screenshot.
 If you need to take a screenshot make sure its not a photo from your phone.

> There are certain cases where its okay to take photos with your phone. THis is when you ar shoing something like a keyboard, which does not apprear on a computer screen.
> If it renders on your computer it should be a screen shot


## Step 2 - How To Take Screenshots

 A screen shot is when you capture a part of your screen from a laptop, desktop, or phone.

 This is not to be confused with taing a photo with your phone.


**DON'T DO THIS**

 ![A photo with your phone](assets/phone.jpg)

**DO THIS INSTEAD**

This is what a screenshot from you computer should look like

 ![A photo with your phone](assets/Screenshot-1.png)
 > Image taking with Flameshot on Linux.



## Step 3 - Use Github Flavored Markdown Task Lists

Github extends Markdown to have a list where you can check off items. [^1]

- [x] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3



## Step 4 - Use Emojis (Optional)

Github Flavored Markdown (GFM) supports emoji short codes.
Here are some examples: [^2]

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lightning| `:cloud_with_lightning:` | 🌩️ |
| Sunglasses | `:sunglasses:` | 😎 |
| Eyes | `:eyes:` | 👀 |
| Guyana | `:guyana:` | 🇬🇾 |



## Step 5 - How To Create A Table

You can use the following markdown format to create tables:

```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lightning| `:cloud_with_lightning:` | 🌩️ |
| Sunglasses | `:sunglasses:` | 😎 |
| Eyes | `:eyes:` | 👀 |
| Guyana | `:guyana:` | 🇬🇾 |
```

Github extends  the functionality of markdown tables to provide more alignment and table cell formattiong options. [^3]

- Make note of where the pipe key is located. 
- It should appear above return/enter key.
- It may vary based on your keyboard layout.

![Photo of the pipe character on a keyboard](assets/pipe.png)

[Secret Window Hidden Garden](secret-window/hidden-garden.md)


## External References

- [Github Flavored Markdown Spec](https://github.github.com/gfm/) 
- [Basic writing and formatting syntax(Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
[^1]: [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)
[^2]: [GFM - Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/tree/master)
[^3]: [GFM - Tables (with extentions)](https://github.github.com/gfm/#tables-extension-) 
