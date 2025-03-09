# Function: <code>sock_zerocopy_put_abort</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sock_zerocopy_put_abort(struct ubuf_info * uarg)
```

```json
{
  "name": "sock_zerocopy_put_abort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587446544,
      "name": "sock_zerocopy_put_abort",
      "external": true,
      "loc": "net/core/skbuff.c:1091",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587446544,
      "name": "sock_zerocopy_put_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sock_zerocopy_put_abort(struct ubuf_info * uarg)
```

```json
{
  "name": "sock_zerocopy_put_abort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587750816,
      "name": "sock_zerocopy_put_abort",
      "external": true,
      "loc": "net/core/skbuff.c:1092",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587750816,
      "name": "sock_zerocopy_put_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void sock_zerocopy_put_abort(struct ubuf_info * uarg, bool have_uref)
```

```json
{
  "name": "sock_zerocopy_put_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587884896,
      "name": "sock_zerocopy_put_abort",
      "external": true,
      "loc": "net/core/skbuff.c:1094",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587884896,
      "name": "sock_zerocopy_put_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void sock_zerocopy_put_abort(struct ubuf_info * uarg, bool have_uref)
```

```json
{
  "name": "sock_zerocopy_put_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588190096,
      "name": "sock_zerocopy_put_abort",
      "external": true,
      "loc": "net/core/skbuff.c:1256",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588190096,
      "name": "sock_zerocopy_put_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void sock_zerocopy_put_abort(struct ubuf_info * uarg, bool have_uref)
```

```json
{
  "name": "sock_zerocopy_put_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588395264,
      "name": "sock_zerocopy_put_abort",
      "external": true,
      "loc": "net/core/skbuff.c:1256",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588395264,
      "name": "sock_zerocopy_put_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void sock_zerocopy_put_abort(struct ubuf_info * uarg, bool have_uref)
```

```json
{
  "name": "sock_zerocopy_put_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589255216,
      "name": "sock_zerocopy_put_abort",
      "external": true,
      "loc": "net/core/skbuff.c:1255",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589255216,
      "name": "sock_zerocopy_put_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void sock_zerocopy_put_abort(struct ubuf_info * uarg, bool have_uref)
```

```json
{
  "name": "sock_zerocopy_put_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589254384,
      "name": "sock_zerocopy_put_abort",
      "external": true,
      "loc": "net/core/skbuff.c:1266",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589254384,
      "name": "sock_zerocopy_put_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void sock_zerocopy_put_abort(struct ubuf_info * uarg, bool have_uref)
```

```json
{
  "name": "sock_zerocopy_put_abort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501911184,
      "name": "sock_zerocopy_put_abort",
      "external": true,
      "loc": "net/core/skbuff.c:1256",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501911184,
      "name": "sock_zerocopy_put_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void sock_zerocopy_put_abort(struct ubuf_info * uarg, bool have_uref)
```

```json
{
  "name": "sock_zerocopy_put_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234672196,
      "name": "sock_zerocopy_put_abort",
      "external": true,
      "loc": "net/core/skbuff.c:1256",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv6/ip6_output.c:__ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234672196,
      "name": "sock_zerocopy_put_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void sock_zerocopy_put_abort(struct ubuf_info * uarg, bool have_uref)
```

```json
{
  "name": "sock_zerocopy_put_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295325120,
      "name": "sock_zerocopy_put_abort",
      "external": true,
      "loc": "net/core/skbuff.c:1256",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295325120,
      "name": "sock_zerocopy_put_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void sock_zerocopy_put_abort(struct ubuf_info * uarg, bool have_uref)
```

```json
{
  "name": "sock_zerocopy_put_abort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278224186,
      "name": "sock_zerocopy_put_abort",
      "external": true,
      "loc": "net/core/skbuff.c:1256",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278224186,
      "name": "sock_zerocopy_put_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void sock_zerocopy_put_abort(struct ubuf_info * uarg, bool have_uref)
```

```json
{
  "name": "sock_zerocopy_put_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588002048,
      "name": "sock_zerocopy_put_abort",
      "external": true,
      "loc": "net/core/skbuff.c:1256",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588002048,
      "name": "sock_zerocopy_put_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void sock_zerocopy_put_abort(struct ubuf_info * uarg, bool have_uref)
```

```json
{
  "name": "sock_zerocopy_put_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587715136,
      "name": "sock_zerocopy_put_abort",
      "external": true,
      "loc": "net/core/skbuff.c:1256",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587715136,
      "name": "sock_zerocopy_put_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void sock_zerocopy_put_abort(struct ubuf_info * uarg, bool have_uref)
```

```json
{
  "name": "sock_zerocopy_put_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588333824,
      "name": "sock_zerocopy_put_abort",
      "external": true,
      "loc": "net/core/skbuff.c:1256",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588333824,
      "name": "sock_zerocopy_put_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void sock_zerocopy_put_abort(struct ubuf_info * uarg, bool have_uref)
```

```json
{
  "name": "sock_zerocopy_put_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588469312,
      "name": "sock_zerocopy_put_abort",
      "external": true,
      "loc": "net/core/skbuff.c:1256",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588469312,
      "name": "sock_zerocopy_put_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void sock_zerocopy_put_abort(struct ubuf_info * uarg)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool have_uref</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void sock_zerocopy_put_abort(struct ubuf_info * uarg, bool have_uref)
```
</details>
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
