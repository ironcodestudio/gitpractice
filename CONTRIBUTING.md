Contributing
============

Thank you for your interest in contributing.  Not all open source projects
using Git are organized and accept pull requets in exactly the same way.
These are the guidelines followed for this project and are common to many
projects managed via Git.

Open An Issue
-------------

Please [open an issue](../../issues) before
submitting your Pull Request.  An issue provides a place for discussion
about the problem.  Sometimes a clarification or discussion of the problem
significantly impacts how it is fixed (or if it is fixed at all), making this
a valuable step in the process.

__A Pull Request submitted without an issue will not be accepted.__

Branches
--------

All Pull Requests should be made against the `develop` branch from your own
branch created specifically for the pull request.  Common names for pull
request branches are all lowercase keywords separated by dashes and
ending with the issue number,
e.g. "fix-mispell-apple-32".

Follow Code Conventions and Standards of the Project
----------------------------------------------------

Ideally, a project includes code standards to help contributors maintain a
consistent approach throughout.  Even in the presence of strong code standards,
individual code decisions can cause code to vary wildly.  Your code should be
as similar to existing code as project.

    The code for a project should feel like it was created by a single developer.

If the project includes an [.editorconfig](http://editorconfig.org/) file,
those values should be respected in your Pull Request.

Commit Messages
---------------

Good commit messages are an important part of an open source project.  This
project requires a multiline commit message (no using `git -m "message"):

- the first line must be 50 characters or less
- the first line must start with a capital letter
- the first line must be written in the imperative tense,
e.g. Fix misspelling of apple (not "Fixes" or "Fixed")
- the second line should be blank
- starting on the third line you can include an optional detailed description
consisting of multiple lines, each line should be no more than 72 characters
followed by a line break
- after the optional detailed description a line should be skipped
- the final line should indicate the issue addressed by this Pull Request
and use the
[GitHub format to automatically close the issue](https://help.github.com/articles/closing-issues-via-commit-messages/)
(e.g. "Fix #32")

### Example Commit Message

```
Fix misspelling of apple

Fix #32
```

or a more verbose version

```
Fix misspelling of apple

The word apple includes an unnecessary "zz" at the beginning of the word.

Fix #32
```


