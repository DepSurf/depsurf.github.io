# Function: <code>vma_compute_subtree_gap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vma_compute_subtree_gap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580696289,
      "name": "vma_compute_subtree_gap",
      "external": false,
      "loc": "mm/mmap.c:356",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:vma_gap_callbacks_rotate",
        "mm/mmap.c:vma_rb_erase",
        "mm/mmap.c:vma_rb_erase",
        "mm/mmap.c:__vma_link_rb",
        "mm/mmap.c:__vma_link_rb",
        "mm/mmap.c:vma_adjust",
        "mm/mmap.c:vma_adjust",
        "mm/mmap.c:vma_adjust",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:do_munmap"
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
  "name": "vma_compute_subtree_gap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580820081,
      "name": "vma_compute_subtree_gap",
      "external": false,
      "loc": "mm/mmap.c:245",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:vma_adjust",
        "mm/mmap.c:vma_adjust",
        "mm/mmap.c:vma_adjust",
        "mm/mmap.c:__vma_link_rb",
        "mm/mmap.c:__vma_link_rb",
        "mm/mmap.c:vma_rb_erase",
        "mm/mmap.c:vma_rb_erase",
        "mm/mmap.c:vma_gap_callbacks_rotate"
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
  "name": "vma_compute_subtree_gap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580885569,
      "name": "vma_compute_subtree_gap",
      "external": false,
      "loc": "mm/mmap.c:252",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_link_rb",
        "mm/mmap.c:__vma_link_rb",
        "mm/mmap.c:__vma_rb_erase",
        "mm/mmap.c:__vma_rb_erase",
        "mm/mmap.c:vma_gap_callbacks_rotate"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
long int vma_compute_subtree_gap(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_compute_subtree_gap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580920672,
      "name": "vma_compute_subtree_gap",
      "external": false,
      "loc": "mm/mmap.c:256",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_link_rb",
        "mm/mmap.c:__vma_link_rb",
        "mm/mmap.c:__vma_rb_erase",
        "mm/mmap.c:__vma_rb_erase",
        "mm/mmap.c:__vma_rb_erase",
        "mm/mmap.c:vma_gap_callbacks_rotate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920672,
      "name": "vma_compute_subtree_gap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
long int vma_compute_subtree_gap(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_compute_subtree_gap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581020272,
      "name": "vma_compute_subtree_gap",
      "external": false,
      "loc": "mm/mmap.c:257",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_link_rb",
        "mm/mmap.c:__vma_link_rb",
        "mm/mmap.c:__vma_rb_erase",
        "mm/mmap.c:__vma_rb_erase",
        "mm/mmap.c:__vma_rb_erase",
        "mm/mmap.c:vma_gap_callbacks_rotate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581020272,
      "name": "vma_compute_subtree_gap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
long int vma_compute_subtree_gap(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_compute_subtree_gap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581155344,
      "name": "vma_compute_subtree_gap",
      "external": false,
      "loc": "mm/mmap.c:266",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_link_rb",
        "mm/mmap.c:__vma_link_rb",
        "mm/mmap.c:__vma_rb_erase",
        "mm/mmap.c:__vma_rb_erase",
        "mm/mmap.c:vma_gap_callbacks_rotate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581155344,
      "name": "vma_compute_subtree_gap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
long int vma_compute_subtree_gap(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_compute_subtree_gap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581235136,
      "name": "vma_compute_subtree_gap",
      "external": false,
      "loc": "mm/mmap.c:290",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_link_rb",
        "mm/mmap.c:__vma_link_rb",
        "mm/mmap.c:__vma_rb_erase",
        "mm/mmap.c:__vma_rb_erase",
        "mm/mmap.c:vma_gap_callbacks_rotate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581235136,
      "name": "vma_compute_subtree_gap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
long int vma_compute_subtree_gap(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_compute_subtree_gap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581309392,
      "name": "vma_compute_subtree_gap",
      "external": false,
      "loc": "mm/mmap.c:292",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_link_rb",
        "mm/mmap.c:__vma_link_rb",
        "mm/mmap.c:__vma_rb_erase",
        "mm/mmap.c:__vma_rb_erase",
        "mm/mmap.c:vma_gap_callbacks_rotate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581309392,
      "name": "vma_compute_subtree_gap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
long int vma_compute_subtree_gap(struct vm_area_struct * vma)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
long int vma_compute_subtree_gap(struct vm_area_struct * vma)
```
</details>
</li>
</ul>
