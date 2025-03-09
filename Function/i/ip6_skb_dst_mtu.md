# Function: <code>ip6_skb_dst_mtu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587000757,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:178",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587221744,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:178",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
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
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587447445,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:198",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587678752,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:198",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
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
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587650805,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:203",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587887120,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:203",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
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
int ip6_skb_dst_mtu(struct sk_buff * skb)
```

```json
{
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587800343,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:204",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588044674,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:204",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ],
      "caller_func": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588043872,
      "name": "ip6_skb_dst_mtu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int ip6_skb_dst_mtu(struct sk_buff * skb)
```

```json
{
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588329239,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:221",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588582172,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:221",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ],
      "caller_func": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588581328,
      "name": "ip6_skb_dst_mtu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588686658,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:243",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588946484,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:243",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
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
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588903735,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:243",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589170833,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:243",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
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
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589346350,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:263",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589623555,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:263",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
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
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589570572,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:263",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589847683,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:263",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
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
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590506573,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:265",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590575594,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:265",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590875033,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:265",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
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
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590566157,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:265",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590635658,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:265",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590936345,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:265",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
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
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590492528,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:266",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590557230,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:266",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590865801,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:266",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
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
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591297532,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:266",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591368503,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:266",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591695851,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:266",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
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
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592964366,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:266",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593042127,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:266",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593393671,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:266",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
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
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594850702,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:266",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594934367,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:266",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595303207,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:266",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
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
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595241832,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:262",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595326524,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:262",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595698228,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:262",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
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
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596083176,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:261",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596167804,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:261",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596546463,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:261",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
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
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503244948,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:263",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503563948,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:263",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
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
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235915656,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:263",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 3236211324,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:263",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
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
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296987020,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:263",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297363264,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:263",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
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
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279274038,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:263",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279522086,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:263",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
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
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589174940,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:263",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589452051,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:263",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
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
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588899932,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:263",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589177043,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:263",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
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
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589611804,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:263",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589888915,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:263",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
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
  "name": "ip6_skb_dst_mtu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589660124,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:263",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589941219,
      "name": "ip6_skb_dst_mtu",
      "external": false,
      "loc": "include/net/ip6_route.h:263",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
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
int ip6_skb_dst_mtu(struct sk_buff * skb)
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
int ip6_skb_dst_mtu(struct sk_buff * skb)
```
</details>
</li>
</ul>
