# Function: <code>__should_split_large_page</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__should_split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579365509,
      "name": "__should_split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:736",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__should_split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579381536,
      "name": "__should_split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:745",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__should_split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579385840,
      "name": "__should_split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:745",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __should_split_large_page(pte_t * kpte, long unsigned int address, struct cpa_data * cpa)
```

```json
{
  "name": "__should_split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579425728,
      "name": "__should_split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:765",
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
      "addr": 18446744071579425728,
      "name": "__should_split_large_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1064
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
int __should_split_large_page(pte_t * kpte, long unsigned int address, struct cpa_data * cpa)
```

```json
{
  "name": "__should_split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579425424,
      "name": "__should_split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:765",
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
      "addr": 18446744071579425424,
      "name": "__should_split_large_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1064
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
int __should_split_large_page(pte_t * kpte, long unsigned int address, struct cpa_data * cpa)
```

```json
{
  "name": "__should_split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579428464,
      "name": "__should_split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:773",
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
      "addr": 18446744071579428464,
      "name": "__should_split_large_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1039
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
int __should_split_large_page(pte_t * kpte, long unsigned int address, struct cpa_data * cpa)
```

```json
{
  "name": "__should_split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__should_split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:773",
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
      "addr": 18446744071579492752,
      "name": "__should_split_large_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1002
    },
    {
      "addr": 18446744071592088493,
      "name": "__should_split_large_page.cold",
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
int __should_split_large_page(pte_t * kpte, long unsigned int address, struct cpa_data * cpa)
```

```json
{
  "name": "__should_split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__should_split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:765",
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
      "addr": 18446744071579572944,
      "name": "__should_split_large_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1137
    },
    {
      "addr": 18446744071593855389,
      "name": "__should_split_large_page.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int __should_split_large_page(pte_t * kpte, long unsigned int address, struct cpa_data * cpa)
```

```json
{
  "name": "__should_split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__should_split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:840",
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
      "addr": 18446744071579681360,
      "name": "__should_split_large_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1330
    },
    {
      "addr": 18446744071595970045,
      "name": "__should_split_large_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int __should_split_large_page(pte_t * kpte, long unsigned int address, struct cpa_data * cpa)
```

```json
{
  "name": "__should_split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__should_split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:841",
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
      "addr": 18446744071579695216,
      "name": "__should_split_large_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1339
    },
    {
      "addr": 18446744071596487635,
      "name": "__should_split_large_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int __should_split_large_page(pte_t * kpte, long unsigned int address, struct cpa_data * cpa)
```

```json
{
  "name": "__should_split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__should_split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:845",
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
      "addr": 18446744071579729744,
      "name": "__should_split_large_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1339
    },
    {
      "addr": 18446744071597384257,
      "name": "__should_split_large_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__should_split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579381744,
      "name": "__should_split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:745",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__should_split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579310033,
      "name": "__should_split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:745",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__should_split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579381664,
      "name": "__should_split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:745",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__should_split_large_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579390144,
      "name": "__should_split_large_page",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:745",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __should_split_large_page(pte_t * kpte, long unsigned int address, struct cpa_data * cpa)
```
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
