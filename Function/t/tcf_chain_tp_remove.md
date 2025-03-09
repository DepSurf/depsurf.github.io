# Function: <code>tcf_chain_tp_remove</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain_tp_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587246101,
      "name": "tcf_chain_tp_remove",
      "external": false,
      "loc": "net/sched/cls_api.c:380",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/cls_api.c:tc_ctl_tfilter"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void tcf_chain_tp_remove(struct tcf_chain * chain, struct tcf_chain_info * chain_info, struct tcf_proto * tp)
```

```json
{
  "name": "tcf_chain_tp_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587755488,
      "name": "tcf_chain_tp_remove",
      "external": false,
      "loc": "net/sched/cls_api.c:556",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/cls_api.c:tc_ctl_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587755488,
      "name": "tcf_chain_tp_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain_tp_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588097088,
      "name": "tcf_chain_tp_remove",
      "external": false,
      "loc": "net/sched/cls_api.c:902",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588097088,
      "name": "tcf_chain_tp_remove.isra.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain_tp_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588278000,
      "name": "tcf_chain_tp_remove",
      "external": false,
      "loc": "net/sched/cls_api.c:1348",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588278000,
      "name": "tcf_chain_tp_remove.isra.41",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain_tp_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588682219,
      "name": "tcf_chain_tp_remove",
      "external": false,
      "loc": "net/sched/cls_api.c:1713",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_del_tfilter"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain_tp_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588907576,
      "name": "tcf_chain_tp_remove",
      "external": false,
      "loc": "net/sched/cls_api.c:1651",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_del_tfilter"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain_tp_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589790693,
      "name": "tcf_chain_tp_remove",
      "external": false,
      "loc": "net/sched/cls_api.c:1664",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_del_tfilter"
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
  "name": "tcf_chain_tp_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589826011,
      "name": "tcf_chain_tp_remove",
      "external": false,
      "loc": "net/sched/cls_api.c:1666",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_del_tfilter"
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
  "name": "tcf_chain_tp_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589731502,
      "name": "tcf_chain_tp_remove",
      "external": false,
      "loc": "net/sched/cls_api.c:1667",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_del_tfilter"
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
  "name": "tcf_chain_tp_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590489806,
      "name": "tcf_chain_tp_remove",
      "external": false,
      "loc": "net/sched/cls_api.c:1665",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_del_tfilter"
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
  "name": "tcf_chain_tp_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592098923,
      "name": "tcf_chain_tp_remove",
      "external": false,
      "loc": "net/sched/cls_api.c:1684",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_del_tfilter"
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
  "name": "tcf_chain_tp_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593915852,
      "name": "tcf_chain_tp_remove",
      "external": false,
      "loc": "net/sched/cls_api.c:1686",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_del_tfilter"
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
  "name": "tcf_chain_tp_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594290360,
      "name": "tcf_chain_tp_remove",
      "external": false,
      "loc": "net/sched/cls_api.c:1834",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_del_tfilter"
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
  "name": "tcf_chain_tp_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595089576,
      "name": "tcf_chain_tp_remove",
      "external": false,
      "loc": "net/sched/cls_api.c:1884",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_del_tfilter"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain_tp_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502499504,
      "name": "tcf_chain_tp_remove",
      "external": false,
      "loc": "net/sched/cls_api.c:1651",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_del_tfilter"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain_tp_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235214380,
      "name": "tcf_chain_tp_remove",
      "external": false,
      "loc": "net/sched/cls_api.c:1651",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_del_tfilter"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain_tp_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296068252,
      "name": "tcf_chain_tp_remove",
      "external": false,
      "loc": "net/sched/cls_api.c:1651",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_del_tfilter"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain_tp_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278677084,
      "name": "tcf_chain_tp_remove",
      "external": false,
      "loc": "net/sched/cls_api.c:1651",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_del_tfilter"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain_tp_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588513960,
      "name": "tcf_chain_tp_remove",
      "external": false,
      "loc": "net/sched/cls_api.c:1651",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_del_tfilter"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain_tp_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588225960,
      "name": "tcf_chain_tp_remove",
      "external": false,
      "loc": "net/sched/cls_api.c:1651",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_del_tfilter"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain_tp_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588846136,
      "name": "tcf_chain_tp_remove",
      "external": false,
      "loc": "net/sched/cls_api.c:1651",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_del_tfilter"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain_tp_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588990456,
      "name": "tcf_chain_tp_remove",
      "external": false,
      "loc": "net/sched/cls_api.c:1651",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_del_tfilter"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void tcf_chain_tp_remove(struct tcf_chain * chain, struct tcf_chain_info * chain_info, struct tcf_proto * tp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void tcf_chain_tp_remove(struct tcf_chain * chain, struct tcf_chain_info * chain_info, struct tcf_proto * tp)
```
</details>
</li>
</ul>
