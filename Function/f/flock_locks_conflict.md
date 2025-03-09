# Function: <code>flock_locks_conflict</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581339440,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:749",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
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
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581517633,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:776",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
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
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581603790,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:796",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
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
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581664878,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:796",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
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
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581810926,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:808",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
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
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581987724,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:808",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool flock_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582077762,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:917",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582065840,
      "name": "flock_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool flock_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582239667,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:913",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582226736,
      "name": "flock_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool flock_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582339427,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:937",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582326400,
      "name": "flock_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
bool flock_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582629702,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:937",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582615792,
      "name": "flock_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
bool flock_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582701888,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:937",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582688208,
      "name": "flock_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
bool flock_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582731918,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:937",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582718096,
      "name": "flock_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
bool flock_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583058830,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:937",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583044992,
      "name": "flock_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
bool flock_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583539669,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:887",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583520912,
      "name": "flock_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
bool flock_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584140197,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:873",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584120192,
      "name": "flock_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
bool flock_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584367429,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:874",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584347120,
      "name": "flock_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
bool flock_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584585781,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:888",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584565456,
      "name": "flock_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool flock_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493923296,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:937",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493907752,
      "name": "flock_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool flock_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227401448,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:937",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227386040,
      "name": "flock_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool flock_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287568488,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:937",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287546272,
      "name": "flock_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool flock_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273475802,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:937",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273463338,
      "name": "flock_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool flock_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582308163,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:937",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582295136,
      "name": "flock_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool flock_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582245923,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:937",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582232896,
      "name": "flock_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool flock_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582298643,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:937",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582285616,
      "name": "flock_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool flock_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "flock_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582377530,
      "name": "flock_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:937",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582364480,
      "name": "flock_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
bool flock_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
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
