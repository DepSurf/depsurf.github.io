# Function: <code>sk_psock_skb_ingress</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_psock_skb_ingress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588176862,
      "name": "sk_psock_skb_ingress",
      "external": false,
      "loc": "net/core/skmsg.c:381",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog"
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
  "name": "sk_psock_skb_ingress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588502873,
      "name": "sk_psock_skb_ingress",
      "external": false,
      "loc": "net/core/skmsg.c:390",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog"
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
  "name": "sk_psock_skb_ingress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588711033,
      "name": "sk_psock_skb_ingress",
      "external": false,
      "loc": "net/core/skmsg.c:399",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog"
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
int sk_psock_skb_ingress(struct sk_psock * psock, struct sk_buff * skb)
```

```json
{
  "name": "sk_psock_skb_ingress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589575712,
      "name": "sk_psock_skb_ingress",
      "external": false,
      "loc": "net/core/skmsg.c:400",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_backlog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589575712,
      "name": "sk_psock_skb_ingress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_psock_skb_ingress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589591047,
      "name": "sk_psock_skb_ingress",
      "external": false,
      "loc": "net/core/skmsg.c:454",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog"
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
  "name": "sk_psock_skb_ingress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589652952,
      "name": "sk_psock_skb_ingress",
      "external": false,
      "loc": "net/core/skmsg.c:550",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog"
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
  "name": "sk_psock_skb_ingress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590409543,
      "name": "sk_psock_skb_ingress",
      "external": false,
      "loc": "net/core/skmsg.c:543",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog"
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
  "name": "sk_psock_skb_ingress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592004789,
      "name": "sk_psock_skb_ingress",
      "external": false,
      "loc": "net/core/skmsg.c:556",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog"
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
  "name": "sk_psock_skb_ingress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593818957,
      "name": "sk_psock_skb_ingress",
      "external": false,
      "loc": "net/core/skmsg.c:563",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog"
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
  "name": "sk_psock_skb_ingress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594193611,
      "name": "sk_psock_skb_ingress",
      "external": false,
      "loc": "net/core/skmsg.c:562",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog"
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
  "name": "sk_psock_skb_ingress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594989062,
      "name": "sk_psock_skb_ingress",
      "external": false,
      "loc": "net/core/skmsg.c:562",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog"
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
  "name": "sk_psock_skb_ingress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502278368,
      "name": "sk_psock_skb_ingress",
      "external": false,
      "loc": "net/core/skmsg.c:399",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog"
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
  "name": "sk_psock_skb_ingress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235013152,
      "name": "sk_psock_skb_ingress",
      "external": false,
      "loc": "net/core/skmsg.c:399",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog"
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
  "name": "sk_psock_skb_ingress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295772416,
      "name": "sk_psock_skb_ingress",
      "external": false,
      "loc": "net/core/skmsg.c:399",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog"
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
  "name": "sk_psock_skb_ingress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278508546,
      "name": "sk_psock_skb_ingress",
      "external": false,
      "loc": "net/core/skmsg.c:399",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog"
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
  "name": "sk_psock_skb_ingress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588317769,
      "name": "sk_psock_skb_ingress",
      "external": false,
      "loc": "net/core/skmsg.c:399",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog"
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
  "name": "sk_psock_skb_ingress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588030553,
      "name": "sk_psock_skb_ingress",
      "external": false,
      "loc": "net/core/skmsg.c:399",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog"
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
  "name": "sk_psock_skb_ingress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588649593,
      "name": "sk_psock_skb_ingress",
      "external": false,
      "loc": "net/core/skmsg.c:399",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog"
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
  "name": "sk_psock_skb_ingress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588789401,
      "name": "sk_psock_skb_ingress",
      "external": false,
      "loc": "net/core/skmsg.c:399",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog"
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
int sk_psock_skb_ingress(struct sk_psock * psock, struct sk_buff * skb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int sk_psock_skb_ingress(struct sk_psock * psock, struct sk_buff * skb)
```
</details>
</li>
</ul>
