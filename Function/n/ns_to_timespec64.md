# Function: <code>ns_to_timespec64</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec ns_to_timespec64(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579917130,
      "name": "ns_to_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:533",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": [
        "kernel/sys.c:do_sysinfo",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_clock_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/pstore/platform.c:pstore_record_init",
        "drivers/dma-buf/sync_debug.c:sync_print_fence",
        "drivers/rtc/rtc-lib.c:rtc_ktime_to_tm",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_get_timestampns",
        "net/core/sock.c:sock_get_timestampns",
        "net/compat.c:compat_sock_get_timestampns",
        "net/compat.c:compat_sock_get_timestampns",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/packet/af_packet.c:tpacket_get_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917264,
      "name": "ns_to_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579962901,
      "name": "ns_to_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:545",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_clock_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/pstore/platform.c:pstore_record_init",
        "drivers/dma-buf/sync_debug.c:sync_print_fence",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/rtc/rtc-lib.c:rtc_ktime_to_tm",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579963296,
      "name": "ns_to_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580009957,
      "name": "ns_to_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:483",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": [
        "kernel/sys.c:do_sysinfo",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_clock_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/pstore/platform.c:pstore_record_init",
        "drivers/dma-buf/sync_debug.c:sync_print_fence",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/rtc/lib.c:rtc_ktime_to_tm",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580010080,
      "name": "ns_to_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580053269,
      "name": "ns_to_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:551",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": [
        "kernel/sys.c:do_sysinfo",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_clock_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/pstore/platform.c:pstore_record_init",
        "drivers/dma-buf/sync_debug.c:sync_print_fence",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/rtc/lib.c:rtc_ktime_to_tm",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/sock.c:sock_gettstamp",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580053392,
      "name": "ns_to_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580102325,
      "name": "ns_to_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:551",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": [
        "kernel/sys.c:do_sysinfo",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_clock_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/pstore/platform.c:pstore_record_init",
        "drivers/dma-buf/sync_debug.c:sync_print_fence",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/rtc/lib.c:rtc_ktime_to_tm",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/sock.c:sock_gettstamp",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580102448,
      "name": "ns_to_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580165173,
      "name": "ns_to_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:506",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_get_tai_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/pstore/platform.c:pstore_dump",
        "drivers/dma-buf/sync_debug.c:sync_print_fence",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/rtc/lib.c:rtc_ktime_to_tm",
        "drivers/ptp/ptp_clock.c:ptp_clock_event",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/sock.c:sock_gettstamp",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/packet/af_packet.c:__packet_set_timestamp",
        "net/packet/af_packet.c:__packet_set_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580162496,
      "name": "ns_to_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580149317,
      "name": "ns_to_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:506",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_get_tai_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/pstore/platform.c:pstore_dump",
        "drivers/dma-buf/sync_debug.c:sync_print_fence",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/rtc/lib.c:rtc_ktime_to_tm",
        "drivers/ptp/ptp_clock.c:ptp_clock_event",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/sock.c:sock_gettstamp",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/packet/af_packet.c:__packet_set_timestamp",
        "net/packet/af_packet.c:__packet_set_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146640,
      "name": "ns_to_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580154005,
      "name": "ns_to_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:506",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_get_tai_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/pstore/platform.c:pstore_dump",
        "drivers/dma-buf/sync_debug.c:sync_print_fence",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/rtc/lib.c:rtc_ktime_to_tm",
        "drivers/ptp/ptp_clock.c:ptp_clock_event",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/sock.c:sock_gettstamp",
        "net/ipv4/tcp.c:tcp_update_recv_tstamps",
        "net/ipv4/tcp.c:tcp_update_recv_tstamps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580151328,
      "name": "ns_to_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580298533,
      "name": "ns_to_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:506",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_get_tai_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/pstore/platform.c:pstore_dump",
        "drivers/dma-buf/sync_debug.c:sync_print_fence",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/rtc/lib.c:rtc_ktime_to_tm",
        "drivers/ptp/ptp_clock.c:ptp_clock_event",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_vclock.c:ptp_vclock_refresh",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/sock.c:sock_gettstamp",
        "net/ipv4/tcp.c:tcp_update_recv_tstamps",
        "net/ipv4/tcp.c:tcp_update_recv_tstamps",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580295856,
      "name": "ns_to_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580507253,
      "name": "ns_to_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:506",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_get_tai_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/pstore/platform.c:pstore_dump",
        "drivers/dma-buf/sync_debug.c:sync_print_fence",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/rtc/lib.c:rtc_ktime_to_tm",
        "drivers/ptp/ptp_clock.c:ptp_clock_event",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_vclock.c:ptp_vclock_refresh",
        "drivers/ptp/ptp_vclock.c:ptp_vclock_gettimex",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/sock.c:sock_gettstamp",
        "net/ipv4/tcp.c:tcp_update_recv_tstamps",
        "net/ipv4/tcp.c:tcp_update_recv_tstamps",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580504624,
      "name": "ns_to_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec64 ns_to_timespec64(s64 nsec)
