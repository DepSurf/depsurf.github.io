# Function: <code>nf_hook</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586570620,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:192",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586956231,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:192",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587235387,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:192",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
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
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587013548,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:185",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587402481,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:185",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587700053,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:185",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
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
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587188592,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:189",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587195232,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:189",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587211635,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:189",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587379518,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:189",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587407723,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:189",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587529312,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:189",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587555043,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:189",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587556096,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:189",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587605713,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:189",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587649705,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:189",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587657565,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:189",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587751653,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:189",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587784688,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:189",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587801509,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:189",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587874032,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:189",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587886481,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:189",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587887856,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:189",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587914480,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:189",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
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
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587320842,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:180",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587327310,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:180",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587343786,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:180",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587513298,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:180",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587543435,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:180",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587664864,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:180",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587701053,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:180",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587702472,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:180",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587752680,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:180",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587799222,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:180",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587806957,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:180",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587907365,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:180",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587941198,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:180",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587958165,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:180",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588030656,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:180",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588043481,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:180",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588045096,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:180",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588072767,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:180",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587841501,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:182",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587847956,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:182",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587863946,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:182",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588035856,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:182",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588066811,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:182",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588190752,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:182",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588227869,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:182",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588229320,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:182",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588281222,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:182",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588328016,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:182",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588336093,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:182",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588442325,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:182",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588475819,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:182",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588492245,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:182",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588562528,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:182",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588580875,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:182",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588582600,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:182",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588616991,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:182",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int nf_hook(u_int8_t pf, unsigned int hook, struct net * net, struct sock * sk, struct sk_buff * skb, struct net_device * indev, struct net_device * outdev, int (*)(struct net *, struct sock *, struct sk_buff *) okfn)
```

```json
{
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588186095,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588192785,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588209178,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588387096,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588420304,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588544720,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588582501,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588583896,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588636543,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588689652,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ]
    },
    {
      "addr": 18446744071588693469,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588803712,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ]
    },
    {
      "addr": 18446744071588838787,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588855232,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_sendpack"
      ]
    },
    {
      "addr": 18446744071588929552,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588945646,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588947368,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588982959,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588675440,
      "name": "nf_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    },
    {
      "addr": 18446744071588803712,
      "name": "nf_hook.constprop.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071588855232,
      "name": "nf_hook.constprop.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int nf_hook(u_int8_t pf, unsigned int hook, struct net * net, struct sock * sk, struct sk_buff * skb, struct net_device * indev, struct net_device * outdev, int (*)(struct net *, struct sock *, struct sk_buff *) okfn)
```

```json
{
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588369390,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588378216,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588395495,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588577779,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588612336,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588743653,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588786474,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588787864,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588852311,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588906676,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ]
    },
    {
      "addr": 18446744071588912925,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589026384,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ]
    },
    {
      "addr": 18446744071589062359,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589078688,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack"
      ]
    },
    {
      "addr": 18446744071589149104,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6mr_forward2"
      ]
    },
    {
      "addr": 18446744071589169987,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589171736,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589206988,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:193",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588367536,
      "name": "nf_hook.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071588891904,
      "name": "nf_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
    },
    {
      "addr": 18446744071588908944,
      "name": "nf_hook.part.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071589026384,
      "name": "nf_hook.constprop.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071589078688,
      "name": "nf_hook.constprop.39",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071589149104,
      "name": "nf_hook.constprop.43",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588772131,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588779463,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588797632,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588987948,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589024204,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589170096,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ]
    },
    {
      "addr": 18446744071589217851,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589219274,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589291916,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589344951,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589355118,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589479728,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ]
    },
    {
      "addr": 18446744071589515564,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589533024,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack"
      ]
    },
    {
      "addr": 18446744071589604464,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6mr_forward2"
      ]
    },
    {
      "addr": 18446744071589622687,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589624474,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589661088,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589170096,
      "name": "nf_hook.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    },
    {
      "addr": 18446744071589479728,
      "name": "nf_hook.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071589533024,
      "name": "nf_hook.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071589604464,
      "name": "nf_hook.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588995763,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589002972,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589021280,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589212004,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589248764,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589398145,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589443147,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589444586,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589516291,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589569159,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589579230,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589703600,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ]
    },
    {
      "addr": 18446744071589739642,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589757104,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack"
      ]
    },
    {
      "addr": 18446744071589832113,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589846863,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589848650,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589885376,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589703600,
      "name": "nf_hook.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071589757104,
      "name": "nf_hook.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589955488,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589961217,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589980003,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590185031,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590222954,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590387345,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590430440,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590431395,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590510741,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590574615,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590584444,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590723225,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590758137,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590779149,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590862465,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590873757,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590875370,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590914510,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
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
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589996320,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590002026,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590020771,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590234199,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590274747,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590444914,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590488584,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590489555,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590570410,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590634563,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590644862,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590782094,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590817593,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590838415,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590923250,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590935053,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590936682,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590977584,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
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
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589910339,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589916117,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589928339,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590148246,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590189451,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590370146,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590414008,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590415001,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590496036,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590562863,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590569246,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590708504,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590744651,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590762568,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590852738,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590864573,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590866345,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590908608,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:205",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
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
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590676755,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590682633,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590695331,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590928618,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590970811,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591165042,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591212488,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591213465,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591301268,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591374249,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591381054,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591524488,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591561306,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591578824,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591681618,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591694669,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591696473,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591722456,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_input_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591728129,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_input",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591744224,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
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
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592303889,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592310273,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592323409,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592569392,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592619703,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_rcv",
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592822276,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592874101,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592875165,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592968026,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593048252,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593055760,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593211575,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593252314,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593275324,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593378964,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593392342,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593394285,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593423476,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_input_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593429936,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_input",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593449465,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
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
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594140097,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594146900,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594160465,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594430943,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594484663,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_rcv",
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594698740,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594752357,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594753469,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594854394,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594940614,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594948352,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595110471,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595154201,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595178508,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595283732,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595301798,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595303853,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595335942,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_input_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595342544,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_input",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595365929,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:211",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
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
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594527233,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:212",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594534046,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:212",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594548081,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:212",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594820655,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:212",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594876135,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:212",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_rcv",
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595090676,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:212",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595145151,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:212",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595145821,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:212",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595245563,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:212",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595332986,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:212",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595341008,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:212",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595504455,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:212",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595549426,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:212",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595574118,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:212",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595678932,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:212",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595696784,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:212",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595698877,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:212",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595731005,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:212",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595738063,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:212",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_input",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595763113,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:212",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
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
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595329937,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:223",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595336753,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:223",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595350685,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:223",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595631961,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:223",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595687431,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:223",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_rcv",
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595900020,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:223",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595962559,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:223",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595963229,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:223",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596086059,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:223",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596174144,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:223",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596181728,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:223",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596348007,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:223",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596392125,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:223",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596412727,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:223",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596525716,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:223",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596545024,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:223",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596547101,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:223",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596578813,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:223",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596585887,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:223",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_input",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596611273,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:223",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
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
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502601644,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502609436,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502627768,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502836516,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502875824,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503040288,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503097540,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503099064,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503182468,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503243344,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503254304,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503395208,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ]
    },
    {
      "addr": 18446603336503434556,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503451292,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503537320,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503563020,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503565064,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503606932,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503395208,
      "name": "nf_hook.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235307108,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 3235315552,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 3235334680,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 3235535672,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 3235571716,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 3235738724,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 3235779540,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 3235781024,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 3235857280,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 3235913100,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 3235927948,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 3236057540,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3236092748,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 3236116700,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack"
      ],
      "caller_func": []
    },
    {
      "addr": 3236194484,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_forward2"
      ],
      "caller_func": []
    },
    {
      "addr": 3236210392,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 3236212248,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 3236251220,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
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
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296192680,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296202264,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296225584,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296486560,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296535608,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296745140,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296808848,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296810944,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296910800,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296985052,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296999292,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297166348,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297215388,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297240172,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297344564,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297361988,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297364640,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297419252,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
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
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278752848,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278759392,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278775504,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278946082,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278979046,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279111198,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279150502,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279151724,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279223156,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279272794,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279282104,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279390402,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279422330,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279440430,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279510868,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279521294,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279522996,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279558616,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
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
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588602147,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588609356,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588627664,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588818388,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588855084,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589003409,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589047515,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589048954,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589120659,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589173527,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589183598,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589307968,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ]
    },
    {
      "addr": 18446744071589344010,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589361472,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack"
      ]
    },
    {
      "addr": 18446744071589436481,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589451231,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589453018,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589489744,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589307968,
      "name": "nf_hook.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071589361472,
      "name": "nf_hook.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588314131,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588321340,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588339648,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588530324,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588567020,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588726465,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588772555,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588773994,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588845699,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588898519,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588908590,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589032960,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ]
    },
    {
      "addr": 18446744071589069002,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589086464,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack"
      ]
    },
    {
      "addr": 18446744071589161473,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589176223,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589178010,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589214736,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589032960,
      "name": "nf_hook.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071589086464,
      "name": "nf_hook.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589038323,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589045532,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589063840,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589254564,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589291324,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589439793,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589484379,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589485818,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589557523,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589610391,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589620462,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589744832,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ]
    },
    {
      "addr": 18446744071589780874,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589798336,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack"
      ]
    },
    {
      "addr": 18446744071589873345,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589888095,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589889882,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589931008,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589744832,
      "name": "nf_hook.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071589798336,
      "name": "nf_hook.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_hook",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589077344,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589084684,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589103104,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589295236,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589332799,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589484404,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589530589,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589532064,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589605034,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589658690,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589668928,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589795312,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ]
    },
    {
      "addr": 18446744071589831599,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589849072,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack"
      ]
    },
    {
      "addr": 18446744071589924852,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589940351,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589942192,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589980388,
      "name": "nf_hook",
      "external": false,
      "loc": "include/linux/netfilter.h:209",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:__ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589795312,
      "name": "nf_hook.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
    },
    {
      "addr": 18446744071589849072,
      "name": "nf_hook.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
int nf_hook(u_int8_t pf, unsigned int hook, struct net * net, struct sock * sk, struct sk_buff * skb, struct net_device * indev, struct net_device * outdev, int (*)(struct net *, struct sock *, struct sk_buff *) okfn)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int nf_hook(u_int8_t pf, unsigned int hook, struct net * net, struct sock * sk, struct sk_buff * skb, struct net_device * indev, struct net_device * outdev, int (*)(struct net *, struct sock *, struct sk_buff *) okfn)
```
</details>
</li>
</ul>
