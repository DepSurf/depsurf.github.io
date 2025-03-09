# Function: <code>fscrypt_has_permitted_context</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581507456,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:160",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581507456,
      "name": "fscrypt_has_permitted_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581592736,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:172",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581592736,
      "name": "fscrypt_has_permitted_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581652416,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:156",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581652416,
      "name": "fscrypt_has_permitted_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581800672,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:157",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581800672,
      "name": "fscrypt_has_permitted_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581975488,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:157",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581975488,
      "name": "fscrypt_has_permitted_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582063664,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:157",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582063664,
      "name": "fscrypt_has_permitted_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582224800,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:158",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582224800,
      "name": "fscrypt_has_permitted_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582314640,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:408",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582314640,
      "name": "fscrypt_has_permitted_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582602368,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:557",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582602368,
      "name": "fscrypt_has_permitted_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582673232,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:590",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:__fscrypt_prepare_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582673232,
      "name": "fscrypt_has_permitted_context",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582702048,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:590",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:__fscrypt_prepare_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582702048,
      "name": "fscrypt_has_permitted_context",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583028064,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:590",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:__fscrypt_prepare_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583028064,
      "name": "fscrypt_has_permitted_context",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583501088,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:611",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:__fscrypt_prepare_rename",
        "fs/crypto/hooks.c:__fscrypt_prepare_rename",
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/ext4/namei.c:ext4_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583501088,
      "name": "fscrypt_has_permitted_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584097776,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:631",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:__fscrypt_prepare_rename",
        "fs/crypto/hooks.c:__fscrypt_prepare_rename",
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/ext4/namei.c:ext4_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584097776,
      "name": "fscrypt_has_permitted_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584324752,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:630",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:__fscrypt_prepare_rename",
        "fs/crypto/hooks.c:__fscrypt_prepare_rename",
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/ext4/namei.c:ext4_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584324752,
      "name": "fscrypt_has_permitted_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584542352,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:657",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:__fscrypt_prepare_rename",
        "fs/crypto/hooks.c:__fscrypt_prepare_rename",
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/ext4/namei.c:ext4_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584542352,
      "name": "fscrypt_has_permitted_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493894216,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:408",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493894216,
      "name": "fscrypt_has_permitted_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227373788,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:408",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227373788,
      "name": "fscrypt_has_permitted_context",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287530368,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:408",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287530368,
      "name": "fscrypt_has_permitted_context",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273452932,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:408",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273452932,
      "name": "fscrypt_has_permitted_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582283376,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:408",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582283376,
      "name": "fscrypt_has_permitted_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582221136,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:408",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582221136,
      "name": "fscrypt_has_permitted_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582273856,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:408",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582273856,
      "name": "fscrypt_has_permitted_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
```

```json
{
  "name": "fscrypt_has_permitted_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582352416,
      "name": "fscrypt_has_permitted_context",
      "external": true,
      "loc": "fs/crypto/policy.c:408",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582352416,
      "name": "fscrypt_has_permitted_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int fscrypt_has_permitted_context(struct inode * parent, struct inode * child)
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
