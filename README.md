# **[dimi-lab.github.io](https://dimi-lab.github.io)** 🚀
This is the source code to generate the webpages for our lab.

# How to make updates
This website is built with _[Lab Website Template.](https://greene-lab.gitbook.io/lab-website-template-docs)_
The official website has a tutorial **[Here](https://greene-lab.gitbook.io/lab-website-template-docs/getting-started/change-your-site)** to show you how to make changes to the content.
Basically, you need to [set up an environment](https://greene-lab.gitbook.io/lab-website-template-docs/getting-started/preview-your-site#on-your-computer-locally) (Mac is recommended), and then follow these steps:
1. Clone this repo to your computer and switch to the appropriate branch.
2. Edit the cloned site on your computer with your favorite text/code editor.
3. Commit and push the changes.
4. The owner of this repo will review and merge your updates, then build and deploy the updated version.
Below is how you can modify specific subpages

## Update Main page
Follow the examples within this file
```
./dimi-lab.github.io/index.md
```
## Update Research
Follow the examples within this folder
```
./dimi-lab.github.io/research
```
## Update Projects
Follow the examples within this file
```
./dimi-lab.github.io/_data/projects.yaml
```
## Update Team
Follow the examples within this folder
```
./dimi-lab.github.io/_members
```
## Update News
Follow the examples within this folder
```
./dimi-lab.github.io/_posts
```
## Update Contact
Follow the examples within this file
```
./dimi-lab.github.io/contact/index.md
```
## Other details
### Add your publications to the list
The publication list is shown in **Main** and **Research** page.
The easiest way to add your publications to the publication list is to add your ORCID to this .yaml file,
```
./dimi-lab.github.io/_data/orcid.yaml
```
The GitHub Pages bot will automatically fetch your publications online and add to "_data/citations.yaml". 
Please note, don't edit this "citations.yaml" directly. It will be refreshed biweekly.

If you are interested in how this happens, please read python code in "./dimi-lab.github.io/_cite".

### Modify some CSS style (advanced user only)
The CSS style is defined in this folder
```
./dimi-lab.github.io/_styles
```
To locate which line in which file you should modify, you may need to switch Chrome to development mode to check which CSS style is taking effect.

# Acknowledgement
The website is built with _[Lab Website Template](https://greene-lab.gitbook.io/lab-website-template-docs)_

