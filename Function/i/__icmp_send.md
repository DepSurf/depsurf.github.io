# Function: <code>__icmp_send</code>

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
void __icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info, const struct ip_options * opt)
```

```json
{
  "name": "__icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588622032,
      "name": "__icmp_send",
      "external": true,
      "loc": "net/ipv4/icmp.c:573",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588622032,
      "name": "__icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1369
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
void __icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info, const struct ip_options * opt)
```

```json
{
  "name": "__icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589034336,
      "name": "__icmp_send",
      "external": true,
      "loc": "net/ipv4/icmp.c:568",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589034336,
      "name": "__icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1427
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
void __icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info, const struct ip_options * opt)
```

```json
{
  "name": "__icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589258848,
      "name": "__icmp_send",
      "external": true,
      "loc": "net/ipv4/icmp.c:569",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589258848,
      "name": "__icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1427
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
void __icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info, const struct ip_options * opt)
```

```json
{
  "name": "__icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590233056,
      "name": "__icmp_send",
      "external": true,
      "loc": "net/ipv4/icmp.c:569",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590233056,
      "name": "__icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1465
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
void __icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info, const struct ip_options * opt)
```

```json
{
  "name": "__icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590285584,
      "name": "__icmp_send",
      "external": true,
      "loc": "net/ipv4/icmp.c:591",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590285584,
      "name": "__icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1445
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
void __icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info, const struct ip_options * opt)
```

```json
{
  "name": "__icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590201200,
      "name": "__icmp_send",
      "external": true,
      "loc": "net/ipv4/icmp.c:591",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590201200,
      "name": "__icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1550
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
void __icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info, const struct ip_options * opt)
```

```json
{
  "name": "__icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590982800,
      "name": "__icmp_send",
      "external": true,
      "loc": "net/ipv4/icmp.c:591",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590982800,
      "name": "__icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1948
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
void __icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info, const struct ip_options * opt)
```

```json
{
  "name": "__icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__icmp_send",
      "external": true,
      "loc": "net/ipv4/icmp.c:584",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594608938,
      "name": "__icmp_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071592624752,
      "name": "__icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2213
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
void __icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info, const struct ip_options * opt)
```

```json
{
  "name": "__icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__icmp_send",
      "external": true,
      "loc": "net/ipv4/icmp.c:584",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596344266,
      "name": "__icmp_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071594490448,
      "name": "__icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2213
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
void __icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info, const struct ip_options * opt)
```

```json
{
  "name": "__icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__icmp_send",
      "external": true,
      "loc": "net/ipv4/icmp.c:587",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596873326,
      "name": "__icmp_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071594883120,
      "name": "__icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2234
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
void __icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info, const struct ip_options * opt)
```

```json
{
  "name": "__icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__icmp_send",
      "external": true,
      "loc": "net/ipv4/icmp.c:587",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597797411,
      "name": "__icmp_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071595694400,
      "name": "__icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2234
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
void __icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info, const struct ip_options * opt)
```

```json
{
  "name": "__icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502888776,
      "name": "__icmp_send",
      "external": true,
      "loc": "net/ipv4/icmp.c:569",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502888776,
      "name": "__icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1172
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
void __icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info, const struct ip_options * opt)
```

```json
{
  "name": "__icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235580556,
      "name": "__icmp_send",
      "external": true,
      "loc": "net/ipv4/icmp.c:569",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235580556,
      "name": "__icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1084
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
void __icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info, const struct ip_options * opt)
```

```json
{
  "name": "__icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296547824,
      "name": "__icmp_send",
      "external": true,
      "loc": "net/ipv4/icmp.c:569",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296547824,
      "name": "__icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1504
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
void __icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info, const struct ip_options * opt)
```

```json
{
  "name": "__icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278985856,
      "name": "__icmp_send",
      "external": true,
      "loc": "net/ipv4/icmp.c:569",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278985856,
      "name": "__icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 900
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
void __icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info, const struct ip_options * opt)
```

```json
{
  "name": "__icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588865024,
      "name": "__icmp_send",
      "external": true,
      "loc": "net/ipv4/icmp.c:569",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588865024,
      "name": "__icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1427
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
void __icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info, const struct ip_options * opt)
```

```json
{
  "name": "__icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588576960,
      "name": "__icmp_send",
      "external": true,
      "loc": "net/ipv4/icmp.c:569",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ip_tunnel.c:tnl_update_pmtu",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588576960,
      "name": "__icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1427
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
void __icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info, const struct ip_options * opt)
```

```json
{
  "name": "__icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589301408,
      "name": "__icmp_send",
      "external": true,
      "loc": "net/ipv4/icmp.c:569",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589301408,
      "name": "__icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1427
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
void __icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info, const struct ip_options * opt)
```

```json
{
  "name": "__icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589342240,
      "name": "__icmp_send",
      "external": true,
      "loc": "net/ipv4/icmp.c:569",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error",
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589342240,
      "name": "__icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1448
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
void __icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info, const struct ip_options * opt)
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
