# Function: <code>list_lru_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580651232,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:109",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "fs/dcache.c:dput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580651232,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580758400,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:109",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "fs/dcache.c:dput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580758400,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580823616,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:109",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823616,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580865792,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:109",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_lru_list_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580865792,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580957008,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:109",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_lru_list_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580957008,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581093056,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:110",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_lru_add",
        "fs/inode.c:inode_lru_list_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581093056,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581171072,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:127",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_lru_add",
        "fs/inode.c:inode_lru_list_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581171072,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581242112,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:125",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_lru_add",
        "fs/inode.c:inode_lru_list_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581242112,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581300560,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:125",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_lru_add",
        "fs/inode.c:inode_lru_list_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581300560,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581491040,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:115",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_lru_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581491040,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581532688,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:115",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_lru_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581532688,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581554544,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:115",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_lru_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581554544,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581818352,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:115",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_lru_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581818352,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:119",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_lru_add",
        "fs/inode.c:inode_add_lru"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593973850,
      "name": "list_lru_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071582206352,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:119",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_lru_add",
        "fs/inode.c:inode_add_lru"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596030837,
      "name": "list_lru_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071582693232,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:119",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_lru_add",
        "fs/inode.c:inode_add_lru"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596552812,
      "name": "list_lru_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071582907152,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool list_lru_add(struct list_lru * lru, struct list_head * item, int nid, struct mem_cgroup * memcg)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:88",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/list_lru.c:list_lru_add_obj",
        "mm/zswap.c:zswap_lru_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597456588,
      "name": "list_lru_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071583080992,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492708040,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:125",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_lru_add",
        "fs/dcache.c:d_lru_add",
        "fs/inode.c:inode_lru_list_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492708040,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226544192,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:125",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_lru_add",
        "fs/inode.c:inode_lru_list_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226544192,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286044720,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:125",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_lru_add",
        "fs/dcache.c:d_lru_add",
        "fs/inode.c:inode_lru_list_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286044720,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272707688,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:125",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_lru_add",
        "fs/inode.c:inode_lru_list_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272707688,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581269408,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:125",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_lru_add",
        "fs/inode.c:inode_lru_list_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581269408,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581216064,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:125",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_lru_add",
        "fs/inode.c:inode_lru_list_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581216064,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581260608,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:125",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_lru_add",
        "fs/inode.c:inode_lru_list_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581260608,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
bool list_lru_add(struct list_lru * lru, struct list_head * item)
```

```json
{
  "name": "list_lru_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581322768,
      "name": "list_lru_add",
      "external": true,
      "loc": "mm/list_lru.c:125",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_lru_add",
        "fs/inode.c:inode_lru_list_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581322768,
      "name": "list_lru_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int nid</code>
</li>
<li>
<b>Param added. </b>
<code>struct mem_cgroup * memcg</code>
</li>
</ul>
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
