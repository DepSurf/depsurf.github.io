# Function: <code>mas_is_err</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mas_is_err(struct ma_state * mas)
```

```json
{
  "name": "mas_is_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595855135,
      "name": "mas_is_err",
      "external": true,
      "loc": "lib/maple_tree.c:248",
      "file": "lib/maple_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/maple_tree.c:mtree_alloc_rrange",
        "lib/maple_tree.c:mtree_alloc_range",
        "lib/maple_tree.c:mtree_alloc_range",
        "lib/maple_tree.c:mtree_alloc_range",
        "lib/maple_tree.c:mtree_alloc_range",
        "lib/maple_tree.c:mtree_insert_range",
        "lib/maple_tree.c:mtree_store_range",
        "lib/maple_tree.c:mas_expected_entries",
        "lib/maple_tree.c:mas_preallocate",
        "lib/maple_tree.c:mas_store_prealloc",
        "lib/maple_tree.c:mas_store_gfp",
        "lib/maple_tree.c:mas_empty_area_rev",
        "lib/maple_tree.c:mas_empty_area",
        "lib/maple_tree.c:mas_empty_area",
        "lib/maple_tree.c:mas_rev_awalk",
        "lib/maple_tree.c:mas_wr_modify",
        "lib/maple_tree.c:mas_wr_bnode",
        "lib/maple_tree.c:mas_wr_node_store",
        "lib/maple_tree.c:mas_destroy_rebalance"
      ],
      "caller_func": [
        "kernel/fork.c:dup_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595850176,
      "name": "mas_is_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mas_is_err(struct ma_state * mas)
```

```json
{
  "name": "mas_is_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596372477,
      "name": "mas_is_err",
      "external": true,
      "loc": "lib/maple_tree.c:253",
      "file": "lib/maple_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/maple_tree.c:mtree_alloc_rrange",
        "lib/maple_tree.c:mtree_alloc_range",
        "lib/maple_tree.c:mtree_insert_range",
        "lib/maple_tree.c:mtree_store_range",
        "lib/maple_tree.c:mas_expected_entries",
        "lib/maple_tree.c:mas_preallocate",
        "lib/maple_tree.c:mas_store_prealloc",
        "lib/maple_tree.c:mas_store_gfp",
        "lib/maple_tree.c:mas_empty_area_rev",
        "lib/maple_tree.c:mas_empty_area",
        "lib/maple_tree.c:mas_empty_area",
        "lib/maple_tree.c:mas_empty_area",
        "lib/maple_tree.c:mas_empty_area",
        "lib/maple_tree.c:mas_rev_awalk",
        "lib/maple_tree.c:mas_wr_modify",
        "lib/maple_tree.c:mas_wr_bnode",
        "lib/maple_tree.c:mas_wr_node_store",
        "lib/maple_tree.c:mas_destroy_rebalance"
      ],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_vmi_align_munmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596370752,
      "name": "mas_is_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mas_is_err",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579873990,
      "name": "mas_is_err",
      "external": false,
      "loc": "include/linux/maple_tree.h:539",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583216461,
      "name": "mas_is_err",
      "external": false,
      "loc": "include/linux/maple_tree.h:539",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_vmi_align_munmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597230328,
      "name": "mas_is_err",
      "external": false,
      "loc": "include/linux/maple_tree.h:539",
      "file": "lib/maple_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/maple_tree.c:mtree_dup",
        "lib/maple_tree.c:__mt_dup",
        "lib/maple_tree.c:mtree_alloc_rrange",
        "lib/maple_tree.c:mtree_alloc_range",
        "lib/maple_tree.c:mtree_insert_range",
        "lib/maple_tree.c:mtree_store_range",
        "lib/maple_tree.c:mtree_store_range",
        "lib/maple_tree.c:mtree_store_range",
        "lib/maple_tree.c:mas_erase",
        "lib/maple_tree.c:mas_erase",
        "lib/maple_tree.c:mas_expected_entries",
        "lib/maple_tree.c:mas_preallocate",
        "lib/maple_tree.c:mas_store_prealloc",
        "lib/maple_tree.c:mas_store_gfp",
        "lib/maple_tree.c:mas_empty_area_rev",
        "lib/maple_tree.c:mas_empty_area",
        "lib/maple_tree.c:mas_empty_area",
        "lib/maple_tree.c:mas_rev_awalk",
        "lib/maple_tree.c:mas_wr_bnode",
        "lib/maple_tree.c:mas_wr_node_store",
        "lib/maple_tree.c:mas_destroy_rebalance"
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
bool mas_is_err(struct ma_state * mas)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
bool mas_is_err(struct ma_state * mas)
```
</details>
</li>
</ul>
