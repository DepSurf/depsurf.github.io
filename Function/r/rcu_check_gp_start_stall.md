# Function: <code>rcu_check_gp_start_stall</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_check_gp_start_stall(struct rcu_node * rnp, struct rcu_data * rdp, const long unsigned int gpssdelay)
```

```json
{
  "name": "rcu_check_gp_start_stall",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579970962,
      "name": "rcu_check_gp_start_stall",
      "external": true,
      "loc": "kernel/rcu/tree.c:2628",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:rcu_fwd_progress_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973984,
      "name": "rcu_check_gp_start_stall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
  "name": "rcu_check_gp_start_stall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580016223,
      "name": "rcu_check_gp_start_stall",
      "external": false,
      "loc": "kernel/rcu/tree_stall.h:596",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_fwd_progress_check",
        "kernel/rcu/tree.c:rcu_core"
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
  "name": "rcu_check_gp_start_stall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580066865,
      "name": "rcu_check_gp_start_stall",
      "external": false,
      "loc": "kernel/rcu/tree_stall.h:605",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_fwd_progress_check",
        "kernel/rcu/tree.c:rcu_core"
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
  "name": "rcu_check_gp_start_stall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580126604,
      "name": "rcu_check_gp_start_stall",
      "external": false,
      "loc": "kernel/rcu/tree_stall.h:704",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_fwd_progress_check",
        "kernel/rcu/tree.c:rcu_core"
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
  "name": "rcu_check_gp_start_stall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591307103,
      "name": "rcu_check_gp_start_stall",
      "external": false,
      "loc": "kernel/rcu/tree_stall.h:723",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_fwd_progress_check",
        "kernel/rcu/tree.c:rcu_core"
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
  "name": "rcu_check_gp_start_stall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591249666,
      "name": "rcu_check_gp_start_stall",
      "external": false,
      "loc": "kernel/rcu/tree_stall.h:779",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_fwd_progress_check",
        "kernel/rcu/tree.c:rcu_core"
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
  "name": "rcu_check_gp_start_stall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592143547,
      "name": "rcu_check_gp_start_stall",
      "external": false,
      "loc": "kernel/rcu/tree_stall.h:874",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_fwd_progress_check",
        "kernel/rcu/tree.c:rcu_core"
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
  "name": "rcu_check_gp_start_stall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593914710,
      "name": "rcu_check_gp_start_stall",
      "external": false,
      "loc": "kernel/rcu/tree_stall.h:914",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_fwd_progress_check",
        "kernel/rcu/tree.c:rcu_core"
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
  "name": "rcu_check_gp_start_stall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580646563,
      "name": "rcu_check_gp_start_stall",
      "external": false,
      "loc": "kernel/rcu/tree_stall.h:906",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_fwd_progress_check",
        "kernel/rcu/tree.c:rcu_core"
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
  "name": "rcu_check_gp_start_stall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580718947,
      "name": "rcu_check_gp_start_stall",
      "external": false,
      "loc": "kernel/rcu/tree_stall.h:937",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_fwd_progress_check",
        "kernel/rcu/tree.c:rcu_core"
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
  "name": "rcu_check_gp_start_stall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580781267,
      "name": "rcu_check_gp_start_stall",
      "external": false,
      "loc": "kernel/rcu/tree_stall.h:943",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_fwd_progress_check",
        "kernel/rcu/tree.c:rcu_core"
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
  "name": "rcu_check_gp_start_stall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491280884,
      "name": "rcu_check_gp_start_stall",
      "external": false,
      "loc": "kernel/rcu/tree_stall.h:605",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_fwd_progress_check",
        "kernel/rcu/tree.c:rcu_core"
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
  "name": "rcu_check_gp_start_stall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225288164,
      "name": "rcu_check_gp_start_stall",
      "external": false,
      "loc": "kernel/rcu/tree_stall.h:605",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_fwd_progress_check",
        "kernel/rcu/tree.c:rcu_core"
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
  "name": "rcu_check_gp_start_stall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284185684,
      "name": "rcu_check_gp_start_stall",
      "external": false,
      "loc": "kernel/rcu/tree_stall.h:605",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_fwd_progress_check",
        "kernel/rcu/tree.c:rcu_core"
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
  "name": "rcu_check_gp_start_stall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271798682,
      "name": "rcu_check_gp_start_stall",
      "external": false,
      "loc": "kernel/rcu/tree_stall.h:605",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_fwd_progress_check",
        "kernel/rcu/tree.c:rcu_core"
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
  "name": "rcu_check_gp_start_stall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580035601,
      "name": "rcu_check_gp_start_stall",
      "external": false,
      "loc": "kernel/rcu/tree_stall.h:605",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_fwd_progress_check",
        "kernel/rcu/tree.c:rcu_core"
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
  "name": "rcu_check_gp_start_stall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579981002,
      "name": "rcu_check_gp_start_stall",
      "external": false,
      "loc": "kernel/rcu/tree_stall.h:605",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_fwd_progress_check",
        "kernel/rcu/tree.c:rcu_core"
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
  "name": "rcu_check_gp_start_stall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580027137,
      "name": "rcu_check_gp_start_stall",
      "external": false,
      "loc": "kernel/rcu/tree_stall.h:605",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_fwd_progress_check",
        "kernel/rcu/tree.c:rcu_core"
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
  "name": "rcu_check_gp_start_stall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580077000,
      "name": "rcu_check_gp_start_stall",
      "external": false,
      "loc": "kernel/rcu/tree_stall.h:605",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_fwd_progress_check",
        "kernel/rcu/tree.c:rcu_core"
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void rcu_check_gp_start_stall(struct rcu_node * rnp, struct rcu_data * rdp, const long unsigned int gpssdelay)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void rcu_check_gp_start_stall(struct rcu_node * rnp, struct rcu_data * rdp, const long unsigned int gpssdelay)
```
</details>
</li>
</ul>
