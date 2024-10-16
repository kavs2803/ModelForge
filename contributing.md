# ENTER MODELFORGE

Ready to make some magic happen with ModelForge? Whether it's your first time forking a repo or you're a seasoned coder, we're excited to have you here! This doc will help you join the action. But first, grab some snacks, maybe a bunsamosa (:p), and let’s lay down some ground rules.

## What is This? 🛠️

This is ModelForge—our low-code ML framework designed to make model-building as smooth as butter. Your contributions are going to make it even cooler, and hacknights are the perfect time to bring in fresh energy, and here's how you can get started:


## Ground Rules Before the Fun Begins 🧑‍💻

1. **Fork it! Clone it!**  
   Fork the repo, clone your copy, and fire up your text editor of choice (we recommend VS Code, but you do you!).

   ```bash
   git clone https://github.com/yourusername/ModelForge.git
   ```

2.Keep your forks synced with the main repo. You don't want to be stuck in a merge-conflict meltdown later. 🎭
```bash
git fetch upstream
git merge upstream/main
```

3.Create a virtual environment, run the following command after cloning the repo
```bash
python -m venv venv
```

4.Activate the virtual environment

- Windows:
  ```bash
  venv\Scripts\activate
  ```
- MacOS:
  ```bash
    source venv/bin/activate
   ```

5.Install required python packages [Make sure virtual environment is running]

```bash
pip install -r requirements.txt
```


6.Create Cool Stuff—But Keep it in a Branch! 🌱
Hack away in a new branch. Create one for each feature, bugfix, or improvement.
```bash
git checkout -b my-awesome-feature
```

7. Make Your Changes
Now, solve the issue! Make your changes in the codebase, implement the fix, feature, or improvement.

7. Stage Your Changes
After making your changes, you'll need to stage them for committing.

```bash
Copy code
git add .
```
8. Commit Your Changes
Once your changes are staged, commit them with a descriptive message that references the issue you're solving.

```bash
git commit -m "Fixes issue #1:added dropdown"
```
9. Push Your Branch to GitHub
Now, push your branch to your fork on GitHub.
```bash
git push origin issue-<issue-number>-fix-description
```
For example:

```bash
git push origin issue-1-fix-dropdown
```
10. Open a Pull Request (PR)
Go to your GitHub repository in your browser.
Click on the Pull Requests tab.
Click New Pull Request.
Choose your branch (named issue-<issue-number>-fix-description).
Click Create Pull Request to submit it.



To run the file

```bash
 python main.py <filename>.yaml
```

