# Function: <code>skb_gro_receive_list</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int skb_gro_receive_list(struct sk_buff * p, struct sk_buff * skb)
```

```json
{
  "name": "skb_gro_receive_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589275536,
      "name": "skb_gro_receive_list",
      "external": true,
      "loc": "net/core/skbuff.c:3708",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:udp_gro_receive_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589275536,
      "name": "skb_gro_receive_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int skb_gro_receive_list(struct sk_buff * p, struct sk_buff * skb)
```

```json
{
  "name": "skb_gro_receive_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589275520,
      "name": "skb_gro_receive_list",
      "external": true,
      "loc": "net/core/skbuff.c:3776",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:udp_gro_receive_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589275520,
      "name": "skb_gro_receive_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int skb_gro_receive_list(struct sk_buff * p, struct sk_buff * skb)
```

```json
{
  "name": "skb_gro_receive_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589169584,
      "name": "skb_gro_receive_list",
      "external": true,
      "loc": "net/core/skbuff.c:3861",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:udp_gro_receive_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589169584,
      "name": "skb_gro_receive_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int skb_gro_receive_list(struct sk_buff * p, struct sk_buff * skb)
```

```json
{
  "name": "skb_gro_receive_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589890368,
      "name": "skb_gro_receive_list",
      "external": true,
      "loc": "net/core/skbuff.c:3921",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:udp_gro_receive_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589890368,
      "name": "skb_gro_receive_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "skb_gro_receive_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592609466,
      "name": "skb_gro_receive_list",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:428",
      "file": "net/ipv4/udp_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp_gro_receive_segment"
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
  "name": "skb_gro_receive_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594473738,
      "name": "skb_gro_receive_list",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:429",
      "file": "net/ipv4/udp_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp_gro_receive_segment"
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
  "name": "skb_gro_receive_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594865030,
      "name": "skb_gro_receive_list",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:436",
      "file": "net/ipv4/udp_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp_gro_receive_segment"
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
  "name": "skb_gro_receive_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595676358,
      "name": "skb_gro_receive_list",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:436",
      "file": "net/ipv4/udp_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp_gro_receive_segment"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int skb_gro_receive_list(struct sk_buff * p, struct sk_buff * skb)
```
</details>
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
int skb_gro_receive_list(struct sk_buff * p, struct sk_buff * skb)
```
</details>
</li>
</ul>
