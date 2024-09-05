# Gulbahari-github-clone.md
  # Cloning a GitHub Repo, Creating a Working Branch Locally, and Pushing the Branch to GitHub

## Prompt Used
How do you clone a GitHub repo, create a working branch locally, and then push the working branch to GitHub?

## Steps1. **Clone the GitHub Repository:**
    ```bash
    git clone https://github.com/username/repo.git
    cd repo
    ```

2. **Create a Working Branch Locally:**
    ```bash
    git checkout -b new-branch
    ```

3. **Push the Working Branch to GitHub:**
    ```bash
    git push origin new-branch
    ```

4. **Verify the Branch on GitHub:**
    - Go to your repository on GitHub.
    - Click on the "Branches" dropdown to see your new branch listed.


------Second Prompt (GitHub Desktop)
# Cloning a GitHub Repo, Creating a Working Branch Locally, and Pushing the Branch to GitHub Using GitHub Desktop

## Prompt Used
Show how to do using GitHub Desktop

## Steps

1. **Clone the GitHub Repository:**
    - Open GitHub Desktop.
    - Go to `File` > `Clone Repository`.
    - Select the repository you want to clone and click `Clone`.

2. **Create a Working Branch Locally:**
    - In GitHub Desktop, go to `Branch` > `New Branch`.
    - Enter the name of the new branch and click `Create Branch`.

3. **Push the Working Branch to GitHub:**
    - Click on `Publish branch` in the top bar.

4. **Verify the Branch on GitHub:**
    - Go to your repository on GitHub.
    - Click on the "Branches" dropdown to see your new branch listed.

-----Third Prompt

# Linking a Report in the `/test-reports` Folder to an Issue in GitHub

## Prompt Used
In GitHub...how do you link a report in the `/test-reports` folder of a repo to an issue in the issues tab?

## Steps

1. **Navigate to the Report:**
    - Go to your repository on GitHub.
    - Navigate to the `/test-reports` folder and open the desired report file.

2. **Copy the File URL:**
    - Click on the file to view it.
    - Copy the URL from the browser's address bar.

3. **Link the Report to an Issue:**
    - Go to the `Issues` tab in your repository.
    - Open an existing issue or create a new one.
    - In the issue description or comment, paste the copied URL to link the report.
    - Optionally, use Markdown to format the link:
        ```markdown
        View Report
        ```
 ------Fourth Prompt (Your Choice)

 # Resolving Merge Conflicts in Git

## Prompt Used
How do you resolve merge conflicts in Git?

## Steps

1. **Identify the Conflict:**
    - When you try to merge branches, Git will notify you of conflicts.
    - Use `git status` to see which files have conflicts.

2. **Open the Conflicted Files:**
    - Open the files with conflicts in your text editor.
    - Look for conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`).

3. **Resolve the Conflicts:**
    - Edit the file to resolve the conflicts between the two sets of changes.
    - Remove the conflict markers after resolving.

4. **Add the Resolved Files:**
    ```bash
    git add <file>
    ```

5. **Commit the Merge:**
    ```bash
    git commit
    ```

6. **Continue with Your Workflow:**
    - Push the changes to the remote repository if needed.
    ```bash
    git push origin <branch>
    ```
