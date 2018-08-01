Basic
---
`$ swift --version`  

REPL
---
`$ swift` - launch  
`:help` - list available LLDB commands  
`:q` - quit

Packages
---
`$ swift package init` - create dir structure  
`$ swift package init —type executable`   
`$ swift build` - load and compile dependencies from Package.swift  
`$ swift test` - run tests  
`$ swift run PackageName Argument1` - build & run executable

LLDB Debugger
---
`swiftc -g FileName.swift` - generate executable, *-g* generate debug info  
`lldb FileName` or `lldb ./build/debug/ExecutableName` - run through the debugger  
`b 2` - set breakpoint at line 2  
`r` - run the process  
`p n` - print value of the parameter n  
`p n * n` - evaluate expression  
`bt` - show backtrace  
`c` -  continue, resume the process  
`br di` - disable all breackpoints 

Resources
---
  * https://swift.org/getting-started/
  * https://github.com/apple/swift-package-manager
  * https://github.com/apple/swift-lldb
  * https://stackoverflow.com/questions/30777110/how-do-i-quit-swift-repl-without-using-ctrl-d
