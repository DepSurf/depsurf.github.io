# Function: <code>pskb_trim_rcsum_slow</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int pskb_trim_rcsum_slow(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_trim_rcsum_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587767152,
      "name": "pskb_trim_rcsum_slow",
      "external": true,
      "loc": "net/core/skbuff.c:1843",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587767152,
      "name": "pskb_trim_rcsum_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int pskb_trim_rcsum_slow(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_trim_rcsum_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587900992,
      "name": "pskb_trim_rcsum_slow",
      "external": true,
      "loc": "net/core/skbuff.c:1853",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587900992,
      "name": "pskb_trim_rcsum_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int pskb_trim_rcsum_slow(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_trim_rcsum_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588207296,
      "name": "pskb_trim_rcsum_slow",
      "external": true,
      "loc": "net/core/skbuff.c:2012",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588207296,
      "name": "pskb_trim_rcsum_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int pskb_trim_rcsum_slow(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_trim_rcsum_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588412352,
      "name": "pskb_trim_rcsum_slow",
      "external": true,
      "loc": "net/core/skbuff.c:2012",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588412352,
      "name": "pskb_trim_rcsum_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int pskb_trim_rcsum_slow(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_trim_rcsum_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589278064,
      "name": "pskb_trim_rcsum_slow",
      "external": true,
      "loc": "net/core/skbuff.c:2011",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ip6_frag_queue",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589278064,
      "name": "pskb_trim_rcsum_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int pskb_trim_rcsum_slow(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_trim_rcsum_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589278032,
      "name": "pskb_trim_rcsum_slow",
      "external": true,
      "loc": "net/core/skbuff.c:2022",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ip6_frag_queue",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589278032,
      "name": "pskb_trim_rcsum_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
int pskb_trim_rcsum_slow(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_trim_rcsum_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589172112,
      "name": "pskb_trim_rcsum_slow",
      "external": true,
      "loc": "net/core/skbuff.c:2064",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589172112,
      "name": "pskb_trim_rcsum_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
int pskb_trim_rcsum_slow(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_trim_rcsum_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589892944,
      "name": "pskb_trim_rcsum_slow",
      "external": true,
      "loc": "net/core/skbuff.c:2136",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589892944,
      "name": "pskb_trim_rcsum_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
int pskb_trim_rcsum_slow(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_trim_rcsum_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591421552,
      "name": "pskb_trim_rcsum_slow",
      "external": true,
      "loc": "net/core/skbuff.c:2185",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_fragment.c:ip_check_defrag",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/exthdrs.c:ip6_parse_tlv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591421552,
      "name": "pskb_trim_rcsum_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int pskb_trim_rcsum_slow(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_trim_rcsum_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593185392,
      "name": "pskb_trim_rcsum_slow",
      "external": true,
      "loc": "net/core/skbuff.c:2388",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_fragment.c:ip_check_defrag",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/exthdrs.c:ip6_parse_tlv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593185392,
      "name": "pskb_trim_rcsum_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int pskb_trim_rcsum_slow(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_trim_rcsum_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593643888,
      "name": "pskb_trim_rcsum_slow",
      "external": true,
      "loc": "net/core/skbuff.c:2552",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_fragment.c:ip_check_defrag",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/exthdrs.c:ip6_parse_tlv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593643888,
      "name": "pskb_trim_rcsum_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
int pskb_trim_rcsum_slow(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_trim_rcsum_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594419808,
      "name": "pskb_trim_rcsum_slow",
      "external": true,
      "loc": "net/core/skbuff.c:2640",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_fragment.c:ip_check_defrag",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/exthdrs.c:ip6_parse_tlv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594419808,
      "name": "pskb_trim_rcsum_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
int pskb_trim_rcsum_slow(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_trim_rcsum_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501929448,
      "name": "pskb_trim_rcsum_slow",
      "external": true,
      "loc": "net/core/skbuff.c:2012",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ip6_frag_queue",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501929448,
      "name": "pskb_trim_rcsum_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int pskb_trim_rcsum_slow(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_trim_rcsum_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234688444,
      "name": "pskb_trim_rcsum_slow",
      "external": true,
      "loc": "net/core/skbuff.c:2012",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ip6_frag_queue",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234688444,
      "name": "pskb_trim_rcsum_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int pskb_trim_rcsum_slow(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_trim_rcsum_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295349024,
      "name": "pskb_trim_rcsum_slow",
      "external": true,
      "loc": "net/core/skbuff.c:2012",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ip6_frag_queue",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295349024,
      "name": "pskb_trim_rcsum_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int pskb_trim_rcsum_slow(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_trim_rcsum_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278239390,
      "name": "pskb_trim_rcsum_slow",
      "external": true,
      "loc": "net/core/skbuff.c:2012",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ip6_frag_queue",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278239390,
      "name": "pskb_trim_rcsum_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int pskb_trim_rcsum_slow(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_trim_rcsum_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588019136,
      "name": "pskb_trim_rcsum_slow",
      "external": true,
      "loc": "net/core/skbuff.c:2012",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588019136,
      "name": "pskb_trim_rcsum_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int pskb_trim_rcsum_slow(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_trim_rcsum_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587732224,
      "name": "pskb_trim_rcsum_slow",
      "external": true,
      "loc": "net/core/skbuff.c:2012",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587732224,
      "name": "pskb_trim_rcsum_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int pskb_trim_rcsum_slow(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_trim_rcsum_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588350912,
      "name": "pskb_trim_rcsum_slow",
      "external": true,
      "loc": "net/core/skbuff.c:2012",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo",
        "net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588350912,
      "name": "pskb_trim_rcsum_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int pskb_trim_rcsum_slow(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_trim_rcsum_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588486432,
      "name": "pskb_trim_rcsum_slow",
      "external": true,
      "loc": "net/core/skbuff.c:2012",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588486432,
      "name": "pskb_trim_rcsum_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int pskb_trim_rcsum_slow(struct sk_buff * skb, unsigned int len)
```
</details>
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
