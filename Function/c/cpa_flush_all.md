# Function: <code>cpa_flush_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpa_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579297000,
      "name": "cpa_flush_all",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:160",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpa_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579296441,
      "name": "cpa_flush_all",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:166",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpa_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579311953,
      "name": "cpa_flush_all",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:166",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpa_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579309616,
      "name": "cpa_flush_all",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:173",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpa_flush_all(long unsigned int cache)
```

```json
{
  "name": "cpa_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579322480,
      "name": "cpa_flush_all",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:173",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__set_memory_enc_dec",
        "arch/x86/mm/pageattr.c:__set_memory_enc_dec",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322480,
      "name": "cpa_flush_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void cpa_flush_all(long unsigned int cache)
```

```json
{
  "name": "cpa_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579333344,
      "name": "cpa_flush_all",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:191",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__set_memory_enc_dec",
        "arch/x86/mm/pageattr.c:__set_memory_enc_dec",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579333344,
      "name": "cpa_flush_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void cpa_flush_all(long unsigned int cache)
```

```json
{
  "name": "cpa_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579359936,
      "name": "cpa_flush_all",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:326",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359936,
      "name": "cpa_flush_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void cpa_flush_all(long unsigned int cache)
```

```json
{
  "name": "cpa_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579374528,
      "name": "cpa_flush_all",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:327",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374528,
      "name": "cpa_flush_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void cpa_flush_all(long unsigned int cache)
```

```json
{
  "name": "cpa_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579378816,
      "name": "cpa_flush_all",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:327",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579378816,
      "name": "cpa_flush_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void cpa_flush_all(long unsigned int cache)
```

```json
{
  "name": "cpa_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579417776,
      "name": "cpa_flush_all",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:336",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417776,
      "name": "cpa_flush_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void cpa_flush_all(long unsigned int cache)
```

```json
{
  "name": "cpa_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579417808,
      "name": "cpa_flush_all",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:336",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417808,
      "name": "cpa_flush_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void cpa_flush_all(long unsigned int cache)
```

```json
{
  "name": "cpa_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579421440,
      "name": "cpa_flush_all",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:344",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579421440,
      "name": "cpa_flush_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void cpa_flush_all(long unsigned int cache)
```

```json
{
  "name": "cpa_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpa_flush_all",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:344",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579485024,
      "name": "cpa_flush_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071592088139,
      "name": "cpa_flush_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void cpa_flush_all(long unsigned int cache)
```

```json
{
  "name": "cpa_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpa_flush_all",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:347",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579563904,
      "name": "cpa_flush_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071593855063,
      "name": "cpa_flush_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void cpa_flush_all(long unsigned int cache)
```

```json
{
  "name": "cpa_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpa_flush_all",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:382",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671856,
      "name": "cpa_flush_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071595969756,
      "name": "cpa_flush_all.cold",
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
void cpa_flush_all(long unsigned int cache)
```

```json
{
  "name": "cpa_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpa_flush_all",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:383",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685664,
      "name": "cpa_flush_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071596487346,
      "name": "cpa_flush_all.cold",
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
void cpa_flush_all(long unsigned int cache)
```

```json
{
  "name": "cpa_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpa_flush_all",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:383",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579720192,
      "name": "cpa_flush_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071597383968,
      "name": "cpa_flush_all.cold",
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void cpa_flush_all(long unsigned int cache)
```

```json
{
  "name": "cpa_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579374720,
      "name": "cpa_flush_all",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:327",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374720,
      "name": "cpa_flush_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void cpa_flush_all(long unsigned int cache)
```

```json
{
  "name": "cpa_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579305664,
      "name": "cpa_flush_all",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:327",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305664,
      "name": "cpa_flush_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
void cpa_flush_all(long unsigned int cache)
```

```json
{
  "name": "cpa_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579374640,
      "name": "cpa_flush_all",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:327",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374640,
      "name": "cpa_flush_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void cpa_flush_all(long unsigned int cache)
```

```json
{
  "name": "cpa_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579383120,
      "name": "cpa_flush_all",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:327",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383120,
      "name": "cpa_flush_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void cpa_flush_all(long unsigned int cache)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void cpa_flush_all(long unsigned int cache)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void cpa_flush_all(long unsigned int cache)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void cpa_flush_all(long unsigned int cache)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void cpa_flush_all(long unsigned int cache)
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
