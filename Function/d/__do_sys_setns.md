# Function: <code>__do_sys_setns</code>

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
  "name": "__do_sys_setns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579584198,
      "name": "__do_sys_setns",
      "external": false,
      "loc": "kernel/nsproxy.c:237",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns"
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
  "name": "__do_sys_setns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579621398,
      "name": "__do_sys_setns",
      "external": false,
      "loc": "kernel/nsproxy.c:237",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns"
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
  "name": "__do_sys_setns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579646054,
      "name": "__do_sys_setns",
      "external": false,
      "loc": "kernel/nsproxy.c:233",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns"
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
  "name": "__do_sys_setns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579683190,
      "name": "__do_sys_setns",
      "external": false,
      "loc": "kernel/nsproxy.c:233",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns"
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
long int __do_sys_setns(int fd, int flags)
```

```json
{
  "name": "__do_sys_setns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579722800,
      "name": "__do_sys_setns",
      "external": false,
      "loc": "kernel/nsproxy.c:515",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579722800,
      "name": "__do_sys_setns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
long int __do_sys_setns(int fd, int flags)
```

```json
{
  "name": "__do_sys_setns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579701200,
      "name": "__do_sys_setns",
      "external": false,
      "loc": "kernel/nsproxy.c:527",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579701200,
      "name": "__do_sys_setns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
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
long int __do_sys_setns(int fd, int flags)
```

```json
{
  "name": "__do_sys_setns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579708336,
      "name": "__do_sys_setns",
      "external": false,
      "loc": "kernel/nsproxy.c:527",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579708336,
      "name": "__do_sys_setns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
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
long int __do_sys_setns(int fd, int flags)
```

```json
{
  "name": "__do_sys_setns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579786480,
      "name": "__do_sys_setns",
      "external": false,
      "loc": "kernel/nsproxy.c:527",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579786480,
      "name": "__do_sys_setns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
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
long int __do_sys_setns(int fd, int flags)
```

```json
{
  "name": "__do_sys_setns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579892560,
      "name": "__do_sys_setns",
      "external": false,
      "loc": "kernel/nsproxy.c:527",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892560,
      "name": "__do_sys_setns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
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
long int __do_sys_setns(int fd, int flags)
```

```json
{
  "name": "__do_sys_setns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580043456,
      "name": "__do_sys_setns",
      "external": false,
      "loc": "kernel/nsproxy.c:546",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580043456,
      "name": "__do_sys_setns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
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
long int __do_sys_setns(int fd, int flags)
```

```json
{
  "name": "__do_sys_setns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580097472,
      "name": "__do_sys_setns",
      "external": false,
      "loc": "kernel/nsproxy.c:546",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097472,
      "name": "__do_sys_setns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
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
long int __do_sys_setns(int fd, int flags)
```

```json
{
  "name": "__do_sys_setns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580142064,
      "name": "__do_sys_setns",
      "external": false,
      "loc": "kernel/nsproxy.c:546",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580142064,
      "name": "__do_sys_setns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
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
  "name": "__do_sys_setns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490858320,
      "name": "__do_sys_setns",
      "external": false,
      "loc": "kernel/nsproxy.c:233",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:__arm64_sys_setns"
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
  "name": "__do_sys_setns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224878252,
      "name": "__do_sys_setns",
      "external": false,
      "loc": "kernel/nsproxy.c:233",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:__se_sys_setns"
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
  "name": "__do_sys_setns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283688200,
      "name": "__do_sys_setns",
      "external": false,
      "loc": "kernel/nsproxy.c:233",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:__se_sys_setns"
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
  "name": "__do_sys_setns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271516990,
      "name": "__do_sys_setns",
      "external": false,
      "loc": "kernel/nsproxy.c:233",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:__se_sys_setns"
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
  "name": "__do_sys_setns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579659510,
      "name": "__do_sys_setns",
      "external": false,
      "loc": "kernel/nsproxy.c:233",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns"
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
  "name": "__do_sys_setns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579587862,
      "name": "__do_sys_setns",
      "external": false,
      "loc": "kernel/nsproxy.c:233",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns"
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
  "name": "__do_sys_setns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579656774,
      "name": "__do_sys_setns",
      "external": false,
      "loc": "kernel/nsproxy.c:233",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns"
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
  "name": "__do_sys_setns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579690646,
      "name": "__do_sys_setns",
      "external": false,
      "loc": "kernel/nsproxy.c:233",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns"
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
long int __do_sys_setns(int fd, int flags)
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
