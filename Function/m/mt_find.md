# Function: <code>mt_find</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void * mt_find(struct maple_tree * mt, long unsigned int * index, long unsigned int max)
```

```json
{
  "name": "mt_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595821296,
      "name": "mt_find",
      "external": true,
      "loc": "lib/maple_tree.c:6427",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "lib/maple_tree.c:mt_find_after"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595821296,
      "name": "mt_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1137
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
void * mt_find(struct maple_tree * mt, long unsigned int * index, long unsigned int max)
```

```json
{
  "name": "mt_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596327968,
      "name": "mt_find",
      "external": true,
      "loc": "lib/maple_tree.c:6484",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_get_next_irq",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:find_extend_vma_locked",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "lib/maple_tree.c:mt_find_after"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596327968,
      "name": "mt_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 559
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
void * mt_find(struct maple_tree * mt, long unsigned int * index, long unsigned int max)
```

```json
{
  "name": "mt_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597251312,
      "name": "mt_find",
      "external": true,
      "loc": "lib/maple_tree.c:6829",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_get_next_irq",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:find_extend_vma_locked",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "lib/maple_tree.c:mt_find_after"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597251312,
      "name": "mt_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1295
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
void * mt_find(struct maple_tree * mt, long unsigned int * index, long unsigned int max)
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
