# Contributing to Wyandotte Robotics

Thanks for helping build the BearBots' code. This guide applies to every repository in the organization unless a repository has its own `CONTRIBUTING.md`.

## Who can contribute

Students, coaches and mentors on FRC Team 8124 and FTC Team 14158. Ask a coach to invite your GitHub account to the organization and add you to your team.

GitHub accounts require you to be at least 13. If you're younger, pair up with a teammate or mentor who commits the work you write together.

## Privacy first

Repositories here can be seen by anyone on the internet. Before you commit, check that your change has **none** of these:

- Student last names, phone numbers, emails, addresses or birthdays
- Photos or videos of students
- Passwords, API keys, Wi‑Fi passwords or team account logins

If you commit one by accident, tell a coach right away. Don't try to fix it by deleting the file: it stays in the history, and a coach needs to clean it up.

Pick a GitHub username that doesn't include your full name, and set your GitHub profile name to your first name and last initial.

## How we work

1. **Pick or create an issue** for the thing you're working on, so the team knows who's doing what.
2. **Make a branch** off `main`. Name it after what you're doing: `drive/field-centric`, `auto/left-side`, `fix/arm-limit`.
3. **Commit small and often.** Write messages that say what changed: "Add field-centric drive toggle", not "stuff" or "fixed it".
4. **Test on the robot** (or in simulation) before you ask for a review. Say in the pull request how you tested it.
5. **Open a pull request** into `main` and fill in the template. Ask a programming lead or mentor to review.
6. **Merge** once it's approved and tested. Delete your branch after merging.

`main` should always hold code that's safe to put on the robot. At a competition, only deploy code from `main`, and only after a lead or mentor says it's ready.

## Code style

- Follow the style of the code around you.
- Use clear names: `armMotor`, not `m3`.
- Keep robot constants (ports, speeds, PID values) in one place, not scattered through the code.
- Comment the *why*, not the *what*.

## Getting help

Ask in your team's channel, ask a programming lead or mentor, or open an issue. Nobody knows everything; asking early saves everyone time.

## Gracious Professionalism

We follow the [FIRST Core Values](https://www.firstinspires.org/about/vision-and-mission) and our [Code of Conduct](CODE_OF_CONDUCT.md). Review each other's code the way you'd want yours reviewed: kind, specific and helpful.
