# Function: <code>bpf_out_neigh_v6</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_out_neigh_v6",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_out_neigh_v6",
      "external": false,
      "loc": "net/core/filter.c:2168",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_redirect_neigh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589521616,
      "name": "bpf_out_neigh_v6.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 814
    },
    {
      "addr": 18446744071591630701,
      "name": "bpf_out_neigh_v6.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_out_neigh_v6",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_out_neigh_v6",
      "external": false,
      "loc": "net/core/filter.c:2165",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_redirect_neigh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589420832,
      "name": "bpf_out_neigh_v6.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 820
    },
    {
      "addr": 18446744071591574134,
      "name": "bpf_out_neigh_v6.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int bpf_out_neigh_v6(struct net * net, struct sk_buff * skb, struct net_device * dev, struct bpf_nh_params * nh)
```

```json
{
  "name": "bpf_out_neigh_v6",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_out_neigh_v6",
      "external": false,
      "loc": "net/core/filter.c:2166",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_redirect_neigh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590147456,
      "name": "bpf_out_neigh_v6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1046
    },
    {
      "addr": 18446744071592702120,
      "name": "bpf_out_neigh_v6.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int bpf_out_neigh_v6(struct net * net, struct sk_buff * skb, struct net_device * dev, struct bpf_nh_params * nh)
```

```json
{
  "name": "bpf_out_neigh_v6",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_out_neigh_v6",
      "external": false,
      "loc": "net/core/filter.c:2167",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_redirect_neigh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591706112,
      "name": "bpf_out_neigh_v6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 821
    },
    {
      "addr": 18446744071594588688,
      "name": "bpf_out_neigh_v6.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int bpf_out_neigh_v6(struct net * net, struct sk_buff * skb, struct net_device * dev, struct bpf_nh_params * nh)
```

```json
{
  "name": "bpf_out_neigh_v6",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_out_neigh_v6",
      "external": false,
      "loc": "net/core/filter.c:2174",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_redirect_neigh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593492816,
      "name": "bpf_out_neigh_v6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 838
    },
    {
      "addr": 18446744071596327087,
      "name": "bpf_out_neigh_v6.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int bpf_out_neigh_v6(struct net * net, struct sk_buff * skb, struct net_device * dev, struct bpf_nh_params * nh)
```

```json
{
  "name": "bpf_out_neigh_v6",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_out_neigh_v6",
      "external": false,
      "loc": "net/core/filter.c:2186",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_redirect_neigh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593957312,
      "name": "bpf_out_neigh_v6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 837
    },
    {
      "addr": 18446744071596857344,
      "name": "bpf_out_neigh_v6.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int bpf_out_neigh_v6(struct net * net, struct sk_buff * skb, struct net_device * dev, struct bpf_nh_params * nh)
```

```json
{
  "name": "bpf_out_neigh_v6",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_out_neigh_v6",
      "external": false,
      "loc": "net/core/filter.c:2193",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_redirect_neigh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594741296,
      "name": "bpf_out_neigh_v6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 831
    },
    {
      "addr": 18446744071597782341,
      "name": "bpf_out_neigh_v6.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int bpf_out_neigh_v6(struct net * net, struct sk_buff * skb, struct net_device * dev, struct bpf_nh_params * nh)
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
