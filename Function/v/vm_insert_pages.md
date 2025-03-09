# Function: <code>vm_insert_pages</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int vm_insert_pages(struct vm_area_struct * vma, long unsigned int addr, struct page * * pages, long unsigned int * num)
```

```json
{
  "name": "vm_insert_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581544672,
      "name": "vm_insert_pages",
      "external": true,
      "loc": "mm/memory.c:1589",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581544672,
      "name": "vm_insert_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int vm_insert_pages(struct vm_area_struct * vma, long unsigned int addr, struct page * * pages, long unsigned int * num)
```

```json
{
  "name": "vm_insert_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581587888,
      "name": "vm_insert_pages",
      "external": true,
      "loc": "mm/memory.c:1763",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch",
        "net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581587888,
      "name": "vm_insert_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int vm_insert_pages(struct vm_area_struct * vma, long unsigned int addr, struct page * * pages, long unsigned int * num)
```

```json
{
  "name": "vm_insert_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581609856,
      "name": "vm_insert_pages",
      "external": true,
      "loc": "mm/memory.c:1781",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch",
        "net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581609856,
      "name": "vm_insert_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int vm_insert_pages(struct vm_area_struct * vma, long unsigned int addr, struct page * * pages, long unsigned int * num)
```

```json
{
  "name": "vm_insert_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581886032,
      "name": "vm_insert_pages",
      "external": true,
      "loc": "mm/memory.c:1876",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch",
        "net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581886032,
      "name": "vm_insert_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int vm_insert_pages(struct vm_area_struct * vma, long unsigned int addr, struct page * * pages, long unsigned int * num)
```

```json
{
  "name": "vm_insert_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582276496,
      "name": "vm_insert_pages",
      "external": true,
      "loc": "mm/memory.c:1969",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch",
        "net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582276496,
      "name": "vm_insert_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int vm_insert_pages(struct vm_area_struct * vma, long unsigned int addr, struct page * * pages, long unsigned int * num)
```

```json
{
  "name": "vm_insert_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582768944,
      "name": "vm_insert_pages",
      "external": true,
      "loc": "mm/memory.c:1940",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch",
        "net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582768944,
      "name": "vm_insert_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int vm_insert_pages(struct vm_area_struct * vma, long unsigned int addr, struct page * * pages, long unsigned int * num)
```

```json
{
  "name": "vm_insert_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582984320,
      "name": "vm_insert_pages",
      "external": true,
      "loc": "mm/memory.c:1960",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch",
        "net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582984320,
      "name": "vm_insert_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1072
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
int vm_insert_pages(struct vm_area_struct * vma, long unsigned int addr, struct page * * pages, long unsigned int * num)
```

```json
{
  "name": "vm_insert_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583159744,
      "name": "vm_insert_pages",
      "external": true,
      "loc": "mm/memory.c:1996",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch",
        "net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583159744,
      "name": "vm_insert_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 988
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int vm_insert_pages(struct vm_area_struct * vma, long unsigned int addr, struct page * * pages, long unsigned int * num)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
