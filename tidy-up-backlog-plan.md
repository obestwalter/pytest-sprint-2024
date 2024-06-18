We have more than 800 open issues, quite a few of them very old and with no proper follow-up and quite a few might be good first issues, if provided with a bit more context. 

We had a small discussion already with @The-Compiler and @webknjaz - the rough plan is going through issues with these things in mind:

1. If the issue is really old and it is not quick/easily to reproduce it, ask for follow-up and mark with [needs: information](https://github.com/pytest-dev/pytest/labels/status%3A%20needs%20information) - we already have automation that those are auto-closed then after a month
2. if it is easy to reproduce: reproduce it, add a comment that verifies the reproduction and update the original issue comment with that info and a link to the reproducing comment, so that it is clear right away that this might be an old issue but it is still valid
3. If an issue is obviously already solved or invalid, close it right away with the proper explanation
4. If something is not yet labelled properly, add the proper label (D'UH!)
5. If something looks like a good first issue, add the label - there are doubts that there are any good first issues, but it's worth a try. This might help:
   * Add a bit more context for people to get started, if more experienced devs can give some pointers already, this might turn it into a doable task
   * if it is a bug, and it does not have a reproducer already: write one marked as XFAIL
6. Review issues labelled `help wanted` as basically we want help with everything. We should the ones that are suitable as good first issue and simply remove the label in the other issues.
7. Close issues which could feasibly be implemented as plugins outside this repo
8. (Maybe) prioritize the bugs (volunteers can fix or not fix wahtever they want, but maybe some pick higher prio bugs if they know they would have a higher impact?)

## Other things to do

* Add automation to close feature requests which are more than one year old (this will likely be controversial, but the thinking here is, that if it is a good idea it will come up again later, or someone will dig it out of the closed issues - more ruthlessly closing feature requests that are not being picked up is the better alternative than clogging the backlog with potentially stale ideas).
* Improve the labels:
  * rename `type:docs` to `topic:docs` as this fits better there
  * rename `type:infrastructure` to `topic:infrastructure` same reason as above
  * rename `type:feature-branch` to `type:feature` - we do not really have feature-branches as such anymore
* Document the labels:
  * e.g. clarify the difference between `type:enhancements` (improving and existing feature) and `type:feature` adding a completely new feature
* Document how we (want to) handle issues and PRs (mainly what are the criteria for closing) with the aim of being helpful for contributors and people opening issues
