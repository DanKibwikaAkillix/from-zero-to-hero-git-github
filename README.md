# From zero to hero with git, GitHub, and remote development environments

## Outline

### 1. Getting started with GitHub

- Go to https://github.com/
- Click "Sign up for GitHub"
- Follow the steps

**Done when**: You can navigate to your GitHub profile at `https://github.com/<your-username>`

### 2. Our first repository

- Go to https://github.com/, find the "+" button on the top-right, click "New repository"
    - Alternatively, go to https://github.com/new
- When asked, use your username as the repository name
    - 👀 You should see a blue sign starting with _"[...] is a ✨special ✨ repository that you can use to add a README.md"_
- Enable "Add README"
- Click "Create repository"

**Done when**: Your GitHub profile shows the contents of your personal README at the top
(use the URL from the previous step)

### 3. Get started with Firebase Studio

> [!WARNING]
> This assumes you have a Google account. If you don't, go to https://accounts.google.com/ to get a **personal** one.

- Go to https://firebase.studio/
- Click "Try Firebase Studio"
- Log in with your Google account, and accept the terms of service
- Click the "Import Repo" button at the bottom
- Paste your GitHub profile URL from step 1
- Use "personal-readme" for the workspace name
- Wait for the workspace to be set up

**Simple workflow**:

- Open your `README.md`
- Make a small edit
- Open the "Source Control" panel on the left
    - 👀 You should see README.md under "Changes" on the top left, with a blue "M" mark
- Type "Update README" in the "Message" box
- Click "Commit", and when the dialog says "There are no staged changes to commit", click "Yes"
- Click "Sync Changes", and when the dialog says "This action will pull and push commits from and to "origin/main"", click "Yes"
- When the dialog says "The extension 'GitHub' wants to sign in using GitHub", click "Allow"
- Click "Copy and Continue to GitHub", paste the 8-character code that appeared in the dialog, and click "Continue"
- Click "Authorize Visual-Studio-Code"

**Done when**: Your GitHub profile shows the _updated_ contents of your personal README at the top

**Advanced workflow**:

- Open your `README.md`
- Make a small edit
- Open the hamburger menu on the top-left, View, Terminal
- When the terminal is ready (you should see a line ending with `$`), type `git status`, then hit the Enter/Return key
    - 👀 You should see `modified: README.md` highlighted in **red**
- Type `git add README.md`, hit Enter/Return, and then repeat `git status`
    - 

## Resources

### git

![Triangular workflows](https://github.blog/wp-content/uploads/2015/07/5dcdcae4-354a-11e5-9f82-915914fad4f7.png)

- https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository

### GitHub for Education

- https://github.com/education/
- https://education.github.com/pack/ (includes GitHub Pro!)
- https://docs.github.com/en/education/about-github-education/github-education-for-students/apply-to-github-education-as-a-student
- https://github.com/settings/education/benefits
- https://education.github.com/experiences/foundations_certificate
- https://education.github.com/experiences/primer_codespaces (only for verified students)

### Canonical

- Ubuntu Community https://ubuntu.com/community
- Canonical Academy https://canonical.com/academy
