# Function: <code>qdisc_maybe_clear_missed</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void qdisc_maybe_clear_missed(struct Qdisc * q, const struct netdev_queue * txq)
```

```json
{
  "name": "qdisc_maybe_clear_missed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589679776,
      "name": "qdisc_maybe_clear_missed",
      "external": false,
      "loc": "net/sched/sch_generic.c:38",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_generic.c:dequeue_skb",
        "net/sched/sch_generic.c:dequeue_skb",
        "net/sched/sch_generic.c:dequeue_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589679776,
      "name": "qdisc_maybe_clear_missed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void qdisc_maybe_clear_missed(struct Qdisc * q, const struct netdev_queue * txq)
```

```json
{
  "name": "qdisc_maybe_clear_missed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590436336,
      "name": "qdisc_maybe_clear_missed",
      "external": false,
      "loc": "net/sched/sch_generic.c:38",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_generic.c:dequeue_skb",
        "net/sched/sch_generic.c:dequeue_skb",
        "net/sched/sch_generic.c:dequeue_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590436336,
      "name": "qdisc_maybe_clear_missed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void qdisc_maybe_clear_missed(struct Qdisc * q, const struct netdev_queue * txq)
```

```json
{
  "name": "qdisc_maybe_clear_missed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592035600,
      "name": "qdisc_maybe_clear_missed",
      "external": false,
      "loc": "net/sched/sch_generic.c:38",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_generic.c:dequeue_skb",
        "net/sched/sch_generic.c:dequeue_skb",
        "net/sched/sch_generic.c:dequeue_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592035600,
      "name": "qdisc_maybe_clear_missed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void qdisc_maybe_clear_missed(struct Qdisc * q, const struct netdev_queue * txq)
```

```json
{
  "name": "qdisc_maybe_clear_missed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593852608,
      "name": "qdisc_maybe_clear_missed",
      "external": false,
      "loc": "net/sched/sch_generic.c:38",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_generic.c:dequeue_skb",
        "net/sched/sch_generic.c:dequeue_skb",
        "net/sched/sch_generic.c:dequeue_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593852608,
      "name": "qdisc_maybe_clear_missed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void qdisc_maybe_clear_missed(struct Qdisc * q, const struct netdev_queue * txq)
```

```json
{
  "name": "qdisc_maybe_clear_missed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594227264,
      "name": "qdisc_maybe_clear_missed",
      "external": false,
      "loc": "net/sched/sch_generic.c:38",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_generic.c:dequeue_skb",
        "net/sched/sch_generic.c:dequeue_skb",
        "net/sched/sch_generic.c:dequeue_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594227264,
      "name": "qdisc_maybe_clear_missed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void qdisc_maybe_clear_missed(struct Qdisc * q, const struct netdev_queue * txq)
```

```json
{
  "name": "qdisc_maybe_clear_missed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595024608,
      "name": "qdisc_maybe_clear_missed",
      "external": false,
      "loc": "net/sched/sch_generic.c:38",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_generic.c:dequeue_skb",
        "net/sched/sch_generic.c:dequeue_skb",
        "net/sched/sch_generic.c:dequeue_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595024608,
      "name": "qdisc_maybe_clear_missed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void qdisc_maybe_clear_missed(struct Qdisc * q, const struct netdev_queue * txq)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
