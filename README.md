# solid-principles

Examples for SOLID principles

#### 1. Single-Responsibility
A class should only have one responsibility and should have one reason to change.

###### Benefits:
- <strong>Testing</strong> - fewer test cases for one responsibility class.
- <strong>Lower coupling</strong> - less functionality will have fewer dependencies.
- <strong>Organization</strong> - smaller, well-organized classes are easier to search.
- <strong>Implementation</strong> - easier.
- <strong>Modification</strong> - prevents unexpected side-effects of future changes and easier to understand.

**Note: oversimplify your code will lead to unreadable and confusing.

###### Tip:
- What is the responsibility of your class/component/...?
- If your answer from above question has "and" word, you should step back and rethink.
