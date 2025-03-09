# Function: <code>rtnetlink_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586380288,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:620",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tclass_notify",
        "net/sched/sch_api.c:qdisc_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tc_ctl_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586380288,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586816336,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:642",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tclass_notify",
        "net/sched/sch_api.c:qdisc_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/act_api.c:tc_ctl_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586816336,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587004144,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:643",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tclass_notify",
        "net/sched/sch_api.c:qdisc_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/act_api.c:tc_ctl_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587004144,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587129296,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:645",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tclass_notify",
        "net/sched/sch_api.c:qdisc_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/act_api.c:tc_ctl_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587129296,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587632816,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:618",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:qdisc_notify",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/act_api.c:tc_ctl_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587632816,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587943024,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:701",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/act_api.c:tc_ctl_action",
        "net/sched/act_api.c:tca_action_gd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587943024,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588091088,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:711",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/act_api.c:tcf_action_add",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_gd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588091088,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588406160,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:706",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/cls_api.c:__tcf_chain_put",
        "net/sched/act_api.c:tcf_action_add",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_gd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588406160,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588612544,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:706",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/cls_api.c:__tcf_chain_put",
        "net/sched/act_api.c:tcf_action_add",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_gd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588612544,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589468112,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:706",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/cls_api.c:__tcf_chain_put",
        "net/sched/act_api.c:tcf_action_add",
        "net/sched/act_api.c:tcf_del_notify",
        "net/sched/act_api.c:tca_action_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589468112,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589469200,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:708",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/cls_api.c:__tcf_chain_put",
        "net/sched/act_api.c:tcf_action_add",
        "net/sched/act_api.c:tcf_del_notify",
        "net/sched/act_api.c:tca_action_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589469200,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589367632,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:710",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/cls_api.c:__tcf_chain_put",
        "net/sched/act_api.c:tcf_action_add",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589367632,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590098096,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:710",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/cls_api.c:__tcf_chain_put",
        "net/sched/act_api.c:tcf_action_add",
        "net/sched/act_api.c:tcf_del_notify",
        "net/sched/act_api.c:tca_action_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590098096,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591648464,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:747",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/cls_api.c:__tcf_chain_put",
        "net/sched/act_api.c:tcf_action_add",
        "net/sched/act_api.c:tcf_del_notify",
        "net/sched/act_api.c:tca_action_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591648464,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593431664,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:748",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/cls_api.c:__tcf_chain_put",
        "net/sched/act_api.c:tcf_action_add",
        "net/sched/act_api.c:tcf_del_notify",
        "net/sched/act_api.c:tca_action_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593431664,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593896624,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:751",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/cls_api.c:__tcf_chain_put",
        "net/sched/act_api.c:tcf_action_add",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593896624,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594679920,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:746",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tfilter_del_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/cls_api.c:__tcf_chain_put",
        "net/sched/act_api.c:tcf_action_add",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_reoffload_cb",
        "net/sched/act_api.c:tca_action_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594679920,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502158408,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:706",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:__tcf_chain_put",
        "net/sched/act_api.c:tcf_action_add",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_gd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502158408,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234901340,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:706",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:qdisc_notify",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/cls_api.c:__tcf_chain_put",
        "net/sched/act_api.c:tcf_action_add",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234901340,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295628064,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:706",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:__tcf_chain_put",
        "net/sched/act_api.c:tcf_action_add",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_gd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295628064,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278413260,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:706",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:__tcf_chain_put",
        "net/sched/act_api.c:tcf_action_add",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_gd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278413260,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588219280,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:706",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/cls_api.c:__tcf_chain_put",
        "net/sched/act_api.c:tcf_action_add",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_gd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588219280,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587932112,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:706",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/cls_api.c:__tcf_chain_put",
        "net/sched/act_api.c:tcf_action_add",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_gd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587932112,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588551104,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:706",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/cls_api.c:__tcf_chain_put",
        "net/sched/act_api.c:tcf_action_add",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_gd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588551104,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int rtnetlink_send(struct sk_buff * skb, struct net * net, u32 pid, unsigned int group, int echo)
```

```json
{
  "name": "rtnetlink_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588688576,
      "name": "rtnetlink_send",
      "external": true,
      "loc": "net/core/rtnetlink.c:706",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/cls_api.c:__tcf_chain_put",
        "net/sched/act_api.c:tcf_action_add",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_gd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588688576,
      "name": "rtnetlink_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
