# Function: <code>dev_qdisc_enqueue</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int dev_qdisc_enqueue(struct sk_buff * skb, struct Qdisc * q, struct sk_buff * * to_free, struct netdev_queue * txq)
```

```json
{
  "name": "dev_qdisc_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589966288,
      "name": "dev_qdisc_enqueue",
      "external": false,
      "loc": "net/core/dev.c:3773",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589966288,
      "name": "dev_qdisc_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
int dev_qdisc_enqueue(struct sk_buff * skb, struct Qdisc * q, struct sk_buff * * to_free, struct netdev_queue * txq)
```

```json
{
  "name": "dev_qdisc_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591509152,
      "name": "dev_qdisc_enqueue",
      "external": false,
      "loc": "net/core/dev.c:3779",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591509152,
      "name": "dev_qdisc_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
int dev_qdisc_enqueue(struct sk_buff * skb, struct Qdisc * q, struct sk_buff * * to_free, struct netdev_queue * txq)
```

```json
{
  "name": "dev_qdisc_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593276240,
      "name": "dev_qdisc_enqueue",
      "external": false,
      "loc": "net/core/dev.c:3766",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593276240,
      "name": "dev_qdisc_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
int dev_qdisc_enqueue(struct sk_buff * skb, struct Qdisc * q, struct sk_buff * * to_free, struct netdev_queue * txq)
```

```json
{
  "name": "dev_qdisc_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593732288,
      "name": "dev_qdisc_enqueue",
      "external": false,
      "loc": "net/core/dev.c:3726",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593732288,
      "name": "dev_qdisc_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
int dev_qdisc_enqueue(struct sk_buff * skb, struct Qdisc * q, struct sk_buff * * to_free, struct netdev_queue * txq)
```

```json
{
  "name": "dev_qdisc_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594514880,
      "name": "dev_qdisc_enqueue",
      "external": false,
      "loc": "net/core/dev.c:3736",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594514880,
      "name": "dev_qdisc_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int dev_qdisc_enqueue(struct sk_buff * skb, struct Qdisc * q, struct sk_buff * * to_free, struct netdev_queue * txq)
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
