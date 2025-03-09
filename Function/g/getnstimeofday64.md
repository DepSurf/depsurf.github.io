# Function: <code>getnstimeofday64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void getnstimeofday64(struct timespec * ts)
```

```json
{
  "name": "getnstimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579851168,
      "name": "getnstimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:676",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:do_gettimeofday",
        "kernel/time/timekeeping.c:do_adjtimex"
      ],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_clock_realtime_get",
        "kernel/trace/blktrace.c:blk_trace_startstop",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/ip_options.c:ip_options_build",
        "net/packet/af_packet.c:prb_open_block",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851168,
      "name": "getnstimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void getnstimeofday64(struct timespec * ts)
```

```json
{
  "name": "getnstimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579884840,
      "name": "getnstimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:681",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:do_gettimeofday"
      ],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_clock_realtime_get",
        "kernel/trace/blktrace.c:blk_trace_startstop",
        "fs/kernfs/dir.c:__kernfs_remove",
        "fs/kernfs/dir.c:kernfs_add_one",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880128,
      "name": "getnstimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void getnstimeofday64(struct timespec * ts)
```

```json
{
  "name": "getnstimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579896600,
      "name": "getnstimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:710",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:do_gettimeofday"
      ],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_clock_realtime_get",
        "kernel/trace/blktrace.c:blk_trace_startstop",
        "fs/kernfs/dir.c:__kernfs_remove",
        "fs/kernfs/dir.c:kernfs_add_one",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892192,
      "name": "getnstimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void getnstimeofday64(struct timespec * ts)
```

```json
{
  "name": "getnstimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579905112,
      "name": "getnstimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:742",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:do_gettimeofday"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:do_gettimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_get",
        "kernel/auditsc.c:__audit_syscall_entry",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/blktrace.c:blk_trace_startstop",
        "fs/kernfs/dir.c:kernfs_add_one",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898048,
      "name": "getnstimeofday64.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579900720,
      "name": "getnstimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void getnstimeofday64(struct timespec * ts)
```

```json
{
  "name": "getnstimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579950164,
      "name": "getnstimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:746",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:do_gettimeofday"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:do_gettimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_get",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "fs/kernfs/dir.c:kernfs_add_one",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942640,
      "name": "getnstimeofday64.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579945520,
      "name": "getnstimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void getnstimeofday64(struct timespec * ts)
```
</details>
</li>
</ul>
