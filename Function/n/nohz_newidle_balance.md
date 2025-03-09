# Function: <code>nohz_newidle_balance</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nohz_newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579701105,
      "name": "nohz_newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9703",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
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
  "name": "nohz_newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579740173,
      "name": "nohz_newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9804",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
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
  "name": "nohz_newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579769515,
      "name": "nohz_newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9744",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
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
  "name": "nohz_newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579812486,
      "name": "nohz_newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9728",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:newidle_balance"
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
void nohz_newidle_balance(struct rq * this_rq)
```

```json
{
  "name": "nohz_newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851728,
      "name": "nohz_newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:10408",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:newidle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851728,
      "name": "nohz_newidle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void nohz_newidle_balance(struct rq * this_rq)
```

```json
{
  "name": "nohz_newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579843872,
      "name": "nohz_newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:10522",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:newidle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579843872,
      "name": "nohz_newidle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
  "name": "nohz_newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579851202,
      "name": "nohz_newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:10584",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:newidle_balance"
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
  "name": "nohz_newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579956428,
      "name": "nohz_newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:10826",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:newidle_balance"
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
  "name": "nohz_newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580071559,
      "name": "nohz_newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:10942",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:newidle_balance"
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
  "name": "nohz_newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580242007,
      "name": "nohz_newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:11469",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:newidle_balance"
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
  "name": "nohz_newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580307971,
      "name": "nohz_newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:11773",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:newidle_balance"
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
  "name": "nohz_newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580360531,
      "name": "nohz_newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:12248",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:newidle_balance"
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
  "name": "nohz_newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490993476,
      "name": "nohz_newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9728",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:newidle_balance"
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
  "name": "nohz_newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225002976,
      "name": "nohz_newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9728",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:newidle_balance"
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
  "name": "nohz_newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283863932,
      "name": "nohz_newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9728",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:newidle_balance"
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
  "name": "nohz_newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271604832,
      "name": "nohz_newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9728",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:newidle_balance"
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
  "name": "nohz_newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579788262,
      "name": "nohz_newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9728",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:newidle_balance"
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
  "name": "nohz_newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579719046,
      "name": "nohz_newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9728",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:newidle_balance"
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
  "name": "nohz_newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579772854,
      "name": "nohz_newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9728",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:newidle_balance"
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
  "name": "nohz_newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579820542,
      "name": "nohz_newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9728",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:newidle_balance"
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
void nohz_newidle_balance(struct rq * this_rq)
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
void nohz_newidle_balance(struct rq * this_rq)
```
</details>
</li>
</ul>
