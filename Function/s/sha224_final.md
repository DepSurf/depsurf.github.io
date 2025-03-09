# Function: <code>sha224_final</code>

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
int sha224_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha224_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584289872,
      "name": "sha224_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:281",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584289872,
      "name": "sha224_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void sha224_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha224_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584699968,
      "name": "sha224_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:277",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584699968,
      "name": "sha224_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void sha224_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha224_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584812976,
      "name": "sha224_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:193",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584812976,
      "name": "sha224_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void sha224_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha224_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584857536,
      "name": "sha224_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:193",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584857536,
      "name": "sha224_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void sha224_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha224_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585278960,
      "name": "sha224_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:193",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585278960,
      "name": "sha224_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void sha224_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha224_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586130192,
      "name": "sha224_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:193",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586130192,
      "name": "sha224_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void sha224_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha224_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587120944,
      "name": "sha224_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:193",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587120944,
      "name": "sha224_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void sha224_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha224_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587383536,
      "name": "sha224_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:152",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587383536,
      "name": "sha224_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void sha224_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha224_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587670320,
      "name": "sha224_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:152",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587670320,
      "name": "sha224_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int sha224_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha224_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496174336,
      "name": "sha224_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:281",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496174336,
      "name": "sha224_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int sha224_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha224_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229497668,
      "name": "sha224_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:281",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229497668,
      "name": "sha224_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int sha224_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha224_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290441472,
      "name": "sha224_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:281",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290441472,
      "name": "sha224_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sha224_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha224_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275231278,
      "name": "sha224_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:281",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275231278,
      "name": "sha224_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int sha224_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha224_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584258608,
      "name": "sha224_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:281",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258608,
      "name": "sha224_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sha224_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha224_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584193808,
      "name": "sha224_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:281",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584193808,
      "name": "sha224_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sha224_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha224_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584242368,
      "name": "sha224_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:281",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584242368,
      "name": "sha224_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sha224_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha224_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584347200,
      "name": "sha224_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:281",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584347200,
      "name": "sha224_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sha224_final(struct sha256_state * sctx, u8 * out)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
