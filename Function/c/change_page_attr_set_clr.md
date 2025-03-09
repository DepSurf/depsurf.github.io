# Function: <code>change_page_attr_set_clr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```

```json
{
  "name": "change_page_attr_set_clr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579296208,
      "name": "change_page_attr_set_clr",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:1365",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:set_memory_nx",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:set_memory_x",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_memory_uc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:set_memory_np",
        "arch/x86/mm/pageattr.c:set_memory_4k",
        "arch/x86/mm/pageattr.c:set_pages_ro",
        "arch/x86/mm/pageattr.c:set_pages_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579296208,
      "name": "change_page_attr_set_clr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1261
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
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```

```json
{
  "name": "change_page_attr_set_clr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579295632,
      "name": "change_page_attr_set_clr",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:1373",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:set_pages_rw",
        "arch/x86/mm/pageattr.c:set_pages_ro",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_4k",
        "arch/x86/mm/pageattr.c:set_memory_np",
        "arch/x86/mm/pageattr.c:set_memory_nx",
        "arch/x86/mm/pageattr.c:set_memory_x",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579295632,
      "name": "change_page_attr_set_clr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1296
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
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```

```json
{
  "name": "change_page_attr_set_clr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579311104,
      "name": "change_page_attr_set_clr",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:1373",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:set_pages_rw",
        "arch/x86/mm/pageattr.c:set_pages_ro",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_4k",
        "arch/x86/mm/pageattr.c:set_memory_np",
        "arch/x86/mm/pageattr.c:set_memory_nx",
        "arch/x86/mm/pageattr.c:set_memory_x",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579311104,
      "name": "change_page_attr_set_clr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1350
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
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```

```json
{
  "name": "change_page_attr_set_clr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579308768,
      "name": "change_page_attr_set_clr",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:1419",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:set_pages_rw",
        "arch/x86/mm/pageattr.c:set_pages_ro",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_4k",
        "arch/x86/mm/pageattr.c:set_memory_np",
        "arch/x86/mm/pageattr.c:set_memory_nx",
        "arch/x86/mm/pageattr.c:set_memory_x",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579308768,
      "name": "change_page_attr_set_clr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1215
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
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```

```json
{
  "name": "change_page_attr_set_clr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579331168,
      "name": "change_page_attr_set_clr",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:1419",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:set_pages_rw",
        "arch/x86/mm/pageattr.c:set_pages_ro",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_4k",
        "arch/x86/mm/pageattr.c:set_memory_np",
        "arch/x86/mm/pageattr.c:set_memory_nx",
        "arch/x86/mm/pageattr.c:set_memory_x",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579331168,
      "name": "change_page_attr_set_clr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 983
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
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```

```json
{
  "name": "change_page_attr_set_clr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579342176,
      "name": "change_page_attr_set_clr",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:1446",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:set_pages_rw",
        "arch/x86/mm/pageattr.c:set_pages_ro",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_global",
        "arch/x86/mm/pageattr.c:set_memory_nonglobal",
        "arch/x86/mm/pageattr.c:set_memory_4k",
        "arch/x86/mm/pageattr.c:set_memory_np_noalias",
        "arch/x86/mm/pageattr.c:set_memory_np",
        "arch/x86/mm/pageattr.c:set_memory_nx",
        "arch/x86/mm/pageattr.c:set_memory_x",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579342176,
      "name": "change_page_attr_set_clr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 848
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
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```

```json
{
  "name": "change_page_attr_set_clr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579369168,
      "name": "change_page_attr_set_clr",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:1653",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:set_pages_rw",
        "arch/x86/mm/pageattr.c:set_pages_ro",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_global",
        "arch/x86/mm/pageattr.c:set_memory_nonglobal",
        "arch/x86/mm/pageattr.c:set_memory_4k",
        "arch/x86/mm/pageattr.c:set_memory_np_noalias",
        "arch/x86/mm/pageattr.c:set_memory_np",
        "arch/x86/mm/pageattr.c:set_memory_nx",
        "arch/x86/mm/pageattr.c:set_memory_x",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579369168,
      "name": "change_page_attr_set_clr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```

