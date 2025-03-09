# Function: <code>get_tree_keyed</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int get_tree_keyed(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super, void * key)
```

```json
{
  "name": "get_tree_keyed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581866368,
      "name": "get_tree_keyed",
      "external": true,
      "loc": "fs/super.c:1241",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:proc_get_tree",
        "ipc/mqueue.c:mqueue_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581866368,
      "name": "get_tree_keyed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int get_tree_keyed(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super, void * key)
```

```json
{
  "name": "get_tree_keyed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582090528,
      "name": "get_tree_keyed",
      "external": true,
      "loc": "fs/super.c:1241",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:mqueue_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582090528,
      "name": "get_tree_keyed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int get_tree_keyed(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super, void * key)
```

```json
{
  "name": "get_tree_keyed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582136560,
      "name": "get_tree_keyed",
      "external": true,
      "loc": "fs/super.c:1188",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:mqueue_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582136560,
      "name": "get_tree_keyed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int get_tree_keyed(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super, void * key)
```

```json
{
  "name": "get_tree_keyed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582161328,
      "name": "get_tree_keyed",
      "external": true,
      "loc": "fs/super.c:1190",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:mqueue_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582161328,
      "name": "get_tree_keyed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int get_tree_keyed(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super, void * key)
```

```json
{
  "name": "get_tree_keyed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582478304,
      "name": "get_tree_keyed",
      "external": true,
      "loc": "fs/super.c:1190",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:mqueue_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582478304,
      "name": "get_tree_keyed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int get_tree_keyed(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super, void * key)
```

```json
{
  "name": "get_tree_keyed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582999136,
      "name": "get_tree_keyed",
      "external": true,
      "loc": "fs/super.c:1189",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:mqueue_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582999136,
      "name": "get_tree_keyed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int get_tree_keyed(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super, void * key)
```

```json
{
  "name": "get_tree_keyed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583563120,
      "name": "get_tree_keyed",
      "external": true,
      "loc": "fs/super.c:1190",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:mqueue_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583563120,
      "name": "get_tree_keyed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int get_tree_keyed(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super, void * key)
```

```json
{
  "name": "get_tree_keyed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583779424,
      "name": "get_tree_keyed",
      "external": true,
      "loc": "fs/super.c:1201",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:mqueue_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583779424,
      "name": "get_tree_keyed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int get_tree_keyed(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super, void * key)
```

```json
{
  "name": "get_tree_keyed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583980976,
      "name": "get_tree_keyed",
      "external": true,
      "loc": "fs/super.c:1299",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:mqueue_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583980976,
      "name": "get_tree_keyed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int get_tree_keyed(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super, void * key)
```

```json
{
  "name": "get_tree_keyed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493338000,
      "name": "get_tree_keyed",
      "external": true,
      "loc": "fs/super.c:1241",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:proc_get_tree",
        "ipc/mqueue.c:mqueue_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493338000,
      "name": "get_tree_keyed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int get_tree_keyed(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super, void * key)
```

```json
{
  "name": "get_tree_keyed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226932096,
      "name": "get_tree_keyed",
      "external": true,
      "loc": "fs/super.c:1241",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:proc_get_tree",
        "ipc/mqueue.c:mqueue_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226932096,
      "name": "get_tree_keyed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int get_tree_keyed(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super, void * key)
```

```json
{
  "name": "get_tree_keyed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286881488,
      "name": "get_tree_keyed",
      "external": true,
      "loc": "fs/super.c:1241",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:proc_get_tree",
        "ipc/mqueue.c:mqueue_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286881488,
      "name": "get_tree_keyed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int get_tree_keyed(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super, void * key)
```

```json
{
  "name": "get_tree_keyed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273068730,
      "name": "get_tree_keyed",
      "external": true,
      "loc": "fs/super.c:1241",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:proc_get_tree",
        "ipc/mqueue.c:mqueue_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273068730,
      "name": "get_tree_keyed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int get_tree_keyed(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super, void * key)
```

```json
{
  "name": "get_tree_keyed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581835104,
      "name": "get_tree_keyed",
      "external": true,
      "loc": "fs/super.c:1241",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:proc_get_tree",
        "ipc/mqueue.c:mqueue_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581835104,
      "name": "get_tree_keyed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int get_tree_keyed(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super, void * key)
```

```json
{
  "name": "get_tree_keyed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581772768,
      "name": "get_tree_keyed",
      "external": true,
      "loc": "fs/super.c:1241",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:proc_get_tree",
        "ipc/mqueue.c:mqueue_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581772768,
      "name": "get_tree_keyed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int get_tree_keyed(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super, void * key)
```

```json
{
  "name": "get_tree_keyed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581826416,
      "name": "get_tree_keyed",
      "external": true,
      "loc": "fs/super.c:1241",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:proc_get_tree",
        "ipc/mqueue.c:mqueue_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581826416,
      "name": "get_tree_keyed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int get_tree_keyed(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super, void * key)
```

```json
{
  "name": "get_tree_keyed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581895600,
      "name": "get_tree_keyed",
      "external": true,
      "loc": "fs/super.c:1241",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:proc_get_tree",
        "ipc/mqueue.c:mqueue_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581895600,
      "name": "get_tree_keyed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int get_tree_keyed(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super, void * key)
```
</details>
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
