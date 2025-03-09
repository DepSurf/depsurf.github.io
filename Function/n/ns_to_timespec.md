# Function: <code>ns_to_timespec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec ns_to_timespec(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579807930,
      "name": "ns_to_timespec",
      "external": true,
      "loc": "kernel/time/time.c:389",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": [
        "kernel/sys.c:do_sysinfo",
        "kernel/time/hrtimer.c:update_rmtp",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-cpu-timers.c:sample_to_timespec",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/alarmtimer.c:alarm_timer_get",
        "kernel/time/alarmtimer.c:alarm_timer_get",
        "kernel/time/alarmtimer.c:alarm_clock_get",
        "kernel/time/alarmtimer.c:update_rmtp",
        "kernel/time/timer_stats.c:tstats_show",
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/rtc/rtc-lib.c:rtc_ktime_to_tm",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_get_timestampns",
        "net/core/sock.c:sock_get_timestampns",
        "net/compat.c:compat_sock_get_timestampns",
        "net/compat.c:compat_sock_get_timestampns",
        "net/packet/af_packet.c:tpacket_get_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579808096,
      "name": "ns_to_timespec",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec ns_to_timespec(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579835786,
      "name": "ns_to_timespec",
      "external": true,
      "loc": "kernel/time/time.c:396",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": [
        "kernel/sys.c:do_sysinfo",
        "kernel/time/hrtimer.c:update_rmtp",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:sample_to_timespec",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/alarmtimer.c:update_rmtp",
        "kernel/time/alarmtimer.c:alarm_timer_get",
        "kernel/time/alarmtimer.c:alarm_timer_get",
        "kernel/time/alarmtimer.c:alarm_clock_get",
        "kernel/time/timer_stats.c:tstats_show",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/rtc/rtc-lib.c:rtc_ktime_to_tm",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_get_timestampns",
        "net/core/sock.c:sock_get_timestampns",
        "net/compat.c:compat_sock_get_timestampns",
        "net/compat.c:compat_sock_get_timestampns",
        "net/packet/af_packet.c:tpacket_get_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579835904,
      "name": "ns_to_timespec",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec ns_to_timespec(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579864842,
      "name": "ns_to_timespec",
      "external": true,
      "loc": "kernel/time/time.c:396",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": [
        "kernel/sys.c:do_sysinfo",
        "kernel/time/hrtimer.c:update_rmtp",
        "kernel/time/timekeeping.c:getboottime64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/alarmtimer.c:update_rmtp",
        "kernel/time/alarmtimer.c:alarm_timer_get",
        "kernel/time/alarmtimer.c:alarm_timer_get",
        "kernel/time/alarmtimer.c:alarm_clock_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/time/posix-timers.c:posix_get_coarse_res",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:sample_to_timespec",
        "kernel/time/timer_stats.c:tstats_show",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/dma-buf/sync_debug.c:sync_print_fence",
        "drivers/rtc/rtc-lib.c:rtc_ktime_to_tm",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_get_timestampns",
        "net/core/sock.c:sock_get_timestampns",
        "net/compat.c:compat_sock_get_timestampns",
        "net/compat.c:compat_sock_get_timestampns",
        "net/packet/af_packet.c:tpacket_get_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579864960,
      "name": "ns_to_timespec",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec ns_to_timespec(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579873706,
      "name": "ns_to_timespec",
      "external": true,
      "loc": "kernel/time/time.c:486",
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
        "drivers/dma-buf/sync_debug.c:sync_print_fence",
        "drivers/rtc/rtc-lib.c:rtc_ktime_to_tm",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_get_timestampns",
        "net/core/sock.c:sock_get_timestampns",
        "net/compat.c:compat_sock_get_timestampns",
        "net/compat.c:compat_sock_get_timestampns",
        "net/packet/af_packet.c:tpacket_get_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579873840,
      "name": "ns_to_timespec",
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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec ns_to_timespec(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579962773,
      "name": "ns_to_timespec",
      "external": true,
      "loc": "kernel/time/time.c:454",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": [
        "kernel/sys.c:do_sysinfo",
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "fs/proc/uptime.c:uptime_proc_show",
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
      "addr": 18446744071579963392,
      "name": "ns_to_timespec",
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
struct timespec ns_to_timespec(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580009829,
      "name": "ns_to_timespec",
      "external": true,
      "loc": "kernel/time/time.c:392",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_timeval",
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": [
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_get_timestampns",
        "net/core/sock.c:sock_get_timestampns",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/packet/af_packet.c:tpacket_get_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580010176,
      "name": "ns_to_timespec",
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
struct timespec ns_to_timespec(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580053141,
      "name": "ns_to_timespec",
      "external": true,
      "loc": "kernel/time/time.c:460",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_timeval",
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": [
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "net/socket.c:__sock_recv_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580053488,
      "name": "ns_to_timespec",
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
struct timespec ns_to_timespec(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580102197,
      "name": "ns_to_timespec",
      "external": true,
      "loc": "kernel/time/time.c:460",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_timeval",
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": [
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "net/socket.c:__sock_recv_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580102544,
      "name": "ns_to_timespec",
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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct timespec ns_to_timespec(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491311440,
      "name": "ns_to_timespec",
      "external": true,
      "loc": "kernel/time/time.c:460",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_timeval",
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": [
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "net/socket.c:__sock_recv_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491311720,
      "name": "ns_to_timespec",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
struct timespec ns_to_timespec(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225307772,
      "name": "ns_to_timespec",
      "external": true,
      "loc": "kernel/time/time.c:460",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": [
        "kernel/time/time.c:ns_to_timeval",
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "sound/core/pcm_lib.c:update_audio_tstamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225307444,
      "name": "ns_to_timespec.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 3225307584,
      "name": "ns_to_timespec",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct timespec ns_to_timespec(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284239048,
      "name": "ns_to_timespec",
      "external": true,
      "loc": "kernel/time/time.c:460",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_timeval",
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": [
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "net/socket.c:__sock_recv_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284239488,
      "name": "ns_to_timespec",
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
struct timespec ns_to_timespec(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271820936,
      "name": "ns_to_timespec",
      "external": true,
      "loc": "kernel/time/time.c:460",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_timeval",
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": [
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "net/socket.c:__sock_recv_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271821172,
      "name": "ns_to_timespec",
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
struct timespec ns_to_timespec(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580071397,
      "name": "ns_to_timespec",
      "external": true,
      "loc": "kernel/time/time.c:460",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_timeval",
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": [
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "net/socket.c:__sock_recv_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071744,
      "name": "ns_to_timespec",
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
struct timespec ns_to_timespec(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580016213,
      "name": "ns_to_timespec",
      "external": true,
      "loc": "kernel/time/time.c:460",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_timeval",
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": [
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "net/socket.c:__sock_recv_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016560,
      "name": "ns_to_timespec",
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
struct timespec ns_to_timespec(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580062469,
      "name": "ns_to_timespec",
      "external": true,
      "loc": "kernel/time/time.c:460",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_timeval",
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": [
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "net/socket.c:__sock_recv_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062816,
      "name": "ns_to_timespec",
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
struct timespec ns_to_timespec(const s64 nsec)
```

```json
{
  "name": "ns_to_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580113237,
      "name": "ns_to_timespec",
      "external": true,
      "loc": "kernel/time/time.c:460",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_timeval",
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": [
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_show",
        "net/socket.c:__sock_recv_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp",
        "net/packet/af_packet.c:tpacket_get_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580113584,
      "name": "ns_to_timespec",
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
struct timespec ns_to_timespec(const s64 nsec)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct timespec ns_to_timespec(const s64 nsec)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct timespec ns_to_timespec(const s64 nsec)
```
</details>
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
