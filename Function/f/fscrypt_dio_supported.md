# Function: <code>fscrypt_dio_supported</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool fscrypt_dio_supported(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "fscrypt_dio_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_dio_supported",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:414",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dio_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594020867,
      "name": "fscrypt_dio_supported.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071583504224,
      "name": "fscrypt_dio_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
bool fscrypt_dio_supported(struct inode * inode)
```

```json
{
  "name": "fscrypt_dio_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584101210,
      "name": "fscrypt_dio_supported",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:406",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_dio_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596058881,
      "name": "fscrypt_dio_supported.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071584101168,
      "name": "fscrypt_dio_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
bool fscrypt_dio_supported(struct inode * inode)
```

```json
{
  "name": "fscrypt_dio_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584328714,
      "name": "fscrypt_dio_supported",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:406",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_dio_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596582722,
      "name": "fscrypt_dio_supported.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071584328672,
      "name": "fscrypt_dio_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
bool fscrypt_dio_supported(struct inode * inode)
```

```json
{
  "name": "fscrypt_dio_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584546442,
      "name": "fscrypt_dio_supported",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:408",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_dio_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597487116,
      "name": "fscrypt_dio_supported.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071584546400,
      "name": "fscrypt_dio_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
bool fscrypt_dio_supported(struct kiocb * iocb, struct iov_iter * iter)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inode * inode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kiocb * iocb</code>
</li>
<li>
<b>Param removed. </b>
<code>struct iov_iter * iter</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
