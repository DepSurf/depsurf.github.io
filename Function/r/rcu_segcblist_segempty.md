# Function: <code>rcu_segcblist_segempty</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool rcu_segcblist_segempty(struct rcu_segcblist * rsclp, int seg)
```

```json
{
  "name": "rcu_segcblist_segempty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579857008,
      "name": "rcu_segcblist_segempty",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:109",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857008,
      "name": "rcu_segcblist_segempty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_segcblist_segempty",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580749740,
      "name": "rcu_segcblist_segempty",
      "external": false,
      "loc": "kernel/rcu/rcu_segcblist.h:121",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580761648,
      "name": "rcu_segcblist_segempty",
      "external": false,
      "loc": "kernel/rcu/rcu_segcblist.h:121",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:show_rcu_nocb_state",
        "kernel/rcu/tree.c:show_rcu_nocb_state",
        "kernel/rcu/tree.c:show_rcu_nocb_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580823576,
      "name": "rcu_segcblist_segempty",
      "external": false,
      "loc": "kernel/rcu/rcu_segcblist.h:121",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
bool rcu_segcblist_segempty(struct rcu_segcblist * rsclp, int seg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
bool rcu_segcblist_segempty(struct rcu_segcblist * rsclp, int seg)
```
</details>
</li>
</ul>
