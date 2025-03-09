# Function: <code>__ia32_sys_epoll_ctl</code>

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
long int __ia32_sys_epoll_ctl(const struct pt_regs * regs)
```

```json
{
  "name": "__ia32_sys_epoll_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581908464,
      "name": "__ia32_sys_epoll_ctl",
      "external": true,
      "loc": "fs/eventpoll.c:1999",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581908464,
      "name": "__ia32_sys_epoll_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1537
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
long int __ia32_sys_epoll_ctl(const struct pt_regs * regs)
```

```json
{
  "name": "__ia32_sys_epoll_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581990976,
      "name": "__ia32_sys_epoll_ctl",
      "external": true,
      "loc": "fs/eventpoll.c:2025",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581990976,
      "name": "__ia32_sys_epoll_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1513
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
long int __ia32_sys_epoll_ctl(const struct pt_regs * regs)
```

```json
{
  "name": "__ia32_sys_epoll_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582126272,
      "name": "__ia32_sys_epoll_ctl",
      "external": true,
      "loc": "fs/eventpoll.c:2103",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582126272,
      "name": "__ia32_sys_epoll_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2103
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
long int __ia32_sys_epoll_ctl(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_epoll_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579671104,
      "name": "__ia32_sys_epoll_ctl",
      "external": true,
      "loc": "kernel/sys_ni.c:68",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582207664,
      "name": "__ia32_sys_epoll_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2103
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
long int __ia32_sys_epoll_ctl(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_epoll_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582446256,
      "name": "__ia32_sys_epoll_ctl",
      "external": true,
      "loc": "kernel/sys_ni.c:68",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582446256,
      "name": "__ia32_sys_epoll_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
long int __ia32_sys_epoll_ctl(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_epoll_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582502944,
      "name": "__ia32_sys_epoll_ctl",
      "external": true,
      "loc": "kernel/sys_ni.c:68",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582502944,
      "name": "__ia32_sys_epoll_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
long int __ia32_sys_epoll_ctl(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_epoll_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582530368,
      "name": "__ia32_sys_epoll_ctl",
      "external": true,
      "loc": "kernel/sys_ni.c:68",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582530368,
      "name": "__ia32_sys_epoll_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
long int __ia32_sys_epoll_ctl(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_epoll_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582846432,
      "name": "__ia32_sys_epoll_ctl",
      "external": true,
      "loc": "kernel/sys_ni.c:68",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582846432,
      "name": "__ia32_sys_epoll_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
long int __ia32_sys_epoll_ctl(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_epoll_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583408048,
      "name": "__ia32_sys_epoll_ctl",
      "external": true,
      "loc": "kernel/sys_ni.c:68",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583408048,
      "name": "__ia32_sys_epoll_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
long int __ia32_sys_epoll_ctl(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_epoll_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583994928,
      "name": "__ia32_sys_epoll_ctl",
      "external": true,
      "loc": "kernel/sys_ni.c:68",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583994928,
      "name": "__ia32_sys_epoll_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
long int __ia32_sys_epoll_ctl(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_epoll_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584219600,
      "name": "__ia32_sys_epoll_ctl",
      "external": true,
      "loc": "kernel/sys_ni.c:58",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584219600,
      "name": "__ia32_sys_epoll_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
long int __ia32_sys_epoll_ctl(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_epoll_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584434144,
      "name": "__ia32_sys_epoll_ctl",
      "external": true,
      "loc": "kernel/sys_ni.c:56",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/syscall_32.c:ia32_sys_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584434144,
      "name": "__ia32_sys_epoll_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int __ia32_sys_epoll_ctl(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_epoll_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579647424,
      "name": "__ia32_sys_epoll_ctl",
      "external": true,
      "loc": "kernel/sys_ni.c:68",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582176400,
      "name": "__ia32_sys_epoll_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2103
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
long int __ia32_sys_epoll_ctl(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_epoll_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579575776,
      "name": "__ia32_sys_epoll_ctl",
      "external": true,
      "loc": "kernel/sys_ni.c:68",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582111648,
      "name": "__ia32_sys_epoll_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2240
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
long int __ia32_sys_epoll_ctl(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_epoll_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579644688,
      "name": "__ia32_sys_epoll_ctl",
      "external": true,
      "loc": "kernel/sys_ni.c:68",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582166880,
      "name": "__ia32_sys_epoll_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2103
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
long int __ia32_sys_epoll_ctl(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_epoll_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579678544,
      "name": "__ia32_sys_epoll_ctl",
      "external": true,
      "loc": "kernel/sys_ni.c:68",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582235536,
      "name": "__ia32_sys_epoll_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4178
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
long int __ia32_sys_epoll_ctl(const struct pt_regs * regs)
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct pt_regs * __unused</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct pt_regs * regs</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long int __ia32_sys_epoll_ctl(const struct pt_regs * __unused)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int __ia32_sys_epoll_ctl(const struct pt_regs * __unused)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long int __ia32_sys_epoll_ctl(const struct pt_regs * __unused)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int __ia32_sys_epoll_ctl(const struct pt_regs * __unused)
```
</details>
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
