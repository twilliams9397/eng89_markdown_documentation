# single hash is used to create heading 1, H1
## double hash is used for heading 2, H2
### triple hash for H3
- dash (-) is used to create a bullet point
 - **to write anything in BOLD use** (** text **)
```python
print("```python ``` is used to write in code, with given language")
```
- `print("for a single line use single mark not triple as above")`
- to add a link/URL use square brackets
[Documentation](https://github.com/twilliams9397/eng89_markdown_documentation)
- to add image use ! and square brackets

![](https://pbs.twimg.com/profile_images/1206603239791218688/0AwZ0m6W_400x400.jpg)
#### To initialise a repo using pycharm:
- `git init`
- to check what is added to send to Github: 
- `git status` to ensure only required files are added to be sent
- to add `git add .` or `git add name_of_file`
- to save changes `git commit -m "logical message explaining what has been added/changed`
- to push changes to Github `git push -u main`
- remote branch must be set to main, if not run `git branch -M main` after commit command
- adding remote to connect localhost with Github repo use repo code from Github e.g.
`git remote add origin git@github.com:twilliams9397/eng89_markdown_documentation.git`, in SSH not HTTPS

**setting branch to -M main and adding remote is only to be done first time**  