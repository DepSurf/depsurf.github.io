# Function: <code>hmm_vma_walk_hole_</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk * walk)
```

```json
{
  "name": "hmm_vma_walk_hole_",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581539568,
      "name": "hmm_vma_walk_hole_",
      "external": false,
      "loc": "mm/hmm.c:345",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581539568,
      "name": "hmm_vma_walk_hole_",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk * walk)
```

```json
{
  "name": "hmm_vma_walk_hole_",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581625568,
      "name": "hmm_vma_walk_hole_",
      "external": false,
      "loc": "mm/hmm.c:363",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581625568,
      "name": "hmm_vma_walk_hole_",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk * walk)
```

```json
{
  "name": "hmm_vma_walk_hole_",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581741904,
      "name": "hmm_vma_walk_hole_",
      "external": false,
      "loc": "mm/hmm.c:342",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581741904,
      "name": "hmm_vma_walk_hole_",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk * walk)
```

```json
{
  "name": "hmm_vma_walk_hole_",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581815616,
      "name": "hmm_vma_walk_hole_",
      "external": false,
      "loc": "mm/hmm.c:283",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581815616,
      "name": "hmm_vma_walk_hole_",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk * walk)
```

```json
{
  "name": "hmm_vma_walk_hole_",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493278864,
      "name": "hmm_vma_walk_hole_",
      "external": false,
      "loc": "mm/hmm.c:283",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole",
        "mm/hmm.c:hmm_vma_walk_hole",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493278864,
      "name": "hmm_vma_walk_hole_",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk * walk)
```

```json
{
  "name": "hmm_vma_walk_hole_",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226884844,
      "name": "hmm_vma_walk_hole_",
      "external": false,
      "loc": "mm/hmm.c:283",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole",
        "mm/hmm.c:hmm_vma_walk_hole",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226884844,
      "name": "hmm_vma_walk_hole_",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk * walk)
```

```json
{
  "name": "hmm_vma_walk_hole_",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286812656,
      "name": "hmm_vma_walk_hole_",
      "external": false,
      "loc": "mm/hmm.c:283",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286812656,
      "name": "hmm_vma_walk_hole_",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk * walk)
```

```json
{
  "name": "hmm_vma_walk_hole_",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273029808,
      "name": "hmm_vma_walk_hole_",
      "external": false,
      "loc": "mm/hmm.c:283",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273029808,
      "name": "hmm_vma_walk_hole_",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk * walk)
```

```json
{
  "name": "hmm_vma_walk_hole_",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581784352,
      "name": "hmm_vma_walk_hole_",
      "external": false,
      "loc": "mm/hmm.c:283",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581784352,
      "name": "hmm_vma_walk_hole_",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk * walk)
```

```json
{
  "name": "hmm_vma_walk_hole_",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581722512,
      "name": "hmm_vma_walk_hole_",
      "external": false,
      "loc": "mm/hmm.c:283",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581722512,
      "name": "hmm_vma_walk_hole_",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk * walk)
```

```json
{
  "name": "hmm_vma_walk_hole_",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581775664,
      "name": "hmm_vma_walk_hole_",
      "external": false,
      "loc": "mm/hmm.c:283",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581775664,
      "name": "hmm_vma_walk_hole_",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk * walk)
```

```json
{
  "name": "hmm_vma_walk_hole_",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581844624,
      "name": "hmm_vma_walk_hole_",
      "external": false,
      "loc": "mm/hmm.c:283",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581844624,
      "name": "hmm_vma_walk_hole_",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk * walk)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk * walk)
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
