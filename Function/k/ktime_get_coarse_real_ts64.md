# Function: <code>ktime_get_coarse_real_ts64</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_coarse_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579989536,
      "name": "ktime_get_coarse_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2136",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/auditsc.c:__audit_syscall_entry",
        "fs/inode.c:current_time",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579989536,
      "name": "ktime_get_coarse_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_coarse_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580036160,
      "name": "ktime_get_coarse_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2150",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/auditsc.c:__audit_syscall_entry",
        "fs/inode.c:current_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580036160,
      "name": "ktime_get_coarse_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_coarse_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580078736,
      "name": "ktime_get_coarse_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2160",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/auditsc.c:__audit_syscall_entry",
        "fs/inode.c:current_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580078736,
      "name": "ktime_get_coarse_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_coarse_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580127792,
      "name": "ktime_get_coarse_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2160",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/auditsc.c:__audit_syscall_entry",
        "fs/inode.c:current_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580127792,
      "name": "ktime_get_coarse_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_coarse_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580188288,
      "name": "ktime_get_coarse_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2159",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:__audit_syscall_entry",
        "fs/inode.c:current_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580188288,
      "name": "ktime_get_coarse_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_coarse_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580172976,
      "name": "ktime_get_coarse_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2222",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:__audit_syscall_entry",
        "fs/inode.c:current_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580172976,
      "name": "ktime_get_coarse_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_coarse_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580177472,
      "name": "ktime_get_coarse_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2233",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:__audit_syscall_entry",
        "fs/inode.c:current_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580177472,
      "name": "ktime_get_coarse_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_coarse_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_coarse_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2234",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:__audit_syscall_entry",
        "fs/inode.c:current_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592152140,
      "name": "ktime_get_coarse_real_ts64.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580325584,
      "name": "ktime_get_coarse_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_coarse_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_coarse_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2255",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/audit.c:audit_log_start",
        "kernel/auditsc.c:__audit_syscall_entry",
        "kernel/auditsc.c:__audit_uring_entry",
        "fs/inode.c:current_time",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593927140,
      "name": "ktime_get_coarse_real_ts64.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580537744,
      "name": "ktime_get_coarse_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_coarse_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_coarse_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2255",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/audit.c:audit_log_start",
        "kernel/auditsc.c:__audit_syscall_entry",
        "kernel/auditsc.c:__audit_uring_entry",
        "fs/inode.c:current_time",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595995185,
      "name": "ktime_get_coarse_real_ts64.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580794528,
      "name": "ktime_get_coarse_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_coarse_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_coarse_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2255",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/audit.c:audit_log_start",
        "kernel/auditsc.c:__audit_syscall_entry",
        "kernel/auditsc.c:__audit_uring_entry",
        "fs/inode.c:current_time",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596513411,
      "name": "ktime_get_coarse_real_ts64.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580877120,
      "name": "ktime_get_coarse_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_coarse_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_coarse_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2255",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/audit.c:audit_log_start",
        "kernel/auditsc.c:__audit_syscall_entry",
        "kernel/auditsc.c:__audit_uring_entry",
        "fs/inode.c:inode_needs_update_time",
        "fs/inode.c:inode_update_timestamps",
        "fs/inode.c:inode_update_timestamps",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597412738,
      "name": "ktime_get_coarse_real_ts64.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580967552,
      "name": "ktime_get_coarse_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_coarse_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491347400,
      "name": "ktime_get_coarse_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2160",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/auditsc.c:__audit_syscall_entry",
        "fs/inode.c:current_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491347400,
      "name": "ktime_get_coarse_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_coarse_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225340612,
      "name": "ktime_get_coarse_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2160",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/auditsc.c:__audit_syscall_entry",
        "fs/inode.c:current_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225340612,
      "name": "ktime_get_coarse_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_coarse_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284278032,
      "name": "ktime_get_coarse_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2160",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/auditsc.c:__audit_syscall_entry",
        "fs/inode.c:current_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284278032,
      "name": "ktime_get_coarse_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_coarse_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271841968,
      "name": "ktime_get_coarse_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2160",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/auditsc.c:__audit_syscall_entry",
        "fs/inode.c:current_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271841968,
      "name": "ktime_get_coarse_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_coarse_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580096992,
      "name": "ktime_get_coarse_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2160",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/auditsc.c:__audit_syscall_entry",
        "fs/inode.c:current_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580096992,
      "name": "ktime_get_coarse_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_coarse_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580042304,
      "name": "ktime_get_coarse_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2160",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/auditsc.c:__audit_syscall_entry",
        "fs/inode.c:current_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580042304,
      "name": "ktime_get_coarse_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_coarse_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580088064,
      "name": "ktime_get_coarse_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2160",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/auditsc.c:__audit_syscall_entry",
        "fs/inode.c:current_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580088064,
      "name": "ktime_get_coarse_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_coarse_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580139808,
      "name": "ktime_get_coarse_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2160",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/auditsc.c:__audit_syscall_entry",
        "fs/inode.c:current_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580139808,
      "name": "ktime_get_coarse_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 * ts)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
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
