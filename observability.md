- **strace**

  Traces system calls and signals made by a process, useful for debugging and seeing what a program is doing with the kernel.

- **ltrace**

  Traces calls to shared library functions and their arguments/returns.

- **ss**

  Displays detailed information about sockets and network connections, similar to but more modern than netstat.

- **netstat**

  Shows network connections, routing tables, interface statistics, and protocol usage.

- **sysdig**
- 
  System-wide capture and inspection tool that records system calls and events, useful for troubleshooting and security analysis.

- **pidstat**
- 
  Per-process statistics reporter (CPU, memory, I/O, etc.), part of the sysstat package.

- **perf**
- 
  Kernel and user-space performance analysis tool for profiling CPU usage, cache misses, context switches, and many other events.

- **ftrace**
- 
  Built-in kernel tracer for function calls and events inside the Linux kernel.

- **stap (SystemTap)**
- 
  Dynamic tracing framework for probing kernel and user-space events using scripts.

- **ktap**
- 
  Lightweight scripting-based dynamic tracing tool for the Linux kernel, similar in spirit to SystemTap.

- **eBPF (with tools using it)**
- 
  Extended Berkeley Packet Filter infrastructure, used by many modern tools to run safe programs in the kernel for tracing and observability.

- **dtrace**
- 
  Originally from Solaris, a comprehensive dynamic tracing framework; on Linux, ports or equivalents provide kernel and user-space probes.

- **lttng**
- 
  Low-overhead tracing framework for recording kernel and user-space events, often used for long-running or production tracing.

- **iostat**
- 
  Reports CPU statistics and I/O statistics for devices and partitions.

- **iotop**
- 
  Top-like interface that shows real-time I/O usage by processes or threads.

- **blktrace**
  Low-level tracing of block I/O operations on storage devices.

- **swapon**
- 
  Enables and displays swap devices or files, used to manage swap space.

- **tiptop**
- 
  Top-like utility focused on showing per-thread performance counters via perf events.

- **iptraf**
- 
  Console-based interactive tool that shows real-time network traffic statistics per connection or interface.

- **tcpdump**
- 
  Command-line packet capture tool for inspecting network traffic on an interface.

- **nicstat**
- 
  Reports per-network-interface throughput, utilization, and errors.

- **ip**
- 
  Modern replacement for ifconfig/route; manages network interfaces, addresses, routes, tunnels, and more.

- **ethtool**
- 
  Queries and configures Ethernet device settings such as speed, duplex, offloads, and driver information.

- **snmpget**
- 
  Simple Network Management Protocol query tool that retrieves specific OIDs from network devices.

- **lldptool**
- 
  Manages and displays information from the LLDP (Link Layer Discovery Protocol) daemon, used for network topology discovery.

- **sar**
- 
  Collects, reports, and saves system activity information over time, including CPU, memory, I/O, and network stats.

- **dstat**
- 
  Versatile real-time resource statistics tool that combines vmstat, iostat, netstat, and others into one view.

- **/proc**
- 
  Pseudo-filesystem exposing kernel and process information, read by many tools or inspected directly with cat/grep.

- **mpstat**
- 
  Reports CPU usage statistics per processor and for all processors combined.

- **top**
- 
  Interactive real-time view of processes and system resource usage, primarily CPU and memory.

- **ps**
- 
  Snapshots process status and attributes at a single point in time.

- **vmstat**
- 
  Reports virtual memory statistics along with processes, CPU, and I/O metrics.

- **slabtop**
- 
  Displays real-time kernel slab cache information for diagnosing kernel memory usage.

- **free**
- 
  Summarizes system memory usage, including RAM and swap, in a simple table.
