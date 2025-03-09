# Function: <code>migration_entry_wait_on_locked</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void migration_entry_wait_on_locked(swp_entry_t entry, pte_t * ptep, spinlock_t * ptl)
```

```json
{
  "name": "migration_entry_wait_on_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581948288,
      "name": "migration_entry_wait_on_locked",
      "external": true,
      "loc": "mm/filemap.c:1401",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait_huge",
        "mm/migrate.c:__migration_entry_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581948288,
      "name": "migration_entry_wait_on_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 750
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
void migration_entry_wait_on_locked(swp_entry_t entry, pte_t * ptep, spinlock_t * ptl)
```

```json
{
  "name": "migration_entry_wait_on_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582382368,
      "name": "migration_entry_wait_on_locked",
      "external": true,
      "loc": "mm/filemap.c:1373",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait_huge",
        "mm/migrate.c:__migration_entry_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582382368,
      "name": "migration_entry_wait_on_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
void migration_entry_wait_on_locked(swp_entry_t entry, spinlock_t * ptl)
```

```json
{
  "name": "migration_entry_wait_on_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582583024,
      "name": "migration_entry_wait_on_locked",
      "external": true,
      "loc": "mm/filemap.c:1380",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:migration_entry_wait_huge",
        "mm/migrate.c:migration_entry_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582583024,
      "name": "migration_entry_wait_on_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 717
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
void migration_entry_wait_on_locked(swp_entry_t entry, spinlock_t * ptl)
```

```json
{
  "name": "migration_entry_wait_on_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582754160,
      "name": "migration_entry_wait_on_locked",
      "external": true,
      "loc": "mm/filemap.c:1350",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:migration_entry_wait_huge",
        "mm/migrate.c:migration_entry_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582754160,
      "name": "migration_entry_wait_on_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 707
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void migration_entry_wait_on_locked(swp_entry_t entry, pte_t * ptep, spinlock_t * ptl)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>pte_t * ptep</code>
</li>
<li>
<b>Param reordered. </b>
<code>entry, ptep, ptl</code> ➡️ <code>entry, ptl</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
