# Function: <code>kcmp_epoll_target</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kcmp_epoll_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579866344,
      "name": "kcmp_epoll_target",
      "external": false,
      "loc": "kernel/kcmp.c:102",
      "file": "kernel/kcmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:SyS_kcmp"
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
  "name": "kcmp_epoll_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579909992,
      "name": "kcmp_epoll_target",
      "external": false,
      "loc": "kernel/kcmp.c:103",
      "file": "kernel/kcmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:SyS_kcmp"
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
int kcmp_epoll_target(struct task_struct * task1, struct task_struct * task2, long unsigned int idx1, struct kcmp_epoll_slot * uslot)
```

```json
{
  "name": "kcmp_epoll_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579953472,
      "name": "kcmp_epoll_target",
      "external": false,
      "loc": "kernel/kcmp.c:103",
      "file": "kernel/kcmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kcmp.c:__ia32_sys_kcmp",
        "kernel/kcmp.c:__x64_sys_kcmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579953472,
      "name": "kcmp_epoll_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
int kcmp_epoll_target(struct task_struct * task1, struct task_struct * task2, long unsigned int idx1, struct kcmp_epoll_slot * uslot)
```

```json
{
  "name": "kcmp_epoll_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579999936,
      "name": "kcmp_epoll_target",
      "external": false,
      "loc": "kernel/kcmp.c:103",
      "file": "kernel/kcmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kcmp.c:__ia32_sys_kcmp",
        "kernel/kcmp.c:__x64_sys_kcmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579999936,
      "name": "kcmp_epoll_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
  "name": "kcmp_epoll_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580044137,
      "name": "kcmp_epoll_target",
      "external": false,
      "loc": "kernel/kcmp.c:103",
      "file": "kernel/kcmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp"
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
  "name": "kcmp_epoll_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580093225,
      "name": "kcmp_epoll_target",
      "external": false,
      "loc": "kernel/kcmp.c:103",
      "file": "kernel/kcmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp"
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
int kcmp_epoll_target(struct task_struct * task1, struct task_struct * task2, long unsigned int idx1, struct kcmp_epoll_slot * uslot)
```

```json
{
  "name": "kcmp_epoll_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580154768,
      "name": "kcmp_epoll_target",
      "external": false,
      "loc": "kernel/kcmp.c:103",
      "file": "kernel/kcmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kcmp.c:__do_sys_kcmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580154768,
      "name": "kcmp_epoll_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
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
int kcmp_epoll_target(struct task_struct * task1, struct task_struct * task2, long unsigned int idx1, struct kcmp_epoll_slot * uslot)
```

```json
{
  "name": "kcmp_epoll_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580139312,
      "name": "kcmp_epoll_target",
      "external": false,
      "loc": "kernel/kcmp.c:98",
      "file": "kernel/kcmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kcmp.c:__do_sys_kcmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580139312,
      "name": "kcmp_epoll_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
  "name": "kcmp_epoll_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580144750,
      "name": "kcmp_epoll_target",
      "external": false,
      "loc": "kernel/kcmp.c:98",
      "file": "kernel/kcmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp"
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
  "name": "kcmp_epoll_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580288494,
      "name": "kcmp_epoll_target",
      "external": false,
      "loc": "kernel/kcmp.c:98",
      "file": "kernel/kcmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp"
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
  "name": "kcmp_epoll_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580496795,
      "name": "kcmp_epoll_target",
      "external": false,
      "loc": "kernel/kcmp.c:98",
      "file": "kernel/kcmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp"
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
  "name": "kcmp_epoll_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580748763,
      "name": "kcmp_epoll_target",
      "external": false,
      "loc": "kernel/kcmp.c:98",
      "file": "kernel/kcmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp"
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
  "name": "kcmp_epoll_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580831525,
      "name": "kcmp_epoll_target",
      "external": false,
      "loc": "kernel/kcmp.c:98",
      "file": "kernel/kcmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp"
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
  "name": "kcmp_epoll_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580920949,
      "name": "kcmp_epoll_target",
      "external": false,
      "loc": "kernel/kcmp.c:100",
      "file": "kernel/kcmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int kcmp_epoll_target(struct task_struct * task1, struct task_struct * task2, long unsigned int idx1, struct kcmp_epoll_slot * uslot)
```

```json
{
  "name": "kcmp_epoll_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491301152,
      "name": "kcmp_epoll_target",
      "external": false,
      "loc": "kernel/kcmp.c:103",
      "file": "kernel/kcmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kcmp.c:__arm64_sys_kcmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491301152,
      "name": "kcmp_epoll_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "kcmp_epoll_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225300292,
      "name": "kcmp_epoll_target",
      "external": false,
      "loc": "kernel/kcmp.c:103",
      "file": "kernel/kcmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__se_sys_kcmp"
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
  "name": "kcmp_epoll_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284227184,
      "name": "kcmp_epoll_target",
      "external": false,
      "loc": "kernel/kcmp.c:103",
      "file": "kernel/kcmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__se_sys_kcmp"
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
  "name": "kcmp_epoll_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271813530,
      "name": "kcmp_epoll_target",
      "external": false,
      "loc": "kernel/kcmp.c:103",
      "file": "kernel/kcmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__se_sys_kcmp"
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
  "name": "kcmp_epoll_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580062425,
      "name": "kcmp_epoll_target",
      "external": false,
      "loc": "kernel/kcmp.c:103",
      "file": "kernel/kcmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp"
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
  "name": "kcmp_epoll_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580007273,
      "name": "kcmp_epoll_target",
      "external": false,
      "loc": "kernel/kcmp.c:103",
      "file": "kernel/kcmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp"
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
  "name": "kcmp_epoll_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580053497,
      "name": "kcmp_epoll_target",
      "external": false,
      "loc": "kernel/kcmp.c:103",
      "file": "kernel/kcmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp"
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
  "name": "kcmp_epoll_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580104255,
      "name": "kcmp_epoll_target",
      "external": false,
      "loc": "kernel/kcmp.c:103",
      "file": "kernel/kcmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp"
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
int kcmp_epoll_target(struct task_struct * task1, struct task_struct * task2, long unsigned int idx1, struct kcmp_epoll_slot * uslot)
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
int kcmp_epoll_target(struct task_struct * task1, struct task_struct * task2, long unsigned int idx1, struct kcmp_epoll_slot * uslot)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int kcmp_epoll_target(struct task_struct * task1, struct task_struct * task2, long unsigned int idx1, struct kcmp_epoll_slot * uslot)
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
int kcmp_epoll_target(struct task_struct * task1, struct task_struct * task2, long unsigned int idx1, struct kcmp_epoll_slot * uslot)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int kcmp_epoll_target(struct task_struct * task1, struct task_struct * task2, long unsigned int idx1, struct kcmp_epoll_slot * uslot)
```
</details>
</li>
</ul>
