# Function: <code>__sha256_final</code>

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
int __sha256_final(struct sha256_state * sctx, u8 * out, int digest_words)
```

```json
{
  "name": "__sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584289632,
      "name": "__sha256_final",
      "external": false,
      "loc": "lib/crypto/sha256.c:246",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/sha256.c:sha224_final",
        "lib/crypto/sha256.c:sha256_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584289632,
      "name": "__sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void __sha256_final(struct sha256_state * sctx, u8 * out, int digest_words)
```

```json
{
  "name": "__sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584699744,
      "name": "__sha256_final",
      "external": false,
      "loc": "lib/crypto/sha256.c:244",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/sha256.c:sha224_final",
        "lib/crypto/sha256.c:sha256_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584699744,
      "name": "__sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
void __sha256_final(struct sha256_state * sctx, u8 * out, int digest_words)
```

```json
{
  "name": "__sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584813121,
      "name": "__sha256_final",
      "external": false,
      "loc": "lib/crypto/sha256.c:160",
      "file": "lib/crypto/sha256.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256"
      ],
      "caller_func": [
        "lib/crypto/sha256.c:sha224_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584812736,
      "name": "__sha256_final",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sha256_final(struct sha256_state * sctx, u8 * out, int digest_words)
```

```json
{
  "name": "__sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584857681,
      "name": "__sha256_final",
      "external": false,
      "loc": "lib/crypto/sha256.c:160",
      "file": "lib/crypto/sha256.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256"
      ],
      "caller_func": [
        "lib/crypto/sha256.c:sha224_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584857296,
      "name": "__sha256_final",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sha256_final(struct sha256_state * sctx, u8 * out, int digest_words)
```

```json
{
  "name": "__sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585279113,
      "name": "__sha256_final",
      "external": false,
      "loc": "lib/crypto/sha256.c:160",
      "file": "lib/crypto/sha256.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256"
      ],
      "caller_func": [
        "lib/crypto/sha256.c:sha224_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585278672,
      "name": "__sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586129985,
      "name": "__sha256_final",
      "external": false,
      "loc": "lib/crypto/sha256.c:160",
      "file": "lib/crypto/sha256.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha224_final"
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
  "name": "__sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587120721,
      "name": "__sha256_final",
      "external": false,
      "loc": "lib/crypto/sha256.c:160",
      "file": "lib/crypto/sha256.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha224_final"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587383235,
      "name": "__sha256_final",
      "external": false,
      "loc": "lib/crypto/sha256.c:140",
      "file": "lib/crypto/sha256.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha224_final"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587670019,
      "name": "__sha256_final",
      "external": false,
      "loc": "lib/crypto/sha256.c:140",
      "file": "lib/crypto/sha256.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha224_final"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __sha256_final(struct sha256_state * sctx, u8 * out, int digest_words)
```

```json
{
  "name": "__sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496174024,
      "name": "__sha256_final",
      "external": false,
      "loc": "lib/crypto/sha256.c:246",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/sha256.c:sha224_final",
        "lib/crypto/sha256.c:sha256_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496174024,
      "name": "__sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int __sha256_final(struct sha256_state * sctx, u8 * out, int digest_words)
```

```json
{
  "name": "__sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229497400,
      "name": "__sha256_final",
      "external": false,
      "loc": "lib/crypto/sha256.c:246",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/sha256.c:sha224_final",
        "lib/crypto/sha256.c:sha256_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229497400,
      "name": "__sha256_final",
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
int __sha256_final(struct sha256_state * sctx, u8 * out, int digest_words)
```

```json
{
  "name": "__sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290441136,
      "name": "__sha256_final",
      "external": false,
      "loc": "lib/crypto/sha256.c:246",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/sha256.c:sha224_final",
        "lib/crypto/sha256.c:sha256_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290441136,
      "name": "__sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
int __sha256_final(struct sha256_state * sctx, u8 * out, int digest_words)
```

```json
{
  "name": "__sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275230964,
      "name": "__sha256_final",
      "external": false,
      "loc": "lib/crypto/sha256.c:246",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/sha256.c:sha224_final",
        "lib/crypto/sha256.c:sha256_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275230964,
      "name": "__sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int __sha256_final(struct sha256_state * sctx, u8 * out, int digest_words)
```

```json
{
  "name": "__sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584258368,
      "name": "__sha256_final",
      "external": false,
      "loc": "lib/crypto/sha256.c:246",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/sha256.c:sha224_final",
        "lib/crypto/sha256.c:sha256_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258368,
      "name": "__sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int __sha256_final(struct sha256_state * sctx, u8 * out, int digest_words)
```

```json
{
  "name": "__sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584193568,
      "name": "__sha256_final",
      "external": false,
      "loc": "lib/crypto/sha256.c:246",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/sha256.c:sha224_final",
        "lib/crypto/sha256.c:sha256_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584193568,
      "name": "__sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int __sha256_final(struct sha256_state * sctx, u8 * out, int digest_words)
```

```json
{
  "name": "__sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584242128,
      "name": "__sha256_final",
      "external": false,
      "loc": "lib/crypto/sha256.c:246",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/sha256.c:sha224_final",
        "lib/crypto/sha256.c:sha256_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584242128,
      "name": "__sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int __sha256_final(struct sha256_state * sctx, u8 * out, int digest_words)
```

```json
{
  "name": "__sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584346960,
      "name": "__sha256_final",
      "external": false,
      "loc": "lib/crypto/sha256.c:246",
      "file": "lib/crypto/sha256.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/sha256.c:sha224_final",
        "lib/crypto/sha256.c:sha256_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584346960,
      "name": "__sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int __sha256_final(struct sha256_state * sctx, u8 * out, int digest_words)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void __sha256_final(struct sha256_state * sctx, u8 * out, int digest_words)
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
