# Function: <code>print_bad_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580663344,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:647",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vm_normal_page",
        "mm/memory.c:vm_normal_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580663344,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 669
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
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580772576,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:652",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:vm_normal_page",
        "mm/memory.c:vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772576,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 685
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
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580837312,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:654",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:vm_normal_page",
        "mm/memory.c:vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580837312,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 685
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
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580882624,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:719",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vm_normal_page",
        "mm/memory.c:vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580882624,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 681
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
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580976256,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:721",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:_vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976256,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 726
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:736",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:_vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581111488,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
    },
    {
      "addr": 18446744071581145984,
      "name": "print_bad_pte.cold.104",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:479",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:_vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581190848,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
    },
    {
      "addr": 18446744071581225808,
      "name": "print_bad_pte.cold.95",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:481",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581263664,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
    },
    {
      "addr": 18446744071581299600,
      "name": "print_bad_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:481",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581322448,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
    },
    {
      "addr": 18446744071581358368,
      "name": "print_bad_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:499",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581518208,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
    },
    {
      "addr": 18446744071581555744,
      "name": "print_bad_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:501",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581563888,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
    },
    {
      "addr": 18446744071591327870,
      "name": "print_bad_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:513",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581584096,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
    },
    {
      "addr": 18446744071591270104,
      "name": "print_bad_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:512",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581849776,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
    },
    {
      "addr": 18446744071592198686,
      "name": "print_bad_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:519",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582241744,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
    },
    {
      "addr": 18446744071593975192,
      "name": "print_bad_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:472",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582735296,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
    },
    {
      "addr": 18446744071596031648,
      "name": "print_bad_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:491",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582949728,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 669
    },
    {
      "addr": 18446744071596553518,
      "name": "print_bad_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:489",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583125008,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 629
    },
    {
      "addr": 18446744071597457283,
      "name": "print_bad_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492727456,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:481",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492727456,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226559396,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:481",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226559396,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286072784,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:481",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286072784,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 884
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
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272718346,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:481",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272718346,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:481",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581291296,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
    },
    {
      "addr": 18446744071581327216,
      "name": "print_bad_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:481",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581235024,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    },
    {
      "addr": 18446744071581270976,
      "name": "print_bad_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:481",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581282496,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
    },
    {
      "addr": 18446744071581318416,
      "name": "print_bad_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void print_bad_pte(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, struct page * page)
```

```json
{
  "name": "print_bad_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_bad_pte",
      "external": false,
      "loc": "mm/memory.c:481",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:vm_normal_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581346512,
      "name": "print_bad_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
    },
    {
      "addr": 18446744071581382393,
      "name": "print_bad_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
