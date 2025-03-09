# Function: <code>fuse_removexattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fuse_removexattr(struct dentry * entry, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582066016,
      "name": "fuse_removexattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1842",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582066016,
      "name": "fuse_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
int fuse_removexattr(struct dentry * entry, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582280240,
      "name": "fuse_removexattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1870",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582280240,
      "name": "fuse_removexattr",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int fuse_removexattr(struct inode * inode, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582415648,
      "name": "fuse_removexattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:176",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582415648,
      "name": "fuse_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int fuse_removexattr(struct inode * inode, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582499056,
      "name": "fuse_removexattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:151",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582499056,
      "name": "fuse_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int fuse_removexattr(struct inode * inode, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582650256,
      "name": "fuse_removexattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:151",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582650256,
      "name": "fuse_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int fuse_removexattr(struct inode * inode, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582843760,
      "name": "fuse_removexattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:151",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582843760,
      "name": "fuse_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int fuse_removexattr(struct inode * inode, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582947552,
      "name": "fuse_removexattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:151",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582947552,
      "name": "fuse_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int fuse_removexattr(struct inode * inode, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583128128,
      "name": "fuse_removexattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:151",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583128128,
      "name": "fuse_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int fuse_removexattr(struct inode * inode, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583234176,
      "name": "fuse_removexattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:151",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583234176,
      "name": "fuse_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int fuse_removexattr(struct inode * inode, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583561456,
      "name": "fuse_removexattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:151",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583561456,
      "name": "fuse_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int fuse_removexattr(struct inode * inode, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583673728,
      "name": "fuse_removexattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:154",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583673728,
      "name": "fuse_removexattr",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int fuse_removexattr(struct inode * inode, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583694800,
      "name": "fuse_removexattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:157",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583694800,
      "name": "fuse_removexattr",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int fuse_removexattr(struct inode * inode, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584055264,
      "name": "fuse_removexattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:157",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584055264,
      "name": "fuse_removexattr",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int fuse_removexattr(struct inode * inode, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584645184,
      "name": "fuse_removexattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:156",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584645184,
      "name": "fuse_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int fuse_removexattr(struct inode * inode, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585326016,
      "name": "fuse_removexattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:156",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585326016,
      "name": "fuse_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int fuse_removexattr(struct inode * inode, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585555968,
      "name": "fuse_removexattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:156",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585555968,
      "name": "fuse_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
int fuse_removexattr(struct inode * inode, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585794272,
      "name": "fuse_removexattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:156",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585794272,
      "name": "fuse_removexattr",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int fuse_removexattr(struct inode * inode, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494957088,
      "name": "fuse_removexattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:151",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494957088,
      "name": "fuse_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int fuse_removexattr(struct inode * inode, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228364936,
      "name": "fuse_removexattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:151",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228364936,
      "name": "fuse_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int fuse_removexattr(struct inode * inode, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288833216,
      "name": "fuse_removexattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:151",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288833216,
      "name": "fuse_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int fuse_removexattr(struct inode * inode, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274258460,
      "name": "fuse_removexattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:151",
      "file": "fs/fuse/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274258460,
      "name": "fuse_removexattr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446743936274259526,
      "name": "fuse_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int fuse_removexattr(struct inode * inode, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583202912,
      "name": "fuse_removexattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:151",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583202912,
      "name": "fuse_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int fuse_removexattr(struct inode * inode, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583140064,
      "name": "fuse_removexattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:151",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583140064,
      "name": "fuse_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int fuse_removexattr(struct inode * inode, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583186944,
      "name": "fuse_removexattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:151",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583186944,
      "name": "fuse_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int fuse_removexattr(struct inode * inode, const char * name)
```

```json
{
  "name": "fuse_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583280704,
      "name": "fuse_removexattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:151",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583280704,
      "name": "fuse_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inode * inode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry * entry</code>
</li>
</ul>
</details>
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
