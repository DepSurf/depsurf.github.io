# Function: <code>csum_partial_copy_nocheck</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len, __wsum sum)
```

```json
{
  "name": "csum_partial_copy_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587330800,
      "name": "csum_partial_copy_nocheck",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:130",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587330800,
      "name": "csum_partial_copy_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len, __wsum sum)
```

```json
{
  "name": "csum_partial_copy_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587829152,
      "name": "csum_partial_copy_nocheck",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:131",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587829152,
      "name": "csum_partial_copy_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len, __wsum sum)
```

```json
{
  "name": "csum_partial_copy_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588044464,
      "name": "csum_partial_copy_nocheck",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:131",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588044464,
      "name": "csum_partial_copy_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len, __wsum sum)
```

```json
{
  "name": "csum_partial_copy_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588264576,
      "name": "csum_partial_copy_nocheck",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:131",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588264576,
      "name": "csum_partial_copy_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len, __wsum sum)
```

```json
{
  "name": "csum_partial_copy_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588817104,
      "name": "csum_partial_copy_nocheck",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:131",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588817104,
      "name": "csum_partial_copy_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len, __wsum sum)
```

```json
{
  "name": "csum_partial_copy_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589195264,
      "name": "csum_partial_copy_nocheck",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:131",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589195264,
      "name": "csum_partial_copy_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len, __wsum sum)
```

```json
{
  "name": "csum_partial_copy_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589436720,
      "name": "csum_partial_copy_nocheck",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:131",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589436720,
      "name": "csum_partial_copy_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len, __wsum sum)
```

```json
{
  "name": "csum_partial_copy_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589894736,
      "name": "csum_partial_copy_nocheck",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:131",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589894736,
      "name": "csum_partial_copy_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len, __wsum sum)
```

```json
{
  "name": "csum_partial_copy_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590120688,
      "name": "csum_partial_copy_nocheck",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:131",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590120688,
      "name": "csum_partial_copy_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len, __wsum sum)
```

```json
{
  "name": "csum_partial_copy_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585124672,
      "name": "csum_partial_copy_nocheck",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:132",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_to_pipe_iter",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585124672,
      "name": "csum_partial_copy_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len)
```

```json
{
  "name": "csum_partial_copy_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585275712,
      "name": "csum_partial_copy_nocheck",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:72",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_to_pipe_iter",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585275712,
      "name": "csum_partial_copy_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len)
```

```json
{
  "name": "csum_partial_copy_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585159248,
      "name": "csum_partial_copy_nocheck",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:72",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585159248,
      "name": "csum_partial_copy_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len)
```

```json
{
  "name": "csum_partial_copy_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585612096,
      "name": "csum_partial_copy_nocheck",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:72",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585612096,
      "name": "csum_partial_copy_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len)
```

```json
{
  "name": "csum_partial_copy_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586768864,
      "name": "csum_partial_copy_nocheck",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:70",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586768864,
      "name": "csum_partial_copy_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len)
```

```json
{
  "name": "csum_partial_copy_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595933920,
      "name": "csum_partial_copy_nocheck",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:70",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595933920,
      "name": "csum_partial_copy_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len)
```

```json
{
  "name": "csum_partial_copy_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596452304,
      "name": "csum_partial_copy_nocheck",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:70",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596452304,
      "name": "csum_partial_copy_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len)
```

```json
{
  "name": "csum_partial_copy_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597347344,
      "name": "csum_partial_copy_nocheck",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:65",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:csum_and_copy_from_iter_full",
        "net/core/skbuff.c:csum_and_copy_from_iter_full",
        "net/core/skbuff.c:csum_and_copy_from_iter_full",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/datagram.c:csum_and_copy_to_iter",
        "net/core/datagram.c:csum_and_copy_to_iter",
        "net/core/datagram.c:csum_and_copy_to_iter",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597347344,
      "name": "csum_partial_copy_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "csum_partial_copy_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "csum_partial_copy_nocheck",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236416128,
      "name": "csum_partial_copy_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 876
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len, __wsum sum)
```

```json
{
  "name": "csum_partial_copy_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589722944,
      "name": "csum_partial_copy_nocheck",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:131",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589722944,
      "name": "csum_partial_copy_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len, __wsum sum)
```

```json
{
  "name": "csum_partial_copy_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589448720,
      "name": "csum_partial_copy_nocheck",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:131",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589448720,
      "name": "csum_partial_copy_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len, __wsum sum)
```

```json
{
  "name": "csum_partial_copy_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590166320,
      "name": "csum_partial_copy_nocheck",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:131",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590166320,
      "name": "csum_partial_copy_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len, __wsum sum)
```

```json
{
  "name": "csum_partial_copy_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590216832,
      "name": "csum_partial_copy_nocheck",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:131",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590216832,
      "name": "csum_partial_copy_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
<code>__wsum sum</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len, __wsum sum)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len, __wsum sum)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len, __wsum sum)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
__wsum csum_partial_copy_nocheck(const void * src, void * dst, int len, __wsum sum)
```
</details>
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
