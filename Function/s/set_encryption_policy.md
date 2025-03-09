# Function: <code>set_encryption_policy</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_encryption_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582314016,
      "name": "set_encryption_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:231",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int set_encryption_policy(struct inode * inode, const union fscrypt_policy * policy)
```

```json
{
  "name": "set_encryption_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_encryption_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:358",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582600944,
      "name": "set_encryption_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071582603049,
      "name": "set_encryption_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int set_encryption_policy(struct inode * inode, const union fscrypt_policy * policy)
```

```json
{
  "name": "set_encryption_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_encryption_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:389",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582671776,
      "name": "set_encryption_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071591342650,
      "name": "set_encryption_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int set_encryption_policy(struct inode * inode, const union fscrypt_policy * policy)
```

```json
{
  "name": "set_encryption_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_encryption_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:389",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582700576,
      "name": "set_encryption_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071591285395,
      "name": "set_encryption_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int set_encryption_policy(struct inode * inode, const union fscrypt_policy * policy)
```

```json
{
  "name": "set_encryption_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_encryption_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:389",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583026576,
      "name": "set_encryption_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    },
    {
      "addr": 18446744071592241553,
      "name": "set_encryption_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
int set_encryption_policy(struct inode * inode, const union fscrypt_policy * policy)
```

```json
{
  "name": "set_encryption_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_encryption_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:410",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583499360,
      "name": "set_encryption_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
    },
    {
      "addr": 18446744071594020287,
      "name": "set_encryption_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int set_encryption_policy(struct inode * inode, const union fscrypt_policy * policy)
```

```json
{
  "name": "set_encryption_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_encryption_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:430",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584095872,
      "name": "set_encryption_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071596058393,
      "name": "set_encryption_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int set_encryption_policy(struct inode * inode, const union fscrypt_policy * policy)
```

```json
{
  "name": "set_encryption_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_encryption_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:429",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584322848,
      "name": "set_encryption_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071596582183,
      "name": "set_encryption_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int set_encryption_policy(struct inode * inode, const union fscrypt_policy * policy)
```

```json
{
  "name": "set_encryption_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_encryption_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:456",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584540432,
      "name": "set_encryption_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071597486245,
      "name": "set_encryption_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
  "name": "set_encryption_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493892900,
      "name": "set_encryption_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:231",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
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
  "name": "set_encryption_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227372904,
      "name": "set_encryption_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:231",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
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
  "name": "set_encryption_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287529532,
      "name": "set_encryption_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:231",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
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
  "name": "set_encryption_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273452508,
      "name": "set_encryption_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:231",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
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
  "name": "set_encryption_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582282752,
      "name": "set_encryption_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:231",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
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
  "name": "set_encryption_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582220512,
      "name": "set_encryption_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:231",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
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
  "name": "set_encryption_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582273232,
      "name": "set_encryption_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:231",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
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
  "name": "set_encryption_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582351792,
      "name": "set_encryption_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:231",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int set_encryption_policy(struct inode * inode, const union fscrypt_policy * policy)
```
</details>
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
