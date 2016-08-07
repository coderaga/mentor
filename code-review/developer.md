## Code Review

### Developer
Guidelines for Developer while having your code reviewed.

- The primary reviewer is the author i.e YOU
- Create a checklist for yourself of the things that the code reviews tend to focus on
	- [Checklist for Developer](https://github.com/coderaga/mentor/blob/master/code-review/checklist-for-developer.md "Checklist for Developer")
- Don't take it personally. The review is of the code, not you. Remember, You are not your code.
- Understand and accept that you will make mistakes
- Be grateful for the reviewer's suggestions. ("Good call. I'll make that change.")
- Explain why the code exists. ("It's like that because of these reasons. Would it be more clear if I rename this class/file/method/variable?")
- Don’t rewrite code without consultation. There’s a fine line between “fixing code” and “rewriting code.” Know the difference
- Extract some changes and refactorings into future tickets/stories.
- Link to the code review from the ticket/story. ("Ready for review: https://github.com/organization/project/pull/1")
- Push commits based on earlier rounds of feedback as isolated commits to the branch. Do not squash until the branch is ready to merge. Reviewers should be able to read individual updates based on their earlier feedback.
- Seek to understand the reviewer's perspective.
- Try to respond to every comment.
- Wait to merge the branch until Continuous Integration (TDDium, TravisCI, etc.) tells you the test suite is green in the branch.
- Merge once you feel confident in the code and its impact on the project.
