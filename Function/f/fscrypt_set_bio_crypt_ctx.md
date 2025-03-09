# Function: <code>fscrypt_set_bio_crypt_ctx</code>

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
void fscrypt_set_bio_crypt_ctx(struct bio * bio, const struct inode * inode, u64 first_lblk, gfp_t gfp_mask)
```

```json
{
  "name": "fscrypt_set_bio_crypt_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582676032,
      "name": "fscrypt_set_bio_crypt_ctx",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:242",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582676032,
      "name": "fscrypt_set_bio_crypt_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void fscrypt_set_bio_crypt_ctx(struct bio * bio, const struct inode * inode, u64 first_lblk, gfp_t gfp_mask)
```

```json
{
  "name": "fscrypt_set_bio_crypt_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582704784,
      "name": "fscrypt_set_bio_crypt_ctx",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:242",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582704784,
      "name": "fscrypt_set_bio_crypt_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void fscrypt_set_bio_crypt_ctx(struct bio * bio, const struct inode * inode, u64 first_lblk, gfp_t gfp_mask)
```

```json
{
  "name": "fscrypt_set_bio_crypt_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583031041,
      "name": "fscrypt_set_bio_crypt_ctx",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:242",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592241922,
      "name": "fscrypt_set_bio_crypt_ctx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583030912,
      "name": "fscrypt_set_bio_crypt_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void fscrypt_set_bio_crypt_ctx(struct bio * bio, const struct inode * inode, u64 first_lblk, gfp_t gfp_mask)
```

```json
{
  "name": "fscrypt_set_bio_crypt_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_set_bio_crypt_ctx",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:274",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh",
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594020929,
      "name": "fscrypt_set_bio_crypt_ctx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583504432,
      "name": "fscrypt_set_bio_crypt_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void fscrypt_set_bio_crypt_ctx(struct bio * bio, const struct inode * inode, u64 first_lblk, gfp_t gfp_mask)
```

```json
{
  "name": "fscrypt_set_bio_crypt_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_set_bio_crypt_ctx",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:265",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh",
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596058908,
      "name": "fscrypt_set_bio_crypt_ctx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584101360,
      "name": "fscrypt_set_bio_crypt_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void fscrypt_set_bio_crypt_ctx(struct bio * bio, const struct inode * inode, u64 first_lblk, gfp_t gfp_mask)
```

```json
{
  "name": "fscrypt_set_bio_crypt_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_set_bio_crypt_ctx",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:265",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh",
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596582749,
      "name": "fscrypt_set_bio_crypt_ctx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584328864,
      "name": "fscrypt_set_bio_crypt_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void fscrypt_set_bio_crypt_ctx(struct bio * bio, const struct inode * inode, u64 first_lblk, gfp_t gfp_mask)
```

```json
{
  "name": "fscrypt_set_bio_crypt_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_set_bio_crypt_ctx",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:267",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh",
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597487143,
      "name": "fscrypt_set_bio_crypt_ctx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584546592,
      "name": "fscrypt_set_bio_crypt_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void fscrypt_set_bio_crypt_ctx(struct bio * bio, const struct inode * inode, u64 first_lblk, gfp_t gfp_mask)
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
