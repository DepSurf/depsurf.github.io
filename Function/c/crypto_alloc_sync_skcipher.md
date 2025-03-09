# Function: <code>crypto_alloc_sync_skcipher</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct crypto_sync_skcipher * crypto_alloc_sync_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_sync_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583543104,
      "name": "crypto_alloc_sync_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:958",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/crypto_null.c:crypto_get_default_null_skcipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583543104,
      "name": "crypto_alloc_sync_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct crypto_sync_skcipher * crypto_alloc_sync_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_sync_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crypto_alloc_sync_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:992",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/crypto_null.c:crypto_get_default_null_skcipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583735984,
      "name": "crypto_alloc_sync_skcipher.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071583731616,
      "name": "crypto_alloc_sync_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct crypto_sync_skcipher * crypto_alloc_sync_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_sync_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583841280,
      "name": "crypto_alloc_sync_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:996",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/crypto_null.c:crypto_get_default_null_skcipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583841280,
      "name": "crypto_alloc_sync_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct crypto_sync_skcipher * crypto_alloc_sync_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_sync_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584230352,
      "name": "crypto_alloc_sync_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:765",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/crypto_null.c:crypto_get_default_null_skcipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584230352,
      "name": "crypto_alloc_sync_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct crypto_sync_skcipher * crypto_alloc_sync_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_sync_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584348960,
      "name": "crypto_alloc_sync_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:765",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/crypto_null.c:crypto_get_default_null_skcipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584348960,
      "name": "crypto_alloc_sync_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
struct crypto_sync_skcipher * crypto_alloc_sync_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_sync_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584383120,
      "name": "crypto_alloc_sync_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:760",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/crypto_null.c:crypto_get_default_null_skcipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584383120,
      "name": "crypto_alloc_sync_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
struct crypto_sync_skcipher * crypto_alloc_sync_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_sync_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584778352,
      "name": "crypto_alloc_sync_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:760",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/crypto_null.c:crypto_get_default_null_skcipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584778352,
      "name": "crypto_alloc_sync_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
struct crypto_sync_skcipher * crypto_alloc_sync_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_sync_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585463280,
      "name": "crypto_alloc_sync_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:760",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/crypto_null.c:crypto_get_default_null_skcipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585463280,
      "name": "crypto_alloc_sync_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct crypto_sync_skcipher * crypto_alloc_sync_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_sync_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586222176,
      "name": "crypto_alloc_sync_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:760",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/crypto_null.c:crypto_get_default_null_skcipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586222176,
      "name": "crypto_alloc_sync_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct crypto_sync_skcipher * crypto_alloc_sync_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_sync_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586457776,
      "name": "crypto_alloc_sync_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:807",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/crypto_null.c:crypto_get_default_null_skcipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586457776,
      "name": "crypto_alloc_sync_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct crypto_sync_skcipher * crypto_alloc_sync_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_sync_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586728864,
      "name": "crypto_alloc_sync_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:906",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/crypto_null.c:crypto_get_default_null_skcipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586728864,
      "name": "crypto_alloc_sync_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct crypto_sync_skcipher * crypto_alloc_sync_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_sync_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495654384,
      "name": "crypto_alloc_sync_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:996",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/crypto_null.c:crypto_get_default_null_skcipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495654384,
      "name": "crypto_alloc_sync_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct crypto_sync_skcipher * crypto_alloc_sync_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_sync_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229008672,
      "name": "crypto_alloc_sync_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:996",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/crypto_null.c:crypto_get_default_null_skcipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229008672,
      "name": "crypto_alloc_sync_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct crypto_sync_skcipher * crypto_alloc_sync_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_sync_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289789920,
      "name": "crypto_alloc_sync_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:996",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/crypto_null.c:crypto_get_default_null_skcipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289789920,
      "name": "crypto_alloc_sync_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct crypto_sync_skcipher * crypto_alloc_sync_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_sync_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274807286,
      "name": "crypto_alloc_sync_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:996",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/crypto_null.c:crypto_get_default_null_skcipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274807286,
      "name": "crypto_alloc_sync_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
struct crypto_sync_skcipher * crypto_alloc_sync_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_sync_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583810016,
      "name": "crypto_alloc_sync_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:996",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/crypto_null.c:crypto_get_default_null_skcipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583810016,
      "name": "crypto_alloc_sync_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct crypto_sync_skcipher * crypto_alloc_sync_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_sync_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583747072,
      "name": "crypto_alloc_sync_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:996",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/crypto_null.c:crypto_get_default_null_skcipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583747072,
      "name": "crypto_alloc_sync_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct crypto_sync_skcipher * crypto_alloc_sync_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_sync_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583793776,
      "name": "crypto_alloc_sync_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:996",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/crypto_null.c:crypto_get_default_null_skcipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583793776,
      "name": "crypto_alloc_sync_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct crypto_sync_skcipher * crypto_alloc_sync_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_sync_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583894864,
      "name": "crypto_alloc_sync_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:996",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/crypto_null.c:crypto_get_default_null_skcipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583894864,
      "name": "crypto_alloc_sync_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct crypto_sync_skcipher * crypto_alloc_sync_skcipher(const char * alg_name, u32 type, u32 mask)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
