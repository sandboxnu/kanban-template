# Kanban Template

## What is this for?

One of the most important parts about being a team lead is having a method for tracking the issues the team will tackle during the semester. This achieves three goals:
1. Creating a concrete, actionable plan for achieving the semester's deliverables
2. Tracking progress towards those deliverables
3. Tracking member progress and success

This tempate is a good starting point for creating an issue tracker for your team.

## What is a Kanban Board?

The idea of a Kanban board is to create an easy mechanism for tracking each issue (or ticket, or story, whatever you want to call it...) the team will work on to complete a project. 

The board is organized as a sequence of columns. Each 'issue' your team will work on as a part of the project begins on the leftmost side, in the 'backlog' or 'todos'. As the issue progresses, it marches across the board, to 'In Development', 'In PR/Review', and finally, 'Done'. In that way, these boards make it easy to determine what's finished, what's left to do, and what's currently in progress for your team.

## How do I use this project template?

To create your own board from this template:
1. Select `Projects` at the top of this repository
2. Select the `Template` project
3. Select `Menu` on the right-most side of the project screen
4. Select the three dots in the corner of the sidebar that appears
5. Select `Copy`
6. Choose the repo that you're in charge of from the list of Owners.

It's a long list of steps, but at the end of it, you'll have a new project board in your repository!

## What does the template come with?

This template comes with four columns:
1. Todo: the issues that remain for you to complete in the remainder of the semester.
2. In Progress: the issues that team members are actively working on. Could also be called `In Development`.
3. In Review: the issues that are in PR and are waiting for a review before they can be released.
4. Done: the issues that have been finished, merged into master, and (as applicable) released to production.

There are other columns that might be useful for your team's workflow. For example, you might add an `In Design` column if your issues must come with a design specification by your team's designer, and the developer won't get started on it until that design is finished. This template isn't meant to be set in stone--it is most effective when it accurately describes the state of your project and reflects your team's development workflow.

## How should I use this new issue tracker?

Your workflow with the issue tracker will look something like this:
1. At the beginning of the semester, once your goals are established, create a GitHub issue for each issue/ticket/'story' that the team will work on to get there
2. When a team member is available for new work, assign them one of the available tickets, and update the position of the ticket as the member makes progress
3. When all of the issues have moved from the `Backlog` to the `Done` column, you've reached your goals for the semester!

If the board is accurate and up-to-date, this creates an effective visual representation to understand progress, both for members and for the team, and acts as a good source of truth for project and issue status.

## What can I do to make managing the board easier?

At a lot of companies, a Kanban board is a physical entity--there's a big whiteboard covered in sticky notes, and members manually move these notes across the board as their issue progresses. Of course, you don't have the luxury of depending on something like that. But, GitHub gives you ways of mimicking this by automatically updating the status of tickets as members interact with the remote repository.

GitHub allows you to do this by assigning an 'automation preset' to columns. These presets allow you to specify where a ticket should move as the GitHub Issue is updated or when a PR is created. For example, the `Todo` preset allows you to place all newly-created GitHub Issues automatically into your `Todo` column. To learn more about project board automation, see [Github's docs](https://help.github.com/en/github/managing-your-work-on-github/about-automation-for-project-boards).
