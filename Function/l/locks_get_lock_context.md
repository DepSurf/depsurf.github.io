# Function: <code>locks_get_lock_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581336768,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:206",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:__posix_lock_file",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": [
        "fs/locks.c:__posix_lock_file",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581336768,
      "name": "locks_get_lock_context.part.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581513520,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:205",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581513520,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581599024,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:215",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581599024,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581660000,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:215",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581660000,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581806048,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:216",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581806048,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581980368,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:216",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581980368,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582068560,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:247",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582068560,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582230352,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:248",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582230352,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582329984,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:249",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582329984,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582622688,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:249",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582622688,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582695120,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:249",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582695120,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582724224,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:249",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582724224,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583051120,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:249",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583051120,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583529888,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:173",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583529888,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584130128,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:173",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584130128,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584357344,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:174",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584357344,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584575760,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:173",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584575760,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493916280,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:249",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493916280,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227395880,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:249",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227395880,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287552176,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:249",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287552176,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273466428,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:249",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273466428,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582298720,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:249",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582298720,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582236480,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:249",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582236480,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582289200,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:249",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582289200,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```

```json
{
  "name": "locks_get_lock_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582368080,
      "name": "locks_get_lock_context",
      "external": false,
      "loc": "fs/locks.c:249",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582368080,
      "name": "locks_get_lock_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct file_lock_context * locks_get_lock_context(struct inode * inode, int type)
```
</details>
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
