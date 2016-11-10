# baiduIFE-stage1
1，首次关联远程库的时候，出现fatal: remote origin already exists.
可先使用命令：git remote rm origin.然后再关联一次。
2，首次推送到关联远程库的时候，出现error: failed to push some refs to...
主要原因是github中README.md文件和LICENSE文件不在本地代码目录中。
可使用命令：git pull --rebase origin master.进行github与本地代码的合并再进行推送。