```

```json
{
  "name": "ns_to_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580761045,
      "name": "ns_to_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:506",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_get_tai_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/pstore/platform.c:pstore_dump",
        "drivers/dma-buf/sync_debug.c:sync_print_fence",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/rtc/lib.c:rtc_ktime_to_tm",
        "drivers/ptp/ptp_clock.c:ptp_clock_event",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_vclock.c:ptp_vclock_refresh",
        "drivers/ptp/ptp_vclock.c:ptp_vclock_gettimex",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/sock.c:sock_gettstamp",
        "net/ipv4/tcp.c:tcp_update_recv_tstamps",
        "net/ipv4/tcp.c:tcp_update_recv_tstamps",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580758096,
      "name": "ns_to_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec64 ns_to_timespec64(s64 nsec)
```

```json
{
  "name": "ns_to_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580843717,
      "name": "ns_to_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:506",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_get_tai_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/pstore/platform.c:pstore_record_init",
        "drivers/dma-buf/sync_debug.c:sync_print_fence",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/rtc/lib.c:rtc_ktime_to_tm",
        "drivers/ptp/ptp_clock.c:ptp_clock_event",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_vclock.c:ptp_vclock_refresh",
        "drivers/ptp/ptp_vclock.c:ptp_vclock_gettimex",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/sock.c:sock_gettstamp",
        "net/ipv4/tcp.c:tcp_update_recv_tstamps",
        "net/ipv4/tcp.c:tcp_update_recv_tstamps",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580840768,
      "name": "ns_to_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec64 ns_to_timespec64(s64 nsec)
```

```json
{
  "name": "ns_to_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580933109,
      "name": "ns_to_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:523",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_get_tai_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/pstore/platform.c:pstore_record_init",
        "drivers/dma-buf/sync_debug.c:sync_print_fence",
        "drivers/gpu/drm/drm_vblank.c:drm_wait_vblank_ioctl",
        "drivers/gpu/drm/drm_vblank.c:drm_wait_vblank_ioctl",
        "drivers/gpu/drm/drm_vblank.c:send_vblank_event",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_helper_get_vblank_timestamp_internal",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_helper_get_vblank_timestamp_internal",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/rtc/lib.c:rtc_ktime_to_tm",
        "drivers/ptp/ptp_clock.c:ptp_clock_event",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_vclock.c:ptp_vclock_refresh",
        "drivers/ptp/ptp_vclock.c:ptp_vclock_gettimex",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/sock.c:sock_gettstamp",
        "net/ipv4/tcp.c:tcp_update_recv_tstamps",
        "net/ipv4/tcp.c:tcp_update_recv_tstamps",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580930160,
      "name": "ns_to_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491311592,
      "name": "ns_to_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:551",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": [
        "kernel/sys.c:do_sysinfo",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_clock_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/pstore/platform.c:pstore_record_init",
        "drivers/dma-buf/sync_debug.c:sync_print_fence",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_gettime",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/rtc/lib.c:rtc_ktime_to_tm",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/sock.c:sock_gettstamp",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491311840,
      "name": "ns_to_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225307920,
      "name": "ns_to_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:551",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": [
        "kernel/sys.c:__se_sys_sysinfo",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_clock_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/pstore/platform.c:pstore_record_init",
        "drivers/dma-buf/sync_debug.c:sync_print_fence",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_gettime",
        "drivers/net/ethernet/ti/cpts.c:cpts_overflow_check",
        "drivers/net/ethernet/ti/cpts.c:cpts_ptp_gettime",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/rtc/lib.c:rtc_ktime_to_tm",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/sock.c:sock_gettstamp",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225308052,
      "name": "ns_to_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284239208,
      "name": "ns_to_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:551",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": [
        "arch/powerpc/xmon/xmon.c:show_uptime",
        "kernel/sys.c:do_sysinfo",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_clock_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/pstore/platform.c:pstore_record_init",
        "drivers/dma-buf/sync_debug.c:sync_print_fence",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/rtc/lib.c:rtc_ktime_to_tm",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/sock.c:sock_gettstamp",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284239360,
      "name": "ns_to_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271821012,
      "name": "ns_to_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:551",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": [
        "kernel/sys.c:__do_sys_sysinfo",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_clock_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "fs/timerfd.c:__se_sys_timerfd_gettime",
        "fs/timerfd.c:__se_sys_timerfd_gettime",
        "fs/timerfd.c:__se_sys_timerfd_settime",
        "fs/timerfd.c:__se_sys_timerfd_settime",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/pstore/platform.c:pstore_record_init",
        "drivers/dma-buf/sync_debug.c:sync_print_fence",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/rtc/lib.c:rtc_ktime_to_tm",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/sock.c:sock_gettstamp",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271821066,
      "name": "ns_to_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580071525,
      "name": "ns_to_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:551",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": [
        "kernel/sys.c:do_sysinfo",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_clock_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/pstore/platform.c:pstore_record_init",
        "drivers/dma-buf/sync_debug.c:sync_print_fence",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/rtc/lib.c:rtc_ktime_to_tm",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/sock.c:sock_gettstamp",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071648,
      "name": "ns_to_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580016341,
      "name": "ns_to_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:551",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": [
        "kernel/sys.c:do_sysinfo",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_clock_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/pstore/platform.c:pstore_record_init",
        "drivers/dma-buf/sync_debug.c:sync_print_fence",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/rtc/lib.c:rtc_ktime_to_tm",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/sock.c:sock_gettstamp",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016464,
      "name": "ns_to_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580062597,
      "name": "ns_to_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:551",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": [
        "kernel/sys.c:do_sysinfo",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_clock_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/pstore/platform.c:pstore_record_init",
        "drivers/dma-buf/sync_debug.c:sync_print_fence",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/rtc/lib.c:rtc_ktime_to_tm",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/sock.c:sock_gettstamp",
        "net/netfilter/nfnetlink_log.c:__build_packet_message",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062720,
      "name": "ns_to_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580113365,
      "name": "ns_to_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:551",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": [
        "kernel/sys.c:do_sysinfo",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_clock_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/pstore/platform.c:pstore_record_init",
        "drivers/dma-buf/sync_debug.c:sync_print_fence",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/rtc/lib.c:rtc_ktime_to_tm",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/sock.c:sock_gettstamp",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580113488,
      "name": "ns_to_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct timespec ns_to_timespec64(const s64 nsec)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct timespec</code> ➡️ <code>struct timespec64</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const s64 nsec</code> ➡️ <code>s64 nsec</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
