# Function: <code>gcm_hash_len</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gcm_hash_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583270478,
      "name": "gcm_hash_len",
      "external": false,
      "loc": "crypto/gcm.c:245",
      "file": "crypto/gcm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_crypt_remain_continue"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gcm_hash_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583479173,
      "name": "gcm_hash_len",
      "external": false,
      "loc": "crypto/gcm.c:245",
      "file": "crypto/gcm.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gcm_hash_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583599621,
      "name": "gcm_hash_len",
      "external": false,
      "loc": "crypto/gcm.c:245",
      "file": "crypto/gcm.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gcm_hash_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583787141,
      "name": "gcm_hash_len",
      "external": false,
      "loc": "crypto/gcm.c:242",
      "file": "crypto/gcm.c",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gcm_hash_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583890085,
      "name": "gcm_hash_len",
      "external": false,
      "loc": "crypto/gcm.c:229",
      "file": "crypto/gcm.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int gcm_hash_len(struct aead_request * req, u32 flags)
```

```json
{
  "name": "gcm_hash_len",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584279664,
      "name": "gcm_hash_len",
      "external": false,
      "loc": "crypto/gcm.c:223",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:gcm_hash_crypt_remain_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584279664,
      "name": "gcm_hash_len",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int gcm_hash_len(struct aead_request * req, u32 flags)
```

```json
{
  "name": "gcm_hash_len",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584398320,
      "name": "gcm_hash_len",
      "external": false,
      "loc": "crypto/gcm.c:223",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:gcm_hash_crypt_remain_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584398320,
      "name": "gcm_hash_len",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gcm_hash_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584432651,
      "name": "gcm_hash_len",
      "external": false,
      "loc": "crypto/gcm.c:223",
      "file": "crypto/gcm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_crypt_remain_continue"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gcm_hash_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584830011,
      "name": "gcm_hash_len",
      "external": false,
      "loc": "crypto/gcm.c:223",
      "file": "crypto/gcm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_crypt_remain_continue"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gcm_hash_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "gcm_hash_len",
      "external": false,
      "loc": "crypto/gcm.c:223",
      "file": "crypto/gcm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_crypt_remain_continue"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gcm_hash_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "gcm_hash_len",
      "external": false,
      "loc": "crypto/gcm.c:223",
      "file": "crypto/gcm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_crypt_remain_continue"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int gcm_hash_len(struct aead_request * req, u32 flags)
```

```json
{
  "name": "gcm_hash_len",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586527424,
      "name": "gcm_hash_len",
      "external": false,
      "loc": "crypto/gcm.c:223",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:gcm_hash_crypt_remain_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586527424,
      "name": "gcm_hash_len",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int gcm_hash_len(struct aead_request * req, u32 flags)
```

```json
{
  "name": "gcm_hash_len",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586797456,
      "name": "gcm_hash_len",
      "external": false,
      "loc": "crypto/gcm.c:223",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:gcm_hash_crypt_remain_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586797456,
      "name": "gcm_hash_len",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
  "name": "gcm_hash_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495712364,
      "name": "gcm_hash_len",
      "external": false,
      "loc": "crypto/gcm.c:229",
      "file": "crypto/gcm.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "gcm_hash_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229064672,
      "name": "gcm_hash_len",
      "external": false,
      "loc": "crypto/gcm.c:229",
      "file": "crypto/gcm.c",
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
  "name": "gcm_hash_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289859828,
      "name": "gcm_hash_len",
      "external": false,
      "loc": "crypto/gcm.c:229",
      "file": "crypto/gcm.c",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "gcm_hash_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274859850,
      "name": "gcm_hash_len",
      "external": false,
      "loc": "crypto/gcm.c:229",
      "file": "crypto/gcm.c",
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
  "name": "gcm_hash_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583858821,
      "name": "gcm_hash_len",
      "external": false,
      "loc": "crypto/gcm.c:229",
      "file": "crypto/gcm.c",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gcm_hash_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583795877,
      "name": "gcm_hash_len",
      "external": false,
      "loc": "crypto/gcm.c:229",
      "file": "crypto/gcm.c",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gcm_hash_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583842581,
      "name": "gcm_hash_len",
      "external": false,
      "loc": "crypto/gcm.c:229",
      "file": "crypto/gcm.c",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gcm_hash_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583943653,
      "name": "gcm_hash_len",
      "external": false,
      "loc": "crypto/gcm.c:229",
      "file": "crypto/gcm.c",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int gcm_hash_len(struct aead_request * req, u32 flags)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int gcm_hash_len(struct aead_request * req, u32 flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int gcm_hash_len(struct aead_request * req, u32 flags)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
