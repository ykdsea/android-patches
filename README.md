# patch-collections

#debugerd-dump-all-stacks.diff
让debugerd打印出所有的stack内容.

#logcat.service.diff
添加自动记录logcat信息的服务.

#init.not.start-dump.memory.patch
init空循环,不启动android. 并打印内存信息,为了方便确认启动过程中的内存消耗.

#backtrace.dump.fail.tid.patch
 打印signal 33出现无相应的tid,并dump当时kernel stack.
需要配合debughelper使用.

#art.anr.dump.patch
art signal catcher中添加系统状态的dump.
需要配合debughelper

#surfaceflinger.dump.ion.usage.patc
surfaceflinger检测ion消耗,并dump layer的消耗.
需要配合debughelper使用.

