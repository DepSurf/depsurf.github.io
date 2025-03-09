# Function: <code>page_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580527121,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:958",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__set_page_dirty_nobuffers",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580796431,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:958",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__basepage_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580882580,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:958",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_huge_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581214862,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:958",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__set_page_dirty"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580605827,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1055",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580919919,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1055",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__basepage_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581014631,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1055",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581039236,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1055",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379506,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1055",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__set_page_dirty"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580672935,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1046",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580944753,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1046",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580988063,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1046",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__basepage_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581088795,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1046",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581114420,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1046",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581457623,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1046",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__set_page_dirty"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580710806,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1088",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580988874,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1088",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581034493,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1088",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__basepage_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581136215,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1088",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581162371,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1088",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581513911,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1088",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__set_page_dirty"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580796375,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1139",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581092524,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1139",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581144237,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1139",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__basepage_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581257847,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1139",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581288750,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1139",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581656167,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1139",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__set_page_dirty"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580936459,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1218",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581233375,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1218",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581287341,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1218",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__basepage_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581404018,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1218",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581435665,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1218",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581819191,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1218",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__set_page_dirty"
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
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581003555,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1286",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581316407,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1286",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581370253,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1286",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__basepage_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581487377,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1286",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581519253,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1286",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581906183,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1286",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__set_page_dirty"
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
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581067958,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1354",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581427361,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1354",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581481071,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1354",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__basepage_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581595505,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1354",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581629059,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1354",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582043143,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1354",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__set_page_dirty"
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
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581123926,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581491601,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581545487,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__basepage_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581666065,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699940,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582120919,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__set_page_dirty"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int page_index(struct page * page)
```

```json
{
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581310566,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1542",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581696930,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1542",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage"
      ],
      "caller_func": [
        "mm/page_io.c:__swap_writepage"
      ]
    },
    {
      "addr": 18446744071581755693,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1542",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__basepage_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581887569,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1542",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581915997,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1542",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582359312,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1542",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__set_page_dirty"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581694752,
      "name": "page_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int page_index(struct page * page)
```

```json
{
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581357592,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1583",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581743727,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1583",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage"
      ],
      "caller_func": [
        "mm/page_io.c:__swap_writepage"
      ]
    },
    {
      "addr": 18446744071581803629,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1583",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__basepage_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581933473,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1583",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581962762,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1583",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582416960,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1583",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__set_page_dirty"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581741536,
      "name": "page_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int page_index(struct page * page)
```

```json
{
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581376790,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1653",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581771833,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1653",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage"
      ],
      "caller_func": [
        "mm/page_io.c:__swap_writepage"
      ]
    },
    {
      "addr": 18446744071581830941,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1653",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_basepage_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581958897,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1653",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581988876,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1653",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582444288,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1653",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__set_page_dirty"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581769792,
      "name": "page_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int page_index(struct page * page)
```

```json
{
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581625769,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1664",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:__set_page_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582054457,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1664",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage"
      ],
      "caller_func": [
        "mm/page_io.c:__swap_writepage"
      ]
    },
    {
      "addr": 18446744071582120223,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1664",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_basepage_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582263649,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1664",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582290979,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1664",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582052448,
      "name": "page_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582490788,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1776",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage_fs",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:sio_write_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582565274,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1776",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_basepage_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582731903,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1776",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583005588,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1909",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage_fs",
        "mm/page_io.c:swap_writepage_fs",
        "mm/page_io.c:sio_write_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583084140,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1909",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_basepage_index"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583214932,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:2180",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage_fs",
        "mm/page_io.c:swap_writepage_fs",
        "mm/page_io.c:sio_write_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583294742,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:2180",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_basepage_index"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583450360,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:2234",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_read_folio_fs",
        "mm/page_io.c:swap_writepage_fs",
        "mm/page_io.c:sio_write_complete"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492498892,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492910544,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492979256,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__basepage_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493109072,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493143640,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493662796,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__set_page_dirty"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226365632,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 3226702252,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 3226805704,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 3227194140,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__set_page_dirty"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285782360,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286315600,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286399380,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__basepage_index"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286583596,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286631328,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287259044,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__set_page_dirty"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272556290,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272834102,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272885048,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__basepage_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272955550,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273289366,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__set_page_dirty"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581092774,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581460449,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581514223,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__basepage_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581634801,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581668676,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582089655,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__set_page_dirty"
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
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581039958,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581402641,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581456415,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__basepage_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581575777,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581608212,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582027175,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__set_page_dirty"
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
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581083974,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581451649,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581505535,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__basepage_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626113,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581659988,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582080135,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__set_page_dirty"
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
  "name": "page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581145894,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581516113,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581570527,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__basepage_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581692465,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581726372,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582152839,
      "name": "page_index",
      "external": false,
      "loc": "include/linux/mm.h:1368",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__set_page_dirty"
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
long unsigned int page_index(struct page * page)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
long unsigned int page_index(struct page * page)
```
</details>
</li>
</ul>
