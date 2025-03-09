# Function: <code>tcp_stream_alloc_skb</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * tcp_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "tcp_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592385088,
      "name": "tcp_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:854",
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
      "addr": 18446744071592385088,
      "name": "tcp_stream_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 553
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
struct sk_buff * tcp_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "tcp_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594235808,
      "name": "tcp_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:858",
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
      "addr": 18446744071594235808,
      "name": "tcp_stream_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
struct sk_buff * tcp_stream_alloc_skb(struct sock * sk, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "tcp_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594622640,
      "name": "tcp_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:862",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
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
      "addr": 18446744071594622640,
      "name": "tcp_stream_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
struct sk_buff * tcp_stream_alloc_skb(struct sock * sk, gfp_t gfp, bool force_schedule)
```

```json
{
  "name": "tcp_stream_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595425648,
      "name": "tcp_stream_alloc_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:867",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
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
      "addr": 18446744071595425648,
      "name": "tcp_stream_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct sk_buff * tcp_stream_alloc_skb(struct sock * sk, int size, gfp_t gfp, bool force_schedule)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int size</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, size, gfp, force_schedule</code> ➡️ <code>sk, gfp, force_schedule</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
