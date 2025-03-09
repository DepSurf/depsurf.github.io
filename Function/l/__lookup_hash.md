# Function: <code>__lookup_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * __lookup_hash(struct qstr * name, struct dentry * base, unsigned int flags)
```

```json
{
  "name": "__lookup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581039904,
      "name": "__lookup_hash",
      "external": false,
      "loc": "fs/namei.c:1510",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:walk_component",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581039904,
      "name": "__lookup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
struct dentry * __lookup_hash(const struct qstr * name, struct dentry * base, unsigned int flags)
```

```json
{
  "name": "__lookup_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581199904,
      "name": "__lookup_hash",
      "external": false,
      "loc": "fs/namei.c:1519",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581199904,
      "name": "__lookup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
struct dentry * __lookup_hash(const struct qstr * name, struct dentry * base, unsigned int flags)
```

```json
{
  "name": "__lookup_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581277168,
      "name": "__lookup_hash",
      "external": false,
      "loc": "fs/namei.c:1515",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581277168,
      "name": "__lookup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
struct dentry * __lookup_hash(const struct qstr * name, struct dentry * base, unsigned int flags)
```

```json
{
  "name": "__lookup_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581326304,
      "name": "__lookup_hash",
      "external": false,
      "loc": "fs/namei.c:1522",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581326304,
      "name": "__lookup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
struct dentry * __lookup_hash(const struct qstr * name, struct dentry * base, unsigned int flags)
```

```json
{
  "name": "__lookup_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581466432,
      "name": "__lookup_hash",
      "external": false,
      "loc": "fs/namei.c:1520",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581466432,
      "name": "__lookup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
struct dentry * __lookup_hash(const struct qstr * name, struct dentry * base, unsigned int flags)
```

```json
{
  "name": "__lookup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581623520,
      "name": "__lookup_hash",
      "external": false,
      "loc": "fs/namei.c:1487",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581623520,
      "name": "__lookup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct dentry * __lookup_hash(const struct qstr * name, struct dentry * base, unsigned int flags)
```

```json
{
  "name": "__lookup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581709744,
      "name": "__lookup_hash",
      "external": false,
      "loc": "fs/namei.c:1528",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581709744,
      "name": "__lookup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct dentry * __lookup_hash(const struct qstr * name, struct dentry * base, unsigned int flags)
```

```json
{
  "name": "__lookup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581827504,
      "name": "__lookup_hash",
      "external": false,
      "loc": "fs/namei.c:1526",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581827504,
      "name": "__lookup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct dentry * __lookup_hash(const struct qstr * name, struct dentry * base, unsigned int flags)
```

```json
{
  "name": "__lookup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581900064,
      "name": "__lookup_hash",
      "external": false,
      "loc": "fs/namei.c:1521",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581900064,
      "name": "__lookup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct dentry * __lookup_hash(const struct qstr * name, struct dentry * base, unsigned int flags)
```

```json
{
  "name": "__lookup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582129424,
      "name": "__lookup_hash",
      "external": false,
      "loc": "fs/namei.c:1427",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582129424,
      "name": "__lookup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct dentry * __lookup_hash(const struct qstr * name, struct dentry * base, unsigned int flags)
```

```json
{
  "name": "__lookup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582175952,
      "name": "__lookup_hash",
      "external": false,
      "loc": "fs/namei.c:1427",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582175952,
      "name": "__lookup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct dentry * __lookup_hash(const struct qstr * name, struct dentry * base, unsigned int flags)
```

```json
{
  "name": "__lookup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582199232,
      "name": "__lookup_hash",
      "external": false,
      "loc": "fs/namei.c:1512",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582199232,
      "name": "__lookup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
struct dentry * __lookup_hash(const struct qstr * name, struct dentry * base, unsigned int flags)
```

```json
{
  "name": "__lookup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582516560,
      "name": "__lookup_hash",
      "external": false,
      "loc": "fs/namei.c:1540",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582516560,
      "name": "__lookup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
struct dentry * __lookup_hash(const struct qstr * name, struct dentry * base, unsigned int flags)
```

```json
{
  "name": "__lookup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583040992,
      "name": "__lookup_hash",
      "external": false,
      "loc": "fs/namei.c:1586",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583040992,
      "name": "__lookup_hash",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dentry * __lookup_hash(const struct qstr * name, struct dentry * base, unsigned int flags)
```

```json
{
  "name": "__lookup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583606368,
      "name": "__lookup_hash",
      "external": false,
      "loc": "fs/namei.c:1583",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583606368,
      "name": "__lookup_hash",
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
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct dentry * __lookup_hash(const struct qstr * name, struct dentry * base, unsigned int flags)
```

```json
{
  "name": "__lookup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493380176,
      "name": "__lookup_hash",
      "external": false,
      "loc": "fs/namei.c:1521",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493380176,
      "name": "__lookup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
struct dentry * __lookup_hash(const struct qstr * name, struct dentry * base, unsigned int flags)
```

```json
{
  "name": "__lookup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226968860,
      "name": "__lookup_hash",
      "external": false,
      "loc": "fs/namei.c:1521",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226968860,
      "name": "__lookup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
struct dentry * __lookup_hash(const struct qstr * name, struct dentry * base, unsigned int flags)
```

```json
{
  "name": "__lookup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286933936,
      "name": "__lookup_hash",
      "external": false,
      "loc": "fs/namei.c:1521",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286933936,
      "name": "__lookup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
struct dentry * __lookup_hash(const struct qstr * name, struct dentry * base, unsigned int flags)
```

```json
{
  "name": "__lookup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273097408,
      "name": "__lookup_hash",
      "external": false,
      "loc": "fs/namei.c:1521",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273097408,
      "name": "__lookup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
struct dentry * __lookup_hash(const struct qstr * name, struct dentry * base, unsigned int flags)
```

```json
{
  "name": "__lookup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581868800,
      "name": "__lookup_hash",
      "external": false,
      "loc": "fs/namei.c:1521",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581868800,
      "name": "__lookup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct dentry * __lookup_hash(const struct qstr * name, struct dentry * base, unsigned int flags)
```

```json
{
  "name": "__lookup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581806400,
      "name": "__lookup_hash",
      "external": false,
      "loc": "fs/namei.c:1521",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581806400,
      "name": "__lookup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct dentry * __lookup_hash(const struct qstr * name, struct dentry * base, unsigned int flags)
```

```json
{
  "name": "__lookup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581860112,
      "name": "__lookup_hash",
      "external": false,
      "loc": "fs/namei.c:1521",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581860112,
      "name": "__lookup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct dentry * __lookup_hash(const struct qstr * name, struct dentry * base, unsigned int flags)
```

```json
{
  "name": "__lookup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581931888,
      "name": "__lookup_hash",
      "external": false,
      "loc": "fs/namei.c:1521",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581931888,
      "name": "__lookup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct qstr * name</code> ➡️ <code>const struct qstr * name</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
struct dentry * __lookup_hash(const struct qstr * name, struct dentry * base, unsigned int flags)
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
