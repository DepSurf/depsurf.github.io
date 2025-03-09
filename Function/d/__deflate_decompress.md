# Function: <code>__deflate_decompress</code>

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
int __deflate_decompress(const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen, void * ctx)
```

```json
{
  "name": "__deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583493808,
      "name": "__deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:224",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/deflate.c:deflate_sdecompress",
        "crypto/deflate.c:deflate_decompress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583493808,
      "name": "__deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
int __deflate_decompress(const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen, void * ctx)
```

```json
{
  "name": "__deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583615072,
      "name": "__deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:224",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/deflate.c:deflate_sdecompress",
        "crypto/deflate.c:deflate_decompress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583615072,
      "name": "__deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
int __deflate_decompress(const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen, void * ctx)
```

```json
{
  "name": "__deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583801168,
      "name": "__deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:220",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/deflate.c:deflate_sdecompress",
        "crypto/deflate.c:deflate_decompress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583801168,
      "name": "__deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
int __deflate_decompress(const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen, void * ctx)
```

```json
{
  "name": "__deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583903008,
      "name": "__deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:220",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/deflate.c:deflate_sdecompress",
        "crypto/deflate.c:deflate_decompress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583903008,
      "name": "__deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584292396,
      "name": "__deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:220",
      "file": "crypto/deflate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/deflate.c:deflate_sdecompress",
        "crypto/deflate.c:deflate_decompress"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584411004,
      "name": "__deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:220",
      "file": "crypto/deflate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/deflate.c:deflate_sdecompress",
        "crypto/deflate.c:deflate_decompress"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584445932,
      "name": "__deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:220",
      "file": "crypto/deflate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/deflate.c:deflate_sdecompress",
        "crypto/deflate.c:deflate_decompress"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584843932,
      "name": "__deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:220",
      "file": "crypto/deflate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/deflate.c:deflate_sdecompress",
        "crypto/deflate.c:deflate_decompress"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585537164,
      "name": "__deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:220",
      "file": "crypto/deflate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/deflate.c:deflate_sdecompress",
        "crypto/deflate.c:deflate_decompress"
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
  "name": "__deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586298732,
      "name": "__deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:220",
      "file": "crypto/deflate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/deflate.c:deflate_sdecompress",
        "crypto/deflate.c:deflate_decompress"
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
  "name": "__deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586542332,
      "name": "__deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:220",
      "file": "crypto/deflate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/deflate.c:deflate_sdecompress",
        "crypto/deflate.c:deflate_decompress"
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
  "name": "__deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586812268,
      "name": "__deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:203",
      "file": "crypto/deflate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/deflate.c:deflate_sdecompress",
        "crypto/deflate.c:deflate_decompress"
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
int __deflate_decompress(const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen, void * ctx)
```

```json
{
  "name": "__deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495723016,
      "name": "__deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:220",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/deflate.c:deflate_sdecompress",
        "crypto/deflate.c:deflate_decompress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495723016,
      "name": "__deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int __deflate_decompress(const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen, void * ctx)
```

```json
{
  "name": "__deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229077540,
      "name": "__deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:220",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/deflate.c:deflate_sdecompress",
        "crypto/deflate.c:deflate_decompress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229077540,
      "name": "__deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int __deflate_decompress(const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen, void * ctx)
```

```json
{
  "name": "__deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289876736,
      "name": "__deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:220",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/deflate.c:deflate_sdecompress",
        "crypto/deflate.c:deflate_decompress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289876736,
      "name": "__deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int __deflate_decompress(const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen, void * ctx)
```

```json
{
  "name": "__deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274874860,
      "name": "__deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:220",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/deflate.c:deflate_sdecompress",
        "crypto/deflate.c:deflate_decompress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274874860,
      "name": "__deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
int __deflate_decompress(const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen, void * ctx)
```

```json
{
  "name": "__deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583871744,
      "name": "__deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:220",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/deflate.c:deflate_sdecompress",
        "crypto/deflate.c:deflate_decompress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583871744,
      "name": "__deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
int __deflate_decompress(const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen, void * ctx)
```

```json
{
  "name": "__deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583808800,
      "name": "__deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:220",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/deflate.c:deflate_sdecompress",
        "crypto/deflate.c:deflate_decompress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583808800,
      "name": "__deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
int __deflate_decompress(const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen, void * ctx)
```

```json
{
  "name": "__deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583855504,
      "name": "__deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:220",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/deflate.c:deflate_sdecompress",
        "crypto/deflate.c:deflate_decompress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583855504,
      "name": "__deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
int __deflate_decompress(const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen, void * ctx)
```

```json
{
  "name": "__deflate_decompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583956576,
      "name": "__deflate_decompress",
      "external": false,
      "loc": "crypto/deflate.c:220",
      "file": "crypto/deflate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/deflate.c:deflate_sdecompress",
        "crypto/deflate.c:deflate_decompress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583956576,
      "name": "__deflate_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
int __deflate_decompress(const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen, void * ctx)
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int __deflate_decompress(const u8 * src, unsigned int slen, u8 * dst, unsigned int * dlen, void * ctx)
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
