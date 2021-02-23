# learning-bcc

## Generals
- https://github.com/iovisor/bcc

## Basics
### [Linux Performance Analysis in 60,000 ms](https://netflixtechblog.com/linux-performance-analysis-in-60-000-milliseconds-accc10403c55)
- `uptime`
- `dmesg | tail`
- `vmstat 1`
- `mpstat -P All 1`
- `pidstat 1`
- `iostat -xz 1`
- `free -m`
- `sar -n DEV 1`
- `sar -n TCP,ETCP 1`
- `top`
### General Performance
- `execsnooop`
- `opensnoop`
- `ext4slower`
- `biolatency`
- `biosnoop`
- `cachestat`
- `tcpconnect`
- `tcpaccept`
- `tcpretrans`
- `runqlat`
- `profile`

## Tools
<center><a href="https://raw.githubusercontent.com/iovisor/bcc/master/images/bcc_tracing_tools_2019.png"><img src="https://raw.githubusercontent.com/iovisor/bcc/master/images/bcc_tracing_tools_2019.png" border=0 width=700></a></center>


## Tutorials
- [bcc Tutorial](https://github.com/iovisor/bcc/blob/master/docs/tutorial.md)
- [bcc Python Developer Tutorial](https://github.com/iovisor/bcc/blob/master/docs/tutorial_bcc_python_developer.md)
