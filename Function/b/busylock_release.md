# Function: <code>busylock_release</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "busylock_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587384543,
      "name": "busylock_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1234",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "busylock_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587529107,
      "name": "busylock_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1274",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void busylock_release(spinlock_t * busy)
```

```json
{
  "name": "busylock_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588039088,
      "name": "busylock_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1281",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588039088,
      "name": "busylock_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "busylock_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588404915,
      "name": "busylock_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1351",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
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
  "name": "busylock_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588596483,
      "name": "busylock_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1419",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
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
  "name": "busylock_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589008057,
      "name": "busylock_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1406",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
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
  "name": "busylock_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589232613,
      "name": "busylock_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1441",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
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
  "name": "busylock_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590207221,
      "name": "busylock_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1447",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
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
  "name": "busylock_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590257877,
      "name": "busylock_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1497",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
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
  "name": "busylock_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590171637,
      "name": "busylock_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1516",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
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
  "name": "busylock_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590952373,
      "name": "busylock_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1517",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
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
  "name": "busylock_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592577683,
      "name": "busylock_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1517",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
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
  "name": "busylock_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594449187,
      "name": "busylock_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1528",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
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
  "name": "busylock_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594840915,
      "name": "busylock_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1500",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
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
  "name": "busylock_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595650979,
      "name": "busylock_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1475",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
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
  "name": "busylock_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502855104,
      "name": "busylock_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1441",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
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
  "name": "busylock_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235542732,
      "name": "busylock_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1441",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
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
  "name": "busylock_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296510404,
      "name": "busylock_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1441",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
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
  "name": "busylock_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278963550,
      "name": "busylock_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1441",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
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
  "name": "busylock_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588838997,
      "name": "busylock_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1441",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
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
  "name": "busylock_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588550933,
      "name": "busylock_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1441",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
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
  "name": "busylock_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589275173,
      "name": "busylock_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1441",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
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
  "name": "busylock_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589315701,
      "name": "busylock_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1441",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void busylock_release(spinlock_t * busy)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void busylock_release(spinlock_t * busy)
```
</details>
</li>
</ul>
