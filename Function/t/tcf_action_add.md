# Function: <code>tcf_action_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586483510,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:947",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_ctl_action"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586930103,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:927",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_ctl_action"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587125194,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:986",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_ctl_action"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587254992,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:1058",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_ctl_action"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587774445,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:1074",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_ctl_action"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588117306,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:1139",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_ctl_action"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int tcf_action_add(struct net * net, struct nlattr * nla, struct nlmsghdr * n, u32 portid, int ovr, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588299152,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:1332",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tc_ctl_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588299152,
      "name": "tcf_action_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int tcf_action_add(struct net * net, struct nlattr * nla, struct nlmsghdr * n, u32 portid, int ovr, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588696784,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:1348",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tc_ctl_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588696784,
      "name": "tcf_action_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
int tcf_action_add(struct net * net, struct nlattr * nla, struct nlmsghdr * n, u32 portid, int ovr, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588920928,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:1351",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tc_ctl_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588920928,
      "name": "tcf_action_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int tcf_action_add(struct net * net, struct nlattr * nla, struct nlmsghdr * n, u32 portid, int ovr, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589809344,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:1444",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tc_ctl_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589809344,
      "name": "tcf_action_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
int tcf_action_add(struct net * net, struct nlattr * nla, struct nlmsghdr * n, u32 portid, int ovr, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589845696,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:1495",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tc_ctl_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589845696,
      "name": "tcf_action_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
int tcf_action_add(struct net * net, struct nlattr * nla, struct nlmsghdr * n, u32 portid, int ovr, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589750976,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:1505",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tc_ctl_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589750976,
      "name": "tcf_action_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 474
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
int tcf_action_add(struct net * net, struct nlattr * nla, struct nlmsghdr * n, u32 portid, u32 flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590509888,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:1506",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tc_ctl_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590509888,
      "name": "tcf_action_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
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
int tcf_action_add(struct net * net, struct nlattr * nla, struct nlmsghdr * n, u32 portid, u32 flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592115184,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:1952",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tc_ctl_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592115184,
      "name": "tcf_action_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
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
int tcf_action_add(struct net * net, struct nlattr * nla, struct nlmsghdr * n, u32 portid, u32 flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593937312,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:1978",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tc_ctl_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593937312,
      "name": "tcf_action_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
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
int tcf_action_add(struct net * net, struct nlattr * nla, struct nlmsghdr * n, u32 portid, u32 flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594313968,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:1975",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tc_ctl_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594313968,
      "name": "tcf_action_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
int tcf_action_add(struct net * net, struct nlattr * nla, struct nlmsghdr * n, u32 portid, u32 flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595111744,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:2052",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tc_ctl_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595111744,
      "name": "tcf_action_add",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int tcf_action_add(struct net * net, struct nlattr * nla, struct nlmsghdr * n, u32 portid, int ovr, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502513600,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:1351",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tc_ctl_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502513600,
      "name": "tcf_action_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
int tcf_action_add(struct net * net, struct nlattr * nla, struct nlmsghdr * n, u32 portid, int ovr, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235225076,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:1351",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tc_ctl_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235225076,
      "name": "tcf_action_add",
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
int tcf_action_add(struct net * net, struct nlattr * nla, struct nlmsghdr * n, u32 portid, int ovr, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296083856,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:1351",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tc_ctl_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296083856,
      "name": "tcf_action_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
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
int tcf_action_add(struct net * net, struct nlattr * nla, struct nlmsghdr * n, u32 portid, int ovr, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278685702,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:1351",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tc_ctl_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278685702,
      "name": "tcf_action_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
int tcf_action_add(struct net * net, struct nlattr * nla, struct nlmsghdr * n, u32 portid, int ovr, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588527312,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:1351",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tc_ctl_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588527312,
      "name": "tcf_action_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int tcf_action_add(struct net * net, struct nlattr * nla, struct nlmsghdr * n, u32 portid, int ovr, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588239312,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:1351",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tc_ctl_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588239312,
      "name": "tcf_action_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int tcf_action_add(struct net * net, struct nlattr * nla, struct nlmsghdr * n, u32 portid, int ovr, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588859488,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:1351",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tc_ctl_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588859488,
      "name": "tcf_action_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int tcf_action_add(struct net * net, struct nlattr * nla, struct nlmsghdr * n, u32 portid, int ovr, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_action_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589000944,
      "name": "tcf_action_add",
      "external": false,
      "loc": "net/sched/act_api.c:1351",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tc_ctl_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589000944,
      "name": "tcf_action_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int tcf_action_add(struct net * net, struct nlattr * nla, struct nlmsghdr * n, u32 portid, int ovr, struct netlink_ext_ack * extack)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int ovr</code>
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
