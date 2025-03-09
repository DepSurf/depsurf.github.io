# Function: <code>rtnl_xdp_report_one</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rtnl_xdp_report_one(struct sk_buff * skb, struct net_device * dev, u32 * prog_id, u8 * mode, u8 tgt_mode, u32 attr, u32 (*)(struct net_device *) get_prog_id)
```

```json
{
  "name": "rtnl_xdp_report_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588062896,
      "name": "rtnl_xdp_report_one",
      "external": false,
      "loc": "net/core/rtnetlink.c:1392",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588062896,
      "name": "rtnl_xdp_report_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rtnl_xdp_report_one(struct sk_buff * skb, struct net_device * dev, u32 * prog_id, u8 * mode, u8 tgt_mode, u32 attr, u32 (*)(struct net_device *) get_prog_id)
```

```json
{
  "name": "rtnl_xdp_report_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588378336,
      "name": "rtnl_xdp_report_one",
      "external": false,
      "loc": "net/core/rtnetlink.c:1390",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588378336,
      "name": "rtnl_xdp_report_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rtnl_xdp_report_one(struct sk_buff * skb, struct net_device * dev, u32 * prog_id, u8 * mode, u8 tgt_mode, u32 attr, u32 (*)(struct net_device *) get_prog_id)
```

```json
{
  "name": "rtnl_xdp_report_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588584736,
      "name": "rtnl_xdp_report_one",
      "external": false,
      "loc": "net/core/rtnetlink.c:1390",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588584736,
      "name": "rtnl_xdp_report_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
  "name": "rtnl_xdp_report_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589445895,
      "name": "rtnl_xdp_report_one",
      "external": false,
      "loc": "net/core/rtnetlink.c:1428",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill"
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
  "name": "rtnl_xdp_report_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589445975,
      "name": "rtnl_xdp_report_one",
      "external": false,
      "loc": "net/core/rtnetlink.c:1439",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rtnl_xdp_report_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589343863,
      "name": "rtnl_xdp_report_one",
      "external": false,
      "loc": "net/core/rtnetlink.c:1441",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill"
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
  "name": "rtnl_xdp_report_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590069271,
      "name": "rtnl_xdp_report_one",
      "external": false,
      "loc": "net/core/rtnetlink.c:1430",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill"
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
  "name": "rtnl_xdp_report_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591616360,
      "name": "rtnl_xdp_report_one",
      "external": false,
      "loc": "net/core/rtnetlink.c:1470",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill"
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
  "name": "rtnl_xdp_report_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593398648,
      "name": "rtnl_xdp_report_one",
      "external": false,
      "loc": "net/core/rtnetlink.c:1481",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill"
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
  "name": "rtnl_xdp_report_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593863272,
      "name": "rtnl_xdp_report_one",
      "external": false,
      "loc": "net/core/rtnetlink.c:1492",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill"
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
  "name": "rtnl_xdp_report_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594645832,
      "name": "rtnl_xdp_report_one",
      "external": false,
      "loc": "net/core/rtnetlink.c:1499",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int rtnl_xdp_report_one(struct sk_buff * skb, struct net_device * dev, u32 * prog_id, u8 * mode, u8 tgt_mode, u32 attr, u32 (*)(struct net_device *) get_prog_id)
```

```json
{
  "name": "rtnl_xdp_report_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502130912,
      "name": "rtnl_xdp_report_one",
      "external": false,
      "loc": "net/core/rtnetlink.c:1390",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502130912,
      "name": "rtnl_xdp_report_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int rtnl_xdp_report_one(struct sk_buff * skb, struct net_device * dev, u32 * prog_id, u8 * mode, u8 tgt_mode, u32 attr, u32 (*)(struct net_device *) get_prog_id)
```

```json
{
  "name": "rtnl_xdp_report_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234874456,
      "name": "rtnl_xdp_report_one",
      "external": false,
      "loc": "net/core/rtnetlink.c:1390",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234874456,
      "name": "rtnl_xdp_report_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int rtnl_xdp_report_one(struct sk_buff * skb, struct net_device * dev, u32 * prog_id, u8 * mode, u8 tgt_mode, u32 attr, u32 (*)(struct net_device *) get_prog_id)
```

```json
{
  "name": "rtnl_xdp_report_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295593344,
      "name": "rtnl_xdp_report_one",
      "external": false,
      "loc": "net/core/rtnetlink.c:1390",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295593344,
      "name": "rtnl_xdp_report_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int rtnl_xdp_report_one(struct sk_buff * skb, struct net_device * dev, u32 * prog_id, u8 * mode, u8 tgt_mode, u32 attr, u32 (*)(struct net_device *) get_prog_id)
```

```json
{
  "name": "rtnl_xdp_report_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278392846,
      "name": "rtnl_xdp_report_one",
      "external": false,
      "loc": "net/core/rtnetlink.c:1390",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278392846,
      "name": "rtnl_xdp_report_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int rtnl_xdp_report_one(struct sk_buff * skb, struct net_device * dev, u32 * prog_id, u8 * mode, u8 tgt_mode, u32 attr, u32 (*)(struct net_device *) get_prog_id)
```

```json
{
  "name": "rtnl_xdp_report_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588191472,
      "name": "rtnl_xdp_report_one",
      "external": false,
      "loc": "net/core/rtnetlink.c:1390",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588191472,
      "name": "rtnl_xdp_report_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int rtnl_xdp_report_one(struct sk_buff * skb, struct net_device * dev, u32 * prog_id, u8 * mode, u8 tgt_mode, u32 attr, u32 (*)(struct net_device *) get_prog_id)
```

```json
{
  "name": "rtnl_xdp_report_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587904304,
      "name": "rtnl_xdp_report_one",
      "external": false,
      "loc": "net/core/rtnetlink.c:1390",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587904304,
      "name": "rtnl_xdp_report_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int rtnl_xdp_report_one(struct sk_buff * skb, struct net_device * dev, u32 * prog_id, u8 * mode, u8 tgt_mode, u32 attr, u32 (*)(struct net_device *) get_prog_id)
```

```json
{
  "name": "rtnl_xdp_report_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588523296,
      "name": "rtnl_xdp_report_one",
      "external": false,
      "loc": "net/core/rtnetlink.c:1390",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588523296,
      "name": "rtnl_xdp_report_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int rtnl_xdp_report_one(struct sk_buff * skb, struct net_device * dev, u32 * prog_id, u8 * mode, u8 tgt_mode, u32 attr, u32 (*)(struct net_device *) get_prog_id)
```

```json
{
  "name": "rtnl_xdp_report_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588660576,
      "name": "rtnl_xdp_report_one",
      "external": false,
      "loc": "net/core/rtnetlink.c:1390",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588660576,
      "name": "rtnl_xdp_report_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
int rtnl_xdp_report_one(struct sk_buff * skb, struct net_device * dev, u32 * prog_id, u8 * mode, u8 tgt_mode, u32 attr, u32 (*)(struct net_device *) get_prog_id)
```
</details>
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
int rtnl_xdp_report_one(struct sk_buff * skb, struct net_device * dev, u32 * prog_id, u8 * mode, u8 tgt_mode, u32 attr, u32 (*)(struct net_device *) get_prog_id)
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
