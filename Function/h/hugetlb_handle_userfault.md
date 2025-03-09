# Function: <code>hugetlb_handle_userfault</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
vm_fault_t hugetlb_handle_userfault(struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, unsigned int flags, long unsigned int haddr, long unsigned int reason)
```

```json
{
  "name": "hugetlb_handle_userfault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581835648,
      "name": "hugetlb_handle_userfault",
      "external": false,
      "loc": "mm/hugetlb.c:4535",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_no_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581835648,
      "name": "hugetlb_handle_userfault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
vm_fault_t hugetlb_handle_userfault(struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, unsigned int flags, long unsigned int haddr, long unsigned int reason)
```

```json
{
  "name": "hugetlb_handle_userfault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582125888,
      "name": "hugetlb_handle_userfault",
      "external": false,
      "loc": "mm/hugetlb.c:4840",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_no_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582125888,
      "name": "hugetlb_handle_userfault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
vm_fault_t hugetlb_handle_userfault(struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, unsigned int flags, long unsigned int haddr, long unsigned int addr, long unsigned int reason)
```

```json
{
  "name": "hugetlb_handle_userfault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582571760,
      "name": "hugetlb_handle_userfault",
      "external": false,
      "loc": "mm/hugetlb.c:5456",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_no_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582571760,
      "name": "hugetlb_handle_userfault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
vm_fault_t hugetlb_handle_userfault(struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, unsigned int flags, long unsigned int haddr, long unsigned int addr, long unsigned int reason)
```

```json
{
  "name": "hugetlb_handle_userfault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583091296,
      "name": "hugetlb_handle_userfault",
      "external": false,
      "loc": "mm/hugetlb.c:5696",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_no_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583091296,
      "name": "hugetlb_handle_userfault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
vm_fault_t hugetlb_handle_userfault(struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, unsigned int flags, long unsigned int haddr, long unsigned int addr, long unsigned int reason)
```

```json
{
  "name": "hugetlb_handle_userfault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583301248,
      "name": "hugetlb_handle_userfault",
      "external": false,
      "loc": "mm/hugetlb.c:5795",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_no_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583301248,
      "name": "hugetlb_handle_userfault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
vm_fault_t hugetlb_handle_userfault(struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, unsigned int flags, long unsigned int haddr, long unsigned int addr, long unsigned int reason)
```

```json
{
  "name": "hugetlb_handle_userfault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583538480,
      "name": "hugetlb_handle_userfault",
      "external": false,
      "loc": "mm/hugetlb.c:6063",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_no_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583538480,
      "name": "hugetlb_handle_userfault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
vm_fault_t hugetlb_handle_userfault(struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, unsigned int flags, long unsigned int haddr, long unsigned int reason)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int addr</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, mapping, idx, flags, haddr, reason</code> ➡️ <code>vma, mapping, idx, flags, haddr, addr, reason</code>
</li>
</ul>
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
