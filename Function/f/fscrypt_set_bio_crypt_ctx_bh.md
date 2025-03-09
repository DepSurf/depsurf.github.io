# Function: <code>fscrypt_set_bio_crypt_ctx_bh</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void fscrypt_set_bio_crypt_ctx_bh(struct bio * bio, const struct buffer_head * first_bh, gfp_t gfp_mask)
```

```json
{
  "name": "fscrypt_set_bio_crypt_ctx_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582676176,
      "name": "fscrypt_set_bio_crypt_ctx_bh",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:291",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/ext4/page-io.c:io_submit_init_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582676176,
      "name": "fscrypt_set_bio_crypt_ctx_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void fscrypt_set_bio_crypt_ctx_bh(struct bio * bio, const struct buffer_head * first_bh, gfp_t gfp_mask)
```

```json
{
  "name": "fscrypt_set_bio_crypt_ctx_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582704928,
      "name": "fscrypt_set_bio_crypt_ctx_bh",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:291",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582704928,
      "name": "fscrypt_set_bio_crypt_ctx_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void fscrypt_set_bio_crypt_ctx_bh(struct bio * bio, const struct buffer_head * first_bh, gfp_t gfp_mask)
```

```json
{
  "name": "fscrypt_set_bio_crypt_ctx_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_set_bio_crypt_ctx_bh",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:291",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592242039,
      "name": "fscrypt_set_bio_crypt_ctx_bh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071583031456,
      "name": "fscrypt_set_bio_crypt_ctx_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void fscrypt_set_bio_crypt_ctx_bh(struct bio * bio, const struct buffer_head * first_bh, gfp_t gfp_mask)
```

```json
{
  "name": "fscrypt_set_bio_crypt_ctx_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_set_bio_crypt_ctx_bh",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:323",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594021000,
      "name": "fscrypt_set_bio_crypt_ctx_bh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071583505264,
      "name": "fscrypt_set_bio_crypt_ctx_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void fscrypt_set_bio_crypt_ctx_bh(struct bio * bio, const struct buffer_head * first_bh, gfp_t gfp_mask)
```

```json
{
  "name": "fscrypt_set_bio_crypt_ctx_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_set_bio_crypt_ctx_bh",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:314",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596058979,
      "name": "fscrypt_set_bio_crypt_ctx_bh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071584102256,
      "name": "fscrypt_set_bio_crypt_ctx_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void fscrypt_set_bio_crypt_ctx_bh(struct bio * bio, const struct buffer_head * first_bh, gfp_t gfp_mask)
```

```json
{
  "name": "fscrypt_set_bio_crypt_ctx_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_set_bio_crypt_ctx_bh",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:314",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/ext4/page-io.c:ext4_bio_write_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596582820,
      "name": "fscrypt_set_bio_crypt_ctx_bh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071584329760,
      "name": "fscrypt_set_bio_crypt_ctx_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void fscrypt_set_bio_crypt_ctx_bh(struct bio * bio, const struct buffer_head * first_bh, gfp_t gfp_mask)
```

```json
{
  "name": "fscrypt_set_bio_crypt_ctx_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584546832,
      "name": "fscrypt_set_bio_crypt_ctx_bh",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:316",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/ext4/page-io.c:ext4_bio_write_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584546832,
      "name": "fscrypt_set_bio_crypt_ctx_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void fscrypt_set_bio_crypt_ctx_bh(struct bio * bio, const struct buffer_head * first_bh, gfp_t gfp_mask)
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
