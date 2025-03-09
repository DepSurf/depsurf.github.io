# Function: <code>lru_cache_disable</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void lru_cache_disable()
```

```json
{
  "name": "lru_cache_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581399536,
      "name": "lru_cache_disable",
      "external": true,
      "loc": "mm/swap.c:869",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/memory_hotplug.c:offline_pages",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581399536,
      "name": "lru_cache_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void lru_cache_disable()
```

```json
{
  "name": "lru_cache_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581650128,
      "name": "lru_cache_disable",
      "external": true,
      "loc": "mm/swap.c:860",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/memory_hotplug.c:offline_pages",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581650128,
      "name": "lru_cache_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void lru_cache_disable()
```

```json
{
  "name": "lru_cache_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582019008,
      "name": "lru_cache_disable",
      "external": true,
      "loc": "mm/swap.c:868",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_contig_migrate_range",
        "mm/memory_hotplug.c:offline_pages",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582019008,
      "name": "lru_cache_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void lru_cache_disable()
```

```json
{
  "name": "lru_cache_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582454192,
      "name": "lru_cache_disable",
      "external": true,
      "loc": "mm/swap.c:958",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_contig_migrate_range",
        "mm/memory_hotplug.c:offline_pages",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582454192,
      "name": "lru_cache_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void lru_cache_disable()
```

```json
{
  "name": "lru_cache_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582659392,
      "name": "lru_cache_disable",
      "external": true,
      "loc": "mm/swap.c:924",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_contig_migrate_range",
        "mm/memory_hotplug.c:offline_pages",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582659392,
      "name": "lru_cache_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void lru_cache_disable()
```

```json
{
  "name": "lru_cache_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582830512,
      "name": "lru_cache_disable",
      "external": true,
      "loc": "mm/swap.c:924",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_contig_migrate_range",
        "mm/memory_hotplug.c:offline_pages",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582830512,
      "name": "lru_cache_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void lru_cache_disable()
```
</details>
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
