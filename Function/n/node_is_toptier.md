# Function: <code>node_is_toptier</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "node_is_toptier",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582335137,
      "name": "node_is_toptier",
      "external": false,
      "loc": "include/linux/node.h:188",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582736560,
      "name": "node_is_toptier",
      "external": false,
      "loc": "include/linux/node.h:188",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582768157,
      "name": "node_is_toptier",
      "external": false,
      "loc": "include/linux/node.h:188",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool node_is_toptier(int node)
```

```json
{
  "name": "node_is_toptier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583266704,
      "name": "node_is_toptier",
      "external": true,
      "loc": "mm/memory-tiers.c:242",
      "file": "mm/memory-tiers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "mm/memory.c:do_numa_page",
        "mm/mprotect.c:change_pte_range",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:folio_migrate_flags",
        "mm/migrate.c:folio_migrate_flags",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583266704,
      "name": "node_is_toptier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
bool node_is_toptier(int node)
```

```json
{
  "name": "node_is_toptier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583487056,
      "name": "node_is_toptier",
      "external": true,
      "loc": "mm/memory-tiers.c:242",
      "file": "mm/memory-tiers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "mm/memory.c:do_numa_page",
        "mm/mprotect.c:change_pte_range",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:folio_migrate_flags",
        "mm/migrate.c:folio_migrate_flags",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583487056,
      "name": "node_is_toptier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
bool node_is_toptier(int node)
```

```json
{
  "name": "node_is_toptier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583679936,
      "name": "node_is_toptier",
      "external": true,
      "loc": "mm/memory-tiers.c:250",
      "file": "mm/memory-tiers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "mm/memory.c:do_numa_page",
        "mm/mprotect.c:change_pte_range",
        "mm/migrate.c:migrate_misplaced_folio",
        "mm/migrate.c:migrate_misplaced_folio",
        "mm/migrate.c:folio_migrate_flags",
        "mm/migrate.c:folio_migrate_flags",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583679936,
      "name": "node_is_toptier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
bool node_is_toptier(int node)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
