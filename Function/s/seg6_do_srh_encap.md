# Function: <code>seg6_do_srh_encap</code>

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
  "name": "seg6_do_srh_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587905866,
      "name": "seg6_do_srh_encap",
      "external": false,
      "loc": "net/ipv6/seg6_iptunnel.c:98",
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
  "name": "seg6_do_srh_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588063051,
      "name": "seg6_do_srh_encap",
      "external": false,
      "loc": "net/ipv6/seg6_iptunnel.c:94",
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
int seg6_do_srh_encap(struct sk_buff * skb, struct ipv6_sr_hdr * osrh, int proto)
```

```json
{
  "name": "seg6_do_srh_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588601392,
      "name": "seg6_do_srh_encap",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:95",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588601392,
      "name": "seg6_do_srh_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 750
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
int seg6_do_srh_encap(struct sk_buff * skb, struct ipv6_sr_hdr * osrh, int proto)
```

```json
{
  "name": "seg6_do_srh_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588967280,
      "name": "seg6_do_srh_encap",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:113",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588967280,
      "name": "seg6_do_srh_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 853
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
int seg6_do_srh_encap(struct sk_buff * skb, struct ipv6_sr_hdr * osrh, int proto)
```

```json
{
  "name": "seg6_do_srh_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589191376,
      "name": "seg6_do_srh_encap",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:113",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589191376,
      "name": "seg6_do_srh_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 866
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
int seg6_do_srh_encap(struct sk_buff * skb, struct ipv6_sr_hdr * osrh, int proto)
```

```json
{
  "name": "seg6_do_srh_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589644864,
      "name": "seg6_do_srh_encap",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:108",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589644864,
      "name": "seg6_do_srh_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 862
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
int seg6_do_srh_encap(struct sk_buff * skb, struct ipv6_sr_hdr * osrh, int proto)
```

```json
{
  "name": "seg6_do_srh_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589869072,
      "name": "seg6_do_srh_encap",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:108",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589869072,
      "name": "seg6_do_srh_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 862
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
int seg6_do_srh_encap(struct sk_buff * skb, struct ipv6_sr_hdr * osrh, int proto)
```

```json
{
  "name": "seg6_do_srh_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590896656,
      "name": "seg6_do_srh_encap",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:108",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590896656,
      "name": "seg6_do_srh_encap",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int seg6_do_srh_encap(struct sk_buff * skb, struct ipv6_sr_hdr * osrh, int proto)
```

```json
{
  "name": "seg6_do_srh_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590958112,
      "name": "seg6_do_srh_encap",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:125",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590958112,
      "name": "seg6_do_srh_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
int seg6_do_srh_encap(struct sk_buff * skb, struct ipv6_sr_hdr * osrh, int proto)
```

```json
{
  "name": "seg6_do_srh_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590888144,
      "name": "seg6_do_srh_encap",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:125",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590888144,
      "name": "seg6_do_srh_encap",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int seg6_do_srh_encap(struct sk_buff * skb, struct ipv6_sr_hdr * osrh, int proto)
```

```json
{
  "name": "seg6_do_srh_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591719376,
      "name": "seg6_do_srh_encap",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:126",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591719376,
      "name": "seg6_do_srh_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 831
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
int seg6_do_srh_encap(struct sk_buff * skb, struct ipv6_sr_hdr * osrh, int proto)
```

```json
{
  "name": "seg6_do_srh_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593420096,
      "name": "seg6_do_srh_encap",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:126",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593420096,
      "name": "seg6_do_srh_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 915
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
int seg6_do_srh_encap(struct sk_buff * skb, struct ipv6_sr_hdr * osrh, int proto)
```

```json
{
  "name": "seg6_do_srh_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595330624,
      "name": "seg6_do_srh_encap",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:128",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595330624,
      "name": "seg6_do_srh_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 796
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
int seg6_do_srh_encap(struct sk_buff * skb, struct ipv6_sr_hdr * osrh, int proto)
```

```json
{
  "name": "seg6_do_srh_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595725728,
      "name": "seg6_do_srh_encap",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:128",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595725728,
      "name": "seg6_do_srh_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 796
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
int seg6_do_srh_encap(struct sk_buff * skb, struct ipv6_sr_hdr * osrh, int proto)
```

```json
{
  "name": "seg6_do_srh_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596573552,
      "name": "seg6_do_srh_encap",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:128",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596573552,
      "name": "seg6_do_srh_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 796
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
int seg6_do_srh_encap(struct sk_buff * skb, struct ipv6_sr_hdr * osrh, int proto)
```

```json
{
  "name": "seg6_do_srh_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503587808,
      "name": "seg6_do_srh_encap",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:108",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503587808,
      "name": "seg6_do_srh_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 792
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
int seg6_do_srh_encap(struct sk_buff * skb, struct ipv6_sr_hdr * osrh, int proto)
```

```json
{
  "name": "seg6_do_srh_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236233528,
      "name": "seg6_do_srh_encap",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:108",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236233528,
      "name": "seg6_do_srh_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 796
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
int seg6_do_srh_encap(struct sk_buff * skb, struct ipv6_sr_hdr * osrh, int proto)
```

```json
{
  "name": "seg6_do_srh_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297394032,
      "name": "seg6_do_srh_encap",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:108",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297394032,
      "name": "seg6_do_srh_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1052
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
int seg6_do_srh_encap(struct sk_buff * skb, struct ipv6_sr_hdr * osrh, int proto)
```

```json
{
  "name": "seg6_do_srh_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279542138,
      "name": "seg6_do_srh_encap",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:108",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279542138,
      "name": "seg6_do_srh_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 794
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
int seg6_do_srh_encap(struct sk_buff * skb, struct ipv6_sr_hdr * osrh, int proto)
```

```json
{
  "name": "seg6_do_srh_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589473440,
      "name": "seg6_do_srh_encap",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:108",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589473440,
      "name": "seg6_do_srh_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 862
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
int seg6_do_srh_encap(struct sk_buff * skb, struct ipv6_sr_hdr * osrh, int proto)
```

```json
{
  "name": "seg6_do_srh_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589198432,
      "name": "seg6_do_srh_encap",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:108",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589198432,
      "name": "seg6_do_srh_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 862
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
int seg6_do_srh_encap(struct sk_buff * skb, struct ipv6_sr_hdr * osrh, int proto)
```

```json
{
  "name": "seg6_do_srh_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589910304,
      "name": "seg6_do_srh_encap",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:108",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589910304,
      "name": "seg6_do_srh_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 862
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
int seg6_do_srh_encap(struct sk_buff * skb, struct ipv6_sr_hdr * osrh, int proto)
```

```json
{
  "name": "seg6_do_srh_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589962768,
      "name": "seg6_do_srh_encap",
      "external": true,
      "loc": "net/ipv6/seg6_iptunnel.c:108",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589962768,
      "name": "seg6_do_srh_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 872
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
int seg6_do_srh_encap(struct sk_buff * skb, struct ipv6_sr_hdr * osrh, int proto)
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
