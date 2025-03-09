# Function: <code>ep_modify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581294411,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1392",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:SyS_epoll_ctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581460506,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1421",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:SyS_epoll_ctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581541290,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1421",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:SyS_epoll_ctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581594740,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1561",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:SyS_epoll_ctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581739243,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1543",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:SyS_epoll_ctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int ep_modify(struct eventpoll * ep, struct epitem * epi, const struct epoll_event * event)
```

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581903936,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1547",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581903936,
      "name": "ep_modify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
int ep_modify(struct eventpoll * ep, struct epitem * epi, const struct epoll_event * event)
```

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989472,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1551",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989472,
      "name": "ep_modify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582127528,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1629",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582208920,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1629",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int ep_modify(struct eventpoll * ep, struct epitem * epi, const struct epoll_event * event)
```

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582440864,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1622",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582440864,
      "name": "ep_modify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
int ep_modify(struct eventpoll * ep, struct epitem * epi, const struct epoll_event * event)
```

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582500704,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1550",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582500704,
      "name": "ep_modify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582529856,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1556",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:do_epoll_ctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582845920,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1558",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:do_epoll_ctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583407546,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1565",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:do_epoll_ctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583994410,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1567",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:do_epoll_ctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584219092,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1612",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:do_epoll_ctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584433636,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1603",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:do_epoll_ctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493769348,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1629",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:__do_sys_epoll_ctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227286980,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1629",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:__do_sys_epoll_ctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287383136,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1629",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:__se_sys_epoll_ctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273369402,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1629",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:__se_sys_epoll_ctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582177656,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1629",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582113014,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1629",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582168136,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1629",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582237444,
      "name": "ep_modify",
      "external": false,
      "loc": "fs/eventpoll.c:1629",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int ep_modify(struct eventpoll * ep, struct epitem * epi, const struct epoll_event * event)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int ep_modify(struct eventpoll * ep, struct epitem * epi, const struct epoll_event * event)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int ep_modify(struct eventpoll * ep, struct epitem * epi, const struct epoll_event * event)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int ep_modify(struct eventpoll * ep, struct epitem * epi, const struct epoll_event * event)
```
</details>
</li>
</ul>
