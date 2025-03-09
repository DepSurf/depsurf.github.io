# Function: <code>move_hugetlb_state</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void move_hugetlb_state(struct page * oldpage, struct page * newpage, int reason)
```

```json
{
  "name": "move_hugetlb_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581304592,
      "name": "move_hugetlb_state",
      "external": true,
      "loc": "mm/hugetlb.c:4839",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581304592,
      "name": "move_hugetlb_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void move_hugetlb_state(struct page * oldpage, struct page * newpage, int reason)
```

```json
{
  "name": "move_hugetlb_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581388256,
      "name": "move_hugetlb_state",
      "external": true,
      "loc": "mm/hugetlb.c:4928",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581388256,
      "name": "move_hugetlb_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
void move_hugetlb_state(struct page * oldpage, struct page * newpage, int reason)
```

```json
{
  "name": "move_hugetlb_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581499920,
      "name": "move_hugetlb_state",
      "external": true,
      "loc": "mm/hugetlb.c:5033",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581499920,
      "name": "move_hugetlb_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
void move_hugetlb_state(struct page * oldpage, struct page * newpage, int reason)
```

```json
{
  "name": "move_hugetlb_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581564432,
      "name": "move_hugetlb_state",
      "external": true,
      "loc": "mm/hugetlb.c:5150",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581564432,
      "name": "move_hugetlb_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
void move_hugetlb_state(struct page * oldpage, struct page * newpage, int reason)
```

```json
{
  "name": "move_hugetlb_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581775072,
      "name": "move_hugetlb_state",
      "external": true,
      "loc": "mm/hugetlb.c:5649",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:unmap_and_move_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581775072,
      "name": "move_hugetlb_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void move_hugetlb_state(struct page * oldpage, struct page * newpage, int reason)
```

```json
{
  "name": "move_hugetlb_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581823232,
      "name": "move_hugetlb_state",
      "external": true,
      "loc": "mm/hugetlb.c:5661",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:unmap_and_move_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581823232,
      "name": "move_hugetlb_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void move_hugetlb_state(struct page * oldpage, struct page * newpage, int reason)
```

```json
{
  "name": "move_hugetlb_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581853424,
      "name": "move_hugetlb_state",
      "external": true,
      "loc": "mm/hugetlb.c:5958",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:unmap_and_move_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581853424,
      "name": "move_hugetlb_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void move_hugetlb_state(struct page * oldpage, struct page * newpage, int reason)
```

```json
{
  "name": "move_hugetlb_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "move_hugetlb_state",
      "external": true,
      "loc": "mm/hugetlb.c:6295",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:unmap_and_move_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592215677,
      "name": "move_hugetlb_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071582145104,
      "name": "move_hugetlb_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
void move_hugetlb_state(struct page * oldpage, struct page * newpage, int reason)
```

```json
{
  "name": "move_hugetlb_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "move_hugetlb_state",
      "external": true,
      "loc": "mm/hugetlb.c:7036",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:unmap_and_move_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593994378,
      "name": "move_hugetlb_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071582598976,
      "name": "move_hugetlb_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
void move_hugetlb_state(struct folio * old_folio, struct folio * new_folio, int reason)
```

```json
{
  "name": "move_hugetlb_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "move_hugetlb_state",
      "external": true,
      "loc": "mm/hugetlb.c:7318",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:unmap_and_move_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596044395,
      "name": "move_hugetlb_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071583117760,
      "name": "move_hugetlb_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
void move_hugetlb_state(struct folio * old_folio, struct folio * new_folio, int reason)
```

```json
{
  "name": "move_hugetlb_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "move_hugetlb_state",
      "external": true,
      "loc": "mm/hugetlb.c:7417",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:unmap_and_move_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596566823,
      "name": "move_hugetlb_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071583328032,
      "name": "move_hugetlb_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
void move_hugetlb_state(struct folio * old_folio, struct folio * new_folio, int reason)
```

```json
{
  "name": "move_hugetlb_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "move_hugetlb_state",
      "external": true,
      "loc": "mm/hugetlb.c:7554",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:unmap_and_move_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597472346,
      "name": "move_hugetlb_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071583564224,
      "name": "move_hugetlb_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
void move_hugetlb_state(struct page * oldpage, struct page * newpage, int reason)
```

```json
{
  "name": "move_hugetlb_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492999256,
      "name": "move_hugetlb_state",
      "external": true,
      "loc": "mm/hugetlb.c:5150",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492999256,
      "name": "move_hugetlb_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void move_hugetlb_state(struct page * oldpage, struct page * newpage, int reason)
```

```json
{
  "name": "move_hugetlb_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286426384,
      "name": "move_hugetlb_state",
      "external": true,
      "loc": "mm/hugetlb.c:5150",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286426384,
      "name": "move_hugetlb_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
void move_hugetlb_state(struct page * oldpage, struct page * newpage, int reason)
```

```json
{
  "name": "move_hugetlb_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272900758,
      "name": "move_hugetlb_state",
      "external": true,
      "loc": "mm/hugetlb.c:5150",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272900758,
      "name": "move_hugetlb_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void move_hugetlb_state(struct page * oldpage, struct page * newpage, int reason)
```

```json
{
  "name": "move_hugetlb_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581533168,
      "name": "move_hugetlb_state",
      "external": true,
      "loc": "mm/hugetlb.c:5150",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581533168,
      "name": "move_hugetlb_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
void move_hugetlb_state(struct page * oldpage, struct page * newpage, int reason)
```

```json
{
  "name": "move_hugetlb_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581474944,
      "name": "move_hugetlb_state",
      "external": true,
      "loc": "mm/hugetlb.c:5150",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581474944,
      "name": "move_hugetlb_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
void move_hugetlb_state(struct page * oldpage, struct page * newpage, int reason)
```

```json
{
  "name": "move_hugetlb_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581524480,
      "name": "move_hugetlb_state",
      "external": true,
      "loc": "mm/hugetlb.c:5150",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581524480,
      "name": "move_hugetlb_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
void move_hugetlb_state(struct page * oldpage, struct page * newpage, int reason)
```

```json
{
  "name": "move_hugetlb_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581589408,
      "name": "move_hugetlb_state",
      "external": true,
      "loc": "mm/hugetlb.c:5150",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581589408,
      "name": "move_hugetlb_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void move_hugetlb_state(struct page * oldpage, struct page * newpage, int reason)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio * old_folio</code>
</li>
<li>
<b>Param added. </b>
<code>struct folio * new_folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * oldpage</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * newpage</code>
</li>
</ul>
</details>
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
void move_hugetlb_state(struct page * oldpage, struct page * newpage, int reason)
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
