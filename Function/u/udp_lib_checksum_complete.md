# Function: <code>udp_lib_checksum_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586743355,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:119",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587114417,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:119",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:__udp6_lib_rcv"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587200296,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:119",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587572743,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:119",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_recvmsg"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587400696,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:119",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587776775,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:119",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_recvmsg"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int udp_lib_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587536537,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:119",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:__first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587931512,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:119",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb"
      ],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587928080,
      "name": "udp_lib_checksum_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int udp_lib_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588059827,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:119",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:__first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588466824,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:119",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb"
      ],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588463152,
      "name": "udp_lib_checksum_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588411895,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:119",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:__first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588832574,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:119",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb"
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
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588603484,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:119",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/udp.c:__first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589056022,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:119",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
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
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589015023,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:115",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/udp.c:__first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589509379,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:115",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
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
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589239695,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:115",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/udp.c:__first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589733478,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:115",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
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
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590213884,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:115",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/udp.c:__first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590752277,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:115",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
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
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590264652,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:116",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/udp.c:__first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590811653,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:116",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
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
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590179118,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:116",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/udp.c:__first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590738646,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:116",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
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
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590959826,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:116",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_read_sock",
        "net/ipv4/udp.c:udp_read_sock",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/udp.c:__first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591555304,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:116",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
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
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592602657,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:116",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_read_sock",
        "net/ipv4/udp.c:__first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593245047,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:116",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
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
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594466771,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:117",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_read_skb",
        "net/ipv4/udp.c:__first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595145852,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:117",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
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
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594857810,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:118",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_read_skb",
        "net/ipv4/udp.c:__first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595540918,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:118",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
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
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595668837,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:118",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_read_skb",
        "net/ipv4/udp.c:__first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596383668,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:118",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
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
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502867064,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:115",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/udp.c:__first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503424164,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:115",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
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
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235563224,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:115",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/udp.c:__first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 3236086764,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:115",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
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
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296523712,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:115",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/udp.c:__first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297205292,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:115",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
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
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278970174,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:115",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/udp.c:__first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279417192,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:115",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
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
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588846079,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:115",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/udp.c:__first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589337846,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:115",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
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
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588558015,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:115",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/udp.c:__first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589062838,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:115",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
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
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589282255,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:115",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/udp.c:__first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589774710,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:115",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
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
  "name": "udp_lib_checksum_complete",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589323663,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:115",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/udp.c:__first_packet_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589825454,
      "name": "udp_lib_checksum_complete",
      "external": false,
      "loc": "include/net/udp.h:115",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int udp_lib_checksum_complete(struct sk_buff * skb)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int udp_lib_checksum_complete(struct sk_buff * skb)
```
</details>
</li>
</ul>
