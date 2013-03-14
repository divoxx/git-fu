Git Fu
======

Git Fu adds some custom, hopefully useful, git commands. Each command is described in detail below.

open-conflicts
--------------

When in a merge conflict, open all the files with conflicts in your configured editor

```bash
git open-conflicts
```

It uses the editor set in git's config (`core.editor`), falling back to whatver `$EDITOR` is set to.

purge-branches
--------------

Remove all branches that have been merged into master from both local and remote (origin).

```bash
git purge-branches
```