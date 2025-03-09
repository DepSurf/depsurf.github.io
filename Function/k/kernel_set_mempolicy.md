# Function: <code>kernel_set_mempolicy</code>

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
long int kernel_set_mempolicy(int mode, const long unsigned int * nmask, long unsigned int maxnode)
```

```json
{
  "name": "kernel_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581314192,
      "name": "kernel_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1344",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__ia32_sys_set_mempolicy",
        "mm/mempolicy.c:__x64_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581314192,
      "name": "kernel_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
long int kernel_set_mempolicy(int mode, const long unsigned int * nmask, long unsigned int maxnode)
```

```json
{
  "name": "kernel_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581398096,
      "name": "kernel_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1384",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__ia32_sys_set_mempolicy",
        "mm/mempolicy.c:__x64_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581398096,
      "name": "kernel_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
long int kernel_set_mempolicy(int mode, const long unsigned int * nmask, long unsigned int maxnode)
```

```json
{
  "name": "kernel_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581510192,
      "name": "kernel_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1430",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__ia32_sys_set_mempolicy",
        "mm/mempolicy.c:__x64_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581510192,
      "name": "kernel_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
long int kernel_set_mempolicy(int mode, const long unsigned int * nmask, long unsigned int maxnode)
```

```json
{
  "name": "kernel_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581574560,
      "name": "kernel_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1434",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__ia32_sys_set_mempolicy",
        "mm/mempolicy.c:__x64_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581574560,
      "name": "kernel_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
long int kernel_set_mempolicy(int mode, const long unsigned int * nmask, long unsigned int maxnode)
```

```json
{
  "name": "kernel_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581784896,
      "name": "kernel_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1503",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__ia32_sys_set_mempolicy",
        "mm/mempolicy.c:__x64_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581784896,
      "name": "kernel_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
long int kernel_set_mempolicy(int mode, const long unsigned int * nmask, long unsigned int maxnode)
```

```json
{
  "name": "kernel_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581829760,
      "name": "kernel_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1479",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__ia32_sys_set_mempolicy",
        "mm/mempolicy.c:__x64_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581829760,
      "name": "kernel_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
long int kernel_set_mempolicy(int mode, const long unsigned int * nmask, long unsigned int maxnode)
```

```json
{
  "name": "kernel_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581860192,
      "name": "kernel_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1493",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__ia32_sys_set_mempolicy",
        "mm/mempolicy.c:__x64_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581860192,
      "name": "kernel_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
long int kernel_set_mempolicy(int mode, const long unsigned int * nmask, long unsigned int maxnode)
```

```json
{
  "name": "kernel_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582152288,
      "name": "kernel_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1488",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__ia32_sys_set_mempolicy",
        "mm/mempolicy.c:__x64_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582152288,
      "name": "kernel_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
long int kernel_set_mempolicy(int mode, const long unsigned int * nmask, long unsigned int maxnode)
```

```json
{
  "name": "kernel_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582607152,
      "name": "kernel_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1552",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__ia32_sys_set_mempolicy",
        "mm/mempolicy.c:__x64_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582607152,
      "name": "kernel_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
long int kernel_set_mempolicy(int mode, const long unsigned int * nmask, long unsigned int maxnode)
```

```json
{
  "name": "kernel_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583129696,
      "name": "kernel_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1567",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__ia32_sys_set_mempolicy",
        "mm/mempolicy.c:__x64_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583129696,
      "name": "kernel_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
long int kernel_set_mempolicy(int mode, const long unsigned int * nmask, long unsigned int maxnode)
```

```json
{
  "name": "kernel_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583340384,
      "name": "kernel_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1578",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__ia32_sys_set_mempolicy",
        "mm/mempolicy.c:__x64_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583340384,
      "name": "kernel_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
long int kernel_set_mempolicy(int mode, const long unsigned int * nmask, long unsigned int maxnode)
```

```json
{
  "name": "kernel_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583576544,
      "name": "kernel_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1564",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__ia32_sys_set_mempolicy",
        "mm/mempolicy.c:__x64_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583576544,
      "name": "kernel_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
long int kernel_set_mempolicy(int mode, const long unsigned int * nmask, long unsigned int maxnode)
```

```json
{
  "name": "kernel_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493010944,
      "name": "kernel_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1434",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__arm64_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__arm64_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493010944,
      "name": "kernel_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
long int kernel_set_mempolicy(int mode, const long unsigned int * nmask, long unsigned int maxnode)
```

```json
{
  "name": "kernel_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286438160,
      "name": "kernel_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1434",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__se_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__se_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286438160,
      "name": "kernel_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
long int kernel_set_mempolicy(int mode, const long unsigned int * nmask, long unsigned int maxnode)
```

```json
{
  "name": "kernel_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581543296,
      "name": "kernel_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1434",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__ia32_sys_set_mempolicy",
        "mm/mempolicy.c:__x64_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581543296,
      "name": "kernel_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
long int kernel_set_mempolicy(int mode, const long unsigned int * nmask, long unsigned int maxnode)
```

```json
{
  "name": "kernel_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581484944,
      "name": "kernel_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1434",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__ia32_sys_set_mempolicy",
        "mm/mempolicy.c:__x64_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581484944,
      "name": "kernel_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
long int kernel_set_mempolicy(int mode, const long unsigned int * nmask, long unsigned int maxnode)
```

```json
{
  "name": "kernel_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581534608,
      "name": "kernel_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1434",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__ia32_sys_set_mempolicy",
        "mm/mempolicy.c:__x64_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581534608,
      "name": "kernel_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
long int kernel_set_mempolicy(int mode, const long unsigned int * nmask, long unsigned int maxnode)
```

```json
{
  "name": "kernel_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581599680,
      "name": "kernel_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1434",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__ia32_sys_set_mempolicy",
        "mm/mempolicy.c:__x64_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581599680,
      "name": "kernel_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
long int kernel_set_mempolicy(int mode, const long unsigned int * nmask, long unsigned int maxnode)
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
long int kernel_set_mempolicy(int mode, const long unsigned int * nmask, long unsigned int maxnode)
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
long int kernel_set_mempolicy(int mode, const long unsigned int * nmask, long unsigned int maxnode)
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
