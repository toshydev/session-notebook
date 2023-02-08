## Markdown Syntax
| Syntax | Element |
| --- | --- |
| `#` | heading 1 |
| `##-n` | heading 2-n |
| `-` | unordered list item |
| `1.-n.` | odered list item |
| `[][x]` | checkbox |
| `**...**` | bold |
| `_..._` | italic |
| `[link name](https://)` | link |
| `>` | blockquote |
| `---` | divider |
| ` `...` ` | inline code block |
| ` ```...``` ` | code block |


## GitHub Commands
**git usage:** `git` [COMMAND] [OPTION] [...]
| Command | Description |
| --- | --- |
| `init` | initiate Git repo |
| `clone` [URL/SSH] | clone Git repo (url/ssh) |
| `status` | show working and staging directory |
| `log` |	show commit history (--oneline : show in one line) |
| `add` [FILE] | add [FILE] to staging directory |
| `commit -m` | commit staging directory with message (-m) in double quotes |
| `fetch`	| fetch changes from remote repo |
| `push -u` [REMOTE] [BRANCH] | push HEAD(current commit) upstream (-u) to remote repo |
| `pull` | download current HEAD from remote repo |
| `checkout` [COMMIT-HASH/BRANCH] | set HEAD to commit at [COMMIT-HASH] or to HEAD at [BRANCH] |
| `remote add` [REMOTE] [HTTPS/SSH] |	add remote repo [REMOTE] to upper stream |
| `branch` [BRANCH] [-m/-M] |	create new branch [BRANCH] (-m/-M) | rename old branch to new branch) |
| `restore` [FILE] | restore to last commit or restore [FILE] only |
| `switch` (-c) [BRANCH] | switch to [BRANCH] (create new with -c) |