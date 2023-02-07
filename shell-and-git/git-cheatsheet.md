git usage: git [COMMAND] [OPTION] [...]
init				:	initiate Git repo
clone [URL/SSH]			:	clone Git repo (https/ssh)
status				:	show working and staging directory
log				:	show commit history (--oneline : show in one line)
add [FILE]			:	add [FILE] to staging directory
commit -m			:	commit staging directory with message (-m) in double quotes
fetch				:	fetch changes from remote repo
push -u [REMOTE] [BRANCH]	:	push HEAD(current commit) upstream (-u) to remote repo
pull				:	download current HEAD from remote repo
checkout [COMMIT-HASH/BRANCH]	:	set HEAD to commit at [COMMIT-HASH] or to HEAD at [BRANCH]
remote add [REMOTE] [HTTPS/SSH]	:	add remote repo [REMOTE] to upper stream
branch [BRANCH]	[-m/-M]		:	create new branch [BRANCH] (-m/-M : rename old branch to new branch)
restore [FILE]			:	restore to last commit or restore [FILE] only

