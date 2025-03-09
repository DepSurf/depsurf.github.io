# Function: <code>do_huge_pmd_wp_page_fallback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_huge_pmd_wp_page_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580911165,
      "name": "do_huge_pmd_wp_page_fallback",
      "external": false,
      "loc": "mm/huge_memory.c:1042",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
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
  "name": "do_huge_pmd_wp_page_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581035249,
      "name": "do_huge_pmd_wp_page_fallback",
      "external": false,
      "loc": "mm/huge_memory.c:829",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
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
  "name": "do_huge_pmd_wp_page_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581110449,
      "name": "do_huge_pmd_wp_page_fallback",
      "external": false,
      "loc": "mm/huge_memory.c:909",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
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
  "name": "do_huge_pmd_wp_page_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581158901,
      "name": "do_huge_pmd_wp_page_fallback",
      "external": false,
      "loc": "mm/huge_memory.c:1112",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
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
  "name": "do_huge_pmd_wp_page_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581284137,
      "name": "do_huge_pmd_wp_page_fallback",
      "external": false,
      "loc": "mm/huge_memory.c:1124",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int do_huge_pmd_wp_page_fallback(struct vm_fault * vmf, pmd_t orig_pmd, struct page * page)
```

```json
{
  "name": "do_huge_pmd_wp_page_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581415456,
      "name": "do_huge_pmd_wp_page_fallback",
      "external": false,
      "loc": "mm/huge_memory.c:1121",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581415456,
      "name": "do_huge_pmd_wp_page_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1760
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
vm_fault_t do_huge_pmd_wp_page_fallback(struct vm_fault * vmf, pmd_t orig_pmd, struct page * page)
```

```json
{
  "name": "do_huge_pmd_wp_page_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581498800,
      "name": "do_huge_pmd_wp_page_fallback",
      "external": false,
      "loc": "mm/huge_memory.c:1136",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581498800,
      "name": "do_huge_pmd_wp_page_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1810
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
vm_fault_t do_huge_pmd_wp_page_fallback(struct vm_fault * vmf, pmd_t orig_pmd, struct page * page)
```

```json
{
  "name": "do_huge_pmd_wp_page_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581608400,
      "name": "do_huge_pmd_wp_page_fallback",
      "external": false,
      "loc": "mm/huge_memory.c:1192",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581608400,
      "name": "do_huge_pmd_wp_page_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1858
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
vm_fault_t do_huge_pmd_wp_page_fallback(struct vm_fault * vmf, pmd_t orig_pmd, struct page * page)
```

```json
{
  "name": "do_huge_pmd_wp_page_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581679296,
      "name": "do_huge_pmd_wp_page_fallback",
      "external": false,
      "loc": "mm/huge_memory.c:1198",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581679296,
      "name": "do_huge_pmd_wp_page_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1887
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
vm_fault_t do_huge_pmd_wp_page_fallback(struct vm_fault * vmf, pmd_t orig_pmd, struct page * page)
```

```json
{
  "name": "do_huge_pmd_wp_page_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493127024,
      "name": "do_huge_pmd_wp_page_fallback",
      "external": false,
      "loc": "mm/huge_memory.c:1198",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493127024,
      "name": "do_huge_pmd_wp_page_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1664
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_wp_page_fallback(struct vm_fault * vmf, pmd_t orig_pmd, struct page * page)
```

```json
{
  "name": "do_huge_pmd_wp_page_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286606624,
      "name": "do_huge_pmd_wp_page_fallback",
      "external": false,
      "loc": "mm/huge_memory.c:1198",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286606624,
      "name": "do_huge_pmd_wp_page_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2544
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_wp_page_fallback(struct vm_fault * vmf, pmd_t orig_pmd, struct page * page)
```

```json
{
  "name": "do_huge_pmd_wp_page_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581648032,
      "name": "do_huge_pmd_wp_page_fallback",
      "external": false,
      "loc": "mm/huge_memory.c:1198",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581648032,
      "name": "do_huge_pmd_wp_page_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1887
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
vm_fault_t do_huge_pmd_wp_page_fallback(struct vm_fault * vmf, pmd_t orig_pmd, struct page * page)
```

```json
{
  "name": "do_huge_pmd_wp_page_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581590864,
      "name": "do_huge_pmd_wp_page_fallback",
      "external": false,
      "loc": "mm/huge_memory.c:1198",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581590864,
      "name": "do_huge_pmd_wp_page_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1784
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
vm_fault_t do_huge_pmd_wp_page_fallback(struct vm_fault * vmf, pmd_t orig_pmd, struct page * page)
```

```json
{
  "name": "do_huge_pmd_wp_page_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581639344,
      "name": "do_huge_pmd_wp_page_fallback",
      "external": false,
      "loc": "mm/huge_memory.c:1198",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581639344,
      "name": "do_huge_pmd_wp_page_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1887
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
vm_fault_t do_huge_pmd_wp_page_fallback(struct vm_fault * vmf, pmd_t orig_pmd, struct page * page)
```

```json
{
  "name": "do_huge_pmd_wp_page_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581705680,
      "name": "do_huge_pmd_wp_page_fallback",
      "external": false,
      "loc": "mm/huge_memory.c:1198",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581705680,
      "name": "do_huge_pmd_wp_page_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1926
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
int do_huge_pmd_wp_page_fallback(struct vm_fault * vmf, pmd_t orig_pmd, struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
</details>
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
vm_fault_t do_huge_pmd_wp_page_fallback(struct vm_fault * vmf, pmd_t orig_pmd, struct page * page)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
vm_fault_t do_huge_pmd_wp_page_fallback(struct vm_fault * vmf, pmd_t orig_pmd, struct page * page)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
vm_fault_t do_huge_pmd_wp_page_fallback(struct vm_fault * vmf, pmd_t orig_pmd, struct page * page)
```
</details>
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
