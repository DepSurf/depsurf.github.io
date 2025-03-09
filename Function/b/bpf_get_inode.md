# Function: <code>bpf_get_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580380288,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:81",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580380288,
      "name": "bpf_get_inode.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
```

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580440352,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:81",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580440352,
      "name": "bpf_get_inode",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
```

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580494208,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:82",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj",
        "kernel/bpf/inode.c:bpf_mkobj",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580494208,
      "name": "bpf_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
```

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580522464,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:83",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj",
        "kernel/bpf/inode.c:bpf_mkobj",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580522464,
      "name": "bpf_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
```

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580584576,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:83",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj",
        "kernel/bpf/inode.c:bpf_mkobj",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580584576,
      "name": "bpf_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
```

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580679952,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:83",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580679952,
      "name": "bpf_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
```

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580750688,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:83",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580750688,
      "name": "bpf_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
```

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580833424,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:80",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580833424,
      "name": "bpf_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
```

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580884464,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:81",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580884464,
      "name": "bpf_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
```

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581022672,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:100",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mklink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581022672,
      "name": "bpf_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
```

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581028880,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:101",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581028880,
      "name": "bpf_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
```

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581040416,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:101",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581040416,
      "name": "bpf_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
```

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581263232,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:101",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581263232,
      "name": "bpf_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
```

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581554112,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:101",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581554112,
      "name": "bpf_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
```

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581926192,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:101",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581926192,
      "name": "bpf_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582111645,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:101",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582110624,
      "name": "bpf_get_inode.part.0",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582251816,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:101",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
```

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492211148,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:81",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_symlink"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492210488,
      "name": "bpf_get_inode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446603336492210640,
      "name": "bpf_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
```

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226108608,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:81",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_symlink"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226108036,
      "name": "bpf_get_inode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 3226108216,
      "name": "bpf_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
```

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285431660,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:81",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_symlink"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285430864,
      "name": "bpf_get_inode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 13835058055285431088,
      "name": "bpf_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
```

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272359946,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:81",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_symlink"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272359390,
      "name": "bpf_get_inode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446743936272359518,
      "name": "bpf_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
```

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580853264,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:81",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580853264,
      "name": "bpf_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
```

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580799440,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:81",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580799440,
      "name": "bpf_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
```

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580844512,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:81",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580844512,
      "name": "bpf_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
```

```json
{
  "name": "bpf_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580902800,
      "name": "bpf_get_inode",
      "external": false,
      "loc": "kernel/bpf/inode.c:81",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580902800,
      "name": "bpf_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
struct inode * bpf_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode)
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
