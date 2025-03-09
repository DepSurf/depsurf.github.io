# Function: <code>swap_vma_readahead</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swap_vma_readahead",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581238251,
      "name": "swap_vma_readahead",
      "external": false,
      "loc": "mm/swap_state.c:732",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
  "name": "swap_vma_readahead",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581321659,
      "name": "swap_vma_readahead",
      "external": false,
      "loc": "mm/swap_state.c:694",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
  "name": "swap_vma_readahead",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581432735,
      "name": "swap_vma_readahead",
      "external": false,
      "loc": "mm/swap_state.c:722",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
  "name": "swap_vma_readahead",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581496975,
      "name": "swap_vma_readahead",
      "external": false,
      "loc": "mm/swap_state.c:722",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
struct page * swap_vma_readahead(swp_entry_t fentry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_vma_readahead",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581702080,
      "name": "swap_vma_readahead",
      "external": false,
      "loc": "mm/swap_state.c:740",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581702080,
      "name": "swap_vma_readahead",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 555
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
struct page * swap_vma_readahead(swp_entry_t fentry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_vma_readahead",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581749792,
      "name": "swap_vma_readahead",
      "external": false,
      "loc": "mm/swap_state.c:832",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749792,
      "name": "swap_vma_readahead",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 561
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
struct page * swap_vma_readahead(swp_entry_t fentry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_vma_readahead",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581777600,
      "name": "swap_vma_readahead",
      "external": false,
      "loc": "mm/swap_state.c:801",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581777600,
      "name": "swap_vma_readahead",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 587
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
struct page * swap_vma_readahead(swp_entry_t fentry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_vma_readahead",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swap_vma_readahead",
      "external": false,
      "loc": "mm/swap_state.c:788",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582060688,
      "name": "swap_vma_readahead",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 18446744071592208987,
      "name": "swap_vma_readahead.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
struct page * swap_vma_readahead(swp_entry_t fentry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_vma_readahead",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swap_vma_readahead",
      "external": false,
      "loc": "mm/swap_state.c:801",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582498928,
      "name": "swap_vma_readahead",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 783
    },
    {
      "addr": 18446744071593987043,
      "name": "swap_vma_readahead.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
struct page * swap_vma_readahead(swp_entry_t fentry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_vma_readahead",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swap_vma_readahead",
      "external": false,
      "loc": "mm/swap_state.c:785",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583012880,
      "name": "swap_vma_readahead",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 783
    },
    {
      "addr": 18446744071596039034,
      "name": "swap_vma_readahead.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
struct page * swap_vma_readahead(swp_entry_t fentry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_vma_readahead",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swap_vma_readahead",
      "external": false,
      "loc": "mm/swap_state.c:783",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583221184,
      "name": "swap_vma_readahead",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1216
    },
    {
      "addr": 18446744071596561179,
      "name": "swap_vma_readahead.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct folio * swap_vma_readahead(swp_entry_t targ_entry, gfp_t gfp_mask, struct mempolicy * mpol, long unsigned int targ_ilx, struct vm_fault * vmf)
```

```json
{
  "name": "swap_vma_readahead",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swap_vma_readahead",
      "external": false,
      "loc": "mm/swap_state.c:799",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583456496,
      "name": "swap_vma_readahead",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1207
    },
    {
      "addr": 18446744071597466771,
      "name": "swap_vma_readahead.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "swap_vma_readahead",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492917252,
      "name": "swap_vma_readahead",
      "external": false,
      "loc": "mm/swap_state.c:722",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "swap_vma_readahead",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226708112,
      "name": "swap_vma_readahead",
      "external": false,
      "loc": "mm/swap_state.c:722",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "swap_vma_readahead",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286324248,
      "name": "swap_vma_readahead",
      "external": false,
      "loc": "mm/swap_state.c:722",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "swap_vma_readahead",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272839202,
      "name": "swap_vma_readahead",
      "external": false,
      "loc": "mm/swap_state.c:722",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swap_vma_readahead",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581465689,
      "name": "swap_vma_readahead",
      "external": false,
      "loc": "mm/swap_state.c:680",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
  "name": "swap_vma_readahead",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581407954,
      "name": "swap_vma_readahead",
      "external": false,
      "loc": "mm/swap_state.c:722",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
  "name": "swap_vma_readahead",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581457023,
      "name": "swap_vma_readahead",
      "external": false,
      "loc": "mm/swap_state.c:722",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
  "name": "swap_vma_readahead",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581521455,
      "name": "swap_vma_readahead",
      "external": false,
      "loc": "mm/swap_state.c:722",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
struct page * swap_vma_readahead(swp_entry_t fentry, gfp_t gfp_mask, struct vm_fault * vmf)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>swp_entry_t targ_entry</code>
</li>
<li>
<b>Param added. </b>
<code>struct mempolicy * mpol</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int targ_ilx</code>
</li>
<li>
<b>Param removed. </b>
<code>swp_entry_t fentry</code>
</li>
<li>
<b>Param reordered. </b>
<code>fentry, gfp_mask, vmf</code> ➡️ <code>targ_entry, gfp_mask, mpol, targ_ilx, vmf</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct page *</code> ➡️ <code>struct folio *</code>
</li>
</ul>
</details>
</li>
</ul>
