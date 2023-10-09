# Writing Good Documentation

## Step 1 - Using Codeblocks

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, and share** code. 

A good __Cloud Engineer__ uses codeblocks whenever possible because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown, you need to use three backticks (`).
- Not to be confused with single quotation marks `'`.

```
$Computer = hostname
Invoke-GPUpdate -Computer $Computer
```

- When you can, you should attempt to apply syntax highlighting to codeblocks.


```PowerShell
$Computer = hostname
Invoke-GPUpdate -Computer $Computer
```

## Step 3 - Use Github Flavored Markdown Task Lists

Github extends Markdown to have a list where you can check off items. <sup>[1]</sup>

- [x] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3

## References

- [Github Flavored Markdown Spec](https://github.github.com/gfm/) 
- [Basic writing and formatting syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>
