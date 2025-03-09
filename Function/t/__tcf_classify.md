# Function: <code>__tcf_classify</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, const struct tcf_proto * orig_tp, struct tcf_result * res, bool compat_mode, u32 * last_executed_chain)
```

```json
{
  "name": "__tcf_classify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcf_classify",
      "external": false,
      "loc": "net/sched/cls_api.c:1525",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify_ingress",
        "net/sched/cls_api.c:tcf_classify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589772448,
      "name": "__tcf_classify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071589798328,
      "name": "__tcf_classify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int __tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, const struct tcf_proto * orig_tp, struct tcf_result * res, bool compat_mode, u32 * last_executed_chain)
```

```json
{
  "name": "__tcf_classify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcf_classify",
      "external": false,
      "loc": "net/sched/cls_api.c:1526",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify_ingress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589807408,
      "name": "__tcf_classify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071591633381,
      "name": "__tcf_classify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int __tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, const struct tcf_proto * orig_tp, struct tcf_result * res, bool compat_mode, u32 * last_executed_chain)
```

```json
{
  "name": "__tcf_classify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcf_classify",
      "external": false,
      "loc": "net/sched/cls_api.c:1526",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify_ingress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589712048,
      "name": "__tcf_classify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071591576782,
      "name": "__tcf_classify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int __tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, const struct tcf_proto * orig_tp, struct tcf_result * res, bool compat_mode, u32 * last_executed_chain)
```

```json
{
  "name": "__tcf_classify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcf_classify",
      "external": false,
      "loc": "net/sched/cls_api.c:1527",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590470224,
      "name": "__tcf_classify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071592710311,
      "name": "__tcf_classify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int __tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, const struct tcf_proto * orig_tp, struct tcf_result * res, bool compat_mode, u32 * last_executed_chain)
```

```json
{
  "name": "__tcf_classify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcf_classify",
      "external": false,
      "loc": "net/sched/cls_api.c:1544",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592073968,
      "name": "__tcf_classify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446744071594596524,
      "name": "__tcf_classify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
int __tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, const struct tcf_proto * orig_tp, struct tcf_result * res, bool compat_mode, u32 * last_executed_chain)
```

```json
{
  "name": "__tcf_classify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593894224,
      "name": "__tcf_classify",
      "external": false,
      "loc": "net/sched/cls_api.c:1546",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593894224,
      "name": "__tcf_classify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int __tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, const struct tcf_proto * orig_tp, struct tcf_result * res, bool compat_mode, struct tcf_exts_miss_cookie_node * n, int act_index, u32 * last_executed_chain)
```

```json
{
  "name": "__tcf_classify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594270800,
      "name": "__tcf_classify",
      "external": false,
      "loc": "net/sched/cls_api.c:1652",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594270800,
      "name": "__tcf_classify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
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
int __tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, const struct tcf_proto * orig_tp, struct tcf_result * res, bool compat_mode, struct tcf_exts_miss_cookie_node * n, int act_index, u32 * last_executed_chain)
```

```json
{
  "name": "__tcf_classify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595068768,
      "name": "__tcf_classify",
      "external": false,
      "loc": "net/sched/cls_api.c:1682",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595068768,
      "name": "__tcf_classify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 490
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
int __tcf_classify(struct sk_buff * skb, const struct tcf_proto * tp, const struct tcf_proto * orig_tp, struct tcf_result * res, bool compat_mode, u32 * last_executed_chain)
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tcf_exts_miss_cookie_node * n</code>
</li>
<li>
<b>Param added. </b>
<code>int act_index</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, tp, orig_tp, res, compat_mode, last_executed_chain</code> ➡️ <code>skb, tp, orig_tp, res, compat_mode, n, act_index, last_executed_chain</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
