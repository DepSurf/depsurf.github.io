# Function: <code>tcf_block_bind</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_block_bind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588671157,
      "name": "tcf_block_bind",
      "external": false,
      "loc": "net/sched/cls_api.c:1561",
      "file": "net/sched/cls_api.c",
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
  "name": "tcf_block_bind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588897557,
      "name": "tcf_block_bind",
      "external": false,
      "loc": "net/sched/cls_api.c:1477",
      "file": "net/sched/cls_api.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int tcf_block_bind(struct tcf_block * block, struct flow_block_offload * bo)
```

```json
{
  "name": "tcf_block_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589784848,
      "name": "tcf_block_bind",
      "external": false,
      "loc": "net/sched/cls_api.c:1440",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589784848,
      "name": "tcf_block_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
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
int tcf_block_bind(struct tcf_block * block, struct flow_block_offload * bo)
```

```json
{
  "name": "tcf_block_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589820128,
      "name": "tcf_block_bind",
      "external": false,
      "loc": "net/sched/cls_api.c:1441",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589820128,
      "name": "tcf_block_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
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
  "name": "tcf_block_bind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589723461,
      "name": "tcf_block_bind",
      "external": false,
      "loc": "net/sched/cls_api.c:1441",
      "file": "net/sched/cls_api.c",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int tcf_block_bind(struct tcf_block * block, struct flow_block_offload * bo)
```

```json
{
  "name": "tcf_block_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_block_bind",
      "external": false,
      "loc": "net/sched/cls_api.c:1442",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590481728,
      "name": "tcf_block_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
    },
    {
      "addr": 18446744071592710615,
      "name": "tcf_block_bind.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
int tcf_block_bind(struct tcf_block * block, struct flow_block_offload * bo)
```

```json
{
  "name": "tcf_block_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_block_bind",
      "external": false,
      "loc": "net/sched/cls_api.c:1459",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592085024,
      "name": "tcf_block_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
    },
    {
      "addr": 18446744071594596823,
      "name": "tcf_block_bind.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
int tcf_block_bind(struct tcf_block * block, struct flow_block_offload * bo)
```

```json
{
  "name": "tcf_block_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_block_bind",
      "external": false,
      "loc": "net/sched/cls_api.c:1461",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593903648,
      "name": "tcf_block_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
    },
    {
      "addr": 18446744071596333025,
      "name": "tcf_block_bind.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
int tcf_block_bind(struct tcf_block * block, struct flow_block_offload * bo)
```

```json
{
  "name": "tcf_block_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_block_bind",
      "external": false,
      "loc": "net/sched/cls_api.c:1566",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594283440,
      "name": "tcf_block_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
    },
    {
      "addr": 18446744071596861913,
      "name": "tcf_block_bind.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
int tcf_block_bind(struct tcf_block * block, struct flow_block_offload * bo)
```

```json
{
  "name": "tcf_block_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_block_bind",
      "external": false,
      "loc": "net/sched/cls_api.c:1596",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595082496,
      "name": "tcf_block_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
    },
    {
      "addr": 18446744071597787005,
      "name": "tcf_block_bind.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_block_bind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502488012,
      "name": "tcf_block_bind",
      "external": false,
      "loc": "net/sched/cls_api.c:1477",
      "file": "net/sched/cls_api.c",
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
  "name": "tcf_block_bind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235201468,
      "name": "tcf_block_bind",
      "external": false,
      "loc": "net/sched/cls_api.c:1477",
      "file": "net/sched/cls_api.c",
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
  "name": "tcf_block_bind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296050672,
      "name": "tcf_block_bind",
      "external": false,
      "loc": "net/sched/cls_api.c:1477",
      "file": "net/sched/cls_api.c",
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
  "name": "tcf_block_bind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278666278,
      "name": "tcf_block_bind",
      "external": false,
      "loc": "net/sched/cls_api.c:1477",
      "file": "net/sched/cls_api.c",
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
  "name": "tcf_block_bind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588503941,
      "name": "tcf_block_bind",
      "external": false,
      "loc": "net/sched/cls_api.c:1477",
      "file": "net/sched/cls_api.c",
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
  "name": "tcf_block_bind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588215941,
      "name": "tcf_block_bind",
      "external": false,
      "loc": "net/sched/cls_api.c:1477",
      "file": "net/sched/cls_api.c",
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
  "name": "tcf_block_bind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588836117,
      "name": "tcf_block_bind",
      "external": false,
      "loc": "net/sched/cls_api.c:1477",
      "file": "net/sched/cls_api.c",
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
  "name": "tcf_block_bind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588976597,
      "name": "tcf_block_bind",
      "external": false,
      "loc": "net/sched/cls_api.c:1477",
      "file": "net/sched/cls_api.c",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int tcf_block_bind(struct tcf_block * block, struct flow_block_offload * bo)
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
int tcf_block_bind(struct tcf_block * block, struct flow_block_offload * bo)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int tcf_block_bind(struct tcf_block * block, struct flow_block_offload * bo)
```
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
