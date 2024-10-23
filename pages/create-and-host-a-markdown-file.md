# Create and Host Markdown Files on GitHub or Codeberg for Docsify-This

For version control (the ability to reverse changes) and potential collaboration, both GitHub and Codeberg are excellent choices for hosting raw Markdown files for [Docsify&#8288;&#8211;&#8288;This](https://docsify-this.net). Below is a step-by-step guide to help you get started with either platform.

_Please note the following external links will open in a new Browser tab, so you can keep this guide open for reference!_

## Step 1: Create a New Repository

1. **Log in** or **Sign up** to [GitHub](https://github.com ':target=_blank') (recommended) or [Codeberg](https://codeberg.org ':target=_blank')
2. **Create a new repository**:
   - Tap the upper-right **+** icon and select **New Repository**
   - Fill in the repository details:
     - Enter a **repository name** for your repository (e.g., `docsify-this-demo`)
     - Confirm that the **Visibility** is **Public**
   - Tap **Create Repository**

## Step 2: Create a New Markdown File

1. Viewing your newly created repository, tap the **creating a new file** link (GitHub) or **New file** button (Codeberg)
2. Enter the **name of your file** and use the `.md` extension (e.g., `demo.md`)
3. Enter your **Markdown content**, such as:
   ```markdown
   # Welcome!
   This is an example of a Markdown file with various elements including headers, paragraphs, links, lists and images.
   
   ## Example Link
   Here’s a link to [Docsify-This](https://docsify-this.net) that allows you to easily publish Markdown files as web pages.

   ## Example Lists
   Markdown supports both ordered and unordered lists. Here is an example of each
   
   ### Unordered List:
   - Item one
   - Item two
     - Sub-item
   - Item three
   
   ### Ordered List:
   1. First step
   2. Second step
      1. Sub-step
   3. Third step

   ## Example Image
   And here is an image of Saturn from the James Webb Space Telescope (JWST):  
   ![JWST Image of Saturn](https://stsci-opo.org/STScI-01H41MM35F0QJZ1FRC1TX9MZVE.png)
   ```
  > **TIP:** If you are using GitHub, tap on the **Preview** toggle to view your Markdown as formatted content

## Step 3: Commit the Changes

1. **Commit your file**:
   - Provide a **Commit Message** (e.g., "Create demo.md") if needed to better describe the changes you’ve made
   - Tap the **Commit Changes** button

## Step 4: Verify the File and Publish it with Docsify-This

1. In your repository, **view the file** to see the rendered Markdown
2. **Copy the file URL** from your Browser’s address bar
3. **Go to [Docsify-This.net](https://docsify-this.net ':target=_blank')** and paste the copied URL into the **Markdown File URL** field
4. Tap the **Publish as a Web Page** button to view your Markdown file rendered as a web page using Docsify-This

_Keep in mind that as you make subsequent edits to the file, it may take GitHub and Codeberg a few moments to update the online raw Markdown file used by Docsify-This to display that file._

---

## Docsify-This Markdown Page Templates
The following are example Markdown templates which can be cloned/forked on GitHub or imported into Codeberg.

- [One Page Article Template](https://github.com/hibbitts-design/docsify-this-one-page-article ':target=_blank')
- [One Page Course Template](https://github.com/hibbitts-design/docsify-this-one-page-course ':target=_blank')
- [Multiple Page Course Site Template](https://github.com/hibbitts-design/docsify-this-multiple-page-course-site ':target=_blank')
- [Multiple Page Open Publishing Site Template](https://github.com/hibbitts-design/docsify-this-multiple-page-open-publishing-site ':target=_blank')
- [LMS Content Pages Template](https://github.com/hibbitts-design/docsify-this-lms-content-pages ':target=_blank')

To use these templates on GitHub:

1. Tap **Use this template** (top-right green button) in the selected template repository, then choose **Create a new repository**
2. Name your repository and tap **Create repository** to copy the template files
3. Open the **home.md** file in your new repository and copy its URL
4. Visit [Docsify-This.net](https://docsify-this.net), paste the URL into the **Markdown File URL** field
5. Select your page options (e.g., Docsify Sidebar), and tap **Publish as a Web Page** to generate your web page for sharing or embedding

Once the template files are in your GitHub account, you can modify them to suit your specific needs.  

---

## Editing Files on the Desktop

Since both GitHub and Codeberg are online [Git services](https://www.w3schools.com/git/git_intro.asp ':target=_blank'), you can use desktop software like GitHub Desktop to sync your content to your local desktop. Syncing files locally enables easier file management, faster editing, and the flexibility to work on your content offline.

### Setting up GitHub Desktop

1. Install [GitHub Desktop](https://desktop.github.com ':target=_blank')
2. Enter your GitHub credentials as prompted
3. Go to a GitHub repository web page, tap **< > Code** and then choose **Open with GitHub Desktop** OR go to a Codeberg repository web page, copy the HTTPS address, then in GitHub Desktop choose **File > Clone Repository** and paste the copied URL
4. Choose the location for your cloned repository and tap the **Clone** button

### Desktop Text Editors

Once your Docsify-This Markdown files are synced (i.e. cloned) to your desktop via GitHub Desktop you can then use the text editor of your choice, such as [VSCode](https://code.visualstudio.com ':target=_blank'), [VSCodium](https://vscodium.com/ ':target=_blank') (Free/Libre Open Source version of VS Code), [Pulsar](https://pulsar-edit.dev ':target=_blank') (was Atom.io), [Typora](https://typora.io/ ':target=_blank') etc.

Using GitHub Desktop you can preview any changes and then commit those changes back to the repository. VSCode and VSCodium can also be used independently for both syncing and editing files.

---

## Supporting Resources

### Articles and Guides

- Basic Syntax | Markdown Guide
  - [markdownguide.org/basic-syntax](https://www.markdownguide.org/basic-syntax ':target=_blank')
- Improving The Accessibility Of Your Markdown
  - [smashingmagazine.com/2021/09/improving-accessibility-of-markdown](https://www.smashingmagazine.com/2021/09/improving-accessibility-of-markdown ':target=_blak')
- OER on GitHub What, Why, & How
  - [evanwill.github.io/make-oer](https://evanwill.github.io/make-oer ':target=_blank')

### Desktop Apps

- Markdown Desktop Editors
  - [code.visualstudio.com](https://code.visualstudio.com ':target=_blank')
  - [vscodium.com](https://vscodium.com/ ':target=_blank')
  - [typora.io](https://typora.io ':target=_blank')
  - [pulsar-edit.dev](https://pulsar-edit.dev ':target=_blank') 
- GitHub Desktop App (can also be used with Codeberg)
  - [desktop.github.com](https://desktop.github.com ':target=_blank')

**Ready to get started?**
Head over to [https://Docsify-This.net](ttps://Docsify-This.net ':target=_blank') and start turning your Markdown files into web pages!

<p xmlns:cc="http://creativecommons.org/ns#" >This work by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://hibbittsdesign.org">Paul Hibbitts</a> is licensed under <a href="https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""></a></p>
