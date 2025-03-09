# Function: <code>fscrypt_new_context</code>

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
int fscrypt_new_context(union fscrypt_context * ctx_u, const union fscrypt_policy * policy_u, const u8 * nonce)
```

```json
{
  "name": "fscrypt_new_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582669920,
      "name": "fscrypt_new_context",
      "external": false,
      "loc": "fs/crypto/policy.c:260",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_set_context",
        "fs/crypto/policy.c:set_encryption_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582669920,
      "name": "fscrypt_new_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int fscrypt_new_context(union fscrypt_context * ctx_u, const union fscrypt_policy * policy_u, const u8 * nonce)
```

```json
{
  "name": "fscrypt_new_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582698736,
      "name": "fscrypt_new_context",
      "external": false,
      "loc": "fs/crypto/policy.c:260",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_set_context",
        "fs/crypto/policy.c:set_encryption_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582698736,
      "name": "fscrypt_new_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int fscrypt_new_context(union fscrypt_context * ctx_u, const union fscrypt_policy * policy_u, const u8 * nonce)
```

```json
{
  "name": "fscrypt_new_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583024736,
      "name": "fscrypt_new_context",
      "external": false,
      "loc": "fs/crypto/policy.c:260",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_set_context",
        "fs/crypto/policy.c:set_encryption_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583024736,
      "name": "fscrypt_new_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int fscrypt_new_context(union fscrypt_context * ctx_u, const union fscrypt_policy * policy_u, const u8 * nonce)
```

```json
{
  "name": "fscrypt_new_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583496992,
      "name": "fscrypt_new_context",
      "external": false,
      "loc": "fs/crypto/policy.c:281",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_set_context",
        "fs/crypto/policy.c:set_encryption_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583496992,
      "name": "fscrypt_new_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int fscrypt_new_context(union fscrypt_context * ctx_u, const union fscrypt_policy * policy_u, const u8 * nonce)
```

```json
{
  "name": "fscrypt_new_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584093104,
      "name": "fscrypt_new_context",
      "external": false,
      "loc": "fs/crypto/policy.c:301",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_set_context",
        "fs/crypto/policy.c:set_encryption_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584093104,
      "name": "fscrypt_new_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int fscrypt_new_context(union fscrypt_context * ctx_u, const union fscrypt_policy * policy_u, const u8 * nonce)
```

```json
{
  "name": "fscrypt_new_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584320064,
      "name": "fscrypt_new_context",
      "external": false,
      "loc": "fs/crypto/policy.c:300",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_set_context",
        "fs/crypto/policy.c:set_encryption_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584320064,
      "name": "fscrypt_new_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
int fscrypt_new_context(union fscrypt_context * ctx_u, const union fscrypt_policy * policy_u, const u8 * nonce)
```

```json
{
  "name": "fscrypt_new_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584537536,
      "name": "fscrypt_new_context",
      "external": false,
      "loc": "fs/crypto/policy.c:325",
      "file": "fs/crypto/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_set_context",
        "fs/crypto/policy.c:set_encryption_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584537536,
      "name": "fscrypt_new_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int fscrypt_new_context(union fscrypt_context * ctx_u, const union fscrypt_policy * policy_u, const u8 * nonce)
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
