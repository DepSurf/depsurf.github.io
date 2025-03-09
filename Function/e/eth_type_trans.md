# Function: <code>eth_type_trans</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586447744,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:154",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/dev.c:napi_gro_frags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586447744,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586893600,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:155",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:__dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586893600,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587087728,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:156",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:__dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587087728,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587216432,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:156",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:__dev_forward_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587216432,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587730928,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:156",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_build_skb",
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:__dev_forward_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587730928,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588065232,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:156",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:__dev_forward_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588065232,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588241792,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:157",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:__dev_forward_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588241792,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588632512,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:155",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:__dev_forward_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588632512,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588854880,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:155",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:__dev_forward_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588854880,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589738768,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:155",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:handle_incoming_queue",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:__dev_forward_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589738768,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589771888,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:155",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_build_skb",
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:handle_incoming_queue",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:__dev_forward_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589771888,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589675520,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:156",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:handle_incoming_queue",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/xdp.c:__xdp_build_skb_from_frame",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589675520,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590432528,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:154",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:handle_incoming_queue",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/xdp.c:__xdp_build_skb_from_frame",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590432528,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592032320,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:155",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:handle_incoming_queue",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/xdp.c:__xdp_build_skb_from_frame",
        "net/core/gro.c:napi_gro_frags",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592032320,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593848688,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:155",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:handle_incoming_queue",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/xdp.c:__xdp_build_skb_from_frame",
        "net/core/gro.c:napi_gro_frags",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593848688,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594223120,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:155",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/virtio_net.c:receive_buf",
        "drivers/net/xen-netfront.c:handle_incoming_queue",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/xdp.c:__xdp_build_skb_from_frame",
        "net/core/gro.c:napi_gro_frags",
        "net/bpf/test_run.c:bpf_prog_test_run_nf",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594223120,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595020480,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:155",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/netkit.c:netkit_xmit",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/virtio_net.c:receive_buf",
        "drivers/net/xen-netfront.c:handle_incoming_queue",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/xdp.c:__xdp_build_skb_from_frame",
        "net/core/gro.c:napi_gro_frags",
        "net/bpf/test_run.c:bpf_prog_test_run_nf",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595020480,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502439128,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:155",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:__dev_forward_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502439128,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235157540,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:155",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:__dev_forward_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235157540,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295986896,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:155",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:__dev_forward_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295986896,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278627986,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:155",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:__dev_forward_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278627986,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588461264,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:155",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:__dev_forward_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588461264,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588173952,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:155",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/vxlan.c:vxlan_rcv",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:__dev_forward_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_tunnel.c:ip_tunnel_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588173952,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588793440,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:155",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:__dev_forward_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588793440,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
__be16 eth_type_trans(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "eth_type_trans",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588934096,
      "name": "eth_type_trans",
      "external": true,
      "loc": "net/ethernet/eth.c:155",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:__dev_forward_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588934096,
      "name": "eth_type_trans",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