```json
{
  "name": "change_page_attr_set_clr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579384160,
      "name": "change_page_attr_set_clr",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:1664",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:set_pages_rw",
        "arch/x86/mm/pageattr.c:set_pages_ro",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_global",
        "arch/x86/mm/pageattr.c:set_memory_nonglobal",
        "arch/x86/mm/pageattr.c:set_memory_4k",
        "arch/x86/mm/pageattr.c:set_memory_np_noalias",
        "arch/x86/mm/pageattr.c:set_memory_np",
        "arch/x86/mm/pageattr.c:set_memory_nx",
        "arch/x86/mm/pageattr.c:set_memory_x",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579384160,
      "name": "change_page_attr_set_clr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```

```json
{
  "name": "change_page_attr_set_clr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579388464,
      "name": "change_page_attr_set_clr",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:1664",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:set_pages_rw",
        "arch/x86/mm/pageattr.c:set_pages_ro",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_global",
        "arch/x86/mm/pageattr.c:set_memory_nonglobal",
        "arch/x86/mm/pageattr.c:set_memory_4k",
        "arch/x86/mm/pageattr.c:set_memory_np_noalias",
        "arch/x86/mm/pageattr.c:set_memory_np",
        "arch/x86/mm/pageattr.c:set_memory_nx",
        "arch/x86/mm/pageattr.c:set_memory_x",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579388464,
      "name": "change_page_attr_set_clr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```

```json
{
  "name": "change_page_attr_set_clr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579428416,
      "name": "change_page_attr_set_clr",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:1687",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:set_pages_rw",
        "arch/x86/mm/pat/set_memory.c:set_pages_ro",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_global",
        "arch/x86/mm/pat/set_memory.c:set_memory_nonglobal",
        "arch/x86/mm/pat/set_memory.c:set_memory_4k",
        "arch/x86/mm/pat/set_memory.c:set_memory_np_noalias",
        "arch/x86/mm/pat/set_memory.c:set_memory_np",
        "arch/x86/mm/pat/set_memory.c:set_memory_nx",
        "arch/x86/mm/pat/set_memory.c:set_memory_x",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wt",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/set_memory.c:__set_memory_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579428416,
      "name": "change_page_attr_set_clr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
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
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```

```json
{
  "name": "change_page_attr_set_clr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579427856,
      "name": "change_page_attr_set_clr",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:1687",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:set_pages_rw",
        "arch/x86/mm/pat/set_memory.c:set_pages_ro",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_global",
        "arch/x86/mm/pat/set_memory.c:set_memory_nonglobal",
        "arch/x86/mm/pat/set_memory.c:set_memory_4k",
        "arch/x86/mm/pat/set_memory.c:set_memory_np_noalias",
        "arch/x86/mm/pat/set_memory.c:set_memory_np",
        "arch/x86/mm/pat/set_memory.c:set_memory_nx",
        "arch/x86/mm/pat/set_memory.c:set_memory_x",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wt",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/set_memory.c:__set_memory_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579427856,
      "name": "change_page_attr_set_clr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
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
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```

```json
{
  "name": "change_page_attr_set_clr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579430864,
      "name": "change_page_attr_set_clr",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:1695",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:set_pages_rw",
        "arch/x86/mm/pat/set_memory.c:set_pages_ro",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_global",
        "arch/x86/mm/pat/set_memory.c:set_memory_nonglobal",
        "arch/x86/mm/pat/set_memory.c:set_memory_4k",
        "arch/x86/mm/pat/set_memory.c:set_memory_np_noalias",
        "arch/x86/mm/pat/set_memory.c:set_memory_np",
        "arch/x86/mm/pat/set_memory.c:set_memory_nx",
        "arch/x86/mm/pat/set_memory.c:set_memory_x",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wt",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/set_memory.c:__set_memory_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579430864,
      "name": "change_page_attr_set_clr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```

