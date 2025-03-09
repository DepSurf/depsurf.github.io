# Function: <code>xsk_init_queue</code>

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
int xsk_init_queue(u32 entries, struct xsk_queue * * queue, bool umem_queue)
```

```json
{
  "name": "xsk_init_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589116080,
      "name": "xsk_init_queue",
      "external": false,
      "loc": "net/xdp/xsk.c:312",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589116080,
      "name": "xsk_init_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int xsk_init_queue(u32 entries, struct xsk_queue * * queue, bool umem_queue)
```

```json
{
  "name": "xsk_init_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589350144,
      "name": "xsk_init_queue",
      "external": false,
      "loc": "net/xdp/xsk.c:324",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589350144,
      "name": "xsk_init_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int xsk_init_queue(u32 entries, struct xsk_queue * * queue, bool umem_queue)
```

```json
{
  "name": "xsk_init_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589805984,
      "name": "xsk_init_queue",
      "external": false,
      "loc": "net/xdp/xsk.c:331",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589805984,
      "name": "xsk_init_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int xsk_init_queue(u32 entries, struct xsk_queue * * queue, bool umem_queue)
```

```json
{
  "name": "xsk_init_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590030208,
      "name": "xsk_init_queue",
      "external": false,
      "loc": "net/xdp/xsk.c:459",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590030208,
      "name": "xsk_init_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_init_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591067288,
      "name": "xsk_init_queue",
      "external": false,
      "loc": "net/xdp/xsk.c:453",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_init_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591131871,
      "name": "xsk_init_queue",
      "external": false,
      "loc": "net/xdp/xsk.c:625",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_init_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591062623,
      "name": "xsk_init_queue",
      "external": false,
      "loc": "net/xdp/xsk.c:718",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_init_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591905231,
      "name": "xsk_init_queue",
      "external": false,
      "loc": "net/xdp/xsk.c:718",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_init_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593625946,
      "name": "xsk_init_queue",
      "external": false,
      "loc": "net/xdp/xsk.c:737",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_init_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595555770,
      "name": "xsk_init_queue",
      "external": false,
      "loc": "net/xdp/xsk.c:747",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_init_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596064090,
      "name": "xsk_init_queue",
      "external": false,
      "loc": "net/xdp/xsk.c:748",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_init_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596931370,
      "name": "xsk_init_queue",
      "external": false,
      "loc": "net/xdp/xsk.c:1020",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int xsk_init_queue(u32 entries, struct xsk_queue * * queue, bool umem_queue)
```

```json
{
  "name": "xsk_init_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503780384,
      "name": "xsk_init_queue",
      "external": false,
      "loc": "net/xdp/xsk.c:459",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503780384,
      "name": "xsk_init_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int xsk_init_queue(u32 entries, struct xsk_queue * * queue, bool umem_queue)
```

```json
{
  "name": "xsk_init_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236400236,
      "name": "xsk_init_queue",
      "external": false,
      "loc": "net/xdp/xsk.c:459",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236400236,
      "name": "xsk_init_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int xsk_init_queue(u32 entries, struct xsk_queue * * queue, bool umem_queue)
```

```json
{
  "name": "xsk_init_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297621328,
      "name": "xsk_init_queue",
      "external": false,
      "loc": "net/xdp/xsk.c:459",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297621328,
      "name": "xsk_init_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int xsk_init_queue(u32 entries, struct xsk_queue * * queue, bool umem_queue)
```

```json
{
  "name": "xsk_init_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279689958,
      "name": "xsk_init_queue",
      "external": false,
      "loc": "net/xdp/xsk.c:459",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279689958,
      "name": "xsk_init_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int xsk_init_queue(u32 entries, struct xsk_queue * * queue, bool umem_queue)
```

```json
{
  "name": "xsk_init_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589633808,
      "name": "xsk_init_queue",
      "external": false,
      "loc": "net/xdp/xsk.c:459",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589633808,
      "name": "xsk_init_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int xsk_init_queue(u32 entries, struct xsk_queue * * queue, bool umem_queue)
```

```json
{
  "name": "xsk_init_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589358336,
      "name": "xsk_init_queue",
      "external": false,
      "loc": "net/xdp/xsk.c:459",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589358336,
      "name": "xsk_init_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int xsk_init_queue(u32 entries, struct xsk_queue * * queue, bool umem_queue)
```

```json
{
  "name": "xsk_init_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590075840,
      "name": "xsk_init_queue",
      "external": false,
      "loc": "net/xdp/xsk.c:459",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590075840,
      "name": "xsk_init_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int xsk_init_queue(u32 entries, struct xsk_queue * * queue, bool umem_queue)
```

```json
{
  "name": "xsk_init_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590125520,
      "name": "xsk_init_queue",
      "external": false,
      "loc": "net/xdp/xsk.c:459",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590125520,
      "name": "xsk_init_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int xsk_init_queue(u32 entries, struct xsk_queue * * queue, bool umem_queue)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
int xsk_init_queue(u32 entries, struct xsk_queue * * queue, bool umem_queue)
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
