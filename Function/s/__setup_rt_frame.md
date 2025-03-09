# Function: <code>__setup_rt_frame</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579035310,
      "name": "__setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:406",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
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
  "name": "__setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579031125,
      "name": "__setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:455",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
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
  "name": "__setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579030748,
      "name": "__setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:456",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
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
  "name": "__setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579023158,
      "name": "__setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:457",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
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
  "name": "__setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579026524,
      "name": "__setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:458",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579031944,
      "name": "__setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:459",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579036617,
      "name": "__setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:459",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __setup_rt_frame(int sig, struct ksignal * ksig, sigset_t * set, struct pt_regs * regs)
```

```json
{
  "name": "__setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579043792,
      "name": "__setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:456",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579043792,
      "name": "__setup_rt_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579046681,
      "name": "__setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:456",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
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
int __setup_rt_frame(int sig, struct ksignal * ksig, sigset_t * set, struct pt_regs * regs)
```

```json
{
  "name": "__setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579055568,
      "name": "__setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:438",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:setup_rt_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579055568,
      "name": "__setup_rt_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 855
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
int __setup_rt_frame(int sig, struct ksignal * ksig, sigset_t * set, struct pt_regs * regs)
```

```json
{
  "name": "__setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579058224,
      "name": "__setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:439",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:setup_rt_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579058224,
      "name": "__setup_rt_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 865
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
int __setup_rt_frame(int sig, struct ksignal * ksig, sigset_t * set, struct pt_regs * regs)
```

```json
{
  "name": "__setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579065104,
      "name": "__setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:455",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:handle_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579065104,
      "name": "__setup_rt_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 843
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
int __setup_rt_frame(int sig, struct ksignal * ksig, sigset_t * set, struct pt_regs * regs)
```

```json
{
  "name": "__setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579086272,
      "name": "__setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:460",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:handle_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579086272,
      "name": "__setup_rt_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 791
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
int __setup_rt_frame(int sig, struct ksignal * ksig, sigset_t * set, struct pt_regs * regs)
```

```json
{
  "name": "__setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579114816,
      "name": "__setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:461",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:handle_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579114816,
      "name": "__setup_rt_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 800
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579047033,
      "name": "__setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:456",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
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
  "name": "__setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578979974,
      "name": "__setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:456",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
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
  "name": "__setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579046617,
      "name": "__setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:456",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
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
  "name": "__setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579050374,
      "name": "__setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:456",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int __setup_rt_frame(int sig, struct ksignal * ksig, sigset_t * set, struct pt_regs * regs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
int __setup_rt_frame(int sig, struct ksignal * ksig, sigset_t * set, struct pt_regs * regs)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __setup_rt_frame(int sig, struct ksignal * ksig, sigset_t * set, struct pt_regs * regs)
```
</details>
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
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int __setup_rt_frame(int sig, struct ksignal * ksig, sigset_t * set, struct pt_regs * regs)
```
</details>
</li>
</ul>
