# Function: <code>__udpv4_gso_segment_csum</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __udpv4_gso_segment_csum(struct sk_buff * seg, __be32 * oldip, __be32 * newip, __be16 * oldport, __be16 * newport)
```

```json
{
  "name": "__udpv4_gso_segment_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590266096,
      "name": "__udpv4_gso_segment_csum",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:190",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:__udpv4_gso_segment_list_csum",
        "net/ipv4/udp_offload.c:__udpv4_gso_segment_list_csum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590266096,
      "name": "__udpv4_gso_segment_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
void __udpv4_gso_segment_csum(struct sk_buff * seg, __be32 * oldip, __be32 * newip, __be16 * oldport, __be16 * newport)
```

```json
{
  "name": "__udpv4_gso_segment_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590180912,
      "name": "__udpv4_gso_segment_csum",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:190",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590180912,
      "name": "__udpv4_gso_segment_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
void __udpv4_gso_segment_csum(struct sk_buff * seg, __be32 * oldip, __be32 * newip, __be16 * oldport, __be16 * newport)
```

```json
{
  "name": "__udpv4_gso_segment_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590961744,
      "name": "__udpv4_gso_segment_csum",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:190",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590961744,
      "name": "__udpv4_gso_segment_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
void __udpv4_gso_segment_csum(struct sk_buff * seg, __be32 * oldip, __be32 * newip, __be16 * oldport, __be16 * newport)
```

```json
{
  "name": "__udpv4_gso_segment_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592604768,
      "name": "__udpv4_gso_segment_csum",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:191",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592604768,
      "name": "__udpv4_gso_segment_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void __udpv4_gso_segment_csum(struct sk_buff * seg, __be32 * oldip, __be32 * newip, __be16 * oldport, __be16 * newport)
```

```json
{
  "name": "__udpv4_gso_segment_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594468896,
      "name": "__udpv4_gso_segment_csum",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:191",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594468896,
      "name": "__udpv4_gso_segment_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void __udpv4_gso_segment_csum(struct sk_buff * seg, __be32 * oldip, __be32 * newip, __be16 * oldport, __be16 * newport)
```

```json
{
  "name": "__udpv4_gso_segment_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594860128,
      "name": "__udpv4_gso_segment_csum",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:192",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594860128,
      "name": "__udpv4_gso_segment_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void __udpv4_gso_segment_csum(struct sk_buff * seg, __be32 * oldip, __be32 * newip, __be16 * oldport, __be16 * newport)
```

```json
{
  "name": "__udpv4_gso_segment_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595671456,
      "name": "__udpv4_gso_segment_csum",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:192",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595671456,
      "name": "__udpv4_gso_segment_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void __udpv4_gso_segment_csum(struct sk_buff * seg, __be32 * oldip, __be32 * newip, __be16 * oldport, __be16 * newport)
```
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
