# Function: <code>cpa_flush</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void cpa_flush(struct cpa_data * data, int cache)
```

```json
{
  "name": "cpa_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579364992,
      "name": "cpa_flush",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:342",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071579364992,
      "name": "cpa_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
void cpa_flush(struct cpa_data * data, int cache)
```

```json
{
  "name": "cpa_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579379536,
      "name": "cpa_flush",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:343",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071579379536,
      "name": "cpa_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
void cpa_flush(struct cpa_data * data, int cache)
```

```json
{
  "name": "cpa_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579383824,
      "name": "cpa_flush",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:343",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071579383824,
      "name": "cpa_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
void cpa_flush(struct cpa_data * data, int cache)
```

```json
{
  "name": "cpa_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579423456,
      "name": "cpa_flush",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:352",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579423456,
      "name": "cpa_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
void cpa_flush(struct cpa_data * data, int cache)
```

```json
{
  "name": "cpa_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579423152,
      "name": "cpa_flush",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:352",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579423152,
      "name": "cpa_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
void cpa_flush(struct cpa_data * data, int cache)
```

```json
{
  "name": "cpa_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579426144,
      "name": "cpa_flush",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:360",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426144,
      "name": "cpa_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
void cpa_flush(struct cpa_data * data, int cache)
```

```json
{
  "name": "cpa_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpa_flush",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:360",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579489872,
      "name": "cpa_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    },
    {
      "addr": 18446744071592088253,
      "name": "cpa_flush.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void cpa_flush(struct cpa_data * data, int cache)
```

```json
{
  "name": "cpa_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpa_flush",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:363",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569888,
      "name": "cpa_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
    },
    {
      "addr": 18446744071593855144,
      "name": "cpa_flush.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void cpa_flush(struct cpa_data * data, int cache)
```

```json
{
  "name": "cpa_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpa_flush",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:398",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579678224,
      "name": "cpa_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
    },
    {
      "addr": 18446744071595969830,
      "name": "cpa_flush.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void cpa_flush(struct cpa_data * data, int cache)
```

```json
{
  "name": "cpa_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpa_flush",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:399",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579692080,
      "name": "cpa_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
    },
    {
      "addr": 18446744071596487420,
      "name": "cpa_flush.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void cpa_flush(struct cpa_data * data, int cache)
```

```json
{
  "name": "cpa_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpa_flush",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:399",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579726608,
      "name": "cpa_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
    },
    {
      "addr": 18446744071597384042,
      "name": "cpa_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void cpa_flush(struct cpa_data * data, int cache)
```

```json
{
  "name": "cpa_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579379728,
      "name": "cpa_flush",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:343",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071579379728,
      "name": "cpa_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
void cpa_flush(struct cpa_data * data, int cache)
```

```json
{
  "name": "cpa_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579309456,
      "name": "cpa_flush",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:343",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071579309456,
      "name": "cpa_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
void cpa_flush(struct cpa_data * data, int cache)
```

```json
{
  "name": "cpa_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579379648,
      "name": "cpa_flush",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:343",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071579379648,
      "name": "cpa_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
void cpa_flush(struct cpa_data * data, int cache)
```

```json
{
  "name": "cpa_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579388128,
      "name": "cpa_flush",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:343",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071579388128,
      "name": "cpa_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void cpa_flush(struct cpa_data * data, int cache)
```
</details>
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
void cpa_flush(struct cpa_data * data, int cache)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void cpa_flush(struct cpa_data * data, int cache)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void cpa_flush(struct cpa_data * data, int cache)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void cpa_flush(struct cpa_data * data, int cache)
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
