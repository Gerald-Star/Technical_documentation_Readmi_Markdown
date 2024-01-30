# 1. Master how to create documentation by creating a Readme.md file on VS Code, load images and best markdown extensions

## 1.1 What is a README.md file? :smile:

README is a documentation file that usually contains a plain text file. It is a documentation directory that contains your project description and information about your project.

README file is commonly created on VS Code and found in the root directory of a software project. The typical filename is always ‘README.md’, or ‘README.txt’ and hosted on Github repository.

The .md in Readme is a file extension for markdown format used to create a lightweight plain-text document.

### 1.1.1 Common Use Cases of README files

- Provides a brief description of a project, the problem the project solves, and aims to achieve.
- Readme file is popularly use to document instructions and guidelines on how to contribute to open-source projects.
- The Readme.md file can be used for onboarding new users and teams in a project, as it serves as a reference and information guide.
- Describes software installation instructions with detailed steps on how to install a set of software and dependencies.
- Provides instructions on how to use new software, updates, syntaxes, or code snippets.
- It can contain links and references for a more detailed documentation for further reading.
- Provides a guideline for software development, changes in tickets, bug fixes, new features and relevant updates.

## 2. How to create Readme.md (Markdown file) on VS Code :slightly_smiling_face:

![Create New File for Readme](/images_markdown/Create_New_file.png)

To view your Readme Markdown after installing the markdown extensions on the images below, right click on your Readme and select *Markdown Readme Enhanced* . This opens your README.md preview on another page.

- Emoji Cheat Sheet :cd:
- How to write markdown syntax :cd:
- How to embed images in markdown :cd:
- How to format code in markdown :cd:
- How to export Readme Markdown into HTML, PDF etc :cd:

### 2.1 Emoji Cheat Sheet link :smile:

<https://www.webfx.com/tools/emoji-cheat-sheet/>

### 2.2 Markdown Extensions

- Download the markdown extensions seen on the pictures below. Mostly, recommended is Matt Briener markdown extensions.

- \*github\* markdown preview by Matt Briener

### 2.2.1 How to write markdown syntax

Markdown syntax is use to display the markdown heading, code and images. Every heading starts with a # symbol, which represents the heading format.

### 2.2.2 Heading levels should only increment by one level at a time <https://www.w3.org/WAI/tutorials/page-structure/headings/>

- One hashtag *#*  displays Heading 1
- Two hashtags *##* displays Heading 2
- Three *###* displays Heading 3
- Four hashtags *####* displays Heading 4
- You can have as many hashtag headings as you want.

### 2.2.4 Unorderd list and ordered list

### 2.2.4.1 Unordered list

Start each line with a - or * character followed by a space. All the child elements here followed an unordered lists rule.

Example

- Microsoft Azure
- Amazon Web Services
- Google
  
### With a star syntax

* Microsoft Azure
* Amazon Web Services
* Google

### 2.2.4.2 Ordered list

You can make a numbered list by starting a new line with a 1.

1. Microsoft Azure
2. Amazon Web Services
3. Google
  
### 2.2.3 These images contains the best VS Code markdown extensions

#### How to add an image on your Readme

- Firstly, import the images on your file.
- Use an exclamation mark in square bracket as written below and declare a an image path.
  -Example stated below:

- '\!['Alternate text](image path)

### 2.2.4 Image Extension

- ![markdown](/images_markdown/Markdown_1.png)
- ![markdown Image](/images_markdown/Markdown_2.png)
- ![markdown Image](/images_markdown/Markdown_3.png)

## 3. To display code using markdown

- You can use backticks ``for single code.

  print`("Hello Bafor ")`

- To display multiply line of code use three backticks
- State the code name after the backticks.

```python
    number = -4

    if number > 0:
    print("Number is positive. ")
    elif number == 0:
    print("Number is zero. ")
    else:
    print("Number is negative. ")
```

# 4 . Export Readme Markdown into HTML or PDF files

Firstly, download the markdown extensions stated on the pictures above. This extensions enables you to control your Readme preview, download as a PDF file, HTML, Pandoc or even as eBook. The markdown extensions controls your Readme documentation page.

To open the Readme preview, right click on the Readme.md file and select *Markdown Preview Enhanced*. This is a markdown extension.

To download as a PDF file or others, right click on the Preview Readme.md, select *Export* then select download of your choice as shown below.

![PDF Markdown](/images_markdown/Export_readme.png)

Summary:
This is how you can create a nicely Readme for your Github to help readers understand your project.

You can find the github repository at: <https://github.com/Gerald-Star/Technical_documentation_Readmi_Markdown.git>
