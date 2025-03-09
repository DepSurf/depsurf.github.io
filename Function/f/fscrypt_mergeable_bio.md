# Function: <code>fscrypt_mergeable_bio</code>

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
bool fscrypt_mergeable_bio(struct bio * bio, const struct inode * inode, u64 next_lblk)
```

```json
{
  "name": "fscrypt_mergeable_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582675536,
      "name": "fscrypt_mergeable_bio",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:320",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582675536,
      "name": "fscrypt_mergeable_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
bool fscrypt_mergeable_bio(struct bio * bio, const struct inode * inode, u64 next_lblk)
```

```json
{
  "name": "fscrypt_mergeable_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582704304,
      "name": "fscrypt_mergeable_bio",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:320",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582704304,
      "name": "fscrypt_mergeable_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
bool fscrypt_mergeable_bio(struct bio * bio, const struct inode * inode, u64 next_lblk)
```

```json
{
  "name": "fscrypt_mergeable_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_mergeable_bio",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:320",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592241943,
      "name": "fscrypt_mergeable_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071583031088,
      "name": "fscrypt_mergeable_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
bool fscrypt_mergeable_bio(struct bio * bio, const struct inode * inode, u64 next_lblk)
```

```json
{
  "name": "fscrypt_mergeable_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_mergeable_bio",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:356",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594020950,
      "name": "fscrypt_mergeable_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583504656,
      "name": "fscrypt_mergeable_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
bool fscrypt_mergeable_bio(struct bio * bio, const struct inode * inode, u64 next_lblk)
```

```json
{
  "name": "fscrypt_mergeable_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_mergeable_bio",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:347",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596058929,
      "name": "fscrypt_mergeable_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584101600,
      "name": "fscrypt_mergeable_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
bool fscrypt_mergeable_bio(struct bio * bio, const struct inode * inode, u64 next_lblk)
```

```json
{
  "name": "fscrypt_mergeable_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_mergeable_bio",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:347",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596582770,
      "name": "fscrypt_mergeable_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584329104,
      "name": "fscrypt_mergeable_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
bool fscrypt_mergeable_bio(struct bio * bio, const struct inode * inode, u64 next_lblk)
```

```json
{
  "name": "fscrypt_mergeable_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_mergeable_bio",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:349",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597487164,
      "name": "fscrypt_mergeable_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584546992,
      "name": "fscrypt_mergeable_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
bool fscrypt_mergeable_bio(struct bio * bio, const struct inode * inode, u64 next_lblk)
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
