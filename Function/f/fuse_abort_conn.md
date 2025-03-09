# Function: <code>fuse_abort_conn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_abort_conn(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582057552,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2140",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582057552,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 856
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
void fuse_abort_conn(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582271520,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2113",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582271520,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 864
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
void fuse_abort_conn(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582361056,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2085",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582361056,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 894
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
void fuse_abort_conn(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582447696,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2089",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582447696,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 866
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
void fuse_abort_conn(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582598496,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2089",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582598496,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 873
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
void fuse_abort_conn(struct fuse_conn * fc, bool is_abort)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582791072,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2096",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_sb_destroy",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582791072,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 881
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
void fuse_abort_conn(struct fuse_conn * fc, bool is_abort)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582895472,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2162",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_sb_destroy",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582895472,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 848
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
void fuse_abort_conn(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583074416,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2180",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_sb_destroy",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583074416,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 890
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
void fuse_abort_conn(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583170944,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2088",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_sb_destroy",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583170944,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 884
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
void fuse_abort_conn(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583493824,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2093",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583493824,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 955
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
void fuse_abort_conn(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583602208,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2104",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_conn_destroy",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583602208,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 955
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
void fuse_abort_conn(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583624880,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2110",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_conn_destroy",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583624880,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 922
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
void fuse_abort_conn(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583983904,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2130",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_conn_destroy",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583983904,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 922
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
void fuse_abort_conn(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584564896,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2122",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_conn_destroy",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584564896,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 961
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
void fuse_abort_conn(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585244320,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2123",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_conn_destroy",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585244320,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 965
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
void fuse_abort_conn(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585474464,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2125",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_conn_destroy",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585474464,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 961
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
void fuse_abort_conn(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585709488,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2125",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_conn_destroy",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585709488,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 961
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
void fuse_abort_conn(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494885776,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2088",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_sb_destroy",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494885776,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1316
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
void fuse_abort_conn(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228299080,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2088",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_sb_destroy",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228299080,
      "name": "fuse_abort_conn.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 880
    },
    {
      "addr": 3228299960,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void fuse_abort_conn(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288745952,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2088",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_sb_destroy",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288745952,
      "name": "fuse_abort_conn.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1332
    },
    {
      "addr": 13835058055288747296,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void fuse_abort_conn(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274201200,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2088",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_sb_destroy",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274201200,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1042
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
void fuse_abort_conn(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583139680,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2088",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_sb_destroy",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583139680,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 884
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
void fuse_abort_conn(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583076832,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2088",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_sb_destroy",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583076832,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 884
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
void fuse_abort_conn(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583123712,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2088",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_sb_destroy",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583123712,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 884
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
void fuse_abort_conn(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_abort_conn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583215984,
      "name": "fuse_abort_conn",
      "external": true,
      "loc": "fs/fuse/dev.c:2088",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/inode.c:fuse_sb_destroy",
        "fs/fuse/inode.c:fuse_umount_begin",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583215984,
      "name": "fuse_abort_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 878
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool is_abort</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool is_abort</code>
</li>
</ul>
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
