# README Cheatsheet
## To Do
- create Data Analysis Project Template Jupyter Notebook file based on outline below


## Data Analysis Initial Project Setup Checklist
- decide on project idea
- Create Jupyter Notebook file from template
- import libraries
- gather data sets
- API application if necessary
- add `README.md` from template
- add `LICENSE.txt` from file


## Data Analysis Project Outline
- Title
	- name
	- table of contents
	- overview
	- import libraries, gather datasets, and initial exploration
- Date Wrangling
	- Quality
		- completeness
		- validity
		- accuracy
		- consistency
	- Tidiness
		- column headers are variable names, not values
		- only one variable is stored in each column
		- variables stored only in columns or rows, not both
		- only one type of observational unit stored in the table
		- don't put one observational unit in multiple tables
- Data Cleaning (Issue, Define, Code, Test)
	- list issues
	- copy dataframes
	- address completeness issues
	- address tidiness issues
	- address remaining quality issues
	- store dataframes
	- finalize dataframes
- Analysis
	- initial exploration
	- univariate analysis and visualizations
	- bivariate analysis and visualizations
	- multivariate analysis and visualizations
	- statistical analysis
- Conclusion
	- explanatory visualizations
	- conclusion
	- limitations

## Commit Cheatsheet
### format:
```
type: subject
body
footer
```

### types:
- `feat` - new feature <br>
- `fix` - bug fix <br>
- `docs` - changes to documentation <br>
- `style` - formatting, no code change <br>
- `refactor` - restructuring code <br>
- `test` - adding tests, no output change <br>
- `chore` - other <br>

## Markdown Cheatsheet
**bold** <br>
_italics_ <br>
`inline code` <br>
# H1 title
###### H6 title
~~strikethrough~~
>quote
```
block of code
```
[text that's a link](https://www.google.com/) <br>
[text to a relative link](docs/CONTRIBUTING.md)
- an unordered list
  - nested list
* another unordered list
  - nested list
  * nested list
1. ordered list
   - nested list
     - nested list

[ ] empty item in task list <br>
[x] checked item in task list

## README Template

# :clipboard: Project Title -  [![Binder](https://mybinder.org/badge_logo.svg)](https://www.google.com)
Project Title is a template for a data science project README. The 'what' of the project is concisely described here. 

## Table of Contents
- [Overview](#overview)
- [Requirements](#requirements) 
- [Features](#features)
- [Issues](#issues) 
- [Contribute](#contribute) 
- [Credits](#credits)
- [Contact](#contact)
- [License](#license)


## Overview
This is a more detailed description of Project Title. Go further here in explaining the purpose and process behind the creation of this project. Discuss the programs, APIs, libraries, and data sets used. Describe the structure of the data sets as well. With that context, go into the broader 'why' of the project. Then finally explain the project's current status and maintenance. 

## Requirements
_programs, APIs, libraries, files needed to run project and mention binder badge_
List all programs, APIs, and non-csv files used in this project.

This code depends on the following libraries:
1.`pandas`
2.`numpy`
3.`matplotlib.pyplot`
4.`seaborn`

In addition to these, the Jupyter Notebook assumes that the data set from it's source has been downloaded, extracted, and saved as `name_of_data_file.csv`.

The Binder badge above can be used to explore an executable environment for this project. Note that this template badge links to the Google homepage.
## Features
Here is where a more comprehensive summary of the findings of the project go. First reiterate 'what' the project does, then go into detail about 'how' it does that.
```
include code samples when relevant
```
![alt text]("Annotation%202020-01-07%20105829.png?raw=true" "Also include screen snips, with alt text and optional titles")

Finally, complete this section with another, more contextualized explanation of the broader 'why' of the project, as well as limitations and further possibilities for it.

## Issues

- this is a list of issues
- and bugs in the project
- as well as a to-do list
- for what needs to be done
- and what steps need to be taken

## Contribute
Any bugs, requests, feedback, pull requests etc. are welcome! For any major changes, please open an issue first to discuss your ideas.

## Credits
- here's where any people who have contributed to this project are mentioned
- as well as any other sources which deserve credit

## Contact
You can get in touch with me on LinkedIn [![LinkedIn Link](https://img.shields.io/badge/Connect-deepaksithu-blue.svg?logo=linkedin&longCache=true&style=social&label=Connect
)](https://www.linkedin.com/in/deepaksithu) <br>
give me that choice follow on Github      ![GitHub followers](https://img.shields.io/github/followers/deepaksithu?style=social)<br>
or email me at deepaksithu@gmail.com.

## License
This project uses the [MIT](https://choosealicense.com/licenses/mit/) license. 
