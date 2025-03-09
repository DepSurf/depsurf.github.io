# Function: <code>page_to_pgoff</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580722637,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:395",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_address_in_vma",
        "mm/rmap.c:page_mapped_in_vma",
        "mm/rmap.c:rmap_walk",
        "mm/rmap.c:rmap_walk",
        "mm/rmap.c:rmap_walk",
        "mm/rmap.c:rmap_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580952721,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:395",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
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
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580556461,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:370",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:find_get_pages_contig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580632014,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:370",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580763297,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:370",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580838769,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:370",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_mapped_in_vma",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581101912,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:370",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
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
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580621502,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:400",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:find_get_pages_contig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580828918,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:400",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580904829,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:400",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580909329,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:400",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_mapped_in_vma",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581177117,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:400",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
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
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580646698,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:416",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:find_get_pages_contig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580870994,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:416",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580951004,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:416",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580955771,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:416",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581223694,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:416",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580730258,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:429",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:find_get_pages_contig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580962242,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:429",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581052380,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:429",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581056955,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:429",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581354494,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:429",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580866382,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:429",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:find_get_pages_contig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581097064,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:429",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581191212,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:429",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581196502,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:429",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581502747,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:429",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:add_to_kill"
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
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580937646,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:429",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:find_get_pages_contig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581176626,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:429",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581274364,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:429",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581279849,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:429",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581588587,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:429",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:add_to_kill",
        "mm/memory-failure.c:add_to_kill"
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
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581246354,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:413",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581348828,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:413",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581353974,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:413",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699575,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:413",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
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
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581304828,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581408140,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581413478,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581773031,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
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
long unsigned int page_to_pgoff(struct page * page)
```

```json
{
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581495569,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:464",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page"
      ],
      "caller_func": [
        "mm/debug.c:__dump_page"
      ]
    },
    {
      "addr": 18446744071581606332,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:464",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581614230,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:464",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581745282,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:464",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581994204,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:464",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs_file",
        "mm/memory-failure.c:collect_procs_file",
        "mm/memory-failure.c:collect_procs_anon",
        "mm/memory-failure.c:collect_procs_anon",
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581495200,
      "name": "page_to_pgoff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581537146,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:527",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581653740,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:527",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581661542,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:527",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582043732,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:527",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs_file",
        "mm/memory-failure.c:collect_procs_file",
        "mm/memory-failure.c:collect_procs_anon",
        "mm/memory-failure.c:collect_procs_anon",
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580256496,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:544",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581558952,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:544",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581675412,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:544",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581682660,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:544",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582069690,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:544",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580407799,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581823205,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581944612,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581952564,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582383738,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580625507,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:793",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582214510,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:793",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582350728,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:793",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:vma_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582366681,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:793",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582647528,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:793",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582885361,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:793",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
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
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580891395,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:789",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582702598,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:789",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582855617,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:789",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582869652,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:789",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583169782,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:789",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583436726,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:789",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580975242,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:810",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582916503,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:810",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583068387,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:810",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:vma_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583085507,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:810",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:vma_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583385866,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:810",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583660761,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:810",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs_anon"
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
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583090616,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:900",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583250310,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:900",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:vma_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583268102,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:900",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:vma_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583628100,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:900",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583855072,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:900",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs_anon",
        "mm/memory-failure.c:collect_procs_anon"
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
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492713928,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492807820,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492813744,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493230888,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226549556,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226619632,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 3226622216,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma"
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
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286051148,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286186408,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286194252,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286747696,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:add_to_kill",
        "mm/memory-failure.c:add_to_kill"
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
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272711634,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272771134,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272774116,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma",
        "mm/rmap.c:page_address_in_vma"
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
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581273676,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581376988,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581382326,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581741767,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
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
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581220236,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581320140,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581325654,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680391,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:add_to_kill",
        "mm/memory-failure.c:add_to_kill"
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
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581264876,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581368188,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581373526,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581733079,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
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
  "name": "page_to_pgoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581328748,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581432060,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581437830,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581801367,
      "name": "page_to_pgoff",
      "external": false,
      "loc": "include/linux/pagemap.h:423",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
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
long unsigned int page_to_pgoff(struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
long unsigned int page_to_pgoff(struct page * page)
```
</details>
</li>
</ul>
