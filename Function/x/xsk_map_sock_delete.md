# Function: <code>xsk_map_sock_delete</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock * xs, struct xdp_sock * * map_entry)
```

```json
{
  "name": "xsk_map_sock_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580946352,
      "name": "xsk_map_sock_delete",
      "external": false,
      "loc": "kernel/bpf/xskmap.c:66",
      "file": "kernel/bpf/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_try_sock_delete",
        "kernel/bpf/xskmap.c:xsk_map_delete_elem",
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580946352,
      "name": "xsk_map_sock_delete",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock * xs, struct xdp_sock * * map_entry)
```

```json
{
  "name": "xsk_map_sock_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591071824,
      "name": "xsk_map_sock_delete",
      "external": false,
      "loc": "net/xdp/xskmap.c:59",
      "file": "net/xdp/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xskmap.c:xsk_map_try_sock_delete",
        "net/xdp/xskmap.c:xsk_map_delete_elem",
        "net/xdp/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591071824,
      "name": "xsk_map_sock_delete",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock * xs, struct xdp_sock * * map_entry)
```

```json
{
  "name": "xsk_map_sock_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591135328,
      "name": "xsk_map_sock_delete",
      "external": false,
      "loc": "net/xdp/xskmap.c:44",
      "file": "net/xdp/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xskmap.c:xsk_map_try_sock_delete",
        "net/xdp/xskmap.c:xsk_map_delete_elem",
        "net/xdp/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591135328,
      "name": "xsk_map_sock_delete",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock * xs, struct xdp_sock * * map_entry)
```

```json
{
  "name": "xsk_map_sock_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591066256,
      "name": "xsk_map_sock_delete",
      "external": false,
      "loc": "net/xdp/xskmap.c:44",
      "file": "net/xdp/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xskmap.c:xsk_map_try_sock_delete",
        "net/xdp/xskmap.c:xsk_map_delete_elem",
        "net/xdp/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591066256,
      "name": "xsk_map_sock_delete",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock * xs, struct xdp_sock * * map_entry)
```

```json
{
  "name": "xsk_map_sock_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591909152,
      "name": "xsk_map_sock_delete",
      "external": false,
      "loc": "net/xdp/xskmap.c:44",
      "file": "net/xdp/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xskmap.c:xsk_map_try_sock_delete",
        "net/xdp/xskmap.c:xsk_map_delete_elem",
        "net/xdp/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591909152,
      "name": "xsk_map_sock_delete",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock * xs, struct xdp_sock * * map_entry)
