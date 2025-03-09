# Function: <code>fscrypt_decrypt_page</code>

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
int fscrypt_decrypt_page(struct page * page)
```

```json
{
  "name": "fscrypt_decrypt_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581502320,
      "name": "fscrypt_decrypt_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:277",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:completion_pages",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581502320,
      "name": "fscrypt_decrypt_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int fscrypt_decrypt_page(const struct inode * inode, struct page * page, unsigned int len, unsigned int offs, u64 lblk_num)
```

```json
{
  "name": "fscrypt_decrypt_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581587344,
      "name": "fscrypt_decrypt_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:317",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:completion_pages",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581587344,
      "name": "fscrypt_decrypt_page",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fscrypt_decrypt_page(const struct inode * inode, struct page * page, unsigned int len, unsigned int offs, u64 lblk_num)
```

```json
{
  "name": "fscrypt_decrypt_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581648144,
      "name": "fscrypt_decrypt_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:318",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581648144,
      "name": "fscrypt_decrypt_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int fscrypt_decrypt_page(const struct inode * inode, struct page * page, unsigned int len, unsigned int offs, u64 lblk_num)
```

```json
{
  "name": "fscrypt_decrypt_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581793584,
      "name": "fscrypt_decrypt_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:298",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793584,
      "name": "fscrypt_decrypt_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fscrypt_decrypt_page(const struct inode * inode, struct page * page, unsigned int len, unsigned int offs, u64 lblk_num)
```

```json
{
  "name": "fscrypt_decrypt_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581968336,
      "name": "fscrypt_decrypt_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:302",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:__fscrypt_decrypt_bio",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581968336,
      "name": "fscrypt_decrypt_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fscrypt_decrypt_page(const struct inode * inode, struct page * page, unsigned int len, unsigned int offs, u64 lblk_num)
```

```json
{
  "name": "fscrypt_decrypt_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582055248,
      "name": "fscrypt_decrypt_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:304",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:__fscrypt_decrypt_bio",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582055248,
      "name": "fscrypt_decrypt_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int fscrypt_decrypt_page(struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct inode * inode</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int len</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int offs</code>
</li>
<li>
<b>Param added. </b>
<code>u64 lblk_num</code>
</li>
<li>
<b>Param reordered. </b>
<code>page</code> ➡️ <code>inode, page, len, offs, lblk_num</code>
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int fscrypt_decrypt_page(const struct inode * inode, struct page * page, unsigned int len, unsigned int offs, u64 lblk_num)
```
</details>
</li>
</ul>
