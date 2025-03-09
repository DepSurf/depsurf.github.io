# Function: <code>vfs_get_super</code>

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
int vfs_get_super(struct fs_context * fc, enum vfs_get_super_keying keying, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "vfs_get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581791552,
      "name": "vfs_get_super",
      "external": true,
      "loc": "fs/super.c:1156",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev",
        "fs/proc/root.c:proc_get_tree",
        "ipc/mqueue.c:mqueue_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581791552,
      "name": "vfs_get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int vfs_get_super(struct fs_context * fc, enum vfs_get_super_keying keying, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "vfs_get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581866016,
      "name": "vfs_get_super",
      "external": true,
      "loc": "fs/super.c:1162",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single_reconf",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581866016,
      "name": "vfs_get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int vfs_get_super(struct fs_context * fc, enum vfs_get_super_keying keying, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "vfs_get_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582090568,
      "name": "vfs_get_super",
      "external": true,
      "loc": "fs/super.c:1162",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev"
      ],
      "caller_func": [
        "fs/super.c:get_tree_single_reconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582092176,
      "name": "vfs_get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int vfs_get_super(struct fs_context * fc, enum vfs_get_super_keying keying, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "vfs_get_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582136600,
      "name": "vfs_get_super",
      "external": true,
      "loc": "fs/super.c:1109",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev"
      ],
      "caller_func": [
        "fs/super.c:get_tree_single_reconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582138576,
      "name": "vfs_get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int vfs_get_super(struct fs_context * fc, enum vfs_get_super_keying keying, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "vfs_get_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582161368,
      "name": "vfs_get_super",
      "external": true,
      "loc": "fs/super.c:1111",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev"
      ],
      "caller_func": [
        "fs/super.c:get_tree_single_reconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582163360,
      "name": "vfs_get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int vfs_get_super(struct fs_context * fc, enum vfs_get_super_keying keying, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "vfs_get_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582478344,
      "name": "vfs_get_super",
      "external": true,
      "loc": "fs/super.c:1111",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev"
      ],
      "caller_func": [
        "fs/super.c:get_tree_single_reconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582480336,
      "name": "vfs_get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int vfs_get_super(struct fs_context * fc, enum vfs_get_super_keying keying, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "vfs_get_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582999176,
      "name": "vfs_get_super",
      "external": true,
      "loc": "fs/super.c:1110",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev"
      ],
      "caller_func": [
        "fs/super.c:get_tree_single_reconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583001184,
      "name": "vfs_get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
int vfs_get_super(struct fs_context * fc, bool reconf, int (*)(struct super_block *, struct fs_context *) test, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "vfs_get_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583562656,
      "name": "vfs_get_super",
      "external": false,
      "loc": "fs/super.c:1128",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single_reconf",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583562656,
      "name": "vfs_get_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
int vfs_get_super(struct fs_context * fc, bool reconf, int (*)(struct super_block *, struct fs_context *) test, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "vfs_get_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583778960,
      "name": "vfs_get_super",
      "external": false,
      "loc": "fs/super.c:1139",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single_reconf",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583778960,
      "name": "vfs_get_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_get_super",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583981016,
      "name": "vfs_get_super",
      "external": false,
      "loc": "fs/super.c:1255",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev"
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
int vfs_get_super(struct fs_context * fc, enum vfs_get_super_keying keying, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "vfs_get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493337536,
      "name": "vfs_get_super",
      "external": true,
      "loc": "fs/super.c:1162",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single_reconf",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493337536,
      "name": "vfs_get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int vfs_get_super(struct fs_context * fc, enum vfs_get_super_keying keying, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "vfs_get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226931744,
      "name": "vfs_get_super",
      "external": true,
      "loc": "fs/super.c:1162",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single_reconf",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226931744,
      "name": "vfs_get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int vfs_get_super(struct fs_context * fc, enum vfs_get_super_keying keying, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "vfs_get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286880960,
      "name": "vfs_get_super",
      "external": true,
      "loc": "fs/super.c:1162",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single_reconf",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286880960,
      "name": "vfs_get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int vfs_get_super(struct fs_context * fc, enum vfs_get_super_keying keying, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "vfs_get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273068340,
      "name": "vfs_get_super",
      "external": true,
      "loc": "fs/super.c:1162",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single_reconf",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273068340,
      "name": "vfs_get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
int vfs_get_super(struct fs_context * fc, enum vfs_get_super_keying keying, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "vfs_get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581834752,
      "name": "vfs_get_super",
      "external": true,
      "loc": "fs/super.c:1162",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single_reconf",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581834752,
      "name": "vfs_get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int vfs_get_super(struct fs_context * fc, enum vfs_get_super_keying keying, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "vfs_get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581772416,
      "name": "vfs_get_super",
      "external": true,
      "loc": "fs/super.c:1162",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single_reconf",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581772416,
      "name": "vfs_get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int vfs_get_super(struct fs_context * fc, enum vfs_get_super_keying keying, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "vfs_get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581826064,
      "name": "vfs_get_super",
      "external": true,
      "loc": "fs/super.c:1162",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single_reconf",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581826064,
      "name": "vfs_get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int vfs_get_super(struct fs_context * fc, enum vfs_get_super_keying keying, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "vfs_get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581895248,
      "name": "vfs_get_super",
      "external": true,
      "loc": "fs/super.c:1162",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single_reconf",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581895248,
      "name": "vfs_get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int vfs_get_super(struct fs_context * fc, enum vfs_get_super_keying keying, int (*)(struct super_block *, struct fs_context *) fill_super)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool reconf</code>
</li>
<li>
<b>Param added. </b>
<code>int (*)(struct super_block *, struct fs_context *) test</code>
</li>
<li>
<b>Param removed. </b>
<code>enum vfs_get_super_keying keying</code>
</li>
<li>
<b>Param reordered. </b>
<code>fc, keying, fill_super</code> ➡️ <code>fc, reconf, test, fill_super</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int vfs_get_super(struct fs_context * fc, bool reconf, int (*)(struct super_block *, struct fs_context *) test, int (*)(struct super_block *, struct fs_context *) fill_super)
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
