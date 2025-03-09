# Function: <code>dst_output</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586555637,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:490",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586562640,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:490",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586726128,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:490",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586871456,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:490",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586906522,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:490",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586930554,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:490",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586956524,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:490",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586989232,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:490",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587094784,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:490",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587123136,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:490",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587138368,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:490",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587200904,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:490",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587221952,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:490",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587234960,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:490",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586562640,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071586726128,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071586989232,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587094784,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587123136,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587138368,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587234960,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586998965,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587013729,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587179332,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587321216,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587352778,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587377050,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587402753,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587446327,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587545504,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587580552,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587591040,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587658872,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587678960,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587700225,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587005680,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587174016,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587437792,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587545504,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587574432,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587591040,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587699616,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587194293,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587208520,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv4/ip_output.c:ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587379523,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587523904,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587555723,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587580128,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587605974,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587649710,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587750000,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587784693,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587795328,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587867352,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587887328,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587907222,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587914721,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:499",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587200992,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587374096,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587641104,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587750000,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587778480,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587795328,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587913984,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587326405,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:469",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587340652,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:469",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv4/ip_output.c:ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587513303,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:469",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587661568,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:469",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587701851,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:469",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587726502,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:469",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587753318,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:469",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587794749,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:469",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587905712,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:469",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587941203,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:469",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587952656,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:469",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588023432,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:469",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588044014,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:469",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588065038,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:469",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588073009,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:469",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587333072,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587508352,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587788768,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587905712,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587935136,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587952656,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588072288,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587847045,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:458",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587858348,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:458",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv4/ip_output.c:ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588035861,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:458",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588186832,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:458",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588228673,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:458",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588253106,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:458",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588281937,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:458",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588328108,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:458",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588440656,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:458",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588475824,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:458",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588488496,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:458",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588560536,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:458",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588581486,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:458",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588603982,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:458",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588617233,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:458",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587853616,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588030960,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588317712,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588440656,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588470576,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588488496,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588616512,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588191813,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588205896,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv4/ip_output.c:ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588387101,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588540944,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588583281,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588607978,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588637082,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588685701,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588804447,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588838803,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588857200,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_sendpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588922872,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588946463,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588969266,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588983201,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588198416,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588382336,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588674512,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588802160,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588834240,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588851760,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588982464,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588377191,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588388936,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv4/ip_output.c:ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588577784,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588743697,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588787249,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588818443,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588853276,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588902781,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589027152,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589062364,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589080291,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589154307,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_forward2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589170812,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589193343,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589207233,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588384048,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588572672,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588890976,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589024832,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589057728,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589075280,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589206496,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588557527,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588778392,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588795218,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588983936,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589175916,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589218689,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589251580,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589292843,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589345084,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589480496,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589511008,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589534635,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589608553,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_forward2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589623532,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589646837,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589661314,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588785264,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588983936,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589332160,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589478096,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589511008,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589529440,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589660592,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588774480,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589001992,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589018882,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589208400,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589393022,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589444001,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589476884,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589517203,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589569292,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589704368,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589739647,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589758715,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589826834,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589847660,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589871045,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589885602,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589008864,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589208400,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589556368,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589701968,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589735104,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589753520,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589884880,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589645662,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:441",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589960152,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:441",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589982775,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:441",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_push_pending_frames",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590185231,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:441",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590380382,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:441",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590431375,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:441",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590467938,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:441",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590510969,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:441",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590574735,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:441",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590723433,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:441",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590758142,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:441",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590779385,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:441",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590852114,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:441",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590874977,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:441",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590898569,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:441",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590914738,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:441",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589967232,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071590180832,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071590560528,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071590720496,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071590753152,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071590771936,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071590914096,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589669408,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:439",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590000936,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:439",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590023543,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:439",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_push_pending_frames",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590234411,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:439",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590437854,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:439",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590489535,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:439",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590526407,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:439",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590570665,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:439",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590634683,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:439",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590782322,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:439",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590817598,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:439",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590838682,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:439",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590912834,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:439",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590936289,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:439",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590960030,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:439",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590977826,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:439",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590007792,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071590230016,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071590620464,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071590779232,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071590812576,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071590831184,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071590977168,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589560745,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:446",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589915080,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:446",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589937911,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:446",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_push_pending_frames",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590148455,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:446",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590363310,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:446",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590414845,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:446",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590451874,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:446",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590496294,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:446",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590562983,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:446",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590707504,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:446",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590744656,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:446",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590759440,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:446",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590843266,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:446",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590865943,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:446",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590890089,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:446",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590909090,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:446",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589928448,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071590145008,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071590560032,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071590707504,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071590740848,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071590759440,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071590908384,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590305810,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:448",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590681544,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:448",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590705015,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:448",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_push_pending_frames",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590928836,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:448",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591155118,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:448",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591213309,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:448",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591253448,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:448",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591301523,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:448",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591374369,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:448",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591523472,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:448",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591561311,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:448",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591576672,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:448",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591671282,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:448",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591696005,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:448",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591721927,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:448",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591744706,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:448",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590695440,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071590925328,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071591371440,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071591523472,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071591556864,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071591576672,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071591717616,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071591744000,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591890510,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592309020,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592333607,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_push_pending_frames",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592569625,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592811949,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592874953,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592918492,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592968347,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593048373,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593210304,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593252319,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593275600,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593367314,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593393826,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593422947,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593443934,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv6/ioam6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6_iptunnel.c:ioam6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593450033,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592323536,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071592567120,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071593045264,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071593210304,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071593247472,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071593268672,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071593418192,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071593449216,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593692878,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594145500,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594171319,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_push_pending_frames",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594430948,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594687885,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594753241,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594799388,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594854687,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594940735,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595108272,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595154206,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595178513,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595275074,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595303362,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595335411,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595359918,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/ioam6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6_iptunnel.c:ioam6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595366657,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:442",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594160608,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071594427088,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071594937584,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071595108272,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071595148432,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071595171232,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071595329104,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071595365664,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594173698,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:456",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594532620,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:456",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594558327,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:456",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_push_pending_frames",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594820660,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:456",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595079789,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:456",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595145593,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:456",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595190752,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:456",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595245831,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:456",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595333107,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:456",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595502272,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:456",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595549431,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:456",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595574123,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:456",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595670242,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:456",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595698386,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:456",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595730470,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:456",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595757190,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:456",
      "file": "net/ipv6/ioam6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6_iptunnel.c:ioam6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595763841,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:456",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594548224,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071594816368,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071595329984,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071595502272,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071595543648,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071595566784,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071595724224,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071595762848,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594970235,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595335329,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595360951,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_push_pending_frames",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595631966,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595892558,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595963001,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596031502,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596086327,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596174179,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596345824,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596392130,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596409632,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596518080,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596546608,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596578275,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596605363,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv6/ioam6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6_iptunnel.c:ioam6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596612001,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:449",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595350832,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071595627664,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071596171168,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071596345824,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071596386400,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071596409632,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071596572048,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071596611008,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502340268,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502608324,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502625532,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502829344,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503040164,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503098416,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503135376,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503182696,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503243500,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503397328,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503434560,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503448288,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503537256,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_forward2_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503563924,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503589652,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503607164,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502614920,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446603336502829344,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446603336503230632,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446603336503393336,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446603336503426248,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446603336503448288,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446603336503606376,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235080964,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 3235314312,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 3235332180,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 3235535992,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 3235739020,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 3235780372,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 3235815348,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3235857500,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 3235913684,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 3236057820,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3236093472,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 3236116984,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack"
      ],
      "caller_func": []
    },
    {
      "addr": 3236194996,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_forward2"
      ],
      "caller_func": []
    },
    {
      "addr": 3236211312,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 3236235376,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 3236251440,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235321040,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 3235531008,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 3235898364,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 3236055064,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 3236087608,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 3236106460,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 3236250724,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295863896,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296200852,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296222516,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296480864,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296739784,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296810080,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296855852,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296910896,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296985232,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297164080,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297215392,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297232640,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297332576,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297363220,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297397488,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297419620,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296209216,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 13835058055296480864,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 13835058055296969104,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 13835058055297164080,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 13835058055297207520,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 13835058055297232640,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 13835058055297418496,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278562500,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278758556,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278773392,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278942252,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279107212,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279151180,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279181574,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279223284,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279273048,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279387694,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279422614,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279434142,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279501112,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279522052,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279544388,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279558794,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278764454,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446743936278942252,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446743936279387694,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446743936279418198,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446743936279434142,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446743936279261356,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446743936279558176,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588380864,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588608376,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588625266,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588814784,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588998654,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589048369,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589081252,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589121571,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589173660,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589308736,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589344015,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589363083,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589431202,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589452028,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589475413,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589489970,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588615248,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588814784,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589160736,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589306336,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589339472,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589357888,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589489248,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588093552,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588320360,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588337250,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588526720,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588721710,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588773409,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588806292,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588846611,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588898652,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589033728,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589069007,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589088075,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589156194,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589177020,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589200405,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589214962,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588327232,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588526720,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588885728,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589031328,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589064464,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589082880,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589214240,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588713040,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589044552,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589061442,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589250960,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589435038,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589485233,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589518116,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589558435,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589610524,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589745600,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589780879,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589799947,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589868066,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589888892,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589912277,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589931234,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589051424,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589250960,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589597600,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589743200,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589776336,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589794752,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589930512,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int dst_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "dst_output",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588853296,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589083704,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589100658,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_local_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589291648,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589479262,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589531473,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589565152,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589605973,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589658823,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589796147,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589831604,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589850765,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589919490,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589941196,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589964825,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589980642,
      "name": "dst_output",
      "external": false,
      "loc": "include/net/dst.h:434",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ip6_local_out"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589090608,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589291648,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589645712,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589793680,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589827088,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589845456,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589979872,
      "name": "dst_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
