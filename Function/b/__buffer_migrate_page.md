# Function: <code>__buffer_migrate_page</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __buffer_migrate_page(struct address_space * mapping, struct page * newpage, struct page * page, enum migrate_mode mode, bool check_refs)
```

```json
{
  "name": "__buffer_migrate_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581477152,
      "name": "__buffer_migrate_page",
      "external": false,
      "loc": "mm/migrate.c:739",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page_norefs",
        "mm/migrate.c:buffer_migrate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581477152,
      "name": "__buffer_migrate_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 567
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __buffer_migrate_page(struct address_space * mapping, struct page * newpage, struct page * page, enum migrate_mode mode, bool check_refs)
```

```json
{
  "name": "__buffer_migrate_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581592240,
      "name": "__buffer_migrate_page",
      "external": false,
      "loc": "mm/migrate.c:735",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page_norefs",
        "mm/migrate.c:buffer_migrate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581592240,
      "name": "__buffer_migrate_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
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
int __buffer_migrate_page(struct address_space * mapping, struct page * newpage, struct page * page, enum migrate_mode mode, bool check_refs)
```

```json
{
  "name": "__buffer_migrate_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581655888,
      "name": "__buffer_migrate_page",
      "external": false,
      "loc": "mm/migrate.c:736",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page_norefs",
        "mm/migrate.c:buffer_migrate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581655888,
      "name": "__buffer_migrate_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_migrate_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581887925,
      "name": "__buffer_migrate_page",
      "external": false,
      "loc": "mm/migrate.c:756",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:buffer_migrate_page_norefs",
        "mm/migrate.c:buffer_migrate_page"
      ],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page_norefs",
        "mm/migrate.c:buffer_migrate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581879616,
      "name": "__buffer_migrate_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_migrate_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581933829,
      "name": "__buffer_migrate_page",
      "external": false,
      "loc": "mm/migrate.c:754",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:buffer_migrate_page_norefs",
        "mm/migrate.c:buffer_migrate_page"
      ],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page_norefs",
        "mm/migrate.c:buffer_migrate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581923104,
      "name": "__buffer_migrate_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_migrate_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581959253,
      "name": "__buffer_migrate_page",
      "external": false,
      "loc": "mm/migrate.c:734",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:buffer_migrate_page_norefs",
        "mm/migrate.c:buffer_migrate_page"
      ],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page_norefs",
        "mm/migrate.c:buffer_migrate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581950992,
      "name": "__buffer_migrate_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 646
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_migrate_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582264005,
      "name": "__buffer_migrate_page",
      "external": false,
      "loc": "mm/migrate.c:697",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:buffer_migrate_page_norefs",
        "mm/migrate.c:buffer_migrate_page"
      ],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page_norefs",
        "mm/migrate.c:buffer_migrate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582255696,
      "name": "__buffer_migrate_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
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
int __buffer_migrate_page(struct address_space * mapping, struct page * newpage, struct page * page, enum migrate_mode mode, bool check_refs)
```

```json
{
  "name": "__buffer_migrate_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582722128,
      "name": "__buffer_migrate_page",
      "external": false,
      "loc": "mm/migrate.c:675",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page_norefs",
        "mm/migrate.c:buffer_migrate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582722128,
      "name": "__buffer_migrate_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 921
    }
  ]
}
```
</details>
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
int __buffer_migrate_page(struct address_space * mapping, struct page * newpage, struct page * page, enum migrate_mode mode, bool check_refs)
```

```json
{
  "name": "__buffer_migrate_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493105512,
      "name": "__buffer_migrate_page",
      "external": false,
      "loc": "mm/migrate.c:736",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page_norefs",
        "mm/migrate.c:buffer_migrate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493105512,
      "name": "__buffer_migrate_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 944
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
int __buffer_migrate_page(struct address_space * mapping, struct page * newpage, struct page * page, enum migrate_mode mode, bool check_refs)
```

```json
{
  "name": "__buffer_migrate_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226802312,
      "name": "__buffer_migrate_page",
      "external": false,
      "loc": "mm/migrate.c:736",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page_norefs",
        "mm/migrate.c:buffer_migrate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226802312,
      "name": "__buffer_migrate_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 956
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __buffer_migrate_page(struct address_space * mapping, struct page * newpage, struct page * page, enum migrate_mode mode, bool check_refs)
```

```json
{
  "name": "__buffer_migrate_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286570624,
      "name": "__buffer_migrate_page",
      "external": false,
      "loc": "mm/migrate.c:736",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page_norefs",
        "mm/migrate.c:buffer_migrate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286570624,
      "name": "__buffer_migrate_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1176
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
int __buffer_migrate_page(struct address_space * mapping, struct page * newpage, struct page * page, enum migrate_mode mode, bool check_refs)
```

```json
{
  "name": "__buffer_migrate_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272952920,
      "name": "__buffer_migrate_page",
      "external": false,
      "loc": "mm/migrate.c:736",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page_norefs",
        "mm/migrate.c:buffer_migrate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272952920,
      "name": "__buffer_migrate_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 712
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
int __buffer_migrate_page(struct address_space * mapping, struct page * newpage, struct page * page, enum migrate_mode mode, bool check_refs)
```

```json
{
  "name": "__buffer_migrate_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581624624,
      "name": "__buffer_migrate_page",
      "external": false,
      "loc": "mm/migrate.c:736",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page_norefs",
        "mm/migrate.c:buffer_migrate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581624624,
      "name": "__buffer_migrate_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
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
int __buffer_migrate_page(struct address_space * mapping, struct page * newpage, struct page * page, enum migrate_mode mode, bool check_refs)
```

```json
{
  "name": "__buffer_migrate_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581565904,
      "name": "__buffer_migrate_page",
      "external": false,
      "loc": "mm/migrate.c:736",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page_norefs",
        "mm/migrate.c:buffer_migrate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581565904,
      "name": "__buffer_migrate_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
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
int __buffer_migrate_page(struct address_space * mapping, struct page * newpage, struct page * page, enum migrate_mode mode, bool check_refs)
```

```json
{
  "name": "__buffer_migrate_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581615936,
      "name": "__buffer_migrate_page",
      "external": false,
      "loc": "mm/migrate.c:736",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page_norefs",
        "mm/migrate.c:buffer_migrate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581615936,
      "name": "__buffer_migrate_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
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
int __buffer_migrate_page(struct address_space * mapping, struct page * newpage, struct page * page, enum migrate_mode mode, bool check_refs)
```

```json
{
  "name": "__buffer_migrate_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581684384,
      "name": "__buffer_migrate_page",
      "external": false,
      "loc": "mm/migrate.c:736",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page_norefs",
        "mm/migrate.c:buffer_migrate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581684384,
      "name": "__buffer_migrate_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
int __buffer_migrate_page(struct address_space * mapping, struct page * newpage, struct page * page, enum migrate_mode mode, bool check_refs)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int __buffer_migrate_page(struct address_space * mapping, struct page * newpage, struct page * page, enum migrate_mode mode, bool check_refs)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int __buffer_migrate_page(struct address_space * mapping, struct page * newpage, struct page * page, enum migrate_mode mode, bool check_refs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int __buffer_migrate_page(struct address_space * mapping, struct page * newpage, struct page * page, enum migrate_mode mode, bool check_refs)
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
