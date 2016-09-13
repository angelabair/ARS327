# Workflow

- When you begin work on a task, branch off of `master` (or, if applicable, some other branch in progress).
  - Do so with `git checkout -b branchname`.
  - Prefix your branch names with some variation of your name or initials and a slash (I personally use `jtg/`).
- When you're ready to show your work to the rest of us, file a pull request.  Don't merge it yet!
- You can pick and choose individual lines to commit.  **Do so.**  It makes your diffs easier to read and reduces the chances of merge conflicts.
- You don't need to fork this repo, you can make pull requests from within it.
- If you're making changes to someone else's branch, branch off of *that* one instead of committing directly to it.
- Once @JesseTG signs off, merge the branch.
  - Then, on your local copy, check out `master` with `git checkout master`, then update with `git pull`.
  - You can then delete your local copy of that branch with `git branch -D branchname`.
- Do not commit directly to `master`.
  - *Do not commit directly to `master`.*
    - **Do not commit directly to `master`.**
- When possible, try to close an issue inside the commit description (by writing "Fix #<issue number>" somewhere).
- Open issues liberally.

# Code Conventions

- *All* indentation shall be done with two spaces, with a max line length of 80 characters.
- All styles will be in Sass (which is a superset of CSS, so you don't have to use Sass features if you don't know them).
- Variable names shall be in `camelCase`.
- HTML/CSS ID and class names will `be-in-slug-case`.
- Prefer CSS to JavaScript when possible.
  - It's often simpler and more performant.
- Load libraries from a CDN (like [cdnjs](https://cdnjs.com/)), unless there's a good reason you shouldn't (e.g. for customized Modernizr builds).
- If a page's content is mostly text, write it in Markdown (with the occasional inline HTML as needed).
- If you write code that looks even the slightest bit weird, *comment it*.
- If you grab code snippets from elsewhere (e.g. StackOverflow), **cite it.**

# Tools

- Use whatever editor you want, but don't commit project files.  In fact, add them to `.gitignore` if they're not already there.
- Use whatever Git client you want *as long as you know how to pick individual lines to commit.*
  - Know how to pull up and use Git commands from the terminal, though.  Just in case.
- Install `jekyll` and run the site locally with `jekyll serve -w`.
- Use either Slack or the [Wiki](https://github.com/angelabair/ARS327/wiki) for notes.

# Other

- Don't be afraid to ask for help!
- If something doesn't sit right with you, speak up!
