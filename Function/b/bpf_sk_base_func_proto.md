# Function: <code>bpf_sk_base_func_proto</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct bpf_func_proto * bpf_sk_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_sk_base_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589542256,
      "name": "bpf_sk_base_func_proto",
      "external": false,
      "loc": "net/core/filter.c:10438",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:flow_dissector_func_proto"
      ],
      "caller_func": [
        "net/core/filter.c:sk_lookup_func_proto",
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_in_func_proto",
        "net/core/filter.c:sk_skb_func_proto",
        "net/core/filter.c:sk_msg_func_proto",
        "net/core/filter.c:sock_ops_func_proto",
        "net/core/filter.c:xdp_func_proto",
        "net/core/filter.c:tc_cls_act_func_proto",
        "net/core/filter.c:cg_skb_func_proto",
        "net/core/filter.c:sock_addr_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589508336,
      "name": "bpf_sk_base_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
const struct bpf_func_proto * bpf_sk_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_sk_base_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589439536,
      "name": "bpf_sk_base_func_proto",
      "external": false,
      "loc": "net/core/filter.c:10580",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:flow_dissector_func_proto"
      ],
      "caller_func": [
        "net/core/filter.c:sk_lookup_func_proto",
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_in_func_proto",
        "net/core/filter.c:sk_skb_func_proto",
        "net/core/filter.c:sk_msg_func_proto",
        "net/core/filter.c:sock_ops_func_proto",
        "net/core/filter.c:xdp_func_proto",
        "net/core/filter.c:tc_cls_act_func_proto",
        "net/core/filter.c:cg_skb_func_proto",
        "net/core/filter.c:sock_addr_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589407168,
      "name": "bpf_sk_base_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
const struct bpf_func_proto * bpf_sk_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_sk_base_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590177616,
      "name": "bpf_sk_base_func_proto",
      "external": false,
      "loc": "net/core/filter.c:10779",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:flow_dissector_func_proto"
      ],
      "caller_func": [
        "net/core/filter.c:sk_lookup_func_proto",
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_in_func_proto",
        "net/core/filter.c:sk_skb_func_proto",
        "net/core/filter.c:sk_msg_func_proto",
        "net/core/filter.c:sock_ops_func_proto",
        "net/core/filter.c:xdp_func_proto",
        "net/core/filter.c:tc_cls_act_func_proto",
        "net/core/filter.c:cg_skb_func_proto",
        "net/core/filter.c:sock_addr_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590130960,
      "name": "bpf_sk_base_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
const struct bpf_func_proto * bpf_sk_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_sk_base_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591682976,
      "name": "bpf_sk_base_func_proto",
      "external": false,
      "loc": "net/core/filter.c:11341",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup_func_proto",
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_in_func_proto",
        "net/core/filter.c:flow_dissector_func_proto",
        "net/core/filter.c:sk_skb_func_proto",
        "net/core/filter.c:sk_msg_func_proto",
        "net/core/filter.c:sock_ops_func_proto",
        "net/core/filter.c:xdp_func_proto",
        "net/core/filter.c:tc_cls_act_func_proto",
        "net/core/filter.c:cg_skb_func_proto",
        "net/core/filter.c:sock_addr_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591682976,
      "name": "bpf_sk_base_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
const struct bpf_func_proto * bpf_sk_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_sk_base_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593469552,
      "name": "bpf_sk_base_func_proto",
      "external": false,
      "loc": "net/core/filter.c:11547",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup_func_proto",
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_in_func_proto",
        "net/core/filter.c:flow_dissector_func_proto",
        "net/core/filter.c:sk_skb_func_proto",
        "net/core/filter.c:sk_msg_func_proto",
        "net/core/filter.c:xdp_func_proto",
        "net/core/filter.c:tc_cls_act_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593469552,
      "name": "bpf_sk_base_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
const struct bpf_func_proto * bpf_sk_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_sk_base_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593936368,
      "name": "bpf_sk_base_func_proto",
      "external": false,
      "loc": "net/core/filter.c:11696",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup_func_proto",
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_in_func_proto",
        "net/core/filter.c:flow_dissector_func_proto",
        "net/core/filter.c:sk_skb_func_proto",
        "net/core/filter.c:sk_msg_func_proto",
        "net/core/filter.c:xdp_func_proto",
        "net/core/filter.c:tc_cls_act_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593936368,
      "name": "bpf_sk_base_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
const struct bpf_func_proto * bpf_sk_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_sk_base_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594719136,
      "name": "bpf_sk_base_func_proto",
      "external": false,
      "loc": "net/core/filter.c:11787",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup_func_proto",
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_in_func_proto",
        "net/core/filter.c:flow_dissector_func_proto",
        "net/core/filter.c:sk_skb_func_proto",
        "net/core/filter.c:sk_msg_func_proto",
        "net/core/filter.c:xdp_func_proto",
        "net/core/filter.c:tc_cls_act_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594719136,
      "name": "bpf_sk_base_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
const struct bpf_func_proto * bpf_sk_base_func_proto(enum bpf_func_id func_id)
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
