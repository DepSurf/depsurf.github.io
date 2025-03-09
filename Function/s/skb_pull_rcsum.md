# Function: <code>skb_pull_rcsum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned char * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586212528,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:3032",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pull_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586212528,
      "name": "skb_pull_rcsum",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned char * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586631104,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:3030",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586631104,
      "name": "skb_pull_rcsum",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned char * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586816576,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:3027",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586816576,
      "name": "skb_pull_rcsum",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586945248,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:3068",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586945248,
      "name": "skb_pull_rcsum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587440656,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:3450",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587440656,
      "name": "skb_pull_rcsum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587744976,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:3466",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587744976,
      "name": "skb_pull_rcsum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587879264,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:3445",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587879264,
      "name": "skb_pull_rcsum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588186432,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:3611",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588186432,
      "name": "skb_pull_rcsum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588389152,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:3617",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588389152,
      "name": "skb_pull_rcsum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589246448,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:3616",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589246448,
      "name": "skb_pull_rcsum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589245712,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:3666",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_eth_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589245712,
      "name": "skb_pull_rcsum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589140512,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:3751",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_eth_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589140512,
      "name": "skb_pull_rcsum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589860064,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:3811",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_eth_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589860064,
      "name": "skb_pull_rcsum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591382944,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:3861",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_eth_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591382944,
      "name": "skb_pull_rcsum",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593143808,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:4063",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_eth_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593143808,
      "name": "skb_pull_rcsum",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593597376,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:4233",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_eth_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/seg6_local.c:seg6_pop_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593597376,
      "name": "skb_pull_rcsum",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594371968,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:4355",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_eth_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/seg6_local.c:seg6_pop_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594371968,
      "name": "skb_pull_rcsum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501899376,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:3617",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501899376,
      "name": "skb_pull_rcsum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234664752,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:3617",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234664752,
      "name": "skb_pull_rcsum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295319152,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:3617",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295319152,
      "name": "skb_pull_rcsum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278220466,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:3617",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278220466,
      "name": "skb_pull_rcsum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587995936,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:3617",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587995936,
      "name": "skb_pull_rcsum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587709040,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:3617",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587709040,
      "name": "skb_pull_rcsum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588327712,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:3617",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588327712,
      "name": "skb_pull_rcsum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void * skb_pull_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull_rcsum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588463136,
      "name": "skb_pull_rcsum",
      "external": true,
      "loc": "net/core/skbuff.c:3617",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588463136,
      "name": "skb_pull_rcsum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned char *</code> ➡️ <code>void *</code>
</li>
</ul>
</details>
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
