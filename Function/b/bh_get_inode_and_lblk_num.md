# Function: <code>bh_get_inode_and_lblk_num</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bh_get_inode_and_lblk_num",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582675733,
      "name": "bh_get_inode_and_lblk_num",
      "external": false,
      "loc": "fs/crypto/inline_crypt.c:258",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh",
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bh_get_inode_and_lblk_num",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582704485,
      "name": "bh_get_inode_and_lblk_num",
      "external": false,
      "loc": "fs/crypto/inline_crypt.c:258",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh",
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bh_get_inode_and_lblk_num",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583031301,
      "name": "bh_get_inode_and_lblk_num",
      "external": false,
      "loc": "fs/crypto/inline_crypt.c:258",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh",
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool bh_get_inode_and_lblk_num(const struct buffer_head * bh, const struct inode * * inode_ret, u64 * lblk_num_ret)
```

```json
{
  "name": "bh_get_inode_and_lblk_num",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583505269,
      "name": "bh_get_inode_and_lblk_num",
      "external": false,
      "loc": "fs/crypto/inline_crypt.c:290",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh"
      ],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583504000,
      "name": "bh_get_inode_and_lblk_num",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071594020747,
      "name": "bh_get_inode_and_lblk_num.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool bh_get_inode_and_lblk_num(const struct buffer_head * bh, const struct inode * * inode_ret, u64 * lblk_num_ret)
```

```json
{
  "name": "bh_get_inode_and_lblk_num",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584102261,
      "name": "bh_get_inode_and_lblk_num",
      "external": false,
      "loc": "fs/crypto/inline_crypt.c:281",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh"
      ],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584100768,
      "name": "bh_get_inode_and_lblk_num",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071596058761,
      "name": "bh_get_inode_and_lblk_num.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool bh_get_inode_and_lblk_num(const struct buffer_head * bh, const struct inode * * inode_ret, u64 * lblk_num_ret)
```

```json
{
  "name": "bh_get_inode_and_lblk_num",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584329765,
      "name": "bh_get_inode_and_lblk_num",
      "external": false,
      "loc": "fs/crypto/inline_crypt.c:281",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh"
      ],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584328288,
      "name": "bh_get_inode_and_lblk_num",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071596582595,
      "name": "bh_get_inode_and_lblk_num.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
bool bh_get_inode_and_lblk_num(const struct buffer_head * bh, const struct inode * * inode_ret, u64 * lblk_num_ret)
```

```json
{
  "name": "bh_get_inode_and_lblk_num",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bh_get_inode_and_lblk_num",
      "external": false,
      "loc": "fs/crypto/inline_crypt.c:283",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh",
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584545744,
      "name": "bh_get_inode_and_lblk_num",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071597486926,
      "name": "bh_get_inode_and_lblk_num.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool bh_get_inode_and_lblk_num(const struct buffer_head * bh, const struct inode * * inode_ret, u64 * lblk_num_ret)
```
</details>
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
