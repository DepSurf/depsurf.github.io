# Function: <code>fuse_dev_install</code>

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
void fuse_dev_install(struct fuse_dev * fud, struct fuse_conn * fc)
```

```json
{
  "name": "fuse_dev_install",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583227328,
      "name": "fuse_dev_install",
      "external": true,
      "loc": "fs/fuse/inode.c:1081",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583227328,
      "name": "fuse_dev_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void fuse_dev_install(struct fuse_dev * fud, struct fuse_conn * fc)
```

```json
{
  "name": "fuse_dev_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583555797,
      "name": "fuse_dev_install",
      "external": true,
      "loc": "fs/fuse/inode.c:1095",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_common"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583552848,
      "name": "fuse_dev_install",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_dev_install(struct fuse_dev * fud, struct fuse_conn * fc)
```

```json
{
  "name": "fuse_dev_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583667233,
      "name": "fuse_dev_install",
      "external": true,
      "loc": "fs/fuse/inode.c:1195",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_common"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583663392,
      "name": "fuse_dev_install",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_dev_install(struct fuse_dev * fud, struct fuse_conn * fc)
```

```json
{
  "name": "fuse_dev_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583688289,
      "name": "fuse_dev_install",
      "external": true,
      "loc": "fs/fuse/inode.c:1237",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_common"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583685120,
      "name": "fuse_dev_install",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_dev_install(struct fuse_dev * fud, struct fuse_conn * fc)
```

```json
{
  "name": "fuse_dev_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584049553,
      "name": "fuse_dev_install",
      "external": true,
      "loc": "fs/fuse/inode.c:1289",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_common"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584045984,
      "name": "fuse_dev_install",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_dev_install(struct fuse_dev * fud, struct fuse_conn * fc)
```

```json
{
  "name": "fuse_dev_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584638926,
      "name": "fuse_dev_install",
      "external": true,
      "loc": "fs/fuse/inode.c:1345",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_common"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584633200,
      "name": "fuse_dev_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void fuse_dev_install(struct fuse_dev * fud, struct fuse_conn * fc)
```

```json
{
  "name": "fuse_dev_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585319494,
      "name": "fuse_dev_install",
      "external": true,
      "loc": "fs/fuse/inode.c:1357",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_common"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585313616,
      "name": "fuse_dev_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void fuse_dev_install(struct fuse_dev * fud, struct fuse_conn * fc)
```

```json
{
  "name": "fuse_dev_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585549435,
      "name": "fuse_dev_install",
      "external": true,
      "loc": "fs/fuse/inode.c:1363",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_common"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585543552,
      "name": "fuse_dev_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_dev_install(struct fuse_dev * fud, struct fuse_conn * fc)
```

```json
{
  "name": "fuse_dev_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585787764,
      "name": "fuse_dev_install",
      "external": true,
      "loc": "fs/fuse/inode.c:1442",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_common"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585781360,
      "name": "fuse_dev_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void fuse_dev_install(struct fuse_dev * fud, struct fuse_conn * fc)
```

```json
{
  "name": "fuse_dev_install",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494948880,
      "name": "fuse_dev_install",
      "external": true,
      "loc": "fs/fuse/inode.c:1081",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494948880,
      "name": "fuse_dev_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void fuse_dev_install(struct fuse_dev * fud, struct fuse_conn * fc)
```

```json
{
  "name": "fuse_dev_install",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228352908,
      "name": "fuse_dev_install",
      "external": true,
      "loc": "fs/fuse/inode.c:1081",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228352908,
      "name": "fuse_dev_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void fuse_dev_install(struct fuse_dev * fud, struct fuse_conn * fc)
```

```json
{
  "name": "fuse_dev_install",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288816128,
      "name": "fuse_dev_install",
      "external": true,
      "loc": "fs/fuse/inode.c:1081",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288816128,
      "name": "fuse_dev_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void fuse_dev_install(struct fuse_dev * fud, struct fuse_conn * fc)
```

```json
{
  "name": "fuse_dev_install",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274252820,
      "name": "fuse_dev_install",
      "external": true,
      "loc": "fs/fuse/inode.c:1081",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274252820,
      "name": "fuse_dev_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void fuse_dev_install(struct fuse_dev * fud, struct fuse_conn * fc)
```

```json
{
  "name": "fuse_dev_install",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583196064,
      "name": "fuse_dev_install",
      "external": true,
      "loc": "fs/fuse/inode.c:1081",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583196064,
      "name": "fuse_dev_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void fuse_dev_install(struct fuse_dev * fud, struct fuse_conn * fc)
```

```json
{
  "name": "fuse_dev_install",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583133216,
      "name": "fuse_dev_install",
      "external": true,
      "loc": "fs/fuse/inode.c:1081",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583133216,
      "name": "fuse_dev_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void fuse_dev_install(struct fuse_dev * fud, struct fuse_conn * fc)
```

```json
{
  "name": "fuse_dev_install",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583180096,
      "name": "fuse_dev_install",
      "external": true,
      "loc": "fs/fuse/inode.c:1081",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583180096,
      "name": "fuse_dev_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void fuse_dev_install(struct fuse_dev * fud, struct fuse_conn * fc)
```

```json
{
  "name": "fuse_dev_install",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583268320,
      "name": "fuse_dev_install",
      "external": true,
      "loc": "fs/fuse/inode.c:1081",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583268320,
      "name": "fuse_dev_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void fuse_dev_install(struct fuse_dev * fud, struct fuse_conn * fc)
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
