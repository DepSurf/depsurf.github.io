# Function: <code>fnhe_dump_bucket</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fnhe_dump_bucket",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fnhe_dump_bucket",
      "external": false,
      "loc": "net/ipv4/route.c:2861",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe"
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
  "name": "fnhe_dump_bucket",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fnhe_dump_bucket",
      "external": false,
      "loc": "net/ipv4/route.c:2872",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe"
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
int fnhe_dump_bucket(struct net * net, struct sk_buff * skb, struct netlink_callback * cb, u32 table_id, struct fnhe_hash_bucket * bucket, int genid, int * fa_index, int fa_start, unsigned int flags)
```

```json
{
  "name": "fnhe_dump_bucket",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589926656,
      "name": "fnhe_dump_bucket",
      "external": false,
      "loc": "net/ipv4/route.c:2959",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:fib_dump_info_fnhe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589926656,
      "name": "fnhe_dump_bucket",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
int fnhe_dump_bucket(struct net * net, struct sk_buff * skb, struct netlink_callback * cb, u32 table_id, struct fnhe_hash_bucket * bucket, int genid, int * fa_index, int fa_start, unsigned int flags)
```

```json
{
  "name": "fnhe_dump_bucket",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589967232,
      "name": "fnhe_dump_bucket",
      "external": false,
      "loc": "net/ipv4/route.c:2941",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:fib_dump_info_fnhe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589967232,
      "name": "fnhe_dump_bucket",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
  "name": "fnhe_dump_bucket",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589904584,
      "name": "fnhe_dump_bucket",
      "external": false,
      "loc": "net/ipv4/route.c:2942",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe"
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
  "name": "fnhe_dump_bucket",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590670428,
      "name": "fnhe_dump_bucket",
      "external": false,
      "loc": "net/ipv4/route.c:3060",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe"
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
  "name": "fnhe_dump_bucket",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592296750,
      "name": "fnhe_dump_bucket",
      "external": false,
      "loc": "net/ipv4/route.c:3084",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe"
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
  "name": "fnhe_dump_bucket",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594132366,
      "name": "fnhe_dump_bucket",
      "external": false,
      "loc": "net/ipv4/route.c:3075",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe"
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
  "name": "fnhe_dump_bucket",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594519390,
      "name": "fnhe_dump_bucket",
      "external": false,
      "loc": "net/ipv4/route.c:3071",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe"
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
  "name": "fnhe_dump_bucket",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595322094,
      "name": "fnhe_dump_bucket",
      "external": false,
      "loc": "net/ipv4/route.c:3026",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe"
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
  "name": "fnhe_dump_bucket",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fnhe_dump_bucket",
      "external": false,
      "loc": "net/ipv4/route.c:2872",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe"
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
  "name": "fnhe_dump_bucket",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fnhe_dump_bucket",
      "external": false,
      "loc": "net/ipv4/route.c:2872",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe"
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
  "name": "fnhe_dump_bucket",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fnhe_dump_bucket",
      "external": false,
      "loc": "net/ipv4/route.c:2872",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe"
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
  "name": "fnhe_dump_bucket",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278749006,
      "name": "fnhe_dump_bucket",
      "external": false,
      "loc": "net/ipv4/route.c:2872",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe"
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
  "name": "fnhe_dump_bucket",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fnhe_dump_bucket",
      "external": false,
      "loc": "net/ipv4/route.c:2872",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe"
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
  "name": "fnhe_dump_bucket",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fnhe_dump_bucket",
      "external": false,
      "loc": "net/ipv4/route.c:2872",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe"
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
  "name": "fnhe_dump_bucket",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fnhe_dump_bucket",
      "external": false,
      "loc": "net/ipv4/route.c:2872",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe"
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
  "name": "fnhe_dump_bucket",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fnhe_dump_bucket",
      "external": false,
      "loc": "net/ipv4/route.c:2872",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe"
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
int fnhe_dump_bucket(struct net * net, struct sk_buff * skb, struct netlink_callback * cb, u32 table_id, struct fnhe_hash_bucket * bucket, int genid, int * fa_index, int fa_start, unsigned int flags)
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
int fnhe_dump_bucket(struct net * net, struct sk_buff * skb, struct netlink_callback * cb, u32 table_id, struct fnhe_hash_bucket * bucket, int genid, int * fa_index, int fa_start, unsigned int flags)
```
</details>
</li>
</ul>
