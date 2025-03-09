# Function: <code>ext4_xattr_set_credits</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_xattr_set_credits(struct inode * inode, size_t value_len, bool is_create, int * credits)
```

```json
{
  "name": "ext4_xattr_set_credits",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582245187,
      "name": "ext4_xattr_set_credits",
      "external": true,
      "loc": "fs/ext4/xattr.c:2392",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set"
      ],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582242928,
      "name": "ext4_xattr_set_credits.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071582245024,
      "name": "ext4_xattr_set_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_xattr_set_credits(struct inode * inode, size_t value_len, bool is_create, int * credits)
```

```json
{
  "name": "ext4_xattr_set_credits",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582394147,
      "name": "ext4_xattr_set_credits",
      "external": true,
      "loc": "fs/ext4/xattr.c:2428",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set"
      ],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582391888,
      "name": "ext4_xattr_set_credits.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071582393984,
      "name": "ext4_xattr_set_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_xattr_set_credits(struct inode * inode, size_t value_len, bool is_create, int * credits)
```

```json
{
  "name": "ext4_xattr_set_credits",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582584634,
      "name": "ext4_xattr_set_credits",
      "external": true,
      "loc": "fs/ext4/xattr.c:2444",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set"
      ],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582464,
      "name": "ext4_xattr_set_credits.part.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071582584336,
      "name": "ext4_xattr_set_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_xattr_set_credits(struct inode * inode, size_t value_len, bool is_create, int * credits)
```

```json
{
  "name": "ext4_xattr_set_credits",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582686010,
      "name": "ext4_xattr_set_credits",
      "external": true,
      "loc": "fs/ext4/xattr.c:2443",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set"
      ],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582683808,
      "name": "ext4_xattr_set_credits.part.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071582685712,
      "name": "ext4_xattr_set_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_xattr_set_credits(struct inode * inode, size_t value_len, bool is_create, int * credits)
```

```json
{
  "name": "ext4_xattr_set_credits",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582859451,
      "name": "ext4_xattr_set_credits",
      "external": true,
      "loc": "fs/ext4/xattr.c:2444",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set"
      ],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582856464,
      "name": "ext4_xattr_set_credits.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071582859152,
      "name": "ext4_xattr_set_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_xattr_set_credits(struct inode * inode, size_t value_len, bool is_create, int * credits)
```

```json
{
  "name": "ext4_xattr_set_credits",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582963611,
      "name": "ext4_xattr_set_credits",
      "external": true,
      "loc": "fs/ext4/xattr.c:2444",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set"
      ],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582960624,
      "name": "ext4_xattr_set_credits.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071582963312,
      "name": "ext4_xattr_set_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int ext4_xattr_set_credits(struct inode * inode, size_t value_len, bool is_create, int * credits)
