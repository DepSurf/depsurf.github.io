# Function: <code>skb_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586214736,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1087",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "net/core/skbuff.c:skb_cow_data",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/ipv4/tcp_output.c:tcp_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586214736,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586633216,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1092",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586633216,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586817936,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1092",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586817936,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586948912,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1094",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586948912,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587441440,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1338",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587441440,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587745856,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1340",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587745856,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587880016,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1350",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587880016,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588185104,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1509",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588185104,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588390480,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1509",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588390480,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589251952,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1508",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589251952,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589251120,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1519",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589251120,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589145888,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1561",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/selftests.c:net_test_loopback_validate",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589145888,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1582",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/selftests.c:net_test_loopback_validate",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592694171,
      "name": "skb_copy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071589865888,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1576",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/selftests.c:net_test_loopback_validate",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594579704,
      "name": "skb_copy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071591392144,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593157584,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1775",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/selftests.c:net_test_loopback_validate",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593157584,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593612480,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1927",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/selftests.c:net_test_loopback_validate",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593612480,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594387552,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:2015",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/selftests.c:net_test_loopback_validate",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594387552,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501905784,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1509",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501905784,
      "name": "skb_copy",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234665684,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1509",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234665684,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295317024,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1509",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295317024,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278215036,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1509",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278215036,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587997264,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1509",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587997264,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587710368,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1509",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587710368,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588329040,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1509",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588329040,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct sk_buff * skb_copy(const struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588464496,
      "name": "skb_copy",
      "external": true,
      "loc": "net/core/skbuff.c:1509",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588464496,
      "name": "skb_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
