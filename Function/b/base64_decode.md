# Function: <code>base64_decode</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "base64_decode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582299228,
      "name": "base64_decode",
      "external": false,
      "loc": "fs/crypto/fname.c:158",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "base64_decode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582584521,
      "name": "base64_decode",
      "external": false,
      "loc": "fs/crypto/fname.c:239",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
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
  "name": "base64_decode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582655370,
      "name": "base64_decode",
      "external": false,
      "loc": "fs/crypto/fname.c:213",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
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
  "name": "base64_decode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582684426,
      "name": "base64_decode",
      "external": false,
      "loc": "fs/crypto/fname.c:213",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int base64_decode(const char * src, int srclen, u8 * dst)
```

```json
{
  "name": "base64_decode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "base64_decode",
      "external": true,
      "loc": "lib/base64.c:73",
      "file": "lib/base64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596115839,
      "name": "base64_decode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071587082912,
      "name": "base64_decode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int base64_decode(const char * src, int srclen, u8 * dst)
```

```json
{
  "name": "base64_decode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "base64_decode",
      "external": true,
      "loc": "lib/base64.c:73",
      "file": "lib/base64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596641575,
      "name": "base64_decode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071587341584,
      "name": "base64_decode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int base64_decode(const char * src, int srclen, u8 * dst)
```

```json
{
  "name": "base64_decode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "base64_decode",
      "external": true,
      "loc": "lib/base64.c:73",
      "file": "lib/base64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597549640,
      "name": "base64_decode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071587625056,
      "name": "base64_decode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "base64_decode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493874832,
      "name": "base64_decode",
      "external": false,
      "loc": "fs/crypto/fname.c:158",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "base64_decode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227357148,
      "name": "base64_decode",
      "external": false,
      "loc": "fs/crypto/fname.c:158",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "base64_decode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287508028,
      "name": "base64_decode",
      "external": false,
      "loc": "fs/crypto/fname.c:158",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "base64_decode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273438978,
      "name": "base64_decode",
      "external": false,
      "loc": "fs/crypto/fname.c:158",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "base64_decode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582267964,
      "name": "base64_decode",
      "external": false,
      "loc": "fs/crypto/fname.c:158",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "base64_decode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582205724,
      "name": "base64_decode",
      "external": false,
      "loc": "fs/crypto/fname.c:158",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "base64_decode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582258444,
      "name": "base64_decode",
      "external": false,
      "loc": "fs/crypto/fname.c:158",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "base64_decode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582337036,
      "name": "base64_decode",
      "external": false,
      "loc": "fs/crypto/fname.c:158",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int base64_decode(const char * src, int srclen, u8 * dst)
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
