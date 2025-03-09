# Function: <code>netif_receive_generic_xdp</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netif_receive_generic_xdp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587039745,
      "name": "netif_receive_generic_xdp",
      "external": false,
      "loc": "net/core/dev.c:4376",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb_internal"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netif_receive_generic_xdp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587538414,
      "name": "netif_receive_generic_xdp",
      "external": false,
      "loc": "net/core/dev.c:3914",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:do_xdp_generic"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netif_receive_generic_xdp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587842290,
      "name": "netif_receive_generic_xdp",
      "external": false,
      "loc": "net/core/dev.c:4018",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netif_receive_generic_xdp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587975931,
      "name": "netif_receive_generic_xdp",
      "external": false,
      "loc": "net/core/dev.c:4313",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
u32 netif_receive_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "netif_receive_generic_xdp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588260416,
      "name": "netif_receive_generic_xdp",
      "external": false,
      "loc": "net/core/dev.c:4322",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588260416,
      "name": "netif_receive_generic_xdp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1066
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
u32 netif_receive_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "netif_receive_generic_xdp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588465536,
      "name": "netif_receive_generic_xdp",
      "external": false,
      "loc": "net/core/dev.c:4224",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588465536,
      "name": "netif_receive_generic_xdp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1080
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
u32 netif_receive_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "netif_receive_generic_xdp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589356960,
      "name": "netif_receive_generic_xdp",
      "external": false,
      "loc": "net/core/dev.c:4585",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589356960,
      "name": "netif_receive_generic_xdp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1127
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
u32 netif_receive_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "netif_receive_generic_xdp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589362512,
      "name": "netif_receive_generic_xdp",
      "external": false,
      "loc": "net/core/dev.c:4614",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589362512,
      "name": "netif_receive_generic_xdp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1161
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
u32 netif_receive_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "netif_receive_generic_xdp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589242064,
      "name": "netif_receive_generic_xdp",
      "external": false,
      "loc": "net/core/dev.c:4720",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589242064,
      "name": "netif_receive_generic_xdp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netif_receive_generic_xdp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589994593,
      "name": "netif_receive_generic_xdp",
      "external": false,
      "loc": "net/core/dev.c:4776",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
u32 netif_receive_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "netif_receive_generic_xdp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591534832,
      "name": "netif_receive_generic_xdp",
      "external": false,
      "loc": "net/core/dev.c:4813",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:do_xdp_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591534832,
      "name": "netif_receive_generic_xdp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
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
u32 netif_receive_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "netif_receive_generic_xdp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593308544,
      "name": "netif_receive_generic_xdp",
      "external": false,
      "loc": "net/core/dev.c:4800",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:do_xdp_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593308544,
      "name": "netif_receive_generic_xdp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
u32 netif_receive_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "netif_receive_generic_xdp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593770256,
      "name": "netif_receive_generic_xdp",
      "external": false,
      "loc": "net/core/dev.c:4775",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:do_xdp_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593770256,
      "name": "netif_receive_generic_xdp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
u32 netif_receive_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "netif_receive_generic_xdp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594549840,
      "name": "netif_receive_generic_xdp",
      "external": false,
      "loc": "net/core/dev.c:4923",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:do_xdp_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594549840,
      "name": "netif_receive_generic_xdp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
u32 netif_receive_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "netif_receive_generic_xdp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502015144,
      "name": "netif_receive_generic_xdp",
      "external": false,
      "loc": "net/core/dev.c:4224",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502015144,
      "name": "netif_receive_generic_xdp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1120
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
u32 netif_receive_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "netif_receive_generic_xdp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234748520,
      "name": "netif_receive_generic_xdp",
      "external": false,
      "loc": "net/core/dev.c:4224",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234748520,
      "name": "netif_receive_generic_xdp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1172
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
u32 netif_receive_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "netif_receive_generic_xdp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295427184,
      "name": "netif_receive_generic_xdp",
      "external": false,
      "loc": "net/core/dev.c:4224",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295427184,
      "name": "netif_receive_generic_xdp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1468
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
u32 netif_receive_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "netif_receive_generic_xdp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278288816,
      "name": "netif_receive_generic_xdp",
      "external": false,
      "loc": "net/core/dev.c:4224",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278288816,
      "name": "netif_receive_generic_xdp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 952
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
u32 netif_receive_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "netif_receive_generic_xdp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588072320,
      "name": "netif_receive_generic_xdp",
      "external": false,
      "loc": "net/core/dev.c:4224",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588072320,
      "name": "netif_receive_generic_xdp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1080
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
u32 netif_receive_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "netif_receive_generic_xdp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587785744,
      "name": "netif_receive_generic_xdp",
      "external": false,
      "loc": "net/core/dev.c:4224",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587785744,
      "name": "netif_receive_generic_xdp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1080
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
u32 netif_receive_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "netif_receive_generic_xdp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588404096,
      "name": "netif_receive_generic_xdp",
      "external": false,
      "loc": "net/core/dev.c:4224",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588404096,
      "name": "netif_receive_generic_xdp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1080
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
u32 netif_receive_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "netif_receive_generic_xdp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588540912,
      "name": "netif_receive_generic_xdp",
      "external": false,
      "loc": "net/core/dev.c:4224",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588540912,
      "name": "netif_receive_generic_xdp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1105
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
u32 netif_receive_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```
</details>
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
u32 netif_receive_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
u32 netif_receive_generic_xdp(struct sk_buff * skb, struct xdp_buff * xdp, struct bpf_prog * xdp_prog)
```
</details>
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
