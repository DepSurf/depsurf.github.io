# Function: <code>__dev_kfree_skb_any</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
```

```json
{
  "name": "__dev_kfree_skb_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586287408,
      "name": "__dev_kfree_skb_any",
      "external": true,
      "loc": "net/core/dev.c:2333",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/netpoll.c:zap_completion_queue",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586287408,
      "name": "__dev_kfree_skb_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
```

```json
{
  "name": "__dev_kfree_skb_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586715232,
      "name": "__dev_kfree_skb_any",
      "external": true,
      "loc": "net/core/dev.c:2355",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586715232,
      "name": "__dev_kfree_skb_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
```

```json
{
  "name": "__dev_kfree_skb_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586901872,
      "name": "__dev_kfree_skb_any",
      "external": true,
      "loc": "net/core/dev.c:2487",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586901872,
      "name": "__dev_kfree_skb_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
```

```json
{
  "name": "__dev_kfree_skb_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587027120,
      "name": "__dev_kfree_skb_any",
      "external": true,
      "loc": "net/core/dev.c:2502",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587027120,
      "name": "__dev_kfree_skb_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
```

```json
{
  "name": "__dev_kfree_skb_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587525216,
      "name": "__dev_kfree_skb_any",
      "external": true,
      "loc": "net/core/dev.c:2529",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587525216,
      "name": "__dev_kfree_skb_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
```

```json
{
  "name": "__dev_kfree_skb_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587825520,
      "name": "__dev_kfree_skb_any",
      "external": true,
      "loc": "net/core/dev.c:2573",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587825520,
      "name": "__dev_kfree_skb_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
```

```json
{
  "name": "__dev_kfree_skb_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587958976,
      "name": "__dev_kfree_skb_any",
      "external": true,
      "loc": "net/core/dev.c:2808",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587958976,
      "name": "__dev_kfree_skb_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
```

```json
{
  "name": "__dev_kfree_skb_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588274384,
      "name": "__dev_kfree_skb_any",
      "external": true,
      "loc": "net/core/dev.c:2818",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588274384,
      "name": "__dev_kfree_skb_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
```

```json
{
  "name": "__dev_kfree_skb_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588480000,
      "name": "__dev_kfree_skb_any",
      "external": true,
      "loc": "net/core/dev.c:2736",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588480000,
      "name": "__dev_kfree_skb_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
```

```json
{
  "name": "__dev_kfree_skb_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589349744,
      "name": "__dev_kfree_skb_any",
      "external": true,
      "loc": "net/core/dev.c:3096",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/dev.c:validate_xmit_vlan",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589349744,
      "name": "__dev_kfree_skb_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
```

```json
{
  "name": "__dev_kfree_skb_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589353200,
      "name": "__dev_kfree_skb_any",
      "external": true,
      "loc": "net/core/dev.c:3121",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/dev.c:validate_xmit_vlan",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589353200,
      "name": "__dev_kfree_skb_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
```

```json
{
  "name": "__dev_kfree_skb_any",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589257719,
      "name": "__dev_kfree_skb_any",
      "external": true,
      "loc": "net/core/dev.c:3189",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:validate_xmit_vlan"
      ],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589256976,
      "name": "__dev_kfree_skb_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
```

```json
{
  "name": "__dev_kfree_skb_any",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589983383,
      "name": "__dev_kfree_skb_any",
      "external": true,
      "loc": "net/core/dev.c:3110",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:validate_xmit_vlan"
      ],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589982640,
      "name": "__dev_kfree_skb_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
```

```json
{
  "name": "__dev_kfree_skb_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591490592,
      "name": "__dev_kfree_skb_any",
      "external": true,
      "loc": "net/core/dev.c:3145",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591490592,
      "name": "__dev_kfree_skb_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
```

```json
{
  "name": "__dev_kfree_skb_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593259456,
      "name": "__dev_kfree_skb_any",
      "external": true,
      "loc": "net/core/dev.c:3130",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593259456,
      "name": "__dev_kfree_skb_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
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
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
```

```json
{
  "name": "__dev_kfree_skb_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502010128,
      "name": "__dev_kfree_skb_any",
      "external": true,
      "loc": "net/core/dev.c:2736",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi",
        "drivers/net/ethernet/freescale/fec_main.c:fec_restart",
        "drivers/net/ethernet/freescale/fec_main.c:fec_restart",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502010128,
      "name": "__dev_kfree_skb_any",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
```

```json
{
  "name": "__dev_kfree_skb_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234743968,
      "name": "__dev_kfree_skb_any",
      "external": true,
      "loc": "net/core/dev.c:2736",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi",
        "drivers/net/ethernet/freescale/fec_main.c:fec_restart",
        "drivers/net/ethernet/freescale/fec_main.c:fec_restart",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ethernet/ti/cpts.c:cpts_overflow_check",
        "drivers/net/ethernet/ti/cpts.c:cpts_fifo_read",
        "drivers/net/ethernet/ti/cpts.c:cpts_fifo_read",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_tx_handler",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234743968,
      "name": "__dev_kfree_skb_any",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
```

```json
{
  "name": "__dev_kfree_skb_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295422000,
      "name": "__dev_kfree_skb_any",
      "external": true,
      "loc": "net/core/dev.c:2736",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:validate_xmit_skb",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295422000,
      "name": "__dev_kfree_skb_any",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
```

```json
{
  "name": "__dev_kfree_skb_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278286300,
      "name": "__dev_kfree_skb_any",
      "external": true,
      "loc": "net/core/dev.c:2736",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:validate_xmit_skb",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278286300,
      "name": "__dev_kfree_skb_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
```

```json
{
  "name": "__dev_kfree_skb_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588086784,
      "name": "__dev_kfree_skb_any",
      "external": true,
      "loc": "net/core/dev.c:2736",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588086784,
      "name": "__dev_kfree_skb_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
```

```json
{
  "name": "__dev_kfree_skb_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587783296,
      "name": "__dev_kfree_skb_any",
      "external": true,
      "loc": "net/core/dev.c:2736",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:validate_xmit_skb",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587783296,
      "name": "__dev_kfree_skb_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
```

```json
{
  "name": "__dev_kfree_skb_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588418560,
      "name": "__dev_kfree_skb_any",
      "external": true,
      "loc": "net/core/dev.c:2736",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588418560,
      "name": "__dev_kfree_skb_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
```

```json
{
  "name": "__dev_kfree_skb_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588557424,
      "name": "__dev_kfree_skb_any",
      "external": true,
      "loc": "net/core/dev.c:2736",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588557424,
      "name": "__dev_kfree_skb_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void __dev_kfree_skb_any(struct sk_buff * skb, enum skb_free_reason reason)
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
