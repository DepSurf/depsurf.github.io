# Function: <code>__skb_ext_del</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __skb_ext_del(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "__skb_ext_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587877680,
      "name": "__skb_ext_del",
      "external": true,
      "loc": "net/core/skbuff.c:5700",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587877680,
      "name": "__skb_ext_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void __skb_ext_del(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "__skb_ext_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588182960,
      "name": "__skb_ext_del",
      "external": true,
      "loc": "net/core/skbuff.c:6060",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588182960,
      "name": "__skb_ext_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void __skb_ext_del(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "__skb_ext_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588389008,
      "name": "__skb_ext_del",
      "external": true,
      "loc": "net/core/skbuff.c:6077",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588389008,
      "name": "__skb_ext_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void __skb_ext_del(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "__skb_ext_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589249248,
      "name": "__skb_ext_del",
      "external": true,
      "loc": "net/core/skbuff.c:6220",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify_ingress",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/mptcp/subflow.c:get_mapping_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589249248,
      "name": "__skb_ext_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void __skb_ext_del(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "__skb_ext_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589248512,
      "name": "__skb_ext_del",
      "external": true,
      "loc": "net/core/skbuff.c:6357",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify_ingress",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/mptcp/subflow.c:get_mapping_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589248512,
      "name": "__skb_ext_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void __skb_ext_del(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "__skb_ext_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589143824,
      "name": "__skb_ext_del",
      "external": true,
      "loc": "net/core/skbuff.c:6445",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify_ingress",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/mptcp/subflow.c:get_mapping_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589143824,
      "name": "__skb_ext_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void __skb_ext_del(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "__skb_ext_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__skb_ext_del",
      "external": true,
      "loc": "net/core/skbuff.c:6521",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592694109,
      "name": "__skb_ext_del.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071589863696,
      "name": "__skb_ext_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
void __skb_ext_del(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "__skb_ext_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__skb_ext_del",
      "external": true,
      "loc": "net/core/skbuff.c:6442",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594579642,
      "name": "__skb_ext_del.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071591388048,
      "name": "__skb_ext_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void __skb_ext_del(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "__skb_ext_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__skb_ext_del",
      "external": true,
      "loc": "net/core/skbuff.c:6643",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596321879,
      "name": "__skb_ext_del.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071593151632,
      "name": "__skb_ext_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void __skb_ext_del(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "__skb_ext_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__skb_ext_del",
      "external": true,
      "loc": "net/core/skbuff.c:6688",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596851543,
      "name": "__skb_ext_del.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071593605408,
      "name": "__skb_ext_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void __skb_ext_del(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "__skb_ext_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__skb_ext_del",
      "external": true,
      "loc": "net/core/skbuff.c:6835",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597776439,
      "name": "__skb_ext_del.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071594380000,
      "name": "__skb_ext_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void __skb_ext_del(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "__skb_ext_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501897176,
      "name": "__skb_ext_del",
      "external": true,
      "loc": "net/core/skbuff.c:6077",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501897176,
      "name": "__skb_ext_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void __skb_ext_del(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "__skb_ext_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234662936,
      "name": "__skb_ext_del",
      "external": true,
      "loc": "net/core/skbuff.c:6077",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234662936,
      "name": "__skb_ext_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void __skb_ext_del(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "__skb_ext_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295312864,
      "name": "__skb_ext_del",
      "external": true,
      "loc": "net/core/skbuff.c:6077",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295312864,
      "name": "__skb_ext_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void __skb_ext_del(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "__skb_ext_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278218494,
      "name": "__skb_ext_del",
      "external": true,
      "loc": "net/core/skbuff.c:6077",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278218494,
      "name": "__skb_ext_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void __skb_ext_del(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "__skb_ext_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587995792,
      "name": "__skb_ext_del",
      "external": true,
      "loc": "net/core/skbuff.c:6077",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587995792,
      "name": "__skb_ext_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void __skb_ext_del(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "__skb_ext_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587708896,
      "name": "__skb_ext_del",
      "external": true,
      "loc": "net/core/skbuff.c:6077",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587708896,
      "name": "__skb_ext_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void __skb_ext_del(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "__skb_ext_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588327568,
      "name": "__skb_ext_del",
      "external": true,
      "loc": "net/core/skbuff.c:6077",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588327568,
      "name": "__skb_ext_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void __skb_ext_del(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "__skb_ext_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588462992,
      "name": "__skb_ext_del",
      "external": true,
      "loc": "net/core/skbuff.c:6077",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588462992,
      "name": "__skb_ext_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void __skb_ext_del(struct sk_buff * skb, enum skb_ext_id id)
```
</details>
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
