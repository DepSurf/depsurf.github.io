# Function: <code>skb_segment</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586228864,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:3052",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586228864,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2739
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
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586653824,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:3050",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586653824,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3052
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
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586838384,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:3047",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586838384,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3330
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
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586965456,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:3088",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586965456,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3163
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
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587463376,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:3470",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587463376,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:3499",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587771575,
      "name": "skb_segment.cold.88",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587767840,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3497
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:3478",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587905288,
      "name": "skb_segment.cold.89",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587901648,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3395
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:3644",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588213260,
      "name": "skb_segment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071588207984,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3472
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:3650",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588417969,
      "name": "skb_segment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071588413024,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3488
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:3740",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589284571,
      "name": "skb_segment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071589278800,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3638
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:3808",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591627375,
      "name": "skb_segment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071589278848,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3632
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:3893",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591570777,
      "name": "skb_segment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071589172960,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3461
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
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:3956",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592694752,
      "name": "skb_segment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071589893792,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3541
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
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:3982",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594580226,
      "name": "skb_segment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071591422448,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3804
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
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593186352,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:4183",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593186352,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3851
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
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593644848,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:4357",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593644848,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3876
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
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594420768,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:4479",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594420768,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3901
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
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501930256,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:3650",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501930256,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3148
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
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234689176,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:3650",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234689176,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3180
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
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295350176,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:3650",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295350176,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3672
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
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278240022,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:3650",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278240022,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2710
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:3650",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588024753,
      "name": "skb_segment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071588019808,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3488
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:3650",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587737841,
      "name": "skb_segment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587732896,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3488
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:3650",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588356529,
      "name": "skb_segment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071588351584,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3488
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * skb_segment(struct sk_buff * head_skb, netdev_features_t features)
```

```json
{
  "name": "skb_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_segment",
      "external": true,
      "loc": "net/core/skbuff.c:3650",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588492110,
      "name": "skb_segment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071588487104,
      "name": "skb_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3488
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
