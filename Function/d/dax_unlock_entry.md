# Function: <code>dax_unlock_entry</code>

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
void dax_unlock_entry(struct xa_state * xas, void * entry)
```

```json
{
  "name": "dax_unlock_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582043824,
      "name": "dax_unlock_entry",
      "external": false,
      "loc": "fs/dax.c:273",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582043824,
      "name": "dax_unlock_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void dax_unlock_entry(struct xa_state * xas, void * entry)
```

```json
{
  "name": "dax_unlock_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582204464,
      "name": "dax_unlock_entry",
      "external": false,
      "loc": "fs/dax.c:278",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582204464,
      "name": "dax_unlock_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void dax_unlock_entry(struct xa_state * xas, void * entry)
```

```json
{
  "name": "dax_unlock_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582285296,
      "name": "dax_unlock_entry",
      "external": false,
      "loc": "fs/dax.c:279",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582285296,
      "name": "dax_unlock_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void dax_unlock_entry(struct xa_state * xas, void * entry)
```

```json
{
  "name": "dax_unlock_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582569344,
      "name": "dax_unlock_entry",
      "external": false,
      "loc": "fs/dax.c:279",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582569344,
      "name": "dax_unlock_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void dax_unlock_entry(struct xa_state * xas, void * entry)
```

```json
{
  "name": "dax_unlock_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582640912,
      "name": "dax_unlock_entry",
      "external": false,
      "loc": "fs/dax.c:279",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582640912,
      "name": "dax_unlock_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void dax_unlock_entry(struct xa_state * xas, void * entry)
```

```json
{
  "name": "dax_unlock_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582669824,
      "name": "dax_unlock_entry",
      "external": false,
      "loc": "fs/dax.c:290",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582669824,
      "name": "dax_unlock_entry",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void dax_unlock_entry(struct xa_state * xas, void * entry)
```

```json
{
  "name": "dax_unlock_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582996080,
      "name": "dax_unlock_entry",
      "external": false,
      "loc": "fs/dax.c:290",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582996080,
      "name": "dax_unlock_entry",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void dax_unlock_entry(struct xa_state * xas, void * entry)
```

```json
{
  "name": "dax_unlock_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583466672,
      "name": "dax_unlock_entry",
      "external": false,
      "loc": "fs/dax.c:290",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583466672,
      "name": "dax_unlock_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void dax_unlock_entry(struct xa_state * xas, void * entry)
```

```json
{
  "name": "dax_unlock_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584059184,
      "name": "dax_unlock_entry",
      "external": false,
      "loc": "fs/dax.c:290",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_unlock_mapping_entry",
        "fs/dax.c:dax_unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584059184,
      "name": "dax_unlock_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void dax_unlock_entry(struct xa_state * xas, void * entry)
```

```json
{
  "name": "dax_unlock_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584282192,
      "name": "dax_unlock_entry",
      "external": false,
      "loc": "fs/dax.c:290",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_unlock_mapping_entry",
        "fs/dax.c:dax_unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584282192,
      "name": "dax_unlock_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void dax_unlock_entry(struct xa_state * xas, void * entry)
```

```json
{
  "name": "dax_unlock_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584498992,
      "name": "dax_unlock_entry",
      "external": false,
      "loc": "fs/dax.c:276",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_unlock_mapping_entry",
        "fs/dax.c:dax_unlock_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584498992,
      "name": "dax_unlock_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void dax_unlock_entry(struct xa_state * xas, void * entry)
```

```json
{
  "name": "dax_unlock_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493861064,
      "name": "dax_unlock_entry",
      "external": false,
      "loc": "fs/dax.c:279",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493861064,
      "name": "dax_unlock_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void dax_unlock_entry(struct xa_state * xas, void * entry)
```

```json
{
  "name": "dax_unlock_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287487680,
      "name": "dax_unlock_entry",
      "external": false,
      "loc": "fs/dax.c:279",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287487680,
      "name": "dax_unlock_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
void dax_unlock_entry(struct xa_state * xas, void * entry)
```

```json
{
  "name": "dax_unlock_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273427448,
      "name": "dax_unlock_entry",
      "external": false,
      "loc": "fs/dax.c:279",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273427448,
      "name": "dax_unlock_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
void dax_unlock_entry(struct xa_state * xas, void * entry)
```

```json
{
  "name": "dax_unlock_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582254032,
      "name": "dax_unlock_entry",
      "external": false,
      "loc": "fs/dax.c:279",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582254032,
      "name": "dax_unlock_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void dax_unlock_entry(struct xa_state * xas, void * entry)
```

```json
{
  "name": "dax_unlock_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582191696,
      "name": "dax_unlock_entry",
      "external": false,
      "loc": "fs/dax.c:279",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582191696,
      "name": "dax_unlock_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void dax_unlock_entry(struct xa_state * xas, void * entry)
```

```json
{
  "name": "dax_unlock_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582244512,
      "name": "dax_unlock_entry",
      "external": false,
      "loc": "fs/dax.c:279",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582244512,
      "name": "dax_unlock_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void dax_unlock_entry(struct xa_state * xas, void * entry)
```

```json
{
  "name": "dax_unlock_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582322416,
      "name": "dax_unlock_entry",
      "external": false,
      "loc": "fs/dax.c:279",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582322416,
      "name": "dax_unlock_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void dax_unlock_entry(struct xa_state * xas, void * entry)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void dax_unlock_entry(struct xa_state * xas, void * entry)
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
