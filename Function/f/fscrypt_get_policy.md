# Function: <code>fscrypt_get_policy</code>

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
int fscrypt_get_policy(struct inode * inode, struct fscrypt_policy * policy)
```

```json
{
  "name": "fscrypt_get_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581506304,
      "name": "fscrypt_get_policy",
      "external": true,
      "loc": "fs/crypto/policy.c:135",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581506304,
      "name": "fscrypt_get_policy",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fscrypt_get_policy(struct inode * inode, union fscrypt_policy * policy)
```

```json
{
  "name": "fscrypt_get_policy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582313472,
      "name": "fscrypt_get_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:208",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex",
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582313472,
      "name": "fscrypt_get_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
int fscrypt_get_policy(struct inode * inode, union fscrypt_policy * policy)
```

```json
{
  "name": "fscrypt_get_policy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582601328,
      "name": "fscrypt_get_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:335",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex",
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582601328,
      "name": "fscrypt_get_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
int fscrypt_get_policy(struct inode * inode, union fscrypt_policy * policy)
```

```json
{
  "name": "fscrypt_get_policy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582672192,
      "name": "fscrypt_get_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:366",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex",
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582672192,
      "name": "fscrypt_get_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
int fscrypt_get_policy(struct inode * inode, union fscrypt_policy * policy)
```

```json
{
  "name": "fscrypt_get_policy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582701008,
      "name": "fscrypt_get_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:366",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex",
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582701008,
      "name": "fscrypt_get_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
int fscrypt_get_policy(struct inode * inode, union fscrypt_policy * policy)
```

```json
{
  "name": "fscrypt_get_policy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583027024,
      "name": "fscrypt_get_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:366",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex",
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583027024,
      "name": "fscrypt_get_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
int fscrypt_get_policy(struct inode * inode, union fscrypt_policy * policy)
```

```json
{
  "name": "fscrypt_get_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583499888,
      "name": "fscrypt_get_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:387",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex",
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583499888,
      "name": "fscrypt_get_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int fscrypt_get_policy(struct inode * inode, union fscrypt_policy * policy)
```

```json
{
  "name": "fscrypt_get_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584096512,
      "name": "fscrypt_get_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:407",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex",
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584096512,
      "name": "fscrypt_get_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int fscrypt_get_policy(struct inode * inode, union fscrypt_policy * policy)
```

```json
{
  "name": "fscrypt_get_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584323488,
      "name": "fscrypt_get_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:406",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex",
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584323488,
      "name": "fscrypt_get_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int fscrypt_get_policy(struct inode * inode, union fscrypt_policy * policy)
```

```json
{
  "name": "fscrypt_get_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584541088,
      "name": "fscrypt_get_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:433",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex",
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584541088,
      "name": "fscrypt_get_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int fscrypt_get_policy(struct inode * inode, union fscrypt_policy * policy)
```

```json
{
  "name": "fscrypt_get_policy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493892080,
      "name": "fscrypt_get_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:208",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex",
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493892080,
      "name": "fscrypt_get_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int fscrypt_get_policy(struct inode * inode, union fscrypt_policy * policy)
```

```json
{
  "name": "fscrypt_get_policy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227372192,
      "name": "fscrypt_get_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:208",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex",
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227372192,
      "name": "fscrypt_get_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int fscrypt_get_policy(struct inode * inode, union fscrypt_policy * policy)
```

```json
{
  "name": "fscrypt_get_policy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287528624,
      "name": "fscrypt_get_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:208",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex",
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287528624,
      "name": "fscrypt_get_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int fscrypt_get_policy(struct inode * inode, union fscrypt_policy * policy)
```

```json
{
  "name": "fscrypt_get_policy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273452054,
      "name": "fscrypt_get_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:208",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex",
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273452054,
      "name": "fscrypt_get_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int fscrypt_get_policy(struct inode * inode, union fscrypt_policy * policy)
```

```json
{
  "name": "fscrypt_get_policy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582282208,
      "name": "fscrypt_get_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:208",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex",
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582282208,
      "name": "fscrypt_get_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
int fscrypt_get_policy(struct inode * inode, union fscrypt_policy * policy)
```

```json
{
  "name": "fscrypt_get_policy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582219968,
      "name": "fscrypt_get_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:208",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex",
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582219968,
      "name": "fscrypt_get_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
int fscrypt_get_policy(struct inode * inode, union fscrypt_policy * policy)
```

```json
{
  "name": "fscrypt_get_policy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582272688,
      "name": "fscrypt_get_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:208",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex",
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582272688,
      "name": "fscrypt_get_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
int fscrypt_get_policy(struct inode * inode, union fscrypt_policy * policy)
```

```json
{
  "name": "fscrypt_get_policy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582351248,
      "name": "fscrypt_get_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:208",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex",
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582351248,
      "name": "fscrypt_get_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
int fscrypt_get_policy(struct inode * inode, struct fscrypt_policy * policy)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
int fscrypt_get_policy(struct inode * inode, struct fscrypt_policy * policy)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int fscrypt_get_policy(struct inode * inode, union fscrypt_policy * policy)
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
