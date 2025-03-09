# Function: <code>mas_next</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * mas_next(struct ma_state * mas, long unsigned int max)
```

```json
{
  "name": "mas_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595822612,
      "name": "mas_next",
      "external": true,
      "loc": "lib/maple_tree.c:5855",
      "file": "lib/maple_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/maple_tree.c:mt_next"
      ],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_mas_align_munmap",
        "mm/mmap.c:find_vma_prev",
        "mm/mempolicy.c:mbind_range",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/coredump.c:dump_vma_snapshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595820992,
      "name": "mas_next",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * mas_next(struct ma_state * mas, long unsigned int max)
```

```json
{
  "name": "mas_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596327360,
      "name": "mas_next",
      "external": true,
      "loc": "lib/maple_tree.c:5719",
      "file": "lib/maple_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:find_vma_prev",
        "mm/mmap.c:vm_unmapped_area",
        "mm/mmap.c:vm_unmapped_area",
        "lib/maple_tree.c:mt_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596327360,
      "name": "mas_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * mas_next(struct ma_state * mas, long unsigned int max)
```

```json
{
  "name": "mas_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597252784,
      "name": "mas_next",
      "external": true,
      "loc": "lib/maple_tree.c:5704",
      "file": "lib/maple_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/maple_tree.c:mt_next",
        "lib/maple_tree.c:mt_next"
      ],
      "caller_func": [
        "mm/mmap.c:find_vma_prev",
        "mm/mmap.c:vm_unmapped_area",
        "mm/mmap.c:vm_unmapped_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597250304,
      "name": "mas_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void * mas_next(struct ma_state * mas, long unsigned int max)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
