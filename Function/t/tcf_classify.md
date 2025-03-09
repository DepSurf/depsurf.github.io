# Function: <code>tcf_classify</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, struct tcf_result * res, bool compat_mode)
```

```json
{
  "name": "tcf_classify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587240288,
      "name": "tcf_classify",
      "external": true,
      "loc": "net/sched/cls_api.c:309",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587240288,
      "name": "tcf_classify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, struct tcf_result * res, bool compat_mode)
```

```json
{
  "name": "tcf_classify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587756304,
      "name": "tcf_classify",
      "external": true,
      "loc": "net/sched/cls_api.c:485",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587756304,
      "name": "tcf_classify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, struct tcf_result * res, bool compat_mode)
```

```json
{
  "name": "tcf_classify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_classify",
      "external": true,
      "loc": "net/sched/cls_api.c:830",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588106364,
      "name": "tcf_classify.cold.43",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071588095472,
      "name": "tcf_classify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, struct tcf_result * res, bool compat_mode)
```

```json
{
  "name": "tcf_classify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_classify",
      "external": true,
      "loc": "net/sched/cls_api.c:1277",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588289508,
      "name": "tcf_classify.cold.65",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071588273040,
      "name": "tcf_classify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, struct tcf_result * res, bool compat_mode)
```

```json
{
  "name": "tcf_classify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_classify",
      "external": true,
      "loc": "net/sched/cls_api.c:1636",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588686920,
      "name": "tcf_classify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071588664624,
      "name": "tcf_classify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, struct tcf_result * res, bool compat_mode)
```

```json
{
  "name": "tcf_classify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_classify",
      "external": true,
      "loc": "net/sched/cls_api.c:1562",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588911169,
      "name": "tcf_classify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071588887200,
      "name": "tcf_classify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, struct tcf_result * res, bool compat_mode)
```

```json
{
  "name": "tcf_classify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589772720,
      "name": "tcf_classify",
      "external": true,
      "loc": "net/sched/cls_api.c:1579",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589772720,
      "name": "tcf_classify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, struct tcf_result * res, bool compat_mode)
```

```json
{
  "name": "tcf_classify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589807680,
      "name": "tcf_classify",
      "external": true,
      "loc": "net/sched/cls_api.c:1580",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589807680,
      "name": "tcf_classify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, struct tcf_result * res, bool compat_mode)
```

```json
{
  "name": "tcf_classify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589712320,
      "name": "tcf_classify",
      "external": true,
      "loc": "net/sched/cls_api.c:1580",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589712320,
      "name": "tcf_classify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int tcf_classify(struct sk_buff * skb, const struct tcf_block * block, const struct tcf_proto * tp, struct tcf_result * res, bool compat_mode)
```

```json
{
  "name": "tcf_classify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590471760,
      "name": "tcf_classify",
      "external": true,
      "loc": "net/sched/cls_api.c:1581",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590471760,
      "name": "tcf_classify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
int tcf_classify(struct sk_buff * skb, const struct tcf_block * block, const struct tcf_proto * tp, struct tcf_result * res, bool compat_mode)
```

```json
{
  "name": "tcf_classify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592075104,
      "name": "tcf_classify",
      "external": true,
      "loc": "net/sched/cls_api.c:1598",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/cls_api.c:tcf_qevent_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592075104,
      "name": "tcf_classify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int tcf_classify(struct sk_buff * skb, const struct tcf_block * block, const struct tcf_proto * tp, struct tcf_result * res, bool compat_mode)
```

```json
{
  "name": "tcf_classify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593895536,
      "name": "tcf_classify",
      "external": true,
      "loc": "net/sched/cls_api.c:1600",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/cls_api.c:tcf_qevent_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593895536,
      "name": "tcf_classify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int tcf_classify(struct sk_buff * skb, const struct tcf_block * block, const struct tcf_proto * tp, struct tcf_result * res, bool compat_mode)
```

```json
{
  "name": "tcf_classify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594271328,
      "name": "tcf_classify",
      "external": true,
      "loc": "net/sched/cls_api.c:1734",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/cls_api.c:tcf_qevent_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594271328,
      "name": "tcf_classify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
int tcf_classify(struct sk_buff * skb, const struct tcf_block * block, const struct tcf_proto * tp, struct tcf_result * res, bool compat_mode)
```

```json
{
  "name": "tcf_classify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595069280,
      "name": "tcf_classify",
      "external": true,
      "loc": "net/sched/cls_api.c:1775",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:tc_run",
        "net/sched/cls_api.c:tcf_qevent_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595069280,
      "name": "tcf_classify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 606
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
int tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, struct tcf_result * res, bool compat_mode)
```

```json
{
  "name": "tcf_classify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502476440,
      "name": "tcf_classify",
      "external": true,
      "loc": "net/sched/cls_api.c:1562",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502476440,
      "name": "tcf_classify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
int tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, struct tcf_result * res, bool compat_mode)
```

```json
{
  "name": "tcf_classify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235192316,
      "name": "tcf_classify",
      "external": true,
      "loc": "net/sched/cls_api.c:1562",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235192316,
      "name": "tcf_classify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, struct tcf_result * res, bool compat_mode)
```

```json
{
  "name": "tcf_classify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296035248,
      "name": "tcf_classify",
      "external": true,
      "loc": "net/sched/cls_api.c:1562",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296035248,
      "name": "tcf_classify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, struct tcf_result * res, bool compat_mode)
```

```json
{
  "name": "tcf_classify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278657614,
      "name": "tcf_classify",
      "external": true,
      "loc": "net/sched/cls_api.c:1562",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278657614,
      "name": "tcf_classify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, struct tcf_result * res, bool compat_mode)
```

```json
{
  "name": "tcf_classify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_classify",
      "external": true,
      "loc": "net/sched/cls_api.c:1562",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588517553,
      "name": "tcf_classify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071588493584,
      "name": "tcf_classify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, struct tcf_result * res, bool compat_mode)
```

```json
{
  "name": "tcf_classify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_classify",
      "external": true,
      "loc": "net/sched/cls_api.c:1562",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588229553,
      "name": "tcf_classify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071588205584,
      "name": "tcf_classify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, struct tcf_result * res, bool compat_mode)
```

```json
{
  "name": "tcf_classify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_classify",
      "external": true,
      "loc": "net/sched/cls_api.c:1562",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588849729,
      "name": "tcf_classify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071588825760,
      "name": "tcf_classify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, struct tcf_result * res, bool compat_mode)
```

```json
{
  "name": "tcf_classify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_classify",
      "external": true,
      "loc": "net/sched/cls_api.c:1562",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588991104,
      "name": "tcf_classify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071588967056,
      "name": "tcf_classify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, struct tcf_result * res, bool compat_mode)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct tcf_block * block</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, tp, res, compat_mode</code> ➡️ <code>skb, block, tp, res, compat_mode</code>
</li>
</ul>
</details>
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
