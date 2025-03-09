# Function: <code>ip_fast_csum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585109821,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586419922,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586549746,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586562680,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586731312,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586790396,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586807369,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp"
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
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585502765,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586862982,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586993042,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587005720,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587179246,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587238700,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587256301,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp"
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
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585690557,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587054070,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587188386,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587201032,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587379437,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587438908,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587458109,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp"
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
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585777517,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587181892,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587320580,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587333112,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587513217,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587580947,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587593370,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586215869,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587686708,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587841236,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587853656,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588035775,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588104883,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588115546,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586473112,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588018893,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588185888,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588198463,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588387011,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588458439,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588470186,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp"
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
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586620840,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588186349,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588368842,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588384095,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588577694,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588645959,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588664942,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp"
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
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586874140,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588511999,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588559021,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588771560,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588785311,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588988077,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589058320,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589077728,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589285188,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587020172,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588720575,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588776107,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588995192,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589008911,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589211914,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589282592,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589301888,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589509620,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587849167,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589588265,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589648353,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589953312,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589967279,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590184941,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590259688,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590275208,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_iphdr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590501310,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap"
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
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587907487,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589599945,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589672100,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589994112,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590007839,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590234109,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590312629,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590328152,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_iphdr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590560910,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap"
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
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587787269,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589488012,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589563700,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589907883,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589922015,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590148159,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590228485,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590245052,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590486254,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap"
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
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588383733,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590228743,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590308900,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590674171,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590688591,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590928531,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591011765,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591028636,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591290638,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap"
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
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589780504,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/slip/slhc.c:slhc_remember",
        "drivers/net/slip/slhc.c:slhc_uncompress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591806985,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591893938,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592300960,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592316047,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592569304,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592659294,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592676107,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592957262,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap"
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
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591431160,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/slip/slhc.c:slhc_remember",
        "drivers/net/slip/slhc.c:slhc_uncompress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593602809,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593696418,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594137200,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594152847,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594430855,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594525223,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594544155,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594842974,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap"
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
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591846363,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/slip/slhc.c:slhc_remember",
        "drivers/net/slip/slhc.c:slhc_uncompress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594076195,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594177192,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594524272,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594540159,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594820567,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594916634,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594935947,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595234298,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap"
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
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592594443,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/slip/slhc.c:slhc_remember",
        "drivers/net/slip/slhc.c:slhc_uncompress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594870832,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594973717,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595326979,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595342751,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595631873,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595728602,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595748171,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596074778,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:45",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap"
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
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500140832,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/arm64/include/asm/checksum.h:18",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502286196,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/arm64/include/asm/checksum.h:18",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502342520,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/arm64/include/asm/checksum.h:18",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502599872,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/arm64/include/asm/checksum.h:18",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502617696,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/arm64/include/asm/checksum.h:18",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_output.c:ip_fraglist_prepare",
        "net/ipv4/ip_output.c:ip_fraglist_init",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502836396,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/arm64/include/asm/checksum.h:18",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502911664,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/arm64/include/asm/checksum.h:18",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502928964,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/arm64/include/asm/checksum.h:18",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503174296,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/arm64/include/asm/checksum.h:18",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232632344,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:61",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235026136,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:61",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 3235082032,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:61",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 3235305928,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:61",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 3235321112,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:61",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 3235535552,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:61",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 3235605064,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:61",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 3235629396,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:61",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp"
      ],
      "caller_func": []
    },
    {
      "addr": 3235849652,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:61",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input"
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
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293357316,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:148",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295788268,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:148",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295865412,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:148",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296191732,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:148",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296209308,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:148",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296486444,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:148",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296582412,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:148",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296608824,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:148",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296901180,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:148",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
__sum16 ip_fast_csum(const void * iph, unsigned int ihl)
```

```json
{
  "name": "ip_fast_csum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275376958,
      "name": "ip_fast_csum",
      "external": true,
      "loc": "lib/checksum.c:106",
      "file": "lib/checksum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_output.c:ip_fraglist_prepare",
        "net/ipv4/ip_output.c:ip_fraglist_init",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/igmp.c:ip_mc_check_igmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275376958,
      "name": "ip_fast_csum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586777196,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588327311,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588382491,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588601576,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588615295,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588818298,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588888768,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588908064,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589113988,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586682428,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588039978,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588095179,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588313560,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588327279,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588530234,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588600704,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588620000,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588839028,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586974732,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588659135,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588714667,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589037752,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589051471,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589254474,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589325152,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589344448,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589550852,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "ip_fast_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587081932,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "drivers/net/slip/slhc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588799391,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588854923,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589076760,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589090655,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589295146,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589373753,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589386768,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589598324,
      "name": "ip_fast_csum",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:46",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
__sum16 ip_fast_csum(const void * iph, unsigned int ihl)
```
</details>
</li>
</ul>