```json
{
  "name": "change_page_attr_set_clr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579495040,
      "name": "change_page_attr_set_clr",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:1695",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:set_pages_rw",
        "arch/x86/mm/pat/set_memory.c:set_pages_ro",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_global",
        "arch/x86/mm/pat/set_memory.c:set_memory_nonglobal",
        "arch/x86/mm/pat/set_memory.c:set_memory_4k",
        "arch/x86/mm/pat/set_memory.c:set_memory_np_noalias",
        "arch/x86/mm/pat/set_memory.c:set_memory_np",
        "arch/x86/mm/pat/set_memory.c:set_memory_nx",
        "arch/x86/mm/pat/set_memory.c:set_memory_x",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wt",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/set_memory.c:__set_memory_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579495040,
      "name": "change_page_attr_set_clr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```

```json
{
  "name": "change_page_attr_set_clr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579575424,
      "name": "change_page_attr_set_clr",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:1687",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:set_pages_rw",
        "arch/x86/mm/pat/set_memory.c:set_pages_ro",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_global",
        "arch/x86/mm/pat/set_memory.c:set_memory_nonglobal",
        "arch/x86/mm/pat/set_memory.c:set_memory_4k",
        "arch/x86/mm/pat/set_memory.c:set_memory_np_noalias",
        "arch/x86/mm/pat/set_memory.c:set_memory_nx",
        "arch/x86/mm/pat/set_memory.c:set_memory_x",
        "arch/x86/mm/pat/set_memory.c:clear_mce_nospec",
        "arch/x86/mm/pat/set_memory.c:set_mce_nospec",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wt",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/set_memory.c:__set_memory_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579575424,
      "name": "change_page_attr_set_clr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```

```json
{
  "name": "change_page_attr_set_clr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579684320,
      "name": "change_page_attr_set_clr",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:1792",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:set_pages_rw",
        "arch/x86/mm/pat/set_memory.c:set_pages_ro",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_global",
        "arch/x86/mm/pat/set_memory.c:set_memory_nonglobal",
        "arch/x86/mm/pat/set_memory.c:set_memory_4k",
        "arch/x86/mm/pat/set_memory.c:set_memory_np_noalias",
        "arch/x86/mm/pat/set_memory.c:set_memory_rox",
        "arch/x86/mm/pat/set_memory.c:set_memory_nx",
        "arch/x86/mm/pat/set_memory.c:set_memory_x",
        "arch/x86/mm/pat/set_memory.c:clear_mce_nospec",
        "arch/x86/mm/pat/set_memory.c:set_mce_nospec",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wt",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/set_memory.c:__set_memory_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684320,
      "name": "change_page_attr_set_clr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```

```json
{
  "name": "change_page_attr_set_clr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579698192,
      "name": "change_page_attr_set_clr",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:1793",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:set_pages_rw",
        "arch/x86/mm/pat/set_memory.c:set_pages_ro",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_global",
        "arch/x86/mm/pat/set_memory.c:set_memory_nonglobal",
        "arch/x86/mm/pat/set_memory.c:set_memory_4k",
        "arch/x86/mm/pat/set_memory.c:set_memory_np_noalias",
        "arch/x86/mm/pat/set_memory.c:set_memory_rox",
        "arch/x86/mm/pat/set_memory.c:set_memory_nx",
        "arch/x86/mm/pat/set_memory.c:set_memory_x",
        "arch/x86/mm/pat/set_memory.c:clear_mce_nospec",
        "arch/x86/mm/pat/set_memory.c:set_mce_nospec",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wt",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/set_memory.c:__set_memory_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698192,
      "name": "change_page_attr_set_clr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```

