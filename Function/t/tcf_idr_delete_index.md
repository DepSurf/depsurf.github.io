# Function: <code>tcf_idr_delete_index</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_idr_delete_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588297873,
      "name": "tcf_idr_delete_index",
      "external": false,
      "loc": "net/sched/act_api.c:341",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tca_action_gd"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_idr_delete_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588695552,
      "name": "tcf_idr_delete_index",
      "external": false,
      "loc": "net/sched/act_api.c:367",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tca_action_gd"
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
  "name": "tcf_idr_delete_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588919668,
      "name": "tcf_idr_delete_index",
      "external": false,
      "loc": "net/sched/act_api.c:367",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tca_action_gd"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int tcf_idr_delete_index(struct tcf_idrinfo * idrinfo, u32 index)
```

```json
{
  "name": "tcf_idr_delete_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589801360,
      "name": "tcf_idr_delete_index",
      "external": false,
      "loc": "net/sched/act_api.c:371",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_del_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589801360,
      "name": "tcf_idr_delete_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
int tcf_idr_delete_index(struct tcf_idrinfo * idrinfo, u32 index)
```

```json
{
  "name": "tcf_idr_delete_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589837136,
      "name": "tcf_idr_delete_index",
      "external": false,
      "loc": "net/sched/act_api.c:423",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_del_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589837136,
      "name": "tcf_idr_delete_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_idr_delete_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589742552,
      "name": "tcf_idr_delete_index",
      "external": false,
      "loc": "net/sched/act_api.c:435",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_delete"
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
  "name": "tcf_idr_delete_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590508530,
      "name": "tcf_idr_delete_index",
      "external": false,
      "loc": "net/sched/act_api.c:435",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_del_notify"
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
  "name": "tcf_idr_delete_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592113743,
      "name": "tcf_idr_delete_index",
      "external": false,
      "loc": "net/sched/act_api.c:679",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_del_notify"
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
  "name": "tcf_idr_delete_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593935759,
      "name": "tcf_idr_delete_index",
      "external": false,
      "loc": "net/sched/act_api.c:705",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_del_notify"
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
  "name": "tcf_idr_delete_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594303960,
      "name": "tcf_idr_delete_index",
      "external": false,
      "loc": "net/sched/act_api.c:700",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "tcf_idr_delete_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595103208,
      "name": "tcf_idr_delete_index",
      "external": false,
      "loc": "net/sched/act_api.c:700",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "tcf_idr_delete_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502512516,
      "name": "tcf_idr_delete_index",
      "external": false,
      "loc": "net/sched/act_api.c:367",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tca_action_gd"
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
  "name": "tcf_idr_delete_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235224488,
      "name": "tcf_idr_delete_index",
      "external": false,
      "loc": "net/sched/act_api.c:367",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tca_action_gd"
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
  "name": "tcf_idr_delete_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296082448,
      "name": "tcf_idr_delete_index",
      "external": false,
      "loc": "net/sched/act_api.c:367",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tca_action_gd"
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
  "name": "tcf_idr_delete_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278684716,
      "name": "tcf_idr_delete_index",
      "external": false,
      "loc": "net/sched/act_api.c:367",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tca_action_gd"
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
  "name": "tcf_idr_delete_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588526052,
      "name": "tcf_idr_delete_index",
      "external": false,
      "loc": "net/sched/act_api.c:367",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tca_action_gd"
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
  "name": "tcf_idr_delete_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588238052,
      "name": "tcf_idr_delete_index",
      "external": false,
      "loc": "net/sched/act_api.c:367",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tca_action_gd"
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
  "name": "tcf_idr_delete_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588858228,
      "name": "tcf_idr_delete_index",
      "external": false,
      "loc": "net/sched/act_api.c:367",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tca_action_gd"
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
  "name": "tcf_idr_delete_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588999684,
      "name": "tcf_idr_delete_index",
      "external": false,
      "loc": "net/sched/act_api.c:367",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tca_action_gd"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int tcf_idr_delete_index(struct tcf_idrinfo * idrinfo, u32 index)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int tcf_idr_delete_index(struct tcf_idrinfo * idrinfo, u32 index)
```
</details>
</li>
</ul>
