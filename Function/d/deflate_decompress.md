# Function: <code>deflate_decompress</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int deflate_decompress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583494080,
      "name": "deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:265",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583494080,
      "name": "deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int deflate_decompress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583615344,
      "name": "deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:265",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583615344,
      "name": "deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int deflate_decompress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583801440,
      "name": "deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:261",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583801440,
      "name": "deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int deflate_decompress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583903280,
      "name": "deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:261",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583903280,
      "name": "deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
int deflate_decompress(char * src, size_t slen, char * dst, size_t dlen)
```

```json
{
  "name": "deflate_decompress",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584003600,
      "name": "deflate_decompress",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1296",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:rawdata_open"
      ]
    },
    {
      "addr": 18446744071584293568,
      "name": "deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:261",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584003600,
      "name": "deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 18446744071584293568,
      "name": "deflate_decompress",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
int deflate_decompress(char * src, size_t slen, char * dst, size_t dlen)
```

```json
{
  "name": "deflate_decompress",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584123376,
      "name": "deflate_decompress",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1296",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:rawdata_open"
      ]
    },
    {
      "addr": 18446744071584412176,
      "name": "deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:261",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123376,
      "name": "deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 18446744071584412176,
      "name": "deflate_decompress",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int deflate_decompress(char * src, size_t slen, char * dst, size_t dlen)
```

```json
{
  "name": "deflate_decompress",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584166104,
      "name": "deflate_decompress",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1296",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:rawdata_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584447104,
      "name": "deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:261",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584447104,
      "name": "deflate_decompress",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int deflate_decompress(char * src, size_t slen, char * dst, size_t dlen)
```

```json
{
  "name": "deflate_decompress",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584550104,
      "name": "deflate_decompress",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1296",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:rawdata_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584845104,
      "name": "deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:261",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584845104,
      "name": "deflate_decompress",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int deflate_decompress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585538224,
      "name": "deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:261",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585538224,
      "name": "deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int deflate_decompress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586299936,
      "name": "deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:261",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586299936,
      "name": "deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int deflate_decompress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586543536,
      "name": "deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:261",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586543536,
      "name": "deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int deflate_decompress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586813616,
      "name": "deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:244",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586813616,
      "name": "deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int deflate_decompress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495723360,
      "name": "deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:261",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495723360,
      "name": "deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
int deflate_decompress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229077852,
      "name": "deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:261",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229077852,
      "name": "deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int deflate_decompress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289877120,
      "name": "deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:261",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289877120,
      "name": "deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int deflate_decompress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274875106,
      "name": "deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:261",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274875106,
      "name": "deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int deflate_decompress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583872016,
      "name": "deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:261",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583872016,
      "name": "deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int deflate_decompress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583809072,
      "name": "deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:261",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583809072,
      "name": "deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int deflate_decompress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583855776,
      "name": "deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:261",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583855776,
      "name": "deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int deflate_decompress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583956848,
      "name": "deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:261",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583956848,
      "name": "deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int deflate_decompress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct crypto_tfm * tfm</code>
</li>
<li>
<b>Param reordered. </b>
<code>tfm, src, slen, dst, dlen</code> ➡️ <code>src, slen, dst, dlen</code>
</li>
<li>
<b>Param type changed. </b>
<code>const u8 * src</code> ➡️ <code>char * src</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int slen</code> ➡️ <code>size_t slen</code>
</li>
<li>
<b>Param type changed. </b>
<code>u8 * dst</code> ➡️ <code>char * dst</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int * dlen</code> ➡️ <code>size_t dlen</code>
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
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct crypto_tfm * tfm</code>
</li>
<li>
<b>Param reordered. </b>
<code>src, slen, dst, dlen</code> ➡️ <code>tfm, src, slen, dst, dlen</code>
</li>
<li>
<b>Param type changed. </b>
<code>char * src</code> ➡️ <code>const u8 * src</code>
</li>
<li>
<b>Param type changed. </b>
<code>size_t slen</code> ➡️ <code>unsigned int slen</code>
</li>
<li>
<b>Param type changed. </b>
<code>char * dst</code> ➡️ <code>u8 * dst</code>
</li>
<li>
<b>Param type changed. </b>
<code>size_t dlen</code> ➡️ <code>unsigned int * dlen</code>
</li>
</ul>
</details>
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
