# Function: <code>tcf_proto_get</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void tcf_proto_get(struct tcf_proto * tp)
```

```json
{
  "name": "tcf_proto_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588663200,
      "name": "tcf_proto_get",
      "external": false,
      "loc": "net/sched/cls_api.c:216",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_chain_tp_find",
        "net/sched/cls_api.c:__tcf_get_next_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588663200,
      "name": "tcf_proto_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void tcf_proto_get(struct tcf_proto * tp)
```

```json
{
  "name": "tcf_proto_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588885664,
      "name": "tcf_proto_get",
      "external": false,
      "loc": "net/sched/cls_api.c:286",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_chain_tp_find",
        "net/sched/cls_api.c:__tcf_get_next_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588885664,
      "name": "tcf_proto_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_proto_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589776704,
      "name": "tcf_proto_get",
      "external": false,
      "loc": "net/sched/cls_api.c:287",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_chain_tp_find",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique",
        "net/sched/cls_api.c:__tcf_get_next_proto"
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
  "name": "tcf_proto_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589811648,
      "name": "tcf_proto_get",
      "external": false,
      "loc": "net/sched/cls_api.c:287",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_chain_tp_find",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique",
        "net/sched/cls_api.c:__tcf_get_next_proto"
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
  "name": "tcf_proto_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589715200,
      "name": "tcf_proto_get",
      "external": false,
      "loc": "net/sched/cls_api.c:287",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_chain_tp_find",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique",
        "net/sched/cls_api.c:__tcf_get_next_proto"
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
  "name": "tcf_proto_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590473408,
      "name": "tcf_proto_get",
      "external": false,
      "loc": "net/sched/cls_api.c:287",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_chain_tp_find",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique",
        "net/sched/cls_api.c:__tcf_get_next_proto"
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
  "name": "tcf_proto_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592077472,
      "name": "tcf_proto_get",
      "external": false,
      "loc": "net/sched/cls_api.c:304",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_chain_tp_find",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique",
        "net/sched/cls_api.c:__tcf_get_next_proto"
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
  "name": "tcf_proto_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593898048,
      "name": "tcf_proto_get",
      "external": false,
      "loc": "net/sched/cls_api.c:306",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_chain_tp_find",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique",
        "net/sched/cls_api.c:__tcf_get_next_proto"
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
  "name": "tcf_proto_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594274304,
      "name": "tcf_proto_get",
      "external": false,
      "loc": "net/sched/cls_api.c:408",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_chain_tp_find",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique",
        "net/sched/cls_api.c:__tcf_get_next_proto"
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
  "name": "tcf_proto_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595072416,
      "name": "tcf_proto_get",
      "external": false,
      "loc": "net/sched/cls_api.c:408",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_chain_tp_find",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique",
        "net/sched/cls_api.c:__tcf_get_next_proto"
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
  "name": "tcf_proto_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502502420,
      "name": "tcf_proto_get",
      "external": false,
      "loc": "net/sched/cls_api.c:286",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:__tcf_get_next_proto"
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
  "name": "tcf_proto_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235209840,
      "name": "tcf_proto_get",
      "external": false,
      "loc": "net/sched/cls_api.c:286",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_chain_tp_find",
        "net/sched/cls_api.c:__tcf_get_next_proto"
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
  "name": "tcf_proto_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296058668,
      "name": "tcf_proto_get",
      "external": false,
      "loc": "net/sched/cls_api.c:286",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:__tcf_get_next_proto"
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
  "name": "tcf_proto_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278670962,
      "name": "tcf_proto_get",
      "external": false,
      "loc": "net/sched/cls_api.c:286",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:__tcf_get_next_proto"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void tcf_proto_get(struct tcf_proto * tp)
```

```json
{
  "name": "tcf_proto_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588492048,
      "name": "tcf_proto_get",
      "external": false,
      "loc": "net/sched/cls_api.c:286",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_chain_tp_find",
        "net/sched/cls_api.c:__tcf_get_next_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588492048,
      "name": "tcf_proto_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void tcf_proto_get(struct tcf_proto * tp)
```

```json
{
  "name": "tcf_proto_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588204048,
      "name": "tcf_proto_get",
      "external": false,
      "loc": "net/sched/cls_api.c:286",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_chain_tp_find",
        "net/sched/cls_api.c:__tcf_get_next_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588204048,
      "name": "tcf_proto_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void tcf_proto_get(struct tcf_proto * tp)
```

```json
{
  "name": "tcf_proto_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588824224,
      "name": "tcf_proto_get",
      "external": false,
      "loc": "net/sched/cls_api.c:286",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_chain_tp_find",
        "net/sched/cls_api.c:__tcf_get_next_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588824224,
      "name": "tcf_proto_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void tcf_proto_get(struct tcf_proto * tp)
```

```json
{
  "name": "tcf_proto_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588964832,
      "name": "tcf_proto_get",
      "external": false,
      "loc": "net/sched/cls_api.c:286",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_chain_tp_find",
        "net/sched/cls_api.c:__tcf_get_next_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588964832,
      "name": "tcf_proto_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void tcf_proto_get(struct tcf_proto * tp)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void tcf_proto_get(struct tcf_proto * tp)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void tcf_proto_get(struct tcf_proto * tp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void tcf_proto_get(struct tcf_proto * tp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void tcf_proto_get(struct tcf_proto * tp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void tcf_proto_get(struct tcf_proto * tp)
```
</details>
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
