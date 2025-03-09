# Function: <code>tcp_zerocopy_vm_insert_batch</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_zerocopy_vm_insert_batch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590026654,
      "name": "tcp_zerocopy_vm_insert_batch",
      "external": false,
      "loc": "net/ipv4/tcp.c:1745",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int tcp_zerocopy_vm_insert_batch(struct vm_area_struct * vma, struct page * * pages, unsigned int pages_to_map, long unsigned int * address, u32 * length, u32 * seq, struct tcp_zerocopy_receive * zc, u32 total_bytes_to_map)
```

```json
{
  "name": "tcp_zerocopy_vm_insert_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590060624,
      "name": "tcp_zerocopy_vm_insert_batch",
      "external": false,
      "loc": "net/ipv4/tcp.c:1975",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590060624,
      "name": "tcp_zerocopy_vm_insert_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int tcp_zerocopy_vm_insert_batch(struct vm_area_struct * vma, struct page * * pages, unsigned int pages_to_map, long unsigned int * address, u32 * length, u32 * seq, struct tcp_zerocopy_receive * zc, u32 total_bytes_to_map)
```

```json
{
  "name": "tcp_zerocopy_vm_insert_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589975392,
      "name": "tcp_zerocopy_vm_insert_batch",
      "external": false,
      "loc": "net/ipv4/tcp.c:1997",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589975392,
      "name": "tcp_zerocopy_vm_insert_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
int tcp_zerocopy_vm_insert_batch(struct vm_area_struct * vma, struct page * * pages, unsigned int pages_to_map, long unsigned int * address, u32 * length, u32 * seq, struct tcp_zerocopy_receive * zc, u32 total_bytes_to_map)
```

```json
{
  "name": "tcp_zerocopy_vm_insert_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590745040,
      "name": "tcp_zerocopy_vm_insert_batch",
      "external": false,
      "loc": "net/ipv4/tcp.c:1999",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590745040,
      "name": "tcp_zerocopy_vm_insert_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
int tcp_zerocopy_vm_insert_batch(struct vm_area_struct * vma, struct page * * pages, unsigned int pages_to_map, long unsigned int * address, u32 * length, u32 * seq, struct tcp_zerocopy_receive * zc, u32 total_bytes_to_map)
```

```json
{
  "name": "tcp_zerocopy_vm_insert_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592377088,
      "name": "tcp_zerocopy_vm_insert_batch",
      "external": false,
      "loc": "net/ipv4/tcp.c:2026",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592377088,
      "name": "tcp_zerocopy_vm_insert_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
int tcp_zerocopy_vm_insert_batch(struct vm_area_struct * vma, struct page * * pages, unsigned int pages_to_map, long unsigned int * address, u32 * length, u32 * seq, struct tcp_zerocopy_receive * zc, u32 total_bytes_to_map)
```

```json
{
  "name": "tcp_zerocopy_vm_insert_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594226640,
      "name": "tcp_zerocopy_vm_insert_batch",
      "external": false,
      "loc": "net/ipv4/tcp.c:2126",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594226640,
      "name": "tcp_zerocopy_vm_insert_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
int tcp_zerocopy_vm_insert_batch(struct vm_area_struct * vma, struct page * * pages, unsigned int pages_to_map, long unsigned int * address, u32 * length, u32 * seq, struct tcp_zerocopy_receive * zc, u32 total_bytes_to_map)
```

```json
{
  "name": "tcp_zerocopy_vm_insert_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594613472,
      "name": "tcp_zerocopy_vm_insert_batch",
      "external": false,
      "loc": "net/ipv4/tcp.c:1982",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594613472,
      "name": "tcp_zerocopy_vm_insert_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
int tcp_zerocopy_vm_insert_batch(struct vm_area_struct * vma, struct page * * pages, unsigned int pages_to_map, long unsigned int * address, u32 * length, u32 * seq, struct tcp_zerocopy_receive * zc, u32 total_bytes_to_map)
```

```json
{
  "name": "tcp_zerocopy_vm_insert_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595417104,
      "name": "tcp_zerocopy_vm_insert_batch",
      "external": false,
      "loc": "net/ipv4/tcp.c:1992",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595417104,
      "name": "tcp_zerocopy_vm_insert_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int tcp_zerocopy_vm_insert_batch(struct vm_area_struct * vma, struct page * * pages, unsigned int pages_to_map, long unsigned int * address, u32 * length, u32 * seq, struct tcp_zerocopy_receive * zc, u32 total_bytes_to_map)
```
</details>
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
