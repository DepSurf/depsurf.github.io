# Function: <code>fsnotify_add_inode_mark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fsnotify_add_inode_mark(struct fsnotify_mark * mark, struct fsnotify_group * group, struct inode * inode, int allow_dups)
```

```json
{
  "name": "fsnotify_add_inode_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581269968,
      "name": "fsnotify_add_inode_mark",
      "external": true,
      "loc": "fs/notify/inode_mark.c:123",
      "file": "fs/notify/inode_mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581269968,
      "name": "fsnotify_add_inode_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int fsnotify_add_inode_mark(struct fsnotify_mark * mark, struct fsnotify_group * group, struct inode * inode, int allow_dups)
```

```json
{
  "name": "fsnotify_add_inode_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581435696,
      "name": "fsnotify_add_inode_mark",
      "external": true,
      "loc": "fs/notify/inode_mark.c:123",
      "file": "fs/notify/inode_mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581435696,
      "name": "fsnotify_add_inode_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int fsnotify_add_inode_mark(struct fsnotify_mark * mark, struct fsnotify_group * group, struct inode * inode, int allow_dups)
```

```json
{
  "name": "fsnotify_add_inode_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581516816,
      "name": "fsnotify_add_inode_mark",
      "external": true,
      "loc": "fs/notify/inode_mark.c:123",
      "file": "fs/notify/inode_mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581516816,
      "name": "fsnotify_add_inode_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_add_inode_mark",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580258930,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:407",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580260336,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:407",
      "file": "kernel/audit_fsnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_fsnotify.c:audit_alloc_mark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580264205,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:407",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:tag_mount"
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
  "name": "fsnotify_add_inode_mark",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580312086,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:439",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580313440,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:439",
      "file": "kernel/audit_fsnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_fsnotify.c:audit_alloc_mark"
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
  "name": "fsnotify_add_inode_mark",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580364268,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:455",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580365577,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:455",
      "file": "kernel/audit_fsnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_fsnotify.c:audit_alloc_mark"
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
  "name": "fsnotify_add_inode_mark",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580413082,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:455",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580414329,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:455",
      "file": "kernel/audit_fsnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_fsnotify.c:audit_alloc_mark"
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
  "name": "fsnotify_add_inode_mark",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580492133,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:482",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580493451,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:482",
      "file": "kernel/audit_fsnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_fsnotify.c:audit_alloc_mark"
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
  "name": "fsnotify_add_inode_mark",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580480245,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:531",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580481531,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:531",
      "file": "kernel/audit_fsnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_fsnotify.c:audit_alloc_mark"
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
  "name": "fsnotify_add_inode_mark",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580484109,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:537",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580485435,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:537",
      "file": "kernel/audit_fsnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_fsnotify.c:audit_alloc_mark"
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
  "name": "fsnotify_add_inode_mark",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580651757,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:537",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580653083,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:537",
      "file": "kernel/audit_fsnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_fsnotify.c:audit_alloc_mark"
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
  "name": "fsnotify_add_inode_mark",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580860698,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:699",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580862204,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:699",
      "file": "kernel/audit_fsnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_fsnotify.c:audit_alloc_mark"
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
  "name": "fsnotify_add_inode_mark",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581148538,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:776",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581150172,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:776",
      "file": "kernel/audit_fsnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_fsnotify.c:audit_alloc_mark"
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
  "name": "fsnotify_add_inode_mark",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581241888,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:776",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581243484,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:776",
      "file": "kernel/audit_fsnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_fsnotify.c:audit_alloc_mark"
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
  "name": "fsnotify_add_inode_mark",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581348060,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:772",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581349749,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:772",
      "file": "kernel/audit_fsnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_fsnotify.c:audit_alloc_mark"
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
  "name": "fsnotify_add_inode_mark",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491678612,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:455",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491680020,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:455",
      "file": "kernel/audit_fsnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_fsnotify.c:audit_alloc_mark"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_add_inode_mark",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225632800,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:455",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 3225634024,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:455",
      "file": "kernel/audit_fsnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_fsnotify.c:audit_alloc_mark"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_add_inode_mark",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284689452,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:455",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284691376,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:455",
      "file": "kernel/audit_fsnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_fsnotify.c:audit_alloc_mark"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_add_inode_mark",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272068454,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:455",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272069672,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:455",
      "file": "kernel/audit_fsnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_fsnotify.c:audit_alloc_mark"
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
  "name": "fsnotify_add_inode_mark",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580381882,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:455",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580383129,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:455",
      "file": "kernel/audit_fsnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_fsnotify.c:audit_alloc_mark"
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
  "name": "fsnotify_add_inode_mark",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580329050,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:455",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580330297,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:455",
      "file": "kernel/audit_fsnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_fsnotify.c:audit_alloc_mark"
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
  "name": "fsnotify_add_inode_mark",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580373130,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:455",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580374377,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:455",
      "file": "kernel/audit_fsnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_fsnotify.c:audit_alloc_mark"
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
  "name": "fsnotify_add_inode_mark",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580428650,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:455",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580429897,
      "name": "fsnotify_add_inode_mark",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:455",
      "file": "kernel/audit_fsnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_fsnotify.c:audit_alloc_mark"
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int fsnotify_add_inode_mark(struct fsnotify_mark * mark, struct fsnotify_group * group, struct inode * inode, int allow_dups)
```
</details>
</li>
</ul>
