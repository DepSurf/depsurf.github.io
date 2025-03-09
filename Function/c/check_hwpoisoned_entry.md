# Function: <code>check_hwpoisoned_entry</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int check_hwpoisoned_entry(pte_t pte, long unsigned int addr, short int shift, long unsigned int poisoned_pfn, struct to_kill * tk)
```

```json
{
  "name": "check_hwpoisoned_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582378784,
      "name": "check_hwpoisoned_entry",
      "external": false,
      "loc": "mm/memory-failure.c:581",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:hwpoison_hugetlb_range",
        "mm/memory-failure.c:hwpoison_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582378784,
      "name": "check_hwpoisoned_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
int check_hwpoisoned_entry(pte_t pte, long unsigned int addr, short int shift, long unsigned int poisoned_pfn, struct to_kill * tk)
```

```json
{
  "name": "check_hwpoisoned_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582879648,
      "name": "check_hwpoisoned_entry",
      "external": false,
      "loc": "mm/memory-failure.c:578",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:hwpoison_hugetlb_range",
        "mm/memory-failure.c:hwpoison_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582879648,
      "name": "check_hwpoisoned_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int check_hwpoisoned_entry(pte_t pte, long unsigned int addr, short int shift, long unsigned int poisoned_pfn, struct to_kill * tk)
```

```json
{
  "name": "check_hwpoisoned_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583428496,
      "name": "check_hwpoisoned_entry",
      "external": false,
      "loc": "mm/memory-failure.c:640",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:hwpoison_hugetlb_range",
        "mm/memory-failure.c:hwpoison_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583428496,
      "name": "check_hwpoisoned_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
int check_hwpoisoned_entry(pte_t pte, long unsigned int addr, short int shift, long unsigned int poisoned_pfn, struct to_kill * tk)
```

```json
{
  "name": "check_hwpoisoned_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583649600,
      "name": "check_hwpoisoned_entry",
      "external": false,
      "loc": "mm/memory-failure.c:736",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:hwpoison_hugetlb_range",
        "mm/memory-failure.c:hwpoison_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583649600,
      "name": "check_hwpoisoned_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
int check_hwpoisoned_entry(pte_t pte, long unsigned int addr, short int shift, long unsigned int poisoned_pfn, struct to_kill * tk)
```

```json
{
  "name": "check_hwpoisoned_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583844416,
      "name": "check_hwpoisoned_entry",
      "external": false,
      "loc": "mm/memory-failure.c:738",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:hwpoison_hugetlb_range",
        "mm/memory-failure.c:hwpoison_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583844416,
      "name": "check_hwpoisoned_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int check_hwpoisoned_entry(pte_t pte, long unsigned int addr, short int shift, long unsigned int poisoned_pfn, struct to_kill * tk)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
