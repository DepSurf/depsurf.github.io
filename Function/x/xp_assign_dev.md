# Function: <code>xp_assign_dev</code>

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
int xp_assign_dev(struct xsk_buff_pool * pool, struct net_device * dev, u16 queue_id, u16 flags)
```

```json
{
  "name": "xp_assign_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591140080,
      "name": "xp_assign_dev",
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
      "addr": 18446744071591140080,
      "name": "xp_assign_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int xp_assign_dev(struct xsk_buff_pool * pool, struct net_device * netdev, u16 queue_id, u16 flags)
```

```json
{
  "name": "xp_assign_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591070416,
      "name": "xp_assign_dev",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:122",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk_buff_pool.c:xp_assign_dev_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591070416,
      "name": "xp_assign_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
int xp_assign_dev(struct xsk_buff_pool * pool, struct net_device * netdev, u16 queue_id, u16 flags)
```

```json
{
  "name": "xp_assign_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_assign_dev",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:122",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk_buff_pool.c:xp_assign_dev_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592751531,
      "name": "xp_assign_dev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591913504,
      "name": "xp_assign_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
int xp_assign_dev(struct xsk_buff_pool * pool, struct net_device * netdev, u16 queue_id, u16 flags)
```

```json
{
  "name": "xp_assign_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_assign_dev",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:143",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk_buff_pool.c:xp_assign_dev_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594638390,
      "name": "xp_assign_dev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593636176,
      "name": "xp_assign_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int xp_assign_dev(struct xsk_buff_pool * pool, struct net_device * netdev, u16 queue_id, u16 flags)
```

```json
{
  "name": "xp_assign_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_assign_dev",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:143",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk_buff_pool.c:xp_assign_dev_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596367859,
      "name": "xp_assign_dev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071595566784,
      "name": "xp_assign_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int xp_assign_dev(struct xsk_buff_pool * pool, struct net_device * netdev, u16 queue_id, u16 flags)
```

```json
{
  "name": "xp_assign_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_assign_dev",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:147",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk_buff_pool.c:xp_assign_dev_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596897596,
      "name": "xp_assign_dev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071596075232,
      "name": "xp_assign_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
int xp_assign_dev(struct xsk_buff_pool * pool, struct net_device * netdev, u16 queue_id, u16 flags)
```

```json
{
  "name": "xp_assign_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_assign_dev",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:163",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk_buff_pool.c:xp_assign_dev_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597822967,
      "name": "xp_assign_dev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071596943776,
      "name": "xp_assign_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 567
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
int xp_assign_dev(struct xsk_buff_pool * pool, struct net_device * dev, u16 queue_id, u16 flags)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net_device * netdev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct net_device * dev</code>
</li>
</ul>
</details>
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
