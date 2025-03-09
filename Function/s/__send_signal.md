# Function: <code>__send_signal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __send_signal(int sig, struct siginfo * info, struct task_struct * t, int group, int from_ancestor_ns)
```

```json
{
  "name": "__send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579427808,
      "name": "__send_signal",
      "external": false,
      "loc": "kernel/signal.c:972",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:send_signal",
        "kernel/signal.c:kill_pid_info_as_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579427808,
      "name": "__send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1093
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __send_signal(int sig, struct siginfo * info, struct task_struct * t, int group, int from_ancestor_ns)
```

```json
{
  "name": "__send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579440224,
      "name": "__send_signal",
      "external": false,
      "loc": "kernel/signal.c:972",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_info_as_cred",
        "kernel/signal.c:send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579440224,
      "name": "__send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __send_signal(int sig, struct siginfo * info, struct task_struct * t, int group, int from_ancestor_ns)
```

```json
{
  "name": "__send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579460592,
      "name": "__send_signal",
      "external": false,
      "loc": "kernel/signal.c:978",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_info_as_cred",
        "kernel/signal.c:send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579460592,
      "name": "__send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __send_signal(int sig, struct siginfo * info, struct task_struct * t, int group, int from_ancestor_ns)
```

```json
{
  "name": "__send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579449024,
      "name": "__send_signal",
      "external": false,
      "loc": "kernel/signal.c:992",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_info_as_cred",
        "kernel/signal.c:send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579449024,
      "name": "__send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __send_signal(int sig, struct siginfo * info, struct task_struct * t, int group, int from_ancestor_ns)
```

```json
{
  "name": "__send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579477424,
      "name": "__send_signal",
      "external": false,
      "loc": "kernel/signal.c:994",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_info_as_cred",
        "kernel/signal.c:send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579477424,
      "name": "__send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __send_signal(int sig, struct siginfo * info, struct task_struct * t, int group, int from_ancestor_ns)
```

```json
{
  "name": "__send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579493568,
      "name": "__send_signal",
      "external": false,
      "loc": "kernel/signal.c:1000",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_info_as_cred",
        "kernel/signal.c:send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493568,
      "name": "__send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1184
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
int __send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type, int from_ancestor_ns)
```

```json
{
  "name": "__send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579527136,
      "name": "__send_signal",
      "external": false,
      "loc": "kernel/signal.c:1075",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_info_as_cred",
        "kernel/signal.c:send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579527136,
      "name": "__send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1161
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
int __send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type, bool force)
```

```json
{
  "name": "__send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579546896,
      "name": "__send_signal",
      "external": false,
      "loc": "kernel/signal.c:1065",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig",
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546896,
      "name": "__send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 998
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
int __send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type, bool force)
```

```json
{
  "name": "__send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579573024,
      "name": "__send_signal",
      "external": false,
      "loc": "kernel/signal.c:1070",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig",
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579573024,
      "name": "__send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 998
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
int __send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type, bool force)
```

```json
{
  "name": "__send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579607344,
      "name": "__send_signal",
      "external": false,
      "loc": "kernel/signal.c:1070",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579607344,
      "name": "__send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 983
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
int __send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type, bool force)
```

```json
{
  "name": "__send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579587552,
      "name": "__send_signal",
      "external": false,
      "loc": "kernel/signal.c:1071",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587552,
      "name": "__send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 976
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
int __send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type, bool force)
```

```json
{
  "name": "__send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579594704,
      "name": "__send_signal",
      "external": false,
      "loc": "kernel/signal.c:1070",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579594704,
      "name": "__send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 984
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
int __send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type, bool force)
```

```json
{
  "name": "__send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__send_signal",
      "external": false,
      "loc": "kernel/signal.c:1071",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579666000,
      "name": "__send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1041
    },
    {
      "addr": 18446744071592101761,
      "name": "__send_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type, bool force)
```

```json
{
  "name": "__send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490735480,
      "name": "__send_signal",
      "external": false,
      "loc": "kernel/signal.c:1070",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig",
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490735480,
      "name": "__send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 916
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
int __send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type, bool force)
```

```json
{
  "name": "__send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224787716,
      "name": "__send_signal",
      "external": false,
      "loc": "kernel/signal.c:1070",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig",
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224787716,
      "name": "__send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1052
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
int __send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type, bool force)
```

```json
{
  "name": "__send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283558944,
      "name": "__send_signal",
      "external": false,
      "loc": "kernel/signal.c:1070",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig",
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283558944,
      "name": "__send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1192
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
int __send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type, bool force)
```

```json
{
  "name": "__send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271444380,
      "name": "__send_signal",
      "external": false,
      "loc": "kernel/signal.c:1070",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271444380,
      "name": "__send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
int __send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type, bool force)
```

```json
{
  "name": "__send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579549328,
      "name": "__send_signal",
      "external": false,
      "loc": "kernel/signal.c:1070",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig",
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549328,
      "name": "__send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 998
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
int __send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type, bool force)
```

```json
{
  "name": "__send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579478048,
      "name": "__send_signal",
      "external": false,
      "loc": "kernel/signal.c:1070",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig",
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579478048,
      "name": "__send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 998
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
int __send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type, bool force)
```

```json
{
  "name": "__send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579546608,
      "name": "__send_signal",
      "external": false,
      "loc": "kernel/signal.c:1070",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig",
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546608,
      "name": "__send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 998
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
int __send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type, bool force)
```

```json
{
  "name": "__send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579579600,
      "name": "__send_signal",
      "external": false,
      "loc": "kernel/signal.c:1070",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig",
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579579600,
      "name": "__send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1059
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
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum pid_type type</code>
</li>
<li>
<b>Param removed. </b>
<code>int group</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct siginfo * info</code> ➡️ <code>struct kernel_siginfo * info</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool force</code>
</li>
<li>
<b>Param removed. </b>
<code>int from_ancestor_ns</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int __send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type, bool force)
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
