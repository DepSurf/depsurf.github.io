# Function: <code>ksys_umount</code>

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
int ksys_umount(char * name, int flags)
```

```json
{
  "name": "ksys_umount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581727440,
      "name": "ksys_umount",
      "external": true,
      "loc": "fs/namespace.c:1717",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__ia32_sys_umount",
        "fs/namespace.c:__x64_sys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581727440,
      "name": "ksys_umount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1056
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
int ksys_umount(char * name, int flags)
```

```json
{
  "name": "ksys_umount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581813968,
      "name": "ksys_umount",
      "external": true,
      "loc": "fs/namespace.c:1635",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__ia32_sys_umount",
        "fs/namespace.c:__x64_sys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581813968,
      "name": "ksys_umount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1087
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
int ksys_umount(char * name, int flags)
```

```json
{
  "name": "ksys_umount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581933952,
      "name": "ksys_umount",
      "external": true,
      "loc": "fs/namespace.c:1670",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__ia32_sys_umount",
        "fs/namespace.c:__x64_sys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581933952,
      "name": "ksys_umount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1156
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
int ksys_umount(char * name, int flags)
```

```json
{
  "name": "ksys_umount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582006592,
      "name": "ksys_umount",
      "external": true,
      "loc": "fs/namespace.c:1675",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__ia32_sys_umount",
        "fs/namespace.c:__x64_sys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582006592,
      "name": "ksys_umount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1153
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
int ksys_umount(char * name, int flags)
```

```json
{
  "name": "ksys_umount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582243856,
      "name": "ksys_umount",
      "external": true,
      "loc": "fs/namespace.c:1725",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__ia32_sys_umount",
        "fs/namespace.c:__x64_sys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582243856,
      "name": "ksys_umount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ksys_umount(char * name, int flags)
```

```json
{
  "name": "ksys_umount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582293356,
      "name": "ksys_umount",
      "external": false,
      "loc": "fs/namespace.c:1753",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__x64_sys_umount"
      ],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582293056,
      "name": "ksys_umount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int ksys_umount(char * name, int flags)
```

```json
{
  "name": "ksys_umount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582320476,
      "name": "ksys_umount",
      "external": false,
      "loc": "fs/namespace.c:1768",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__x64_sys_umount"
      ],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582320176,
      "name": "ksys_umount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int ksys_umount(char * name, int flags)
```

```json
{
  "name": "ksys_umount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582640924,
      "name": "ksys_umount",
      "external": false,
      "loc": "fs/namespace.c:1769",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__x64_sys_umount"
      ],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582640624,
      "name": "ksys_umount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_umount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583178108,
      "name": "ksys_umount",
      "external": false,
      "loc": "fs/namespace.c:1810",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__ia32_sys_umount",
        "fs/namespace.c:__x64_sys_umount"
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
  "name": "ksys_umount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583753068,
      "name": "ksys_umount",
      "external": false,
      "loc": "fs/namespace.c:1915",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__ia32_sys_umount",
        "fs/namespace.c:__x64_sys_umount"
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
  "name": "ksys_umount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583970060,
      "name": "ksys_umount",
      "external": false,
      "loc": "fs/namespace.c:1902",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__ia32_sys_umount",
        "fs/namespace.c:__x64_sys_umount"
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
  "name": "ksys_umount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584182364,
      "name": "ksys_umount",
      "external": false,
      "loc": "fs/namespace.c:1904",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__ia32_sys_umount",
        "fs/namespace.c:__x64_sys_umount"
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
int ksys_umount(char * name, int flags)
```

```json
{
  "name": "ksys_umount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493528160,
      "name": "ksys_umount",
      "external": true,
      "loc": "fs/namespace.c:1675",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__arm64_sys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493528160,
      "name": "ksys_umount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int ksys_umount(char * name, int flags)
```

```json
{
  "name": "ksys_umount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227081404,
      "name": "ksys_umount",
      "external": true,
      "loc": "fs/namespace.c:1675",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__se_sys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227081404,
      "name": "ksys_umount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int ksys_umount(char * name, int flags)
```

```json
{
  "name": "ksys_umount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287095280,
      "name": "ksys_umount",
      "external": true,
      "loc": "fs/namespace.c:1675",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__se_sys_oldumount",
        "fs/namespace.c:__se_sys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287095280,
      "name": "ksys_umount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1608
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int ksys_umount(char * name, int flags)
```

```json
{
  "name": "ksys_umount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273195046,
      "name": "ksys_umount",
      "external": true,
      "loc": "fs/namespace.c:1675",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__se_sys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273195046,
      "name": "ksys_umount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1094
    }
  ]
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
int ksys_umount(char * name, int flags)
```

```json
{
  "name": "ksys_umount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581975328,
      "name": "ksys_umount",
      "external": true,
      "loc": "fs/namespace.c:1675",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__ia32_sys_umount",
        "fs/namespace.c:__x64_sys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581975328,
      "name": "ksys_umount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1153
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
int ksys_umount(char * name, int flags)
```

```json
{
  "name": "ksys_umount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581912896,
      "name": "ksys_umount",
      "external": true,
      "loc": "fs/namespace.c:1675",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__ia32_sys_umount",
        "fs/namespace.c:__x64_sys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581912896,
      "name": "ksys_umount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1153
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
int ksys_umount(char * name, int flags)
```

```json
{
  "name": "ksys_umount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581966608,
      "name": "ksys_umount",
      "external": true,
      "loc": "fs/namespace.c:1675",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__ia32_sys_umount",
        "fs/namespace.c:__x64_sys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581966608,
      "name": "ksys_umount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1153
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
int ksys_umount(char * name, int flags)
```

```json
{
  "name": "ksys_umount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582037072,
      "name": "ksys_umount",
      "external": true,
      "loc": "fs/namespace.c:1675",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__ia32_sys_umount",
        "fs/namespace.c:__x64_sys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582037072,
      "name": "ksys_umount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1149
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
int ksys_umount(char * name, int flags)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int ksys_umount(char * name, int flags)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
