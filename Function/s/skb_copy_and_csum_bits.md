# Function: <code>skb_copy_and_csum_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len, __wsum csum)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586216832,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2190",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_segment",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586216832,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 803
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len, __wsum csum)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586633616,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2188",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586633616,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 775
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len, __wsum csum)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586819056,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2164",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586819056,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 769
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len, __wsum csum)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586938896,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2178",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586938896,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 721
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len, __wsum csum)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587433040,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2546",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587433040,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len, __wsum csum)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587737376,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2562",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587737376,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 707
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len, __wsum csum)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587870912,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2558",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587870912,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 698
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len, __wsum csum)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2724",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588211679,
      "name": "skb_copy_and_csum_bits.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071588176352,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 649
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len, __wsum csum)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588381520,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2726",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588381520,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len, __wsum csum)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589243648,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2725",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589243648,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589242944,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2742",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589242944,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 589
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589137936,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2825",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589137936,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589857360,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2897",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589857360,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591383776,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2946",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591383776,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 660
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593146384,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:3152",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593146384,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 660
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593600016,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:3322",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593600016,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 750
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594374608,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:3410",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594374608,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 750
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len, __wsum csum)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501892704,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2726",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501892704,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 660
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len, __wsum csum)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234656492,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2726",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/ip6_output.c:__ip6_append_data",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234656492,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 912
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len, __wsum csum)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295306576,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2726",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295306576,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 956
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len, __wsum csum)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278212590,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2726",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278212590,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len, __wsum csum)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587988304,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2726",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587988304,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len, __wsum csum)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587701408,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2726",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587701408,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len, __wsum csum)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588320080,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2726",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588320080,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
__wsum skb_copy_and_csum_bits(const struct sk_buff * skb, int offset, u8 * to, int len, __wsum csum)
```

```json
{
  "name": "skb_copy_and_csum_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588455456,
      "name": "skb_copy_and_csum_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2726",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_copy_and_csum_dev",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/icmp.c:icmp_glue_bits",
        "net/ipv6/icmp.c:icmpv6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588455456,
      "name": "skb_copy_and_csum_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 625
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>__wsum csum</code>
</li>
</ul>
</details>
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
