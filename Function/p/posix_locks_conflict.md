# Function: <code>posix_locks_conflict</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581336016,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:731",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_test_lock",
        "fs/locks.c:__posix_lock_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581336016,
      "name": "posix_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581516704,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:758",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581516704,
      "name": "posix_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581602112,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:778",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581602112,
      "name": "posix_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581662928,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:778",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581662928,
      "name": "posix_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581807744,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:790",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581807744,
      "name": "posix_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581981472,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:790",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581981472,
      "name": "posix_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
bool posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582070080,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:898",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582070080,
      "name": "posix_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
bool posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582232288,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:894",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582232288,
      "name": "posix_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
bool posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582331968,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:918",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582331968,
      "name": "posix_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
bool posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582630886,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:918",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock",
        "fs/locks.c:posix_test_lock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582619856,
      "name": "posix_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
bool posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582703078,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:918",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock",
        "fs/locks.c:posix_test_lock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582692288,
      "name": "posix_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
bool posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582733093,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:918",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock",
        "fs/locks.c:posix_test_lock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582723216,
      "name": "posix_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
bool posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583060005,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:918",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock",
        "fs/locks.c:posix_test_lock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583050112,
      "name": "posix_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
bool posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583533487,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:868",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock",
        "fs/locks.c:posix_test_lock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583527856,
      "name": "posix_locks_conflict",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584133855,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:854",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock",
        "fs/locks.c:posix_test_lock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584127920,
      "name": "posix_locks_conflict",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584361023,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:855",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock",
        "fs/locks.c:posix_test_lock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584354736,
      "name": "posix_locks_conflict",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584579423,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:854",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock",
        "fs/locks.c:posix_test_lock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584573072,
      "name": "posix_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
bool posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493911968,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:918",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493911968,
      "name": "posix_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
bool posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227393452,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:918",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227393452,
      "name": "posix_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
bool posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287555872,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:918",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287555872,
      "name": "posix_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
bool posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273468322,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:918",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273468322,
      "name": "posix_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
bool posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582300704,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:918",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582300704,
      "name": "posix_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
bool posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582238464,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:918",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582238464,
      "name": "posix_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
bool posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582291184,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:918",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582291184,
      "name": "posix_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
bool posix_locks_conflict(struct file_lock * caller_fl, struct file_lock * sys_fl)
```

```json
{
  "name": "posix_locks_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582370464,
      "name": "posix_locks_conflict",
      "external": false,
      "loc": "fs/locks.c:918",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582370464,
      "name": "posix_locks_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
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
