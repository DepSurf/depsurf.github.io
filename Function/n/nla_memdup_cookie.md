# Function: <code>nla_memdup_cookie</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int nla_memdup_cookie(struct tc_action * a, struct nlattr * * tb)
```

```json
{
  "name": "nla_memdup_cookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587120848,
      "name": "nla_memdup_cookie",
      "external": true,
      "loc": "net/sched/act_api.c:535",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_init_1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587120848,
      "name": "nla_memdup_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nla_memdup_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587250809,
      "name": "nla_memdup_cookie",
      "external": false,
      "loc": "net/sched/act_api.c:586",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_init_1"
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
  "name": "nla_memdup_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587770254,
      "name": "nla_memdup_cookie",
      "external": false,
      "loc": "net/sched/act_api.c:602",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_init_1"
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
  "name": "nla_memdup_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588113340,
      "name": "nla_memdup_cookie",
      "external": false,
      "loc": "net/sched/act_api.c:622",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_init_1"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nla_memdup_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588294190,
      "name": "nla_memdup_cookie",
      "external": false,
      "loc": "net/sched/act_api.c:787",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_init_1"
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
  "name": "nla_memdup_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588692008,
      "name": "nla_memdup_cookie",
      "external": false,
      "loc": "net/sched/act_api.c:818",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_init_1"
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
  "name": "nla_memdup_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588915954,
      "name": "nla_memdup_cookie",
      "external": false,
      "loc": "net/sched/act_api.c:818",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_init_1"
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
struct tc_cookie * nla_memdup_cookie(struct nlattr * * tb)
```

```json
{
  "name": "nla_memdup_cookie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589800800,
      "name": "nla_memdup_cookie",
      "external": false,
      "loc": "net/sched/act_api.c:865",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_init_1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589800800,
      "name": "nla_memdup_cookie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
struct tc_cookie * nla_memdup_cookie(struct nlattr * * tb)
```

```json
{
  "name": "nla_memdup_cookie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589836576,
      "name": "nla_memdup_cookie",
      "external": false,
      "loc": "net/sched/act_api.c:871",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_init_1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589836576,
      "name": "nla_memdup_cookie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
  "name": "nla_memdup_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589746482,
      "name": "nla_memdup_cookie",
      "external": false,
      "loc": "net/sched/act_api.c:884",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_init_1"
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
  "name": "nla_memdup_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590504679,
      "name": "nla_memdup_cookie",
      "external": false,
      "loc": "net/sched/act_api.c:893",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_init_1"
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
  "name": "nla_memdup_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592108916,
      "name": "nla_memdup_cookie",
      "external": false,
      "loc": "net/sched/act_api.c:1214",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_init_1"
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
  "name": "nla_memdup_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593928788,
      "name": "nla_memdup_cookie",
      "external": false,
      "loc": "net/sched/act_api.c:1240",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_init_1"
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
  "name": "nla_memdup_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594305764,
      "name": "nla_memdup_cookie",
      "external": false,
      "loc": "net/sched/act_api.c:1235",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_init_1"
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
  "name": "nla_memdup_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595104859,
      "name": "nla_memdup_cookie",
      "external": false,
      "loc": "net/sched/act_api.c:1266",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_init_1"
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
  "name": "nla_memdup_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502508864,
      "name": "nla_memdup_cookie",
      "external": false,
      "loc": "net/sched/act_api.c:818",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_init_1"
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
  "name": "nla_memdup_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235220880,
      "name": "nla_memdup_cookie",
      "external": false,
      "loc": "net/sched/act_api.c:818",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_init_1"
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
  "name": "nla_memdup_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296077380,
      "name": "nla_memdup_cookie",
      "external": false,
      "loc": "net/sched/act_api.c:818",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_init_1"
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
  "name": "nla_memdup_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278681738,
      "name": "nla_memdup_cookie",
      "external": false,
      "loc": "net/sched/act_api.c:818",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_init_1"
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
  "name": "nla_memdup_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588522338,
      "name": "nla_memdup_cookie",
      "external": false,
      "loc": "net/sched/act_api.c:818",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_init_1"
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
  "name": "nla_memdup_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588234338,
      "name": "nla_memdup_cookie",
      "external": false,
      "loc": "net/sched/act_api.c:818",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_init_1"
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
  "name": "nla_memdup_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588854514,
      "name": "nla_memdup_cookie",
      "external": false,
      "loc": "net/sched/act_api.c:818",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_init_1"
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
  "name": "nla_memdup_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588995938,
      "name": "nla_memdup_cookie",
      "external": false,
      "loc": "net/sched/act_api.c:818",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_init_1"
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int nla_memdup_cookie(struct tc_action * a, struct nlattr * * tb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int nla_memdup_cookie(struct tc_action * a, struct nlattr * * tb)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct tc_cookie * nla_memdup_cookie(struct nlattr * * tb)
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
struct tc_cookie * nla_memdup_cookie(struct nlattr * * tb)
```
</details>
</li>
</ul>
