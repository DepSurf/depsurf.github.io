# Function: <code>__locks_wake_up_blocks</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __locks_wake_up_blocks(struct file_lock * blocker)
```

```json
{
  "name": "__locks_wake_up_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582069632,
      "name": "__locks_wake_up_blocks",
      "external": false,
      "loc": "fs/locks.c:734",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:locks_delete_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582069632,
      "name": "__locks_wake_up_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void __locks_wake_up_blocks(struct file_lock * blocker)
```

```json
{
  "name": "__locks_wake_up_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582231584,
      "name": "__locks_wake_up_blocks",
      "external": false,
      "loc": "fs/locks.c:730",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:__locks_insert_block",
        "fs/locks.c:locks_delete_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582231584,
      "name": "__locks_wake_up_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
void __locks_wake_up_blocks(struct file_lock * blocker)
```

```json
{
  "name": "__locks_wake_up_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582331216,
      "name": "__locks_wake_up_blocks",
      "external": false,
      "loc": "fs/locks.c:730",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:__locks_insert_block",
        "fs/locks.c:locks_delete_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582331216,
      "name": "__locks_wake_up_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void __locks_wake_up_blocks(struct file_lock * blocker)
```

```json
{
  "name": "__locks_wake_up_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582621280,
      "name": "__locks_wake_up_blocks",
      "external": false,
      "loc": "fs/locks.c:730",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:time_out_leases",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:locks_unlink_lock_ctx",
        "fs/locks.c:__locks_insert_block",
        "fs/locks.c:locks_delete_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582621280,
      "name": "__locks_wake_up_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void __locks_wake_up_blocks(struct file_lock * blocker)
```

```json
{
  "name": "__locks_wake_up_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582693712,
      "name": "__locks_wake_up_blocks",
      "external": false,
      "loc": "fs/locks.c:730",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:time_out_leases",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:locks_unlink_lock_ctx",
        "fs/locks.c:__locks_insert_block",
        "fs/locks.c:locks_delete_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582693712,
      "name": "__locks_wake_up_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void __locks_wake_up_blocks(struct file_lock * blocker)
```

```json
{
  "name": "__locks_wake_up_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582723744,
      "name": "__locks_wake_up_blocks",
      "external": false,
      "loc": "fs/locks.c:730",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:time_out_leases",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:locks_unlink_lock_ctx",
        "fs/locks.c:__locks_insert_block",
        "fs/locks.c:locks_delete_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582723744,
      "name": "__locks_wake_up_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void __locks_wake_up_blocks(struct file_lock * blocker)
```

```json
{
  "name": "__locks_wake_up_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583050640,
      "name": "__locks_wake_up_blocks",
      "external": false,
      "loc": "fs/locks.c:730",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:time_out_leases",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:locks_unlink_lock_ctx",
        "fs/locks.c:__locks_insert_block",
        "fs/locks.c:locks_delete_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583050640,
      "name": "__locks_wake_up_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void __locks_wake_up_blocks(struct file_lock * blocker)
```

```json
{
  "name": "__locks_wake_up_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583528448,
      "name": "__locks_wake_up_blocks",
      "external": false,
      "loc": "fs/locks.c:680",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:time_out_leases",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:locks_unlink_lock_ctx",
        "fs/locks.c:__locks_insert_block",
        "fs/locks.c:locks_delete_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583528448,
      "name": "__locks_wake_up_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
void __locks_wake_up_blocks(struct file_lock * blocker)
```

```json
{
  "name": "__locks_wake_up_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584128576,
      "name": "__locks_wake_up_blocks",
      "external": false,
      "loc": "fs/locks.c:666",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:time_out_leases",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:locks_unlink_lock_ctx",
        "fs/locks.c:__locks_insert_block",
        "fs/locks.c:locks_delete_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584128576,
      "name": "__locks_wake_up_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
void __locks_wake_up_blocks(struct file_lock * blocker)
```

```json
{
  "name": "__locks_wake_up_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584355776,
      "name": "__locks_wake_up_blocks",
      "external": false,
      "loc": "fs/locks.c:667",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:time_out_leases",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:locks_unlink_lock_ctx",
        "fs/locks.c:__locks_insert_block",
        "fs/locks.c:locks_delete_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584355776,
      "name": "__locks_wake_up_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
void __locks_wake_up_blocks(struct file_lock * blocker)
```

```json
{
  "name": "__locks_wake_up_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584574112,
      "name": "__locks_wake_up_blocks",
      "external": false,
      "loc": "fs/locks.c:666",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:time_out_leases",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:locks_unlink_lock_ctx",
        "fs/locks.c:__locks_insert_block",
        "fs/locks.c:locks_delete_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584574112,
      "name": "__locks_wake_up_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
void __locks_wake_up_blocks(struct file_lock * blocker)
```

```json
{
  "name": "__locks_wake_up_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493911040,
      "name": "__locks_wake_up_blocks",
      "external": false,
      "loc": "fs/locks.c:730",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:__locks_insert_block",
        "fs/locks.c:__locks_insert_block",
        "fs/locks.c:locks_delete_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493911040,
      "name": "__locks_wake_up_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void __locks_wake_up_blocks(struct file_lock * blocker)
```

```json
{
  "name": "__locks_wake_up_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227391816,
      "name": "__locks_wake_up_blocks",
      "external": false,
      "loc": "fs/locks.c:730",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:__locks_insert_block",
        "fs/locks.c:locks_delete_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227391816,
      "name": "__locks_wake_up_blocks",
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
void __locks_wake_up_blocks(struct file_lock * blocker)
```

```json
{
  "name": "__locks_wake_up_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287553536,
      "name": "__locks_wake_up_blocks",
      "external": false,
      "loc": "fs/locks.c:730",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:__locks_insert_block",
        "fs/locks.c:__locks_insert_block",
        "fs/locks.c:locks_delete_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287553536,
      "name": "__locks_wake_up_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
void __locks_wake_up_blocks(struct file_lock * blocker)
```

```json
{
  "name": "__locks_wake_up_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273467524,
      "name": "__locks_wake_up_blocks",
      "external": false,
      "loc": "fs/locks.c:730",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:__locks_insert_block",
        "fs/locks.c:locks_delete_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273467524,
      "name": "__locks_wake_up_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void __locks_wake_up_blocks(struct file_lock * blocker)
```

```json
{
  "name": "__locks_wake_up_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582299952,
      "name": "__locks_wake_up_blocks",
      "external": false,
      "loc": "fs/locks.c:730",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:__locks_insert_block",
        "fs/locks.c:locks_delete_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582299952,
      "name": "__locks_wake_up_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void __locks_wake_up_blocks(struct file_lock * blocker)
```

```json
{
  "name": "__locks_wake_up_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582237712,
      "name": "__locks_wake_up_blocks",
      "external": false,
      "loc": "fs/locks.c:730",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:__locks_insert_block",
        "fs/locks.c:locks_delete_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582237712,
      "name": "__locks_wake_up_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void __locks_wake_up_blocks(struct file_lock * blocker)
```

```json
{
  "name": "__locks_wake_up_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582290432,
      "name": "__locks_wake_up_blocks",
      "external": false,
      "loc": "fs/locks.c:730",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:__locks_insert_block",
        "fs/locks.c:locks_delete_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582290432,
      "name": "__locks_wake_up_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void __locks_wake_up_blocks(struct file_lock * blocker)
```

```json
{
  "name": "__locks_wake_up_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582369328,
      "name": "__locks_wake_up_blocks",
      "external": false,
      "loc": "fs/locks.c:730",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:__locks_insert_block",
        "fs/locks.c:locks_delete_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582369328,
      "name": "__locks_wake_up_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void __locks_wake_up_blocks(struct file_lock * blocker)
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
