# Function: <code>__crypto_xor</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __crypto_xor(u8 * dst, const u8 * src, unsigned int len)
```

```json
{
  "name": "__crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583030336,
      "name": "__crypto_xor",
      "external": true,
      "loc": "crypto/algapi.c:978",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583030336,
      "name": "__crypto_xor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void __crypto_xor(u8 * dst, const u8 * src1, const u8 * src2, unsigned int len)
```

```json
{
  "name": "__crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583195616,
      "name": "__crypto_xor",
      "external": true,
      "loc": "crypto/algapi.c:992",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583195616,
      "name": "__crypto_xor",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __crypto_xor(u8 * dst, const u8 * src1, const u8 * src2, unsigned int len)
```

```json
{
  "name": "__crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583404512,
      "name": "__crypto_xor",
      "external": true,
      "loc": "crypto/algapi.c:989",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583404512,
      "name": "__crypto_xor",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __crypto_xor(u8 * dst, const u8 * src1, const u8 * src2, unsigned int len)
```

```json
{
  "name": "__crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583524448,
      "name": "__crypto_xor",
      "external": true,
      "loc": "crypto/algapi.c:998",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583524448,
      "name": "__crypto_xor",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __crypto_xor(u8 * dst, const u8 * src1, const u8 * src2, unsigned int len)
```

```json
{
  "name": "__crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583712048,
      "name": "__crypto_xor",
      "external": true,
      "loc": "crypto/algapi.c:967",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583712048,
      "name": "__crypto_xor",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __crypto_xor(u8 * dst, const u8 * src1, const u8 * src2, unsigned int len)
```

```json
{
  "name": "__crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583821664,
      "name": "__crypto_xor",
      "external": true,
      "loc": "crypto/algapi.c:977",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583821664,
      "name": "__crypto_xor",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __crypto_xor(u8 * dst, const u8 * src1, const u8 * src2, unsigned int len)
```

```json
{
  "name": "__crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584216800,
      "name": "__crypto_xor",
      "external": true,
      "loc": "crypto/algapi.c:975",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584216800,
      "name": "__crypto_xor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void __crypto_xor(u8 * dst, const u8 * src1, const u8 * src2, unsigned int len)
```

```json
{
  "name": "__crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584335168,
      "name": "__crypto_xor",
      "external": true,
      "loc": "crypto/algapi.c:994",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_segment",
        "crypto/cbc.c:crypto_cbc_encrypt",
        "crypto/cbc.c:crypto_cbc_encrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584335168,
      "name": "__crypto_xor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void __crypto_xor(u8 * dst, const u8 * src1, const u8 * src2, unsigned int len)
```

```json
{
  "name": "__crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584369696,
      "name": "__crypto_xor",
      "external": true,
      "loc": "crypto/algapi.c:994",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_encrypt",
        "crypto/cbc.c:crypto_cbc_encrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584369696,
      "name": "__crypto_xor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void __crypto_xor(u8 * dst, const u8 * src1, const u8 * src2, unsigned int len)
```

```json
{
  "name": "__crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584764800,
      "name": "__crypto_xor",
      "external": true,
      "loc": "crypto/algapi.c:976",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_encrypt",
        "crypto/cbc.c:crypto_cbc_encrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584764800,
      "name": "__crypto_xor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void __crypto_xor(u8 * dst, const u8 * src1, const u8 * src2, unsigned int len)
```

```json
{
  "name": "__crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585448032,
      "name": "__crypto_xor",
      "external": true,
      "loc": "crypto/algapi.c:1000",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_encrypt",
        "crypto/cbc.c:crypto_cbc_encrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585448032,
      "name": "__crypto_xor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void __crypto_xor(u8 * dst, const u8 * src1, const u8 * src2, unsigned int len)
```

```json
{
  "name": "__crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587101200,
      "name": "__crypto_xor",
      "external": true,
      "loc": "lib/crypto/utils.c:17",
      "file": "lib/crypto/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_segment",
        "crypto/cbc.c:crypto_cbc_encrypt_inplace",
        "crypto/cbc.c:crypto_cbc_encrypt_segment",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587101200,
      "name": "__crypto_xor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void __crypto_xor(u8 * dst, const u8 * src1, const u8 * src2, unsigned int len)
```

```json
{
  "name": "__crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587361168,
      "name": "__crypto_xor",
      "external": true,
      "loc": "lib/crypto/utils.c:17",
      "file": "lib/crypto/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_segment",
        "crypto/cbc.c:crypto_cbc_encrypt_inplace",
        "crypto/cbc.c:crypto_cbc_encrypt_segment",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587361168,
      "name": "__crypto_xor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void __crypto_xor(u8 * dst, const u8 * src1, const u8 * src2, unsigned int len)
```

```json
{
  "name": "__crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587647760,
      "name": "__crypto_xor",
      "external": true,
      "loc": "lib/crypto/utils.c:17",
      "file": "lib/crypto/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_segment",
        "crypto/cbc.c:crypto_cbc_encrypt_inplace",
        "crypto/cbc.c:crypto_cbc_encrypt_segment",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587647760,
      "name": "__crypto_xor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void __crypto_xor(u8 * dst, const u8 * src1, const u8 * src2, unsigned int len)
```

```json
{
  "name": "__crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495628872,
      "name": "__crypto_xor",
      "external": true,
      "loc": "crypto/algapi.c:977",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495628872,
      "name": "__crypto_xor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void __crypto_xor(u8 * dst, const u8 * src1, const u8 * src2, unsigned int len)
```

```json
{
  "name": "__crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228987036,
      "name": "__crypto_xor",
      "external": true,
      "loc": "crypto/algapi.c:977",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_encrypt",
        "crypto/cbc.c:crypto_cbc_encrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228987036,
      "name": "__crypto_xor",
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
void __crypto_xor(u8 * dst, const u8 * src1, const u8 * src2, unsigned int len)
```

```json
{
  "name": "__crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289754320,
      "name": "__crypto_xor",
      "external": true,
      "loc": "crypto/algapi.c:977",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289754320,
      "name": "__crypto_xor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void __crypto_xor(u8 * dst, const u8 * src1, const u8 * src2, unsigned int len)
```

```json
{
  "name": "__crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274786672,
      "name": "__crypto_xor",
      "external": true,
      "loc": "crypto/algapi.c:977",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash",
        "crypto/ghash-generic.c:ghash_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274786672,
      "name": "__crypto_xor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
void __crypto_xor(u8 * dst, const u8 * src1, const u8 * src2, unsigned int len)
```

```json
{
  "name": "__crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583790400,
      "name": "__crypto_xor",
      "external": true,
      "loc": "crypto/algapi.c:977",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583790400,
      "name": "__crypto_xor",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void __crypto_xor(u8 * dst, const u8 * src1, const u8 * src2, unsigned int len)
```

```json
{
  "name": "__crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583727456,
      "name": "__crypto_xor",
      "external": true,
      "loc": "crypto/algapi.c:977",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583727456,
      "name": "__crypto_xor",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void __crypto_xor(u8 * dst, const u8 * src1, const u8 * src2, unsigned int len)
```

```json
{
  "name": "__crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583774160,
      "name": "__crypto_xor",
      "external": true,
      "loc": "crypto/algapi.c:977",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583774160,
      "name": "__crypto_xor",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void __crypto_xor(u8 * dst, const u8 * src1, const u8 * src2, unsigned int len)
```

```json
{
  "name": "__crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583875152,
      "name": "__crypto_xor",
      "external": true,
      "loc": "crypto/algapi.c:977",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583875152,
      "name": "__crypto_xor",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void __crypto_xor(u8 * dst, const u8 * src, unsigned int len)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const u8 * src1</code>
</li>
<li>
<b>Param added. </b>
<code>const u8 * src2</code>
</li>
<li>
<b>Param removed. </b>
<code>const u8 * src</code>
</li>
<li>
<b>Param reordered. </b>
<code>dst, src, len</code> ➡️ <code>dst, src1, src2, len</code>
</li>
</ul>
</details>
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
