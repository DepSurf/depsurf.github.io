# Function: <code>__ppp_channel_push</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ppp_channel_push",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585684734,
      "name": "__ppp_channel_push",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1882",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __ppp_channel_push(struct channel * pch)
```

```json
{
  "name": "__ppp_channel_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585771712,
      "name": "__ppp_channel_push",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1896",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585771712,
      "name": "__ppp_channel_push",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __ppp_channel_push(struct channel * pch)
```

```json
{
  "name": "__ppp_channel_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586207904,
      "name": "__ppp_channel_push",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1923",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586207904,
      "name": "__ppp_channel_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __ppp_channel_push(struct channel * pch)
```

```json
{
  "name": "__ppp_channel_push",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586467136,
      "name": "__ppp_channel_push",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1906",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586467136,
      "name": "__ppp_channel_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __ppp_channel_push(struct channel * pch)
```

```json
{
  "name": "__ppp_channel_push",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586614832,
      "name": "__ppp_channel_push",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1906",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586614832,
      "name": "__ppp_channel_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __ppp_channel_push(struct channel * pch)
```

```json
{
  "name": "__ppp_channel_push",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586867472,
      "name": "__ppp_channel_push",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1902",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586867472,
      "name": "__ppp_channel_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __ppp_channel_push(struct channel * pch)
```

```json
{
  "name": "__ppp_channel_push",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587013488,
      "name": "__ppp_channel_push",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1902",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587013488,
      "name": "__ppp_channel_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void __ppp_channel_push(struct channel * pch)
```

```json
{
  "name": "__ppp_channel_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587845056,
      "name": "__ppp_channel_push",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1990",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587845056,
      "name": "__ppp_channel_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void __ppp_channel_push(struct channel * pch)
```

```json
{
  "name": "__ppp_channel_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587904240,
      "name": "__ppp_channel_push",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:2100",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587904240,
      "name": "__ppp_channel_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void __ppp_channel_push(struct channel * pch)
```

```json
{
  "name": "__ppp_channel_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587780608,
      "name": "__ppp_channel_push",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:2133",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587780608,
      "name": "__ppp_channel_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void __ppp_channel_push(struct channel * pch)
```

```json
{
  "name": "__ppp_channel_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588376976,
      "name": "__ppp_channel_push",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:2138",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588376976,
      "name": "__ppp_channel_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void __ppp_channel_push(struct channel * pch)
```

```json
{
  "name": "__ppp_channel_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589770592,
      "name": "__ppp_channel_push",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:2139",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589770592,
      "name": "__ppp_channel_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
void __ppp_channel_push(struct channel * pch)
```

```json
{
  "name": "__ppp_channel_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591420944,
      "name": "__ppp_channel_push",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:2141",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591420944,
      "name": "__ppp_channel_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
void __ppp_channel_push(struct channel * pch)
```

```json
{
  "name": "__ppp_channel_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591836240,
      "name": "__ppp_channel_push",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:2141",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591836240,
      "name": "__ppp_channel_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
void __ppp_channel_push(struct channel * pch)
```

```json
{
  "name": "__ppp_channel_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592584304,
      "name": "__ppp_channel_push",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:2141",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592584304,
      "name": "__ppp_channel_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void __ppp_channel_push(struct channel * pch)
```

```json
{
  "name": "__ppp_channel_push",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500125368,
      "name": "__ppp_channel_push",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1902",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500125368,
      "name": "__ppp_channel_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void __ppp_channel_push(struct channel * pch)
```

```json
{
  "name": "__ppp_channel_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232624876,
      "name": "__ppp_channel_push",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1902",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232624876,
      "name": "__ppp_channel_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
void __ppp_channel_push(struct channel * pch)
```

```json
{
  "name": "__ppp_channel_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293347920,
      "name": "__ppp_channel_push",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1902",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293347920,
      "name": "__ppp_channel_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void __ppp_channel_push(struct channel * pch)
```

```json
{
  "name": "__ppp_channel_push",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277080548,
      "name": "__ppp_channel_push",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1902",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277080548,
      "name": "__ppp_channel_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __ppp_channel_push(struct channel * pch)
```

```json
{
  "name": "__ppp_channel_push",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586770512,
      "name": "__ppp_channel_push",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1902",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586770512,
      "name": "__ppp_channel_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void __ppp_channel_push(struct channel * pch)
```

```json
{
  "name": "__ppp_channel_push",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586675744,
      "name": "__ppp_channel_push",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1902",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586675744,
      "name": "__ppp_channel_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void __ppp_channel_push(struct channel * pch)
```

```json
{
  "name": "__ppp_channel_push",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586968048,
      "name": "__ppp_channel_push",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1902",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586968048,
      "name": "__ppp_channel_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void __ppp_channel_push(struct channel * pch)
```

```json
{
  "name": "__ppp_channel_push",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587075200,
      "name": "__ppp_channel_push",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1902",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587075200,
      "name": "__ppp_channel_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void __ppp_channel_push(struct channel * pch)
```
</details>
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
