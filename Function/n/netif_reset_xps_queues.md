# Function: <code>netif_reset_xps_queues</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```

```json
{
  "name": "netif_reset_xps_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586885616,
      "name": "netif_reset_xps_queues",
      "external": false,
      "loc": "net/core/dev.c:2040",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586885616,
      "name": "netif_reset_xps_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```

```json
{
  "name": "netif_reset_xps_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587010144,
      "name": "netif_reset_xps_queues",
      "external": false,
      "loc": "net/core/dev.c:2074",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587010144,
      "name": "netif_reset_xps_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```

```json
{
  "name": "netif_reset_xps_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587508720,
      "name": "netif_reset_xps_queues",
      "external": false,
      "loc": "net/core/dev.c:2094",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587508720,
      "name": "netif_reset_xps_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```

```json
{
  "name": "netif_reset_xps_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587812832,
      "name": "netif_reset_xps_queues",
      "external": false,
      "loc": "net/core/dev.c:2138",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587812832,
      "name": "netif_reset_xps_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```

```json
{
  "name": "netif_reset_xps_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587967488,
      "name": "netif_reset_xps_queues",
      "external": false,
      "loc": "net/core/dev.c:2229",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_unbind_sb_channel",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587967488,
      "name": "netif_reset_xps_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```

```json
{
  "name": "netif_reset_xps_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588266208,
      "name": "netif_reset_xps_queues",
      "external": false,
      "loc": "net/core/dev.c:2239",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_unbind_sb_channel",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588266208,
      "name": "netif_reset_xps_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```

```json
{
  "name": "netif_reset_xps_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588472528,
      "name": "netif_reset_xps_queues",
      "external": false,
      "loc": "net/core/dev.c:2157",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_unbind_sb_channel",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588472528,
      "name": "netif_reset_xps_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
  "name": "netif_reset_xps_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589386608,
      "name": "netif_reset_xps_queues",
      "external": false,
      "loc": "net/core/dev.c:2517",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_unbind_sb_channel",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_unbind_sb_channel",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589336688,
      "name": "netif_reset_xps_queues.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netif_reset_xps_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589354393,
      "name": "netif_reset_xps_queues",
      "external": false,
      "loc": "net/core/dev.c:2542",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_unbind_sb_channel",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_unbind_sb_channel",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589337504,
      "name": "netif_reset_xps_queues.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```

```json
{
  "name": "netif_reset_xps_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589234416,
      "name": "netif_reset_xps_queues",
      "external": false,
      "loc": "net/core/dev.c:2606",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_unbind_sb_channel",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589234416,
      "name": "netif_reset_xps_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```

```json
{
  "name": "netif_reset_xps_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589959488,
      "name": "netif_reset_xps_queues",
      "external": false,
      "loc": "net/core/dev.c:2481",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_unbind_sb_channel",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589959488,
      "name": "netif_reset_xps_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```

```json
{
  "name": "netif_reset_xps_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591495824,
      "name": "netif_reset_xps_queues",
      "external": false,
      "loc": "net/core/dev.c:2458",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_unbind_sb_channel",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591495824,
      "name": "netif_reset_xps_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```

```json
{
  "name": "netif_reset_xps_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593264208,
      "name": "netif_reset_xps_queues",
      "external": false,
      "loc": "net/core/dev.c:2443",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_unbind_sb_channel",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593264208,
      "name": "netif_reset_xps_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```

```json
{
  "name": "netif_reset_xps_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593721808,
      "name": "netif_reset_xps_queues",
      "external": false,
      "loc": "net/core/dev.c:2469",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_unbind_sb_channel",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593721808,
      "name": "netif_reset_xps_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```

```json
{
  "name": "netif_reset_xps_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594503072,
      "name": "netif_reset_xps_queues",
      "external": false,
      "loc": "net/core/dev.c:2472",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_unbind_sb_channel",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594503072,
      "name": "netif_reset_xps_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```

```json
{
  "name": "netif_reset_xps_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501992552,
      "name": "netif_reset_xps_queues",
      "external": false,
      "loc": "net/core/dev.c:2157",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_unbind_sb_channel",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501992552,
      "name": "netif_reset_xps_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```

```json
{
  "name": "netif_reset_xps_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234763932,
      "name": "netif_reset_xps_queues",
      "external": false,
      "loc": "net/core/dev.c:2157",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_unbind_sb_channel",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234763932,
      "name": "netif_reset_xps_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "netif_reset_xps_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295435248,
      "name": "netif_reset_xps_queues",
      "external": false,
      "loc": "net/core/dev.c:2157",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netif_reset_xps_queues_gt"
      ],
      "caller_func": [
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netif_reset_xps_queues_gt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295433488,
      "name": "netif_reset_xps_queues.part.0",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```

```json
{
  "name": "netif_reset_xps_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278302420,
      "name": "netif_reset_xps_queues",
      "external": false,
      "loc": "net/core/dev.c:2157",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_unbind_sb_channel",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278302420,
      "name": "netif_reset_xps_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```

```json
{
  "name": "netif_reset_xps_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588079312,
      "name": "netif_reset_xps_queues",
      "external": false,
      "loc": "net/core/dev.c:2157",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_unbind_sb_channel",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588079312,
      "name": "netif_reset_xps_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```

```json
{
  "name": "netif_reset_xps_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587792880,
      "name": "netif_reset_xps_queues",
      "external": false,
      "loc": "net/core/dev.c:2157",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_unbind_sb_channel",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587792880,
      "name": "netif_reset_xps_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```

```json
{
  "name": "netif_reset_xps_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588411088,
      "name": "netif_reset_xps_queues",
      "external": false,
      "loc": "net/core/dev.c:2157",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_unbind_sb_channel",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588411088,
      "name": "netif_reset_xps_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```

```json
{
  "name": "netif_reset_xps_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588549680,
      "name": "netif_reset_xps_queues",
      "external": false,
      "loc": "net/core/dev.c:2157",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netdev_unbind_sb_channel",
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_set_tc_queue",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588549680,
      "name": "netif_reset_xps_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void netif_reset_xps_queues(struct net_device * dev, u16 offset, u16 count)
```
</details>
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
