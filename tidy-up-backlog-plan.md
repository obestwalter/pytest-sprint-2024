We have more than 800 open issues, quite a few of them very old and with no proper follow-up and quite a few might be good first issues, if provided with a bit more context. 

We had a small discussion already with @The-Compiler and @webknjaz - the rough plan is going through issues with these things in mind:

1. If the issue is really old and it is not quick/easily to reproduce it, ask for follow-up and mark with [needs: information](https://github.com/pytest-dev/pytest/labels/status%3A%20needs%20information) - we already have automation that those are auto-closed then after a month
2. if it is easy to reproduce: reproduce it, add a comment that verifies the reproduction and update the original issue comment with that info and a link to the reproducing comment, so that it is clear right away that this might be an old issue but it is still valid
3. If an issue is obviously already solved or invalid, close it right away with the proper explanation
4. If something is not yet labelled properly, add the proper label (D'UH!)
5. If something looks like a good first issue, add the label (and maybe add a bit more context for people to get started)
6. Review the help wanted, as basically we want help with everything, so maybe relabel the ones that are suitable to good first issue and simply remove the label in the other issues.

When looking at the labels with @The-Compiler, we also had a few thoughts about improving the labelling a bit, which boils down to:

* rename `type:docs` to `topic:docs` as this fits better there
* rename `type:infrastructure` to `topic:infrastructure` same reason as above
* rename `type:feature-branch` to `type:feature` - we do not really have feature-branches as such anymore
* relabel `type:enhancements` to `type:feature` and delete `type:enhancements`
