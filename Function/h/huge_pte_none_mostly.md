# Function: <code>huge_pte_none_mostly</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int huge_pte_none_mostly(pte_t pte)
```

```json
{
  "name": "huge_pte_none_mostly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582573229,
      "name": "huge_pte_none_mostly",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:102",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_pte_none_mostly",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:102",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    },
    {
      "addr": 0,
      "name": "huge_pte_none_mostly",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:102",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582924480,
      "name": "huge_pte_none_mostly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int huge_pte_none_mostly(pte_t pte)
```

```json
{
  "name": "huge_pte_none_mostly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583092388,
      "name": "huge_pte_none_mostly",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:102",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_pte_none_mostly",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:102",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    },
    {
      "addr": 0,
      "name": "huge_pte_none_mostly",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:102",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583480096,
      "name": "huge_pte_none_mostly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int huge_pte_none_mostly(pte_t pte)
```

```json
{
  "name": "huge_pte_none_mostly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "huge_pte_none_mostly",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:109",
      "file": "mm/mincore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583302251,
      "name": "huge_pte_none_mostly",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:109",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_pte_none_mostly",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:109",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_atomic_copy"
      ]
    },
    {
      "addr": 0,
      "name": "huge_pte_none_mostly",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:109",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583696784,
      "name": "huge_pte_none_mostly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
  "name": "huge_pte_none_mostly",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "huge_pte_none_mostly",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:109",
      "file": "mm/mincore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583539298,
      "name": "huge_pte_none_mostly",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:109",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_pte_none_mostly",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:109",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_pte_none_mostly",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:109",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
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
int huge_pte_none_mostly(pte_t pte)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int huge_pte_none_mostly(pte_t pte)
```
</details>
</li>
</ul>
