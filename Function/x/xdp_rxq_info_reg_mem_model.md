# Function: <code>xdp_rxq_info_reg_mem_model</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info * xdp_rxq, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "xdp_rxq_info_reg_mem_model",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587997152,
      "name": "xdp_rxq_info_reg_mem_model",
      "external": true,
      "loc": "net/core/xdp.c:238",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587997152,
      "name": "xdp_rxq_info_reg_mem_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info * xdp_rxq, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "xdp_rxq_info_reg_mem_model",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588156688,
      "name": "xdp_rxq_info_reg_mem_model",
      "external": true,
      "loc": "net/core/xdp.c:252",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588156688,
      "name": "xdp_rxq_info_reg_mem_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info * xdp_rxq, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "xdp_rxq_info_reg_mem_model",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588478307,
      "name": "xdp_rxq_info_reg_mem_model",
      "external": true,
      "loc": "net/core/xdp.c:315",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588482755,
      "name": "xdp_rxq_info_reg_mem_model.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071588478224,
      "name": "xdp_rxq_info_reg_mem_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 711
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
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info * xdp_rxq, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "xdp_rxq_info_reg_mem_model",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588683616,
      "name": "xdp_rxq_info_reg_mem_model",
      "external": true,
      "loc": "net/core/xdp.c:289",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588683616,
      "name": "xdp_rxq_info_reg_mem_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 724
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
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info * xdp_rxq, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "xdp_rxq_info_reg_mem_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589550128,
      "name": "xdp_rxq_info_reg_mem_model",
      "external": true,
      "loc": "net/core/xdp.c:262",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589550128,
      "name": "xdp_rxq_info_reg_mem_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 741
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
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info * xdp_rxq, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "xdp_rxq_info_reg_mem_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589560208,
      "name": "xdp_rxq_info_reg_mem_model",
      "external": true,
      "loc": "net/core/xdp.c:263",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_create_page_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589560208,
      "name": "xdp_rxq_info_reg_mem_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info * xdp_rxq, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "xdp_rxq_info_reg_mem_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589459344,
      "name": "xdp_rxq_info_reg_mem_model",
      "external": true,
      "loc": "net/core/xdp.c:263",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_create_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589459344,
      "name": "xdp_rxq_info_reg_mem_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info * xdp_rxq, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "xdp_rxq_info_reg_mem_model",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590196064,
      "name": "xdp_rxq_info_reg_mem_model",
      "external": true,
      "loc": "net/core/xdp.c:264",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590195408,
      "name": "xdp_rxq_info_reg_mem_model.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 649
    },
    {
      "addr": 18446744071592703942,
      "name": "xdp_rxq_info_reg_mem_model.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071590196064,
      "name": "xdp_rxq_info_reg_mem_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info * xdp_rxq, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "xdp_rxq_info_reg_mem_model",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591758832,
      "name": "xdp_rxq_info_reg_mem_model",
      "external": true,
      "loc": "net/core/xdp.c:348",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591758832,
      "name": "xdp_rxq_info_reg_mem_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info * xdp_rxq, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "xdp_rxq_info_reg_mem_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593550464,
      "name": "xdp_rxq_info_reg_mem_model",
      "external": true,
      "loc": "net/core/xdp.c:348",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593550464,
      "name": "xdp_rxq_info_reg_mem_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info * xdp_rxq, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "xdp_rxq_info_reg_mem_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594019264,
      "name": "xdp_rxq_info_reg_mem_model",
      "external": true,
      "loc": "net/core/xdp.c:350",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594019264,
      "name": "xdp_rxq_info_reg_mem_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info * xdp_rxq, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "xdp_rxq_info_reg_mem_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594805392,
      "name": "xdp_rxq_info_reg_mem_model",
      "external": true,
      "loc": "net/core/xdp.c:350",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594805392,
      "name": "xdp_rxq_info_reg_mem_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info * xdp_rxq, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "xdp_rxq_info_reg_mem_model",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502239720,
      "name": "xdp_rxq_info_reg_mem_model",
      "external": true,
      "loc": "net/core/xdp.c:289",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502239720,
      "name": "xdp_rxq_info_reg_mem_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 792
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
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info * xdp_rxq, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "xdp_rxq_info_reg_mem_model",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234983436,
      "name": "xdp_rxq_info_reg_mem_model",
      "external": true,
      "loc": "net/core/xdp.c:289",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_create_xdp_rxqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234983436,
      "name": "xdp_rxq_info_reg_mem_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 800
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
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info * xdp_rxq, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "xdp_rxq_info_reg_mem_model",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295729952,
      "name": "xdp_rxq_info_reg_mem_model",
      "external": true,
      "loc": "net/core/xdp.c:289",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295729952,
      "name": "xdp_rxq_info_reg_mem_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1112
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
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info * xdp_rxq, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "xdp_rxq_info_reg_mem_model",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278480188,
      "name": "xdp_rxq_info_reg_mem_model",
      "external": true,
      "loc": "net/core/xdp.c:289",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278480188,
      "name": "xdp_rxq_info_reg_mem_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 714
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
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info * xdp_rxq, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "xdp_rxq_info_reg_mem_model",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588290352,
      "name": "xdp_rxq_info_reg_mem_model",
      "external": true,
      "loc": "net/core/xdp.c:289",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588290352,
      "name": "xdp_rxq_info_reg_mem_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 724
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
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info * xdp_rxq, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "xdp_rxq_info_reg_mem_model",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588003168,
      "name": "xdp_rxq_info_reg_mem_model",
      "external": true,
      "loc": "net/core/xdp.c:289",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588003168,
      "name": "xdp_rxq_info_reg_mem_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 724
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
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info * xdp_rxq, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "xdp_rxq_info_reg_mem_model",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588622176,
      "name": "xdp_rxq_info_reg_mem_model",
      "external": true,
      "loc": "net/core/xdp.c:289",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588622176,
      "name": "xdp_rxq_info_reg_mem_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 724
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
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info * xdp_rxq, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "xdp_rxq_info_reg_mem_model",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588760144,
      "name": "xdp_rxq_info_reg_mem_model",
      "external": true,
      "loc": "net/core/xdp.c:289",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588760144,
      "name": "xdp_rxq_info_reg_mem_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 749
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
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info * xdp_rxq, enum xdp_mem_type type, void * allocator)
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
