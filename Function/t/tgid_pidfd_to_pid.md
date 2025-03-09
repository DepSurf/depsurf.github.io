# Function: <code>tgid_pidfd_to_pid</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pid * tgid_pidfd_to_pid(const struct file * file)
```

```json
{
  "name": "tgid_pidfd_to_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582379088,
      "name": "tgid_pidfd_to_pid",
      "external": true,
      "loc": "fs/proc/base.c:3128",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582379088,
      "name": "tgid_pidfd_to_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct pid * tgid_pidfd_to_pid(const struct file * file)
```

```json
{
  "name": "tgid_pidfd_to_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582478000,
      "name": "tgid_pidfd_to_pid",
      "external": true,
      "loc": "fs/proc/base.c:3128",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582478000,
      "name": "tgid_pidfd_to_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct pid * tgid_pidfd_to_pid(const struct file * file)
```

```json
{
  "name": "tgid_pidfd_to_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582776608,
      "name": "tgid_pidfd_to_pid",
      "external": true,
      "loc": "fs/proc/base.c:3268",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582776608,
      "name": "tgid_pidfd_to_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct pid * tgid_pidfd_to_pid(const struct file * file)
```

```json
{
  "name": "tgid_pidfd_to_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582849968,
      "name": "tgid_pidfd_to_pid",
      "external": true,
      "loc": "fs/proc/base.c:3285",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582849968,
      "name": "tgid_pidfd_to_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct pid * tgid_pidfd_to_pid(const struct file * file)
```

```json
{
  "name": "tgid_pidfd_to_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582878368,
      "name": "tgid_pidfd_to_pid",
      "external": true,
      "loc": "fs/proc/base.c:3297",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582878368,
      "name": "tgid_pidfd_to_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pid * tgid_pidfd_to_pid(const struct file * file)
```

```json
{
  "name": "tgid_pidfd_to_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583211984,
      "name": "tgid_pidfd_to_pid",
      "external": true,
      "loc": "fs/proc/base.c:3303",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583211984,
      "name": "tgid_pidfd_to_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pid * tgid_pidfd_to_pid(const struct file * file)
```

```json
{
  "name": "tgid_pidfd_to_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583708880,
      "name": "tgid_pidfd_to_pid",
      "external": true,
      "loc": "fs/proc/base.c:3351",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583708880,
      "name": "tgid_pidfd_to_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pid * tgid_pidfd_to_pid(const struct file * file)
```

```json
{
  "name": "tgid_pidfd_to_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584319936,
      "name": "tgid_pidfd_to_pid",
      "external": true,
      "loc": "fs/proc/base.c:3367",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584319936,
      "name": "tgid_pidfd_to_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pid * tgid_pidfd_to_pid(const struct file * file)
```

```json
{
  "name": "tgid_pidfd_to_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584549888,
      "name": "tgid_pidfd_to_pid",
      "external": true,
      "loc": "fs/proc/base.c:3369",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584549888,
      "name": "tgid_pidfd_to_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pid * tgid_pidfd_to_pid(const struct file * file)
```

```json
{
  "name": "tgid_pidfd_to_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584781728,
      "name": "tgid_pidfd_to_pid",
      "external": true,
      "loc": "fs/proc/base.c:3376",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584781728,
      "name": "tgid_pidfd_to_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct pid * tgid_pidfd_to_pid(const struct file * file)
```

```json
{
  "name": "tgid_pidfd_to_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494098056,
      "name": "tgid_pidfd_to_pid",
      "external": true,
      "loc": "fs/proc/base.c:3128",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__arm64_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494098056,
      "name": "tgid_pidfd_to_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct pid * tgid_pidfd_to_pid(const struct file * file)
```

```json
{
  "name": "tgid_pidfd_to_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227549176,
      "name": "tgid_pidfd_to_pid",
      "external": true,
      "loc": "fs/proc/base.c:3128",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227549176,
      "name": "tgid_pidfd_to_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct pid * tgid_pidfd_to_pid(const struct file * file)
```

```json
{
  "name": "tgid_pidfd_to_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287766352,
      "name": "tgid_pidfd_to_pid",
      "external": true,
      "loc": "fs/proc/base.c:3128",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287766352,
      "name": "tgid_pidfd_to_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct pid * tgid_pidfd_to_pid(const struct file * file)
```

```json
{
  "name": "tgid_pidfd_to_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273584740,
      "name": "tgid_pidfd_to_pid",
      "external": true,
      "loc": "fs/proc/base.c:3128",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273584740,
      "name": "tgid_pidfd_to_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct pid * tgid_pidfd_to_pid(const struct file * file)
```

```json
{
  "name": "tgid_pidfd_to_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582446736,
      "name": "tgid_pidfd_to_pid",
      "external": true,
      "loc": "fs/proc/base.c:3128",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582446736,
      "name": "tgid_pidfd_to_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct pid * tgid_pidfd_to_pid(const struct file * file)
```

```json
{
  "name": "tgid_pidfd_to_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582383904,
      "name": "tgid_pidfd_to_pid",
      "external": true,
      "loc": "fs/proc/base.c:3128",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582383904,
      "name": "tgid_pidfd_to_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct pid * tgid_pidfd_to_pid(const struct file * file)
```

```json
{
  "name": "tgid_pidfd_to_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582437216,
      "name": "tgid_pidfd_to_pid",
      "external": true,
      "loc": "fs/proc/base.c:3128",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582437216,
      "name": "tgid_pidfd_to_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct pid * tgid_pidfd_to_pid(const struct file * file)
```

```json
{
  "name": "tgid_pidfd_to_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582517376,
      "name": "tgid_pidfd_to_pid",
      "external": true,
      "loc": "fs/proc/base.c:3128",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582517376,
      "name": "tgid_pidfd_to_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct pid * tgid_pidfd_to_pid(const struct file * file)
```
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
