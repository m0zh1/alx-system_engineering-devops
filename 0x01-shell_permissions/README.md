0-iam_betty changes current user to 'betty'
1-wh_am_i file prints effective username of current user
2-groups prints all the groups current user is part of
3-new_owner changes owner of file
4-empty creates an empty file
5-execute adds execute permission to the owner of file
6-multiple_permissions adds execute permission to owner&group and read to others
7-everybody adds execution permission to owner, group, and others
8-James_Bond sets permission to 007
9-John_Doe sets file mode to rwxr-x-wx
10-mirror_permissions Set mode of file 'hello' the same as 'olleh'
[master 1725dd0] Sets the mode using --refence flag
 2 files changed, 3 insertions(+)
 create mode 100755 0x01-shell_permissions/10-mirror_permissions
11-directories_permissions adds execute permission to all subdirs of the current di owner, group and others - Regular files arent changed
12-directory_permissions creates a dir 'my_dir' with permissions 751 in working dir
