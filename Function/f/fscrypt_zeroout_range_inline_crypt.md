# Function: <code>fscrypt_zeroout_range_inline_crypt</code>

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
int fscrypt_zeroout_range_inline_crypt(const struct inode * inode, long unsigned int lblk, sector_t pblk, unsigned int len)
```

```json
{
  "name": "fscrypt_zeroout_range_inline_crypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582673760,
      "name": "fscrypt_zeroout_range_inline_crypt",
      "external": false,
      "loc": "fs/crypto/bio.c:44",
      "file": "fs/crypto/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582673760,
      "name": "fscrypt_zeroout_range_inline_crypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 587
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
int fscrypt_zeroout_range_inline_crypt(const struct inode * inode, long unsigned int lblk, sector_t pblk, unsigned int len)
```

```json
{
  "name": "fscrypt_zeroout_range_inline_crypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582702576,
      "name": "fscrypt_zeroout_range_inline_crypt",
      "external": false,
      "loc": "fs/crypto/bio.c:44",
      "file": "fs/crypto/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582702576,
      "name": "fscrypt_zeroout_range_inline_crypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
int fscrypt_zeroout_range_inline_crypt(const struct inode * inode, long unsigned int lblk, sector_t pblk, unsigned int len)
```

```json
{
  "name": "fscrypt_zeroout_range_inline_crypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_zeroout_range_inline_crypt",
      "external": false,
      "loc": "fs/crypto/bio.c:44",
      "file": "fs/crypto/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583028592,
      "name": "fscrypt_zeroout_range_inline_crypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 581
    },
    {
      "addr": 18446744071592241685,
      "name": "fscrypt_zeroout_range_inline_crypt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int fscrypt_zeroout_range_inline_crypt(const struct inode * inode, long unsigned int lblk, sector_t pblk, unsigned int len)
```

```json
{
  "name": "fscrypt_zeroout_range_inline_crypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_zeroout_range_inline_crypt",
      "external": false,
      "loc": "fs/crypto/bio.c:46",
      "file": "fs/crypto/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583501744,
      "name": "fscrypt_zeroout_range_inline_crypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
    },
    {
      "addr": 18446744071594020421,
      "name": "fscrypt_zeroout_range_inline_crypt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
int fscrypt_zeroout_range_inline_crypt(const struct inode * inode, long unsigned int lblk, sector_t pblk, unsigned int len)
```

```json
{
  "name": "fscrypt_zeroout_range_inline_crypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_zeroout_range_inline_crypt",
      "external": false,
      "loc": "fs/crypto/bio.c:50",
      "file": "fs/crypto/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584098448,
      "name": "fscrypt_zeroout_range_inline_crypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
    },
    {
      "addr": 18446744071596058435,
      "name": "fscrypt_zeroout_range_inline_crypt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
int fscrypt_zeroout_range_inline_crypt(const struct inode * inode, long unsigned int lblk, sector_t pblk, unsigned int len)
```

```json
{
  "name": "fscrypt_zeroout_range_inline_crypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_zeroout_range_inline_crypt",
      "external": false,
      "loc": "fs/crypto/bio.c:48",
      "file": "fs/crypto/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584325200,
      "name": "fscrypt_zeroout_range_inline_crypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
    },
    {
      "addr": 18446744071596582225,
      "name": "fscrypt_zeroout_range_inline_crypt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
int fscrypt_zeroout_range_inline_crypt(const struct inode * inode, long unsigned int lblk, sector_t pblk, unsigned int len)
```

```json
{
  "name": "fscrypt_zeroout_range_inline_crypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_zeroout_range_inline_crypt",
      "external": false,
      "loc": "fs/crypto/bio.c:48",
      "file": "fs/crypto/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584543120,
      "name": "fscrypt_zeroout_range_inline_crypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
    },
    {
      "addr": 18446744071597486322,
      "name": "fscrypt_zeroout_range_inline_crypt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
int fscrypt_zeroout_range_inline_crypt(const struct inode * inode, long unsigned int lblk, sector_t pblk, unsigned int len)
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
