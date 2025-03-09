# Function: <code>seg6_lookup_nexthop</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int seg6_lookup_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id)
```

```json
{
  "name": "seg6_lookup_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588973696,
      "name": "seg6_lookup_nexthop",
      "external": true,
      "loc": "net/ipv6/seg6_local.c:152",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588973696,
      "name": "seg6_lookup_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
int seg6_lookup_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id)
```

```json
{
  "name": "seg6_lookup_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589197728,
      "name": "seg6_lookup_nexthop",
      "external": true,
      "loc": "net/ipv6/seg6_local.c:152",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589197728,
      "name": "seg6_lookup_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int seg6_lookup_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id)
```

```json
{
  "name": "seg6_lookup_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "seg6_lookup_nexthop",
      "external": true,
      "loc": "net/ipv6/seg6_local.c:147",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589653644,
      "name": "seg6_lookup_nexthop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071589651280,
      "name": "seg6_lookup_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
int seg6_lookup_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id)
```

```json
{
  "name": "seg6_lookup_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589875632,
      "name": "seg6_lookup_nexthop",
      "external": true,
      "loc": "net/ipv6/seg6_local.c:154",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589875632,
      "name": "seg6_lookup_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_lookup_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id)
```

```json
{
  "name": "seg6_lookup_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590905768,
      "name": "seg6_lookup_nexthop",
      "external": true,
      "loc": "net/ipv6/seg6_local.c:212",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_push_seg6_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590905296,
      "name": "seg6_lookup_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_lookup_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id)
```

```json
{
  "name": "seg6_lookup_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590969405,
      "name": "seg6_lookup_nexthop",
      "external": true,
      "loc": "net/ipv6/seg6_local.c:265",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_push_seg6_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590968912,
      "name": "seg6_lookup_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_lookup_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id)
```

```json
{
  "name": "seg6_lookup_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590900214,
      "name": "seg6_lookup_nexthop",
      "external": true,
      "loc": "net/ipv6/seg6_local.c:294",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_push_seg6_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590899568,
      "name": "seg6_lookup_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_lookup_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id)
```

```json
{
  "name": "seg6_lookup_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591733845,
      "name": "seg6_lookup_nexthop",
      "external": true,
      "loc": "net/ipv6/seg6_local.c:266",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_push_seg6_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591733168,
      "name": "seg6_lookup_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_lookup_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id)
```

```json
{
  "name": "seg6_lookup_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593435942,
      "name": "seg6_lookup_nexthop",
      "external": true,
      "loc": "net/ipv6/seg6_local.c:268",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_push_seg6_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593435328,
      "name": "seg6_lookup_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_lookup_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id)
```

```json
{
  "name": "seg6_lookup_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595351014,
      "name": "seg6_lookup_nexthop",
      "external": true,
      "loc": "net/ipv6/seg6_local.c:319",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_push_seg6_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595350368,
      "name": "seg6_lookup_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_lookup_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id)
```

```json
{
  "name": "seg6_lookup_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595748358,
      "name": "seg6_lookup_nexthop",
      "external": true,
      "loc": "net/ipv6/seg6_local.c:326",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end",
        "net/ipv6/seg6_local.c:end_flv8986_core"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_push_seg6_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595747712,
      "name": "seg6_lookup_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_lookup_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id)
```

```json
{
  "name": "seg6_lookup_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596596534,
      "name": "seg6_lookup_nexthop",
      "external": true,
      "loc": "net/ipv6/seg6_local.c:330",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end",
        "net/ipv6/seg6_local.c:end_flv8986_core",
        "net/ipv6/seg6_local.c:input_action_end_x_core"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_push_seg6_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596595888,
      "name": "seg6_lookup_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int seg6_lookup_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id)
```

```json
{
  "name": "seg6_lookup_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503595072,
      "name": "seg6_lookup_nexthop",
      "external": true,
      "loc": "net/ipv6/seg6_local.c:154",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503595072,
      "name": "seg6_lookup_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
int seg6_lookup_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id)
```

```json
{
  "name": "seg6_lookup_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236240300,
      "name": "seg6_lookup_nexthop",
      "external": true,
      "loc": "net/ipv6/seg6_local.c:154",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap",
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236240300,
      "name": "seg6_lookup_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
int seg6_lookup_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id)
```

```json
{
  "name": "seg6_lookup_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297404864,
      "name": "seg6_lookup_nexthop",
      "external": true,
      "loc": "net/ipv6/seg6_local.c:154",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297404864,
      "name": "seg6_lookup_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
int seg6_lookup_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id)
```

```json
{
  "name": "seg6_lookup_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279548634,
      "name": "seg6_lookup_nexthop",
      "external": true,
      "loc": "net/ipv6/seg6_local.c:154",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279548634,
      "name": "seg6_lookup_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int seg6_lookup_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id)
```

```json
{
  "name": "seg6_lookup_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589480000,
      "name": "seg6_lookup_nexthop",
      "external": true,
      "loc": "net/ipv6/seg6_local.c:154",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589480000,
      "name": "seg6_lookup_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
int seg6_lookup_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id)
```

```json
{
  "name": "seg6_lookup_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589204992,
      "name": "seg6_lookup_nexthop",
      "external": true,
      "loc": "net/ipv6/seg6_local.c:154",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589204992,
      "name": "seg6_lookup_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
int seg6_lookup_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id)
```

```json
{
  "name": "seg6_lookup_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589916864,
      "name": "seg6_lookup_nexthop",
      "external": true,
      "loc": "net/ipv6/seg6_local.c:154",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589916864,
      "name": "seg6_lookup_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
int seg6_lookup_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id)
```

```json
{
  "name": "seg6_lookup_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589969472,
      "name": "seg6_lookup_nexthop",
      "external": true,
      "loc": "net/ipv6/seg6_local.c:154",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589969472,
      "name": "seg6_lookup_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
int seg6_lookup_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id)
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
