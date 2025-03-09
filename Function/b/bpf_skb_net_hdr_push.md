# Function: <code>bpf_skb_net_hdr_push</code>

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
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586830549,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:1809",
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
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587021621,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:1931",
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
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587149315,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:1975",
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
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587656915,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:2040",
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
int bpf_skb_net_hdr_push(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587961184,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:2557",
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
      "addr": 18446744071587961184,
      "name": "bpf_skb_net_hdr_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int bpf_skb_net_hdr_push(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588111248,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:2749",
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
      "addr": 18446744071588111248,
      "name": "bpf_skb_net_hdr_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int bpf_skb_net_hdr_push(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588428656,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:2795",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588428656,
      "name": "bpf_skb_net_hdr_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int bpf_skb_net_hdr_push(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588634224,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:2797",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588634224,
      "name": "bpf_skb_net_hdr_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int bpf_skb_net_hdr_push(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589501152,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:2835",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_net_grow",
        "net/core/filter.c:bpf_skb_net_grow",
        "net/core/filter.c:bpf_skb_proto_4_to_6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589501152,
      "name": "bpf_skb_net_hdr_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int bpf_skb_net_hdr_push(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589503552,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:3204",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_net_grow",
        "net/core/filter.c:bpf_skb_net_grow",
        "net/core/filter.c:bpf_skb_proto_4_to_6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589503552,
      "name": "bpf_skb_net_hdr_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int bpf_skb_net_hdr_push(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589401760,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:3201",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_net_grow",
        "net/core/filter.c:bpf_skb_net_grow",
        "net/core/filter.c:bpf_skb_change_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589401760,
      "name": "bpf_skb_net_hdr_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int bpf_skb_net_hdr_push(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590127872,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:3188",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_net_grow",
        "net/core/filter.c:bpf_skb_net_grow",
        "net/core/filter.c:bpf_skb_change_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590127872,
      "name": "bpf_skb_net_hdr_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int bpf_skb_net_hdr_push(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591679216,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:3189",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_net_grow",
        "net/core/filter.c:bpf_skb_net_grow",
        "net/core/filter.c:bpf_skb_change_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591679216,
      "name": "bpf_skb_net_hdr_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593511895,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:3199",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_net_grow",
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
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593974951,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:3215",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_net_grow",
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
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594759799,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:3249",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_net_grow",
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
int bpf_skb_net_hdr_push(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502180792,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:2797",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502180792,
      "name": "bpf_skb_net_hdr_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int bpf_skb_net_hdr_push(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234927524,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:2797",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234927524,
      "name": "bpf_skb_net_hdr_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
int bpf_skb_net_hdr_push(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295654848,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:2797",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295654848,
      "name": "bpf_skb_net_hdr_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int bpf_skb_net_hdr_push(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278435194,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:2797",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278435194,
      "name": "bpf_skb_net_hdr_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int bpf_skb_net_hdr_push(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588240960,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:2797",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588240960,
      "name": "bpf_skb_net_hdr_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int bpf_skb_net_hdr_push(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587953776,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:2797",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587953776,
      "name": "bpf_skb_net_hdr_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int bpf_skb_net_hdr_push(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588572784,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:2797",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588572784,
      "name": "bpf_skb_net_hdr_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int bpf_skb_net_hdr_push(struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "bpf_skb_net_hdr_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588710272,
      "name": "bpf_skb_net_hdr_push",
      "external": false,
      "loc": "net/core/filter.c:2797",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588710272,
      "name": "bpf_skb_net_hdr_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int bpf_skb_net_hdr_push(struct sk_buff * skb, u32 off, u32 len)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int bpf_skb_net_hdr_push(struct sk_buff * skb, u32 off, u32 len)
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
