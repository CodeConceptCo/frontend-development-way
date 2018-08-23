## 2. Rules of the commit

Commit will stay in git history so it's also important to have a representative name for it.

The first part of a commit, as in the branch, can be **ticket id **or** sprint name **if exist.

Commit body should briefly describe the work that was done.

_Bad_

-   pie widget card
-   pie card



_Good_

-   CC-001: Created pie widget card
-   Created pie widget card
-   Fixed title for pie widget card



Benefit: you can set up Jira integration with GitHub and GitLab that will allow you to jump from commit with ticket id right to that ticket.

Also, you can use [commitizen](https://github.com/commitizen/cz-cli) to make a commit.

Commitizen is an open source project that helps contributors be good open source citizens. It accomplishes this by prompting them to follow commit message conventions at commit time. It also empowers project maintainers to create or use predefined commit message conventions in their repos to better communicate their expectations to potential contributors.