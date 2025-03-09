# Function: <code>ip6_rcv_core</code>

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
  "name": "ip6_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588909104,
      "name": "ip6_rcv_core",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:121",
      "file": "net/ipv6/ip6_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ipv6_list_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588909104,
      "name": "ip6_rcv_core.isra.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1097
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589351216,
      "name": "ip6_rcv_core",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:121",
      "file": "net/ipv6/ip6_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ipv6_list_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589351216,
      "name": "ip6_rcv_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589575424,
      "name": "ip6_rcv_core",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:123",
      "file": "net/ipv6/ip6_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ipv6_list_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589575424,
      "name": "ip6_rcv_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * ip6_rcv_core(struct sk_buff * skb, struct net_device * dev, struct net * net)
```

```json
{
  "name": "ip6_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590580096,
      "name": "ip6_rcv_core",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:145",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ipv6_list_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590580096,
      "name": "ip6_rcv_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1210
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
struct sk_buff * ip6_rcv_core(struct sk_buff * skb, struct net_device * dev, struct net * net)
```

```json
{
  "name": "ip6_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590640560,
      "name": "ip6_rcv_core",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:145",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ipv6_list_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590640560,
      "name": "ip6_rcv_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * ip6_rcv_core(struct sk_buff * skb, struct net_device * dev, struct net * net)
```

```json
{
  "name": "ip6_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590566368,
      "name": "ip6_rcv_core",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:145",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ipv6_list_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590566368,
      "name": "ip6_rcv_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1185
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
struct sk_buff * ip6_rcv_core(struct sk_buff * skb, struct net_device * dev, struct net * net)
```

```json
{
  "name": "ip6_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591377968,
      "name": "ip6_rcv_core",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:145",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ipv6_list_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591377968,
      "name": "ip6_rcv_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1339
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
struct sk_buff * ip6_rcv_core(struct sk_buff * skb, struct net_device * dev, struct net * net)
```

```json
{
  "name": "ip6_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593052496,
      "name": "ip6_rcv_core",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:148",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ipv6_list_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593052496,
      "name": "ip6_rcv_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1470
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
struct sk_buff * ip6_rcv_core(struct sk_buff * skb, struct net_device * dev, struct net * net)
```

```json
{
  "name": "ip6_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594945376,
      "name": "ip6_rcv_core",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:148",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ipv6_list_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594945376,
      "name": "ip6_rcv_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1470
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
struct sk_buff * ip6_rcv_core(struct sk_buff * skb, struct net_device * dev, struct net * net)
```

```json
{
  "name": "ip6_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595338000,
      "name": "ip6_rcv_core",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:148",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ipv6_list_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595338000,
      "name": "ip6_rcv_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1495
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
struct sk_buff * ip6_rcv_core(struct sk_buff * skb, struct net_device * dev, struct net * net)
```

```json
{
  "name": "ip6_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596178752,
      "name": "ip6_rcv_core",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:149",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ipv6_list_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596178752,
      "name": "ip6_rcv_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1465
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503251080,
      "name": "ip6_rcv_core",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:123",
      "file": "net/ipv6/ip6_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ipv6_list_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503251080,
      "name": "ip6_rcv_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sk_buff * ip6_rcv_core(struct sk_buff * skb, struct net_device * dev, struct net * net)
```

```json
{
  "name": "ip6_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235922368,
      "name": "ip6_rcv_core",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:123",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ipv6_list_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235922368,
      "name": "ip6_rcv_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sk_buff * ip6_rcv_core(struct sk_buff * skb, struct net_device * dev, struct net * net)
```

```json
{
  "name": "ip6_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296994080,
      "name": "ip6_rcv_core",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:123",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ipv6_list_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296994080,
      "name": "ip6_rcv_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1540
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct sk_buff * ip6_rcv_core(struct sk_buff * skb, struct net_device * dev, struct net * net)
```

```json
{
  "name": "ip6_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279278650,
      "name": "ip6_rcv_core",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:123",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ipv6_list_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279278650,
      "name": "ip6_rcv_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1174
    }
  ]
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
  "name": "ip6_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589179792,
      "name": "ip6_rcv_core",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:123",
      "file": "net/ipv6/ip6_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ipv6_list_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589179792,
      "name": "ip6_rcv_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588904784,
      "name": "ip6_rcv_core",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:123",
      "file": "net/ipv6/ip6_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ipv6_list_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588904784,
      "name": "ip6_rcv_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589616656,
      "name": "ip6_rcv_core",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:123",
      "file": "net/ipv6/ip6_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ipv6_list_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589616656,
      "name": "ip6_rcv_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589664992,
      "name": "ip6_rcv_core",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:123",
      "file": "net/ipv6/ip6_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ipv6_list_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589664992,
      "name": "ip6_rcv_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1183
    }
  ]
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
struct sk_buff * ip6_rcv_core(struct sk_buff * skb, struct net_device * dev, struct net * net)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct sk_buff * ip6_rcv_core(struct sk_buff * skb, struct net_device * dev, struct net * net)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct sk_buff * ip6_rcv_core(struct sk_buff * skb, struct net_device * dev, struct net * net)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct sk_buff * ip6_rcv_core(struct sk_buff * skb, struct net_device * dev, struct net * net)
```
</details>
</li>
</ul>
