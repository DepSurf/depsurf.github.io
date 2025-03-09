# Function: <code>bpf_prog_run_generic_xdp</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
u32 bpf_prog_run_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "bpf_prog_run_generic_xdp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_prog_run_generic_xdp",
      "external": true,
      "loc": "net/core/dev.c:4688",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592698814,
      "name": "bpf_prog_run_generic_xdp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071589993328,
      "name": "bpf_prog_run_generic_xdp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 911
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
u32 bpf_prog_run_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "bpf_prog_run_generic_xdp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_prog_run_generic_xdp",
      "external": true,
      "loc": "net/core/dev.c:4725",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb",
        "net/core/dev.c:netif_receive_generic_xdp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594585006,
      "name": "bpf_prog_run_generic_xdp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071591533904,
      "name": "bpf_prog_run_generic_xdp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 926
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
u32 bpf_prog_run_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "bpf_prog_run_generic_xdp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_prog_run_generic_xdp",
      "external": true,
      "loc": "net/core/dev.c:4712",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb",
        "net/core/dev.c:netif_receive_generic_xdp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596324384,
      "name": "bpf_prog_run_generic_xdp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071593307600,
      "name": "bpf_prog_run_generic_xdp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 926
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
u32 bpf_prog_run_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "bpf_prog_run_generic_xdp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_prog_run_generic_xdp",
      "external": true,
      "loc": "net/core/dev.c:4687",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb",
        "net/core/dev.c:netif_receive_generic_xdp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596854697,
      "name": "bpf_prog_run_generic_xdp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071593769296,
      "name": "bpf_prog_run_generic_xdp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 941
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
u32 bpf_prog_run_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "bpf_prog_run_generic_xdp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_prog_run_generic_xdp",
      "external": true,
      "loc": "net/core/dev.c:4835",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb",
        "net/core/dev.c:netif_receive_generic_xdp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597779730,
      "name": "bpf_prog_run_generic_xdp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071594548880,
      "name": "bpf_prog_run_generic_xdp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 941
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
u32 bpf_prog_run_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```
</details>
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
