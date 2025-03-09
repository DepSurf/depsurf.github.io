# Function: <code>__swap_entry_free</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
unsigned char __swap_entry_free(struct swap_info_struct * p, swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_entry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580997120,
      "name": "__swap_entry_free",
      "external": false,
      "loc": "mm/swapfile.c:1075",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580997120,
      "name": "__swap_entry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
unsigned char __swap_entry_free(struct swap_info_struct * p, swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_entry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581103552,
      "name": "__swap_entry_free",
      "external": false,
      "loc": "mm/swapfile.c:1110",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581103552,
      "name": "__swap_entry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
unsigned char __swap_entry_free(struct swap_info_struct * p, swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_entry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581244192,
      "name": "__swap_entry_free",
      "external": false,
      "loc": "mm/swapfile.c:1110",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581244192,
      "name": "__swap_entry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__swap_entry_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581327856,
      "name": "__swap_entry_free",
      "external": false,
      "loc": "mm/swapfile.c:1177",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581327856,
      "name": "__swap_entry_free.constprop.48",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__swap_entry_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581438752,
      "name": "__swap_entry_free",
      "external": false,
      "loc": "mm/swapfile.c:1277",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581438752,
      "name": "__swap_entry_free.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__swap_entry_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581502976,
      "name": "__swap_entry_free",
      "external": false,
      "loc": "mm/swapfile.c:1277",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581502976,
      "name": "__swap_entry_free.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
unsigned char __swap_entry_free(struct swap_info_struct * p, swp_entry_t entry)
```

```json
{
  "name": "__swap_entry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581710992,
      "name": "__swap_entry_free",
      "external": false,
      "loc": "mm/swapfile.c:1313",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:free_swap_and_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581710992,
      "name": "__swap_entry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
unsigned char __swap_entry_free(struct swap_info_struct * p, swp_entry_t entry)
```

```json
{
  "name": "__swap_entry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581758784,
      "name": "__swap_entry_free",
      "external": false,
      "loc": "mm/swapfile.c:1331",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:free_swap_and_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758784,
      "name": "__swap_entry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
unsigned char __swap_entry_free(struct swap_info_struct * p, swp_entry_t entry)
```

```json
{
  "name": "__swap_entry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581785728,
      "name": "__swap_entry_free",
      "external": false,
      "loc": "mm/swapfile.c:1330",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:free_swap_and_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581785728,
      "name": "__swap_entry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
unsigned char __swap_entry_free(struct swap_info_struct * p, swp_entry_t entry)
```

```json
{
  "name": "__swap_entry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582069504,
      "name": "__swap_entry_free",
      "external": false,
      "loc": "mm/swapfile.c:1299",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:free_swap_and_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582069504,
      "name": "__swap_entry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
unsigned char __swap_entry_free(struct swap_info_struct * p, swp_entry_t entry)
```

```json
{
  "name": "__swap_entry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582508688,
      "name": "__swap_entry_free",
      "external": false,
      "loc": "mm/swapfile.c:1282",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:free_swap_and_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582508688,
      "name": "__swap_entry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
unsigned char __swap_entry_free(struct swap_info_struct * p, swp_entry_t entry)
```

```json
{
  "name": "__swap_entry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583023808,
      "name": "__swap_entry_free",
      "external": false,
      "loc": "mm/swapfile.c:1286",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:free_swap_and_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583023808,
      "name": "__swap_entry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
unsigned char __swap_entry_free(struct swap_info_struct * p, swp_entry_t entry)
```

```json
{
  "name": "__swap_entry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583232976,
      "name": "__swap_entry_free",
      "external": false,
      "loc": "mm/swapfile.c:1292",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:free_swap_and_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583232976,
      "name": "__swap_entry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
unsigned char __swap_entry_free(struct swap_info_struct * p, swp_entry_t entry)
```

```json
{
  "name": "__swap_entry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583467424,
      "name": "__swap_entry_free",
      "external": false,
      "loc": "mm/swapfile.c:1292",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:free_swap_and_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583467424,
      "name": "__swap_entry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
  "name": "__swap_entry_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492924296,
      "name": "__swap_entry_free",
      "external": false,
      "loc": "mm/swapfile.c:1277",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492924296,
      "name": "__swap_entry_free.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__swap_entry_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226713152,
      "name": "__swap_entry_free",
      "external": false,
      "loc": "mm/swapfile.c:1277",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226713152,
      "name": "__swap_entry_free.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__swap_entry_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286332096,
      "name": "__swap_entry_free",
      "external": false,
      "loc": "mm/swapfile.c:1277",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286332096,
      "name": "__swap_entry_free.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__swap_entry_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272844224,
      "name": "__swap_entry_free",
      "external": false,
      "loc": "mm/swapfile.c:1277",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272844224,
      "name": "__swap_entry_free.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__swap_entry_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581471712,
      "name": "__swap_entry_free",
      "external": false,
      "loc": "mm/swapfile.c:1277",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581471712,
      "name": "__swap_entry_free.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
  "name": "__swap_entry_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581413968,
      "name": "__swap_entry_free",
      "external": false,
      "loc": "mm/swapfile.c:1277",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581413968,
      "name": "__swap_entry_free.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__swap_entry_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581463024,
      "name": "__swap_entry_free",
      "external": false,
      "loc": "mm/swapfile.c:1277",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463024,
      "name": "__swap_entry_free.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__swap_entry_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581527488,
      "name": "__swap_entry_free",
      "external": false,
      "loc": "mm/swapfile.c:1277",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581527488,
      "name": "__swap_entry_free.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
unsigned char __swap_entry_free(struct swap_info_struct * p, swp_entry_t entry, unsigned char usage)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
unsigned char __swap_entry_free(struct swap_info_struct * p, swp_entry_t entry, unsigned char usage)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
unsigned char __swap_entry_free(struct swap_info_struct * p, swp_entry_t entry)
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
