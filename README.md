# @_@ NO COMMENTS IT IS WINDOWS 11 PRO

msdt.exe    /id    PerformanceDiagnostic
net    stop    iphlpsvc
net    stop    wscsvc
net    stop    Winmgmt
net    start    Winmgmt
net    start    wscsvc
net    start    iphlpsvc
