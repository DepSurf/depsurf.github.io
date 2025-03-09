# Function: <code>pidfd_pid</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pid * pidfd_pid(const struct file * file)
```

```json
{
  "name": "pidfd_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579501168,
      "name": "pidfd_pid",
      "external": true,
      "loc": "kernel/fork.c:1682",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501168,
      "name": "pidfd_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct pid * pidfd_pid(const struct file * file)
```

```json
{
  "name": "pidfd_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579529552,
      "name": "pidfd_pid",
      "external": true,
      "loc": "kernel/fork.c:1707",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/pid.c:__ia32_sys_pidfd_getfd",
        "kernel/pid.c:__x64_sys_pidfd_getfd",
        "kernel/nsproxy.c:__do_sys_setns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579529552,
      "name": "pidfd_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct pid * pidfd_pid(const struct file * file)
```

```json
{
  "name": "pidfd_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579512352,
      "name": "pidfd_pid",
      "external": true,
      "loc": "kernel/fork.c:1703",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/pid.c:__ia32_sys_pidfd_getfd",
        "kernel/pid.c:__x64_sys_pidfd_getfd",
        "kernel/pid.c:pidfd_get_pid",
        "kernel/nsproxy.c:__do_sys_setns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579512352,
      "name": "pidfd_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct pid * pidfd_pid(const struct file * file)
```

```json
{
  "name": "pidfd_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579515424,
      "name": "pidfd_pid",
      "external": true,
      "loc": "kernel/fork.c:1702",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/pid.c:__ia32_sys_pidfd_getfd",
        "kernel/pid.c:__x64_sys_pidfd_getfd",
        "kernel/pid.c:pidfd_get_pid",
        "kernel/nsproxy.c:__do_sys_setns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579515424,
      "name": "pidfd_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct pid * pidfd_pid(const struct file * file)
```

```json
{
  "name": "pidfd_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579587136,
      "name": "pidfd_pid",
      "external": true,
      "loc": "kernel/fork.c:1781",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/pid.c:__ia32_sys_pidfd_getfd",
        "kernel/pid.c:__x64_sys_pidfd_getfd",
        "kernel/pid.c:pidfd_get_pid",
        "kernel/nsproxy.c:__do_sys_setns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587136,
      "name": "pidfd_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct pid * pidfd_pid(const struct file * file)
```

```json
{
  "name": "pidfd_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579678000,
      "name": "pidfd_pid",
      "external": true,
      "loc": "kernel/fork.c:1826",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/pid.c:__ia32_sys_pidfd_getfd",
        "kernel/pid.c:__x64_sys_pidfd_getfd",
        "kernel/pid.c:pidfd_get_pid",
        "kernel/nsproxy.c:__do_sys_setns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579678000,
      "name": "pidfd_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct pid * pidfd_pid(const struct file * file)
```

```json
{
  "name": "pidfd_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579798272,
      "name": "pidfd_pid",
      "external": true,
      "loc": "kernel/fork.c:1848",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/pid.c:__ia32_sys_pidfd_getfd",
        "kernel/pid.c:__x64_sys_pidfd_getfd",
        "kernel/pid.c:pidfd_get_pid",
        "kernel/nsproxy.c:__do_sys_setns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579798272,
      "name": "pidfd_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct pid * pidfd_pid(const struct file * file)
```

```json
{
  "name": "pidfd_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579840672,
      "name": "pidfd_pid",
      "external": true,
      "loc": "kernel/fork.c:1996",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/pid.c:__ia32_sys_pidfd_getfd",
        "kernel/pid.c:__x64_sys_pidfd_getfd",
        "kernel/pid.c:pidfd_get_pid",
        "kernel/nsproxy.c:__do_sys_setns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579840672,
      "name": "pidfd_pid",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pid * pidfd_pid(const struct file * file)
```

```json
{
  "name": "pidfd_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579878480,
      "name": "pidfd_pid",
      "external": true,
      "loc": "kernel/fork.c:1993",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/pid.c:__ia32_sys_pidfd_getfd",
        "kernel/pid.c:__x64_sys_pidfd_getfd",
        "kernel/pid.c:pidfd_get_pid",
        "kernel/nsproxy.c:__do_sys_setns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579878480,
      "name": "pidfd_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct pid * pidfd_pid(const struct file * file)
```

```json
{
  "name": "pidfd_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490633904,
      "name": "pidfd_pid",
      "external": true,
      "loc": "kernel/fork.c:1682",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/signal.c:__arm64_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490633904,
      "name": "pidfd_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct pid * pidfd_pid(const struct file * file)
```

```json
{
  "name": "pidfd_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224711800,
      "name": "pidfd_pid",
      "external": true,
      "loc": "kernel/fork.c:1682",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/signal.c:__se_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224711800,
      "name": "pidfd_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct pid * pidfd_pid(const struct file * file)
```

```json
{
  "name": "pidfd_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283452608,
      "name": "pidfd_pid",
      "external": true,
      "loc": "kernel/fork.c:1682",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/signal.c:__se_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283452608,
      "name": "pidfd_pid",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pid * pidfd_pid(const struct file * file)
```

```json
{
  "name": "pidfd_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271389304,
      "name": "pidfd_pid",
      "external": true,
      "loc": "kernel/fork.c:1682",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/signal.c:__se_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271389304,
      "name": "pidfd_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct pid * pidfd_pid(const struct file * file)
```

```json
{
  "name": "pidfd_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579474832,
      "name": "pidfd_pid",
      "external": true,
      "loc": "kernel/fork.c:1682",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579474832,
      "name": "pidfd_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct pid * pidfd_pid(const struct file * file)
```

```json
{
  "name": "pidfd_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579403728,
      "name": "pidfd_pid",
      "external": true,
      "loc": "kernel/fork.c:1682",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403728,
      "name": "pidfd_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct pid * pidfd_pid(const struct file * file)
```

```json
{
  "name": "pidfd_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579474752,
      "name": "pidfd_pid",
      "external": true,
      "loc": "kernel/fork.c:1682",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579474752,
      "name": "pidfd_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct pid * pidfd_pid(const struct file * file)
```

```json
{
  "name": "pidfd_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579506576,
      "name": "pidfd_pid",
      "external": true,
      "loc": "kernel/fork.c:1682",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506576,
      "name": "pidfd_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct pid * pidfd_pid(const struct file * file)
```
</details>
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
