# Function: <code>__bpf_redirect_neigh</code>

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
int __bpf_redirect_neigh(struct sk_buff * skb, struct net_device * dev, struct bpf_nh_params * nh)
```

```json
{
  "name": "__bpf_redirect_neigh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589531568,
      "name": "__bpf_redirect_neigh",
      "external": false,
      "loc": "net/core/filter.c:2388",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589531568,
      "name": "__bpf_redirect_neigh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
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
int __bpf_redirect_neigh(struct sk_buff * skb, struct net_device * dev, struct bpf_nh_params * nh)
```

```json
{
  "name": "__bpf_redirect_neigh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589429232,
      "name": "__bpf_redirect_neigh",
      "external": false,
      "loc": "net/core/filter.c:2385",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589429232,
      "name": "__bpf_redirect_neigh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
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
int __bpf_redirect_neigh(struct sk_buff * skb, struct net_device * dev, struct bpf_nh_params * nh)
```

```json
{
  "name": "__bpf_redirect_neigh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590164224,
      "name": "__bpf_redirect_neigh",
      "external": false,
      "loc": "net/core/filter.c:2369",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590164224,
      "name": "__bpf_redirect_neigh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 810
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
int __bpf_redirect_neigh(struct sk_buff * skb, struct net_device * dev, struct bpf_nh_params * nh)
```

```json
{
  "name": "__bpf_redirect_neigh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591719712,
      "name": "__bpf_redirect_neigh",
      "external": false,
      "loc": "net/core/filter.c:2370",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591719712,
      "name": "__bpf_redirect_neigh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 857
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
int __bpf_redirect_neigh(struct sk_buff * skb, struct net_device * dev, struct bpf_nh_params * nh)
```

```json
{
  "name": "__bpf_redirect_neigh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593506944,
      "name": "__bpf_redirect_neigh",
      "external": false,
      "loc": "net/core/filter.c:2377",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593506944,
      "name": "__bpf_redirect_neigh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 857
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
int __bpf_redirect_neigh(struct sk_buff * skb, struct net_device * dev, struct bpf_nh_params * nh)
```

```json
{
  "name": "__bpf_redirect_neigh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593969536,
      "name": "__bpf_redirect_neigh",
      "external": false,
      "loc": "net/core/filter.c:2393",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593969536,
      "name": "__bpf_redirect_neigh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 860
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
int __bpf_redirect_neigh(struct sk_buff * skb, struct net_device * dev, struct bpf_nh_params * nh)
```

```json
{
  "name": "__bpf_redirect_neigh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594754144,
      "name": "__bpf_redirect_neigh",
      "external": false,
      "loc": "net/core/filter.c:2400",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594754144,
      "name": "__bpf_redirect_neigh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 854
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
int __bpf_redirect_neigh(struct sk_buff * skb, struct net_device * dev, struct bpf_nh_params * nh)
```
</details>
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
