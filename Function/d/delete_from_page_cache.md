# Function: <code>delete_from_page_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void delete_from_page_cache(struct page * page)
```

```json
{
  "name": "delete_from_page_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580477072,
      "name": "delete_from_page_cache",
      "external": true,
      "loc": "mm/filemap.c:230",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_page",
        "mm/shmem.c:shmem_getpage_gfp",
        "fs/dax.c:__dax_fault",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580477072,
      "name": "delete_from_page_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void delete_from_page_cache(struct page * page)
```

```json
{
  "name": "delete_from_page_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580557696,
      "name": "delete_from_page_cache",
      "external": true,
      "loc": "mm/filemap.c:306",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_page",
        "mm/shmem.c:shmem_getpage_gfp",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580557696,
      "name": "delete_from_page_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void delete_from_page_cache(struct page * page)
```

```json
{
  "name": "delete_from_page_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580622800,
      "name": "delete_from_page_cache",
      "external": true,
      "loc": "mm/filemap.c:271",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_page",
        "mm/shmem.c:shmem_getpage_gfp",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580622800,
      "name": "delete_from_page_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void delete_from_page_cache(struct page * page)
```

```json
{
  "name": "delete_from_page_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580650672,
      "name": "delete_from_page_cache",
      "external": true,
      "loc": "mm/filemap.c:265",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_page",
        "mm/shmem.c:shmem_getpage_gfp",
        "fs/hugetlbfs/inode.c:remove_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580650672,
      "name": "delete_from_page_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void delete_from_page_cache(struct page * page)
```

```json
{
  "name": "delete_from_page_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580734192,
      "name": "delete_from_page_cache",
      "external": true,
      "loc": "mm/filemap.c:294",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:generic_error_remove_page",
        "mm/shmem.c:shmem_getpage_gfp",
        "fs/hugetlbfs/inode.c:remove_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580734192,
      "name": "delete_from_page_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void delete_from_page_cache(struct page * page)
```

```json
{
  "name": "delete_from_page_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580872256,
      "name": "delete_from_page_cache",
      "external": true,
      "loc": "mm/filemap.c:294",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:generic_error_remove_page",
        "mm/shmem.c:shmem_getpage_gfp",
        "fs/hugetlbfs/inode.c:remove_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580872256,
      "name": "delete_from_page_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void delete_from_page_cache(struct page * page)
```

```json
{
  "name": "delete_from_page_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580944224,
      "name": "delete_from_page_cache",
      "external": true,
      "loc": "mm/filemap.c:262",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:generic_error_remove_page",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "fs/hugetlbfs/inode.c:remove_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580944224,
      "name": "delete_from_page_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void delete_from_page_cache(struct page * page)
```

```json
{
  "name": "delete_from_page_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581041552,
      "name": "delete_from_page_cache",
      "external": true,
      "loc": "mm/filemap.c:264",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:generic_error_remove_page",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "fs/hugetlbfs/inode.c:remove_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581041552,
      "name": "delete_from_page_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void delete_from_page_cache(struct page * page)
```

```json
{
  "name": "delete_from_page_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581096992,
      "name": "delete_from_page_cache",
      "external": true,
      "loc": "mm/filemap.c:266",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:generic_error_remove_page",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "fs/hugetlbfs/inode.c:remove_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581096992,
      "name": "delete_from_page_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void delete_from_page_cache(struct page * page)
```

```json
{
  "name": "delete_from_page_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581269392,
      "name": "delete_from_page_cache",
      "external": true,
      "loc": "mm/filemap.c:266",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:generic_error_remove_page",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "fs/hugetlbfs/inode.c:remove_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581269392,
      "name": "delete_from_page_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
void delete_from_page_cache(struct page * page)
```

```json
{
  "name": "delete_from_page_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581309952,
      "name": "delete_from_page_cache",
      "external": true,
      "loc": "mm/filemap.c:267",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:generic_error_remove_page",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "fs/hugetlbfs/inode.c:remove_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581309952,
      "name": "delete_from_page_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void delete_from_page_cache(struct page * page)
```

```json
{
  "name": "delete_from_page_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581340608,
      "name": "delete_from_page_cache",
      "external": true,
      "loc": "mm/filemap.c:258",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:generic_error_remove_page",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "fs/hugetlbfs/inode.c:remove_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581340608,
      "name": "delete_from_page_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void delete_from_page_cache(struct page * page)
```

```json
{
  "name": "delete_from_page_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581589536,
      "name": "delete_from_page_cache",
      "external": true,
      "loc": "mm/filemap.c:260",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:generic_error_remove_page",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "fs/hugetlbfs/inode.c:remove_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581589536,
      "name": "delete_from_page_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void delete_from_page_cache(struct page * page)
```

```json
{
  "name": "delete_from_page_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581995712,
      "name": "delete_from_page_cache",
      "external": true,
      "loc": "mm/folio-compat.c:143",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "fs/hugetlbfs/inode.c:remove_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995712,
      "name": "delete_from_page_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void delete_from_page_cache(struct page * page)
```

```json
{
  "name": "delete_from_page_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492461264,
      "name": "delete_from_page_cache",
      "external": true,
      "loc": "mm/filemap.c:266",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:generic_error_remove_page",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "fs/hugetlbfs/inode.c:remove_huge_page",
        "fs/hugetlbfs/inode.c:remove_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492461264,
      "name": "delete_from_page_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void delete_from_page_cache(struct page * page)
```

```json
{
  "name": "delete_from_page_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226337020,
      "name": "delete_from_page_cache",
      "external": true,
      "loc": "mm/filemap.c:266",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:generic_error_remove_page",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226337020,
      "name": "delete_from_page_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void delete_from_page_cache(struct page * page)
```

```json
{
  "name": "delete_from_page_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285741504,
      "name": "delete_from_page_cache",
      "external": true,
      "loc": "mm/filemap.c:266",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:generic_error_remove_page",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "fs/hugetlbfs/inode.c:remove_huge_page",
        "fs/hugetlbfs/inode.c:remove_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285741504,
      "name": "delete_from_page_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void delete_from_page_cache(struct page * page)
```

```json
{
  "name": "delete_from_page_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272532850,
      "name": "delete_from_page_cache",
      "external": true,
      "loc": "mm/filemap.c:266",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:generic_error_remove_page",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "fs/hugetlbfs/inode.c:remove_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272532850,
      "name": "delete_from_page_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void delete_from_page_cache(struct page * page)
```

```json
{
  "name": "delete_from_page_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581065840,
      "name": "delete_from_page_cache",
      "external": true,
      "loc": "mm/filemap.c:266",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:generic_error_remove_page",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "fs/hugetlbfs/inode.c:remove_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581065840,
      "name": "delete_from_page_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void delete_from_page_cache(struct page * page)
```

```json
{
  "name": "delete_from_page_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581013040,
      "name": "delete_from_page_cache",
      "external": true,
      "loc": "mm/filemap.c:266",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:generic_error_remove_page",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "fs/hugetlbfs/inode.c:remove_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581013040,
      "name": "delete_from_page_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void delete_from_page_cache(struct page * page)
```

```json
{
  "name": "delete_from_page_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581057040,
      "name": "delete_from_page_cache",
      "external": true,
      "loc": "mm/filemap.c:266",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:generic_error_remove_page",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "fs/hugetlbfs/inode.c:remove_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581057040,
      "name": "delete_from_page_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void delete_from_page_cache(struct page * page)
```

```json
{
  "name": "delete_from_page_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581118592,
      "name": "delete_from_page_cache",
      "external": true,
      "loc": "mm/filemap.c:266",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:generic_error_remove_page",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "fs/hugetlbfs/inode.c:remove_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581118592,
      "name": "delete_from_page_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void delete_from_page_cache(struct page * page)
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
