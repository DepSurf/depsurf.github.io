# Function: <code>pin_user_pages</code>

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
long int pin_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "pin_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581508848,
      "name": "pin_user_pages",
      "external": true,
      "loc": "mm/gup.c:3027",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sqe_buffer_register",
        "net/xdp/xdp_umem.c:xdp_umem_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581508848,
      "name": "pin_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
long int pin_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "pin_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581548752,
      "name": "pin_user_pages",
      "external": true,
      "loc": "mm/gup.c:2814",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sqe_buffer_register",
        "net/xdp/xdp_umem.c:xdp_umem_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581548752,
      "name": "pin_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
long int pin_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "pin_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581571936,
      "name": "pin_user_pages",
      "external": true,
      "loc": "mm/gup.c:2880",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sqe_buffer_register",
        "net/xdp/xdp_umem.c:xdp_umem_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571936,
      "name": "pin_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
long int pin_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "pin_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581836528,
      "name": "pin_user_pages",
      "external": true,
      "loc": "mm/gup.c:2975",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sqe_buffer_register",
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581836528,
      "name": "pin_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
long int pin_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "pin_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582228288,
      "name": "pin_user_pages",
      "external": true,
      "loc": "mm/gup.c:3132",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_pin_pages",
        "net/xdp/xdp_umem.c:xdp_umem_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582228288,
      "name": "pin_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
long int pin_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "pin_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582719456,
      "name": "pin_user_pages",
      "external": true,
      "loc": "mm/gup.c:3158",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rsrc.c:io_pin_pages",
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582719456,
      "name": "pin_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
long int pin_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "pin_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582935680,
      "name": "pin_user_pages",
      "external": true,
      "loc": "mm/gup.c:3364",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rsrc.c:io_pin_pages",
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582935680,
      "name": "pin_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
long int pin_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "pin_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583110928,
      "name": "pin_user_pages",
      "external": true,
      "loc": "mm/gup.c:3382",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rsrc.c:io_pin_pages",
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583110928,
      "name": "pin_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
long int pin_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct * * vmas</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
