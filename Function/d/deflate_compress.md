# Function: <code>deflate_compress</code>

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
int deflate_compress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_compress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583494608,
      "name": "deflate_compress",
      "external": false,
      "loc": "crypto/deflate.c:209",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583494608,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int deflate_compress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_compress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583615872,
      "name": "deflate_compress",
      "external": false,
      "loc": "crypto/deflate.c:209",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583615872,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int deflate_compress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_compress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583801968,
      "name": "deflate_compress",
      "external": false,
      "loc": "crypto/deflate.c:205",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583801968,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int deflate_compress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_compress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583903808,
      "name": "deflate_compress",
      "external": false,
      "loc": "crypto/deflate.c:205",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583903808,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int deflate_compress(const char * src, size_t slen, char * * dst, size_t * dlen)
```

```json
{
  "name": "deflate_compress",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584074640,
      "name": "deflate_compress",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:1102",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    },
    {
      "addr": 18446744071584292576,
      "name": "deflate_compress",
      "external": false,
      "loc": "crypto/deflate.c:205",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584074640,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
    },
    {
      "addr": 18446744071584292576,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int deflate_compress(const char * src, size_t slen, char * * dst, size_t * dlen)
```

```json
{
  "name": "deflate_compress",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584194016,
      "name": "deflate_compress",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:1102",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    },
    {
      "addr": 18446744071584411184,
      "name": "deflate_compress",
      "external": false,
      "loc": "crypto/deflate.c:205",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584194016,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
    },
    {
      "addr": 18446744071584411184,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
int deflate_compress(const char * src, size_t slen, char * * dst, size_t * dlen)
```

```json
{
  "name": "deflate_compress",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584220912,
      "name": "deflate_compress",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:1102",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    },
    {
      "addr": 18446744071584446112,
      "name": "deflate_compress",
      "external": false,
      "loc": "crypto/deflate.c:205",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584220912,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
    },
    {
      "addr": 18446744071584446112,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
int deflate_compress(const char * src, size_t slen, char * * dst, size_t * dlen)
```

```json
{
  "name": "deflate_compress",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584606352,
      "name": "deflate_compress",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:1102",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    },
    {
      "addr": 18446744071584844112,
      "name": "deflate_compress",
      "external": false,
      "loc": "crypto/deflate.c:205",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584606352,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
    },
    {
      "addr": 18446744071584844112,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int deflate_compress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_compress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585537376,
      "name": "deflate_compress",
      "external": false,
      "loc": "crypto/deflate.c:205",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585537376,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int deflate_compress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_compress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586298960,
      "name": "deflate_compress",
      "external": false,
      "loc": "crypto/deflate.c:205",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586298960,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int deflate_compress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_compress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586542560,
      "name": "deflate_compress",
      "external": false,
      "loc": "crypto/deflate.c:205",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586542560,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int deflate_compress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_compress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586813056,
      "name": "deflate_compress",
      "external": false,
      "loc": "crypto/deflate.c:188",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586813056,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int deflate_compress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_compress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495723992,
      "name": "deflate_compress",
      "external": false,
      "loc": "crypto/deflate.c:205",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495723992,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
int deflate_compress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_compress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229078372,
      "name": "deflate_compress",
      "external": false,
      "loc": "crypto/deflate.c:205",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229078372,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int deflate_compress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_compress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289877952,
      "name": "deflate_compress",
      "external": false,
      "loc": "crypto/deflate.c:205",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289877952,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
int deflate_compress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_compress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274875690,
      "name": "deflate_compress",
      "external": false,
      "loc": "crypto/deflate.c:205",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274875690,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int deflate_compress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_compress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583872544,
      "name": "deflate_compress",
      "external": false,
      "loc": "crypto/deflate.c:205",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583872544,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int deflate_compress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_compress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583809600,
      "name": "deflate_compress",
      "external": false,
      "loc": "crypto/deflate.c:205",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583809600,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int deflate_compress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_compress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583856304,
      "name": "deflate_compress",
      "external": false,
      "loc": "crypto/deflate.c:205",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583856304,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int deflate_compress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
```

```json
{
  "name": "deflate_compress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583957376,
      "name": "deflate_compress",
      "external": false,
      "loc": "crypto/deflate.c:205",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583957376,
      "name": "deflate_compress",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int deflate_compress(struct crypto_tfm * tfm, const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen)
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
<code>const u8 * src</code> ➡️ <code>const char * src</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int slen</code> ➡️ <code>size_t slen</code>
</li>
<li>
<b>Param type changed. </b>
<code>u8 * dst</code> ➡️ <code>char * * dst</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int * dlen</code> ➡️ <code>size_t * dlen</code>
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
<code>const char * src</code> ➡️ <code>const u8 * src</code>
</li>
<li>
<b>Param type changed. </b>
<code>size_t slen</code> ➡️ <code>unsigned int slen</code>
</li>
<li>
<b>Param type changed. </b>
<code>char * * dst</code> ➡️ <code>u8 * dst</code>
</li>
<li>
<b>Param type changed. </b>
<code>size_t * dlen</code> ➡️ <code>unsigned int * dlen</code>
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
