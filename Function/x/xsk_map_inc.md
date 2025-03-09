# Function: <code>xsk_map_inc</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xsk_map_inc(struct xsk_map * map)
```

```json
{
  "name": "xsk_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580946794,
      "name": "xsk_map_inc",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:19",
      "file": "kernel/bpf/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ],
      "caller_func": [
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580947696,
      "name": "xsk_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xsk_map_inc(struct xsk_map * map)
```

```json
{
  "name": "xsk_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591072270,
      "name": "xsk_map_inc",
      "external": true,
      "loc": "net/xdp/xskmap.c:14",
      "file": "net/xdp/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xskmap.c:xsk_map_update_elem"
      ],
      "caller_func": [
        "net/xdp/xsk.c:xsk_delete_from_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591072688,
      "name": "xsk_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int xsk_map_inc(struct xsk_map * map)
```

```json
{
  "name": "xsk_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492290516,
      "name": "xsk_map_inc",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:19",
      "file": "kernel/bpf/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ],
      "caller_func": [
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492291120,
      "name": "xsk_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int xsk_map_inc(struct xsk_map * map)
```

```json
{
  "name": "xsk_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226176120,
      "name": "xsk_map_inc",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:19",
      "file": "kernel/bpf/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ],
      "caller_func": [
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226177112,
      "name": "xsk_map_inc",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int xsk_map_inc(struct xsk_map * map)
```

```json
{
  "name": "xsk_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285523920,
      "name": "xsk_map_inc",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:19",
      "file": "kernel/bpf/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ],
      "caller_func": [
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285525088,
      "name": "xsk_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int xsk_map_inc(struct xsk_map * map)
```

```json
{
  "name": "xsk_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272422158,
      "name": "xsk_map_inc",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:19",
      "file": "kernel/bpf/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ],
      "caller_func": [
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272422936,
      "name": "xsk_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int xsk_map_inc(struct xsk_map * map)
```

```json
{
  "name": "xsk_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580915594,
      "name": "xsk_map_inc",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:19",
      "file": "kernel/bpf/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ],
      "caller_func": [
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916496,
      "name": "xsk_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int xsk_map_inc(struct xsk_map * map)
```

```json
{
  "name": "xsk_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580861658,
      "name": "xsk_map_inc",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:19",
      "file": "kernel/bpf/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ],
      "caller_func": [
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580862560,
      "name": "xsk_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int xsk_map_inc(struct xsk_map * map)
```

```json
{
  "name": "xsk_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580906842,
      "name": "xsk_map_inc",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:19",
      "file": "kernel/bpf/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ],
      "caller_func": [
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907744,
      "name": "xsk_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int xsk_map_inc(struct xsk_map * map)
```

```json
{
  "name": "xsk_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580965594,
      "name": "xsk_map_inc",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:19",
      "file": "kernel/bpf/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ],
      "caller_func": [
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580966496,
      "name": "xsk_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int xsk_map_inc(struct xsk_map * map)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int xsk_map_inc(struct xsk_map * map)
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
