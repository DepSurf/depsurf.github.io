# Function: <code>mm_account_pinned_pages</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mm_account_pinned_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587444643,
      "name": "mm_account_pinned_pages",
      "external": false,
      "loc": "net/core/skbuff.c:893",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_zerocopy_realloc",
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_realloc",
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587434832,
      "name": "mm_account_pinned_pages.part.52",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mm_account_pinned_pages(struct mmpin * mmp, size_t size)
```

```json
{
  "name": "mm_account_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587739088,
      "name": "mm_account_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:895",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_realloc",
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587739088,
      "name": "mm_account_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int mm_account_pinned_pages(struct mmpin * mmp, size_t size)
```

```json
{
  "name": "mm_account_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587873808,
      "name": "mm_account_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:897",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_realloc",
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587873808,
      "name": "mm_account_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int mm_account_pinned_pages(struct mmpin * mmp, size_t size)
```

```json
{
  "name": "mm_account_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588179088,
      "name": "mm_account_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1055",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_realloc",
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588179088,
      "name": "mm_account_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int mm_account_pinned_pages(struct mmpin * mmp, size_t size)
```

```json
{
  "name": "mm_account_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588384880,
      "name": "mm_account_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1055",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_realloc",
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588384880,
      "name": "mm_account_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mm_account_pinned_pages(struct mmpin * mmp, size_t size)
```

```json
{
  "name": "mm_account_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589257049,
      "name": "mm_account_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1054",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_zerocopy_realloc",
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_realloc",
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589252336,
      "name": "mm_account_pinned_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071589252544,
      "name": "mm_account_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mm_account_pinned_pages(struct mmpin * mmp, size_t size)
```

```json
{
  "name": "mm_account_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589256185,
      "name": "mm_account_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1065",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_zerocopy_realloc",
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_realloc",
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589251504,
      "name": "mm_account_pinned_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071589251712,
      "name": "mm_account_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mm_account_pinned_pages(struct mmpin * mmp, size_t size)
```

```json
{
  "name": "mm_account_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589157593,
      "name": "mm_account_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1108",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:msg_zerocopy_realloc",
        "net/core/skbuff.c:msg_zerocopy_alloc"
      ],
      "caller_func": [
        "net/core/skbuff.c:msg_zerocopy_realloc",
        "net/core/skbuff.c:msg_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589146256,
      "name": "mm_account_pinned_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071589146464,
      "name": "mm_account_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mm_account_pinned_pages(struct mmpin * mmp, size_t size)
```

```json
{
  "name": "mm_account_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589877513,
      "name": "mm_account_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1129",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:msg_zerocopy_realloc",
        "net/core/skbuff.c:msg_zerocopy_alloc"
      ],
      "caller_func": [
        "net/core/skbuff.c:msg_zerocopy_realloc",
        "net/core/skbuff.c:msg_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589866352,
      "name": "mm_account_pinned_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071589866560,
      "name": "mm_account_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int mm_account_pinned_pages(struct mmpin * mmp, size_t size)
```

```json
{
  "name": "mm_account_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591393392,
      "name": "mm_account_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1131",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:msg_zerocopy_realloc",
        "net/core/skbuff.c:msg_zerocopy_realloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591393392,
      "name": "mm_account_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
int mm_account_pinned_pages(struct mmpin * mmp, size_t size)
```

```json
{
  "name": "mm_account_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593158112,
      "name": "mm_account_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1312",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:msg_zerocopy_realloc",
        "net/core/skbuff.c:msg_zerocopy_realloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593158112,
      "name": "mm_account_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int mm_account_pinned_pages(struct mmpin * mmp, size_t size)
```

```json
{
  "name": "mm_account_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593613024,
      "name": "mm_account_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1452",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:msg_zerocopy_realloc",
        "net/core/skbuff.c:msg_zerocopy_realloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593613024,
      "name": "mm_account_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int mm_account_pinned_pages(struct mmpin * mmp, size_t size)
```

```json
{
  "name": "mm_account_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594388096,
      "name": "mm_account_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1540",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:msg_zerocopy_realloc",
        "net/core/skbuff.c:msg_zerocopy_realloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594388096,
      "name": "mm_account_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int mm_account_pinned_pages(struct mmpin * mmp, size_t size)
```

```json
{
  "name": "mm_account_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501898448,
      "name": "mm_account_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1055",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_realloc",
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501898448,
      "name": "mm_account_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int mm_account_pinned_pages(struct mmpin * mmp, size_t size)
```

```json
{
  "name": "mm_account_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234658412,
      "name": "mm_account_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1055",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_realloc",
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234658412,
      "name": "mm_account_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int mm_account_pinned_pages(struct mmpin * mmp, size_t size)
```

```json
{
  "name": "mm_account_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295310688,
      "name": "mm_account_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1055",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_realloc",
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295310688,
      "name": "mm_account_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int mm_account_pinned_pages(struct mmpin * mmp, size_t size)
```

```json
{
  "name": "mm_account_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278214654,
      "name": "mm_account_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1055",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_realloc",
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278214654,
      "name": "mm_account_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int mm_account_pinned_pages(struct mmpin * mmp, size_t size)
```

```json
{
  "name": "mm_account_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587991664,
      "name": "mm_account_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1055",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_realloc",
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587991664,
      "name": "mm_account_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int mm_account_pinned_pages(struct mmpin * mmp, size_t size)
```

```json
{
  "name": "mm_account_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587704768,
      "name": "mm_account_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1055",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_realloc",
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587704768,
      "name": "mm_account_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int mm_account_pinned_pages(struct mmpin * mmp, size_t size)
```

```json
{
  "name": "mm_account_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588323440,
      "name": "mm_account_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1055",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_realloc",
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588323440,
      "name": "mm_account_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int mm_account_pinned_pages(struct mmpin * mmp, size_t size)
```

```json
{
  "name": "mm_account_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588458864,
      "name": "mm_account_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1055",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_realloc",
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588458864,
      "name": "mm_account_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int mm_account_pinned_pages(struct mmpin * mmp, size_t size)
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
