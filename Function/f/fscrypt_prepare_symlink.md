# Function: <code>fscrypt_prepare_symlink</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fscrypt_prepare_symlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582447615,
      "name": "fscrypt_prepare_symlink",
      "external": false,
      "loc": "include/linux/fscrypt.h:213",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_symlink"
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
  "name": "fscrypt_prepare_symlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582547087,
      "name": "fscrypt_prepare_symlink",
      "external": false,
      "loc": "include/linux/fscrypt.h:213",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_symlink"
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
  "name": "fscrypt_prepare_symlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582719225,
      "name": "fscrypt_prepare_symlink",
      "external": false,
      "loc": "include/linux/fscrypt.h:679",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_symlink"
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
  "name": "fscrypt_prepare_symlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582821705,
      "name": "fscrypt_prepare_symlink",
      "external": false,
      "loc": "include/linux/fscrypt.h:728",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_symlink"
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
  "name": "fscrypt_prepare_symlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583132967,
      "name": "fscrypt_prepare_symlink",
      "external": false,
      "loc": "include/linux/fscrypt.h:711",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_symlink"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int fscrypt_prepare_symlink(struct inode * dir, const char * target, unsigned int len, unsigned int max_len, struct fscrypt_str * disk_link)
```

```json
{
  "name": "fscrypt_prepare_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582656848,
      "name": "fscrypt_prepare_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:197",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582656848,
      "name": "fscrypt_prepare_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int fscrypt_prepare_symlink(struct inode * dir, const char * target, unsigned int len, unsigned int max_len, struct fscrypt_str * disk_link)
```

```json
{
  "name": "fscrypt_prepare_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582685920,
      "name": "fscrypt_prepare_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:197",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582685920,
      "name": "fscrypt_prepare_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int fscrypt_prepare_symlink(struct inode * dir, const char * target, unsigned int len, unsigned int max_len, struct fscrypt_str * disk_link)
```

```json
{
  "name": "fscrypt_prepare_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583011616,
      "name": "fscrypt_prepare_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:197",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583011616,
      "name": "fscrypt_prepare_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int fscrypt_prepare_symlink(struct inode * dir, const char * target, unsigned int len, unsigned int max_len, struct fscrypt_str * disk_link)
```

```json
{
  "name": "fscrypt_prepare_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583482384,
      "name": "fscrypt_prepare_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:197",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583482384,
      "name": "fscrypt_prepare_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int fscrypt_prepare_symlink(struct inode * dir, const char * target, unsigned int len, unsigned int max_len, struct fscrypt_str * disk_link)
```

```json
{
  "name": "fscrypt_prepare_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584077200,
      "name": "fscrypt_prepare_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:193",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584077200,
      "name": "fscrypt_prepare_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int fscrypt_prepare_symlink(struct inode * dir, const char * target, unsigned int len, unsigned int max_len, struct fscrypt_str * disk_link)
```

```json
{
  "name": "fscrypt_prepare_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584303856,
      "name": "fscrypt_prepare_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:223",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584303856,
      "name": "fscrypt_prepare_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int fscrypt_prepare_symlink(struct inode * dir, const char * target, unsigned int len, unsigned int max_len, struct fscrypt_str * disk_link)
```

```json
{
  "name": "fscrypt_prepare_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584520880,
      "name": "fscrypt_prepare_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:223",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584520880,
      "name": "fscrypt_prepare_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "fscrypt_prepare_symlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494492016,
      "name": "fscrypt_prepare_symlink",
      "external": false,
      "loc": "include/linux/fscrypt.h:728",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_symlink"
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
  "name": "fscrypt_prepare_symlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227929540,
      "name": "fscrypt_prepare_symlink",
      "external": false,
      "loc": "include/linux/fscrypt.h:728",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_symlink"
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
  "name": "fscrypt_prepare_symlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288256756,
      "name": "fscrypt_prepare_symlink",
      "external": false,
      "loc": "include/linux/fscrypt.h:728",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_symlink"
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
  "name": "fscrypt_prepare_symlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273892734,
      "name": "fscrypt_prepare_symlink",
      "external": false,
      "loc": "include/linux/fscrypt.h:728",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_symlink"
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
  "name": "fscrypt_prepare_symlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582790441,
      "name": "fscrypt_prepare_symlink",
      "external": false,
      "loc": "include/linux/fscrypt.h:728",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_symlink"
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
  "name": "fscrypt_prepare_symlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582727609,
      "name": "fscrypt_prepare_symlink",
      "external": false,
      "loc": "include/linux/fscrypt.h:728",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_symlink"
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
  "name": "fscrypt_prepare_symlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582779321,
      "name": "fscrypt_prepare_symlink",
      "external": false,
      "loc": "include/linux/fscrypt.h:728",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_symlink"
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
  "name": "fscrypt_prepare_symlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582865641,
      "name": "fscrypt_prepare_symlink",
      "external": false,
      "loc": "include/linux/fscrypt.h:728",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_symlink"
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
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int fscrypt_prepare_symlink(struct inode * dir, const char * target, unsigned int len, unsigned int max_len, struct fscrypt_str * disk_link)
```
</details>
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
