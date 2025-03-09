# Function: <code>tc_setup_flow_action</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tc_setup_flow_action(struct flow_action * flow_action, const struct tcf_exts * exts)
```

```json
{
  "name": "tc_setup_flow_action",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588666896,
      "name": "tc_setup_flow_action",
      "external": true,
      "loc": "net/sched/cls_api.c:3178",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588666896,
      "name": "tc_setup_flow_action.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1235
    },
    {
      "addr": 18446744071588668144,
      "name": "tc_setup_flow_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int tc_setup_flow_action(struct flow_action * flow_action, const struct tcf_exts * exts, bool rtnl_held)
```

```json
{
  "name": "tc_setup_flow_action",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588889824,
      "name": "tc_setup_flow_action",
      "external": true,
      "loc": "net/sched/cls_api.c:3435",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588889824,
      "name": "tc_setup_flow_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1800
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tc_setup_flow_action(struct flow_action * flow_action, const struct tcf_exts * exts)
```

```json
{
  "name": "tc_setup_flow_action",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589796096,
      "name": "tc_setup_flow_action",
      "external": true,
      "loc": "net/sched/cls_api.c:3554",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589796096,
      "name": "tc_setup_flow_action.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2204
    },
    {
      "addr": 18446744071589798304,
      "name": "tc_setup_flow_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tc_setup_flow_action(struct flow_action * flow_action, const struct tcf_exts * exts)
```

```json
{
  "name": "tc_setup_flow_action",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589831552,
      "name": "tc_setup_flow_action",
      "external": true,
      "loc": "net/sched/cls_api.c:3553",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589831552,
      "name": "tc_setup_flow_action.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2659
    },
    {
      "addr": 18446744071589834224,
      "name": "tc_setup_flow_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tc_setup_flow_action(struct flow_action * flow_action, const struct tcf_exts * exts)
```

```json
{
  "name": "tc_setup_flow_action",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589724432,
      "name": "tc_setup_flow_action",
      "external": true,
      "loc": "net/sched/cls_api.c:3554",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589724432,
      "name": "tc_setup_flow_action.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2713
    },
    {
      "addr": 18446744071589727152,
      "name": "tc_setup_flow_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tc_setup_flow_action(struct flow_action * flow_action, const struct tcf_exts * exts)
```

```json
{
  "name": "tc_setup_flow_action",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590485536,
      "name": "tc_setup_flow_action",
      "external": true,
      "loc": "net/sched/cls_api.c:3555",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590482832,
      "name": "tc_setup_flow_action.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2698
    },
    {
      "addr": 18446744071592710669,
      "name": "tc_setup_flow_action.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071590485536,
      "name": "tc_setup_flow_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int tc_setup_flow_action(struct flow_action * flow_action, const struct tcf_exts * exts, bool rtnl_held)
```

```json
{
  "name": "tc_setup_flow_action",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502479688,
      "name": "tc_setup_flow_action",
      "external": true,
      "loc": "net/sched/cls_api.c:3435",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502479688,
      "name": "tc_setup_flow_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1928
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
int tc_setup_flow_action(struct flow_action * flow_action, const struct tcf_exts * exts, bool rtnl_held)
```

```json
{
  "name": "tc_setup_flow_action",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235196684,
      "name": "tc_setup_flow_action",
      "external": true,
      "loc": "net/sched/cls_api.c:3435",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235196684,
      "name": "tc_setup_flow_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1668
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
int tc_setup_flow_action(struct flow_action * flow_action, const struct tcf_exts * exts, bool rtnl_held)
```

```json
{
  "name": "tc_setup_flow_action",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296040352,
      "name": "tc_setup_flow_action",
      "external": true,
      "loc": "net/sched/cls_api.c:3435",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296040352,
      "name": "tc_setup_flow_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2000
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
int tc_setup_flow_action(struct flow_action * flow_action, const struct tcf_exts * exts, bool rtnl_held)
```

```json
{
  "name": "tc_setup_flow_action",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278660230,
      "name": "tc_setup_flow_action",
      "external": true,
      "loc": "net/sched/cls_api.c:3435",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278660230,
      "name": "tc_setup_flow_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1282
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
int tc_setup_flow_action(struct flow_action * flow_action, const struct tcf_exts * exts, bool rtnl_held)
```

```json
{
  "name": "tc_setup_flow_action",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588496208,
      "name": "tc_setup_flow_action",
      "external": true,
      "loc": "net/sched/cls_api.c:3435",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588496208,
      "name": "tc_setup_flow_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1800
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
int tc_setup_flow_action(struct flow_action * flow_action, const struct tcf_exts * exts, bool rtnl_held)
```

```json
{
  "name": "tc_setup_flow_action",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588208208,
      "name": "tc_setup_flow_action",
      "external": true,
      "loc": "net/sched/cls_api.c:3435",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588208208,
      "name": "tc_setup_flow_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1800
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
int tc_setup_flow_action(struct flow_action * flow_action, const struct tcf_exts * exts, bool rtnl_held)
```

```json
{
  "name": "tc_setup_flow_action",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588828384,
      "name": "tc_setup_flow_action",
      "external": true,
      "loc": "net/sched/cls_api.c:3435",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588828384,
      "name": "tc_setup_flow_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1800
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
int tc_setup_flow_action(struct flow_action * flow_action, const struct tcf_exts * exts, bool rtnl_held)
```

```json
{
  "name": "tc_setup_flow_action",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588971136,
      "name": "tc_setup_flow_action",
      "external": true,
      "loc": "net/sched/cls_api.c:3435",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588971136,
      "name": "tc_setup_flow_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2414
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int tc_setup_flow_action(struct flow_action * flow_action, const struct tcf_exts * exts)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool rtnl_held</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool rtnl_held</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int tc_setup_flow_action(struct flow_action * flow_action, const struct tcf_exts * exts)
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
