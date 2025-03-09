# Function: <code>seg6_do_srh_inline</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seg6_do_srh_inline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587906273,
      "name": "seg6_do_srh_inline",
      "external": false,
      "loc": "net/ipv6/seg6_iptunnel.c:151",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seg6_do_srh_inline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588063511,
      "name": "seg6_do_srh_inline",
      "external": false,
      "loc": "net/ipv6/seg6_iptunnel.c:147",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int seg6_do_srh_inline(struct sk_buff * skb, struct ipv6_sr_hdr * osrh)
```

```json
{
  "name": "seg6_do_srh_inline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588602144,
      "name": "seg6_do_srh_inline",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:156",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588602144,
      "name": "seg6_do_srh_inline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 691
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
int seg6_do_srh_inline(struct sk_buff * skb, struct ipv6_sr_hdr * osrh)
```

```json
{
  "name": "seg6_do_srh_inline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588966576,
      "name": "seg6_do_srh_inline",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:176",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588966576,
      "name": "seg6_do_srh_inline",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int seg6_do_srh_inline(struct sk_buff * skb, struct ipv6_sr_hdr * osrh)
```

```json
{
  "name": "seg6_do_srh_inline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589190672,
      "name": "seg6_do_srh_inline",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:178",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589190672,
      "name": "seg6_do_srh_inline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 689
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
int seg6_do_srh_inline(struct sk_buff * skb, struct ipv6_sr_hdr * osrh)
```

```json
{
  "name": "seg6_do_srh_inline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589644176,
      "name": "seg6_do_srh_inline",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:173",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589644176,
      "name": "seg6_do_srh_inline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 677
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
int seg6_do_srh_inline(struct sk_buff * skb, struct ipv6_sr_hdr * osrh)
```

```json
{
  "name": "seg6_do_srh_inline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589868384,
      "name": "seg6_do_srh_inline",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:173",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589868384,
      "name": "seg6_do_srh_inline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 677
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
int seg6_do_srh_inline(struct sk_buff * skb, struct ipv6_sr_hdr * osrh)
```

```json
{
  "name": "seg6_do_srh_inline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590896000,
      "name": "seg6_do_srh_inline",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:173",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590896000,
      "name": "seg6_do_srh_inline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
int seg6_do_srh_inline(struct sk_buff * skb, struct ipv6_sr_hdr * osrh)
```

```json
{
  "name": "seg6_do_srh_inline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590957456,
      "name": "seg6_do_srh_inline",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:190",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590957456,
      "name": "seg6_do_srh_inline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 653
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
int seg6_do_srh_inline(struct sk_buff * skb, struct ipv6_sr_hdr * osrh)
```

```json
{
  "name": "seg6_do_srh_inline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590887488,
      "name": "seg6_do_srh_inline",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:190",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590887488,
      "name": "seg6_do_srh_inline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
int seg6_do_srh_inline(struct sk_buff * skb, struct ipv6_sr_hdr * osrh)
```

```json
{
  "name": "seg6_do_srh_inline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591718720,
      "name": "seg6_do_srh_inline",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:199",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591718720,
      "name": "seg6_do_srh_inline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
int seg6_do_srh_inline(struct sk_buff * skb, struct ipv6_sr_hdr * osrh)
```

```json
{
  "name": "seg6_do_srh_inline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593419376,
      "name": "seg6_do_srh_inline",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:201",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593419376,
      "name": "seg6_do_srh_inline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
int seg6_do_srh_inline(struct sk_buff * skb, struct ipv6_sr_hdr * osrh)
```

```json
{
  "name": "seg6_do_srh_inline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595331440,
      "name": "seg6_do_srh_inline",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:321",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595331440,
      "name": "seg6_do_srh_inline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 672
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
int seg6_do_srh_inline(struct sk_buff * skb, struct ipv6_sr_hdr * osrh)
```

```json
{
  "name": "seg6_do_srh_inline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595726544,
      "name": "seg6_do_srh_inline",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:321",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595726544,
      "name": "seg6_do_srh_inline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 672
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
int seg6_do_srh_inline(struct sk_buff * skb, struct ipv6_sr_hdr * osrh)
```

```json
{
  "name": "seg6_do_srh_inline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596574368,
      "name": "seg6_do_srh_inline",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:321",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596574368,
      "name": "seg6_do_srh_inline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 672
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
int seg6_do_srh_inline(struct sk_buff * skb, struct ipv6_sr_hdr * osrh)
```

```json
{
  "name": "seg6_do_srh_inline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503587184,
      "name": "seg6_do_srh_inline",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:173",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503587184,
      "name": "seg6_do_srh_inline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
int seg6_do_srh_inline(struct sk_buff * skb, struct ipv6_sr_hdr * osrh)
```

```json
{
  "name": "seg6_do_srh_inline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236232904,
      "name": "seg6_do_srh_inline",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:173",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236232904,
      "name": "seg6_do_srh_inline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
int seg6_do_srh_inline(struct sk_buff * skb, struct ipv6_sr_hdr * osrh)
```

```json
{
  "name": "seg6_do_srh_inline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297395088,
      "name": "seg6_do_srh_inline",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:173",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297395088,
      "name": "seg6_do_srh_inline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 916
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
int seg6_do_srh_inline(struct sk_buff * skb, struct ipv6_sr_hdr * osrh)
```

```json
{
  "name": "seg6_do_srh_inline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279542932,
      "name": "seg6_do_srh_inline",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:173",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279542932,
      "name": "seg6_do_srh_inline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
int seg6_do_srh_inline(struct sk_buff * skb, struct ipv6_sr_hdr * osrh)
```

```json
{
  "name": "seg6_do_srh_inline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589472752,
      "name": "seg6_do_srh_inline",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:173",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589472752,
      "name": "seg6_do_srh_inline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 677
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
int seg6_do_srh_inline(struct sk_buff * skb, struct ipv6_sr_hdr * osrh)
```

```json
{
  "name": "seg6_do_srh_inline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589197744,
      "name": "seg6_do_srh_inline",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:173",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589197744,
      "name": "seg6_do_srh_inline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 677
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
int seg6_do_srh_inline(struct sk_buff * skb, struct ipv6_sr_hdr * osrh)
```

```json
{
  "name": "seg6_do_srh_inline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589909616,
      "name": "seg6_do_srh_inline",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:173",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589909616,
      "name": "seg6_do_srh_inline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 677
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
int seg6_do_srh_inline(struct sk_buff * skb, struct ipv6_sr_hdr * osrh)
```

```json
{
  "name": "seg6_do_srh_inline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589962080,
      "name": "seg6_do_srh_inline",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:173",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589962080,
      "name": "seg6_do_srh_inline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 677
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
int seg6_do_srh_inline(struct sk_buff * skb, struct ipv6_sr_hdr * osrh)
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
