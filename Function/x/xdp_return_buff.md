# Function: <code>xdp_return_buff</code>

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
void xdp_return_buff(struct xdp_buff * xdp)
```

```json
{
  "name": "xdp_return_buff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587998688,
      "name": "xdp_return_buff",
      "external": true,
      "loc": "net/core/xdp.c:361",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587998688,
      "name": "xdp_return_buff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xdp_return_buff(struct xdp_buff * xdp)
```

```json
{
  "name": "xdp_return_buff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588158560,
      "name": "xdp_return_buff",
      "external": true,
      "loc": "net/core/xdp.c:376",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": [
        "net/xdp/xsk.c:xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588158288,
      "name": "xdp_return_buff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xdp_return_buff(struct xdp_buff * xdp)
```

```json
{
  "name": "xdp_return_buff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588480748,
      "name": "xdp_return_buff",
      "external": true,
      "loc": "net/core/xdp.c:448",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": [
        "net/xdp/xsk.c:xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588480464,
      "name": "xdp_return_buff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xdp_return_buff(struct xdp_buff * xdp)
```

```json
{
  "name": "xdp_return_buff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588685900,
      "name": "xdp_return_buff",
      "external": true,
      "loc": "net/core/xdp.c:415",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": [
        "net/xdp/xsk.c:xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588685616,
      "name": "xdp_return_buff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void xdp_return_buff(struct xdp_buff * xdp)
```

```json
{
  "name": "xdp_return_buff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589553344,
      "name": "xdp_return_buff",
      "external": true,
      "loc": "net/core/xdp.c:383",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_run_prog",
        "kernel/bpf/devmap.c:dev_map_run_prog",
        "net/xdp/xsk.c:__xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589553344,
      "name": "xdp_return_buff",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void xdp_return_buff(struct xdp_buff * xdp)
```

```json
{
  "name": "xdp_return_buff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589562464,
      "name": "xdp_return_buff",
      "external": true,
      "loc": "net/core/xdp.c:441",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_run_prog",
        "kernel/bpf/devmap.c:dev_map_run_prog",
        "net/xdp/xsk.c:__xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589562464,
      "name": "xdp_return_buff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void xdp_return_buff(struct xdp_buff * xdp)
```

```json
{
  "name": "xdp_return_buff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589460752,
      "name": "xdp_return_buff",
      "external": true,
      "loc": "net/core/xdp.c:442",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_run_prog",
        "kernel/bpf/devmap.c:dev_map_run_prog",
        "net/xdp/xsk.c:__xsk_map_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589460752,
      "name": "xdp_return_buff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void xdp_return_buff(struct xdp_buff * xdp)
```

```json
{
  "name": "xdp_return_buff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590198416,
      "name": "xdp_return_buff",
      "external": true,
      "loc": "net/core/xdp.c:443",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_map_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590198416,
      "name": "xdp_return_buff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void xdp_return_buff(struct xdp_buff * xdp)
```

```json
{
  "name": "xdp_return_buff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591763872,
      "name": "xdp_return_buff",
      "external": true,
      "loc": "net/core/xdp.c:515",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_map_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591763872,
      "name": "xdp_return_buff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void xdp_return_buff(struct xdp_buff * xdp)
```

```json
{
  "name": "xdp_return_buff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593554464,
      "name": "xdp_return_buff",
      "external": true,
      "loc": "net/core/xdp.c:513",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_map_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593554464,
      "name": "xdp_return_buff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void xdp_return_buff(struct xdp_buff * xdp)
```

```json
{
  "name": "xdp_return_buff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594023440,
      "name": "xdp_return_buff",
      "external": true,
      "loc": "net/core/xdp.c:515",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_map_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594023440,
      "name": "xdp_return_buff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void xdp_return_buff(struct xdp_buff * xdp)
```

```json
{
  "name": "xdp_return_buff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594810160,
      "name": "xdp_return_buff",
      "external": true,
      "loc": "net/core/xdp.c:515",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_map_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594810160,
      "name": "xdp_return_buff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void xdp_return_buff(struct xdp_buff * xdp)
```

```json
{
  "name": "xdp_return_buff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502243668,
      "name": "xdp_return_buff",
      "external": true,
      "loc": "net/core/xdp.c:415",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": [
        "net/xdp/xsk.c:xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502243384,
      "name": "xdp_return_buff",
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
void xdp_return_buff(struct xdp_buff * xdp)
```

```json
{
  "name": "xdp_return_buff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234988892,
      "name": "xdp_return_buff",
      "external": true,
      "loc": "net/core/xdp.c:415",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": [
        "net/xdp/xsk.c:xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234988600,
      "name": "xdp_return_buff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void xdp_return_buff(struct xdp_buff * xdp)
```

```json
{
  "name": "xdp_return_buff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295736348,
      "name": "xdp_return_buff",
      "external": true,
      "loc": "net/core/xdp.c:415",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": [
        "net/xdp/xsk.c:xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295736016,
      "name": "xdp_return_buff",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void xdp_return_buff(struct xdp_buff * xdp)
```

```json
{
  "name": "xdp_return_buff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278484258,
      "name": "xdp_return_buff",
      "external": true,
      "loc": "net/core/xdp.c:415",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": [
        "net/xdp/xsk.c:xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278484006,
      "name": "xdp_return_buff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void xdp_return_buff(struct xdp_buff * xdp)
```

```json
{
  "name": "xdp_return_buff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588292636,
      "name": "xdp_return_buff",
      "external": true,
      "loc": "net/core/xdp.c:415",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": [
        "net/xdp/xsk.c:xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588292352,
      "name": "xdp_return_buff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void xdp_return_buff(struct xdp_buff * xdp)
```

```json
{
  "name": "xdp_return_buff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588005452,
      "name": "xdp_return_buff",
      "external": true,
      "loc": "net/core/xdp.c:415",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": [
        "net/xdp/xsk.c:xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588005168,
      "name": "xdp_return_buff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void xdp_return_buff(struct xdp_buff * xdp)
```

```json
{
  "name": "xdp_return_buff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588624460,
      "name": "xdp_return_buff",
      "external": true,
      "loc": "net/core/xdp.c:415",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": [
        "net/xdp/xsk.c:xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588624176,
      "name": "xdp_return_buff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void xdp_return_buff(struct xdp_buff * xdp)
```

```json
{
  "name": "xdp_return_buff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588762476,
      "name": "xdp_return_buff",
      "external": true,
      "loc": "net/core/xdp.c:415",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": [
        "net/xdp/xsk.c:xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588762192,
      "name": "xdp_return_buff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void xdp_return_buff(struct xdp_buff * xdp)
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
