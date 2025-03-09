# Function: <code>xdp_do_generic_redirect</code>

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
int xdp_do_generic_redirect(struct net_device * dev, struct sk_buff * skb, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_generic_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587661392,
      "name": "xdp_do_generic_redirect",
      "external": true,
      "loc": "net/core/filter.c:2731",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:do_xdp_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587661392,
      "name": "xdp_do_generic_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
int xdp_do_generic_redirect(struct net_device * dev, struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_generic_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587975312,
      "name": "xdp_do_generic_redirect",
      "external": true,
      "loc": "net/core/filter.c:3368",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587975312,
      "name": "xdp_do_generic_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 879
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
int xdp_do_generic_redirect(struct net_device * dev, struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_generic_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588125728,
      "name": "xdp_do_generic_redirect",
      "external": true,
      "loc": "net/core/filter.c:3560",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588125728,
      "name": "xdp_do_generic_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 934
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
int xdp_do_generic_redirect(struct net_device * dev, struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_generic_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588444288,
      "name": "xdp_do_generic_redirect",
      "external": true,
      "loc": "net/core/filter.c:3684",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588444288,
      "name": "xdp_do_generic_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
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
int xdp_do_generic_redirect(struct net_device * dev, struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_generic_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588653840,
      "name": "xdp_do_generic_redirect",
      "external": true,
      "loc": "net/core/filter.c:3691",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588653840,
      "name": "xdp_do_generic_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 817
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
int xdp_do_generic_redirect(struct net_device * dev, struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_generic_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589537632,
      "name": "xdp_do_generic_redirect",
      "external": true,
      "loc": "net/core/filter.c:3651",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589537632,
      "name": "xdp_do_generic_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
int xdp_do_generic_redirect(struct net_device * dev, struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_generic_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589546800,
      "name": "xdp_do_generic_redirect",
      "external": true,
      "loc": "net/core/filter.c:4058",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589546800,
      "name": "xdp_do_generic_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int xdp_do_generic_redirect(struct net_device * dev, struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_generic_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589444400,
      "name": "xdp_do_generic_redirect",
      "external": true,
      "loc": "net/core/filter.c:4013",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589444400,
      "name": "xdp_do_generic_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 698
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
int xdp_do_generic_redirect(struct net_device * dev, struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_generic_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590179488,
      "name": "xdp_do_generic_redirect",
      "external": true,
      "loc": "net/core/filter.c:4071",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590179488,
      "name": "xdp_do_generic_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 773
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
int xdp_do_generic_redirect(struct net_device * dev, struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_generic_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591741920,
      "name": "xdp_do_generic_redirect",
      "external": true,
      "loc": "net/core/filter.c:4352",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb",
        "net/core/dev.c:do_xdp_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591741920,
      "name": "xdp_do_generic_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 878
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
int xdp_do_generic_redirect(struct net_device * dev, struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_generic_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593531424,
      "name": "xdp_do_generic_redirect",
      "external": true,
      "loc": "net/core/filter.c:4366",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb",
        "net/core/dev.c:do_xdp_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593531424,
      "name": "xdp_do_generic_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 881
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
int xdp_do_generic_redirect(struct net_device * dev, struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_generic_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593999088,
      "name": "xdp_do_generic_redirect",
      "external": true,
      "loc": "net/core/filter.c:4417",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb",
        "net/core/dev.c:do_xdp_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593999088,
      "name": "xdp_do_generic_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 959
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
int xdp_do_generic_redirect(struct net_device * dev, struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_generic_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594783408,
      "name": "xdp_do_generic_redirect",
      "external": true,
      "loc": "net/core/filter.c:4491",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb",
        "net/core/dev.c:do_xdp_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594783408,
      "name": "xdp_do_generic_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 956
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
int xdp_do_generic_redirect(struct net_device * dev, struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_generic_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502221824,
      "name": "xdp_do_generic_redirect",
      "external": true,
      "loc": "net/core/filter.c:3691",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502221824,
      "name": "xdp_do_generic_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1000
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
int xdp_do_generic_redirect(struct net_device * dev, struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_generic_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234944916,
      "name": "xdp_do_generic_redirect",
      "external": true,
      "loc": "net/core/filter.c:3691",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234944916,
      "name": "xdp_do_generic_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 988
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
int xdp_do_generic_redirect(struct net_device * dev, struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_generic_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295682528,
      "name": "xdp_do_generic_redirect",
      "external": true,
      "loc": "net/core/filter.c:3691",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295682528,
      "name": "xdp_do_generic_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1264
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
int xdp_do_generic_redirect(struct net_device * dev, struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_generic_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278453400,
      "name": "xdp_do_generic_redirect",
      "external": true,
      "loc": "net/core/filter.c:3691",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278453400,
      "name": "xdp_do_generic_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
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
int xdp_do_generic_redirect(struct net_device * dev, struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_generic_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588260576,
      "name": "xdp_do_generic_redirect",
      "external": true,
      "loc": "net/core/filter.c:3691",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588260576,
      "name": "xdp_do_generic_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 817
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
int xdp_do_generic_redirect(struct net_device * dev, struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_generic_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587973392,
      "name": "xdp_do_generic_redirect",
      "external": true,
      "loc": "net/core/filter.c:3691",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587973392,
      "name": "xdp_do_generic_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 817
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
int xdp_do_generic_redirect(struct net_device * dev, struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_generic_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588592400,
      "name": "xdp_do_generic_redirect",
      "external": true,
      "loc": "net/core/filter.c:3691",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588592400,
      "name": "xdp_do_generic_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 817
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
int xdp_do_generic_redirect(struct net_device * dev, struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "xdp_do_generic_redirect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588729888,
      "name": "xdp_do_generic_redirect",
      "external": true,
      "loc": "net/core/filter.c:3691",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588729888,
      "name": "xdp_do_generic_redirect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 885
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
int xdp_do_generic_redirect(struct net_device * dev, struct sk_buff * skb, struct bpf_prog * xdp_prog)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xdp_buff * xdp</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, skb, xdp_prog</code> ➡️ <code>dev, skb, xdp, xdp_prog</code>
</li>
</ul>
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
