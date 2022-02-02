# Resolving Issues

## Learning Goals

- Identify issues on SE curriculum repositories
- Fix issues

## Introduction

One of the most effective ways we have for acting on feedback from students and
instructors is by resolving open issues on lessons. We ask that students and
instructors open up issues on GitHub whenever they have a problem with a
specific lesson. The curriculum team has weekly "issues sprints" where we divvy
up the open issues and work through the backlog from the previous week. This
process allows us to stay on top of all open issues, and let students and
instructors know that their issue was resolved.

## Identifying SE Issues

Whenever a student or instructor opens an issue in a lesson in the
learn-co-curriculum GitHub organization page, they'll be prompted to fill out
the following template:

- [SE Issues Template](https://github.com/learn-co-curriculum/.github/blob/main/.github/ISSUE_TEMPLATE/se_report.yml)

This template helps ensure that we get all the necessary information about the
issue that is needed to resolve it, and it also adds an `se-curriculum` label to
the issue which makes it easier to differentiate from issues on non-SE lessons.

To review all open issues that have the `se-curriculum` label, use this link:

- https://github.com/issues?q=user%3Alearn-co-curriculum+label%3A%22se+curriculum%22+is%3Aopen+

On occasion, students will submit issues without using the correct template, so
the `se-curriculum` label won't be applied. For that reason, it's also helpful
to view recent issues from the Insights page:

- https://github.com/orgs/learn-co-curriculum/insights

Clicking "Issues" on this page will search for issues from the past week, and
you can look for other open issues on SE lessons that don't have the correct
label here.

After identifying all open issues from the previous week, assign each issue to a
curriculum developer who will be responsible for resolving the issue.

Note that for issues raised on video lessons, Ix from the Central Lecture team
is currently responsible for updating videos based on student feedback. Issues
on these repos can be assigned to their GitHub handle,
[ixnp](https://github.com/ixnp).

## Responding to Issues

For each issue assigned to a curriculum developer, the first step is to identify
what action needs to be taken based on the issue. In some cases, no action is
needed beyond a response to the student. Here is a summary of issues that are
not actionable:

- A misunderstanding with the challenge. Please tell them to ask-a-question or
  work with a coach
- This is an issue that you can't replicate. Ask the reporter for more
  details...then check back in a week. If they haven't responded close the issue
  (with a smile! and a comment) and ask them to re-open if they come across the
  issue again.

You can view common saved responses in the SE Curriculum Docs' ["Saved
Replies"][saved replies] section and find a reply that suits your need. These
replies can be considered to be a starting point — feel free to edit as desired.

[saved replies]:
  https://musical-waddle-2d4eff4c.pages.github.io/docs/issues/saved-replies/canvas-raised-issue-success

If action does need to be taken, your next step should be to respond to the
student on GitHub by replying to the issue to let them know you'll be looking
into their issue.

## Fixing the Issue

To fix an issue, you need to first make sure you understand the issue clearly
and have a plan on how to fix it. Here's an approximate workflow to follow:

1. Clone down the lesson repository
2. Create a branch for your change (or multiple branches, if the solution branch
   needs to be updated as well)
3. Make your change in the branch, test the code (use the lab tests and solution
   branch if applicable) and commit your changes
4. Push up your changed code and open a PR
5. [Link the associated issue in the PR][link issue] (i.e. enter "Closes #5" in
   the PR description)
6. Optionally get your PR reviewed by another curriculum team member, if you
   need another pair of eyes
7. Merge the PR (prefer using Squash and Merge if you made multiple commits),
   and delete your branch
8. If a change was made to the README, the `github-to-canvas` workflow will
   automatically update the blueprint in Canvas. You'll need to sync these
   changes to associated courses, so...
9. Open the Canvas blueprint associated with the lesson, and sync!

## Exercise

To practice resolving an issue, we'll make a fix to the lesson you're working on
right now! Head to the issues page for this lesson's repo:

- https://github.com/learn-co-curriculum/se-curriculum-training-resolving-issues/issues

You'll see one open issue. Use the steps above to resolve the issue, and make
sure your change is reflected in this Canvas course as well as any associated
courses (make sure to sync your update).

[link issue]:
  https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue
