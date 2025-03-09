# Function: <code>flock_make_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581346001,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:374",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:SyS_flock"
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
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581526741,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:401",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:SyS_flock"
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
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581612646,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:411",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:SyS_flock"
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
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581673212,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:411",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:SyS_flock"
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
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581819484,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:428",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:SyS_flock"
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
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581993713,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:428",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct file_lock * flock_make_lock(struct file * filp, unsigned int cmd, struct file_lock * fl)
```

```json
{
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582069456,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:477",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_remove_flock",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582069456,
      "name": "flock_make_lock",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct file_lock * flock_make_lock(struct file * filp, unsigned int cmd, struct file_lock * fl)
```

```json
{
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582231408,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:478",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_remove_flock",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582231408,
      "name": "flock_make_lock",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct file_lock * flock_make_lock(struct file * filp, unsigned int cmd, struct file_lock * fl)
```

```json
{
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582331040,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:479",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_remove_flock",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582331040,
      "name": "flock_make_lock",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct file_lock * flock_make_lock(struct file * filp, unsigned int cmd, struct file_lock * fl)
```

```json
{
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582630417,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:479",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_flock"
      ],
      "caller_func": [
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582624080,
      "name": "flock_make_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
struct file_lock * flock_make_lock(struct file * filp, unsigned int cmd, struct file_lock * fl)
```

```json
{
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582702609,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:479",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_flock"
      ],
      "caller_func": [
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582696464,
      "name": "flock_make_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
struct file_lock * flock_make_lock(struct file * filp, unsigned int cmd, struct file_lock * fl)
```

```json
{
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582732625,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:479",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_flock"
      ],
      "caller_func": [
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582725904,
      "name": "flock_make_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
struct file_lock * flock_make_lock(struct file * filp, unsigned int cmd, struct file_lock * fl)
```

```json
{
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583059537,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:479",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_flock"
      ],
      "caller_func": [
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583052784,
      "name": "flock_make_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583540512,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:429",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_flock",
        "fs/locks.c:__do_sys_flock"
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
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584141056,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:428",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_flock",
        "fs/locks.c:__do_sys_flock"
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
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584368291,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:429",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_flock",
        "fs/locks.c:__do_sys_flock"
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
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584586643,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:428",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_flock",
        "fs/locks.c:__do_sys_flock"
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
struct file_lock * flock_make_lock(struct file * filp, unsigned int cmd, struct file_lock * fl)
```

```json
{
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493910848,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:479",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_remove_flock",
        "fs/locks.c:__arm64_sys_flock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493910848,
      "name": "flock_make_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct file_lock * flock_make_lock(struct file * filp, unsigned int cmd, struct file_lock * fl)
```

```json
{
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227391468,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:479",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_remove_flock",
        "fs/locks.c:__se_sys_flock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227391468,
      "name": "flock_make_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct file_lock * flock_make_lock(struct file * filp, unsigned int cmd, struct file_lock * fl)
```

```json
{
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287553248,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:479",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_remove_flock",
        "fs/locks.c:__se_sys_flock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287553248,
      "name": "flock_make_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
struct file_lock * flock_make_lock(struct file * filp, unsigned int cmd, struct file_lock * fl)
```

```json
{
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273467352,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:479",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_remove_flock",
        "fs/locks.c:__se_sys_flock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273467352,
      "name": "flock_make_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
struct file_lock * flock_make_lock(struct file * filp, unsigned int cmd, struct file_lock * fl)
```

```json
{
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582299776,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:479",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_remove_flock",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582299776,
      "name": "flock_make_lock",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct file_lock * flock_make_lock(struct file * filp, unsigned int cmd, struct file_lock * fl)
```

```json
{
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582237536,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:479",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_remove_flock",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582237536,
      "name": "flock_make_lock",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct file_lock * flock_make_lock(struct file * filp, unsigned int cmd, struct file_lock * fl)
```

```json
{
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582290256,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:479",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_remove_flock",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582290256,
      "name": "flock_make_lock",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct file_lock * flock_make_lock(struct file * filp, unsigned int cmd, struct file_lock * fl)
```

```json
{
  "name": "flock_make_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582369152,
      "name": "flock_make_lock",
      "external": false,
      "loc": "fs/locks.c:479",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_remove_flock",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582369152,
      "name": "flock_make_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct file_lock * flock_make_lock(struct file * filp, unsigned int cmd, struct file_lock * fl)
```
</details>
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
struct file_lock * flock_make_lock(struct file * filp, unsigned int cmd, struct file_lock * fl)
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
