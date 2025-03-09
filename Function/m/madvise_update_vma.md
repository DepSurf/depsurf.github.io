# Function: <code>madvise_update_vma</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int madvise_update_vma(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start, long unsigned int end, long unsigned int new_flags, struct anon_vma_name * anon_name)
```

```json
{
  "name": "madvise_update_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582482304,
      "name": "madvise_update_vma",
      "external": false,
      "loc": "mm/madvise.c:139",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_vma_anon_name",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582482304,
      "name": "madvise_update_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
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
int madvise_update_vma(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start, long unsigned int end, long unsigned int new_flags, struct anon_vma_name * anon_name)
```

```json
{
  "name": "madvise_update_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582996624,
      "name": "madvise_update_vma",
      "external": false,
      "loc": "mm/madvise.c:137",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_vma_anon_name",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582996624,
      "name": "madvise_update_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
int madvise_update_vma(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start, long unsigned int end, long unsigned int new_flags, struct anon_vma_name * anon_name)
```

```json
{
  "name": "madvise_update_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583204832,
      "name": "madvise_update_vma",
      "external": false,
      "loc": "mm/madvise.c:137",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_vma_anon_name",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583204832,
      "name": "madvise_update_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 704
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
int madvise_update_vma(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start, long unsigned int end, long unsigned int new_flags, struct anon_vma_name * anon_name)
```

```json
{
  "name": "madvise_update_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583440528,
      "name": "madvise_update_vma",
      "external": false,
      "loc": "mm/madvise.c:137",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_vma_anon_name",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583440528,
      "name": "madvise_update_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
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
int madvise_update_vma(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start, long unsigned int end, long unsigned int new_flags, struct anon_vma_name * anon_name)
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
