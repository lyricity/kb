# Contributing

# Quick Guide

## To submit a page edit:

1. Open any file in our repo via GitHub.com

2. Click the pencil ✏️ on the top right of the file.

3. Make changes to the file.

4. Describe what you changed under **Propose file change** at the bottom of the page (usually `edit(<filename>): <reason>`).

5. Click [![Propose file change](https://img.shields.io/badge/Propose_file_change-brightgreen)](#).

6. Verify your changes and click [![Create pull request](https://img.shields.io/badge/Create_pull_request-brightgreen)](#), and confirm.

7. That's it! ✔️

## To submit a NEW page:

1. Create a new file.

  - [![New unsorted file](https://img.shields.io/badge/New_file-blue)](https://github.com/lyricity/kb/new/master/Unsorted) Click this button to create a new Unsorted file (we can sort it later!).
  - OR Navigate to the appropriate Folder on our repo via Github.com and click [![Create new file](https://img.shields.io/badge/Create_new_file-lightgray)](#) on the top right.

2. Name the file.

3. Create the file's content.

4. Describe what you changed under **Propose new file** at the bottom of the page (usually `create(<filename>)`).

5. Click [![Propose new file](https://img.shields.io/badge/Propose_new_file-brightgreen)](#).

6. Verify your changes and click [![Create pull request](https://img.shields.io/badge/Create_pull_request-brightgreen)](#), and confirm.

7. That's it! ✔️

--------------------------------------------------------------------------------

_Why use the GitHub browser editor? The GitHub editor is our choice because it is most convenient for most users, requiring no software or knowledge of git to submit changes._

# How do I...?

- [Use This Guide](#introduction)

- Ask or Say Something 🤔🐛😱

  - [Request Support](#request-support)
  - [Report an Issue](#report-an-issue)
  - [Request a Edit](#request-a-edit)

- Make Something 🤓👩🏽‍💻📜🍳

  - [Contribute](#contribute)

- Manage Something ✅🙆🏼💃👔

  - [Provide Support on Issues](#provide-support-on-issues)
  - [Label Issues](#label-issues)
  - [Clean Up Issues and PRs](#clean-up-issues-and-prs)
  - [Review Pull Requests](#review-pull-requests)
  - [Merge Pull Requests](#merge-pull-requests)
  - [Tag a Release](#tag-a-release)
  - [Join the Project Team](#join-the-project-team)

# Introduction

Thank you so much for your interest in contributing! All types of contributions are encouraged and valued. See the [table of contents](#toc) for different ways to help and details about how this project handles them! 📝

Please make sure to read the relevant section before making your contribution! It will make it a lot easier for us maintainers to make the most of it and smooth out the experience for all involved. 💚

The [Project Team](#join-the-project-team) looks forward to your contributions. 🙌🏾✨

# Request Support

If you have a question about this project, how to use it, or just need clarification about something:

- Open an Issue at <https://github.com/lyricwulf/kb/issues>
- Provide as much context as you can about what you're running into.

Once it's filed:

- The project team will [label the issue](#label-issues).
- Someone will try to have a response soon.
- If you or the maintainers don't respond to an issue for 30 days, the [issue will be closed](#clean-up-issues-and-prs). If you want to come back to it, reply (once, please), and we'll reopen the existing issue. Please avoid filing new issues as extensions of one you already made.

# Report an Issue

If you run into an issue with the project:

- Open an Issue at <https://github.com/lyricwulf/kb/issues>

Once it's filed:

- The project team will [label the issue](#label-issues).
- If you or the maintainers don't respond to an issue for 30 days, the [issue will be closed](#clean-up-issues-and-prs). If you want to come back to it, reply (once, please), and we'll reopen the existing issue. Please avoid filing new issues as extensions of one you already made.
- `critical` issues may be left open, depending on perceived immediacy and severity, even past the 30 day deadline.

# Request an Edit

If the project doesn't include something you need or want:

- Open an Issue at <https://github.com/lyricwulf/kb/issues>
- Please try and be clear about why existing docs do not work.

Once it's filed:

- The project team will [label the issue](#label-issues).
- The project team will evaluate the edit request, possibly asking you more questions to understand its purpose and any relevant requirements. If the issue is closed, the team will convey their reasoning and suggest an alternative path forward.
- If the edit request is accepted, it will be marked for implementation with `edit-accepted`, which can then be done by either by a core team member or by anyone in the community who wants to [contribute edits](#contribute-edits).

Note: The team is unlikely to be able to accept every single edit request that is filed. Please understand if they need to say no.

# Contribute

Contributions of any size are welcome! Feel free to file a PR even if you're just rewording a sentence to be more clear, or fixing a spelling mistake!

To contribute documentation:

- Edit or add any relevant documentation.
- Make sure your changes are formatted correctly and consistently with the rest of the documentation.
- Re-read what you wrote, and run a spellchecker on it to make sure you didn't miss anything.
- Write clear, concise commit message(s) using `<folder>(<page>): <message>`.
- Go to <https://github.com/lyricwulf/kb/pulls> and open a new pull request with your changes.
- If your PR is connected to an open issue, add a line in your PR's description that says `Fixes: #123`, where `#123` is the number of the issue you're fixing.

Once you've filed the PR:

- One or more maintainers will use GitHub's review feature to review your PR.
- If the maintainer asks for any changes, edit your changes, push, and ask for another review.
- If the maintainer decides to pass on your PR, they will thank you for the contribution and explain why they won't be accepting the changes. That's ok! We still really appreciate you taking the time to do it, and we don't take that lightly. 💚
- If your PR gets accepted, it will be marked as such, and merged into the `latest` branch soon after. Your contribution will be distributed to the masses next time the maintainers [tag a release](#tag-a-release)

# Label Issues

[Needs Collaborator](#join-the-project-team): Issue Tracker

One of the most important tasks in handling issues is labeling them usefully and accurately. All other tasks involving issues ultimately rely on the issue being classified in such a way that relevant parties looking to do their own tasks can find them quickly and easily.

In order to label issues, [open up the list of unlabeled issues](https://github.com/lyricwulf/kb/issues?q=is%3Aopen+is%3Aissue+no%3Alabel) and, **from newest to oldest**, read through each one and apply issue labels according to the table below. If you're unsure about what label to apply, skip the issue and try the next one: don't feel obligated to label each and every issue yourself!

Label           | Apply When                                                                                                                                                                                                                                                                                                    | Notes
--------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
`bug`           | Cases where the documentation is understood in a way it wasn't intended.                                                                                                                                                                                                                                      | If something is stated that surprises the _user_ but does not go against the way the doc is designed, it should use the `enhancement` label.
`critical`      | Added to `bug` issues if the problem described makes the doc completely unusable in a common situation.                                                                                                                                                                                                       |
`documentation` | Added to issues or pull requests that affect any of the documentation for the project.                                                                                                                                                                                                                        | Can be combined with other labels, such as `bug` or `enhancement`.
`duplicate`     | Added to issues or PRs that refer to the exact same issue as another one that's been previously labeled.                                                                                                                                                                                                      | Duplicate issues should be marked and closed right away, with a message referencing the issue it's a duplicate of (with `#123`)
`enhancement`   | Added to [edit requests](#request-a-edit), PRs, or documentation issues that are purely additive: the docs are underrstood as expected, but a change is being requested or suggested.                                                                                                                         |
`help wanted`   | Applied by [Committers](#join-the-project-team) to issues and PRs that they would like to get outside help for. Generally, this means it's lower priority for the maintainer team to itself implement, but that the community is encouraged to pick up if they so desire                                      | Never applied on first-pass labeling.
`in-progress`   | Applied by [Committers](#join-the-project-team) to PRs that are pending some work before they're ready for review.                                                                                                                                                                                            | The original PR submitter should @mention the team member that applied the label once the PR is complete.
`performance`   | This issue or PR is directly related to improving performance.                                                                                                                                                                                                                                                |
`refactor`      | Added to issues or PRs that deal with cleaning up or modifying the project for the betterment of it.                                                                                                                                                                                                          |
`support`       | This issue is either asking a question about how to use the project, clarifying the reason for unexpected docs, or possibly reporting a `bug` but does not have enough detail yet to determine whether it would count as such.                                                                                |
`wont-add`      | Labelers may apply this label to issues that clearly have nothing at all to do with the project or are otherwise entirely outside of its scope/sphere of influence. [Committers](#join-the-project-team) may apply this label and close an issue or PR if they decide to pass on an otherwise relevant issue. | The issue or PR should be closed as soon as the label is applied, and a clear explanation provided of why the label was used. Contributors are free to contest the labeling, but the decision ultimately falls on committers as to whether to accept something or not.

# Clean Up Issues and PRs

[Needs Collaborator](#join-the-project-team): Issue Tracker

Issues and PRs can go stale after a while. Maybe they're abandoned. Maybe the team will just plain not have time to address them any time soon.

In these cases, they should be closed until they're brought up again or the interaction starts over.

To clean up issues and PRs:

- Search the issue tracker for issues or PRs, and add the term `updated:<=YYYY-MM-DD`, where the date is 30 days before today.
- Go through each issue _from oldest to newest_, and close them if **all of the following are true**:

  - not opened by a maintainer
  - not marked as `critical`
  - not marked as `starter` or `help wanted` (these might stick around for a while, in general, as they're intended to be available)
  - no explicit messages in the comments asking for it to be left open
  - does not belong to a milestone

- Leave a message when closing saying "Cleaning up stale issue. Please reopen or ping us if and when you're ready to resume this. See <https://github.com/lyricwulf/kb/blob/latest/CONTRIBUTING.md#clean-up-issues-and-prs> for more details."

# Review Pull Requests

[Needs Collaborator](#join-the-project-team): Issue Tracker

While anyone can comment on a PR, add feedback, etc, PRs are only _approved_ by team members with Issue Tracker or higher permissions.

PR reviews use [GitHub's own review feature](https://help.github.com/articles/about-pull-request-reviews/), which manages comments, approval, and review iteration.

Some notes:

- You may ask for minor changes ("nitpicks"), but consider whether they are really blockers to merging: try to err on the side of "approve, with comments".
- _ALL PULL REQUESTS_ should be thoroughly proofread.
- Please make sure you're familiar with the documentation being updated, unless it's a minor change (spellchecking, minor formatting, etc). You may @mention another project member who you think is better suited for the review, but still provide a non-approving review of your own.
- Be extra kind: people who submit contributions are putting themselves in a pretty vulnerable position, and have put time and care into what they've done (even if that's not obvious to you!) -- always respond with respect, be understanding, but don't feel like you need to sacrifice your standards for their sake, either. Just don't be a jerk about it?

# Merge Pull Requests

[Needs Collaborator](#join-the-project-team): Committer

TBD

# Tag A Release

[Needs Collaborator](#join-the-project-team): Committer

TBD

# Join the Project Team

## Ways to Join

There are many ways to contribute! Most of them don't require any official status unless otherwise noted. That said, there's a couple of positions that grant special repository abilities, and this section describes how they're granted and what they do.

All of the below positions are granted based on the project team's needs, as well as their consensus opinion about whether they would like to work with the person and think that they would fit well into that position. The process is relatively informal, and it's likely that people who express interest in participating can just be granted the permissions they'd like.

You can spot a collaborator on the repo by looking for the `[Collaborator]` or `[Owner]` tags next to their names.

Permission    | Description
------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Issue Tracker | Granted to contributors who express a strong interest in spending time on the project's issue tracker. These tasks are mainly [labeling issues](#label-issues), [cleaning up old ones](#clean-up-issues-and-prs), and [reviewing pull requests](#review-pull-requests), as well as all the usual things non-team-member contributors can do. Issue handlers should not merge pull requests, tag releases, or directly commit edits themselves: that should still be done through the usual pull request process. Becoming an Issue Handler means the project team trusts you to understand enough of the team's process and context to implement it on the issue tracker.
Committer     | Granted to contributors who want to handle the actual pull request merges, tagging new versions, etc. Committers should have a good level of familiarity with the docs, and enough context to understand the implications of various changes, as well as a good sense of the will and expectations of the project team.
Admin/Owner   | Granted to people ultimately responsible for the project, its community, etc.

--------------------------------------------------------------------------------

_This document adapted from [WeAllJS/weallcontribute](https://github.com/WeAllJS/weallcontribute)._
