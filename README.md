# GitHub Docs Example
This is a part of Andrew Brown's Terratown Project

## Step 1 - Using Codeblocks. 

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, and share** code. 
A good __Cloud Engineer__ uses Codeblocks whenever possible. 

Because it allows others to copy and paste their code to replicate or research issues. 

- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with single quotation (')
```

function calculateSquare(number) {
  return number * number;
}

// Example usage:
const num = 5;
const square = calculateSquare(num);
console.log(`The square of ${num} is ${square}`);

```

- When you can you should attempt to apply syntax highlighting to your codeblocks
```js

function calculateSquare(number) {
  return number * number;
}

// Example usage:
const num = 5;
const square = calculateSquare(num);
console.log(`The square of ${num} is ${square}`);

```

- Make note of where the backtick keyboard key is located.
- It should appear above the tab key but it may vary based on your keyboard layout.
<img width="225" src="https://github.com/isteak-z/github-docs-example/assets/67278219/b02ce45e-a67a-4bbd-9b35-fee805194de9"/>

Good Cloud Engineers use codeblocks for both Code and Error that appear in the console. 
```bash

#!/bin/bash

echo "This is a normal message."
echo "Another normal message."
non_existent_command
echo "This message will not be reached."

```
> Here is an example of using a codeblock for an error that appears in bash.

## Step 1 - How to take screenshots

A screenshot is when you capture a part of you screen from your laptop, desktop or phone.

This is not to be confused with taking a photo with your phone.

![a photo with your phone](assets/phone-photo.jpg)

## Step 3 - Use GitHub Flavoured Task Lists

GitHub extends Markdown to have a list where you can check off items. [<sup>[1]</sup>](#external-references)


- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

## Step 4 - Use Emojis (Optional)

GitHub Flavoured Markdown (GFM) supports emojis shortcodes.
Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:`	| :cloud: |
| Cloud with lightning | `:cloud_with_lightning:`	| :cloud_with_lightning: |

## Step 5 - How to create a table

You can use the following markdown format to create tables:

```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:`	| ☁️: |
| Cloud with lightning | `:cloud_with_lightning:`	| 🌩️: |
```
GitHub extends the functionality of Markdown tables to provide more alignment and table cell formatting options. [<sup>[2]</sup>](#external-references)

- Make note of where the pipe keyboard key is located.
- It should appear above the return or enter key but it may vary based on your keyboard layout.

![Photo of pipe character on our keyboard](assets/pipe-key.jpg)

## External References
- [Referencing Issues & Pull Requests] (GitHub Flavoured Markdown) https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#referencing-issues-and-pull-requests 
- [Referencing External Resources] (GitHub Flavoured Markdown) https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#referencing-external-resources
- [GFM - Task Lists] https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists <sup>[1]</sup>
- [GFM - Emoji CheatSheet] https://github.com/ikatyang/emoji-cheat-sheet
- [GFM - Tables (with extensiom)] https://github.github.com/gfm/#tables-extension- <sup>[2]</sup>








