# Function: <code>mm_unaccount_pinned_pages</code>

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
  "name": "mm_unaccount_pinned_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587446112,
      "name": "mm_unaccount_pinned_pages",
      "external": false,
      "loc": "net/core/skbuff.c:923",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_zerocopy_callback"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void mm_unaccount_pinned_pages(struct mmpin * mmp)
```

```json
{
  "name": "mm_unaccount_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587735184,
      "name": "mm_unaccount_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:926",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587735184,
      "name": "mm_unaccount_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void mm_unaccount_pinned_pages(struct mmpin * mmp)
```

```json
{
  "name": "mm_unaccount_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587869296,
      "name": "mm_unaccount_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:928",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587869296,
      "name": "mm_unaccount_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void mm_unaccount_pinned_pages(struct mmpin * mmp)
```

```json
{
  "name": "mm_unaccount_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588174576,
      "name": "mm_unaccount_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1086",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588174576,
      "name": "mm_unaccount_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void mm_unaccount_pinned_pages(struct mmpin * mmp)
```

```json
{
  "name": "mm_unaccount_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588379712,
      "name": "mm_unaccount_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1086",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588379712,
      "name": "mm_unaccount_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void mm_unaccount_pinned_pages(struct mmpin * mmp)
```

```json
{
  "name": "mm_unaccount_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589254696,
      "name": "mm_unaccount_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1085",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_zerocopy_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589240960,
      "name": "mm_unaccount_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void mm_unaccount_pinned_pages(struct mmpin * mmp)
```

```json
{
  "name": "mm_unaccount_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589253864,
      "name": "mm_unaccount_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1096",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_zerocopy_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589240240,
      "name": "mm_unaccount_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void mm_unaccount_pinned_pages(struct mmpin * mmp)
```

```json
{
  "name": "mm_unaccount_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589156213,
      "name": "mm_unaccount_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1139",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__msg_zerocopy_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589135088,
      "name": "mm_unaccount_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void mm_unaccount_pinned_pages(struct mmpin * mmp)
```

```json
{
  "name": "mm_unaccount_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589876273,
      "name": "mm_unaccount_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1160",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:msg_zerocopy_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589854800,
      "name": "mm_unaccount_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void mm_unaccount_pinned_pages(struct mmpin * mmp)
```

```json
{
  "name": "mm_unaccount_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591408213,
      "name": "mm_unaccount_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1162",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__msg_zerocopy_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591379856,
      "name": "mm_unaccount_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void mm_unaccount_pinned_pages(struct mmpin * mmp)
```

```json
{
  "name": "mm_unaccount_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593172837,
      "name": "mm_unaccount_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1342",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__msg_zerocopy_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593140688,
      "name": "mm_unaccount_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void mm_unaccount_pinned_pages(struct mmpin * mmp)
```

```json
{
  "name": "mm_unaccount_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593626885,
      "name": "mm_unaccount_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1486",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__msg_zerocopy_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593593504,
      "name": "mm_unaccount_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void mm_unaccount_pinned_pages(struct mmpin * mmp)
```

```json
{
  "name": "mm_unaccount_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594402197,
      "name": "mm_unaccount_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1574",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__msg_zerocopy_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594366400,
      "name": "mm_unaccount_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void mm_unaccount_pinned_pages(struct mmpin * mmp)
```

```json
{
  "name": "mm_unaccount_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501901328,
      "name": "mm_unaccount_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1086",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501901328,
      "name": "mm_unaccount_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void mm_unaccount_pinned_pages(struct mmpin * mmp)
```

```json
{
  "name": "mm_unaccount_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234654568,
      "name": "mm_unaccount_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1086",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234654568,
      "name": "mm_unaccount_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void mm_unaccount_pinned_pages(struct mmpin * mmp)
```

```json
{
  "name": "mm_unaccount_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295302992,
      "name": "mm_unaccount_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1086",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295302992,
      "name": "mm_unaccount_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void mm_unaccount_pinned_pages(struct mmpin * mmp)
```

```json
{
  "name": "mm_unaccount_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278223734,
      "name": "mm_unaccount_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1086",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_zerocopy_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278211044,
      "name": "mm_unaccount_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void mm_unaccount_pinned_pages(struct mmpin * mmp)
```

```json
{
  "name": "mm_unaccount_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587986496,
      "name": "mm_unaccount_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1086",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587986496,
      "name": "mm_unaccount_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void mm_unaccount_pinned_pages(struct mmpin * mmp)
```

```json
{
  "name": "mm_unaccount_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587699600,
      "name": "mm_unaccount_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1086",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587699600,
      "name": "mm_unaccount_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void mm_unaccount_pinned_pages(struct mmpin * mmp)
```

```json
{
  "name": "mm_unaccount_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588318272,
      "name": "mm_unaccount_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1086",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588318272,
      "name": "mm_unaccount_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void mm_unaccount_pinned_pages(struct mmpin * mmp)
```

```json
{
  "name": "mm_unaccount_pinned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588453616,
      "name": "mm_unaccount_pinned_pages",
      "external": true,
      "loc": "net/core/skbuff.c:1086",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588453616,
      "name": "mm_unaccount_pinned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void mm_unaccount_pinned_pages(struct mmpin * mmp)
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
