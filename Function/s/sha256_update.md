# Function: <code>sha256_update</code>

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
int sha256_update(struct sha256_state * sctx, const u8 * data, unsigned int len)
```

```json
{
  "name": "sha256_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584289344,
      "name": "sha256_update",
      "external": true,
      "loc": "lib/crypto/sha256.c:209",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup",
        "crypto/sha256_generic.c:crypto_sha256_update",
        "lib/crypto/sha256.c:__sha256_final",
        "lib/crypto/sha256.c:__sha256_final",
        "lib/crypto/sha256.c:sha224_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584289344,
      "name": "sha256_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void sha256_update(struct sha256_state * sctx, const u8 * data, unsigned int len)
```

```json
{
  "name": "sha256_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584699456,
      "name": "sha256_update",
      "external": true,
      "loc": "lib/crypto/sha256.c:209",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup",
        "crypto/sha256_generic.c:crypto_sha256_update",
        "lib/crypto/sha256.c:__sha256_final",
        "lib/crypto/sha256.c:__sha256_final",
        "lib/crypto/sha256.c:sha224_update",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "net/mptcp/crypto.c:mptcp_crypto_hmac_sha",
        "net/mptcp/crypto.c:mptcp_crypto_hmac_sha",
        "net/mptcp/crypto.c:mptcp_crypto_key_sha"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584699456,
      "name": "sha256_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
void sha256_update(struct sha256_state * sctx, const u8 * data, unsigned int len)
```

```json
{
  "name": "sha256_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584812352,
      "name": "sha256_update",
      "external": true,
      "loc": "lib/crypto/sha256.c:122",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup",
        "crypto/sha256_generic.c:crypto_sha256_update",
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha224_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584812352,
      "name": "sha256_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
void sha256_update(struct sha256_state * sctx, const u8 * data, unsigned int len)
```

```json
{
  "name": "sha256_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584856912,
      "name": "sha256_update",
      "external": true,
      "loc": "lib/crypto/sha256.c:122",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup",
        "crypto/sha256_generic.c:crypto_sha256_update",
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha224_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584856912,
      "name": "sha256_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
void sha256_update(struct sha256_state * sctx, const u8 * data, unsigned int len)
```

```json
{
  "name": "sha256_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585278288,
      "name": "sha256_update",
      "external": true,
      "loc": "lib/crypto/sha256.c:122",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup",
        "crypto/sha256_generic.c:crypto_sha256_update",
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha224_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585278288,
      "name": "sha256_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
void sha256_update(struct sha256_state * sctx, const u8 * data, unsigned int len)
```

```json
{
  "name": "sha256_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586129392,
      "name": "sha256_update",
      "external": true,
      "loc": "lib/crypto/sha256.c:122",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup",
        "crypto/sha256_generic.c:crypto_sha256_update",
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha224_final",
        "lib/crypto/sha256.c:sha224_final",
        "lib/crypto/sha256.c:sha224_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586129392,
      "name": "sha256_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
void sha256_update(struct sha256_state * sctx, const u8 * data, unsigned int len)
```

```json
{
  "name": "sha256_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587120096,
      "name": "sha256_update",
      "external": true,
      "loc": "lib/crypto/sha256.c:122",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup",
        "crypto/sha256_generic.c:crypto_sha256_update",
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha224_final",
        "lib/crypto/sha256.c:sha224_final",
        "lib/crypto/sha256.c:sha224_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587120096,
      "name": "sha256_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sha256_update(struct sha256_state * sctx, const u8 * data, unsigned int len)
```

```json
{
  "name": "sha256_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587383230,
      "name": "sha256_update",
      "external": true,
      "loc": "lib/crypto/sha256.c:134",
      "file": "lib/crypto/sha256.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256"
      ],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup",
        "crypto/sha256_generic.c:crypto_sha256_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587382736,
      "name": "sha256_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sha256_update(struct sha256_state * sctx, const u8 * data, unsigned int len)
```

```json
{
  "name": "sha256_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587670014,
      "name": "sha256_update",
      "external": true,
      "loc": "lib/crypto/sha256.c:134",
      "file": "lib/crypto/sha256.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256"
      ],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup",
        "crypto/sha256_generic.c:crypto_sha256_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587669520,
      "name": "sha256_update",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int sha256_update(struct sha256_state * sctx, const u8 * data, unsigned int len)
```

```json
{
  "name": "sha256_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496173800,
      "name": "sha256_update",
      "external": true,
      "loc": "lib/crypto/sha256.c:209",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup",
        "crypto/sha256_generic.c:crypto_sha256_update",
        "lib/crypto/sha256.c:__sha256_final",
        "lib/crypto/sha256.c:__sha256_final",
        "lib/crypto/sha256.c:sha224_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496173800,
      "name": "sha256_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int sha256_update(struct sha256_state * sctx, const u8 * data, unsigned int len)
```

```json
{
  "name": "sha256_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229497228,
      "name": "sha256_update",
      "external": true,
      "loc": "lib/crypto/sha256.c:209",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup",
        "crypto/sha256_generic.c:crypto_sha256_update",
        "lib/crypto/sha256.c:__sha256_final",
        "lib/crypto/sha256.c:__sha256_final",
        "lib/crypto/sha256.c:sha224_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229497228,
      "name": "sha256_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int sha256_update(struct sha256_state * sctx, const u8 * data, unsigned int len)
```

```json
{
  "name": "sha256_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290440800,
      "name": "sha256_update",
      "external": true,
      "loc": "lib/crypto/sha256.c:209",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup",
        "crypto/sha256_generic.c:crypto_sha256_update",
        "lib/crypto/sha256.c:__sha256_final",
        "lib/crypto/sha256.c:__sha256_final",
        "lib/crypto/sha256.c:sha224_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290440800,
      "name": "sha256_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int sha256_update(struct sha256_state * sctx, const u8 * data, unsigned int len)
```

```json
{
  "name": "sha256_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275230764,
      "name": "sha256_update",
      "external": true,
      "loc": "lib/crypto/sha256.c:209",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup",
        "crypto/sha256_generic.c:crypto_sha256_update",
        "lib/crypto/sha256.c:__sha256_final",
        "lib/crypto/sha256.c:__sha256_final",
        "lib/crypto/sha256.c:sha224_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275230764,
      "name": "sha256_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int sha256_update(struct sha256_state * sctx, const u8 * data, unsigned int len)
```

```json
{
  "name": "sha256_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584258080,
      "name": "sha256_update",
      "external": true,
      "loc": "lib/crypto/sha256.c:209",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup",
        "crypto/sha256_generic.c:crypto_sha256_update",
        "lib/crypto/sha256.c:__sha256_final",
        "lib/crypto/sha256.c:__sha256_final",
        "lib/crypto/sha256.c:sha224_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258080,
      "name": "sha256_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int sha256_update(struct sha256_state * sctx, const u8 * data, unsigned int len)
```

```json
{
  "name": "sha256_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584193280,
      "name": "sha256_update",
      "external": true,
      "loc": "lib/crypto/sha256.c:209",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup",
        "crypto/sha256_generic.c:crypto_sha256_update",
        "lib/crypto/sha256.c:__sha256_final",
        "lib/crypto/sha256.c:__sha256_final",
        "lib/crypto/sha256.c:sha224_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584193280,
      "name": "sha256_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int sha256_update(struct sha256_state * sctx, const u8 * data, unsigned int len)
```

```json
{
  "name": "sha256_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584241840,
      "name": "sha256_update",
      "external": true,
      "loc": "lib/crypto/sha256.c:209",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup",
        "crypto/sha256_generic.c:crypto_sha256_update",
        "lib/crypto/sha256.c:__sha256_final",
        "lib/crypto/sha256.c:__sha256_final",
        "lib/crypto/sha256.c:sha224_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584241840,
      "name": "sha256_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int sha256_update(struct sha256_state * sctx, const u8 * data, unsigned int len)
```

```json
{
  "name": "sha256_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584346672,
      "name": "sha256_update",
      "external": true,
      "loc": "lib/crypto/sha256.c:209",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup",
        "crypto/sha256_generic.c:crypto_sha256_update",
        "lib/crypto/sha256.c:__sha256_final",
        "lib/crypto/sha256.c:__sha256_final",
        "lib/crypto/sha256.c:sha224_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584346672,
      "name": "sha256_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int sha256_update(struct sha256_state * sctx, const u8 * data, unsigned int len)
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
