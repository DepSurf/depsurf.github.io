# Function: <code>pte_none_mostly</code>

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
int pte_none_mostly(pte_t pte)
```

```json
{
  "name": "pte_none_mostly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582291113,
      "name": "pte_none_mostly",
      "external": false,
      "loc": "include/linux/swapops.h:365",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582836972,
      "name": "pte_none_mostly",
      "external": false,
      "loc": "include/linux/swapops.h:365",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582925505,
      "name": "pte_none_mostly",
      "external": false,
      "loc": "include/linux/swapops.h:365",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582942171,
      "name": "pte_none_mostly",
      "external": false,
      "loc": "include/linux/swapops.h:365",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583422960,
      "name": "pte_none_mostly",
      "external": false,
      "loc": "include/linux/swapops.h:365",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582924480,
      "name": "pte_none_mostly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071583423152,
      "name": "pte_none_mostly",
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
int pte_none_mostly(pte_t pte)
```

```json
{
  "name": "pte_none_mostly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582783640,
      "name": "pte_none_mostly",
      "external": false,
      "loc": "include/linux/swapops.h:457",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583380329,
      "name": "pte_none_mostly",
      "external": false,
      "loc": "include/linux/swapops.h:457",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481177,
      "name": "pte_none_mostly",
      "external": false,
      "loc": "include/linux/swapops.h:457",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583499012,
      "name": "pte_none_mostly",
      "external": false,
      "loc": "include/linux/swapops.h:457",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584011296,
      "name": "pte_none_mostly",
      "external": false,
      "loc": "include/linux/swapops.h:457",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583480096,
      "name": "pte_none_mostly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071584011504,
      "name": "pte_none_mostly",
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
int pte_none_mostly(pte_t pte)
```

```json
{
  "name": "pte_none_mostly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583000369,
      "name": "pte_none_mostly",
      "external": false,
      "loc": "include/linux/swapops.h:448",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583600500,
      "name": "pte_none_mostly",
      "external": false,
      "loc": "include/linux/swapops.h:448",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583697702,
      "name": "pte_none_mostly",
      "external": false,
      "loc": "include/linux/swapops.h:448",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583714005,
      "name": "pte_none_mostly",
      "external": false,
      "loc": "include/linux/swapops.h:448",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_handle_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584235822,
      "name": "pte_none_mostly",
      "external": false,
      "loc": "include/linux/swapops.h:448",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583696784,
      "name": "pte_none_mostly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071584236048,
      "name": "pte_none_mostly",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pte_none_mostly(pte_t pte)
```

```json
{
  "name": "pte_none_mostly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583179745,
      "name": "pte_none_mostly",
      "external": false,
      "loc": "include/linux/swapops.h:453",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583796962,
      "name": "pte_none_mostly",
      "external": false,
      "loc": "include/linux/swapops.h:453",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583900533,
      "name": "pte_none_mostly",
      "external": false,
      "loc": "include/linux/swapops.h:453",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583914801,
      "name": "pte_none_mostly",
      "external": false,
      "loc": "include/linux/swapops.h:453",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_handle_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584450192,
      "name": "pte_none_mostly",
      "external": false,
      "loc": "include/linux/swapops.h:453",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584450192,
      "name": "pte_none_mostly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int pte_none_mostly(pte_t pte)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
