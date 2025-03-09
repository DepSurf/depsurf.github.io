# Function: <code>bpf_skb_net_hdr_pop</code>

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
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586830048,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:1829",
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
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587021120,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:1951",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587149550,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:1995",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_adjust_room",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587657164,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:2060",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_adjust_room",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int bpf_skb_net_hdr_pop(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587978576,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:2577",
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
      "addr": 18446744071587978576,
      "name": "bpf_skb_net_hdr_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
int bpf_skb_net_hdr_pop(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588130288,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:2769",
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
      "addr": 18446744071588130288,
      "name": "bpf_skb_net_hdr_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
int bpf_skb_net_hdr_pop(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588445088,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:2815",
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
      "addr": 18446744071588445088,
      "name": "bpf_skb_net_hdr_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
int bpf_skb_net_hdr_pop(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588650816,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:2817",
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
      "addr": 18446744071588650816,
      "name": "bpf_skb_net_hdr_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589529014,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:2855",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_net_shrink",
        "net/core/filter.c:bpf_skb_proto_6_to_4"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589538023,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:3224",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_net_shrink",
        "net/core/filter.c:bpf_skb_proto_6_to_4"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int bpf_skb_net_hdr_pop(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589424224,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:3221",
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
      "addr": 18446744071589424224,
      "name": "bpf_skb_net_hdr_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
int bpf_skb_net_hdr_pop(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590150384,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:3208",
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
      "addr": 18446744071590150384,
      "name": "bpf_skb_net_hdr_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
int bpf_skb_net_hdr_pop(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591713072,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:3209",
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
      "addr": 18446744071591713072,
      "name": "bpf_skb_net_hdr_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593512180,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:3219",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_adjust_room",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593975236,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:3235",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_adjust_room",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594760084,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:3269",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_adjust_room",
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int bpf_skb_net_hdr_pop(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502197008,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:2817",
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
      "addr": 18446603336502197008,
      "name": "bpf_skb_net_hdr_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int bpf_skb_net_hdr_pop(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234948556,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:2817",
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
      "addr": 3234948556,
      "name": "bpf_skb_net_hdr_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
int bpf_skb_net_hdr_pop(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295690944,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:2817",
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
      "addr": 13835058055295690944,
      "name": "bpf_skb_net_hdr_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
int bpf_skb_net_hdr_pop(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278454610,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:2817",
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
      "addr": 18446743936278454610,
      "name": "bpf_skb_net_hdr_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int bpf_skb_net_hdr_pop(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588257552,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:2817",
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
      "addr": 18446744071588257552,
      "name": "bpf_skb_net_hdr_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
int bpf_skb_net_hdr_pop(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587970368,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:2817",
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
      "addr": 18446744071587970368,
      "name": "bpf_skb_net_hdr_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
int bpf_skb_net_hdr_pop(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588589376,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:2817",
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
      "addr": 18446744071588589376,
      "name": "bpf_skb_net_hdr_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
int bpf_skb_net_hdr_pop(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588726864,
      "name": "bpf_skb_net_hdr_pop",
      "external": false,
      "loc": "net/core/filter.c:2817",
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
      "addr": 18446744071588726864,
      "name": "bpf_skb_net_hdr_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
int bpf_skb_net_hdr_pop(struct sk_buff * skb, u32 off, u32 len)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int bpf_skb_net_hdr_pop(struct sk_buff * skb, u32 off, u32 len)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int bpf_skb_net_hdr_pop(struct sk_buff * skb, u32 off, u32 len)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int bpf_skb_net_hdr_pop(struct sk_buff * skb, u32 off, u32 len)
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
