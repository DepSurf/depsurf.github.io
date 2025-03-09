# Function: <code>iget5_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581107904,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1009",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdget",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581107904,
      "name": "iget5_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 519
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
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581273584,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1018",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdget",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581273584,
      "name": "iget5_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581351664,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1020",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdget",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581351664,
      "name": "iget5_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581407408,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1021",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdget",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581407408,
      "name": "iget5_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581549008,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1021",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdget",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581549008,
      "name": "iget5_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 483
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581706928,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1090",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdget",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581706928,
      "name": "iget5_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581791168,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1116",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdget",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581791168,
      "name": "iget5_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581909744,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1129",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdget",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581909744,
      "name": "iget5_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581982272,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1140",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdget",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581982272,
      "name": "iget5_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582216992,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1141",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdget",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582216992,
      "name": "iget5_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582264416,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1140",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582264416,
      "name": "iget5_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582289520,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1147",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582289520,
      "name": "iget5_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582608304,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1151",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582608304,
      "name": "iget5_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583140112,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1232",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583140112,
      "name": "iget5_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583711776,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1234",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583711776,
      "name": "iget5_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583929248,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1278",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583929248,
      "name": "iget5_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584136094,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1226",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597478273,
      "name": "iget5_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071584135824,
      "name": "iget5_locked",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493491928,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1140",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdget",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493491928,
      "name": "iget5_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227053888,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1140",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdget",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227053888,
      "name": "iget5_locked",
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287057040,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1140",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdget",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287057040,
      "name": "iget5_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273167448,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1140",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdget",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273167448,
      "name": "iget5_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581951008,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1140",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdget",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581951008,
      "name": "iget5_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581888576,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1140",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdget",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581888576,
      "name": "iget5_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581942320,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1140",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdget",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581942320,
      "name": "iget5_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct inode * iget5_locked(struct super_block * sb, long unsigned int hashval, int (*)(struct inode *, void *) test, int (*)(struct inode *, void *) set, void * data)
```

```json
{
  "name": "iget5_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582013744,
      "name": "iget5_locked",
      "external": true,
      "loc": "fs/inode.c:1140",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdget",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582013744,
      "name": "iget5_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
