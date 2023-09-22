# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good _Cloud Engineer_ uses Codeblocks whenever possible.

Because it allows others to copy and paste, their codes to replicate or research issues.


- Inorder to create Codeblocks in markdown you need to use three backticks ( ` )
- Not to be confused with qutations ( ' )

```
from flask import Flask

# Create a Flask web application
app = Flask(__name__)

# Define a route for the home page
@app.route('/')
def hello_world():
    return 'Hello, World! This is my Python web app.'

if __name__ == '__main__':
    # Run the web application
    app.run()
```

- When you can you should attempt to apply syntax highlighting to your Codeblocks.

```py
from flask import Flask

# Create a Flask web application
app = Flask(__name__)

# Define a route for the home page
@app.route('/')
def hello_world():
    return 'Hello, World! This is my Python web app.'

if __name__ == '__main__':
    # Run the web application
    app.run()
```

-Make note of where the backtick key is.
![backtick](https://github.com/Brian-dotcom-stack/github-docs-example/assets/118678353/0b86e400-4769-482e-aa6d-6723cc8ba8ea)

<img width="200" src = "https://github.com/Brian-dotcom-stack/github-docs-example/assets/118678353/0b86e400-4769-482e-aa6d-6723cc8ba8ea" />

-Good Cloud Engineers use Codeblocks for both code and Errors that appear in the console.

```bash

bash: command not found: some_command
```
>Here is an example of using a codeblock for an error that appears in bash.

## Step 3 - Use Gthub Flavoured Tas Lst

Github extends mardown to have a list where you can chec off tems. <sup>[1]</sup>

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

# Step 4 - Use Emojis (Optional)

GFM  supports emoj shortcodes.
-Here are some examples.

```md
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with rain | `:cloud_with_rain:` | 🌧️ |
```

## Step 5 - How to Create a table

You can use the following markdown format to creaate tables:

```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | : cloud : | :cloud: |
| Cloud with lightning | : cloud_with_lightning : | 🌩️ |
```
Github extends the functionality of markdown tables to provide more alignment and table cell formatting options. [<sup>[2]</sup>](#external-references)


![pipe character](https://github.com/Brian-dotcom-stack/github-docs-example/assets/118678353/29c4682c-c1e0-498e-8363-89d10417346b)


## External References

- [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#images) 
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)<sup>[2]</sup>
- [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>
- [GFM - Emoji CheatSheet]([URL](https://github.com/ikatyang/emoji-cheat-sheet#smileys--emotion)https://github.com/ikatyang/emoji-cheat-sheet#smileys--emotion)
- [GFM - Tables with Extensions](https://github.github.com/gfm/#tables-extension-)  <sup>[2]</sup>



