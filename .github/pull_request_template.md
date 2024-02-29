> https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#referencing-issues-and-pull-requests

> @octocat :+1: This PR looks great - it's ready to merge! :shipit:
> https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

> <!-- This content will not appear in the rendered Markdown -->

> Let's rename \*our-new-project\* to \*our-old-project\*.

> Here is a simple footnote[^1].

> A footnote can also have multiple lines[^2].

> [^1]: My reference.
> [^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
>  This is a second line.

> - [x] #739
> - [ ] https://github.com/octo-org/octo-repo/issues/740
> - [ ] Add delight to the experience when all tasks are complete :tada:

## Developer Notes
>>  ### Task Link 
>> ### Comments

## Pull Request Reviewer{Name} Checklist 
> - [ ] Does the code work? Does it perform its intended function, the logic is correct etc.
> - [ ] Is all the code easily understood?
> - [ ] Does it have correct linting?
> - [ ] Is there any redundant or duplicate code?
> - [ ] Is the code as modular as possible?
> - [ ] Can any global variables be replaced?
> - [ ] Can any of the code be replaced with library functions?
> - [ ] Can any logging or debugging code be removed?
> - [ ] Does code follow defined architecture?
> - [ ] Does feature implementation follow UAC and specified design?
> - [ ] Ensure PR passes CI server, re-running once or twice if it fails. Failure could be due to other issues, so determine whether the PR is responsible if failure occurs.
> - [ ] Request changes to the code and/or additional unit tests if any issues are found.
> - [ ] Is any code invoking memory leaks?
> - [ ] Are properties declared with the correct storage semantics? (e.g. weak or unowned instead of strong)
> - [ ] Are good names used for classes, enum, struct , methods, and variables?
