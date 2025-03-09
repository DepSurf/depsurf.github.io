# Function: <code>crypto_sha256_final</code>

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
int crypto_sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583873136,
      "name": "crypto_sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:53",
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
      "addr": 18446744071583873136,
      "name": "crypto_sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int crypto_sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584263472,
      "name": "crypto_sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:56",
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
      "addr": 18446744071584263392,
      "name": "crypto_sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
int crypto_sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584382208,
      "name": "crypto_sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:56",
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
      "addr": 18446744071584382128,
      "name": "crypto_sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
int crypto_sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584416704,
      "name": "crypto_sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:56",
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
      "addr": 18446744071584416624,
      "name": "crypto_sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
int crypto_sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584812352,
      "name": "crypto_sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:56",
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
      "addr": 18446744071584812272,
      "name": "crypto_sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
int crypto_sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585503072,
      "name": "crypto_sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:44",
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
      "addr": 18446744071585502960,
      "name": "crypto_sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int crypto_sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586265728,
      "name": "crypto_sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:44",
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
      "addr": 18446744071586265600,
      "name": "crypto_sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int crypto_sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586506880,
      "name": "crypto_sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:44",
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
      "addr": 18446744071586506768,
      "name": "crypto_sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
int crypto_sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586776272,
      "name": "crypto_sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:44",
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
      "addr": 18446744071586776160,
      "name": "crypto_sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
int crypto_sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495691800,
      "name": "crypto_sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:53",
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
      "addr": 18446603336495691800,
      "name": "crypto_sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
int crypto_sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229041316,
      "name": "crypto_sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:53",
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
      "addr": 3229041316,
      "name": "crypto_sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int crypto_sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289836560,
      "name": "crypto_sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:53",
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
      "addr": 13835058055289836560,
      "name": "crypto_sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int crypto_sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274839436,
      "name": "crypto_sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:53",
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
      "addr": 18446743936274839436,
      "name": "crypto_sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
int crypto_sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583841872,
      "name": "crypto_sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:53",
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
      "addr": 18446744071583841872,
      "name": "crypto_sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
int crypto_sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583778928,
      "name": "crypto_sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:53",
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
      "addr": 18446744071583778928,
      "name": "crypto_sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
int crypto_sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583825632,
      "name": "crypto_sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:53",
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
      "addr": 18446744071583825632,
      "name": "crypto_sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
int crypto_sha256_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_sha256_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583926704,
      "name": "crypto_sha256_final",
      "external": false,
      "loc": "crypto/sha256_generic.c:53",
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
      "addr": 18446744071583926704,
      "name": "crypto_sha256_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
int crypto_sha256_final(struct shash_desc * desc, u8 * out)
```
</details>
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
