# Function: <code>numamigrate_update_ratelimit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool numamigrate_update_ratelimit(pg_data_t * pgdat, long unsigned int nr_pages)
```

```json
{
  "name": "numamigrate_update_ratelimit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580879488,
      "name": "numamigrate_update_ratelimit",
      "external": false,
      "loc": "mm/migrate.c:1595",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580879488,
      "name": "numamigrate_update_ratelimit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
bool numamigrate_update_ratelimit(pg_data_t * pgdat, long unsigned int nr_pages)
```

```json
{
  "name": "numamigrate_update_ratelimit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581007024,
      "name": "numamigrate_update_ratelimit",
      "external": false,
      "loc": "mm/migrate.c:1777",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581007024,
      "name": "numamigrate_update_ratelimit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
bool numamigrate_update_ratelimit(pg_data_t * pgdat, long unsigned int nr_pages)
```

```json
{
  "name": "numamigrate_update_ratelimit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581081056,
      "name": "numamigrate_update_ratelimit",
      "external": false,
      "loc": "mm/migrate.c:1786",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581081056,
      "name": "numamigrate_update_ratelimit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
bool numamigrate_update_ratelimit(pg_data_t * pgdat, long unsigned int nr_pages)
```

```json
{
  "name": "numamigrate_update_ratelimit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581129248,
      "name": "numamigrate_update_ratelimit",
      "external": false,
      "loc": "mm/migrate.c:1765",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581129248,
      "name": "numamigrate_update_ratelimit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
bool numamigrate_update_ratelimit(pg_data_t * pgdat, long unsigned int nr_pages)
```

```json
{
  "name": "numamigrate_update_ratelimit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581242784,
      "name": "numamigrate_update_ratelimit",
      "external": false,
      "loc": "mm/migrate.c:1863",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581242784,
      "name": "numamigrate_update_ratelimit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool numamigrate_update_ratelimit(pg_data_t * pgdat, long unsigned int nr_pages)
```

```json
{
  "name": "numamigrate_update_ratelimit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581390624,
      "name": "numamigrate_update_ratelimit",
      "external": false,
      "loc": "mm/migrate.c:1868",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581390624,
      "name": "numamigrate_update_ratelimit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
bool numamigrate_update_ratelimit(pg_data_t * pgdat, long unsigned int nr_pages)
```
</details>
</li>
</ul>
