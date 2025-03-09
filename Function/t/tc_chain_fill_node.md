# Function: <code>tc_chain_fill_node</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int tc_chain_fill_node(struct tcf_chain * chain, struct net * net, struct sk_buff * skb, struct tcf_block * block, u32 portid, u32 seq, u16 flags, int event)
```

```json
{
  "name": "tc_chain_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588276816,
      "name": "tc_chain_fill_node",
      "external": false,
      "loc": "net/sched/cls_api.c:2031",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_chain_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588276816,
      "name": "tc_chain_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
int tc_chain_fill_node(const struct tcf_proto_ops * tmplt_ops, void * tmplt_priv, u32 chain_index, struct net * net, struct sk_buff * skb, struct tcf_block * block, u32 portid, u32 seq, u16 flags, int event)
```

```json
{
  "name": "tc_chain_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tc_chain_fill_node",
      "external": false,
      "loc": "net/sched/cls_api.c:2641",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:__tcf_chain_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588668496,
      "name": "tc_chain_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    },
    {
      "addr": 18446744071588687014,
      "name": "tc_chain_fill_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int tc_chain_fill_node(const struct tcf_proto_ops * tmplt_ops, void * tmplt_priv, u32 chain_index, struct net * net, struct sk_buff * skb, struct tcf_block * block, u32 portid, u32 seq, u16 flags, int event)
```

```json
{
  "name": "tc_chain_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588891936,
      "name": "tc_chain_fill_node",
      "external": false,
      "loc": "net/sched/cls_api.c:2605",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:__tcf_chain_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588891936,
      "name": "tc_chain_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
int tc_chain_fill_node(const struct tcf_proto_ops * tmplt_ops, void * tmplt_priv, u32 chain_index, struct net * net, struct sk_buff * skb, struct tcf_block * block, u32 portid, u32 seq, u16 flags, int event)
```

```json
{
  "name": "tc_chain_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589780048,
      "name": "tc_chain_fill_node",
      "external": false,
      "loc": "net/sched/cls_api.c:2641",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:__tcf_chain_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589780048,
      "name": "tc_chain_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int tc_chain_fill_node(const struct tcf_proto_ops * tmplt_ops, void * tmplt_priv, u32 chain_index, struct net * net, struct sk_buff * skb, struct tcf_block * block, u32 portid, u32 seq, u16 flags, int event)
```

```json
{
  "name": "tc_chain_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tc_chain_fill_node",
      "external": false,
      "loc": "net/sched/cls_api.c:2642",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:__tcf_chain_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589815312,
      "name": "tc_chain_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
    },
    {
      "addr": 18446744071591633455,
      "name": "tc_chain_fill_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int tc_chain_fill_node(const struct tcf_proto_ops * tmplt_ops, void * tmplt_priv, u32 chain_index, struct net * net, struct sk_buff * skb, struct tcf_block * block, u32 portid, u32 seq, u16 flags, int event)
```

```json
{
  "name": "tc_chain_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tc_chain_fill_node",
      "external": false,
      "loc": "net/sched/cls_api.c:2643",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:__tcf_chain_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589716752,
      "name": "tc_chain_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
    },
    {
      "addr": 18446744071591576856,
      "name": "tc_chain_fill_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int tc_chain_fill_node(const struct tcf_proto_ops * tmplt_ops, void * tmplt_priv, u32 chain_index, struct net * net, struct sk_buff * skb, struct tcf_block * block, u32 portid, u32 seq, u16 flags, int event)
```

```json
{
  "name": "tc_chain_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tc_chain_fill_node",
      "external": false,
      "loc": "net/sched/cls_api.c:2643",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:__tcf_chain_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590474992,
      "name": "tc_chain_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
    },
    {
      "addr": 18446744071592710439,
      "name": "tc_chain_fill_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int tc_chain_fill_node(const struct tcf_proto_ops * tmplt_ops, void * tmplt_priv, u32 chain_index, struct net * net, struct sk_buff * skb, struct tcf_block * block, u32 portid, u32 seq, u16 flags, int event)
```

```json
{
  "name": "tc_chain_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tc_chain_fill_node",
      "external": false,
      "loc": "net/sched/cls_api.c:2662",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:__tcf_chain_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592080032,
      "name": "tc_chain_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
    },
    {
      "addr": 18446744071594596710,
      "name": "tc_chain_fill_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int tc_chain_fill_node(const struct tcf_proto_ops * tmplt_ops, void * tmplt_priv, u32 chain_index, struct net * net, struct sk_buff * skb, struct tcf_block * block, u32 portid, u32 seq, u16 flags, int event)
```

```json
{
  "name": "tc_chain_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593899216,
      "name": "tc_chain_fill_node",
      "external": false,
      "loc": "net/sched/cls_api.c:2666",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:__tcf_chain_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593899216,
      "name": "tc_chain_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
int tc_chain_fill_node(const struct tcf_proto_ops * tmplt_ops, void * tmplt_priv, u32 chain_index, struct net * net, struct sk_buff * skb, struct tcf_block * block, u32 portid, u32 seq, u16 flags, int event, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tc_chain_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594277872,
      "name": "tc_chain_fill_node",
      "external": false,
      "loc": "net/sched/cls_api.c:2822",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:__tcf_chain_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594277872,
      "name": "tc_chain_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
int tc_chain_fill_node(const struct tcf_proto_ops * tmplt_ops, void * tmplt_priv, u32 chain_index, struct net * net, struct sk_buff * skb, struct tcf_block * block, u32 portid, u32 seq, u16 flags, int event, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tc_chain_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595076608,
      "name": "tc_chain_fill_node",
      "external": false,
      "loc": "net/sched/cls_api.c:2875",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:__tcf_chain_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595076608,
      "name": "tc_chain_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
  "name": "tc_chain_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502483088,
      "name": "tc_chain_fill_node",
      "external": false,
      "loc": "net/sched/cls_api.c:2605",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:__tcf_chain_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502483088,
      "name": "tc_chain_fill_node.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
int tc_chain_fill_node(const struct tcf_proto_ops * tmplt_ops, void * tmplt_priv, u32 chain_index, struct net * net, struct sk_buff * skb, struct tcf_block * block, u32 portid, u32 seq, u16 flags, int event)
```

```json
{
  "name": "tc_chain_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235198672,
      "name": "tc_chain_fill_node",
      "external": false,
      "loc": "net/sched/cls_api.c:2605",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:__tcf_chain_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235198672,
      "name": "tc_chain_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
int tc_chain_fill_node(const struct tcf_proto_ops * tmplt_ops, void * tmplt_priv, u32 chain_index, struct net * net, struct sk_buff * skb, struct tcf_block * block, u32 portid, u32 seq, u16 flags, int event)
```

```json
{
  "name": "tc_chain_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296046384,
      "name": "tc_chain_fill_node",
      "external": false,
      "loc": "net/sched/cls_api.c:2605",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:__tcf_chain_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296046384,
      "name": "tc_chain_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
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
int tc_chain_fill_node(const struct tcf_proto_ops * tmplt_ops, void * tmplt_priv, u32 chain_index, struct net * net, struct sk_buff * skb, struct tcf_block * block, u32 portid, u32 seq, u16 flags, int event)
```

```json
{
  "name": "tc_chain_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278663798,
      "name": "tc_chain_fill_node",
      "external": false,
      "loc": "net/sched/cls_api.c:2605",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:__tcf_chain_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278663798,
      "name": "tc_chain_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int tc_chain_fill_node(const struct tcf_proto_ops * tmplt_ops, void * tmplt_priv, u32 chain_index, struct net * net, struct sk_buff * skb, struct tcf_block * block, u32 portid, u32 seq, u16 flags, int event)
```

```json
{
  "name": "tc_chain_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588498320,
      "name": "tc_chain_fill_node",
      "external": false,
      "loc": "net/sched/cls_api.c:2605",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:__tcf_chain_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588498320,
      "name": "tc_chain_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
int tc_chain_fill_node(const struct tcf_proto_ops * tmplt_ops, void * tmplt_priv, u32 chain_index, struct net * net, struct sk_buff * skb, struct tcf_block * block, u32 portid, u32 seq, u16 flags, int event)
```

```json
{
  "name": "tc_chain_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588210320,
      "name": "tc_chain_fill_node",
      "external": false,
      "loc": "net/sched/cls_api.c:2605",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:__tcf_chain_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588210320,
      "name": "tc_chain_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
int tc_chain_fill_node(const struct tcf_proto_ops * tmplt_ops, void * tmplt_priv, u32 chain_index, struct net * net, struct sk_buff * skb, struct tcf_block * block, u32 portid, u32 seq, u16 flags, int event)
```

```json
{
  "name": "tc_chain_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588830496,
      "name": "tc_chain_fill_node",
      "external": false,
      "loc": "net/sched/cls_api.c:2605",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:__tcf_chain_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588830496,
      "name": "tc_chain_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
int tc_chain_fill_node(const struct tcf_proto_ops * tmplt_ops, void * tmplt_priv, u32 chain_index, struct net * net, struct sk_buff * skb, struct tcf_block * block, u32 portid, u32 seq, u16 flags, int event)
```

```json
{
  "name": "tc_chain_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588973856,
      "name": "tc_chain_fill_node",
      "external": false,
      "loc": "net/sched/cls_api.c:2605",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:__tcf_chain_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588973856,
      "name": "tc_chain_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int tc_chain_fill_node(struct tcf_chain * chain, struct net * net, struct sk_buff * skb, struct tcf_block * block, u32 portid, u32 seq, u16 flags, int event)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct tcf_proto_ops * tmplt_ops</code>
</li>
<li>
<b>Param added. </b>
<code>void * tmplt_priv</code>
</li>
<li>
<b>Param added. </b>
<code>u32 chain_index</code>
</li>
<li>
<b>Param removed. </b>
<code>struct tcf_chain * chain</code>
</li>
<li>
<b>Param reordered. </b>
<code>chain, net, skb, block, portid, seq, flags, event</code> ➡️ <code>tmplt_ops, tmplt_priv, chain_index, net, skb, block, portid, seq, flags, event</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack * extack</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int tc_chain_fill_node(const struct tcf_proto_ops * tmplt_ops, void * tmplt_priv, u32 chain_index, struct net * net, struct sk_buff * skb, struct tcf_block * block, u32 portid, u32 seq, u16 flags, int event)
```
</details>
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
