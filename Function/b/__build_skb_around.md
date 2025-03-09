# Function: <code>__build_skb_around</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * __build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "__build_skb_around",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588174000,
      "name": "__build_skb_around",
      "external": false,
      "loc": "net/core/skbuff.c:261",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:__build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588174000,
      "name": "__build_skb_around",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
struct sk_buff * __build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "__build_skb_around",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588379136,
      "name": "__build_skb_around",
      "external": false,
      "loc": "net/core/skbuff.c:261",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:__build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588379136,
      "name": "__build_skb_around",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
struct sk_buff * __build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "__build_skb_around",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589240608,
      "name": "__build_skb_around",
      "external": false,
      "loc": "net/core/skbuff.c:262",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:__build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589240608,
      "name": "__build_skb_around",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
struct sk_buff * __build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "__build_skb_around",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589240000,
      "name": "__build_skb_around",
      "external": false,
      "loc": "net/core/skbuff.c:265",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:__build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589240000,
      "name": "__build_skb_around",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void __build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "__build_skb_around",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589133824,
      "name": "__build_skb_around",
      "external": false,
      "loc": "net/core/skbuff.c:190",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__napi_build_skb",
        "net/core/skbuff.c:__build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589133824,
      "name": "__build_skb_around",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
void __build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "__build_skb_around",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589853232,
      "name": "__build_skb_around",
      "external": false,
      "loc": "net/core/skbuff.c:192",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__napi_build_skb",
        "net/core/skbuff.c:__build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589853232,
      "name": "__build_skb_around",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
void __build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "__build_skb_around",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591378064,
      "name": "__build_skb_around",
      "external": false,
      "loc": "net/core/skbuff.c:190",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__napi_build_skb",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:__build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591378064,
      "name": "__build_skb_around",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void __build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "__build_skb_around",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__build_skb_around",
      "external": false,
      "loc": "net/core/skbuff.c:339",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__napi_build_skb",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:__build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593148512,
      "name": "__build_skb_around",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    },
    {
      "addr": 18446744071596321776,
      "name": "__build_skb_around.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void __build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "__build_skb_around",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__build_skb_around",
      "external": false,
      "loc": "net/core/skbuff.c:410",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__napi_build_skb",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:__build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593602256,
      "name": "__build_skb_around",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    },
    {
      "addr": 18446744071596851459,
      "name": "__build_skb_around.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void __build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "__build_skb_around",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__build_skb_around",
      "external": false,
      "loc": "net/core/skbuff.c:411",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__napi_build_skb",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:__build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594376848,
      "name": "__build_skb_around",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    },
    {
      "addr": 18446744071597776355,
      "name": "__build_skb_around.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct sk_buff * __build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "__build_skb_around",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501890536,
      "name": "__build_skb_around",
      "external": false,
      "loc": "net/core/skbuff.c:261",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:__build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501890536,
      "name": "__build_skb_around",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
struct sk_buff * __build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "__build_skb_around",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234652476,
      "name": "__build_skb_around",
      "external": false,
      "loc": "net/core/skbuff.c:261",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:__build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234652476,
      "name": "__build_skb_around",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
struct sk_buff * __build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "__build_skb_around",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295299904,
      "name": "__build_skb_around",
      "external": false,
      "loc": "net/core/skbuff.c:261",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:__build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295299904,
      "name": "__build_skb_around",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__build_skb_around",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278207046,
      "name": "__build_skb_around",
      "external": false,
      "loc": "net/core/skbuff.c:261",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:__build_skb"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct sk_buff * __build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "__build_skb_around",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587985920,
      "name": "__build_skb_around",
      "external": false,
      "loc": "net/core/skbuff.c:261",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:__build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587985920,
      "name": "__build_skb_around",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
struct sk_buff * __build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "__build_skb_around",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587699024,
      "name": "__build_skb_around",
      "external": false,
      "loc": "net/core/skbuff.c:261",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:__build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587699024,
      "name": "__build_skb_around",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
struct sk_buff * __build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "__build_skb_around",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588317696,
      "name": "__build_skb_around",
      "external": false,
      "loc": "net/core/skbuff.c:261",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:__build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588317696,
      "name": "__build_skb_around",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
struct sk_buff * __build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "__build_skb_around",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588453040,
      "name": "__build_skb_around",
      "external": false,
      "loc": "net/core/skbuff.c:261",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:__build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588453040,
      "name": "__build_skb_around",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct sk_buff * __build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct sk_buff *</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct sk_buff * __build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```
</details>
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
