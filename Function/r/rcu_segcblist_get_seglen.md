# Function: <code>rcu_segcblist_get_seglen</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_segcblist_get_seglen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580111995,
      "name": "rcu_segcblist_get_seglen",
      "external": false,
      "loc": "kernel/rcu/rcu_segcblist.c:92",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_n_segment_cbs"
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
  "name": "rcu_segcblist_get_seglen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580253736,
      "name": "rcu_segcblist_get_seglen",
      "external": false,
      "loc": "kernel/rcu/rcu_segcblist.c:92",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_n_segment_cbs"
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
  "name": "rcu_segcblist_get_seglen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580422502,
      "name": "rcu_segcblist_get_seglen",
      "external": false,
      "loc": "kernel/rcu/rcu_segcblist.c:92",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_n_segment_cbs"
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
  "name": "rcu_segcblist_get_seglen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580662470,
      "name": "rcu_segcblist_get_seglen",
      "external": false,
      "loc": "kernel/rcu/rcu_segcblist.c:92",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_n_segment_cbs"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int rcu_segcblist_get_seglen(struct rcu_segcblist * rsclp, int seg)
```

```json
{
  "name": "rcu_segcblist_get_seglen",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580738662,
      "name": "rcu_segcblist_get_seglen",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:92",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_n_segment_cbs"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580736080,
      "name": "rcu_segcblist_get_seglen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int rcu_segcblist_get_seglen(struct rcu_segcblist * rsclp, int seg)
```

```json
{
  "name": "rcu_segcblist_get_seglen",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580823632,
      "name": "rcu_segcblist_get_seglen",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:92",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_n_segment_cbs"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580821136,
      "name": "rcu_segcblist_get_seglen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
long int rcu_segcblist_get_seglen(struct rcu_segcblist * rsclp, int seg)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
