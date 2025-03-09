# Function: <code>pages_per_huge_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:410",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580883961,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:410",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:410",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:410",
      "file": "ipc/shm.c",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580932974,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:406",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_total_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009337,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:406",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582156447,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:406",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582380825,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:406",
      "file": "ipc/shm.c",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581001299,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:406",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_total_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581083385,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:406",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582245871,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:406",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582472985,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:406",
      "file": "ipc/shm.c",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581048906,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:428",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_total_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581131641,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:428",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581251708,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:428",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582330930,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:428",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582553785,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:428",
      "file": "ipc/shm.c",
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
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581159690,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:422",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_total_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581246973,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:422",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581383637,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:422",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582481631,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:422",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582706237,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:422",
      "file": "ipc/shm.c",
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
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581303097,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:435",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_total_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581390985,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:435",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581533983,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:435",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582672471,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:435",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582898968,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:435",
      "file": "ipc/shm.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581386787,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:446",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_total_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581474445,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:446",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581619933,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:446",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582774327,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:446",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583007128,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:446",
      "file": "ipc/shm.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581498313,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_total_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581589425,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581732151,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582948751,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583188635,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "ipc/shm.c",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581562881,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_total_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581653089,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581805737,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583055407,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583294443,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "ipc/shm.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581761416,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:583",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_total_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:update_and_free_page",
        "mm/hugetlb.c:add_reservation_in_range",
        "mm/hugetlb.c:add_reservation_in_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581869794,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:583",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:copy_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583374463,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:583",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583625883,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:583",
      "file": "ipc/shm.c",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581809519,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:581",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_total_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581915922,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:581",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:copy_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583490365,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:581",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583746427,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:581",
      "file": "ipc/shm.c",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581837896,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:694",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_total_pages",
        "mm/hugetlb.c:gather_bootmem_prealloc",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942431,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:694",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582063113,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:694",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583511935,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:694",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583771387,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:694",
      "file": "ipc/shm.c",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582128640,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:717",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_total_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:add_reservation_in_range",
        "mm/hugetlb.c:add_reservation_in_range"
      ],
      "caller_func": [
        "mm/hugetlb.c:gather_bootmem_prealloc"
      ]
    },
    {
      "addr": 18446744071615396590,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:717",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582373201,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:717",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583867259,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:717",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584133429,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:717",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592210990,
      "name": "pages_per_huge_page.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582575141,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:747",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_total_pages",
        "mm/hugetlb.c:demote_free_huge_page",
        "mm/hugetlb.c:demote_free_huge_page",
        "mm/hugetlb.c:demote_free_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:add_reservation_in_range",
        "mm/hugetlb.c:add_reservation_in_range"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071617188573,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:747",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582873169,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:747",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584439962,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:747",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584729845,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:747",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593989544,
      "name": "pages_per_huge_page.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
unsigned int pages_per_huge_page(const struct hstate * h)
```

```json
{
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583093174,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:786",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_total_pages",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:demote_free_huge_page",
        "mm/hugetlb.c:demote_free_huge_page",
        "mm/hugetlb.c:demote_free_huge_page",
        "mm/hugetlb.c:demote_free_huge_page",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_fresh_hugetlb_folio",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:__update_and_free_page",
        "mm/hugetlb.c:add_reservation_in_range"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:add_reservation_in_range"
      ]
    },
    {
      "addr": 18446744071627884216,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:786",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_init",
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize",
        "mm/hugetlb_vmemmap.c:vmemmap_should_optimize",
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583420940,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:786",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585101194,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:786",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio",
        "fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585423278,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:786",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583060672,
      "name": "pages_per_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071596040189,
      "name": "pages_per_huge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
unsigned int pages_per_huge_page(const struct hstate * h)
```

```json
{
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583304021,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:814",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_total_pages",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:demote_free_hugetlb_folio",
        "mm/hugetlb.c:demote_free_hugetlb_folio",
        "mm/hugetlb.c:demote_free_hugetlb_folio",
        "mm/hugetlb.c:demote_free_hugetlb_folio",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_fresh_hugetlb_folio",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:__update_and_free_hugetlb_folio",
        "mm/hugetlb.c:add_reservation_in_range",
        "mm/hugetlb.c:add_reservation_in_range"
      ],
      "caller_func": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ]
    },
    {
      "addr": 18446744071619647448,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:814",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_init",
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize",
        "mm/hugetlb_vmemmap.c:vmemmap_should_optimize",
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583642201,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:814",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585330842,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:814",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio",
        "fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585654024,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:814",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583271296,
      "name": "pages_per_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071596562369,
      "name": "pages_per_huge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583541929,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:835",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_total_pages",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:demote_free_hugetlb_folio",
        "mm/hugetlb.c:demote_free_hugetlb_folio",
        "mm/hugetlb.c:demote_free_hugetlb_folio",
        "mm/hugetlb.c:demote_free_hugetlb_folio",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:gather_bootmem_prealloc",
        "mm/hugetlb.c:prep_and_add_bootmem_folios",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:__alloc_fresh_hugetlb_folio",
        "mm/hugetlb.c:free_huge_folio",
        "mm/hugetlb.c:free_huge_folio",
        "mm/hugetlb.c:add_reservation_in_range",
        "mm/hugetlb.c:add_reservation_in_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621954440,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:835",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_init",
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize_folios",
        "mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_optimize_folio",
        "mm/hugetlb_vmemmap.c:vmemmap_should_optimize_folio",
        "mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_restore_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583837321,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:835",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585565558,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:835",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio",
        "fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585900792,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:835",
      "file": "ipc/shm.c",
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492996040,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_total_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493103156,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493271368,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494753240,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495035120,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "ipc/shm.c",
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
  "name": "pages_per_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:684",
      "file": "mm/migrate.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286421068,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_total_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286563236,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286797468,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288583892,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288915804,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:shm_add_rss_swap"
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
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272899190,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_total_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272950972,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273023678,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274096218,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274311784,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:shm_add_rss_swap"
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
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581531617,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_total_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581621825,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581774473,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583024143,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583263179,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "ipc/shm.c",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581473431,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_total_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563121,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581712836,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582961295,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583200331,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "ipc/shm.c",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581522929,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_total_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581613137,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581765785,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583012751,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583247211,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "ipc/shm.c",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pages_per_huge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581587878,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_total_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680995,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581834650,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583101930,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583342059,
      "name": "pages_per_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:434",
      "file": "ipc/shm.c",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
unsigned int pages_per_huge_page(const struct hstate * h)
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
unsigned int pages_per_huge_page(const struct hstate * h)
```
</details>
</li>
</ul>
