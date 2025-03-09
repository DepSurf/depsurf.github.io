# Function: <code>pskb_trim_rcsum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586226747,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2739",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586549882,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2739",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586552212,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2739",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_defrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586750802,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2739",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587007921,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2739",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587121910,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2739",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587159893,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2739",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587180326,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2739",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pskb_trim_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586652299,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2932",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586993162,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2932",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586995572,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2932",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_defrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587198557,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2932",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587455199,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2932",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587572110,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2932",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587612572,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2932",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587634558,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2932",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586994592,
      "name": "pskb_trim_rcsum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pskb_trim_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586836875,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2970",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587188506,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2970",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587190900,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2970",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_defrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587399024,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2970",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587658733,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2970",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587776142,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2970",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587817132,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2970",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587839214,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:2970",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587189920,
      "name": "pskb_trim_rcsum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pskb_trim_rcsum(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586964983,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3035",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587320747,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3035",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587323140,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3035",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_defrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587534896,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3035",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587808199,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3035",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587932735,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3035",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587974387,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3035",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587996279,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3035",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587322128,
      "name": "pskb_trim_rcsum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587463063,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3134",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587841403,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3134",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587843835,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3134",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_defrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588057237,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3134",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588337340,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3134",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588468059,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3134",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588510307,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3134",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588532807,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3134",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587842800,
      "name": "pskb_trim_rcsum.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587767445,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3147",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588185997,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3147",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588188047,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3147",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_defrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588409741,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3147",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588694548,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3147",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588831344,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3147",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588874445,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3147",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588897127,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3147",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587901278,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3224",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588368942,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3224",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588372826,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3224",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_defrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588601319,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3224",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588910021,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3224",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589054778,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3224",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589097489,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3224",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589120628,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3224",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588207586,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3311",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588771662,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3311",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588774590,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3311",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589012936,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3311",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589352190,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3311",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589508307,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3311",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589552846,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3311",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589573993,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3311",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588412642,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588995294,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588998190,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589237608,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589576419,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589732403,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589776878,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589798377,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589278357,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3400",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589953414,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3400",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589957710,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3400",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590212818,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3400",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590581080,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3400",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590751579,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3400",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590796644,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3400",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590821282,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3400",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589278405,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3426",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589994214,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3426",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589998526,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3426",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590263586,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3426",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590641539,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3426",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590810882,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3426",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590855892,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3426",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590881298,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3426",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589172497,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3490",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589907985,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3490",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589912526,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3490",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590178066,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3490",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590567338,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3490",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590737922,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3490",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590784819,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3490",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590810213,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3490",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589893329,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3527",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590674273,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3527",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590678974,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3527",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590958850,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3527",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591379007,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3527",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591554569,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3527",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591602659,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3527",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591627746,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3527",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591421957,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3901",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592301060,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3901",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592308573,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3901",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_check_defrag",
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592601676,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3901",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593053431,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3901",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593244317,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3901",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593295550,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3901",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593322426,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3901",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ip6_parse_tlv"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593185813,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3797",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594137300,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3797",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594145021,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3797",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_check_defrag",
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594465676,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3797",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594946311,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3797",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595145209,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3797",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595199536,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3797",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595227607,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3797",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ip6_parse_tlv"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593644309,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3831",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594524380,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3831",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594532141,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3831",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_check_defrag",
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594856844,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3831",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595338935,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3831",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595540176,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3831",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595595280,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3831",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595623708,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3831",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ip6_parse_tlv"
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
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594420229,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3859",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595327087,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3859",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595334877,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3859",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_check_defrag",
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595667948,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3859",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596179687,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3859",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596382954,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3859",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596438144,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3859",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596470962,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3859",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ip6_parse_tlv"
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
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501929784,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502599988,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502605864,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502864980,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503252052,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503423132,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503481680,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503505788,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234688764,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 3235306052,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 3235309700,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3235561144,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 3235923792,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 3236085980,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 3236132364,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3236155848,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295349480,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296191860,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296196060,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296521388,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296995320,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297204012,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297267112,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297294576,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278239690,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278752404,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278754992,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278968240,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279279630,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279416682,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279456006,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279476224,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
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
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588019426,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588601678,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588604574,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588843992,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589180787,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589336771,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589381246,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589402745,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587732514,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588313662,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588316558,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588555928,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588905779,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589061763,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589106238,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589127737,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588351202,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589037854,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589040750,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589280168,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589617651,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589773635,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589818110,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589839609,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589923483,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/netfilter/nf_conntrack_reasm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pskb_trim_rcsum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588486722,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589076862,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589079902,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589321576,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589665986,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589824339,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589868830,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589890889,
      "name": "pskb_trim_rcsum",
      "external": false,
      "loc": "include/linux/skbuff.h:3376",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int pskb_trim_rcsum(struct sk_buff * skb, unsigned int len)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
int pskb_trim_rcsum(struct sk_buff * skb, unsigned int len)
```
</details>
</li>
</ul>
