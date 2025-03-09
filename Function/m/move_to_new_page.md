# Function: <code>move_to_new_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int move_to_new_page(struct page * newpage, struct page * page, enum migrate_mode mode)
```

```json
{
  "name": "move_to_new_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580885040,
      "name": "move_to_new_page",
      "external": false,
      "loc": "mm/migrate.c:747",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580885040,
      "name": "move_to_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
int move_to_new_page(struct page * newpage, struct page * page, enum migrate_mode mode)
```

```json
{
  "name": "move_to_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581013328,
      "name": "move_to_new_page",
      "external": false,
      "loc": "mm/migrate.c:847",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581013328,
      "name": "move_to_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 581
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
int move_to_new_page(struct page * newpage, struct page * page, enum migrate_mode mode)
```

```json
{
  "name": "move_to_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581087504,
      "name": "move_to_new_page",
      "external": false,
      "loc": "mm/migrate.c:849",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581087504,
      "name": "move_to_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 581
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
int move_to_new_page(struct page * newpage, struct page * page, enum migrate_mode mode)
```

```json
{
  "name": "move_to_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581135040,
      "name": "move_to_new_page",
      "external": false,
      "loc": "mm/migrate.c:835",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581135040,
      "name": "move_to_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
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
int move_to_new_page(struct page * newpage, struct page * page, enum migrate_mode mode)
```

```json
{
  "name": "move_to_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581253120,
      "name": "move_to_new_page",
      "external": false,
      "loc": "mm/migrate.c:903",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581253120,
      "name": "move_to_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
int move_to_new_page(struct page * newpage, struct page * page, enum migrate_mode mode)
```

```json
{
  "name": "move_to_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581399264,
      "name": "move_to_new_page",
      "external": false,
      "loc": "mm/migrate.c:915",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581399264,
      "name": "move_to_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
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
int move_to_new_page(struct page * newpage, struct page * page, enum migrate_mode mode)
```

```json
{
  "name": "move_to_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581482864,
      "name": "move_to_new_page",
      "external": false,
      "loc": "mm/migrate.c:928",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581482864,
      "name": "move_to_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
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
int move_to_new_page(struct page * newpage, struct page * page, enum migrate_mode mode)
```

```json
{
  "name": "move_to_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581593904,
      "name": "move_to_new_page",
      "external": false,
      "loc": "mm/migrate.c:926",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581593904,
      "name": "move_to_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
int move_to_new_page(struct page * newpage, struct page * page, enum migrate_mode mode)
```

```json
{
  "name": "move_to_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581661984,
      "name": "move_to_new_page",
      "external": false,
      "loc": "mm/migrate.c:927",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581661984,
      "name": "move_to_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
int move_to_new_page(struct page * newpage, struct page * page, enum migrate_mode mode)
```

```json
{
  "name": "move_to_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581883344,
      "name": "move_to_new_page",
      "external": false,
      "loc": "mm/migrate.c:941",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883344,
      "name": "move_to_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
int move_to_new_page(struct page * newpage, struct page * page, enum migrate_mode mode)
```

```json
{
  "name": "move_to_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581929360,
      "name": "move_to_new_page",
      "external": false,
      "loc": "mm/migrate.c:939",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581929360,
      "name": "move_to_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
int move_to_new_page(struct page * newpage, struct page * page, enum migrate_mode mode)
```

```json
{
  "name": "move_to_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581954704,
      "name": "move_to_new_page",
      "external": false,
      "loc": "mm/migrate.c:919",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581954704,
      "name": "move_to_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
int move_to_new_page(struct page * newpage, struct page * page, enum migrate_mode mode)
```

```json
{
  "name": "move_to_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582259440,
      "name": "move_to_new_page",
      "external": false,
      "loc": "mm/migrate.c:882",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582259440,
      "name": "move_to_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int move_to_new_page(struct page * newpage, struct page * page, enum migrate_mode mode)
```

```json
{
  "name": "move_to_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493107776,
      "name": "move_to_new_page",
      "external": false,
      "loc": "mm/migrate.c:927",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493107776,
      "name": "move_to_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
int move_to_new_page(struct page * newpage, struct page * page, enum migrate_mode mode)
```

```json
{
  "name": "move_to_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226804492,
      "name": "move_to_new_page",
      "external": false,
      "loc": "mm/migrate.c:927",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226804492,
      "name": "move_to_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
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
int move_to_new_page(struct page * newpage, struct page * page, enum migrate_mode mode)
```

```json
{
  "name": "move_to_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286577536,
      "name": "move_to_new_page",
      "external": false,
      "loc": "mm/migrate.c:927",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286577536,
      "name": "move_to_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 924
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
int move_to_new_page(struct page * newpage, struct page * page, enum migrate_mode mode)
```

```json
{
  "name": "move_to_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272954560,
      "name": "move_to_new_page",
      "external": false,
      "loc": "mm/migrate.c:927",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272954560,
      "name": "move_to_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
int move_to_new_page(struct page * newpage, struct page * page, enum migrate_mode mode)
```

```json
{
  "name": "move_to_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581630720,
      "name": "move_to_new_page",
      "external": false,
      "loc": "mm/migrate.c:927",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581630720,
      "name": "move_to_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
int move_to_new_page(struct page * newpage, struct page * page, enum migrate_mode mode)
```

```json
{
  "name": "move_to_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581571776,
      "name": "move_to_new_page",
      "external": false,
      "loc": "mm/migrate.c:927",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571776,
      "name": "move_to_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
int move_to_new_page(struct page * newpage, struct page * page, enum migrate_mode mode)
```

```json
{
  "name": "move_to_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581622032,
      "name": "move_to_new_page",
      "external": false,
      "loc": "mm/migrate.c:927",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581622032,
      "name": "move_to_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
int move_to_new_page(struct page * newpage, struct page * page, enum migrate_mode mode)
```

```json
{
  "name": "move_to_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581688416,
      "name": "move_to_new_page",
      "external": false,
      "loc": "mm/migrate.c:927",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581688416,
      "name": "move_to_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 590
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int move_to_new_page(struct page * newpage, struct page * page, enum migrate_mode mode)
```
</details>
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
