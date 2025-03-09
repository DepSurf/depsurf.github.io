# Function: <code>nf_checksum</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
__sum16 nf_checksum(struct sk_buff * skb, unsigned int hook, unsigned int dataoff, u_int8_t protocol, short unsigned int family)
```

```json
{
  "name": "nf_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588158544,
      "name": "nf_checksum",
      "external": true,
      "loc": "net/netfilter/utils.c:7",
      "file": "net/netfilter/utils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588158544,
      "name": "nf_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
__sum16 nf_checksum(struct sk_buff * skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family)
```

```json
{
  "name": "nf_checksum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588342240,
      "name": "nf_checksum",
      "external": true,
      "loc": "net/netfilter/utils.c:122",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588342240,
      "name": "nf_checksum",
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
__sum16 nf_checksum(struct sk_buff * skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family)
```

```json
{
  "name": "nf_checksum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588742560,
      "name": "nf_checksum",
      "external": true,
      "loc": "net/netfilter/utils.c:123",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588742560,
      "name": "nf_checksum",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff * skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family)
```

```json
{
  "name": "nf_checksum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588966288,
      "name": "nf_checksum",
      "external": true,
      "loc": "net/netfilter/utils.c:123",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588966288,
      "name": "nf_checksum",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff * skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family)
```

```json
{
  "name": "nf_checksum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589921520,
      "name": "nf_checksum",
      "external": true,
      "loc": "net/netfilter/utils.c:123",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589921520,
      "name": "nf_checksum",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff * skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family)
```

```json
{
  "name": "nf_checksum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589962176,
      "name": "nf_checksum",
      "external": true,
      "loc": "net/netfilter/utils.c:123",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589962176,
      "name": "nf_checksum",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff * skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family)
```

```json
{
  "name": "nf_checksum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589876912,
      "name": "nf_checksum",
      "external": true,
      "loc": "net/netfilter/utils.c:123",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589876912,
      "name": "nf_checksum",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff * skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family)
```

```json
{
  "name": "nf_checksum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590640544,
      "name": "nf_checksum",
      "external": true,
      "loc": "net/netfilter/utils.c:123",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590640544,
      "name": "nf_checksum",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff * skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family)
```

```json
{
  "name": "nf_checksum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592264608,
      "name": "nf_checksum",
      "external": true,
      "loc": "net/netfilter/utils.c:123",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592264608,
      "name": "nf_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
__sum16 nf_checksum(struct sk_buff * skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family)
```

```json
{
  "name": "nf_checksum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594099344,
      "name": "nf_checksum",
      "external": true,
      "loc": "net/netfilter/utils.c:123",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594099344,
      "name": "nf_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
__sum16 nf_checksum(struct sk_buff * skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family)
```

```json
{
  "name": "nf_checksum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594484496,
      "name": "nf_checksum",
      "external": true,
      "loc": "net/netfilter/utils.c:123",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594484496,
      "name": "nf_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
__sum16 nf_checksum(struct sk_buff * skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family)
```

```json
{
  "name": "nf_checksum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595286720,
      "name": "nf_checksum",
      "external": true,
      "loc": "net/netfilter/utils.c:123",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595286720,
      "name": "nf_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
__sum16 nf_checksum(struct sk_buff * skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family)
```

```json
{
  "name": "nf_checksum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502569344,
      "name": "nf_checksum",
      "external": true,
      "loc": "net/netfilter/utils.c:123",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502569344,
      "name": "nf_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
__sum16 nf_checksum(struct sk_buff * skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family)
```

```json
{
  "name": "nf_checksum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235275164,
      "name": "nf_checksum",
      "external": true,
      "loc": "net/netfilter/utils.c:123",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235275164,
      "name": "nf_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
__sum16 nf_checksum(struct sk_buff * skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family)
```

```json
{
  "name": "nf_checksum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296153024,
      "name": "nf_checksum",
      "external": true,
      "loc": "net/netfilter/utils.c:123",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296153024,
      "name": "nf_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
__sum16 nf_checksum(struct sk_buff * skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family)
```

```json
{
  "name": "nf_checksum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278727116,
      "name": "nf_checksum",
      "external": true,
      "loc": "net/netfilter/utils.c:123",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278727116,
      "name": "nf_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
__sum16 nf_checksum(struct sk_buff * skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family)
```

```json
{
  "name": "nf_checksum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588572672,
      "name": "nf_checksum",
      "external": true,
      "loc": "net/netfilter/utils.c:123",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588572672,
      "name": "nf_checksum",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff * skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family)
```

```json
{
  "name": "nf_checksum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588284656,
      "name": "nf_checksum",
      "external": true,
      "loc": "net/netfilter/utils.c:123",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588284656,
      "name": "nf_checksum",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff * skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family)
```

```json
{
  "name": "nf_checksum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588904848,
      "name": "nf_checksum",
      "external": true,
      "loc": "net/netfilter/utils.c:123",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet",
        "net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udp_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588904848,
      "name": "nf_checksum",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
__sum16 nf_checksum(struct sk_buff * skb, unsigned int hook, unsigned int dataoff, u8 protocol, short unsigned int family)
```

```json
{
  "name": "nf_checksum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589047408,
      "name": "nf_checksum",
      "external": true,
      "loc": "net/netfilter/utils.c:123",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589047408,
      "name": "nf_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
__sum16 nf_checksum(struct sk_buff * skb, unsigned int hook, unsigned int dataoff, u_int8_t protocol, short unsigned int family)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u_int8_t protocol</code> ➡️ <code>u8 protocol</code>
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
