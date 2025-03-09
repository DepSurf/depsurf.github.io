# Function: <code>seg6_lookup_any_nexthop</code>

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
int seg6_lookup_any_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id, bool local_delivery)
```

```json
{
  "name": "seg6_lookup_any_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590899584,
      "name": "seg6_lookup_any_nexthop",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:155",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071590899584,
      "name": "seg6_lookup_any_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
int seg6_lookup_any_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id, bool local_delivery)
```

```json
{
  "name": "seg6_lookup_any_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590960912,
      "name": "seg6_lookup_any_nexthop",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:208",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071590960912,
      "name": "seg6_lookup_any_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
int seg6_lookup_any_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id, bool local_delivery)
```

```json
{
  "name": "seg6_lookup_any_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590891056,
      "name": "seg6_lookup_any_nexthop",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:237",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071590891056,
      "name": "seg6_lookup_any_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
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
int seg6_lookup_any_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id, bool local_delivery)
```

```json
{
  "name": "seg6_lookup_any_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591728272,
      "name": "seg6_lookup_any_nexthop",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:209",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071591728272,
      "name": "seg6_lookup_any_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
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
int seg6_lookup_any_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id, bool local_delivery)
```

```json
{
  "name": "seg6_lookup_any_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593430080,
      "name": "seg6_lookup_any_nexthop",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:210",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071593430080,
      "name": "seg6_lookup_any_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
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
int seg6_lookup_any_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id, bool local_delivery)
```

```json
{
  "name": "seg6_lookup_any_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595344560,
      "name": "seg6_lookup_any_nexthop",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:261",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071595344560,
      "name": "seg6_lookup_any_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
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
int seg6_lookup_any_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id, bool local_delivery)
```

```json
{
  "name": "seg6_lookup_any_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595740080,
      "name": "seg6_lookup_any_nexthop",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:268",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap",
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end",
        "net/ipv6/seg6_local.c:end_flv8986_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595740080,
      "name": "seg6_lookup_any_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
int seg6_lookup_any_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id, bool local_delivery)
```

```json
{
  "name": "seg6_lookup_any_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596587920,
      "name": "seg6_lookup_any_nexthop",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:272",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap",
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end",
        "net/ipv6/seg6_local.c:end_flv8986_core",
        "net/ipv6/seg6_local.c:input_action_end_x_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596587920,
      "name": "seg6_lookup_any_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int seg6_lookup_any_nexthop(struct sk_buff * skb, struct in6_addr * nhaddr, u32 tbl_id, bool local_delivery)
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
