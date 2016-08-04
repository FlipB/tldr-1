# diff

> Compare files and directories.

- Compare files:

`diff {{file1}} {{file2}}`

- Compare files, ignoring white spaces:

`diff -w {{file1}} {{file2}}`

- Compare files, showing differences side by side:

`diff -y {{file1}} {{file2}}`

- Compare directories recursively:

`diff -r {{directory1}} {{directory2}}`

- Compare directories, only showing the names of files that differ:

`diff -rq {{directory1}} {{directory2}}`

- Create patch file of changes from directory1 to directory2:

`diff -Naur {{directory1}} {{directory2}} > {{patchfile}}`
