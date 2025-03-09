# Function: <code>__do_sys_prlimit64</code>

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
  "name": "__do_sys_prlimit64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579531544,
      "name": "__do_sys_prlimit64",
      "external": false,
      "loc": "kernel/sys.c:1630",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_prlimit64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579567656,
      "name": "__do_sys_prlimit64",
      "external": false,
      "loc": "kernel/sys.c:1631",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_prlimit64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579590670,
      "name": "__do_sys_prlimit64",
      "external": false,
      "loc": "kernel/sys.c:1631",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
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
  "name": "__do_sys_prlimit64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579616718,
      "name": "__do_sys_prlimit64",
      "external": false,
      "loc": "kernel/sys.c:1621",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
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
long int __do_sys_prlimit64(pid_t pid, unsigned int resource, const struct rlimit64 * new_rlim, struct rlimit64 * old_rlim)
```

```json
{
  "name": "__do_sys_prlimit64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579647792,
      "name": "__do_sys_prlimit64",
      "external": false,
      "loc": "kernel/sys.c:1637",
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
      "addr": 18446744071579647792,
      "name": "__do_sys_prlimit64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 511
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
long int __do_sys_prlimit64(pid_t pid, unsigned int resource, const struct rlimit64 * new_rlim, struct rlimit64 * old_rlim)
```

```json
{
  "name": "__do_sys_prlimit64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579628320,
      "name": "__do_sys_prlimit64",
      "external": false,
      "loc": "kernel/sys.c:1638",
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
      "addr": 18446744071579628320,
      "name": "__do_sys_prlimit64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
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
long int __do_sys_prlimit64(pid_t pid, unsigned int resource, const struct rlimit64 * new_rlim, struct rlimit64 * old_rlim)
```

```json
{
  "name": "__do_sys_prlimit64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579634864,
      "name": "__do_sys_prlimit64",
      "external": false,
      "loc": "kernel/sys.c:1655",
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
      "addr": 18446744071579634864,
      "name": "__do_sys_prlimit64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 679
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
long int __do_sys_prlimit64(pid_t pid, unsigned int resource, const struct rlimit64 * new_rlim, struct rlimit64 * old_rlim)
```

```json
{
  "name": "__do_sys_prlimit64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579711392,
      "name": "__do_sys_prlimit64",
      "external": false,
      "loc": "kernel/sys.c:1664",
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
      "addr": 18446744071579711392,
      "name": "__do_sys_prlimit64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 679
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
long int __do_sys_prlimit64(pid_t pid, unsigned int resource, const struct rlimit64 * new_rlim, struct rlimit64 * old_rlim)
```

```json
{
  "name": "__do_sys_prlimit64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579801824,
      "name": "__do_sys_prlimit64",
      "external": false,
      "loc": "kernel/sys.c:1676",
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
      "addr": 18446744071579801824,
      "name": "__do_sys_prlimit64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 758
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
long int __do_sys_prlimit64(pid_t pid, unsigned int resource, const struct rlimit64 * new_rlim, struct rlimit64 * old_rlim)
```

```json
{
  "name": "__do_sys_prlimit64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579940224,
      "name": "__do_sys_prlimit64",
      "external": false,
      "loc": "kernel/sys.c:1681",
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
      "addr": 18446744071579940224,
      "name": "__do_sys_prlimit64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 758
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
long int __do_sys_prlimit64(pid_t pid, unsigned int resource, const struct rlimit64 * new_rlim, struct rlimit64 * old_rlim)
```

```json
{
  "name": "__do_sys_prlimit64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579990288,
      "name": "__do_sys_prlimit64",
      "external": false,
      "loc": "kernel/sys.c:1699",
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
      "addr": 18446744071579990288,
      "name": "__do_sys_prlimit64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 758
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
long int __do_sys_prlimit64(pid_t pid, unsigned int resource, const struct rlimit64 * new_rlim, struct rlimit64 * old_rlim)
```

```json
{
  "name": "__do_sys_prlimit64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580029696,
      "name": "__do_sys_prlimit64",
      "external": false,
      "loc": "kernel/sys.c:1699",
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
      "addr": 18446744071580029696,
      "name": "__do_sys_prlimit64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 758
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
  "name": "__do_sys_prlimit64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490783600,
      "name": "__do_sys_prlimit64",
      "external": false,
      "loc": "kernel/sys.c:1621",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
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
  "name": "__do_sys_prlimit64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224820272,
      "name": "__do_sys_prlimit64",
      "external": false,
      "loc": "kernel/sys.c:1621",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
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
  "name": "__do_sys_prlimit64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283608944,
      "name": "__do_sys_prlimit64",
      "external": false,
      "loc": "kernel/sys.c:1621",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
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
  "name": "__do_sys_prlimit64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271467568,
      "name": "__do_sys_prlimit64",
      "external": false,
      "loc": "kernel/sys.c:1621",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
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
  "name": "__do_sys_prlimit64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579593022,
      "name": "__do_sys_prlimit64",
      "external": false,
      "loc": "kernel/sys.c:1621",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
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
  "name": "__do_sys_prlimit64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579521662,
      "name": "__do_sys_prlimit64",
      "external": false,
      "loc": "kernel/sys.c:1621",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
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
  "name": "__do_sys_prlimit64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579590302,
      "name": "__do_sys_prlimit64",
      "external": false,
      "loc": "kernel/sys.c:1621",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
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
  "name": "__do_sys_prlimit64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579623928,
      "name": "__do_sys_prlimit64",
      "external": false,
      "loc": "kernel/sys.c:1621",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long int __do_sys_prlimit64(pid_t pid, unsigned int resource, const struct rlimit64 * new_rlim, struct rlimit64 * old_rlim)
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
