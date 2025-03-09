# Function: <code>skb_free_head</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586209663,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:572",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_release_data",
        "net/core/skbuff.c:pskb_expand_head"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void skb_free_head(struct sk_buff * skb)
```

```json
{
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586627840,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:573",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586627840,
      "name": "skb_free_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void skb_free_head(struct sk_buff * skb)
```

```json
{
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586812640,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:573",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586812640,
      "name": "skb_free_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void skb_free_head(struct sk_buff * skb)
```

```json
{
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586937440,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:572",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586937440,
      "name": "skb_free_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void skb_free_head(struct sk_buff * skb)
```

```json
{
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587430784,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:543",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587430784,
      "name": "skb_free_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void skb_free_head(struct sk_buff * skb)
```

```json
{
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587735136,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:543",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587735136,
      "name": "skb_free_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void skb_free_head(struct sk_buff * skb)
```

```json
{
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587869248,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:550",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587869248,
      "name": "skb_free_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void skb_free_head(struct sk_buff * skb)
```

```json
{
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588174528,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:584",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588174528,
      "name": "skb_free_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void skb_free_head(struct sk_buff * skb)
```

```json
{
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588379664,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:584",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588379664,
      "name": "skb_free_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589263026,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:583",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
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
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589262178,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:597",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
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
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589155134,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:644",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void skb_free_head(struct sk_buff * skb)
```

```json
{
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589853776,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:646",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589853776,
      "name": "skb_free_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void skb_free_head(struct sk_buff * skb)
```

```json
{
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591378704,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:646",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591378704,
      "name": "skb_free_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void skb_free_head(struct sk_buff * skb)
```

```json
{
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593139280,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:813",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593139280,
      "name": "skb_free_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void skb_free_head(struct sk_buff * skb, bool napi_safe)
```

```json
{
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593597152,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:903",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593597152,
      "name": "skb_free_head",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void skb_free_head(struct sk_buff * skb, bool napi_safe)
```

```json
{
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594382272,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:989",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594382272,
      "name": "skb_free_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
void skb_free_head(struct sk_buff * skb)
```

```json
{
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501890864,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:584",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501890864,
      "name": "skb_free_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void skb_free_head(struct sk_buff * skb)
```

```json
{
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234653068,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:584",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234653068,
      "name": "skb_free_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void skb_free_head(struct sk_buff * skb)
```

```json
{
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295300688,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:584",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295300688,
      "name": "skb_free_head",
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
void skb_free_head(struct sk_buff * skb)
```

```json
{
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278208636,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:584",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278208636,
      "name": "skb_free_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void skb_free_head(struct sk_buff * skb)
```

```json
{
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587986448,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:584",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587986448,
      "name": "skb_free_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void skb_free_head(struct sk_buff * skb)
```

```json
{
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587699552,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:584",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587699552,
      "name": "skb_free_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void skb_free_head(struct sk_buff * skb)
```

```json
{
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588318224,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:584",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588318224,
      "name": "skb_free_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void skb_free_head(struct sk_buff * skb)
```

```json
{
  "name": "skb_free_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588453568,
      "name": "skb_free_head",
      "external": false,
      "loc": "net/core/skbuff.c:584",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588453568,
      "name": "skb_free_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void skb_free_head(struct sk_buff * skb)
```
</details>
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
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void skb_free_head(struct sk_buff * skb)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void skb_free_head(struct sk_buff * skb)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool napi_safe</code>
</li>
</ul>
</details>
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
