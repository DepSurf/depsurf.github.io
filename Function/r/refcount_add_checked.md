# Function: <code>refcount_add_checked</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void refcount_add_checked(unsigned int i, refcount_t * r)
```

```json
{
  "name": "refcount_add_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583965456,
      "name": "refcount_add_checked",
      "external": true,
      "loc": "lib/refcount.c:100",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583965456,
      "name": "refcount_add_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void refcount_add_checked(unsigned int i, refcount_t * r)
```

```json
{
  "name": "refcount_add_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584145328,
      "name": "refcount_add_checked",
      "external": true,
      "loc": "lib/refcount.c:103",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584145328,
      "name": "refcount_add_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void refcount_add_checked(unsigned int i, refcount_t * r)
```

```json
{
  "name": "refcount_add_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584267776,
      "name": "refcount_add_checked",
      "external": true,
      "loc": "lib/refcount.c:103",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584267776,
      "name": "refcount_add_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
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
void refcount_add_checked(unsigned int i, refcount_t * r)
```

```json
{
  "name": "refcount_add_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496151656,
      "name": "refcount_add_checked",
      "external": true,
      "loc": "lib/refcount.c:103",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "fs/io_uring.c:__arm64_sys_io_uring_register",
        "net/core/sock.c:skb_set_owner_w",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/packet/af_packet.c:tpacket_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496151656,
      "name": "refcount_add_checked",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void refcount_add_checked(unsigned int i, refcount_t * r)
```

```json
{
  "name": "refcount_add_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229472016,
      "name": "refcount_add_checked",
      "external": true,
      "loc": "lib/refcount.c:103",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "fs/io_uring.c:__se_sys_io_uring_register",
        "net/core/sock.c:skb_set_owner_w",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/ipv6/ip6_output.c:__ip6_append_data",
        "net/ipv6/ip6_output.c:__ip6_append_data",
        "net/packet/af_packet.c:tpacket_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229472016,
      "name": "refcount_add_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void refcount_add_checked(unsigned int i, refcount_t * r)
```

```json
{
  "name": "refcount_add_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290411200,
      "name": "refcount_add_checked",
      "external": true,
      "loc": "lib/refcount.c:103",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290411200,
      "name": "refcount_add_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void refcount_add_checked(unsigned int i, refcount_t * r)
```

```json
{
  "name": "refcount_add_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275204738,
      "name": "refcount_add_checked",
      "external": true,
      "loc": "lib/refcount.c:103",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275204738,
      "name": "refcount_add_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void refcount_add_checked(unsigned int i, refcount_t * r)
```

```json
{
  "name": "refcount_add_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584236512,
      "name": "refcount_add_checked",
      "external": true,
      "loc": "lib/refcount.c:103",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584236512,
      "name": "refcount_add_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void refcount_add_checked(unsigned int i, refcount_t * r)
```

```json
{
  "name": "refcount_add_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584171712,
      "name": "refcount_add_checked",
      "external": true,
      "loc": "lib/refcount.c:103",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584171712,
      "name": "refcount_add_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void refcount_add_checked(unsigned int i, refcount_t * r)
```

```json
{
  "name": "refcount_add_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584220272,
      "name": "refcount_add_checked",
      "external": true,
      "loc": "lib/refcount.c:103",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584220272,
      "name": "refcount_add_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void refcount_add_checked(unsigned int i, refcount_t * r)
```

```json
{
  "name": "refcount_add_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584325104,
      "name": "refcount_add_checked",
      "external": true,
      "loc": "lib/refcount.c:103",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584325104,
      "name": "refcount_add_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void refcount_add_checked(unsigned int i, refcount_t * r)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void refcount_add_checked(unsigned int i, refcount_t * r)
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