```

```json
{
  "name": "xsk_map_sock_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593630048,
      "name": "xsk_map_sock_delete",
      "external": false,
      "loc": "net/xdp/xskmap.c:46",
      "file": "net/xdp/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xskmap.c:xsk_map_try_sock_delete",
        "net/xdp/xskmap.c:xsk_map_delete_elem",
        "net/xdp/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593630048,
      "name": "xsk_map_sock_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void xsk_map_sock_delete(struct xdp_sock * xs, struct xdp_sock * * map_entry)
```

```json
{
  "name": "xsk_map_sock_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595560192,
      "name": "xsk_map_sock_delete",
      "external": false,
      "loc": "net/xdp/xskmap.c:46",
      "file": "net/xdp/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xskmap.c:xsk_map_try_sock_delete",
        "net/xdp/xskmap.c:xsk_map_delete_elem",
        "net/xdp/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595560192,
      "name": "xsk_map_sock_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void xsk_map_sock_delete(struct xdp_sock * xs, struct xdp_sock * * map_entry)
```

```json
{
  "name": "xsk_map_sock_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596068576,
      "name": "xsk_map_sock_delete",
      "external": false,
      "loc": "net/xdp/xskmap.c:49",
      "file": "net/xdp/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xskmap.c:xsk_map_try_sock_delete",
        "net/xdp/xskmap.c:xsk_map_delete_elem",
        "net/xdp/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596068576,
      "name": "xsk_map_sock_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void xsk_map_sock_delete(struct xdp_sock * xs, struct xdp_sock * * map_entry)
```

```json
{
  "name": "xsk_map_sock_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596936576,
      "name": "xsk_map_sock_delete",
      "external": false,
      "loc": "net/xdp/xskmap.c:49",
      "file": "net/xdp/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xskmap.c:xsk_map_try_sock_delete",
        "net/xdp/xskmap.c:xsk_map_delete_elem",
        "net/xdp/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596936576,
      "name": "xsk_map_sock_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock * xs, struct xdp_sock * * map_entry)
```

```json
{
  "name": "xsk_map_sock_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492289784,
      "name": "xsk_map_sock_delete",
      "external": false,
      "loc": "kernel/bpf/xskmap.c:66",
      "file": "kernel/bpf/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_try_sock_delete",
        "kernel/bpf/xskmap.c:xsk_map_delete_elem",
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492289784,
      "name": "xsk_map_sock_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
void xsk_map_sock_delete(struct xdp_sock * xs, struct xdp_sock * * map_entry)
```

```json
{
  "name": "xsk_map_sock_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226175784,
      "name": "xsk_map_sock_delete",
      "external": false,
      "loc": "kernel/bpf/xskmap.c:66",
      "file": "kernel/bpf/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_try_sock_delete",
        "kernel/bpf/xskmap.c:xsk_map_delete_elem",
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226175784,
      "name": "xsk_map_sock_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void xsk_map_sock_delete(struct xdp_sock * xs, struct xdp_sock * * map_entry)
```

```json
{
  "name": "xsk_map_sock_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285523024,
      "name": "xsk_map_sock_delete",
      "external": false,
      "loc": "kernel/bpf/xskmap.c:66",
      "file": "kernel/bpf/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_try_sock_delete",
        "kernel/bpf/xskmap.c:xsk_map_delete_elem",
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285523024,
      "name": "xsk_map_sock_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
void xsk_map_sock_delete(struct xdp_sock * xs, struct xdp_sock * * map_entry)
```

```json
{
  "name": "xsk_map_sock_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272421728,
      "name": "xsk_map_sock_delete",
      "external": false,
      "loc": "kernel/bpf/xskmap.c:66",
      "file": "kernel/bpf/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_try_sock_delete",
        "kernel/bpf/xskmap.c:xsk_map_delete_elem",
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272421728,
      "name": "xsk_map_sock_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void xsk_map_sock_delete(struct xdp_sock * xs, struct xdp_sock * * map_entry)
```

```json
{
  "name": "xsk_map_sock_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580915152,
      "name": "xsk_map_sock_delete",
      "external": false,
      "loc": "kernel/bpf/xskmap.c:66",
      "file": "kernel/bpf/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_try_sock_delete",
        "kernel/bpf/xskmap.c:xsk_map_delete_elem",
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915152,
      "name": "xsk_map_sock_delete",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock * xs, struct xdp_sock * * map_entry)
```

```json
{
  "name": "xsk_map_sock_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580861216,
      "name": "xsk_map_sock_delete",
      "external": false,
      "loc": "kernel/bpf/xskmap.c:66",
      "file": "kernel/bpf/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_try_sock_delete",
        "kernel/bpf/xskmap.c:xsk_map_delete_elem",
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580861216,
      "name": "xsk_map_sock_delete",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock * xs, struct xdp_sock * * map_entry)
```

```json
{
  "name": "xsk_map_sock_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580906400,
      "name": "xsk_map_sock_delete",
      "external": false,
      "loc": "kernel/bpf/xskmap.c:66",
      "file": "kernel/bpf/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_try_sock_delete",
        "kernel/bpf/xskmap.c:xsk_map_delete_elem",
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580906400,
      "name": "xsk_map_sock_delete",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock * xs, struct xdp_sock * * map_entry)
```

```json
{
  "name": "xsk_map_sock_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580965152,
      "name": "xsk_map_sock_delete",
      "external": false,
      "loc": "kernel/bpf/xskmap.c:66",
      "file": "kernel/bpf/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_try_sock_delete",
        "kernel/bpf/xskmap.c:xsk_map_delete_elem",
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580965152,
      "name": "xsk_map_sock_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void xsk_map_sock_delete(struct xdp_sock * xs, struct xdp_sock * * map_entry)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
