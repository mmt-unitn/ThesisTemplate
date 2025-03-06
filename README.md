# Thesis template

This is a template for writing your thesis with Quarto and R. Head on <https://mmt-unitn.github.io/ThesisTemplate/> to 
have a look at the rendered version of this template in HTML format.

## How-to

You will need a GitHub account. Once you have it, proceed as follows:

1. go to <https://github.com/mmt-unitn/ThesisTemplate>
2. click on the green button "Use this template" (top right) and select "Create a new repository"
3. give a name to your repository, provide a description, and make it public or private (depending on your specific case)
4. clone **your new repository** on your computer
5. open the `ThesisTemplate.Rproj` file with RStudio
6. have fun

## Structure

The template already provides a basic structure for your thesis. 
You can modify it as you like, according to your specific case and to your tutor's instructions.

## How to generate the PDF

From RStudio embedded terminal, type:

```bash
quarto render --to pdf
```

The output will be in the `_book` folder.

During the development, it is faster to use the command:

```bash
quarto preview
```

which provides a live HTML preview of your thesis in a browser.
