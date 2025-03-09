# Function: <code>rcu_poll_gp_seq_end_unlocked</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void rcu_poll_gp_seq_end_unlocked(long unsigned int * snap)
```

```json
{
  "name": "rcu_poll_gp_seq_end_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580626240,
      "name": "rcu_poll_gp_seq_end_unlocked",
      "external": false,
      "loc": "kernel/rcu/tree.c:1415",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:rcu_exp_wait_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580626240,
      "name": "rcu_poll_gp_seq_end_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void rcu_poll_gp_seq_end_unlocked(long unsigned int * snap)
```

```json
{
  "name": "rcu_poll_gp_seq_end_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580700016,
      "name": "rcu_poll_gp_seq_end_unlocked",
      "external": false,
      "loc": "kernel/rcu/tree.c:1368",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:synchronize_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580700016,
      "name": "rcu_poll_gp_seq_end_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void rcu_poll_gp_seq_end_unlocked(long unsigned int * snap)
```

```json
{
  "name": "rcu_poll_gp_seq_end_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580766624,
      "name": "rcu_poll_gp_seq_end_unlocked",
      "external": false,
      "loc": "kernel/rcu/tree.c:1410",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:synchronize_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580766624,
      "name": "rcu_poll_gp_seq_end_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void rcu_poll_gp_seq_end_unlocked(long unsigned int * snap)
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
