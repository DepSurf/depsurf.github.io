# Function: <code>uevent_net_broadcast</code>

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
  "name": "uevent_net_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589141160,
      "name": "uevent_net_broadcast",
      "external": false,
      "loc": "lib/kobject_uevent.c:676",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
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
  "name": "uevent_net_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589378472,
      "name": "uevent_net_broadcast",
      "external": false,
      "loc": "lib/kobject_uevent.c:678",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
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
  "name": "uevent_net_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589835656,
      "name": "uevent_net_broadcast",
      "external": false,
      "loc": "lib/kobject_uevent.c:681",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
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
  "name": "uevent_net_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590061800,
      "name": "uevent_net_broadcast",
      "external": false,
      "loc": "lib/kobject_uevent.c:681",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
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
int uevent_net_broadcast(struct sock * usk, struct sk_buff * skb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "uevent_net_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585057856,
      "name": "uevent_net_broadcast",
      "external": false,
      "loc": "lib/kobject_uevent.c:681",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585057856,
      "name": "uevent_net_broadcast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
int uevent_net_broadcast(struct sock * usk, struct sk_buff * skb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "uevent_net_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585207328,
      "name": "uevent_net_broadcast",
      "external": false,
      "loc": "lib/kobject_uevent.c:681",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585207328,
      "name": "uevent_net_broadcast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
  "name": "uevent_net_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585090392,
      "name": "uevent_net_broadcast",
      "external": false,
      "loc": "lib/kobject_uevent.c:682",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
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
  "name": "uevent_net_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585537832,
      "name": "uevent_net_broadcast",
      "external": false,
      "loc": "lib/kobject_uevent.c:682",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
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
  "name": "uevent_net_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586692168,
      "name": "uevent_net_broadcast",
      "external": false,
      "loc": "lib/kobject_uevent.c:682",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
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
  "name": "uevent_net_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595773624,
      "name": "uevent_net_broadcast",
      "external": false,
      "loc": "lib/kobject_uevent.c:682",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
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
  "name": "uevent_net_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596298184,
      "name": "uevent_net_broadcast",
      "external": false,
      "loc": "lib/kobject_uevent.c:682",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
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
  "name": "uevent_net_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597183272,
      "name": "uevent_net_broadcast",
      "external": false,
      "loc": "lib/kobject_uevent.c:682",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
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
  "name": "uevent_net_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503839304,
      "name": "uevent_net_broadcast",
      "external": false,
      "loc": "lib/kobject_uevent.c:681",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
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
  "name": "uevent_net_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236458008,
      "name": "uevent_net_broadcast",
      "external": false,
      "loc": "lib/kobject_uevent.c:681",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
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
  "name": "uevent_net_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297686408,
      "name": "uevent_net_broadcast",
      "external": false,
      "loc": "lib/kobject_uevent.c:681",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
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
  "name": "uevent_net_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279728340,
      "name": "uevent_net_broadcast",
      "external": false,
      "loc": "lib/kobject_uevent.c:681",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
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
  "name": "uevent_net_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589664056,
      "name": "uevent_net_broadcast",
      "external": false,
      "loc": "lib/kobject_uevent.c:681",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
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
  "name": "uevent_net_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589389880,
      "name": "uevent_net_broadcast",
      "external": false,
      "loc": "lib/kobject_uevent.c:681",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
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
  "name": "uevent_net_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590107432,
      "name": "uevent_net_broadcast",
      "external": false,
      "loc": "lib/kobject_uevent.c:681",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
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
  "name": "uevent_net_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590157736,
      "name": "uevent_net_broadcast",
      "external": false,
      "loc": "lib/kobject_uevent.c:681",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
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
int uevent_net_broadcast(struct sock * usk, struct sk_buff * skb, struct netlink_ext_ack * extack)
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
int uevent_net_broadcast(struct sock * usk, struct sk_buff * skb, struct netlink_ext_ack * extack)
```
</details>
</li>
</ul>
