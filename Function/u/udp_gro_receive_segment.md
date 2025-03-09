# Function: <code>udp_gro_receive_segment</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "udp_gro_receive_segment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588606400,
      "name": "udp_gro_receive_segment",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:348",
      "file": "net/ipv4/udp_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp_gro_receive"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "udp_gro_receive_segment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589018045,
      "name": "udp_gro_receive_segment",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:349",
      "file": "net/ipv4/udp_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp_gro_receive"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "udp_gro_receive_segment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589242605,
      "name": "udp_gro_receive_segment",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:349",
      "file": "net/ipv4/udp_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp_gro_receive"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * udp_gro_receive_segment(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "udp_gro_receive_segment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590215680,
      "name": "udp_gro_receive_segment",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:366",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:udp_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590215680,
      "name": "udp_gro_receive_segment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
struct sk_buff * udp_gro_receive_segment(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "udp_gro_receive_segment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590270304,
      "name": "udp_gro_receive_segment",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:428",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:udp_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590270304,
      "name": "udp_gro_receive_segment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 569
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
struct sk_buff * udp_gro_receive_segment(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "udp_gro_receive_segment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590185024,
      "name": "udp_gro_receive_segment",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:428",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:udp_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590185024,
      "name": "udp_gro_receive_segment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
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
struct sk_buff * udp_gro_receive_segment(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "udp_gro_receive_segment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590965856,
      "name": "udp_gro_receive_segment",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:428",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:udp_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590965856,
      "name": "udp_gro_receive_segment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
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
struct sk_buff * udp_gro_receive_segment(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "udp_gro_receive_segment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592609040,
      "name": "udp_gro_receive_segment",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:456",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:udp_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592609040,
      "name": "udp_gro_receive_segment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
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
struct sk_buff * udp_gro_receive_segment(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "udp_gro_receive_segment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594473312,
      "name": "udp_gro_receive_segment",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:457",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:udp_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594473312,
      "name": "udp_gro_receive_segment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
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
struct sk_buff * udp_gro_receive_segment(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "udp_gro_receive_segment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594864608,
      "name": "udp_gro_receive_segment",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:464",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:udp_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594864608,
      "name": "udp_gro_receive_segment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 661
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
struct sk_buff * udp_gro_receive_segment(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "udp_gro_receive_segment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595675936,
      "name": "udp_gro_receive_segment",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:464",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:udp_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595675936,
      "name": "udp_gro_receive_segment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 661
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "udp_gro_receive_segment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502870732,
      "name": "udp_gro_receive_segment",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:349",
      "file": "net/ipv4/udp_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp_gro_receive"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "udp_gro_receive_segment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235566080,
      "name": "udp_gro_receive_segment",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:349",
      "file": "net/ipv4/udp_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp_gro_receive"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "udp_gro_receive_segment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296531240,
      "name": "udp_gro_receive_segment",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:349",
      "file": "net/ipv4/udp_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp_gro_receive"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "udp_gro_receive_segment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278972882,
      "name": "udp_gro_receive_segment",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:349",
      "file": "net/ipv4/udp_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp_gro_receive"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "udp_gro_receive_segment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588848989,
      "name": "udp_gro_receive_segment",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:349",
      "file": "net/ipv4/udp_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp_gro_receive"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "udp_gro_receive_segment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588560925,
      "name": "udp_gro_receive_segment",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:349",
      "file": "net/ipv4/udp_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp_gro_receive"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "udp_gro_receive_segment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589285165,
      "name": "udp_gro_receive_segment",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:349",
      "file": "net/ipv4/udp_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp_gro_receive"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "udp_gro_receive_segment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589326610,
      "name": "udp_gro_receive_segment",
      "external": false,
      "loc": "net/ipv4/udp_offload.c:349",
      "file": "net/ipv4/udp_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp_gro_receive"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct sk_buff * udp_gro_receive_segment(struct list_head * head, struct sk_buff * skb)
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
