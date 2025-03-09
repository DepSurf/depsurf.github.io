# Function: <code>icmp_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info)
```

```json
{
  "name": "icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586768048,
      "name": "icmp_send",
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
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_options.c:ip_options_compile",
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
      "addr": 18446744071586768048,
      "name": "icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1131
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
void icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info)
```

```json
{
  "name": "icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587216032,
      "name": "icmp_send",
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
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
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
      "addr": 18446744071587216032,
      "name": "icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1221
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
void icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info)
```

```json
{
  "name": "icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587416560,
      "name": "icmp_send",
      "external": true,
      "loc": "net/ipv4/icmp.c:570",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
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
      "addr": 18446744071587416560,
      "name": "icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1224
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
void icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info)
```

```json
{
  "name": "icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587552848,
      "name": "icmp_send",
      "external": true,
      "loc": "net/ipv4/icmp.c:576",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
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
      "addr": 18446744071587552848,
      "name": "icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1274
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
void icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info)
```

```json
{
  "name": "icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588076400,
      "name": "icmp_send",
      "external": true,
      "loc": "net/ipv4/icmp.c:576",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
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
      "addr": 18446744071588076400,
      "name": "icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1286
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
void icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info)
```

```json
{
  "name": "icmp_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588430608,
      "name": "icmp_send",
      "external": true,
      "loc": "net/ipv4/icmp.c:576",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
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
      "addr": 18446744071588430608,
      "name": "icmp_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1280
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmp_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588343749,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:45",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588370506,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:45",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588376710,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:45",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588377684,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:45",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588378913,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:45",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_compile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588387660,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:45",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588603578,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:45",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588787675,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:45",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588789278,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:45",
      "file": "net/ipv4/xfrm4_protocol.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmp_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588745025,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588773301,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588778036,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588778907,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588782103,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_compile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588789171,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589015124,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589219090,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589220638,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_protocol.c",
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
  "name": "icmp_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588968769,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588996901,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589001636,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589002550,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589005687,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_compile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589012371,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589239787,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589444430,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589445966,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_protocol.c",
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
  "name": "icmp_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589923891,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589955013,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589959790,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589960667,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589963812,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589972805,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590213976,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590234749,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/icmp.c:icmp_ndo_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590432094,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590509186,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/xfrm/xfrm_output.c",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmp_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589964426,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589995797,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590000611,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590001451,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590004605,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590013397,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590264744,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590490270,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590568798,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/xfrm/xfrm_output.c",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmp_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589879325,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589909042,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589914931,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589915685,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589918834,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589927621,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590179210,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590415694,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590493619,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/xfrm/xfrm_output.c",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmp_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590643229,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590675412,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590681394,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590682209,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590685406,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590694581,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590959918,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591214142,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591298473,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/xfrm/xfrm_output.c",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmp_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592267929,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592302276,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592306346,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592309649,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592311074,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592322606,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592602736,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592875950,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592965644,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/xfrm/xfrm_output.c",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmp_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594103113,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594138495,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594142722,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594146226,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594147742,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594159614,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594466846,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594754350,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594851992,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/xfrm/xfrm_output.c",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmp_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594489978,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594525631,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594529849,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594533365,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594534905,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594547198,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594857889,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595146702,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595243132,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/xfrm/xfrm_output.c",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmp_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595292810,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595328319,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595332585,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595336078,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595337609,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595349790,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595668916,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595964110,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596083008,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/xfrm/xfrm_output.c",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "icmp_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502582468,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502602824,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502605540,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502608848,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502611636,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_compile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502624308,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502867172,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503098840,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503100244,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_protocol.c",
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
  "name": "icmp_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235278120,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 3235308460,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 3235312024,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 3235314656,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 3235318100,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_compile"
      ],
      "caller_func": []
    },
    {
      "addr": 3235325884,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235563332,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 3235780740,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 3235782064,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_protocol.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "icmp_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296157132,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296194268,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296198284,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296201848,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296205508,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296214244,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296523832,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296810656,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296812692,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_protocol.c",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "icmp_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278729890,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278753804,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278758098,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278759002,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278761576,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278767964,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278970282,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279151516,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279152680,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_protocol.c",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmp_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588575153,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588603285,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588608020,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588608934,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588612071,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_compile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588618755,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588846171,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589048798,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589050334,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_protocol.c",
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
  "name": "icmp_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588287137,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588315269,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588320004,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588320918,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588324055,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_compile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588330739,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588558107,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588703181,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_tunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel.c:tnl_update_pmtu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588773838,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588775374,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_protocol.c",
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
  "name": "icmp_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589011329,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589039461,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589044196,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589045110,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589048247,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_compile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589054931,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589282347,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589485662,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589487198,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_protocol.c",
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
  "name": "icmp_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589049912,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/route.c:ip_rt_send_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589078501,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589081802,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589084262,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589087441,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_compile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589094115,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589323755,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589531902,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589533454,
      "name": "icmp_send",
      "external": false,
      "loc": "include/net/icmp.h:41",
      "file": "net/ipv4/xfrm4_protocol.c",
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void icmp_send(struct sk_buff * skb_in, int type, int code, __be32 info)
```
</details>
</li>
</ul>
