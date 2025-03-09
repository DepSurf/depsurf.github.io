# Function: <code>tcf_idr_release_unsafe</code>

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
  "name": "tcf_idr_release_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588296382,
      "name": "tcf_idr_release_unsafe",
      "external": false,
      "loc": "net/sched/act_api.c:248",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_idr_release_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588694138,
      "name": "tcf_idr_release_unsafe",
      "external": false,
      "loc": "net/sched/act_api.c:273",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_idr_release_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588918234,
      "name": "tcf_idr_release_unsafe",
      "external": false,
      "loc": "net/sched/act_api.c:273",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_idr_release_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589802770,
      "name": "tcf_idr_release_unsafe",
      "external": false,
      "loc": "net/sched/act_api.c:277",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_del_walker"
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
  "name": "tcf_idr_release_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589838576,
      "name": "tcf_idr_release_unsafe",
      "external": false,
      "loc": "net/sched/act_api.c:327",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_del_walker"
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
  "name": "tcf_idr_release_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589743398,
      "name": "tcf_idr_release_unsafe",
      "external": false,
      "loc": "net/sched/act_api.c:338",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_del_walker"
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
  "name": "tcf_idr_release_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590501878,
      "name": "tcf_idr_release_unsafe",
      "external": false,
      "loc": "net/sched/act_api.c:338",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_del_walker"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcf_idr_release_unsafe(struct tc_action * p)
```

```json
{
  "name": "tcf_idr_release_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592106064,
      "name": "tcf_idr_release_unsafe",
      "external": false,
      "loc": "net/sched/act_api.c:576",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592106064,
      "name": "tcf_idr_release_unsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcf_idr_release_unsafe(struct tc_action * p)
```

```json
{
  "name": "tcf_idr_release_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593927584,
      "name": "tcf_idr_release_unsafe",
      "external": false,
      "loc": "net/sched/act_api.c:577",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593927584,
      "name": "tcf_idr_release_unsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcf_idr_release_unsafe(struct tc_action * p)
```

```json
{
  "name": "tcf_idr_release_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594302528,
      "name": "tcf_idr_release_unsafe",
      "external": false,
      "loc": "net/sched/act_api.c:572",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594302528,
      "name": "tcf_idr_release_unsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_idr_release_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595115066,
      "name": "tcf_idr_release_unsafe",
      "external": false,
      "loc": "net/sched/act_api.c:572",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_reoffload_cb",
        "net/sched/act_api.c:tcf_action_reoffload_cb"
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
  "name": "tcf_idr_release_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502510948,
      "name": "tcf_idr_release_unsafe",
      "external": false,
      "loc": "net/sched/act_api.c:273",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "tcf_idr_release_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235222952,
      "name": "tcf_idr_release_unsafe",
      "external": false,
      "loc": "net/sched/act_api.c:273",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "tcf_idr_release_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296080312,
      "name": "tcf_idr_release_unsafe",
      "external": false,
      "loc": "net/sched/act_api.c:273",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_idr_release_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278683456,
      "name": "tcf_idr_release_unsafe",
      "external": false,
      "loc": "net/sched/act_api.c:273",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_idr_release_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588524618,
      "name": "tcf_idr_release_unsafe",
      "external": false,
      "loc": "net/sched/act_api.c:273",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_idr_release_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588236618,
      "name": "tcf_idr_release_unsafe",
      "external": false,
      "loc": "net/sched/act_api.c:273",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_idr_release_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588856794,
      "name": "tcf_idr_release_unsafe",
      "external": false,
      "loc": "net/sched/act_api.c:273",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_idr_release_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588998250,
      "name": "tcf_idr_release_unsafe",
      "external": false,
      "loc": "net/sched/act_api.c:273",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int tcf_idr_release_unsafe(struct tc_action * p)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int tcf_idr_release_unsafe(struct tc_action * p)
```
</details>
</li>
</ul>
