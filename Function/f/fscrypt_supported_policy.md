# Function: <code>fscrypt_supported_policy</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool fscrypt_supported_policy(const union fscrypt_policy * policy_u, const struct inode * inode)
```

```json
{
  "name": "fscrypt_supported_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582313101,
      "name": "fscrypt_supported_policy",
      "external": true,
      "loc": "fs/crypto/policy.c:42",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582314850,
      "name": "fscrypt_supported_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071582313072,
      "name": "fscrypt_supported_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool fscrypt_supported_policy(const union fscrypt_policy * policy_u, const struct inode * inode)
```

```json
{
  "name": "fscrypt_supported_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_supported_policy",
      "external": true,
      "loc": "fs/crypto/policy.c:207",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/policy.c:set_encryption_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582602889,
      "name": "fscrypt_supported_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071582600784,
      "name": "fscrypt_supported_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
bool fscrypt_supported_policy(const union fscrypt_policy * policy_u, const struct inode * inode)
```

```json
{
  "name": "fscrypt_supported_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_supported_policy",
      "external": true,
      "loc": "fs/crypto/policy.c:237",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/policy.c:set_encryption_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591342490,
      "name": "fscrypt_supported_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071582671616,
      "name": "fscrypt_supported_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
bool fscrypt_supported_policy(const union fscrypt_policy * policy_u, const struct inode * inode)
```

```json
{
  "name": "fscrypt_supported_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_supported_policy",
      "external": true,
      "loc": "fs/crypto/policy.c:237",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/policy.c:set_encryption_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591285235,
      "name": "fscrypt_supported_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071582700416,
      "name": "fscrypt_supported_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
bool fscrypt_supported_policy(const union fscrypt_policy * policy_u, const struct inode * inode)
```

```json
{
  "name": "fscrypt_supported_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_supported_policy",
      "external": true,
      "loc": "fs/crypto/policy.c:237",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/policy.c:set_encryption_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592241389,
      "name": "fscrypt_supported_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071583026416,
      "name": "fscrypt_supported_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
bool fscrypt_supported_policy(const union fscrypt_policy * policy_u, const struct inode * inode)
```

```json
{
  "name": "fscrypt_supported_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_supported_policy",
      "external": true,
      "loc": "fs/crypto/policy.c:258",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/policy.c:set_encryption_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594020142,
      "name": "fscrypt_supported_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071583499120,
      "name": "fscrypt_supported_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
bool fscrypt_supported_policy(const union fscrypt_policy * policy_u, const struct inode * inode)
```

```json
{
  "name": "fscrypt_supported_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584095536,
      "name": "fscrypt_supported_policy",
      "external": true,
      "loc": "fs/crypto/policy.c:278",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/policy.c:set_encryption_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584095536,
      "name": "fscrypt_supported_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
bool fscrypt_supported_policy(const union fscrypt_policy * policy_u, const struct inode * inode)
```

```json
{
  "name": "fscrypt_supported_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584322512,
      "name": "fscrypt_supported_policy",
      "external": true,
      "loc": "fs/crypto/policy.c:277",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/policy.c:set_encryption_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584322512,
      "name": "fscrypt_supported_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
bool fscrypt_supported_policy(const union fscrypt_policy * policy_u, const struct inode * inode)
```

```json
{
  "name": "fscrypt_supported_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584540096,
      "name": "fscrypt_supported_policy",
      "external": true,
      "loc": "fs/crypto/policy.c:302",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/policy.c:set_encryption_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584540096,
      "name": "fscrypt_supported_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
bool fscrypt_supported_policy(const union fscrypt_policy * policy_u, const struct inode * inode)
```

```json
{
  "name": "fscrypt_supported_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493891536,
      "name": "fscrypt_supported_policy",
      "external": true,
      "loc": "fs/crypto/policy.c:42",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493891536,
      "name": "fscrypt_supported_policy",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool fscrypt_supported_policy(const union fscrypt_policy * policy_u, const struct inode * inode)
```

```json
{
  "name": "fscrypt_supported_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227371644,
      "name": "fscrypt_supported_policy",
      "external": true,
      "loc": "fs/crypto/policy.c:42",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227371644,
      "name": "fscrypt_supported_policy",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool fscrypt_supported_policy(const union fscrypt_policy * policy_u, const struct inode * inode)
```

```json
{
  "name": "fscrypt_supported_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287527920,
      "name": "fscrypt_supported_policy",
      "external": true,
      "loc": "fs/crypto/policy.c:42",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287527920,
      "name": "fscrypt_supported_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
bool fscrypt_supported_policy(const union fscrypt_policy * policy_u, const struct inode * inode)
```

```json
{
  "name": "fscrypt_supported_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273451488,
      "name": "fscrypt_supported_policy",
      "external": true,
      "loc": "fs/crypto/policy.c:42",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273451488,
      "name": "fscrypt_supported_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
bool fscrypt_supported_policy(const union fscrypt_policy * policy_u, const struct inode * inode)
```

```json
{
  "name": "fscrypt_supported_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582281837,
      "name": "fscrypt_supported_policy",
      "external": true,
      "loc": "fs/crypto/policy.c:42",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582283586,
      "name": "fscrypt_supported_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071582281808,
      "name": "fscrypt_supported_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
bool fscrypt_supported_policy(const union fscrypt_policy * policy_u, const struct inode * inode)
```

```json
{
  "name": "fscrypt_supported_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582219597,
      "name": "fscrypt_supported_policy",
      "external": true,
      "loc": "fs/crypto/policy.c:42",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582221346,
      "name": "fscrypt_supported_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071582219568,
      "name": "fscrypt_supported_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
bool fscrypt_supported_policy(const union fscrypt_policy * policy_u, const struct inode * inode)
```

```json
{
  "name": "fscrypt_supported_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582272317,
      "name": "fscrypt_supported_policy",
      "external": true,
      "loc": "fs/crypto/policy.c:42",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582274066,
      "name": "fscrypt_supported_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071582272288,
      "name": "fscrypt_supported_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
bool fscrypt_supported_policy(const union fscrypt_policy * policy_u, const struct inode * inode)
```

```json
{
  "name": "fscrypt_supported_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582350877,
      "name": "fscrypt_supported_policy",
      "external": true,
      "loc": "fs/crypto/policy.c:42",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582352626,
      "name": "fscrypt_supported_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071582350848,
      "name": "fscrypt_supported_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
bool fscrypt_supported_policy(const union fscrypt_policy * policy_u, const struct inode * inode)
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
