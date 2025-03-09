# Function: <code>bpf_skb_generic_pop</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586830048,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:1794",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_change_proto"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587021120,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:1916",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_change_proto"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int bpf_skb_generic_pop(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587147856,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:1960",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587147856,
      "name": "bpf_skb_generic_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int bpf_skb_generic_pop(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587655328,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:2025",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587655328,
      "name": "bpf_skb_generic_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587978637,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:2542",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588130343,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:2734",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
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
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588445143,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:2780",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
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
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588650871,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:2782",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
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
int bpf_skb_generic_pop(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589517760,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:2820",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_net_shrink",
        "net/core/filter.c:bpf_skb_proto_6_to_4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589517760,
      "name": "bpf_skb_generic_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
int bpf_skb_generic_pop(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589524560,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:3189",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_net_shrink",
        "net/core/filter.c:bpf_skb_proto_6_to_4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589524560,
      "name": "bpf_skb_generic_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589424279,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:3186",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590150439,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:3173",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591713127,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:3174",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int bpf_skb_generic_pop(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593499616,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:3181",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593499616,
      "name": "bpf_skb_generic_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int bpf_skb_generic_pop(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593964576,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:3197",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593964576,
      "name": "bpf_skb_generic_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int bpf_skb_generic_pop(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594747136,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:3231",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594747136,
      "name": "bpf_skb_generic_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502197068,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:2782",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
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
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234948612,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:2782",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
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
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295691012,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:2782",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
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
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278454646,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:2782",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
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
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588257607,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:2782",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
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
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587970423,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:2782",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
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
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588589431,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:2782",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
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
  "name": "bpf_skb_generic_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588726919,
      "name": "bpf_skb_generic_pop",
      "external": false,
      "loc": "net/core/filter.c:2782",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int bpf_skb_generic_pop(struct sk_buff * skb, u32 off, u32 len)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int bpf_skb_generic_pop(struct sk_buff * skb, u32 off, u32 len)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int bpf_skb_generic_pop(struct sk_buff * skb, u32 off, u32 len)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int bpf_skb_generic_pop(struct sk_buff * skb, u32 off, u32 len)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int bpf_skb_generic_pop(struct sk_buff * skb, u32 off, u32 len)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
