# Function: <code>__split_large_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579292980,
      "name": "__split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:610",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
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
  "name": "__split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579292535,
      "name": "__split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:616",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
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
  "name": "__split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579307960,
      "name": "__split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:616",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
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
  "name": "__split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579305726,
      "name": "__split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:652",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579327934,
      "name": "__split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:652",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579339008,
      "name": "__split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:680",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579365616,
      "name": "__split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:930",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int __split_large_page(struct cpa_data * cpa, pte_t * kpte, long unsigned int address, struct page * base)
```

```json
{
  "name": "__split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:940",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579379904,
      "name": "__split_large_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1499
    },
    {
      "addr": 18446744071579388733,
      "name": "__split_large_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int __split_large_page(struct cpa_data * cpa, pte_t * kpte, long unsigned int address, struct page * base)
```

```json
{
  "name": "__split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:940",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579384208,
      "name": "__split_large_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1499
    },
    {
      "addr": 18446744071579392037,
      "name": "__split_large_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __split_large_page(struct cpa_data * cpa, pte_t * kpte, long unsigned int address, struct page * base)
```

```json
{
  "name": "__split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:960",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424608,
      "name": "__split_large_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1120
    },
    {
      "addr": 18446744071579432613,
      "name": "__split_large_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int __split_large_page(struct cpa_data * cpa, pte_t * kpte, long unsigned int address, struct page * base)
```

```json
{
  "name": "__split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:960",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424304,
      "name": "__split_large_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1120
    },
    {
      "addr": 18446744071591270549,
      "name": "__split_large_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int __split_large_page(struct cpa_data * cpa, pte_t * kpte, long unsigned int address, struct page * base)
```

```json
{
  "name": "__split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:968",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579427312,
      "name": "__split_large_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1152
    },
    {
      "addr": 18446744071591213309,
      "name": "__split_large_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int __split_large_page(struct cpa_data * cpa, pte_t * kpte, long unsigned int address, struct page * base)
```

```json
{
  "name": "__split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:968",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491552,
      "name": "__split_large_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1194
    },
    {
      "addr": 18446744071592088439,
      "name": "__split_large_page.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int __split_large_page(struct cpa_data * cpa, pte_t * kpte, long unsigned int address, struct page * base)
```

```json
{
  "name": "__split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:960",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571728,
      "name": "__split_large_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1209
    },
    {
      "addr": 18446744071593855338,
      "name": "__split_large_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int __split_large_page(struct cpa_data * cpa, pte_t * kpte, long unsigned int address, struct page * base)
```

```json
{
  "name": "__split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:1037",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579680080,
      "name": "__split_large_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1249
    },
    {
      "addr": 18446744071595970024,
      "name": "__split_large_page.cold",
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
int __split_large_page(struct cpa_data * cpa, pte_t * kpte, long unsigned int address, struct page * base)
```

```json
{
  "name": "__split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:1038",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579693968,
      "name": "__split_large_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1220
    },
    {
      "addr": 18446744071596487614,
      "name": "__split_large_page.cold",
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
int __split_large_page(struct cpa_data * cpa, pte_t * kpte, long unsigned int address, struct page * base)
```

```json
{
  "name": "__split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:1042",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579728496,
      "name": "__split_large_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1220
    },
    {
      "addr": 18446744071597384236,
      "name": "__split_large_page.cold",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int __split_large_page(struct cpa_data * cpa, pte_t * kpte, long unsigned int address, struct page * base)
```

```json
{
  "name": "__split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:940",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579380112,
      "name": "__split_large_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1499
    },
    {
      "addr": 18446744071579387941,
      "name": "__split_large_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579310149,
      "name": "__split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:940",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int __split_large_page(struct cpa_data * cpa, pte_t * kpte, long unsigned int address, struct page * base)
```

```json
{
  "name": "__split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:940",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579380032,
      "name": "__split_large_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1499
    },
    {
      "addr": 18446744071579387861,
      "name": "__split_large_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int __split_large_page(struct cpa_data * cpa, pte_t * kpte, long unsigned int address, struct page * base)
```

```json
{
  "name": "__split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:940",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579388512,
      "name": "__split_large_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1495
    },
    {
      "addr": 18446744071579396389,
      "name": "__split_large_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
int __split_large_page(struct cpa_data * cpa, pte_t * kpte, long unsigned int address, struct page * base)
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
int __split_large_page(struct cpa_data * cpa, pte_t * kpte, long unsigned int address, struct page * base)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __split_large_page(struct cpa_data * cpa, pte_t * kpte, long unsigned int address, struct page * base)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __split_large_page(struct cpa_data * cpa, pte_t * kpte, long unsigned int address, struct page * base)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __split_large_page(struct cpa_data * cpa, pte_t * kpte, long unsigned int address, struct page * base)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int __split_large_page(struct cpa_data * cpa, pte_t * kpte, long unsigned int address, struct page * base)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
