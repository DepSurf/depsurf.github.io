# Function: <code>alloc_fs_context</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct fs_context * alloc_fs_context(struct file_system_type * fs_type, struct dentry * reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose)
```

```json
{
  "name": "alloc_fs_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582034624,
      "name": "alloc_fs_context",
      "external": false,
      "loc": "fs/fs_context.c:251",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:fs_context_for_submount",
        "fs/fs_context.c:fs_context_for_reconfigure",
        "fs/fs_context.c:fs_context_for_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582034624,
      "name": "alloc_fs_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
struct fs_context * alloc_fs_context(struct file_system_type * fs_type, struct dentry * reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose)
```

```json
{
  "name": "alloc_fs_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582112384,
      "name": "alloc_fs_context",
      "external": false,
      "loc": "fs/fs_context.c:251",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:fs_context_for_submount",
        "fs/fs_context.c:fs_context_for_reconfigure",
        "fs/fs_context.c:fs_context_for_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582112384,
      "name": "alloc_fs_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
struct fs_context * alloc_fs_context(struct file_system_type * fs_type, struct dentry * reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose)
```

```json
{
  "name": "alloc_fs_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582349328,
      "name": "alloc_fs_context",
      "external": false,
      "loc": "fs/fs_context.c:224",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:fs_context_for_submount",
        "fs/fs_context.c:fs_context_for_reconfigure",
        "fs/fs_context.c:fs_context_for_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582349328,
      "name": "alloc_fs_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
struct fs_context * alloc_fs_context(struct file_system_type * fs_type, struct dentry * reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose)
```

```json
{
  "name": "alloc_fs_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582401072,
      "name": "alloc_fs_context",
      "external": false,
      "loc": "fs/fs_context.c:224",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:fs_context_for_submount",
        "fs/fs_context.c:fs_context_for_reconfigure",
        "fs/fs_context.c:fs_context_for_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582401072,
      "name": "alloc_fs_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 687
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
struct fs_context * alloc_fs_context(struct file_system_type * fs_type, struct dentry * reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose)
```

```json
{
  "name": "alloc_fs_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582428320,
      "name": "alloc_fs_context",
      "external": false,
      "loc": "fs/fs_context.c:224",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:fs_context_for_submount",
        "fs/fs_context.c:fs_context_for_reconfigure",
        "fs/fs_context.c:fs_context_for_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582428320,
      "name": "alloc_fs_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
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
struct fs_context * alloc_fs_context(struct file_system_type * fs_type, struct dentry * reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose)
```

```json
{
  "name": "alloc_fs_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582751072,
      "name": "alloc_fs_context",
      "external": false,
      "loc": "fs/fs_context.c:247",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:fs_context_for_submount",
        "fs/fs_context.c:fs_context_for_reconfigure",
        "fs/fs_context.c:fs_context_for_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582751072,
      "name": "alloc_fs_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
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
struct fs_context * alloc_fs_context(struct file_system_type * fs_type, struct dentry * reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose)
```

```json
{
  "name": "alloc_fs_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583298544,
      "name": "alloc_fs_context",
      "external": false,
      "loc": "fs/fs_context.c:247",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:fs_context_for_submount",
        "fs/fs_context.c:fs_context_for_reconfigure",
        "fs/fs_context.c:fs_context_for_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583298544,
      "name": "alloc_fs_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
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
struct fs_context * alloc_fs_context(struct file_system_type * fs_type, struct dentry * reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose)
```

```json
{
  "name": "alloc_fs_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583883408,
      "name": "alloc_fs_context",
      "external": false,
      "loc": "fs/fs_context.c:247",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:fs_context_for_submount",
        "fs/fs_context.c:fs_context_for_reconfigure",
        "fs/fs_context.c:fs_context_for_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583883408,
      "name": "alloc_fs_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
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
struct fs_context * alloc_fs_context(struct file_system_type * fs_type, struct dentry * reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose)
```

```json
{
  "name": "alloc_fs_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584105104,
      "name": "alloc_fs_context",
      "external": false,
      "loc": "fs/fs_context.c:247",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:fs_context_for_submount",
        "fs/fs_context.c:fs_context_for_reconfigure",
        "fs/fs_context.c:fs_context_for_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584105104,
      "name": "alloc_fs_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
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
struct fs_context * alloc_fs_context(struct file_system_type * fs_type, struct dentry * reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose)
```

```json
{
  "name": "alloc_fs_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584321360,
      "name": "alloc_fs_context",
      "external": false,
      "loc": "fs/fs_context.c:275",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:fs_context_for_submount",
        "fs/fs_context.c:fs_context_for_reconfigure",
        "fs/fs_context.c:fs_context_for_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584321360,
      "name": "alloc_fs_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 697
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
struct fs_context * alloc_fs_context(struct file_system_type * fs_type, struct dentry * reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose)
```

```json
{
  "name": "alloc_fs_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493652816,
      "name": "alloc_fs_context",
      "external": false,
      "loc": "fs/fs_context.c:251",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:fs_context_for_submount",
        "fs/fs_context.c:fs_context_for_reconfigure",
        "fs/fs_context.c:fs_context_for_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493652816,
      "name": "alloc_fs_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
struct fs_context * alloc_fs_context(struct file_system_type * fs_type, struct dentry * reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose)
```

```json
{
  "name": "alloc_fs_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227185416,
      "name": "alloc_fs_context",
      "external": false,
      "loc": "fs/fs_context.c:251",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:fs_context_for_submount",
        "fs/fs_context.c:fs_context_for_reconfigure",
        "fs/fs_context.c:fs_context_for_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227185416,
      "name": "alloc_fs_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
struct fs_context * alloc_fs_context(struct file_system_type * fs_type, struct dentry * reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose)
```

```json
{
  "name": "alloc_fs_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287247248,
      "name": "alloc_fs_context",
      "external": false,
      "loc": "fs/fs_context.c:251",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:fs_context_for_submount",
        "fs/fs_context.c:fs_context_for_reconfigure",
        "fs/fs_context.c:fs_context_for_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287247248,
      "name": "alloc_fs_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
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
struct fs_context * alloc_fs_context(struct file_system_type * fs_type, struct dentry * reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose)
```

```json
{
  "name": "alloc_fs_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273282190,
      "name": "alloc_fs_context",
      "external": false,
      "loc": "fs/fs_context.c:251",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:fs_context_for_submount",
        "fs/fs_context.c:fs_context_for_reconfigure",
        "fs/fs_context.c:fs_context_for_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273282190,
      "name": "alloc_fs_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
struct fs_context * alloc_fs_context(struct file_system_type * fs_type, struct dentry * reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose)
```

```json
{
  "name": "alloc_fs_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582081120,
      "name": "alloc_fs_context",
      "external": false,
      "loc": "fs/fs_context.c:251",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:fs_context_for_submount",
        "fs/fs_context.c:fs_context_for_reconfigure",
        "fs/fs_context.c:fs_context_for_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582081120,
      "name": "alloc_fs_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
struct fs_context * alloc_fs_context(struct file_system_type * fs_type, struct dentry * reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose)
```

```json
{
  "name": "alloc_fs_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582018640,
      "name": "alloc_fs_context",
      "external": false,
      "loc": "fs/fs_context.c:251",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:fs_context_for_submount",
        "fs/fs_context.c:fs_context_for_reconfigure",
        "fs/fs_context.c:fs_context_for_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582018640,
      "name": "alloc_fs_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
struct fs_context * alloc_fs_context(struct file_system_type * fs_type, struct dentry * reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose)
```

```json
{
  "name": "alloc_fs_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582072400,
      "name": "alloc_fs_context",
      "external": false,
      "loc": "fs/fs_context.c:251",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:fs_context_for_submount",
        "fs/fs_context.c:fs_context_for_reconfigure",
        "fs/fs_context.c:fs_context_for_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582072400,
      "name": "alloc_fs_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
struct fs_context * alloc_fs_context(struct file_system_type * fs_type, struct dentry * reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose)
```

```json
{
  "name": "alloc_fs_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582144160,
      "name": "alloc_fs_context",
      "external": false,
      "loc": "fs/fs_context.c:251",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:fs_context_for_submount",
        "fs/fs_context.c:fs_context_for_reconfigure",
        "fs/fs_context.c:fs_context_for_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582144160,
      "name": "alloc_fs_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct fs_context * alloc_fs_context(struct file_system_type * fs_type, struct dentry * reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose)
```
</details>
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
