# Function: <code>skb_ext_add</code>

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
void * skb_ext_add(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "skb_ext_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587877312,
      "name": "skb_ext_add",
      "external": true,
      "loc": "net/core/skbuff.c:5656",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/xfrm/xfrm_input.c:secpath_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587877312,
      "name": "skb_ext_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
void * skb_ext_add(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "skb_ext_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588182592,
      "name": "skb_ext_add",
      "external": true,
      "loc": "net/core/skbuff.c:6016",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/xfrm/xfrm_input.c:secpath_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588182592,
      "name": "skb_ext_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
void * skb_ext_add(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "skb_ext_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588388624,
      "name": "skb_ext_add",
      "external": true,
      "loc": "net/core/skbuff.c:6033",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/xfrm/xfrm_input.c:secpath_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588388624,
      "name": "skb_ext_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
void * skb_ext_add(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "skb_ext_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589282496,
      "name": "skb_ext_add",
      "external": true,
      "loc": "net/core/skbuff.c:6176",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify_ingress",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589282496,
      "name": "skb_ext_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
void * skb_ext_add(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "skb_ext_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589282528,
      "name": "skb_ext_add",
      "external": true,
      "loc": "net/core/skbuff.c:6313",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify_ingress",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589282528,
      "name": "skb_ext_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
void * skb_ext_add(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "skb_ext_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589176480,
      "name": "skb_ext_add",
      "external": true,
      "loc": "net/core/skbuff.c:6401",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify_ingress",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/mptcp/subflow.c:subflow_add_reset_reason",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589176480,
      "name": "skb_ext_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
void * skb_ext_add(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "skb_ext_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_ext_add",
      "external": true,
      "loc": "net/core/skbuff.c:6476",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/mptcp/subflow.c:subflow_add_reset_reason",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592694827,
      "name": "skb_ext_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589897392,
      "name": "skb_ext_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 663
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
void * skb_ext_add(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "skb_ext_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_ext_add",
      "external": true,
      "loc": "net/core/skbuff.c:6389",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/mptcp/subflow.c:subflow_add_reset_reason",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594580295,
      "name": "skb_ext_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071591426320,
      "name": "skb_ext_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 678
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void * skb_ext_add(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "skb_ext_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_ext_add",
      "external": true,
      "loc": "net/core/skbuff.c:6590",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/mptcp/subflow.c:subflow_add_reset_reason",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596322175,
      "name": "skb_ext_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071593192896,
      "name": "skb_ext_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void * skb_ext_add(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "skb_ext_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_ext_add",
      "external": true,
      "loc": "net/core/skbuff.c:6635",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/mptcp/subflow.c:subflow_add_reset_reason",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596852097,
      "name": "skb_ext_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071593652144,
      "name": "skb_ext_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void * skb_ext_add(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "skb_ext_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_ext_add",
      "external": true,
      "loc": "net/core/skbuff.c:6782",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/mptcp/subflow.c:subflow_add_reset_reason",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597776983,
      "name": "skb_ext_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071594427920,
      "name": "skb_ext_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
void * skb_ext_add(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "skb_ext_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501896776,
      "name": "skb_ext_add",
      "external": true,
      "loc": "net/core/skbuff.c:6033",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/xfrm/xfrm_input.c:secpath_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501896776,
      "name": "skb_ext_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
void * skb_ext_add(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "skb_ext_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234662584,
      "name": "skb_ext_add",
      "external": true,
      "loc": "net/core/skbuff.c:6033",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/xfrm/xfrm_input.c:secpath_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234662584,
      "name": "skb_ext_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void * skb_ext_add(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "skb_ext_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295312320,
      "name": "skb_ext_add",
      "external": true,
      "loc": "net/core/skbuff.c:6033",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/xfrm/xfrm_input.c:secpath_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295312320,
      "name": "skb_ext_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
void * skb_ext_add(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "skb_ext_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278218132,
      "name": "skb_ext_add",
      "external": true,
      "loc": "net/core/skbuff.c:6033",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/xfrm/xfrm_input.c:secpath_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278218132,
      "name": "skb_ext_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
void * skb_ext_add(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "skb_ext_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587995408,
      "name": "skb_ext_add",
      "external": true,
      "loc": "net/core/skbuff.c:6033",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/xfrm/xfrm_input.c:secpath_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587995408,
      "name": "skb_ext_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
void * skb_ext_add(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "skb_ext_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587708512,
      "name": "skb_ext_add",
      "external": true,
      "loc": "net/core/skbuff.c:6033",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/xfrm/xfrm_input.c:secpath_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587708512,
      "name": "skb_ext_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
void * skb_ext_add(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "skb_ext_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588327184,
      "name": "skb_ext_add",
      "external": true,
      "loc": "net/core/skbuff.c:6033",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/xfrm/xfrm_input.c:secpath_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588327184,
      "name": "skb_ext_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
void * skb_ext_add(struct sk_buff * skb, enum skb_ext_id id)
```

```json
{
  "name": "skb_ext_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588462608,
      "name": "skb_ext_add",
      "external": true,
      "loc": "net/core/skbuff.c:6033",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_classify",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/xfrm/xfrm_input.c:secpath_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588462608,
      "name": "skb_ext_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
void * skb_ext_add(struct sk_buff * skb, enum skb_ext_id id)
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
