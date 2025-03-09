# Function: <code>xdp_do_redirect</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int xdp_do_redirect(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587651744,
      "name": "xdp_do_redirect",
      "external": true,
      "loc": "net/core/filter.c:2645",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587651744,
      "name": "xdp_do_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 960
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
int xdp_do_redirect(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587972224,
      "name": "xdp_do_redirect",
      "external": true,
      "loc": "net/core/filter.c:3285",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587972224,
      "name": "xdp_do_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1221
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
int xdp_do_redirect(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588127264,
      "name": "xdp_do_redirect",
      "external": true,
      "loc": "net/core/filter.c:3501",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588127264,
      "name": "xdp_do_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 722
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
int xdp_do_redirect(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588448736,
      "name": "xdp_do_redirect",
      "external": true,
      "loc": "net/core/filter.c:3630",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588448736,
      "name": "xdp_do_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 545
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
int xdp_do_redirect(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588655280,
      "name": "xdp_do_redirect",
      "external": true,
      "loc": "net/core/filter.c:3636",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588655280,
      "name": "xdp_do_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
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
int xdp_do_redirect(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589532336,
      "name": "xdp_do_redirect",
      "external": true,
      "loc": "net/core/filter.c:3573",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589532336,
      "name": "xdp_do_redirect",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int xdp_do_redirect(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589539440,
      "name": "xdp_do_redirect",
      "external": true,
      "loc": "net/core/filter.c:3980",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "drivers/net/tun.c:tun_xdp_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589539440,
      "name": "xdp_do_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
int xdp_do_redirect(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589437136,
      "name": "xdp_do_redirect",
      "external": true,
      "loc": "net/core/filter.c:3926",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "drivers/net/tun.c:tun_xdp_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589437136,
      "name": "xdp_do_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
int xdp_do_redirect(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590169184,
      "name": "xdp_do_redirect",
      "external": true,
      "loc": "net/core/filter.c:3964",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "drivers/net/tun.c:tun_xdp_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590169184,
      "name": "xdp_do_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
int xdp_do_redirect(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591738944,
      "name": "xdp_do_redirect",
      "external": true,
      "loc": "net/core/filter.c:4268",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "drivers/net/tun.c:tun_xdp_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591738944,
      "name": "xdp_do_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1072
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
int xdp_do_redirect(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593528224,
      "name": "xdp_do_redirect",
      "external": true,
      "loc": "net/core/filter.c:4282",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "drivers/net/tun.c:tun_xdp_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593528224,
      "name": "xdp_do_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1063
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
int xdp_do_redirect(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593993840,
      "name": "xdp_do_redirect",
      "external": true,
      "loc": "net/core/filter.c:4336",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "drivers/net/tun.c:tun_xdp_act",
        "drivers/net/virtio_net.c:virtnet_xdp_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593993840,
      "name": "xdp_do_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1047
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
int xdp_do_redirect(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594778048,
      "name": "xdp_do_redirect",
      "external": true,
      "loc": "net/core/filter.c:4415",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "drivers/net/tun.c:tun_xdp_act",
        "drivers/net/virtio_net.c:virtnet_xdp_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594778048,
      "name": "xdp_do_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1028
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
int xdp_do_redirect(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502221104,
      "name": "xdp_do_redirect",
      "external": true,
      "loc": "net/core/filter.c:3636",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502221104,
      "name": "xdp_do_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
int xdp_do_redirect(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234946960,
      "name": "xdp_do_redirect",
      "external": true,
      "loc": "net/core/filter.c:3636",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_act",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234946960,
      "name": "xdp_do_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
int xdp_do_redirect(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295681696,
      "name": "xdp_do_redirect",
      "external": true,
      "loc": "net/core/filter.c:3636",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295681696,
      "name": "xdp_do_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 820
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
int xdp_do_redirect(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278452878,
      "name": "xdp_do_redirect",
      "external": true,
      "loc": "net/core/filter.c:3636",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278452878,
      "name": "xdp_do_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
int xdp_do_redirect(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588262016,
      "name": "xdp_do_redirect",
      "external": true,
      "loc": "net/core/filter.c:3636",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588262016,
      "name": "xdp_do_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
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
int xdp_do_redirect(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587974832,
      "name": "xdp_do_redirect",
      "external": true,
      "loc": "net/core/filter.c:3636",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587974832,
      "name": "xdp_do_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
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
int xdp_do_redirect(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588593840,
      "name": "xdp_do_redirect",
      "external": true,
      "loc": "net/core/filter.c:3636",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588593840,
      "name": "xdp_do_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
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
int xdp_do_redirect(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588731456,
      "name": "xdp_do_redirect",
      "external": true,
      "loc": "net/core/filter.c:3636",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588731456,
      "name": "xdp_do_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 613
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int xdp_do_redirect(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```
</details>
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
