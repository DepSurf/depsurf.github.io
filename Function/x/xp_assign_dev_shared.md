# Function: <code>xp_assign_dev_shared</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int xp_assign_dev_shared(struct xsk_buff_pool * pool, struct xdp_umem * umem, struct net_device * dev, u16 queue_id)
```

```json
{
  "name": "xp_assign_dev_shared",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591140112,
      "name": "xp_assign_dev_shared",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:200",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591140112,
      "name": "xp_assign_dev_shared",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int xp_assign_dev_shared(struct xsk_buff_pool * pool, struct xdp_umem * umem, struct net_device * dev, u16 queue_id)
```

```json
{
  "name": "xp_assign_dev_shared",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591070896,
      "name": "xp_assign_dev_shared",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:194",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591070896,
      "name": "xp_assign_dev_shared",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int xp_assign_dev_shared(struct xsk_buff_pool * pool, struct xdp_umem * umem, struct net_device * dev, u16 queue_id)
```

```json
{
  "name": "xp_assign_dev_shared",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_assign_dev_shared",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:194",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592751552,
      "name": "xp_assign_dev_shared.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071591914016,
      "name": "xp_assign_dev_shared",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int xp_assign_dev_shared(struct xsk_buff_pool * pool, struct xdp_umem * umem, struct net_device * dev, u16 queue_id)
```

```json
{
  "name": "xp_assign_dev_shared",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_assign_dev_shared",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:215",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594638411,
      "name": "xp_assign_dev_shared.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071593636720,
      "name": "xp_assign_dev_shared",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int xp_assign_dev_shared(struct xsk_buff_pool * pool, struct xdp_sock * umem_xs, struct net_device * dev, u16 queue_id)
```

```json
{
  "name": "xp_assign_dev_shared",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_assign_dev_shared",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:215",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596367880,
      "name": "xp_assign_dev_shared.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071595567344,
      "name": "xp_assign_dev_shared",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int xp_assign_dev_shared(struct xsk_buff_pool * pool, struct xdp_sock * umem_xs, struct net_device * dev, u16 queue_id)
```

```json
{
  "name": "xp_assign_dev_shared",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_assign_dev_shared",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:218",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596897617,
      "name": "xp_assign_dev_shared.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071596075792,
      "name": "xp_assign_dev_shared",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int xp_assign_dev_shared(struct xsk_buff_pool * pool, struct xdp_sock * umem_xs, struct net_device * dev, u16 queue_id)
```

```json
{
  "name": "xp_assign_dev_shared",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_assign_dev_shared",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:242",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597822988,
      "name": "xp_assign_dev_shared.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071596944368,
      "name": "xp_assign_dev_shared",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int xp_assign_dev_shared(struct xsk_buff_pool * pool, struct xdp_umem * umem, struct net_device * dev, u16 queue_id)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xdp_sock * umem_xs</code>
</li>
<li>
<b>Param removed. </b>
<code>struct xdp_umem * umem</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
