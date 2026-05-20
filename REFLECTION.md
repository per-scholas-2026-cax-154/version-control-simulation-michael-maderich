# Version Control Workflow Reflection

## Branch Creation and Management

My version control workflow began with initializing the repository on the `main` branch, establishing a clean starting point. From there, I created two feature branches to work on different components in parallel: `feature/footer` and `feature/header`. This approach allowed me to isolate changes for distinct features, preventing unintended side effects to the main codebase. By organizing work into separate branches, I maintained a clear separation of concerns - one branch for header functionality and another for footer functionality. This branching strategy is a fundamental practice in collaborative development, enabling team members to work independently while keeping the main branch stable.

## Handling the Merge Conflict

When merging both feature branches back into main, I encountered a merge conflict in `index.html`. This conflict arose because both branches modified the same file, creating divergent changes that Git couldn't automatically reconcile. To resolve this, I used VS Code's merge conflict interface, which provided a visual comparison of the conflicting sections. I carefully reviewed the changes from both branches and chose to accept the incoming changes, effectively integrating the modifications from the feature branches. This hands-on conflict resolution taught me the importance of clear communication about which changes take precedence and reinforced the value of VS Code's intuitive merge tools in resolving such issues efficiently.

## Pull Request Process and Code Quality

The pull request process, simulated through the `review/main` branch and remote tracking, emphasized the importance of code review and quality assurance before merging into the main branch. By requiring changes to go through a review branch first, the workflow ensured that all modifications were scrutinized before integration. This process promotes collaboration by allowing team members to discuss changes, identify potential issues, and ensure code quality standards are met. The practice of using pull requests prevents directly committing to main, reducing the risk of introducing bugs into the production-ready codebase and fostering a culture of accountability and continuous improvement through peer review.

## Peer Review Evidence

I conducted a thorough review of Pull Request #1 on GitHub, which merges 3 commits from `main` into `review/main`. During my review of the `index.html` file changes, I identified an issue: the copyright notice on line 13 references "2024 Michael Maderich" when it should reflect the current year, 2026. I posted a comment on the specific line requesting this correction. This review process demonstrates the value of peer scrutiny in catching details that could impact the accuracy and professionalism of the code. The GitHub pull request interface provided clear visibility into the diff, making it easy to identify inconsistencies and provide targeted, actionable feedback.
