# Function: <code>vmemmap_verify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587361204,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:90",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587361204,
      "name": "vmemmap_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587862616,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:162",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587862616,
      "name": "vmemmap_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588077322,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:162",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588077322,
      "name": "vmemmap_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588303775,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:162",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588303775,
      "name": "vmemmap_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588869046,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:165",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588869046,
      "name": "vmemmap_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589248026,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:143",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589248026,
      "name": "vmemmap_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589490312,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:132",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589490312,
      "name": "vmemmap_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589951278,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:132",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589951278,
      "name": "vmemmap_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590178805,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:132",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590178805,
      "name": "vmemmap_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591197110,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:131",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591197110,
      "name": "vmemmap_verify",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591692012,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:132",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591692012,
      "name": "vmemmap_verify",
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
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591634779,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:132",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591634779,
      "name": "vmemmap_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592808920,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:486",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592808920,
      "name": "vmemmap_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594710048,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:532",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "mm/sparse-vmemmap.c:vmemmap_populate_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594710048,
      "name": "vmemmap_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596454736,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:133",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_check_pmd",
        "mm/sparse-vmemmap.c:vmemmap_populate_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596454736,
      "name": "vmemmap_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596996064,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:133",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_check_pmd",
        "mm/sparse-vmemmap.c:vmemmap_populate_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596996064,
      "name": "vmemmap_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597925552,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:133",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_check_pmd",
        "mm/sparse-vmemmap.c:vmemmap_populate_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597925552,
      "name": "vmemmap_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503921780,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:132",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/mmu.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503921780,
      "name": "vmemmap_verify",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297817296,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:132",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297817296,
      "name": "vmemmap_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270896982,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:132",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270896982,
      "name": "vmemmap_verify",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589781093,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:132",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589781093,
      "name": "vmemmap_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589503916,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:132",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589503916,
      "name": "vmemmap_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590224501,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:132",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590224501,
      "name": "vmemmap_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vmemmap_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590274859,
      "name": "vmemmap_verify",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:132",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590274859,
      "name": "vmemmap_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void vmemmap_verify(pte_t * pte, int node, long unsigned int start, long unsigned int end)
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
