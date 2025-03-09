# Function: <code>grub_reclaim</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 grub_reclaim(u64 delta, struct rq * rq, struct sched_dl_entity * dl_se)
```

```json
{
  "name": "grub_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579664415,
      "name": "grub_reclaim",
      "external": true,
      "loc": "kernel/sched/deadline.c:1088",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579666816,
      "name": "grub_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 grub_reclaim(u64 delta, struct rq * rq, struct sched_dl_entity * dl_se)
```

```json
{
  "name": "grub_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579694931,
      "name": "grub_reclaim",
      "external": true,
      "loc": "kernel/sched/deadline.c:1087",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579697312,
      "name": "grub_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
  "name": "grub_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579726556,
      "name": "grub_reclaim",
      "external": false,
      "loc": "kernel/sched/deadline.c:1120",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
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
  "name": "grub_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579768858,
      "name": "grub_reclaim",
      "external": false,
      "loc": "kernel/sched/deadline.c:1121",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
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
  "name": "grub_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579796199,
      "name": "grub_reclaim",
      "external": false,
      "loc": "kernel/sched/deadline.c:1120",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
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
  "name": "grub_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579842230,
      "name": "grub_reclaim",
      "external": false,
      "loc": "kernel/sched/deadline.c:1153",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
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
  "name": "grub_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579880902,
      "name": "grub_reclaim",
      "external": false,
      "loc": "kernel/sched/deadline.c:1155",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
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
  "name": "grub_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579874010,
      "name": "grub_reclaim",
      "external": false,
      "loc": "kernel/sched/deadline.c:1229",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
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
  "name": "grub_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579882830,
      "name": "grub_reclaim",
      "external": false,
      "loc": "kernel/sched/deadline.c:1215",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
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
  "name": "grub_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579998518,
      "name": "grub_reclaim",
      "external": false,
      "loc": "kernel/sched/deadline.c:1215",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
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
  "name": "grub_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580115899,
      "name": "grub_reclaim",
      "external": false,
      "loc": "kernel/sched/deadline.c:1276",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:update_curr_dl"
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
  "name": "grub_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580289277,
      "name": "grub_reclaim",
      "external": false,
      "loc": "kernel/sched/deadline.c:1281",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:update_curr_dl"
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
  "name": "grub_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580356645,
      "name": "grub_reclaim",
      "external": false,
      "loc": "kernel/sched/deadline.c:1274",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:update_curr_dl"
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
  "name": "grub_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580411778,
      "name": "grub_reclaim",
      "external": false,
      "loc": "kernel/sched/deadline.c:1303",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:update_curr_dl_se"
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
  "name": "grub_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491030776,
      "name": "grub_reclaim",
      "external": false,
      "loc": "kernel/sched/deadline.c:1153",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
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
  "name": "grub_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225039536,
      "name": "grub_reclaim",
      "external": false,
      "loc": "kernel/sched/deadline.c:1153",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
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
  "name": "grub_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283907364,
      "name": "grub_reclaim",
      "external": false,
      "loc": "kernel/sched/deadline.c:1153",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
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
  "name": "grub_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271635500,
      "name": "grub_reclaim",
      "external": false,
      "loc": "kernel/sched/deadline.c:1153",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
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
  "name": "grub_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579814582,
      "name": "grub_reclaim",
      "external": false,
      "loc": "kernel/sched/deadline.c:1153",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
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
  "name": "grub_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579749206,
      "name": "grub_reclaim",
      "external": false,
      "loc": "kernel/sched/deadline.c:1153",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
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
  "name": "grub_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579802598,
      "name": "grub_reclaim",
      "external": false,
      "loc": "kernel/sched/deadline.c:1153",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
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
  "name": "grub_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579847582,
      "name": "grub_reclaim",
      "external": false,
      "loc": "kernel/sched/deadline.c:1153",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
u64 grub_reclaim(u64 delta, struct rq * rq, struct sched_dl_entity * dl_se)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
u64 grub_reclaim(u64 delta, struct rq * rq, struct sched_dl_entity * dl_se)
```
</details>
</li>
</ul>
