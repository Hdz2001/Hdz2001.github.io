# Applying Etter's Modern Technical Writing principles to host an online resume and README

## Table of Content
- [Purpose](#purpose)
- [Prerequisites](#prerequisites)
- [Instructions](#instructions)
- [More Resources](#more-resources)
- [Author and Acknowledgements](#author-and-acknowledgements)
- [FAQ](#faq)

## Purpose 

- **The purpose of this document** is to help users understand about how to host documents on a public repository, such as GitHub Pages. In this case, the document will shows how to create your resume and host it on your website utilizing the techniques outlined in Andrew Etter's book, Modern Technical Writing. 
- **Essential tools:** Markdown, a Markdown editor, a static site generator (such as Jekyll), and either GitHub Pages or Codeberg Pages for hosting.
  - **The tutorial will perform using Markdown, Jekyll and Github Pages hosting.**


## Prerequisites
- **Required:**
  - Have a GitHub account, with GitHub account, you can have access to GitHub pages for hosting.
    - If you don't have one, you will need to [create a GitHub account](#more-resources).
  - A general understanding of Git, Version Control and Markdown. 
    - **What is Git and Version Control and why understanding them important?** 
        - Git is a common distributed version control system designed to track changes in files, enabling collaboration among developers working on software projects.
        - Version control is one of the core principles from Modern Technical Writing. It is a mechanism that tracks modifications to a file or group of files across time, enabling you to keep track of your changes and retrieve specific versions later on. 
    - **What is Markdown and why understanding it important?**
        - Markdown is one of Lightweight Markup mentioned in Modern Technical Writing, along with reStructuredText, AsciiDoc and LaTeX. It is the most commonly utilized lightweight markup language globally and allows users to easily add formatting elements such as headers, lists, bold and italic text, links, and images using simple and intuitive syntax. Markdown is often used for writing content for websites, blogs, documentation, and README files on platforms like GitHub, Reddit, and Stack Overflow. It provides a convenient way to write structured content without the need for complex HTML tags or formatting tools.

- **Recommended**:
  - Markdown editor: 
    - A Markdown editor will help enhancing your work speed and allow more customization to your Markdown file.
- For more readings and resources about above topics, you can navigate to the [More Resources](#more-resources) section.

## Instructions
Here are the step-by-step instruction of hosting your resume using GitHub pages: 

1. **Create your repository for hosting:**
   1. After succesfully created your GitHub account, login to your account.
   2. You can either: 
      1. Click the "+" button and choose "New Repository" 
      
            ![CreateNewRep_Method1](https://github.com/Hdz2001/Hdz2001.github.io/blob/main/image/CreateNewRep_Method1.png?raw=true) 

      2. Click the green "New" button
      
            ![CreateNewRep_Method2](https://github.com/Hdz2001/Hdz2001.github.io/blob/main/image/CreateNewRep_Method2.png?raw=true) 

   3. After that, you will be redirected to the page below. Enter the name of the repository `[YourUserName].github.io` into the input box then click green "Create Repository" button.    

        ![NameYourRep](https://github.com/Hdz2001/Hdz2001.github.io/blob/main/image/NameYourRep.png?raw=true)  

2. **Upload your resume to your repository:**
   1. Click the "uploading an existing file". This will bring you to another window. 
        
        ![UploadExistingFile](https://github.com/Hdz2001/Hdz2001.github.io/blob/main/image/UploadExistingFile.png?raw=true)

   2. Add your file into the box. 
      1. I recommend naming the file as `index.md` on your computer before adding it, because the website will only work if your resume is named `index.md`. 
      2. Moreover, you can write your commit message and extended description to keep track of what changes have been done to the repository. 

            ![UploadExistingFilePopUp](https://github.com/Hdz2001/Hdz2001.github.io/blob/main/image/UploadExistingFilePopUp.png?raw=true)

   3. In case you didn't change your resume file name in the step above, you can change its name by doing: 
      1. Click your resume file. 
      
            ![ClickOnFileResume](https://github.com/Hdz2001/Hdz2001.github.io/blob/main/image/ClickOnFileResume.png?raw=true)

      2. Click the pencil icon to edit the file. 
      
            ![ClickOnFileResume_PencilIcon](https://github.com/Hdz2001/Hdz2001.github.io/blob/main/image/ClickOnFileResume_PencilIcon.png?raw=true)

      3. Rename the file using the input box to `index.md`. 

      4. Click the "Commit change..." button. 
      
            ![RenameAndCommitResumeFile](https://github.com/Hdz2001/Hdz2001.github.io/blob/main/image/RenameAndCommitResumeFile.png?raw=true)

      5. Click the "Commit change" button again. Optionally, enter your commit message. 
      
            ![CommitAgainChangeFileName](https://github.com/Hdz2001/Hdz2001.github.io/blob/main/image/CommitAgainChangeFileName.png?raw=true)

   4. After that, your resume will now be hosted on the website: `[YourUserName].github.io`. Give it some time to finish deploying your website. 

3. **Customize your website theme using Jekyll:**
   1. Create new file on your repository by clicking "Add file" then "Create new file". 
   
        ![CreateNewFileConfig](https://github.com/Hdz2001/Hdz2001.github.io/blob/main/image/CreateNewFileConfig.png?raw=true)

   2. Name your file `_config.yml` in the input box. 

   3. Add into "Enter file contents here" the lines: `remote_theme: pages-themes/cayman@v0.2.0` and `plugins:- jekyll-remote-theme`
      1. This will be the simpliest way to do it. However, you can use other theme and more customization as well. Have a look at [More Resources](#more-resources) section. 

   4. Click "Commit changes..." button. 

        ![CustomizeConfigFile](https://github.com/Hdz2001/Hdz2001.github.io/blob/main/image/CustomizeConfigFile.png?raw=true)

   5. Click the "Commit change" button again. Optionally, enter your commit message. 

        ![CreateConfigFileCommit](https://github.com/Hdz2001/Hdz2001.github.io/blob/main/image/CreateConfigFileCommit.png?raw=true)

4. **After that, your website will be finished and will look like this:** 

![WebPage.gif](https://github.com/Hdz2001/Hdz2001.github.io/blob/main/image/WebPage.gif?raw=true)

## More Resources 
- [Modern Technical Writing by Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
- **GitHub:** 
  - [Create an account](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github)
  - [Get started with your account](https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account) 
- **Markdown:**
  - [Learn about Markdown](https://www.markdownguide.org/getting-started/)
  - [Practice using Markdown](https://www.markdowntutorial.com/)
  - [Recommended Markdown editors](https://www.webfx.com/blog/web-design/online-markdown-editors/) 
- **Jekyll:**
  - [Jekyll templates supported by GitHub Pages](https://pages.github.com/themes/)
  - Advanced Jekyll setup:
    - [Beautiful Jekyll](https://github.com/daattali/beautiful-jekyll)
    - [Jekyll Front Matter Customization](https://jekyllrb.com/docs/front-matter/)
 
## Author and Acknowledgements
- **Author:** Hung Tran
- **Edited and reviewed by:** Ying Liang, Kaiden Bereznycky
- **Jekyll Theme:** Cayman
- I want to thank my COMP3040 instructor, Stewart Wilcox, for giving us the template for this README and giving us clear instructions.

## FAQ
1. **Why is Markdown better than a word processor?**
- **Simplicity:** Markdown uses simple syntax to format text, making it easier to write and read compared to the complex formatting options in word processors.
- **Portability:** Markdown files are plain text files, which means they can be opened and edited with any text editor. This makes Markdown documents highly portable and compatible across different platforms and devices.
- **Focus on Content:** Markdown encourages users to focus on the content rather than formatting, which can enhance productivity and streamline the writing process.
- **Integration with Web Technologies:**
  - Markdown is widely supported by various platforms and tools, including websites, blogging platforms, and documentation frameworks, making it a preferred choice for writing content for the web.
  - Moreover, Markdown files work well with version control systems like Git, allowing users to track changes and collaborate more effectively on documents.

2. **Why is my resume not showing up?**
   1. After uploading all your files, give GitHub some time to deploy your page. Your GitHub repository will look as followed if it's in process of deploying and when it's done. 

        ![PageDeploying](https://github.com/Hdz2001/Hdz2001.github.io/blob/main/image/PageDeploying.png?raw=true) 
        
        ![PageDeployDone](https://github.com/Hdz2001/Hdz2001.github.io/blob/main/image/PageDeployDone.png?raw=true)
   2. If the page still doesn't show after deploying, double-check these values: 
      1. Make sure your GitHub repository name is `[YourUserName].github.io`
      2. Make sure the GitHub website url is `https://[YourUserName].github.io/`
      3. Make sure your resume file name is `index.md`
