# Writing Good Documentation

## Step 1 - Using Codeblocks

Good cloud engineers will use Codeblocks to make it easy for other engineers to read, copy, paste their code.  

Format codeblocks by using three backticks (`)

Sample Python code

```
class Dog:
    def __init__(self, name, breed):
        self.name = name
        self.breed = breed

    def bark(self):
        print(self.name + " says Woof!")

my_dog = Dog("Buddy", "Golden Retriever")
my_dog.bark()
```

Even better you should use color coding to highlight syntax and make your code easier to read.  Simply include a language spec with your codeblock:

```python
class Dog:
    def __init__(self, name, breed):
        self.name = name
        self.breed = breed

    def bark(self):
        print(self.name + " says Woof!")

my_dog = Dog("Buddy", "Golden Retriever")
my_dog.bark()
```



## Step 2 - Posting Images

![appleiie-small](https://github.com/michaelgraff/github-docs-example/assets/38571586/a684346f-3d95-492d-b054-a3c99c48b0c3)

## Step 3 - Using Github Flavored Markdown Task Lists

GitHub extends Markdown to have a list where you can check off items.<sup>[1]</sup>

- [X] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3

## Step 4 - Using Emojis (optional)

Github Flavored Markdown (GFM) supports emoji shortcodes.<sup>[2]</sup>   Here are some examples.

| Name | Short Code | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Àlarm Clock | `:alarm_clock:` | :alarm_clock: |
| Star | `:star:` | :star: |




## References

- [GFM Spec](https://github.github.com/gfm/)
- [GFM Basic Writing and Formatting Syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- <sup>[1]</sup>[GFM Working with Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)
- <sup>[2]</sup>[Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
  
