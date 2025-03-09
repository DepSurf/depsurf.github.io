# Function: <code>tc_chain_notify</code>

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
int tc_chain_notify(struct tcf_chain * chain, struct sk_buff * oskb, u32 seq, u16 flags, int event, bool unicast)
```

```json
{
  "name": "tc_chain_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588277264,
      "name": "tc_chain_notify",
      "external": false,
      "loc": "net/sched/cls_api.c:2079",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:__tcf_chain_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588277264,
      "name": "tc_chain_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
int tc_chain_notify(struct tcf_chain * chain, struct sk_buff * oskb, u32 seq, u16 flags, int event, bool unicast)
```

```json
{
  "name": "tc_chain_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588668944,
      "name": "tc_chain_notify",
      "external": false,
      "loc": "net/sched/cls_api.c:2691",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:__tcf_chain_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588668944,
      "name": "tc_chain_notify",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain * chain, struct sk_buff * oskb, u32 seq, u16 flags, int event, bool unicast)
```

```json
{
  "name": "tc_chain_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588892384,
      "name": "tc_chain_notify",
      "external": false,
      "loc": "net/sched/cls_api.c:2655",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:__tcf_chain_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588892384,
      "name": "tc_chain_notify",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain * chain, struct sk_buff * oskb, u32 seq, u16 flags, int event, bool unicast)
```

```json
{
  "name": "tc_chain_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589780496,
      "name": "tc_chain_notify",
      "external": false,
      "loc": "net/sched/cls_api.c:2691",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:__tcf_chain_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589780496,
      "name": "tc_chain_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int tc_chain_notify(struct tcf_chain * chain, struct sk_buff * oskb, u32 seq, u16 flags, int event, bool unicast)
```

```json
{
  "name": "tc_chain_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589815776,
      "name": "tc_chain_notify",
      "external": false,
      "loc": "net/sched/cls_api.c:2692",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:__tcf_chain_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589815776,
      "name": "tc_chain_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int tc_chain_notify(struct tcf_chain * chain, struct sk_buff * oskb, u32 seq, u16 flags, int event, bool unicast)
```

```json
{
  "name": "tc_chain_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589717216,
      "name": "tc_chain_notify",
      "external": false,
      "loc": "net/sched/cls_api.c:2693",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:__tcf_chain_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589717216,
      "name": "tc_chain_notify",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain * chain, struct sk_buff * oskb, u32 seq, u16 flags, int event, bool unicast)
```

```json
{
  "name": "tc_chain_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590475456,
      "name": "tc_chain_notify",
      "external": false,
      "loc": "net/sched/cls_api.c:2693",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:__tcf_chain_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590475456,
      "name": "tc_chain_notify",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain * chain, struct sk_buff * oskb, u32 seq, u16 flags, int event, bool unicast)
```

```json
{
  "name": "tc_chain_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592080512,
      "name": "tc_chain_notify",
      "external": false,
      "loc": "net/sched/cls_api.c:2712",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:__tcf_chain_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592080512,
      "name": "tc_chain_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int tc_chain_notify(struct tcf_chain * chain, struct sk_buff * oskb, u32 seq, u16 flags, int event, bool unicast)
```

```json
{
  "name": "tc_chain_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593899728,
      "name": "tc_chain_notify",
      "external": false,
      "loc": "net/sched/cls_api.c:2716",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:__tcf_chain_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593899728,
      "name": "tc_chain_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int tc_chain_notify(struct tcf_chain * chain, struct sk_buff * oskb, u32 seq, u16 flags, int event, bool unicast, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tc_chain_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594278448,
      "name": "tc_chain_notify",
      "external": false,
      "loc": "net/sched/cls_api.c:2878",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:__tcf_chain_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594278448,
      "name": "tc_chain_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
int tc_chain_notify(struct tcf_chain * chain, struct sk_buff * oskb, u32 seq, u16 flags, int event, bool unicast, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tc_chain_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595077184,
      "name": "tc_chain_notify",
      "external": false,
      "loc": "net/sched/cls_api.c:2931",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:__tcf_chain_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595077184,
      "name": "tc_chain_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int tc_chain_notify(struct tcf_chain * chain, struct sk_buff * oskb, u32 seq, u16 flags, int event, bool unicast)
```

```json
{
  "name": "tc_chain_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502483536,
      "name": "tc_chain_notify",
      "external": false,
      "loc": "net/sched/cls_api.c:2655",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:__tcf_chain_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502483536,
      "name": "tc_chain_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int tc_chain_notify(struct tcf_chain * chain, struct sk_buff * oskb, u32 seq, u16 flags, int event, bool unicast)
```

```json
{
  "name": "tc_chain_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235199108,
      "name": "tc_chain_notify",
      "external": false,
      "loc": "net/sched/cls_api.c:2655",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:__tcf_chain_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235199108,
      "name": "tc_chain_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int tc_chain_notify(struct tcf_chain * chain, struct sk_buff * oskb, u32 seq, u16 flags, int event, bool unicast)
```

```json
{
  "name": "tc_chain_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296046992,
      "name": "tc_chain_notify",
      "external": false,
      "loc": "net/sched/cls_api.c:2655",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:__tcf_chain_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296046992,
      "name": "tc_chain_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int tc_chain_notify(struct tcf_chain * chain, struct sk_buff * oskb, u32 seq, u16 flags, int event, bool unicast)
```

```json
{
  "name": "tc_chain_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278664118,
      "name": "tc_chain_notify",
      "external": false,
      "loc": "net/sched/cls_api.c:2655",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:__tcf_chain_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278664118,
      "name": "tc_chain_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int tc_chain_notify(struct tcf_chain * chain, struct sk_buff * oskb, u32 seq, u16 flags, int event, bool unicast)
```

```json
{
  "name": "tc_chain_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588498768,
      "name": "tc_chain_notify",
      "external": false,
      "loc": "net/sched/cls_api.c:2655",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:__tcf_chain_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588498768,
      "name": "tc_chain_notify",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain * chain, struct sk_buff * oskb, u32 seq, u16 flags, int event, bool unicast)
```

```json
{
  "name": "tc_chain_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588210768,
      "name": "tc_chain_notify",
      "external": false,
      "loc": "net/sched/cls_api.c:2655",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:__tcf_chain_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588210768,
      "name": "tc_chain_notify",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain * chain, struct sk_buff * oskb, u32 seq, u16 flags, int event, bool unicast)
```

```json
{
  "name": "tc_chain_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588830944,
      "name": "tc_chain_notify",
      "external": false,
      "loc": "net/sched/cls_api.c:2655",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:__tcf_chain_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588830944,
      "name": "tc_chain_notify",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain * chain, struct sk_buff * oskb, u32 seq, u16 flags, int event, bool unicast)
```

```json
{
  "name": "tc_chain_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588974304,
      "name": "tc_chain_notify",
      "external": false,
      "loc": "net/sched/cls_api.c:2655",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:__tcf_chain_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588974304,
      "name": "tc_chain_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int tc_chain_notify(struct tcf_chain * chain, struct sk_buff * oskb, u32 seq, u16 flags, int event, bool unicast)
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
