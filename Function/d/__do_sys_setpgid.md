# Function: <code>__do_sys_setpgid</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_setpgid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579525155,
      "name": "__do_sys_setpgid",
      "external": false,
      "loc": "kernel/sys.c:1006",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid"
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
  "name": "__do_sys_setpgid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579551507,
      "name": "__do_sys_setpgid",
      "external": false,
      "loc": "kernel/sys.c:1006",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_setpgid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579584035,
      "name": "__do_sys_setpgid",
      "external": false,
      "loc": "kernel/sys.c:1006",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid"
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
  "name": "__do_sys_setpgid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579599779,
      "name": "__do_sys_setpgid",
      "external": false,
      "loc": "kernel/sys.c:1006",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid"
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
long int __do_sys_setpgid(pid_t pid, pid_t pgid)
```

```json
{
  "name": "__do_sys_setpgid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579630928,
      "name": "__do_sys_setpgid",
      "external": false,
      "loc": "kernel/sys.c:1020",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579630928,
      "name": "__do_sys_setpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
long int __do_sys_setpgid(pid_t pid, pid_t pgid)
```

```json
{
  "name": "__do_sys_setpgid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579610896,
      "name": "__do_sys_setpgid",
      "external": false,
      "loc": "kernel/sys.c:1021",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579610896,
      "name": "__do_sys_setpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
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
long int __do_sys_setpgid(pid_t pid, pid_t pgid)
```

```json
{
  "name": "__do_sys_setpgid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579617344,
      "name": "__do_sys_setpgid",
      "external": false,
      "loc": "kernel/sys.c:1038",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579617344,
      "name": "__do_sys_setpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
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
long int __do_sys_setpgid(pid_t pid, pid_t pgid)
```

```json
{
  "name": "__do_sys_setpgid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579693600,
      "name": "__do_sys_setpgid",
      "external": false,
      "loc": "kernel/sys.c:1047",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579693600,
      "name": "__do_sys_setpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
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
long int __do_sys_setpgid(pid_t pid, pid_t pgid)
```

```json
{
  "name": "__do_sys_setpgid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579794848,
      "name": "__do_sys_setpgid",
      "external": false,
      "loc": "kernel/sys.c:1054",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579794848,
      "name": "__do_sys_setpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
long int __do_sys_setpgid(pid_t pid, pid_t pgid)
```

```json
{
  "name": "__do_sys_setpgid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579929264,
      "name": "__do_sys_setpgid",
      "external": false,
      "loc": "kernel/sys.c:1055",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579929264,
      "name": "__do_sys_setpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
long int __do_sys_setpgid(pid_t pid, pid_t pgid)
```

```json
{
  "name": "__do_sys_setpgid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579979200,
      "name": "__do_sys_setpgid",
      "external": false,
      "loc": "kernel/sys.c:1073",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979200,
      "name": "__do_sys_setpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
long int __do_sys_setpgid(pid_t pid, pid_t pgid)
```

```json
{
  "name": "__do_sys_setpgid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580018608,
      "name": "__do_sys_setpgid",
      "external": false,
      "loc": "kernel/sys.c:1073",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580018608,
      "name": "__do_sys_setpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_setpgid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490764276,
      "name": "__do_sys_setpgid",
      "external": false,
      "loc": "kernel/sys.c:1006",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__arm64_sys_setpgid"
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
  "name": "__do_sys_setpgid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224817532,
      "name": "__do_sys_setpgid",
      "external": false,
      "loc": "kernel/sys.c:1006",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__se_sys_setpgid"
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
  "name": "__do_sys_setpgid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283591020,
      "name": "__do_sys_setpgid",
      "external": false,
      "loc": "kernel/sys.c:1006",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__se_sys_setpgid"
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
  "name": "__do_sys_setpgid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271465772,
      "name": "__do_sys_setpgid",
      "external": false,
      "loc": "kernel/sys.c:1006",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__se_sys_setpgid"
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
  "name": "__do_sys_setpgid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579576083,
      "name": "__do_sys_setpgid",
      "external": false,
      "loc": "kernel/sys.c:1006",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid"
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
  "name": "__do_sys_setpgid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579504695,
      "name": "__do_sys_setpgid",
      "external": false,
      "loc": "kernel/sys.c:1006",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid"
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
  "name": "__do_sys_setpgid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579573363,
      "name": "__do_sys_setpgid",
      "external": false,
      "loc": "kernel/sys.c:1006",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid"
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
  "name": "__do_sys_setpgid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579617331,
      "name": "__do_sys_setpgid",
      "external": false,
      "loc": "kernel/sys.c:1006",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long int __do_sys_setpgid(pid_t pid, pid_t pgid)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
