# Function: <code>do_vma_munmap</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_vma_munmap(struct vma_iterator * vmi, struct vm_area_struct * vma, long unsigned int start, long unsigned int end, struct list_head * uf, bool unlock)
```

```json
{
  "name": "do_vma_munmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583037157,
      "name": "do_vma_munmap",
      "external": true,
      "loc": "mm/mmap.c:3020",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__do_sys_brk"
      ],
      "caller_func": [
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583032064,
      "name": "do_vma_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int do_vma_munmap(struct vma_iterator * vmi, struct vm_area_struct * vma, long unsigned int start, long unsigned int end, struct list_head * uf, bool unlock)
```

```json
{
  "name": "do_vma_munmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583218722,
      "name": "do_vma_munmap",
      "external": true,
      "loc": "mm/mmap.c:3109",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__do_sys_brk"
      ],
      "caller_func": [
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583213280,
      "name": "do_vma_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int do_vma_munmap(struct vma_iterator * vmi, struct vm_area_struct * vma, long unsigned int start, long unsigned int end, struct list_head * uf, bool unlock)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
