# Function: <code>migrate_page_states</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void migrate_page_states(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581241984,
      "name": "migrate_page_states",
      "external": true,
      "loc": "mm/migrate.c:658",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_page_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581241984,
      "name": "migrate_page_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
void migrate_page_states(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581388032,
      "name": "migrate_page_states",
      "external": true,
      "loc": "mm/migrate.c:670",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page",
        "mm/migrate.c:migrate_page_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581388032,
      "name": "migrate_page_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
void migrate_page_states(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581472000,
      "name": "migrate_page_states",
      "external": true,
      "loc": "mm/migrate.c:597",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_page_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581472000,
      "name": "migrate_page_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 562
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
void migrate_page_states(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581587344,
      "name": "migrate_page_states",
      "external": true,
      "loc": "mm/migrate.c:593",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_page_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581587344,
      "name": "migrate_page_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 558
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
void migrate_page_states(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581651088,
      "name": "migrate_page_states",
      "external": true,
      "loc": "mm/migrate.c:594",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_page_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581651088,
      "name": "migrate_page_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
void migrate_page_states(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581871056,
      "name": "migrate_page_states",
      "external": true,
      "loc": "mm/migrate.c:606",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_page",
        "mm/migrate.c:migrate_page_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581871056,
      "name": "migrate_page_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 642
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
void migrate_page_states(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581917184,
      "name": "migrate_page_states",
      "external": true,
      "loc": "mm/migrate.c:603",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_page",
        "mm/migrate.c:migrate_page_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581917184,
      "name": "migrate_page_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 660
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
void migrate_page_states(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581940464,
      "name": "migrate_page_states",
      "external": true,
      "loc": "mm/migrate.c:583",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_page",
        "mm/migrate.c:migrate_page_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581940464,
      "name": "migrate_page_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 660
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
void migrate_page_states(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582246032,
      "name": "migrate_page_states",
      "external": true,
      "loc": "mm/migrate.c:543",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_page",
        "mm/migrate.c:migrate_page_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582246032,
      "name": "migrate_page_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 672
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
void migrate_page_states(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581995392,
      "name": "migrate_page_states",
      "external": true,
      "loc": "mm/folio-compat.c:63",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995392,
      "name": "migrate_page_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void migrate_page_states(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493101856,
      "name": "migrate_page_states",
      "external": true,
      "loc": "mm/migrate.c:594",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493101856,
      "name": "migrate_page_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1200
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
void migrate_page_states(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226800828,
      "name": "migrate_page_states",
      "external": true,
      "loc": "mm/migrate.c:594",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:__buffer_migrate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226800828,
      "name": "migrate_page_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
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
void migrate_page_states(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286560544,
      "name": "migrate_page_states",
      "external": true,
      "loc": "mm/migrate.c:594",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286560544,
      "name": "migrate_page_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1304
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
void migrate_page_states(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272950182,
      "name": "migrate_page_states",
      "external": true,
      "loc": "mm/migrate.c:594",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:migrate_page_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272950182,
      "name": "migrate_page_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 690
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
void migrate_page_states(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581619824,
      "name": "migrate_page_states",
      "external": true,
      "loc": "mm/migrate.c:594",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_page_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581619824,
      "name": "migrate_page_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
void migrate_page_states(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581561152,
      "name": "migrate_page_states",
      "external": true,
      "loc": "mm/migrate.c:594",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_page_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581561152,
      "name": "migrate_page_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
void migrate_page_states(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581611136,
      "name": "migrate_page_states",
      "external": true,
      "loc": "mm/migrate.c:594",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_page_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581611136,
      "name": "migrate_page_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
void migrate_page_states(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581678736,
      "name": "migrate_page_states",
      "external": true,
      "loc": "mm/migrate.c:594",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_page_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581678736,
      "name": "migrate_page_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void migrate_page_states(struct page * newpage, struct page * page)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void migrate_page_states(struct page * newpage, struct page * page)
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
