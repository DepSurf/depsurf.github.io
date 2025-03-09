# Function: <code>fib_add_multipath</code>

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
  "name": "fib_add_multipath",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589109498,
      "name": "fib_add_multipath",
      "external": false,
      "loc": "net/ipv4/fib_semantics.c:1687",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
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
  "name": "fib_add_multipath",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589333690,
      "name": "fib_add_multipath",
      "external": false,
      "loc": "net/ipv4/fib_semantics.c:1687",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
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
int fib_add_multipath(struct sk_buff * skb, struct fib_info * fi)
```

```json
{
  "name": "fib_add_multipath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590302320,
      "name": "fib_add_multipath",
      "external": false,
      "loc": "net/ipv4/fib_semantics.c:1696",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590302320,
      "name": "fib_add_multipath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
int fib_add_multipath(struct sk_buff * skb, struct fib_info * fi)
```

```json
{
  "name": "fib_add_multipath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590355936,
      "name": "fib_add_multipath",
      "external": false,
      "loc": "net/ipv4/fib_semantics.c:1695",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590355936,
      "name": "fib_add_multipath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
  "name": "fib_add_multipath",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590281930,
      "name": "fib_add_multipath",
      "external": false,
      "loc": "net/ipv4/fib_semantics.c:1696",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
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
  "name": "fib_add_multipath",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591068465,
      "name": "fib_add_multipath",
      "external": false,
      "loc": "net/ipv4/fib_semantics.c:1741",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
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
  "name": "fib_add_multipath",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592717469,
      "name": "fib_add_multipath",
      "external": false,
      "loc": "net/ipv4/fib_semantics.c:1728",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
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
  "name": "fib_add_multipath",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594587661,
      "name": "fib_add_multipath",
      "external": false,
      "loc": "net/ipv4/fib_semantics.c:1734",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
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
  "name": "fib_add_multipath",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594979309,
      "name": "fib_add_multipath",
      "external": false,
      "loc": "net/ipv4/fib_semantics.c:1734",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
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
  "name": "fib_add_multipath",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595791805,
      "name": "fib_add_multipath",
      "external": false,
      "loc": "net/ipv4/fib_semantics.c:1741",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
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
  "name": "fib_add_multipath",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502972552,
      "name": "fib_add_multipath",
      "external": false,
      "loc": "net/ipv4/fib_semantics.c:1687",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
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
  "name": "fib_add_multipath",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235661860,
      "name": "fib_add_multipath",
      "external": false,
      "loc": "net/ipv4/fib_semantics.c:1687",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
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
  "name": "fib_add_multipath",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296654568,
      "name": "fib_add_multipath",
      "external": false,
      "loc": "net/ipv4/fib_semantics.c:1687",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
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
  "name": "fib_add_multipath",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279051868,
      "name": "fib_add_multipath",
      "external": false,
      "loc": "net/ipv4/fib_semantics.c:1687",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
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
  "name": "fib_add_multipath",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588939866,
      "name": "fib_add_multipath",
      "external": false,
      "loc": "net/ipv4/fib_semantics.c:1687",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
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
  "name": "fib_add_multipath",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588651802,
      "name": "fib_add_multipath",
      "external": false,
      "loc": "net/ipv4/fib_semantics.c:1687",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
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
  "name": "fib_add_multipath",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589376250,
      "name": "fib_add_multipath",
      "external": false,
      "loc": "net/ipv4/fib_semantics.c:1687",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
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
  "name": "fib_add_multipath",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589419226,
      "name": "fib_add_multipath",
      "external": false,
      "loc": "net/ipv4/fib_semantics.c:1687",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
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
int fib_add_multipath(struct sk_buff * skb, struct fib_info * fi)
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
int fib_add_multipath(struct sk_buff * skb, struct fib_info * fi)
```
</details>
</li>
</ul>
