# Function: <code>xdp_get_umem_from_qid</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xdp_umem * xdp_get_umem_from_qid(struct net_device * dev, u16 queue_id)
```

```json
{
  "name": "xdp_get_umem_from_qid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589355364,
      "name": "xdp_get_umem_from_qid",
      "external": true,
      "loc": "net/xdp/xdp_umem.c:60",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_assign_dev"
      ],
      "caller_func": [
        "net/core/ethtool.c:ethtool_set_channels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589355200,
      "name": "xdp_get_umem_from_qid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct xdp_umem * xdp_get_umem_from_qid(struct net_device * dev, u16 queue_id)
```

```json
{
  "name": "xdp_get_umem_from_qid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589811848,
      "name": "xdp_get_umem_from_qid",
      "external": true,
      "loc": "net/xdp/xdp_umem.c:63",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_assign_dev"
      ],
      "caller_func": [
        "net/core/ethtool.c:ethtool_set_channels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589811200,
      "name": "xdp_get_umem_from_qid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct xdp_umem * xdp_get_umem_from_qid(struct net_device * dev, u16 queue_id)
```

```json
{
  "name": "xdp_get_umem_from_qid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590036704,
      "name": "xdp_get_umem_from_qid",
      "external": true,
      "loc": "net/xdp/xdp_umem.c:70",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_assign_dev"
      ],
      "caller_func": [
        "net/core/ethtool.c:ethtool_set_channels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590036160,
      "name": "xdp_get_umem_from_qid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct xdp_umem * xdp_get_umem_from_qid(struct net_device * dev, u16 queue_id)
```

```json
{
  "name": "xdp_get_umem_from_qid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591069591,
      "name": "xdp_get_umem_from_qid",
      "external": true,
      "loc": "net/xdp/xdp_umem.c:70",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_assign_dev"
      ],
      "caller_func": [
        "net/ethtool/ioctl.c:ethtool_set_channels",
        "net/ethtool/channels.c:ethnl_set_channels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591068208,
      "name": "xdp_get_umem_from_qid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct xdp_umem * xdp_get_umem_from_qid(struct net_device * dev, u16 queue_id)
```

```json
{
  "name": "xdp_get_umem_from_qid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503791088,
      "name": "xdp_get_umem_from_qid",
      "external": true,
      "loc": "net/xdp/xdp_umem.c:70",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_assign_dev"
      ],
      "caller_func": [
        "net/core/ethtool.c:ethtool_set_channels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503790256,
      "name": "xdp_get_umem_from_qid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct xdp_umem * xdp_get_umem_from_qid(struct net_device * dev, u16 queue_id)
```

```json
{
  "name": "xdp_get_umem_from_qid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236410096,
      "name": "xdp_get_umem_from_qid",
      "external": true,
      "loc": "net/xdp/xdp_umem.c:70",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_assign_dev"
      ],
      "caller_func": [
        "net/core/ethtool.c:ethtool_set_channels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236409420,
      "name": "xdp_get_umem_from_qid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct xdp_umem * xdp_get_umem_from_qid(struct net_device * dev, u16 queue_id)
```

```json
{
  "name": "xdp_get_umem_from_qid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297632920,
      "name": "xdp_get_umem_from_qid",
      "external": true,
      "loc": "net/xdp/xdp_umem.c:70",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_assign_dev"
      ],
      "caller_func": [
        "net/core/ethtool.c:ethtool_set_channels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297632112,
      "name": "xdp_get_umem_from_qid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct xdp_umem * xdp_get_umem_from_qid(struct net_device * dev, u16 queue_id)
```

```json
{
  "name": "xdp_get_umem_from_qid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279696170,
      "name": "xdp_get_umem_from_qid",
      "external": true,
      "loc": "net/xdp/xdp_umem.c:70",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_assign_dev"
      ],
      "caller_func": [
        "net/core/ethtool.c:ethtool_set_channels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279695650,
      "name": "xdp_get_umem_from_qid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
struct xdp_umem * xdp_get_umem_from_qid(struct net_device * dev, u16 queue_id)
```

```json
{
  "name": "xdp_get_umem_from_qid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589640304,
      "name": "xdp_get_umem_from_qid",
      "external": true,
      "loc": "net/xdp/xdp_umem.c:70",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_assign_dev"
      ],
      "caller_func": [
        "net/core/ethtool.c:ethtool_set_channels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589639760,
      "name": "xdp_get_umem_from_qid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct xdp_umem * xdp_get_umem_from_qid(struct net_device * dev, u16 queue_id)
```

```json
{
  "name": "xdp_get_umem_from_qid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589364832,
      "name": "xdp_get_umem_from_qid",
      "external": true,
      "loc": "net/xdp/xdp_umem.c:70",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_assign_dev"
      ],
      "caller_func": [
        "net/core/ethtool.c:ethtool_set_channels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589364288,
      "name": "xdp_get_umem_from_qid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct xdp_umem * xdp_get_umem_from_qid(struct net_device * dev, u16 queue_id)
```

```json
{
  "name": "xdp_get_umem_from_qid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590082336,
      "name": "xdp_get_umem_from_qid",
      "external": true,
      "loc": "net/xdp/xdp_umem.c:70",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_assign_dev"
      ],
      "caller_func": [
        "net/core/ethtool.c:ethtool_set_channels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590081792,
      "name": "xdp_get_umem_from_qid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct xdp_umem * xdp_get_umem_from_qid(struct net_device * dev, u16 queue_id)
```

```json
{
  "name": "xdp_get_umem_from_qid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590132544,
      "name": "xdp_get_umem_from_qid",
      "external": true,
      "loc": "net/xdp/xdp_umem.c:70",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_assign_dev"
      ],
      "caller_func": [
        "net/core/ethtool.c:ethtool_set_channels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590132000,
      "name": "xdp_get_umem_from_qid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct xdp_umem * xdp_get_umem_from_qid(struct net_device * dev, u16 queue_id)
```
</details>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
struct xdp_umem * xdp_get_umem_from_qid(struct net_device * dev, u16 queue_id)
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
