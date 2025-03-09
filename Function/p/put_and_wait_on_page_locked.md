# Function: <code>put_and_wait_on_page_locked</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void put_and_wait_on_page_locked(struct page * page)
```

```json
{
  "name": "put_and_wait_on_page_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580947472,
      "name": "put_and_wait_on_page_locked",
      "external": true,
      "loc": "mm/filemap.c:1188",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580947472,
      "name": "put_and_wait_on_page_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 617
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
void put_and_wait_on_page_locked(struct page * page)
```

```json
{
  "name": "put_and_wait_on_page_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581044736,
      "name": "put_and_wait_on_page_locked",
      "external": true,
      "loc": "mm/filemap.c:1236",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581044736,
      "name": "put_and_wait_on_page_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
void put_and_wait_on_page_locked(struct page * page)
```

```json
{
  "name": "put_and_wait_on_page_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581100272,
      "name": "put_and_wait_on_page_locked",
      "external": true,
      "loc": "mm/filemap.c:1245",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581100272,
      "name": "put_and_wait_on_page_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
void put_and_wait_on_page_locked(struct page * page)
```

```json
{
  "name": "put_and_wait_on_page_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581276288,
      "name": "put_and_wait_on_page_locked",
      "external": true,
      "loc": "mm/filemap.c:1220",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581276288,
      "name": "put_and_wait_on_page_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void put_and_wait_on_page_locked(struct page * page)
```

```json
{
  "name": "put_and_wait_on_page_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581323168,
      "name": "put_and_wait_on_page_locked",
      "external": true,
      "loc": "mm/filemap.c:1397",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323168,
      "name": "put_and_wait_on_page_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int put_and_wait_on_page_locked(struct page * page, int state)
```

```json
{
  "name": "put_and_wait_on_page_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581343409,
      "name": "put_and_wait_on_page_locked",
      "external": true,
      "loc": "mm/filemap.c:1386",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_update_page"
      ],
      "caller_func": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581342720,
      "name": "put_and_wait_on_page_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int put_and_wait_on_page_locked(struct page * page, int state)
```

```json
{
  "name": "put_and_wait_on_page_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581590857,
      "name": "put_and_wait_on_page_locked",
      "external": true,
      "loc": "mm/filemap.c:1441",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_update_page"
      ],
      "caller_func": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581589984,
      "name": "put_and_wait_on_page_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void put_and_wait_on_page_locked(struct page * page)
```

```json
{
  "name": "put_and_wait_on_page_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492465248,
      "name": "put_and_wait_on_page_locked",
      "external": true,
      "loc": "mm/filemap.c:1245",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__migration_entry_wait",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492465248,
      "name": "put_and_wait_on_page_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void put_and_wait_on_page_locked(struct page * page)
```

```json
{
  "name": "put_and_wait_on_page_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226341096,
      "name": "put_and_wait_on_page_locked",
      "external": true,
      "loc": "mm/filemap.c:1245",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__migration_entry_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226341096,
      "name": "put_and_wait_on_page_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
void put_and_wait_on_page_locked(struct page * page)
```

```json
{
  "name": "put_and_wait_on_page_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285746304,
      "name": "put_and_wait_on_page_locked",
      "external": true,
      "loc": "mm/filemap.c:1245",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285746304,
      "name": "put_and_wait_on_page_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 944
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
void put_and_wait_on_page_locked(struct page * page)
```

```json
{
  "name": "put_and_wait_on_page_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272535950,
      "name": "put_and_wait_on_page_locked",
      "external": true,
      "loc": "mm/filemap.c:1245",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__migration_entry_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272535950,
      "name": "put_and_wait_on_page_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
void put_and_wait_on_page_locked(struct page * page)
```

```json
{
  "name": "put_and_wait_on_page_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581069120,
      "name": "put_and_wait_on_page_locked",
      "external": true,
      "loc": "mm/filemap.c:1245",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069120,
      "name": "put_and_wait_on_page_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
void put_and_wait_on_page_locked(struct page * page)
```

```json
{
  "name": "put_and_wait_on_page_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581016320,
      "name": "put_and_wait_on_page_locked",
      "external": true,
      "loc": "mm/filemap.c:1245",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581016320,
      "name": "put_and_wait_on_page_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
void put_and_wait_on_page_locked(struct page * page)
```

```json
{
  "name": "put_and_wait_on_page_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581060320,
      "name": "put_and_wait_on_page_locked",
      "external": true,
      "loc": "mm/filemap.c:1245",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581060320,
      "name": "put_and_wait_on_page_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
void put_and_wait_on_page_locked(struct page * page)
```

```json
{
  "name": "put_and_wait_on_page_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581121904,
      "name": "put_and_wait_on_page_locked",
      "external": true,
      "loc": "mm/filemap.c:1245",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581121904,
      "name": "put_and_wait_on_page_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 591
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
void put_and_wait_on_page_locked(struct page * page)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int state</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int put_and_wait_on_page_locked(struct page * page, int state)
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
