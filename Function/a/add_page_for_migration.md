# Function: <code>add_page_for_migration</code>

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
  "name": "add_page_for_migration",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581408132,
      "name": "add_page_for_migration",
      "external": false,
      "loc": "mm/migrate.c:1494",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages"
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
  "name": "add_page_for_migration",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581491620,
      "name": "add_page_for_migration",
      "external": false,
      "loc": "mm/migrate.c:1527",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages"
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
  "name": "add_page_for_migration",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581599366,
      "name": "add_page_for_migration",
      "external": false,
      "loc": "mm/migrate.c:1522",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
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
  "name": "add_page_for_migration",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581669939,
      "name": "add_page_for_migration",
      "external": false,
      "loc": "mm/migrate.c:1525",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
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
int add_page_for_migration(struct mm_struct * mm, long unsigned int addr, int node, struct list_head * pagelist, bool migrate_all)
```

```json
{
  "name": "add_page_for_migration",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581872368,
      "name": "add_page_for_migration",
      "external": false,
      "loc": "mm/migrate.c:1539",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581872368,
      "name": "add_page_for_migration",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
int add_page_for_migration(struct mm_struct * mm, long unsigned int addr, int node, struct list_head * pagelist, bool migrate_all)
```

```json
{
  "name": "add_page_for_migration",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581918512,
      "name": "add_page_for_migration",
      "external": false,
      "loc": "mm/migrate.c:1660",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581918512,
      "name": "add_page_for_migration",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
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
int add_page_for_migration(struct mm_struct * mm, long unsigned int addr, int node, struct list_head * pagelist, bool migrate_all)
```

```json
{
  "name": "add_page_for_migration",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581943504,
      "name": "add_page_for_migration",
      "external": false,
      "loc": "mm/migrate.c:1642",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581943504,
      "name": "add_page_for_migration",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
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
int add_page_for_migration(struct mm_struct * mm, long unsigned int addr, int node, struct list_head * pagelist, bool migrate_all)
```

```json
{
  "name": "add_page_for_migration",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582248560,
      "name": "add_page_for_migration",
      "external": false,
      "loc": "mm/migrate.c:1686",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582248560,
      "name": "add_page_for_migration",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 594
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
int add_page_for_migration(struct mm_struct * mm, long unsigned int addr, int node, struct list_head * pagelist, bool migrate_all)
```

```json
{
  "name": "add_page_for_migration",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582721184,
      "name": "add_page_for_migration",
      "external": false,
      "loc": "mm/migrate.c:1617",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582721184,
      "name": "add_page_for_migration",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 939
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
int add_page_for_migration(struct mm_struct * mm, long unsigned int addr, int node, struct list_head * pagelist, bool migrate_all)
```

```json
{
  "name": "add_page_for_migration",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583247328,
      "name": "add_page_for_migration",
      "external": false,
      "loc": "mm/migrate.c:1724",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583247328,
      "name": "add_page_for_migration",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1044
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
int add_page_for_migration(struct mm_struct * mm, const void * p, int node, struct list_head * pagelist, bool migrate_all)
```

```json
{
  "name": "add_page_for_migration",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583468800,
      "name": "add_page_for_migration",
      "external": false,
      "loc": "mm/migrate.c:2055",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583468800,
      "name": "add_page_for_migration",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1028
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
int add_page_for_migration(struct mm_struct * mm, const void * p, int node, struct list_head * pagelist, bool migrate_all)
```

```json
{
  "name": "add_page_for_migration",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583658832,
      "name": "add_page_for_migration",
      "external": false,
      "loc": "mm/migrate.c:2078",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583658832,
      "name": "add_page_for_migration",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
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
  "name": "add_page_for_migration",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493113724,
      "name": "add_page_for_migration",
      "external": false,
      "loc": "mm/migrate.c:1525",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "add_page_for_migration",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286589876,
      "name": "add_page_for_migration",
      "external": false,
      "loc": "mm/migrate.c:1525",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_page_for_migration",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581638675,
      "name": "add_page_for_migration",
      "external": false,
      "loc": "mm/migrate.c:1525",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
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
  "name": "add_page_for_migration",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581579635,
      "name": "add_page_for_migration",
      "external": false,
      "loc": "mm/migrate.c:1525",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
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
  "name": "add_page_for_migration",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581629987,
      "name": "add_page_for_migration",
      "external": false,
      "loc": "mm/migrate.c:1525",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
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
  "name": "add_page_for_migration",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581696291,
      "name": "add_page_for_migration",
      "external": false,
      "loc": "mm/migrate.c:1525",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
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
int add_page_for_migration(struct mm_struct * mm, long unsigned int addr, int node, struct list_head * pagelist, bool migrate_all)
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const void * p</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int addr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
