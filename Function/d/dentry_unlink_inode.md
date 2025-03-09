# Function: <code>dentry_unlink_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581090463,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:355",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_delete"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581247152,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:323",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_delete",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581247152,
      "name": "dentry_unlink_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581324848,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:323",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_delete",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581324848,
      "name": "dentry_unlink_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581380624,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:355",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_delete",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581380624,
      "name": "dentry_unlink_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581522064,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:355",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_delete",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581522064,
      "name": "dentry_unlink_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581682560,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:357",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_delete",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581682560,
      "name": "dentry_unlink_inode",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581769600,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:357",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_delete",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581769600,
      "name": "dentry_unlink_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581886976,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:357",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581886976,
      "name": "dentry_unlink_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581959760,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:357",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581959760,
      "name": "dentry_unlink_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582193056,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:357",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582193056,
      "name": "dentry_unlink_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582240560,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:357",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582240560,
      "name": "dentry_unlink_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582266288,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:359",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582266288,
      "name": "dentry_unlink_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582584048,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:359",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582584048,
      "name": "dentry_unlink_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583113072,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:384",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583113072,
      "name": "dentry_unlink_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583681872,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:384",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583681872,
      "name": "dentry_unlink_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583900016,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:384",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583900016,
      "name": "dentry_unlink_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584107440,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:383",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584107440,
      "name": "dentry_unlink_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493456800,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:357",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493456800,
      "name": "dentry_unlink_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227022424,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:357",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_delete",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227022424,
      "name": "dentry_unlink_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287009520,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:357",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_delete",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287009520,
      "name": "dentry_unlink_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
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
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273140752,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:357",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273140752,
      "name": "dentry_unlink_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581928496,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:357",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581928496,
      "name": "dentry_unlink_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581866080,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:357",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581866080,
      "name": "dentry_unlink_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581919808,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:357",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581919808,
      "name": "dentry_unlink_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
void dentry_unlink_inode(struct dentry * dentry)
```

```json
{
  "name": "dentry_unlink_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581986848,
      "name": "dentry_unlink_inode",
      "external": false,
      "loc": "fs/dcache.c:357",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581986848,
      "name": "dentry_unlink_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void dentry_unlink_inode(struct dentry * dentry)
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
