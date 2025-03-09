# Function: <code>ep_loop_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581295338,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:1732",
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
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581461504,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:1761",
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
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581542288,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:1761",
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
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581595657,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:1922",
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
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581740162,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:1904",
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
int ep_loop_check(struct eventpoll * ep, struct file * file)
```

```json
{
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581901296,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:1906",
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
      "addr": 18446744071581901296,
      "name": "ep_loop_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
int ep_loop_check(struct eventpoll * ep, struct file * file)
```

```json
{
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581986144,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:1932",
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
      "addr": 18446744071581986144,
      "name": "ep_loop_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582127734,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:2010",
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
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582209126,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:2010",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582446055,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:2017",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582502805,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:1931",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582530048,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:1937",
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
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582846112,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:1938",
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
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583407422,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:1967",
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
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583994286,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:1969",
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
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584218957,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:2018",
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
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584433501,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:2009",
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
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493769696,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:2010",
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
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227287232,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:2010",
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
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287383388,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:2010",
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
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273369588,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:2010",
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
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582177862,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:2010",
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
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582113239,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:2010",
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
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582168342,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:2010",
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
  "name": "ep_loop_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582237695,
      "name": "ep_loop_check",
      "external": false,
      "loc": "fs/eventpoll.c:2010",
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
int ep_loop_check(struct eventpoll * ep, struct file * file)
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
int ep_loop_check(struct eventpoll * ep, struct file * file)
```
</details>
</li>
</ul>
