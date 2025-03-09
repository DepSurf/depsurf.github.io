# Function: <code>device_private_entry_fault</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int device_private_entry_fault(struct vm_area_struct * vma, long unsigned int addr, swp_entry_t entry, unsigned int flags, pmd_t * pmdp)
```

```json
{
  "name": "device_private_entry_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580715488,
      "name": "device_private_entry_fault",
      "external": true,
      "loc": "kernel/memremap.c:224",
      "file": "kernel/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580715488,
      "name": "device_private_entry_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int device_private_entry_fault(struct vm_area_struct * vma, long unsigned int addr, swp_entry_t entry, unsigned int flags, pmd_t * pmdp)
```

```json
{
  "name": "device_private_entry_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580848608,
      "name": "device_private_entry_fault",
      "external": true,
      "loc": "kernel/memremap.c:45",
      "file": "kernel/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580848608,
      "name": "device_private_entry_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
vm_fault_t device_private_entry_fault(struct vm_area_struct * vma, long unsigned int addr, swp_entry_t entry, unsigned int flags, pmd_t * pmdp)
```

```json
{
  "name": "device_private_entry_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580917488,
      "name": "device_private_entry_fault",
      "external": true,
      "loc": "kernel/memremap.c:21",
      "file": "kernel/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580917488,
      "name": "device_private_entry_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int device_private_entry_fault(struct vm_area_struct * vma, long unsigned int addr, swp_entry_t entry, unsigned int flags, pmd_t * pmdp)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
vm_fault_t device_private_entry_fault(struct vm_area_struct * vma, long unsigned int addr, swp_entry_t entry, unsigned int flags, pmd_t * pmdp)
```
</details>
</li>
</ul>
