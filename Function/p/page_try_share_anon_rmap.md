# Function: <code>page_try_share_anon_rmap</code>

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
  "name": "page_try_share_anon_rmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582377849,
      "name": "page_try_share_anon_rmap",
      "external": false,
      "loc": "include/linux/rmap.h:285",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582648419,
      "name": "page_try_share_anon_rmap",
      "external": false,
      "loc": "include/linux/rmap.h:285",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582743094,
      "name": "page_try_share_anon_rmap",
      "external": false,
      "loc": "include/linux/rmap.h:285",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582784530,
      "name": "page_try_share_anon_rmap",
      "external": false,
      "loc": "include/linux/rmap.h:285",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int page_try_share_anon_rmap(struct page * page)
```

```json
{
  "name": "page_try_share_anon_rmap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582882197,
      "name": "page_try_share_anon_rmap",
      "external": false,
      "loc": "include/linux/rmap.h:285",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": [
        "mm/rmap.c:try_to_migrate_one"
      ]
    },
    {
      "addr": 18446744071583170671,
      "name": "page_try_share_anon_rmap",
      "external": false,
      "loc": "include/linux/rmap.h:285",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583274681,
      "name": "page_try_share_anon_rmap",
      "external": false,
      "loc": "include/linux/rmap.h:285",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583317419,
      "name": "page_try_share_anon_rmap",
      "external": false,
      "loc": "include/linux/rmap.h:285",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:set_pmd_migration_entry"
      ],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582868320,
      "name": "page_try_share_anon_rmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    },
    {
      "addr": 18446744071583284384,
      "name": "page_try_share_anon_rmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_try_share_anon_rmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583096427,
      "name": "page_try_share_anon_rmap",
      "external": false,
      "loc": "include/linux/rmap.h:294",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583386749,
      "name": "page_try_share_anon_rmap",
      "external": false,
      "loc": "include/linux/rmap.h:294",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583496998,
      "name": "page_try_share_anon_rmap",
      "external": false,
      "loc": "include/linux/rmap.h:294",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583535857,
      "name": "page_try_share_anon_rmap",
      "external": false,
      "loc": "include/linux/rmap.h:294",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked"
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
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int page_try_share_anon_rmap(struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int page_try_share_anon_rmap(struct page * page)
```
</details>
</li>
</ul>
