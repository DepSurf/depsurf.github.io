# Function: <code>locks_insert_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void locks_insert_block(struct file_lock * blocker, struct file_lock * waiter)
```

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581336704,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:646",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:__break_lease"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581336704,
      "name": "locks_insert_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void locks_insert_block(struct file_lock * blocker, struct file_lock * waiter)
```

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581517408,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:673",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:__break_lease",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581517408,
      "name": "locks_insert_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void locks_insert_block(struct file_lock * blocker, struct file_lock * waiter)
```

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581602832,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:693",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:__break_lease",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581602832,
      "name": "locks_insert_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void locks_insert_block(struct file_lock * blocker, struct file_lock * waiter)
```

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581663536,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:693",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:__break_lease",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581663536,
      "name": "locks_insert_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void locks_insert_block(struct file_lock * blocker, struct file_lock * waiter)
```

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581808336,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:710",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:__break_lease",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581808336,
      "name": "locks_insert_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581988979,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:710",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:__break_lease",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582076707,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:825",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:__break_lease",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582238734,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:821",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:__break_lease",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582338468,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:845",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:__break_lease",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582628279,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:845",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:__break_lease",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582700511,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:845",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:__break_lease",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582729696,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:845",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:__break_lease",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583056608,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:845",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:__break_lease",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583532118,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:795",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:__break_lease",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584132470,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:781",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:__break_lease",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584359638,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:782",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:__break_lease",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584578038,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:781",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:__break_lease",
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493919820,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:845",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:__break_lease",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void locks_insert_block(struct file_lock * blocker, struct file_lock * waiter, bool (*)(struct file_lock *, struct file_lock *) conflict)
```

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227392476,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:845",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:__break_lease",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227392476,
      "name": "locks_insert_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void locks_insert_block(struct file_lock * blocker, struct file_lock * waiter, bool (*)(struct file_lock *, struct file_lock *) conflict)
```

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287554592,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:845",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:__break_lease",
        "fs/locks.c:flock_lock_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287554592,
      "name": "locks_insert_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273474478,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:845",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:__break_lease",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582307204,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:845",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:__break_lease",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582244964,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:845",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:__break_lease",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582297684,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:845",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:__break_lease",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locks_insert_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582381941,
      "name": "locks_insert_block",
      "external": false,
      "loc": "fs/locks.c:845",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:__break_lease",
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void locks_insert_block(struct file_lock * blocker, struct file_lock * waiter)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void locks_insert_block(struct file_lock * blocker, struct file_lock * waiter, bool (*)(struct file_lock *, struct file_lock *) conflict)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void locks_insert_block(struct file_lock * blocker, struct file_lock * waiter, bool (*)(struct file_lock *, struct file_lock *) conflict)
```
</details>
</li>
</ul>
