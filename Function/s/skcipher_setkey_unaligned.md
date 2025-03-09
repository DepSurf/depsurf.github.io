# Function: <code>skcipher_setkey_unaligned</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "skcipher_setkey_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583047754,
      "name": "skcipher_setkey_unaligned",
      "external": false,
      "loc": "crypto/skcipher.c:767",
      "file": "crypto/skcipher.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "skcipher_setkey_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583213239,
      "name": "skcipher_setkey_unaligned",
      "external": false,
      "loc": "crypto/skcipher.c:773",
      "file": "crypto/skcipher.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey"
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
  "name": "skcipher_setkey_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583421440,
      "name": "skcipher_setkey_unaligned",
      "external": false,
      "loc": "crypto/skcipher.c:786",
      "file": "crypto/skcipher.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "skcipher_setkey_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583542400,
      "name": "skcipher_setkey_unaligned",
      "external": false,
      "loc": "crypto/skcipher.c:793",
      "file": "crypto/skcipher.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "skcipher_setkey_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583734800,
      "name": "skcipher_setkey_unaligned",
      "external": false,
      "loc": "crypto/skcipher.c:793",
      "file": "crypto/skcipher.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "skcipher_setkey_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583844608,
      "name": "skcipher_setkey_unaligned",
      "external": false,
      "loc": "crypto/skcipher.c:797",
      "file": "crypto/skcipher.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int skcipher_setkey_unaligned(struct crypto_skcipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "skcipher_setkey_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584229472,
      "name": "skcipher_setkey_unaligned",
      "external": false,
      "loc": "crypto/skcipher.c:578",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_setkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584229472,
      "name": "skcipher_setkey_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int skcipher_setkey_unaligned(struct crypto_skcipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "skcipher_setkey_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584347936,
      "name": "skcipher_setkey_unaligned",
      "external": false,
      "loc": "crypto/skcipher.c:578",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_setkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584347936,
      "name": "skcipher_setkey_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int skcipher_setkey_unaligned(struct crypto_skcipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "skcipher_setkey_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584382128,
      "name": "skcipher_setkey_unaligned",
      "external": false,
      "loc": "crypto/skcipher.c:573",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_setkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584382128,
      "name": "skcipher_setkey_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int skcipher_setkey_unaligned(struct crypto_skcipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "skcipher_setkey_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584777360,
      "name": "skcipher_setkey_unaligned",
      "external": false,
      "loc": "crypto/skcipher.c:573",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_setkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584777360,
      "name": "skcipher_setkey_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int skcipher_setkey_unaligned(struct crypto_skcipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "skcipher_setkey_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585462368,
      "name": "skcipher_setkey_unaligned",
      "external": false,
      "loc": "crypto/skcipher.c:573",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_setkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585462368,
      "name": "skcipher_setkey_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
int skcipher_setkey_unaligned(struct crypto_skcipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "skcipher_setkey_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586223376,
      "name": "skcipher_setkey_unaligned",
      "external": false,
      "loc": "crypto/skcipher.c:573",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_setkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586223376,
      "name": "skcipher_setkey_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
int skcipher_setkey_unaligned(struct crypto_skcipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "skcipher_setkey_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586458960,
      "name": "skcipher_setkey_unaligned",
      "external": false,
      "loc": "crypto/skcipher.c:591",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_setkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586458960,
      "name": "skcipher_setkey_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
int skcipher_setkey_unaligned(struct crypto_skcipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "skcipher_setkey_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586730016,
      "name": "skcipher_setkey_unaligned",
      "external": false,
      "loc": "crypto/skcipher.c:595",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_setkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586730016,
      "name": "skcipher_setkey_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
  "name": "skcipher_setkey_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495655984,
      "name": "skcipher_setkey_unaligned",
      "external": false,
      "loc": "crypto/skcipher.c:797",
      "file": "crypto/skcipher.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey"
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
  "name": "skcipher_setkey_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229012116,
      "name": "skcipher_setkey_unaligned",
      "external": false,
      "loc": "crypto/skcipher.c:797",
      "file": "crypto/skcipher.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "skcipher_setkey_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289794496,
      "name": "skcipher_setkey_unaligned",
      "external": false,
      "loc": "crypto/skcipher.c:797",
      "file": "crypto/skcipher.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey"
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
  "name": "skcipher_setkey_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274808312,
      "name": "skcipher_setkey_unaligned",
      "external": false,
      "loc": "crypto/skcipher.c:797",
      "file": "crypto/skcipher.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "skcipher_setkey_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583813344,
      "name": "skcipher_setkey_unaligned",
      "external": false,
      "loc": "crypto/skcipher.c:797",
      "file": "crypto/skcipher.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey"
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
  "name": "skcipher_setkey_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583750400,
      "name": "skcipher_setkey_unaligned",
      "external": false,
      "loc": "crypto/skcipher.c:797",
      "file": "crypto/skcipher.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey"
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
  "name": "skcipher_setkey_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583797104,
      "name": "skcipher_setkey_unaligned",
      "external": false,
      "loc": "crypto/skcipher.c:797",
      "file": "crypto/skcipher.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey"
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
  "name": "skcipher_setkey_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583898160,
      "name": "skcipher_setkey_unaligned",
      "external": false,
      "loc": "crypto/skcipher.c:797",
      "file": "crypto/skcipher.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int skcipher_setkey_unaligned(struct crypto_skcipher * tfm, const u8 * key, unsigned int keylen)
```
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
