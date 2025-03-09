# Function: <code>sha256_final</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582677500,
      "name": "sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:234",
      "file": "crypto/sha256_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582678448,
      "name": "sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582928912,
      "name": "sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:250",
      "file": "crypto/sha256_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582928912,
      "name": "sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583031344,
      "name": "sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:250",
      "file": "crypto/sha256_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583031344,
      "name": "sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583085344,
      "name": "sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:250",
      "file": "crypto/sha256_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583085344,
      "name": "sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583251776,
      "name": "sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:250",
      "file": "crypto/sha256_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583251776,
      "name": "sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583459504,
      "name": "sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:250",
      "file": "crypto/sha256_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583459504,
      "name": "sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
int sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583581472,
      "name": "sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:250",
      "file": "crypto/sha256_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583581472,
      "name": "sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
int sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583770448,
      "name": "sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:245",
      "file": "crypto/sha256_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583770448,
      "name": "sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
int sha256_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584289856,
      "name": "sha256_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:275",
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
      "addr": 18446744071584289856,
      "name": "sha256_final",
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
void sha256_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584699952,
      "name": "sha256_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:271",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "net/mptcp/crypto.c:mptcp_crypto_hmac_sha",
        "net/mptcp/crypto.c:mptcp_crypto_hmac_sha",
        "net/mptcp/crypto.c:mptcp_crypto_key_sha"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584699952,
      "name": "sha256_final",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sha256_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584813121,
      "name": "sha256_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:187",
      "file": "lib/crypto/sha256.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256"
      ],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584812944,
      "name": "sha256_final",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sha256_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584857681,
      "name": "sha256_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:187",
      "file": "lib/crypto/sha256.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256"
      ],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584857504,
      "name": "sha256_final",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sha256_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585279113,
      "name": "sha256_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:187",
      "file": "lib/crypto/sha256.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256"
      ],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585278928,
      "name": "sha256_final",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sha256_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586129985,
      "name": "sha256_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:187",
      "file": "lib/crypto/sha256.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256"
      ],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586130448,
      "name": "sha256_final",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sha256_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587120721,
      "name": "sha256_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:187",
      "file": "lib/crypto/sha256.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256"
      ],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587121216,
      "name": "sha256_final",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sha256_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587383235,
      "name": "sha256_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:146",
      "file": "lib/crypto/sha256.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256"
      ],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587383376,
      "name": "sha256_final",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sha256_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587670019,
      "name": "sha256_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:146",
      "file": "lib/crypto/sha256.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256"
      ],
      "caller_func": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587670160,
      "name": "sha256_final",
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
int sha256_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496174312,
      "name": "sha256_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:275",
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
      "addr": 18446603336496174312,
      "name": "sha256_final",
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
int sha256_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229497644,
      "name": "sha256_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:275",
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
      "addr": 3229497644,
      "name": "sha256_final",
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
int sha256_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290441456,
      "name": "sha256_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:275",
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
      "addr": 13835058055290441456,
      "name": "sha256_final",
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
int sha256_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275231252,
      "name": "sha256_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:275",
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
      "addr": 18446743936275231252,
      "name": "sha256_final",
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
int sha256_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584258592,
      "name": "sha256_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:275",
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
      "addr": 18446744071584258592,
      "name": "sha256_final",
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
int sha256_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584193792,
      "name": "sha256_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:275",
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
      "addr": 18446744071584193792,
      "name": "sha256_final",
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
int sha256_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584242352,
      "name": "sha256_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:275",
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
      "addr": 18446744071584242352,
      "name": "sha256_final",
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
int sha256_final(struct sha256_state * sctx, u8 * out)
```

```json
{
  "name": "sha256_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584347184,
      "name": "sha256_final",
      "external": true,
      "loc": "lib/crypto/sha256.c:275",
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
      "addr": 18446744071584347184,
      "name": "sha256_final",
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sha256_state * sctx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct shash_desc * desc</code>
</li>
</ul>
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
