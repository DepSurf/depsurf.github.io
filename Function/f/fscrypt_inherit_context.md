# Function: <code>fscrypt_inherit_context</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int fscrypt_inherit_context(struct inode * parent, struct inode * child, void * fs_data, bool preload)
```

```json
{
  "name": "fscrypt_inherit_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581507136,
      "name": "fscrypt_inherit_context",
      "external": true,
      "loc": "fs/crypto/policy.c:207",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581507136,
      "name": "fscrypt_inherit_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int fscrypt_inherit_context(struct inode * parent, struct inode * child, void * fs_data, bool preload)
```

```json
{
  "name": "fscrypt_inherit_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581592416,
      "name": "fscrypt_inherit_context",
      "external": true,
      "loc": "fs/crypto/policy.c:224",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581592416,
      "name": "fscrypt_inherit_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int fscrypt_inherit_context(struct inode * parent, struct inode * child, void * fs_data, bool preload)
```

```json
{
  "name": "fscrypt_inherit_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581652752,
      "name": "fscrypt_inherit_context",
      "external": true,
      "loc": "fs/crypto/policy.c:237",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581652752,
      "name": "fscrypt_inherit_context",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fscrypt_inherit_context(struct inode * parent, struct inode * child, void * fs_data, bool preload)
```

```json
{
  "name": "fscrypt_inherit_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581801008,
      "name": "fscrypt_inherit_context",
      "external": true,
      "loc": "fs/crypto/policy.c:238",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581801008,
      "name": "fscrypt_inherit_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int fscrypt_inherit_context(struct inode * parent, struct inode * child, void * fs_data, bool preload)
```

```json
{
  "name": "fscrypt_inherit_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581975824,
      "name": "fscrypt_inherit_context",
      "external": true,
      "loc": "fs/crypto/policy.c:238",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581975824,
      "name": "fscrypt_inherit_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int fscrypt_inherit_context(struct inode * parent, struct inode * child, void * fs_data, bool preload)
```

```json
{
  "name": "fscrypt_inherit_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582064000,
      "name": "fscrypt_inherit_context",
      "external": true,
      "loc": "fs/crypto/policy.c:239",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582064000,
      "name": "fscrypt_inherit_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int fscrypt_inherit_context(struct inode * parent, struct inode * child, void * fs_data, bool preload)
```

```json
{
  "name": "fscrypt_inherit_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582225136,
      "name": "fscrypt_inherit_context",
      "external": true,
      "loc": "fs/crypto/policy.c:240",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582225136,
      "name": "fscrypt_inherit_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int fscrypt_inherit_context(struct inode * parent, struct inode * child, void * fs_data, bool preload)
```

```json
{
  "name": "fscrypt_inherit_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582312832,
      "name": "fscrypt_inherit_context",
      "external": true,
      "loc": "fs/crypto/policy.c:469",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582312832,
      "name": "fscrypt_inherit_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int fscrypt_inherit_context(struct inode * parent, struct inode * child, void * fs_data, bool preload)
```

```json
{
  "name": "fscrypt_inherit_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582599312,
      "name": "fscrypt_inherit_context",
      "external": true,
      "loc": "fs/crypto/policy.c:618",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582599312,
      "name": "fscrypt_inherit_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int fscrypt_inherit_context(struct inode * parent, struct inode * child, void * fs_data, bool preload)
```

```json
{
  "name": "fscrypt_inherit_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493890816,
      "name": "fscrypt_inherit_context",
      "external": true,
      "loc": "fs/crypto/policy.c:469",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493890816,
      "name": "fscrypt_inherit_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int fscrypt_inherit_context(struct inode * parent, struct inode * child, void * fs_data, bool preload)
```

```json
{
  "name": "fscrypt_inherit_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227371360,
      "name": "fscrypt_inherit_context",
      "external": true,
      "loc": "fs/crypto/policy.c:469",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227371360,
      "name": "fscrypt_inherit_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int fscrypt_inherit_context(struct inode * parent, struct inode * child, void * fs_data, bool preload)
```

```json
{
  "name": "fscrypt_inherit_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287527488,
      "name": "fscrypt_inherit_context",
      "external": true,
      "loc": "fs/crypto/policy.c:469",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287527488,
      "name": "fscrypt_inherit_context",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int fscrypt_inherit_context(struct inode * parent, struct inode * child, void * fs_data, bool preload)
```

```json
{
  "name": "fscrypt_inherit_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273451246,
      "name": "fscrypt_inherit_context",
      "external": true,
      "loc": "fs/crypto/policy.c:469",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273451246,
      "name": "fscrypt_inherit_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int fscrypt_inherit_context(struct inode * parent, struct inode * child, void * fs_data, bool preload)
```

```json
{
  "name": "fscrypt_inherit_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582281568,
      "name": "fscrypt_inherit_context",
      "external": true,
      "loc": "fs/crypto/policy.c:469",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582281568,
      "name": "fscrypt_inherit_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int fscrypt_inherit_context(struct inode * parent, struct inode * child, void * fs_data, bool preload)
```

```json
{
  "name": "fscrypt_inherit_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582219328,
      "name": "fscrypt_inherit_context",
      "external": true,
      "loc": "fs/crypto/policy.c:469",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582219328,
      "name": "fscrypt_inherit_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int fscrypt_inherit_context(struct inode * parent, struct inode * child, void * fs_data, bool preload)
```

```json
{
  "name": "fscrypt_inherit_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582272048,
      "name": "fscrypt_inherit_context",
      "external": true,
      "loc": "fs/crypto/policy.c:469",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582272048,
      "name": "fscrypt_inherit_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int fscrypt_inherit_context(struct inode * parent, struct inode * child, void * fs_data, bool preload)
```

```json
{
  "name": "fscrypt_inherit_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582350608,
      "name": "fscrypt_inherit_context",
      "external": true,
      "loc": "fs/crypto/policy.c:469",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582350608,
      "name": "fscrypt_inherit_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int fscrypt_inherit_context(struct inode * parent, struct inode * child, void * fs_data, bool preload)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int fscrypt_inherit_context(struct inode * parent, struct inode * child, void * fs_data, bool preload)
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
