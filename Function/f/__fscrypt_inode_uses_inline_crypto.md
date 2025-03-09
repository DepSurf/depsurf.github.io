# Function: <code>__fscrypt_inode_uses_inline_crypto</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __fscrypt_inode_uses_inline_crypto(const struct inode * inode)
```

```json
{
  "name": "__fscrypt_inode_uses_inline_crypto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582675660,
      "name": "__fscrypt_inode_uses_inline_crypto",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:206",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio"
      ],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_read_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582675344,
      "name": "__fscrypt_inode_uses_inline_crypto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool __fscrypt_inode_uses_inline_crypto(const struct inode * inode)
```

```json
{
  "name": "__fscrypt_inode_uses_inline_crypto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582704429,
      "name": "__fscrypt_inode_uses_inline_crypto",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:206",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio"
      ],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_read_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582704112,
      "name": "__fscrypt_inode_uses_inline_crypto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool __fscrypt_inode_uses_inline_crypto(const struct inode * inode)
```

```json
{
  "name": "__fscrypt_inode_uses_inline_crypto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583031225,
      "name": "__fscrypt_inode_uses_inline_crypto",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:206",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio"
      ],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_read_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592241890,
      "name": "__fscrypt_inode_uses_inline_crypto.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583030880,
      "name": "__fscrypt_inode_uses_inline_crypto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool __fscrypt_inode_uses_inline_crypto(const struct inode * inode)
```

```json
{
  "name": "__fscrypt_inode_uses_inline_crypto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583504331,
      "name": "__fscrypt_inode_uses_inline_crypto",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:238",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/inline_crypt.c:fscrypt_dio_supported",
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio",
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx"
      ],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_read_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594020825,
      "name": "__fscrypt_inode_uses_inline_crypto.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071583504176,
      "name": "__fscrypt_inode_uses_inline_crypto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
bool __fscrypt_inode_uses_inline_crypto(const struct inode * inode)
```

```json
{
  "name": "__fscrypt_inode_uses_inline_crypto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584101766,
      "name": "__fscrypt_inode_uses_inline_crypto",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:229",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio",
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx"
      ],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_read_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596058839,
      "name": "__fscrypt_inode_uses_inline_crypto.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071584100960,
      "name": "__fscrypt_inode_uses_inline_crypto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
bool __fscrypt_inode_uses_inline_crypto(const struct inode * inode)
```

```json
{
  "name": "__fscrypt_inode_uses_inline_crypto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584329270,
      "name": "__fscrypt_inode_uses_inline_crypto",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:229",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio",
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx"
      ],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_read_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/page-io.c:ext4_bio_write_folio",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596582680,
      "name": "__fscrypt_inode_uses_inline_crypto.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071584328464,
      "name": "__fscrypt_inode_uses_inline_crypto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool __fscrypt_inode_uses_inline_crypto(const struct inode * inode)
```

```json
{
  "name": "__fscrypt_inode_uses_inline_crypto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584547158,
      "name": "__fscrypt_inode_uses_inline_crypto",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:229",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio",
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx"
      ],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_read_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/page-io.c:ext4_bio_write_folio",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597487074,
      "name": "__fscrypt_inode_uses_inline_crypto.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071584546000,
      "name": "__fscrypt_inode_uses_inline_crypto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool __fscrypt_inode_uses_inline_crypto(const struct inode * inode)
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
