# Function: <code>sk_stream_alloc_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * sk_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "sk_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586614912,
      "name": "sk_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:816",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586614912,
      "name": "sk_stream_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
struct sk_buff * sk_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "sk_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587059680,
      "name": "sk_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:805",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587059680,
      "name": "sk_stream_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
struct sk_buff * sk_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "sk_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587256256,
      "name": "sk_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:809",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587256256,
      "name": "sk_stream_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
struct sk_buff * sk_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "sk_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587388512,
      "name": "sk_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:831",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587388512,
      "name": "sk_stream_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
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
struct sk_buff * sk_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "sk_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587904784,
      "name": "sk_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:859",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587904784,
      "name": "sk_stream_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 483
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
struct sk_buff * sk_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "sk_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588256368,
      "name": "sk_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:864",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588256368,
      "name": "sk_stream_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
struct sk_buff * sk_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "sk_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588444576,
      "name": "sk_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:863",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588444576,
      "name": "sk_stream_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
struct sk_buff * sk_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "sk_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588849632,
      "name": "sk_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:852",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588849632,
      "name": "sk_stream_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 724
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct sk_buff * sk_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "sk_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589072944,
      "name": "sk_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:854",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589072944,
      "name": "sk_stream_alloc_skb",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * sk_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "sk_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590037344,
      "name": "sk_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:861",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tso_fragment",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590037344,
      "name": "sk_stream_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 719
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
struct sk_buff * sk_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "sk_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590068400,
      "name": "sk_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:865",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_build_frag",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tso_fragment",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590068400,
      "name": "sk_stream_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
struct sk_buff * sk_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "sk_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589982752,
      "name": "sk_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:864",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_build_frag",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tso_fragment",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589982752,
      "name": "sk_stream_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 722
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
struct sk_buff * sk_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "sk_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590752208,
      "name": "sk_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:861",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_build_frag",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tso_fragment",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590752208,
      "name": "sk_stream_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 722
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct sk_buff * sk_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "sk_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502689552,
      "name": "sk_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:854",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502689552,
      "name": "sk_stream_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
struct sk_buff * sk_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "sk_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235390792,
      "name": "sk_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:854",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235390792,
      "name": "sk_stream_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
struct sk_buff * sk_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "sk_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296298624,
      "name": "sk_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:854",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296298624,
      "name": "sk_stream_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 848
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
struct sk_buff * sk_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "sk_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278820068,
      "name": "sk_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:854",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278820068,
      "name": "sk_stream_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct sk_buff * sk_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "sk_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588679328,
      "name": "sk_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:854",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588679328,
      "name": "sk_stream_alloc_skb",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct sk_buff * sk_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "sk_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588391312,
      "name": "sk_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:854",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588391312,
      "name": "sk_stream_alloc_skb",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct sk_buff * sk_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "sk_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589115504,
      "name": "sk_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:854",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589115504,
      "name": "sk_stream_alloc_skb",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct sk_buff * sk_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "sk_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589155328,
      "name": "sk_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:854",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589155328,
      "name": "sk_stream_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 707
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct sk_buff * sk_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
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
