# Function: <code>kernel_get_mempolicy</code>

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
int kernel_get_mempolicy(int * policy, long unsigned int * nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "kernel_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581314832,
      "name": "kernel_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1470",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__ia32_sys_get_mempolicy",
        "mm/mempolicy.c:__x64_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581314832,
      "name": "kernel_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1853
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
int kernel_get_mempolicy(int * policy, long unsigned int * nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "kernel_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581398736,
      "name": "kernel_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1510",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__ia32_sys_get_mempolicy",
        "mm/mempolicy.c:__x64_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581398736,
      "name": "kernel_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2072
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
int kernel_get_mempolicy(int * policy, long unsigned int * nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "kernel_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581510832,
      "name": "kernel_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1556",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__ia32_sys_get_mempolicy",
        "mm/mempolicy.c:__x64_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581510832,
      "name": "kernel_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2122
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
int kernel_get_mempolicy(int * policy, long unsigned int * nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "kernel_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581575200,
      "name": "kernel_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1556",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__ia32_sys_get_mempolicy",
        "mm/mempolicy.c:__x64_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581575200,
      "name": "kernel_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2122
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
int kernel_get_mempolicy(int * policy, long unsigned int * nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "kernel_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581786736,
      "name": "kernel_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1625",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__ia32_sys_get_mempolicy",
        "mm/mempolicy.c:__x64_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581786736,
      "name": "kernel_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
int kernel_get_mempolicy(int * policy, long unsigned int * nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "kernel_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581831680,
      "name": "kernel_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1601",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__ia32_sys_get_mempolicy",
        "mm/mempolicy.c:__x64_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831680,
      "name": "kernel_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
int kernel_get_mempolicy(int * policy, long unsigned int * nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "kernel_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581862400,
      "name": "kernel_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1615",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__ia32_sys_get_mempolicy",
        "mm/mempolicy.c:__x64_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581862400,
      "name": "kernel_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
int kernel_get_mempolicy(int * policy, long unsigned int * nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "kernel_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582153968,
      "name": "kernel_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1610",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__ia32_sys_get_mempolicy",
        "mm/mempolicy.c:__x64_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582153968,
      "name": "kernel_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
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
int kernel_get_mempolicy(int * policy, long unsigned int * nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "kernel_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582609120,
      "name": "kernel_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1674",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__ia32_sys_get_mempolicy",
        "mm/mempolicy.c:__x64_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582609120,
      "name": "kernel_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
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
int kernel_get_mempolicy(int * policy, long unsigned int * nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "kernel_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583132288,
      "name": "kernel_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1689",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__ia32_sys_get_mempolicy",
        "mm/mempolicy.c:__x64_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583132288,
      "name": "kernel_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
int kernel_get_mempolicy(int * policy, long unsigned int * nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "kernel_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583342512,
      "name": "kernel_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1700",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__ia32_sys_get_mempolicy",
        "mm/mempolicy.c:__x64_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583342512,
      "name": "kernel_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
int kernel_get_mempolicy(int * policy, long unsigned int * nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "kernel_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583578688,
      "name": "kernel_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1684",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__ia32_sys_get_mempolicy",
        "mm/mempolicy.c:__x64_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583578688,
      "name": "kernel_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
int kernel_get_mempolicy(int * policy, long unsigned int * nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "kernel_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493011912,
      "name": "kernel_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1556",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__arm64_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__arm64_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__arm64_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493011912,
      "name": "kernel_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2220
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int kernel_get_mempolicy(int * policy, long unsigned int * nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "kernel_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286439040,
      "name": "kernel_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1556",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__se_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__se_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__se_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286439040,
      "name": "kernel_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2064
    }
  ]
}
```
</details>
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
int kernel_get_mempolicy(int * policy, long unsigned int * nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "kernel_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581543936,
      "name": "kernel_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1556",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__ia32_sys_get_mempolicy",
        "mm/mempolicy.c:__x64_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581543936,
      "name": "kernel_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2122
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
int kernel_get_mempolicy(int * policy, long unsigned int * nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "kernel_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581485584,
      "name": "kernel_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1556",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__ia32_sys_get_mempolicy",
        "mm/mempolicy.c:__x64_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581485584,
      "name": "kernel_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2122
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
int kernel_get_mempolicy(int * policy, long unsigned int * nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "kernel_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581535248,
      "name": "kernel_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1556",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__ia32_sys_get_mempolicy",
        "mm/mempolicy.c:__x64_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581535248,
      "name": "kernel_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2122
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
int kernel_get_mempolicy(int * policy, long unsigned int * nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "kernel_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581600320,
      "name": "kernel_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1556",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__ia32_sys_get_mempolicy",
        "mm/mempolicy.c:__x64_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581600320,
      "name": "kernel_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2088
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
int kernel_get_mempolicy(int * policy, long unsigned int * nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags)
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
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int kernel_get_mempolicy(int * policy, long unsigned int * nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int kernel_get_mempolicy(int * policy, long unsigned int * nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags)
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
