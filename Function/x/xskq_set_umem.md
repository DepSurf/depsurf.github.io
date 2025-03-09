# Function: <code>xskq_set_umem</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void xskq_set_umem(struct xsk_queue * q, struct xdp_umem_props * umem_props)
```

```json
{
  "name": "xskq_set_umem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589122864,
      "name": "xskq_set_umem",
      "external": true,
      "loc": "net/xdp/xsk_queue.c:10",
      "file": "net/xdp/xsk_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589122864,
      "name": "xskq_set_umem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void xskq_set_umem(struct xsk_queue * q, u64 size, u64 chunk_mask)
```

```json
{
  "name": "xskq_set_umem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589357152,
      "name": "xskq_set_umem",
      "external": true,
      "loc": "net/xdp/xsk_queue.c:12",
      "file": "net/xdp/xsk_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589357152,
      "name": "xskq_set_umem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void xskq_set_umem(struct xsk_queue * q, u64 size, u64 chunk_mask)
```

```json
{
  "name": "xskq_set_umem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589814224,
      "name": "xskq_set_umem",
      "external": true,
      "loc": "net/xdp/xsk_queue.c:12",
      "file": "net/xdp/xsk_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589814224,
      "name": "xskq_set_umem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void xskq_set_umem(struct xsk_queue * q, u64 size, u64 chunk_mask)
```

```json
{
  "name": "xskq_set_umem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590039184,
      "name": "xskq_set_umem",
      "external": true,
      "loc": "net/xdp/xsk_queue.c:12",
      "file": "net/xdp/xsk_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590039184,
      "name": "xskq_set_umem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void xskq_set_umem(struct xsk_queue * q, u64 size, u64 chunk_mask)
```

```json
{
  "name": "xskq_set_umem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503793640,
      "name": "xskq_set_umem",
      "external": true,
      "loc": "net/xdp/xsk_queue.c:12",
      "file": "net/xdp/xsk_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503793640,
      "name": "xskq_set_umem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void xskq_set_umem(struct xsk_queue * q, u64 size, u64 chunk_mask)
```

```json
{
  "name": "xskq_set_umem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236412776,
      "name": "xskq_set_umem",
      "external": true,
      "loc": "net/xdp/xsk_queue.c:12",
      "file": "net/xdp/xsk_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236412776,
      "name": "xskq_set_umem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void xskq_set_umem(struct xsk_queue * q, u64 size, u64 chunk_mask)
```

```json
{
  "name": "xskq_set_umem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297636240,
      "name": "xskq_set_umem",
      "external": true,
      "loc": "net/xdp/xsk_queue.c:12",
      "file": "net/xdp/xsk_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297636240,
      "name": "xskq_set_umem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void xskq_set_umem(struct xsk_queue * q, u64 size, u64 chunk_mask)
```

```json
{
  "name": "xskq_set_umem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279698474,
      "name": "xskq_set_umem",
      "external": true,
      "loc": "net/xdp/xsk_queue.c:12",
      "file": "net/xdp/xsk_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279698474,
      "name": "xskq_set_umem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void xskq_set_umem(struct xsk_queue * q, u64 size, u64 chunk_mask)
```

```json
{
  "name": "xskq_set_umem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589642784,
      "name": "xskq_set_umem",
      "external": true,
      "loc": "net/xdp/xsk_queue.c:12",
      "file": "net/xdp/xsk_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589642784,
      "name": "xskq_set_umem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void xskq_set_umem(struct xsk_queue * q, u64 size, u64 chunk_mask)
```

```json
{
  "name": "xskq_set_umem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589367312,
      "name": "xskq_set_umem",
      "external": true,
      "loc": "net/xdp/xsk_queue.c:12",
      "file": "net/xdp/xsk_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589367312,
      "name": "xskq_set_umem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void xskq_set_umem(struct xsk_queue * q, u64 size, u64 chunk_mask)
```

```json
{
  "name": "xskq_set_umem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590084816,
      "name": "xskq_set_umem",
      "external": true,
      "loc": "net/xdp/xsk_queue.c:12",
      "file": "net/xdp/xsk_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590084816,
      "name": "xskq_set_umem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void xskq_set_umem(struct xsk_queue * q, u64 size, u64 chunk_mask)
```

```json
{
  "name": "xskq_set_umem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590135024,
      "name": "xskq_set_umem",
      "external": true,
      "loc": "net/xdp/xsk_queue.c:12",
      "file": "net/xdp/xsk_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590135024,
      "name": "xskq_set_umem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void xskq_set_umem(struct xsk_queue * q, struct xdp_umem_props * umem_props)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 size</code>
</li>
<li>
<b>Param added. </b>
<code>u64 chunk_mask</code>
</li>
<li>
<b>Param removed. </b>
<code>struct xdp_umem_props * umem_props</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void xskq_set_umem(struct xsk_queue * q, u64 size, u64 chunk_mask)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
