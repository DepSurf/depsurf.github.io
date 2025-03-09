# Function: <code>get_state_synchronize_rcu_full</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void get_state_synchronize_rcu_full(struct rcu_gp_oldstate * rgosp)
```

```json
{
  "name": "get_state_synchronize_rcu_full",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580624837,
      "name": "get_state_synchronize_rcu_full",
      "external": true,
      "loc": "kernel/rcu/tree.c:3620",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited_full",
        "kernel/rcu/tree.c:start_poll_synchronize_rcu_full"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580612432,
      "name": "get_state_synchronize_rcu_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void get_state_synchronize_rcu_full(struct rcu_gp_oldstate * rgosp)
```

```json
{
  "name": "get_state_synchronize_rcu_full",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580703557,
      "name": "get_state_synchronize_rcu_full",
      "external": true,
      "loc": "kernel/rcu/tree.c:3612",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited_full",
        "kernel/rcu/tree.c:start_poll_synchronize_rcu_full",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/rcu/tree.c:kfree_rcu_monitor"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580686272,
      "name": "get_state_synchronize_rcu_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void get_state_synchronize_rcu_full(struct rcu_gp_oldstate * rgosp)
```

```json
{
  "name": "get_state_synchronize_rcu_full",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580769893,
      "name": "get_state_synchronize_rcu_full",
      "external": true,
      "loc": "kernel/rcu/tree.c:3684",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited_full",
        "kernel/rcu/tree.c:start_poll_synchronize_rcu_full",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/rcu/tree.c:kfree_rcu_monitor"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580753088,
      "name": "get_state_synchronize_rcu_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void get_state_synchronize_rcu_full(struct rcu_gp_oldstate * rgosp)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
