# Function: <code>rt6_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rt6_release(struct rt6_info * rt)
```

```json
{
  "name": "rt6_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587077648,
      "name": "rt6_release",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:185",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_repair_tree",
        "net/ipv6/ip6_fib.c:fib6_add_1",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587077648,
      "name": "rt6_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rt6_release(struct rt6_info * rt)
```

```json
{
  "name": "rt6_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587529264,
      "name": "rt6_release",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:184",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_repair_tree",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add_1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587529264,
      "name": "rt6_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rt6_release(struct rt6_info * rt)
```

```json
{
  "name": "rt6_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587733616,
      "name": "rt6_release",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:184",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_repair_tree",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add_1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587733616,
      "name": "rt6_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rt6_release(struct rt6_info * rt)
```

```json
{
  "name": "rt6_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587887104,
      "name": "rt6_release",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:192",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_repair_tree",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add_1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587887104,
      "name": "rt6_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt6_release",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588405621,
      "name": "rt6_release",
      "external": false,
      "loc": "include/net/ip6_fib.h:269",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pol_route"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588429657,
      "name": "rt6_release",
      "external": false,
      "loc": "include/net/ip6_fib.h:269",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add"
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
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void rt6_release(struct rt6_info * rt)
```
</details>
</li>
</ul>
