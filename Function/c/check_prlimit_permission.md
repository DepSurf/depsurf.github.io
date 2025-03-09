# Function: <code>check_prlimit_permission</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579457530,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1442",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:SyS_prlimit64"
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
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579470746,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1442",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:SyS_prlimit64"
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
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579491146,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1443",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:SyS_prlimit64"
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
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579479209,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1547",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:SyS_prlimit64"
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
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579507081,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1554",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:SyS_prlimit64"
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
int check_prlimit_permission(struct task_struct * task, unsigned int flags)
```

```json
{
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579516544,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1608",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579516544,
      "name": "check_prlimit_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int check_prlimit_permission(struct task_struct * task, unsigned int flags)
```

```json
{
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579552848,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1609",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552848,
      "name": "check_prlimit_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579590752,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1609",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64"
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
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579616800,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1599",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64"
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
int check_prlimit_permission(struct task_struct * task, unsigned int flags)
```

```json
{
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579633056,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1615",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prlimit64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579633056,
      "name": "check_prlimit_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int check_prlimit_permission(struct task_struct * task, unsigned int flags)
```

```json
{
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579613264,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1616",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prlimit64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579613264,
      "name": "check_prlimit_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579634996,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1633",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_prlimit64"
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
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579711524,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1642",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_prlimit64"
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
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579802023,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1654",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_prlimit64"
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
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579940423,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1659",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_prlimit64"
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
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579990487,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1677",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_prlimit64"
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
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580029895,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1677",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_prlimit64"
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
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490783856,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1599",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__arm64_sys_prlimit64"
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
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224820512,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1599",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__se_sys_prlimit64"
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
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283609040,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1599",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__se_sys_prlimit64"
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
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271467632,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1599",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__se_sys_prlimit64"
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
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579593104,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1599",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64"
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
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579521744,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1599",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64"
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
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579590384,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1599",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64"
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
  "name": "check_prlimit_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579624018,
      "name": "check_prlimit_permission",
      "external": false,
      "loc": "kernel/sys.c:1599",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64"
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
int check_prlimit_permission(struct task_struct * task, unsigned int flags)
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
int check_prlimit_permission(struct task_struct * task, unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int check_prlimit_permission(struct task_struct * task, unsigned int flags)
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
int check_prlimit_permission(struct task_struct * task, unsigned int flags)
```
</details>
</li>
</ul>
