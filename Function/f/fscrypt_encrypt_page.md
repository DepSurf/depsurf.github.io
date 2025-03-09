# Function: <code>fscrypt_encrypt_page</code>

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
struct page * fscrypt_encrypt_page(struct inode * inode, struct page * plaintext_page, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_encrypt_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581502560,
      "name": "fscrypt_encrypt_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:230",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581502560,
      "name": "fscrypt_encrypt_page",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * fscrypt_encrypt_page(const struct inode * inode, struct page * page, unsigned int len, unsigned int offs, u64 lblk_num, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_encrypt_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581587632,
      "name": "fscrypt_encrypt_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:248",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581587632,
      "name": "fscrypt_encrypt_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
struct page * fscrypt_encrypt_page(const struct inode * inode, struct page * page, unsigned int len, unsigned int offs, u64 lblk_num, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_encrypt_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581648240,
      "name": "fscrypt_encrypt_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:249",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581648240,
      "name": "fscrypt_encrypt_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
struct page * fscrypt_encrypt_page(const struct inode * inode, struct page * page, unsigned int len, unsigned int offs, u64 lblk_num, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_encrypt_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581793680,
      "name": "fscrypt_encrypt_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:229",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793680,
      "name": "fscrypt_encrypt_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
struct page * fscrypt_encrypt_page(const struct inode * inode, struct page * page, unsigned int len, unsigned int offs, u64 lblk_num, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_encrypt_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581967952,
      "name": "fscrypt_encrypt_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:233",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581967952,
      "name": "fscrypt_encrypt_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
struct page * fscrypt_encrypt_page(const struct inode * inode, struct page * page, unsigned int len, unsigned int offs, u64 lblk_num, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_encrypt_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582054864,
      "name": "fscrypt_encrypt_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:235",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582054864,
      "name": "fscrypt_encrypt_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
struct page * fscrypt_encrypt_page(struct inode * inode, struct page * plaintext_page, gfp_t gfp_flags)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct page * page</code>
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
<b>Param removed. </b>
<code>struct page * plaintext_page</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, plaintext_page, gfp_flags</code> ➡️ <code>inode, page, len, offs, lblk_num, gfp_flags</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct inode * inode</code> ➡️ <code>const struct inode * inode</code>
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
struct page * fscrypt_encrypt_page(const struct inode * inode, struct page * page, unsigned int len, unsigned int offs, u64 lblk_num, gfp_t gfp_flags)
```
</details>
</li>
</ul>
