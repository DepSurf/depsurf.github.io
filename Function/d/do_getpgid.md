# Function: <code>do_getpgid</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_getpgid(pid_t pid)
```

```json
{
  "name": "do_getpgid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579515797,
      "name": "do_getpgid",
      "external": false,
      "loc": "kernel/sys.c:1077",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__x64_sys_getpgrp"
      ],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_getpgid",
        "kernel/sys.c:__x64_sys_getpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579515616,
      "name": "do_getpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_getpgid(pid_t pid)
```

```json
{
  "name": "do_getpgid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579552101,
      "name": "do_getpgid",
      "external": false,
      "loc": "kernel/sys.c:1077",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__x64_sys_getpgrp"
      ],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_getpgid",
        "kernel/sys.c:__x64_sys_getpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551920,
      "name": "do_getpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
int do_getpgid(pid_t pid)
```

```json
{
  "name": "do_getpgid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579573888,
      "name": "do_getpgid",
      "external": false,
      "loc": "kernel/sys.c:1077",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__x64_sys_getpgrp",
        "kernel/sys.c:__ia32_sys_getpgid",
        "kernel/sys.c:__x64_sys_getpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579573888,
      "name": "do_getpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int do_getpgid(pid_t pid)
```

```json
{
  "name": "do_getpgid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579600208,
      "name": "do_getpgid",
      "external": false,
      "loc": "kernel/sys.c:1077",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__x64_sys_getpgrp",
        "kernel/sys.c:__ia32_sys_getpgid",
        "kernel/sys.c:__x64_sys_getpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579600208,
      "name": "do_getpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_getpgid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579638485,
      "name": "do_getpgid",
      "external": false,
      "loc": "kernel/sys.c:1091",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_getpgrp",
        "kernel/sys.c:__ia32_sys_getpgid",
        "kernel/sys.c:__x64_sys_getpgid"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_getpgid(pid_t pid)
```

```json
{
  "name": "do_getpgid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579618421,
      "name": "do_getpgid",
      "external": false,
      "loc": "kernel/sys.c:1092",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_getpgrp"
      ],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_getpgid",
        "kernel/sys.c:__x64_sys_getpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611408,
      "name": "do_getpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_getpgid(pid_t pid)
```

```json
{
  "name": "do_getpgid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579624709,
      "name": "do_getpgid",
      "external": false,
      "loc": "kernel/sys.c:1109",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_getpgrp"
      ],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_getpgid",
        "kernel/sys.c:__x64_sys_getpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579617872,
      "name": "do_getpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_getpgid(pid_t pid)
```

```json
{
  "name": "do_getpgid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579702149,
      "name": "do_getpgid",
      "external": false,
      "loc": "kernel/sys.c:1118",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_getpgrp"
      ],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_getpgid",
        "kernel/sys.c:__x64_sys_getpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579694128,
      "name": "do_getpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_getpgid(pid_t pid)
```

```json
{
  "name": "do_getpgid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579803253,
      "name": "do_getpgid",
      "external": false,
      "loc": "kernel/sys.c:1125",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_getpgrp"
      ],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_getpgid",
        "kernel/sys.c:__x64_sys_getpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579795360,
      "name": "do_getpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_getpgid(pid_t pid)
```

```json
{
  "name": "do_getpgid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579941749,
      "name": "do_getpgid",
      "external": false,
      "loc": "kernel/sys.c:1126",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_getpgrp"
      ],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_getpgid",
        "kernel/sys.c:__x64_sys_getpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579929824,
      "name": "do_getpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_getpgid(pid_t pid)
```

```json
{
  "name": "do_getpgid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579991813,
      "name": "do_getpgid",
      "external": false,
      "loc": "kernel/sys.c:1144",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_getpgrp"
      ],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_getpgid",
        "kernel/sys.c:__x64_sys_getpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979760,
      "name": "do_getpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_getpgid(pid_t pid)
```

```json
{
  "name": "do_getpgid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580031221,
      "name": "do_getpgid",
      "external": false,
      "loc": "kernel/sys.c:1144",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_getpgrp"
      ],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_getpgid",
        "kernel/sys.c:__x64_sys_getpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019168,
      "name": "do_getpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
  "name": "do_getpgid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490764192,
      "name": "do_getpgid",
      "external": false,
      "loc": "kernel/sys.c:1077",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__arm64_sys_getpgrp",
        "kernel/sys.c:__arm64_sys_getpgid"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int do_getpgid(pid_t pid)
```

```json
{
  "name": "do_getpgid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224808628,
      "name": "do_getpgid",
      "external": false,
      "loc": "kernel/sys.c:1077",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:sys_getpgrp",
        "kernel/sys.c:__se_sys_getpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224808628,
      "name": "do_getpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "do_getpgid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283596252,
      "name": "do_getpgid",
      "external": false,
      "loc": "kernel/sys.c:1077",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:sys_getpgrp",
        "kernel/sys.c:__se_sys_getpgid"
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
  "name": "do_getpgid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271466074,
      "name": "do_getpgid",
      "external": false,
      "loc": "kernel/sys.c:1077",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__se_sys_getpgid"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int do_getpgid(pid_t pid)
```

```json
{
  "name": "do_getpgid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579576512,
      "name": "do_getpgid",
      "external": false,
      "loc": "kernel/sys.c:1077",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__x64_sys_getpgrp",
        "kernel/sys.c:__ia32_sys_getpgid",
        "kernel/sys.c:__x64_sys_getpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579576512,
      "name": "do_getpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int do_getpgid(pid_t pid)
```

```json
{
  "name": "do_getpgid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505136,
      "name": "do_getpgid",
      "external": false,
      "loc": "kernel/sys.c:1077",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__x64_sys_getpgrp",
        "kernel/sys.c:__ia32_sys_getpgid",
        "kernel/sys.c:__x64_sys_getpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505136,
      "name": "do_getpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int do_getpgid(pid_t pid)
```

```json
{
  "name": "do_getpgid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579573792,
      "name": "do_getpgid",
      "external": false,
      "loc": "kernel/sys.c:1077",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__x64_sys_getpgrp",
        "kernel/sys.c:__ia32_sys_getpgid",
        "kernel/sys.c:__x64_sys_getpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579573792,
      "name": "do_getpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int do_getpgid(pid_t pid)
```

```json
{
  "name": "do_getpgid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579607824,
      "name": "do_getpgid",
      "external": false,
      "loc": "kernel/sys.c:1077",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__x64_sys_getpgrp",
        "kernel/sys.c:__ia32_sys_getpgid",
        "kernel/sys.c:__x64_sys_getpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579607824,
      "name": "do_getpgid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int do_getpgid(pid_t pid)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int do_getpgid(pid_t pid)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int do_getpgid(pid_t pid)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int do_getpgid(pid_t pid)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int do_getpgid(pid_t pid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int do_getpgid(pid_t pid)
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
