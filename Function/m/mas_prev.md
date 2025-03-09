# Function: <code>mas_prev</code>

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
void * mas_prev(struct ma_state * mas, long unsigned int min)
```

```json
{
  "name": "mas_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595811145,
      "name": "mas_prev",
      "external": true,
      "loc": "lib/maple_tree.c:5910",
      "file": "lib/maple_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/maple_tree.c:mt_prev"
      ],
      "caller_func": [
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_mas_align_munmap",
        "mm/mmap.c:do_mas_align_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:find_vma_prev",
        "mm/mmap.c:find_mergeable_anon_vma",
        "mm/mmap.c:find_mergeable_anon_vma",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mempolicy.c:mbind_range",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595810688,
      "name": "mas_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void * mas_prev(struct ma_state * mas, long unsigned int min)
```

```json
{
  "name": "mas_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596331040,
      "name": "mas_prev",
      "external": true,
      "loc": "lib/maple_tree.c:5826",
      "file": "lib/maple_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_vmi_align_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:find_vma_prev",
        "mm/mmap.c:vm_unmapped_area",
        "mm/mmap.c:vm_unmapped_area",
        "mm/mmap.c:find_mergeable_anon_vma",
        "mm/mmap.c:find_mergeable_anon_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:move_vma",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:do_mbind",
        "fs/exec.c:shift_arg_pages",
        "fs/userfaultfd.c:userfaultfd_register",
        "lib/maple_tree.c:mt_prev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596331040,
      "name": "mas_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
void * mas_prev(struct ma_state * mas, long unsigned int min)
```

```json
{
  "name": "mas_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597248272,
      "name": "mas_prev",
      "external": true,
      "loc": "lib/maple_tree.c:5835",
      "file": "lib/maple_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/maple_tree.c:mt_prev",
        "lib/maple_tree.c:mt_prev"
      ],
      "caller_func": [
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:find_vma_prev",
        "mm/mmap.c:vm_unmapped_area",
        "mm/mmap.c:vm_unmapped_area",
        "mm/mmap.c:find_mergeable_anon_vma",
        "mm/mmap.c:find_mergeable_anon_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:move_vma",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:do_mbind",
        "fs/exec.c:shift_arg_pages",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597247632,
      "name": "mas_prev",
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
void * mas_prev(struct ma_state * mas, long unsigned int min)
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
