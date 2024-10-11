# Create and Host Markdown Files on GitHub or Codeberg for Docsify-This

For version control (the ability to reverse changes) and potential collaboration, both GitHub and Codeberg are excellent choices for hosting raw Markdown files for Docsify-This. Below is a step-by-step guide to help you get started with either platform.

## Step 1: Create a New Repository

1. **Log in** or **Sign up** to [GitHub](https://github.com)(recommended) or [Codeberg](https://codeberg.org)
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

## Step 4: Verify the File and View it with Docsify-This

1. In your repository, **view the file** to see the rendered Markdown
2. **Copy the file URL** from your Browser’s address bar
3. **Go to [Docsify-This.net](https://docsify-this.net)** and paste the copied URL into the **Markdown File URL** field
4. Tap the **Publish as a Web Page** button to view your Markdown file rendered as a web page using Docsify-This

_Please note that as you make subsequent edits to the file, it may take GitHub and Codeberg a few moments to update the online raw Markdown file used by Docsify-This to display that file._

---

## Editing Files on the Desktop

Since both GitHub and Codeberg are online [Git services](https://www.w3schools.com/git/git_intro.asp), you can use desktop software like GitHub Desktop to sync your content to your local desktop. Syncing files locally enables easier file management, faster editing, and the flexibility to work on your content offline.

### Setting up GitHub Desktop

1. Install [GitHub Desktop](https://desktop.github.com)
2. Enter your GitHub credentials as prompted
3. Go to a GitHub repository web page, tap **< > Code** and then choose **Open with GitHub Desktop** OR go to a Codeberg repository web page, copy the HTTPS address, then in GitHub Desktop choose **File > Clone Repository** and paste the copied URL
4. Choose the location for your cloned repository and tap the **Clone** button

### Desktop Text Editors

Once your Docsify-This Markdown files are synced (i.e. cloned) to your desktop via GitHub Desktop you can then use the text editor of your choice, such as [VSCode](https://code.visualstudio.com), [Pulsar](https://pulsar-edit.dev) (was Atom.io), [Typora](https://typora.io/) etc.

Using GitHub Desktop you can preview any changes and then commit those changes back to the repository. VSCode can also be used independently for both syncing and editing files.

---

## Additional Resources

### Articles and Guides

- Basic Syntax | Markdown Guide
  - https://www.markdownguide.org/basic-syntax
- Improving The Accessibility Of Your Markdown
  - https://www.smashingmagazine.com/2021/09/improving-accessibility-of-markdown
- OER on GitHub What, Why, & How
  - https://evanwill.github.io/make-oer

### Desktop Apps

- Markdown Desktop Editors
  - https://code.visualstudio.com/
  - https://typora.io
- GitHub Desktop App (can also be used with Codeberg)
  - https://desktop.github.com

**Ready to get started?**
Head over to https://Docsify-This.net and start turning your Markdown files into web pages!

<p xmlns:cc="http://creativecommons.org/ns#" >This work by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://hibbittsdesign.org">Paul Hibbitts</a> is licensed under <a href="https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""></a></p>
