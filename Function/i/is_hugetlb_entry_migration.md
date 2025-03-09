# Function: <code>is_hugetlb_entry_migration</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580791056,
      "name": "is_hugetlb_entry_migration",
      "external": false,
      "loc": "mm/hugetlb.c:3052",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:follow_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580791056,
      "name": "is_hugetlb_entry_migration",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580914320,
      "name": "is_hugetlb_entry_migration",
      "external": false,
      "loc": "mm/hugetlb.c:3079",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914320,
      "name": "is_hugetlb_entry_migration",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580982896,
      "name": "is_hugetlb_entry_migration",
      "external": false,
      "loc": "mm/hugetlb.c:3185",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580982896,
      "name": "is_hugetlb_entry_migration",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
bool is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581037824,
      "name": "is_hugetlb_entry_migration",
      "external": true,
      "loc": "mm/hugetlb.c:3168",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037824,
      "name": "is_hugetlb_entry_migration",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581147568,
      "name": "is_hugetlb_entry_migration",
      "external": true,
      "loc": "mm/hugetlb.c:3184",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581147568,
      "name": "is_hugetlb_entry_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
bool is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581291008,
      "name": "is_hugetlb_entry_migration",
      "external": true,
      "loc": "mm/hugetlb.c:3214",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581291008,
      "name": "is_hugetlb_entry_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
bool is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581373920,
      "name": "is_hugetlb_entry_migration",
      "external": true,
      "loc": "mm/hugetlb.c:3208",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581373920,
      "name": "is_hugetlb_entry_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
bool is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581484896,
      "name": "is_hugetlb_entry_migration",
      "external": true,
      "loc": "mm/hugetlb.c:3276",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581484896,
      "name": "is_hugetlb_entry_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
bool is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581549312,
      "name": "is_hugetlb_entry_migration",
      "external": true,
      "loc": "mm/hugetlb.c:3393",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581549312,
      "name": "is_hugetlb_entry_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
bool is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581759184,
      "name": "is_hugetlb_entry_migration",
      "external": true,
      "loc": "mm/hugetlb.c:3804",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581759184,
      "name": "is_hugetlb_entry_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581807168,
      "name": "is_hugetlb_entry_migration",
      "external": true,
      "loc": "mm/hugetlb.c:3774",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581807168,
      "name": "is_hugetlb_entry_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
bool is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581835152,
      "name": "is_hugetlb_entry_migration",
      "external": true,
      "loc": "mm/hugetlb.c:3943",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581835152,
      "name": "is_hugetlb_entry_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
bool is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582125376,
      "name": "is_hugetlb_entry_migration",
      "external": true,
      "loc": "mm/hugetlb.c:4232",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582125376,
      "name": "is_hugetlb_entry_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
bool is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582571056,
      "name": "is_hugetlb_entry_migration",
      "external": true,
      "loc": "mm/hugetlb.c:4683",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/migrate.c:__migration_entry_wait_huge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582571056,
      "name": "is_hugetlb_entry_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
bool is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583090592,
      "name": "is_hugetlb_entry_migration",
      "external": true,
      "loc": "mm/hugetlb.c:4922",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/migrate.c:__migration_entry_wait_huge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583090592,
      "name": "is_hugetlb_entry_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
bool is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583300624,
      "name": "is_hugetlb_entry_migration",
      "external": true,
      "loc": "mm/hugetlb.c:4997",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/migrate.c:migration_entry_wait_huge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583300624,
      "name": "is_hugetlb_entry_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583537200,
      "name": "is_hugetlb_entry_migration",
      "external": true,
      "loc": "mm/hugetlb.c:5255",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/mempolicy.c:queue_folios_hugetlb",
        "mm/migrate.c:migration_entry_wait_huge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583537200,
      "name": "is_hugetlb_entry_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492998104,
      "name": "is_hugetlb_entry_migration",
      "external": true,
      "loc": "mm/hugetlb.c:3393",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492984072,
      "name": "is_hugetlb_entry_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286405824,
      "name": "is_hugetlb_entry_migration",
      "external": true,
      "loc": "mm/hugetlb.c:3393",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/hugetlbpage.c:follow_huge_pd",
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286405824,
      "name": "is_hugetlb_entry_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
bool is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272899770,
      "name": "is_hugetlb_entry_migration",
      "external": true,
      "loc": "mm/hugetlb.c:3393",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272888418,
      "name": "is_hugetlb_entry_migration",
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
bool is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581518048,
      "name": "is_hugetlb_entry_migration",
      "external": true,
      "loc": "mm/hugetlb.c:3393",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581518048,
      "name": "is_hugetlb_entry_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
bool is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581460240,
      "name": "is_hugetlb_entry_migration",
      "external": true,
      "loc": "mm/hugetlb.c:3393",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581460240,
      "name": "is_hugetlb_entry_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
bool is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581509360,
      "name": "is_hugetlb_entry_migration",
      "external": true,
      "loc": "mm/hugetlb.c:3393",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581509360,
      "name": "is_hugetlb_entry_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
bool is_hugetlb_entry_migration(pte_t pte)
```

```json
{
  "name": "is_hugetlb_entry_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581574368,
      "name": "is_hugetlb_entry_migration",
      "external": true,
      "loc": "mm/hugetlb.c:3393",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581574368,
      "name": "is_hugetlb_entry_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool is_hugetlb_entry_migration(pte_t pte)
```
</details>
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