```json
{
  "name": "change_page_attr_set_clr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579732720,
      "name": "change_page_attr_set_clr",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:1797",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:set_pages_rw",
        "arch/x86/mm/pat/set_memory.c:set_pages_ro",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_global",
        "arch/x86/mm/pat/set_memory.c:set_memory_nonglobal",
        "arch/x86/mm/pat/set_memory.c:set_memory_4k",
        "arch/x86/mm/pat/set_memory.c:set_memory_np_noalias",
        "arch/x86/mm/pat/set_memory.c:set_memory_rox",
        "arch/x86/mm/pat/set_memory.c:set_memory_nx",
        "arch/x86/mm/pat/set_memory.c:set_memory_x",
        "arch/x86/mm/pat/set_memory.c:clear_mce_nospec",
        "arch/x86/mm/pat/set_memory.c:set_mce_nospec",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wt",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/set_memory.c:__set_memory_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579732720,
      "name": "change_page_attr_set_clr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```

```json
{
  "name": "change_page_attr_set_clr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579384368,
      "name": "change_page_attr_set_clr",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:1664",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:set_pages_rw",
        "arch/x86/mm/pageattr.c:set_pages_ro",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_global",
        "arch/x86/mm/pageattr.c:set_memory_nonglobal",
        "arch/x86/mm/pageattr.c:set_memory_4k",
        "arch/x86/mm/pageattr.c:set_memory_np_noalias",
        "arch/x86/mm/pageattr.c:set_memory_np",
        "arch/x86/mm/pageattr.c:set_memory_nx",
        "arch/x86/mm/pageattr.c:set_memory_x",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579384368,
      "name": "change_page_attr_set_clr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```

```json
{
  "name": "change_page_attr_set_clr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579313792,
      "name": "change_page_attr_set_clr",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:1664",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:set_pages_rw",
        "arch/x86/mm/pageattr.c:set_pages_ro",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_global",
        "arch/x86/mm/pageattr.c:set_memory_nonglobal",
        "arch/x86/mm/pageattr.c:set_memory_4k",
        "arch/x86/mm/pageattr.c:set_memory_np_noalias",
        "arch/x86/mm/pageattr.c:set_memory_np",
        "arch/x86/mm/pageattr.c:set_memory_nx",
        "arch/x86/mm/pageattr.c:set_memory_x",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579313792,
      "name": "change_page_attr_set_clr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```

```json
{
  "name": "change_page_attr_set_clr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579384288,
      "name": "change_page_attr_set_clr",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:1664",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:set_pages_rw",
        "arch/x86/mm/pageattr.c:set_pages_ro",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_global",
        "arch/x86/mm/pageattr.c:set_memory_nonglobal",
        "arch/x86/mm/pageattr.c:set_memory_4k",
        "arch/x86/mm/pageattr.c:set_memory_np_noalias",
        "arch/x86/mm/pageattr.c:set_memory_np",
        "arch/x86/mm/pageattr.c:set_memory_nx",
        "arch/x86/mm/pageattr.c:set_memory_x",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579384288,
      "name": "change_page_attr_set_clr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```

```json
{
  "name": "change_page_attr_set_clr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579392800,
      "name": "change_page_attr_set_clr",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:1664",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:set_pages_rw",
        "arch/x86/mm/pageattr.c:set_pages_ro",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_global",
        "arch/x86/mm/pageattr.c:set_memory_nonglobal",
        "arch/x86/mm/pageattr.c:set_memory_4k",
        "arch/x86/mm/pageattr.c:set_memory_np_noalias",
        "arch/x86/mm/pageattr.c:set_memory_np",
        "arch/x86/mm/pageattr.c:set_memory_nx",
        "arch/x86/mm/pageattr.c:set_memory_x",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579392800,
      "name": "change_page_attr_set_clr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int change_page_attr_set_clr(long unsigned int * addr, int numpages, pgprot_t mask_set, pgprot_t mask_clr, int force_split, int in_flag, struct page * * pages)
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
