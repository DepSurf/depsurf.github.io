# Function: <code>bpf_fib_set_fwd_params</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_fib_set_fwd_params",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587964992,
      "name": "bpf_fib_set_fwd_params",
      "external": false,
      "loc": "net/core/filter.c:4167",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587964992,
      "name": "bpf_fib_set_fwd_params.isra.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_fib_set_fwd_params",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588115936,
      "name": "bpf_fib_set_fwd_params",
      "external": false,
      "loc": "net/core/filter.c:4452",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588115936,
      "name": "bpf_fib_set_fwd_params.isra.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_fib_set_fwd_params",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588434160,
      "name": "bpf_fib_set_fwd_params",
      "external": false,
      "loc": "net/core/filter.c:4590",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588434160,
      "name": "bpf_fib_set_fwd_params.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_fib_set_fwd_params",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588640032,
      "name": "bpf_fib_set_fwd_params",
      "external": false,
      "loc": "net/core/filter.c:4599",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588640032,
      "name": "bpf_fib_set_fwd_params.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int bpf_fib_set_fwd_params(struct bpf_fib_lookup * params, const struct neighbour * neigh, const struct net_device * dev)
```

```json
{
  "name": "bpf_fib_set_fwd_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589495328,
      "name": "bpf_fib_set_fwd_params",
      "external": false,
      "loc": "net/core/filter.c:4725",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589495328,
      "name": "bpf_fib_set_fwd_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int bpf_fib_set_fwd_params(struct bpf_fib_lookup * params, const struct neighbour * neigh, const struct net_device * dev)
```

```json
{
  "name": "bpf_fib_set_fwd_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589497408,
      "name": "bpf_fib_set_fwd_params",
      "external": false,
      "loc": "net/core/filter.c:5269",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589497408,
      "name": "bpf_fib_set_fwd_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
int bpf_fib_set_fwd_params(struct bpf_fib_lookup * params, const struct neighbour * neigh, const struct net_device * dev, u32 mtu)
```

```json
{
  "name": "bpf_fib_set_fwd_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589396016,
      "name": "bpf_fib_set_fwd_params",
      "external": false,
      "loc": "net/core/filter.c:5245",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589396016,
      "name": "bpf_fib_set_fwd_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int bpf_fib_set_fwd_params(struct bpf_fib_lookup * params, const struct neighbour * neigh, const struct net_device * dev, u32 mtu)
```

```json
{
  "name": "bpf_fib_set_fwd_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590125824,
      "name": "bpf_fib_set_fwd_params",
      "external": false,
      "loc": "net/core/filter.c:5369",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590125824,
      "name": "bpf_fib_set_fwd_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int bpf_fib_set_fwd_params(struct bpf_fib_lookup * params, const struct neighbour * neigh, const struct net_device * dev, u32 mtu)
```

```json
{
  "name": "bpf_fib_set_fwd_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591675536,
      "name": "bpf_fib_set_fwd_params",
      "external": false,
      "loc": "net/core/filter.c:5678",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591675536,
      "name": "bpf_fib_set_fwd_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
int bpf_fib_set_fwd_params(struct bpf_fib_lookup * params, const struct neighbour * neigh, const struct net_device * dev, u32 mtu)
```

```json
{
  "name": "bpf_fib_set_fwd_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593477504,
      "name": "bpf_fib_set_fwd_params",
      "external": false,
      "loc": "net/core/filter.c:5692",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593477504,
      "name": "bpf_fib_set_fwd_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_fib_set_fwd_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593983316,
      "name": "bpf_fib_set_fwd_params",
      "external": false,
      "loc": "net/core/filter.c:5746",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_fib_set_fwd_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594767646,
      "name": "bpf_fib_set_fwd_params",
      "external": false,
      "loc": "net/core/filter.c:5820",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_fib_set_fwd_params",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502184520,
      "name": "bpf_fib_set_fwd_params",
      "external": false,
      "loc": "net/core/filter.c:4599",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502184520,
      "name": "bpf_fib_set_fwd_params.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int bpf_fib_set_fwd_params(struct bpf_fib_lookup * params, const struct neighbour * neigh, const struct net_device * dev)
```

```json
{
  "name": "bpf_fib_set_fwd_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234923228,
      "name": "bpf_fib_set_fwd_params",
      "external": false,
      "loc": "net/core/filter.c:4599",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234923228,
      "name": "bpf_fib_set_fwd_params",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int bpf_fib_set_fwd_params(struct bpf_fib_lookup * params, const struct neighbour * neigh, const struct net_device * dev)
```

```json
{
  "name": "bpf_fib_set_fwd_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295650896,
      "name": "bpf_fib_set_fwd_params",
      "external": false,
      "loc": "net/core/filter.c:4599",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295650896,
      "name": "bpf_fib_set_fwd_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_fib_set_fwd_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278463554,
      "name": "bpf_fib_set_fwd_params",
      "external": false,
      "loc": "net/core/filter.c:4599",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_fib_set_fwd_params",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588246768,
      "name": "bpf_fib_set_fwd_params",
      "external": false,
      "loc": "net/core/filter.c:4599",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588246768,
      "name": "bpf_fib_set_fwd_params.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_fib_set_fwd_params",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587959584,
      "name": "bpf_fib_set_fwd_params",
      "external": false,
      "loc": "net/core/filter.c:4599",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587959584,
      "name": "bpf_fib_set_fwd_params.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_fib_set_fwd_params",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588578592,
      "name": "bpf_fib_set_fwd_params",
      "external": false,
      "loc": "net/core/filter.c:4599",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588578592,
      "name": "bpf_fib_set_fwd_params.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_fib_set_fwd_params",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588716080,
      "name": "bpf_fib_set_fwd_params",
      "external": false,
      "loc": "net/core/filter.c:4599",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588716080,
      "name": "bpf_fib_set_fwd_params.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int bpf_fib_set_fwd_params(struct bpf_fib_lookup * params, const struct neighbour * neigh, const struct net_device * dev)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 mtu</code>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int bpf_fib_set_fwd_params(struct bpf_fib_lookup * params, const struct neighbour * neigh, const struct net_device * dev, u32 mtu)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int bpf_fib_set_fwd_params(struct bpf_fib_lookup * params, const struct neighbour * neigh, const struct net_device * dev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int bpf_fib_set_fwd_params(struct bpf_fib_lookup * params, const struct neighbour * neigh, const struct net_device * dev)
```
</details>
</li>
</ul>
