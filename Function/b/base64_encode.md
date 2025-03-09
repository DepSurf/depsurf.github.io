# Function: <code>base64_encode</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int base64_encode(const u8 * src, int len, char * dst)
```

```json
{
  "name": "base64_encode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582297472,
      "name": "base64_encode",
      "external": false,
      "loc": "fs/crypto/fname.c:139",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr",
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582297472,
      "name": "base64_encode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "base64_encode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582583310,
      "name": "base64_encode",
      "external": false,
      "loc": "fs/crypto/fname.c:220",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "base64_encode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582654254,
      "name": "base64_encode",
      "external": false,
      "loc": "fs/crypto/fname.c:194",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
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
  "name": "base64_encode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582683330,
      "name": "base64_encode",
      "external": false,
      "loc": "fs/crypto/fname.c:194",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int base64_encode(const u8 * src, int srclen, char * dst)
```

```json
{
  "name": "base64_encode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587082608,
      "name": "base64_encode",
      "external": true,
      "loc": "lib/base64.c:32",
      "file": "lib/base64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587082608,
      "name": "base64_encode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
int base64_encode(const u8 * src, int srclen, char * dst)
```

```json
{
  "name": "base64_encode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "base64_encode",
      "external": true,
      "loc": "lib/base64.c:32",
      "file": "lib/base64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596641491,
      "name": "base64_encode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071587341280,
      "name": "base64_encode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int base64_encode(const u8 * src, int srclen, char * dst)
```

```json
{
  "name": "base64_encode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "base64_encode",
      "external": true,
      "loc": "lib/base64.c:32",
      "file": "lib/base64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597549556,
      "name": "base64_encode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071587624752,
      "name": "base64_encode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int base64_encode(const u8 * src, int len, char * dst)
```

```json
{
  "name": "base64_encode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493872816,
      "name": "base64_encode",
      "external": false,
      "loc": "fs/crypto/fname.c:139",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr",
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493872816,
      "name": "base64_encode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
int base64_encode(const u8 * src, int len, char * dst)
```

```json
{
  "name": "base64_encode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227355260,
      "name": "base64_encode",
      "external": false,
      "loc": "fs/crypto/fname.c:139",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr",
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227355260,
      "name": "base64_encode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int base64_encode(const u8 * src, int len, char * dst)
```

```json
{
  "name": "base64_encode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287505504,
      "name": "base64_encode",
      "external": false,
      "loc": "fs/crypto/fname.c:139",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr",
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287505504,
      "name": "base64_encode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int base64_encode(const u8 * src, int len, char * dst)
```

```json
{
  "name": "base64_encode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273437180,
      "name": "base64_encode",
      "external": false,
      "loc": "fs/crypto/fname.c:139",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr",
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273437180,
      "name": "base64_encode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
int base64_encode(const u8 * src, int len, char * dst)
```

```json
{
  "name": "base64_encode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582266208,
      "name": "base64_encode",
      "external": false,
      "loc": "fs/crypto/fname.c:139",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr",
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582266208,
      "name": "base64_encode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int base64_encode(const u8 * src, int len, char * dst)
```

```json
{
  "name": "base64_encode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582203968,
      "name": "base64_encode",
      "external": false,
      "loc": "fs/crypto/fname.c:139",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr",
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582203968,
      "name": "base64_encode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int base64_encode(const u8 * src, int len, char * dst)
```

```json
{
  "name": "base64_encode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582256688,
      "name": "base64_encode",
      "external": false,
      "loc": "fs/crypto/fname.c:139",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr",
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582256688,
      "name": "base64_encode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int base64_encode(const u8 * src, int len, char * dst)
```

```json
{
  "name": "base64_encode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582335280,
      "name": "base64_encode",
      "external": false,
      "loc": "fs/crypto/fname.c:139",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr",
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582335280,
      "name": "base64_encode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int base64_encode(const u8 * src, int len, char * dst)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int base64_encode(const u8 * src, int len, char * dst)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int base64_encode(const u8 * src, int srclen, char * dst)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