```

```json
{
  "name": "ext4_xattr_set_credits",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583278624,
      "name": "ext4_xattr_set_credits",
      "external": true,
      "loc": "fs/ext4/xattr.c:2431",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583278624,
      "name": "ext4_xattr_set_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int ext4_xattr_set_credits(struct inode * inode, size_t value_len, bool is_create, int * credits)
```

```json
{
  "name": "ext4_xattr_set_credits",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583379856,
      "name": "ext4_xattr_set_credits",
      "external": true,
      "loc": "fs/ext4/xattr.c:2437",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583379856,
      "name": "ext4_xattr_set_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int ext4_xattr_set_credits(struct inode * inode, size_t value_len, bool is_create, int * credits)
```

```json
{
  "name": "ext4_xattr_set_credits",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583402480,
      "name": "ext4_xattr_set_credits",
      "external": true,
      "loc": "fs/ext4/xattr.c:2437",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583402480,
      "name": "ext4_xattr_set_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int ext4_xattr_set_credits(struct inode * inode, size_t value_len, bool is_create, int * credits)
```

```json
{
  "name": "ext4_xattr_set_credits",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583746816,
      "name": "ext4_xattr_set_credits",
      "external": true,
      "loc": "fs/ext4/xattr.c:2420",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583746816,
      "name": "ext4_xattr_set_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int ext4_xattr_set_credits(struct inode * inode, size_t value_len, bool is_create, int * credits)
```

```json
{
  "name": "ext4_xattr_set_credits",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584303824,
      "name": "ext4_xattr_set_credits",
      "external": true,
      "loc": "fs/ext4/xattr.c:2435",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584303824,
      "name": "ext4_xattr_set_credits",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_xattr_set_credits(struct inode * inode, size_t value_len, bool is_create, int * credits)
```

```json
{
  "name": "ext4_xattr_set_credits",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584952320,
      "name": "ext4_xattr_set_credits",
      "external": true,
      "loc": "fs/ext4/xattr.c:2455",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584952320,
      "name": "ext4_xattr_set_credits",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_xattr_set_credits(struct inode * inode, size_t value_len, bool is_create, int * credits)
```

```json
{
  "name": "ext4_xattr_set_credits",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585180528,
      "name": "ext4_xattr_set_credits",
      "external": true,
      "loc": "fs/ext4/xattr.c:2498",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585180528,
      "name": "ext4_xattr_set_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int ext4_xattr_set_credits(struct inode * inode, size_t value_len, bool is_create, int * credits)
```

```json
{
  "name": "ext4_xattr_set_credits",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585413424,
      "name": "ext4_xattr_set_credits",
      "external": true,
      "loc": "fs/ext4/xattr.c:2498",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585413424,
      "name": "ext4_xattr_set_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_xattr_set_credits(struct inode * inode, size_t value_len, bool is_create, int * credits)
```

```json
{
  "name": "ext4_xattr_set_credits",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494638136,
      "name": "ext4_xattr_set_credits",
      "external": true,
      "loc": "fs/ext4/xattr.c:2444",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set"
      ],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494635744,
      "name": "ext4_xattr_set_credits.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446603336494637760,
      "name": "ext4_xattr_set_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int ext4_xattr_set_credits(struct inode * inode, size_t value_len, bool is_create, int * credits)
```

```json
{
  "name": "ext4_xattr_set_credits",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228083168,
      "name": "ext4_xattr_set_credits",
      "external": true,
      "loc": "fs/ext4/xattr.c:2444",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set"
      ],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228081012,
      "name": "ext4_xattr_set_credits.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 3228082908,
      "name": "ext4_xattr_set_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int ext4_xattr_set_credits(struct inode * inode, size_t value_len, bool is_create, int * credits)
```

```json
{
  "name": "ext4_xattr_set_credits",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288449548,
      "name": "ext4_xattr_set_credits",
      "external": true,
      "loc": "fs/ext4/xattr.c:2444",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set"
      ],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288445568,
      "name": "ext4_xattr_set_credits.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 13835058055288449152,
      "name": "ext4_xattr_set_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int ext4_xattr_set_credits(struct inode * inode, size_t value_len, bool is_create, int * credits)
```

```json
{
  "name": "ext4_xattr_set_credits",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274008262,
      "name": "ext4_xattr_set_credits",
      "external": true,
      "loc": "fs/ext4/xattr.c:2444",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set"
      ],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274006430,
      "name": "ext4_xattr_set_credits.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446743936274008090,
      "name": "ext4_xattr_set_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_xattr_set_credits(struct inode * inode, size_t value_len, bool is_create, int * credits)
```

```json
{
  "name": "ext4_xattr_set_credits",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582932347,
      "name": "ext4_xattr_set_credits",
      "external": true,
      "loc": "fs/ext4/xattr.c:2444",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set"
      ],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582929360,
      "name": "ext4_xattr_set_credits.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071582932048,
      "name": "ext4_xattr_set_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_xattr_set_credits(struct inode * inode, size_t value_len, bool is_create, int * credits)
```

```json
{
  "name": "ext4_xattr_set_credits",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582869499,
      "name": "ext4_xattr_set_credits",
      "external": true,
      "loc": "fs/ext4/xattr.c:2444",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set"
      ],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582866512,
      "name": "ext4_xattr_set_credits.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071582869200,
      "name": "ext4_xattr_set_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_xattr_set_credits(struct inode * inode, size_t value_len, bool is_create, int * credits)
```

```json
{
  "name": "ext4_xattr_set_credits",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582920955,
      "name": "ext4_xattr_set_credits",
      "external": true,
      "loc": "fs/ext4/xattr.c:2444",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set"
      ],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582917968,
      "name": "ext4_xattr_set_credits.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071582920656,
      "name": "ext4_xattr_set_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_xattr_set_credits(struct inode * inode, size_t value_len, bool is_create, int * credits)
```

```json
{
  "name": "ext4_xattr_set_credits",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583008011,
      "name": "ext4_xattr_set_credits",
      "external": true,
      "loc": "fs/ext4/xattr.c:2444",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set"
      ],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583005024,
      "name": "ext4_xattr_set_credits.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071583007712,
      "name": "ext4_xattr_set_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int ext4_xattr_set_credits(struct inode * inode, size_t value_len, bool is_create, int * credits)
```
</details>
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
