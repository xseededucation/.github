Jira Story Link - 

Objective : <what is the object of the implementation>
Solution : <What implementation done>
Evidence : <Any GIF/Video/Report Sample as proof of the implementation for happy path(Normal scenario excluding the corner cases)>

# Before submitting for Code Review, the developer should check the following:
- [ ] Does this PR contain less than 200 Lines of Change?
- [ ] Is the feature tested?
- [ ] Is self review of code done?
- [ ] Is Unit test coverage > 85%?
- [ ] HLD & LLD reviewed and signed off from Desh / Shriram?
- [ ] Is HLD, LLD and code implementation in sync? That is, any change to logic made during the coding phase been updated in LLD?
- [ ] Is DB structure optimized?
- [ ] Are DB Indexes added?
- [ ] DRY Principle followed?
- [ ] Single Responsibility Principle followed?
- [ ] Is Linter configured (if already not present in the repository)?
- [ ] New Relic SDK integrated (if not integrated already)?
- [ ] Zero commented out code?
- [ ] Are unwanted comments removed?
- [ ] Decisions are commented?
- [ ] Max 300 lines per file constraint met?
- [ ] Does all functions have 6 lines max?
- [ ] Exceptions are handled everywhere?
- [ ] Added Logs?

# When reviewing a pull request, the reviewer check for the following:
- [ ] Every point in previous section checked?
- [ ] HLD reviewed?
- [ ] LLD reviewed?
- [ ] Code implemented as mentioned in LLD?
- [ ] HLD & LLD reviewed and signed off from Desh / Shriram? 
- [ ] Is Unit test coverage > 85%?
- [ ] Is DB structure optimized?
- [ ] Are DB Indexes added?
- [ ] DRY Principle followed?
- [ ] Single Responsibility Principle followed?
- [ ] Is Linter configured (if already not present in the repository)?
- [ ] New Relic SDK integrated (if not integrated already)?
- [ ] Zero commented out code?
- [ ] Are unwanted comments removed?
- [ ] Decisions are commented?
- [ ] Max 300 lines per file constraint met?
- [ ] Does all functions have 6 lines max?
- [ ] Are commits made as per the standard?
- [ ] Exceptions are handled everywhere?
- [ ] Are enough logs present to debug any issue that might arise in the future?
- [ ] Number of issues found during code review been logged in Conversation tab?
- [ ] Do you have enough understanding to explain the code to another developer?

# When deploying to production, the deployer check for the following:
- [ ] Are all points previous two sections checked?
- [ ] Are all conversations in the PR resolved by Code Reviewer?
- [ ] Is JIRA Story in `Can Go Live` stage?
- [ ] Does this require any script to be run?
- [ ] Does this require mobile app release?
- [ ] Is mobile app released (if needed) ?
