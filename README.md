## Hosting a Markdown-formatted Resume on GitHub Pages

**Purpose:** A step-by-step tutorial on how to host a resume on a static website using Markdown, GitHub Pages, and Jekyll using the ideas from Andrew Etter's book "Modern Technical Writing.".

### Summary
- [Prerequisites](#prerequisites)
- [Instructions](#instructions)
- [More Resources](#more-resources)
- [Authors and Acknowledgements](#authors-and-acknowledgments)
- [FAQ](#faq)


### Prerequisites

#### Markdown-Formatted Resume
In a plain text editor, markdown is a straightforward markup language that may be used to produce stylized content. Markdown was developed by John Gruber and Aaron Swartz in 2004 as a markup language with the intention of enabling anyone to write in a plain text format that is simple to read and write. 

#### Why use Markdown? 
>According to Etter's book Modern Technical Writing, "Lightweight Markup Language" can be helpful and straightforward while developing a website. It has a small learning curve and uses simple syntax. You can also make changes to the file using a standard text editor.


#### GitHub Account
A Github account is necessary to host ypur resume online website. You can use GitHub or Codeburg. I have used Github for my resume.  

#### Jekyll
Jekyll is a static page generator for websites. It uses content written in the markup language and design of your choice to build a static website. The look and feel of the website, as well as the URLs and information presented on the page, are all editable. You can either choose from a variety of themes from  [here](https://pages.github.com/themes/) . To apply a yheme just add a '_config.yml' file containing a straightforward jekyll theme to your repository, as illustrated below and using this [help](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll)

In `_config.yml` 
```
theme: jekyll-theme-architect
```


### Instructions

#### 1. Resume 
Markdown is the most widely used lightweight markup language in the world, and there are a number of software tools that may help you get the most out of it, including: 

>* [Visual Studio Code](https://code.visualstudio.com/)(For Mac os ,Windows and Linux)
>* [Atom](https://atom.en.uptodown.com/windows) (windows)
>* [iA Writer](https://ia.net/writer) (Mac OS)
>* [ReText](https://codepre.com/how-to-install-retext-restructuredtext-editor-in-ubuntu-a-markdown-editor-for-linux.html) (Linux)   

**Notes** 
* If you choose to host your resume on GitHub, please utilise [GitHub Markdown Doc](https://guides.github.com/features/mastering-markdown/). The GitHub infrastructure has been specially considered when creating this version of Markdown. If you want to ensure optimal efficiency and no rendering problems when publishing your resume to GitHub, do not use any other version of Markdown.
* name and save your resume file as `index.md` .

#### 2. GitHub Account 
>In his book " _Modern Technical Writing_" Etter advocates the usage of DVCSs like Git and Mercurial rather than centralised systems. With these systems, offline work is permitted and overall performance is enhanced. A benefit of having all of your work, including documentation, in one location is that the majority of developers use this technology..

#### Installing Git
1. Visit and follow instructions on this [link](https://github.com/git-guides/install-git) for installiing git in your system
<br />


#### Creating an Account 
1. Go to [GitHub](https://github.com/)
2. Select Sign up
3. Enter your email first and then set your password
4. Then enter your username
5. Verify your account from your email address and you are all set

#### Create a New Repository 
1. Go to [GitHub](https://github.com/)
2. Sign in to your account
3. Click on Repositories 
3. Click the New Button - **Green Button on the top left of the screen**
4. Name you repository using the format - *YourUserName*.github.io
5. Then click on Create repository - **Bottom of the screen**

#### Upload your Resume in the repository
After you have created your repository
1. Click "Add file " and it will guve a drop down menu
2. Select "Upload files" from the drop down menu
3. Drag and drop your 'idex.md' file from your computer.
4. You can also select "Choose your files' and it will let you select and upload
    your desired 'idex.md' file from your computer's local directry.
5. Then click on the green "Commit changes" located at the bottom to ulpoad your 'index.md' file.

**Note:** You resume must be named as index.md


#### 3. Hosting your Resume using GitHub Pages
>According to Etter in his book "Modern Technical Writing," static websites are good for documentation since they have no dependencies and are simple to deploy. In addition to allowing you to apply styles to your documentation, known as themes, to make it appear more expert and consistent, GitHub Pages leverages Jekyll to host static content.. 

1. Go to your repository and click on Settings
2. Find the **Pages** section from the sidebar
3. Make sure that the 'main' branch is chosen as source and **Save**

#### Conclusion 
You have completed hosting your resume online on GitHub .

Your resuume will look like something like this when u go to a url using the follwing URL address rule: <br/>
  *YourUserName*.github.io  <br/>
<br/>
![](Resume.gif)



#### More Resources
* [Basic Syntax](https://www.markdownguide.org/basic-syntax)  
* [Markdown Guide](https://www.markdownguide.org/getting-started)
* [Markdown Tutorial](https://www.markdowntutorial.com/lesson/1/)



### Authors and Acknowledgments
This "README.md" was  written by Mahamud hasan Asif Using Markdown and Github pages. Special thanks to :<br/>
[James Le](https://github.com/khanhnamle1994/khanhnamle1994) <br/>
[Saif Mahmud](https://github.com/vmsaif) <br/>

### FAQ

**Why is Markdown better than a Word processor?**
> You can segregate content from style using markdown. By doing this, you can maintain consistency in both your content and writing style without having to think about it.

**Why is my resume not online?**  
> Make sure you have named your resume as 'index.md'

**How do I change a theme?**
> In your '_config.yml' file just write the name of a different theme from [here](https://pages.github.com/themes/). 
