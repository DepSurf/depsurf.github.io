# Function: <code>migrate_page_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void migrate_page_copy(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580883632,
      "name": "migrate_page_copy",
      "external": true,
      "loc": "mm/migrate.c:524",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "fs/aio.c:aio_migratepage",
        "fs/hugetlbfs/inode.c:hugetlbfs_migrate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580883632,
      "name": "migrate_page_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1316
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
void migrate_page_copy(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581009024,
      "name": "migrate_page_copy",
      "external": true,
      "loc": "mm/migrate.c:619",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:buffer_migrate_page",
        "fs/aio.c:aio_migratepage",
        "fs/hugetlbfs/inode.c:hugetlbfs_migrate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581009024,
      "name": "migrate_page_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1478
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
void migrate_page_copy(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581083056,
      "name": "migrate_page_copy",
      "external": true,
      "loc": "mm/migrate.c:621",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:buffer_migrate_page",
        "fs/aio.c:aio_migratepage",
        "fs/hugetlbfs/inode.c:hugetlbfs_migrate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581083056,
      "name": "migrate_page_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1519
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
void migrate_page_copy(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581130960,
      "name": "migrate_page_copy",
      "external": true,
      "loc": "mm/migrate.c:607",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "fs/aio.c:aio_migratepage",
        "fs/hugetlbfs/inode.c:hugetlbfs_migrate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581130960,
      "name": "migrate_page_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1238
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
void migrate_page_copy(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581246688,
      "name": "migrate_page_copy",
      "external": true,
      "loc": "mm/migrate.c:717",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "fs/aio.c:aio_migratepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581246688,
      "name": "migrate_page_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 868
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
void migrate_page_copy(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581390896,
      "name": "migrate_page_copy",
      "external": true,
      "loc": "mm/migrate.c:729",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:buffer_migrate_page",
        "fs/aio.c:aio_migratepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581390896,
      "name": "migrate_page_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
void migrate_page_copy(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581474352,
      "name": "migrate_page_copy",
      "external": true,
      "loc": "mm/migrate.c:658",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "fs/aio.c:aio_migratepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581474352,
      "name": "migrate_page_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 842
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
void migrate_page_copy(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581589328,
      "name": "migrate_page_copy",
      "external": true,
      "loc": "mm/migrate.c:654",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "fs/aio.c:aio_migratepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581589328,
      "name": "migrate_page_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 938
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
void migrate_page_copy(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581652992,
      "name": "migrate_page_copy",
      "external": true,
      "loc": "mm/migrate.c:655",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "fs/aio.c:aio_migratepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581652992,
      "name": "migrate_page_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 938
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
void migrate_page_copy(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581871712,
      "name": "migrate_page_copy",
      "external": true,
      "loc": "mm/migrate.c:675",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_page",
        "fs/aio.c:aio_migratepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581871712,
      "name": "migrate_page_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void migrate_page_copy(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581917856,
      "name": "migrate_page_copy",
      "external": true,
      "loc": "mm/migrate.c:673",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_page",
        "fs/aio.c:aio_migratepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581917856,
      "name": "migrate_page_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void migrate_page_copy(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581942336,
      "name": "migrate_page_copy",
      "external": true,
      "loc": "mm/migrate.c:653",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_page",
        "fs/aio.c:aio_migratepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581942336,
      "name": "migrate_page_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
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
void migrate_page_copy(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582246704,
      "name": "migrate_page_copy",
      "external": true,
      "loc": "mm/migrate.c:616",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_page",
        "fs/aio.c:aio_migratepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582246704,
      "name": "migrate_page_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void migrate_page_copy(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581995232,
      "name": "migrate_page_copy",
      "external": true,
      "loc": "mm/folio-compat.c:69",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_page",
        "fs/aio.c:aio_migratepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995232,
      "name": "migrate_page_copy",
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
void migrate_page_copy(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493103056,
      "name": "migrate_page_copy",
      "external": true,
      "loc": "mm/migrate.c:655",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:__buffer_migrate_page",
        "fs/aio.c:aio_migratepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493103056,
      "name": "migrate_page_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void migrate_page_copy(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226803112,
      "name": "migrate_page_copy",
      "external": true,
      "loc": "mm/migrate.c:655",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__buffer_migrate_page"
      ],
      "caller_func": [
        "fs/aio.c:aio_migratepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226801576,
      "name": "migrate_page_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void migrate_page_copy(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286563104,
      "name": "migrate_page_copy",
      "external": true,
      "loc": "mm/migrate.c:655",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "fs/aio.c:aio_migratepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286563104,
      "name": "migrate_page_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1208
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
void migrate_page_copy(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272950872,
      "name": "migrate_page_copy",
      "external": true,
      "loc": "mm/migrate.c:655",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_page",
        "fs/aio.c:aio_migratepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272950872,
      "name": "migrate_page_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 798
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
void migrate_page_copy(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581621728,
      "name": "migrate_page_copy",
      "external": true,
      "loc": "mm/migrate.c:655",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "fs/aio.c:aio_migratepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581621728,
      "name": "migrate_page_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 938
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
void migrate_page_copy(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581563024,
      "name": "migrate_page_copy",
      "external": true,
      "loc": "mm/migrate.c:655",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "fs/aio.c:aio_migratepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581563024,
      "name": "migrate_page_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 938
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
void migrate_page_copy(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581613040,
      "name": "migrate_page_copy",
      "external": true,
      "loc": "mm/migrate.c:655",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "fs/aio.c:aio_migratepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581613040,
      "name": "migrate_page_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 938
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
void migrate_page_copy(struct page * newpage, struct page * page)
```

```json
{
  "name": "migrate_page_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581680640,
      "name": "migrate_page_copy",
      "external": true,
      "loc": "mm/migrate.c:655",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "fs/aio.c:aio_migratepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581680640,
      "name": "migrate_page_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1149
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void migrate_page_copy(struct page * newpage, struct page * page)
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
