# Function: <code>__fscrypt_decrypt_bio</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __fscrypt_decrypt_bio(struct bio * bio, bool done)
```

```json
{
  "name": "__fscrypt_decrypt_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581976048,
      "name": "__fscrypt_decrypt_bio",
      "external": false,
      "loc": "fs/crypto/bio.c:29",
      "file": "fs/crypto/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages",
        "fs/crypto/bio.c:fscrypt_decrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581976048,
      "name": "__fscrypt_decrypt_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void __fscrypt_decrypt_bio(struct bio * bio, bool done)
```

```json
{
  "name": "__fscrypt_decrypt_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582064208,
      "name": "__fscrypt_decrypt_bio",
      "external": false,
      "loc": "fs/crypto/bio.c:29",
      "file": "fs/crypto/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages",
        "fs/crypto/bio.c:fscrypt_decrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582064208,
      "name": "__fscrypt_decrypt_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __fscrypt_decrypt_bio(struct bio * bio, bool done)
```

```json
{
  "name": "__fscrypt_decrypt_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582225344,
      "name": "__fscrypt_decrypt_bio",
      "external": false,
      "loc": "fs/crypto/bio.c:29",
      "file": "fs/crypto/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages",
        "fs/crypto/bio.c:fscrypt_decrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582225344,
      "name": "__fscrypt_decrypt_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __fscrypt_decrypt_bio(struct bio * bio, bool done)
```

```json
{
  "name": "__fscrypt_decrypt_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582315056,
      "name": "__fscrypt_decrypt_bio",
      "external": false,
      "loc": "fs/crypto/bio.c:29",
      "file": "fs/crypto/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages",
        "fs/crypto/bio.c:fscrypt_decrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582315056,
      "name": "__fscrypt_decrypt_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __fscrypt_decrypt_bio(struct bio * bio, bool done)
```

```json
{
  "name": "__fscrypt_decrypt_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493895088,
      "name": "__fscrypt_decrypt_bio",
      "external": false,
      "loc": "fs/crypto/bio.c:29",
      "file": "fs/crypto/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages",
        "fs/crypto/bio.c:fscrypt_decrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493895088,
      "name": "__fscrypt_decrypt_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __fscrypt_decrypt_bio(struct bio * bio, bool done)
```

```json
{
  "name": "__fscrypt_decrypt_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227374028,
      "name": "__fscrypt_decrypt_bio",
      "external": false,
      "loc": "fs/crypto/bio.c:29",
      "file": "fs/crypto/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages",
        "fs/crypto/bio.c:fscrypt_decrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227374028,
      "name": "__fscrypt_decrypt_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __fscrypt_decrypt_bio(struct bio * bio, bool done)
```

```json
{
  "name": "__fscrypt_decrypt_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287530752,
      "name": "__fscrypt_decrypt_bio",
      "external": false,
      "loc": "fs/crypto/bio.c:29",
      "file": "fs/crypto/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages",
        "fs/crypto/bio.c:fscrypt_decrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287530752,
      "name": "__fscrypt_decrypt_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __fscrypt_decrypt_bio(struct bio * bio, bool done)
```

```json
{
  "name": "__fscrypt_decrypt_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273453124,
      "name": "__fscrypt_decrypt_bio",
      "external": false,
      "loc": "fs/crypto/bio.c:29",
      "file": "fs/crypto/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages",
        "fs/crypto/bio.c:fscrypt_decrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273453124,
      "name": "__fscrypt_decrypt_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __fscrypt_decrypt_bio(struct bio * bio, bool done)
```

```json
{
  "name": "__fscrypt_decrypt_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582283792,
      "name": "__fscrypt_decrypt_bio",
      "external": false,
      "loc": "fs/crypto/bio.c:29",
      "file": "fs/crypto/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages",
        "fs/crypto/bio.c:fscrypt_decrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582283792,
      "name": "__fscrypt_decrypt_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void __fscrypt_decrypt_bio(struct bio * bio, bool done)
```

```json
{
  "name": "__fscrypt_decrypt_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582221552,
      "name": "__fscrypt_decrypt_bio",
      "external": false,
      "loc": "fs/crypto/bio.c:29",
      "file": "fs/crypto/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages",
        "fs/crypto/bio.c:fscrypt_decrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582221552,
      "name": "__fscrypt_decrypt_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void __fscrypt_decrypt_bio(struct bio * bio, bool done)
```

```json
{
  "name": "__fscrypt_decrypt_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582274272,
      "name": "__fscrypt_decrypt_bio",
      "external": false,
      "loc": "fs/crypto/bio.c:29",
      "file": "fs/crypto/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages",
        "fs/crypto/bio.c:fscrypt_decrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582274272,
      "name": "__fscrypt_decrypt_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void __fscrypt_decrypt_bio(struct bio * bio, bool done)
```

```json
{
  "name": "__fscrypt_decrypt_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582352832,
      "name": "__fscrypt_decrypt_bio",
      "external": false,
      "loc": "fs/crypto/bio.c:29",
      "file": "fs/crypto/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages",
        "fs/crypto/bio.c:fscrypt_decrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582352832,
      "name": "__fscrypt_decrypt_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void __fscrypt_decrypt_bio(struct bio * bio, bool done)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void __fscrypt_decrypt_bio(struct bio * bio, bool done)
```
</details>
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
