# Function: <code>ipv6_mc_rejoin_groups</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipv6_mc_rejoin_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587962680,
      "name": "ipv6_mc_rejoin_groups",
      "external": false,
      "loc": "net/ipv6/mcast.c:2600",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipv6_mc_rejoin_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588496024,
      "name": "ipv6_mc_rejoin_groups",
      "external": false,
      "loc": "net/ipv6/mcast.c:2602",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipv6_mc_rejoin_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588859544,
      "name": "ipv6_mc_rejoin_groups",
      "external": false,
      "loc": "net/ipv6/mcast.c:2628",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event"
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
  "name": "ipv6_mc_rejoin_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589082888,
      "name": "ipv6_mc_rejoin_groups",
      "external": false,
      "loc": "net/ipv6/mcast.c:2628",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event"
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
  "name": "ipv6_mc_rejoin_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589537114,
      "name": "ipv6_mc_rejoin_groups",
      "external": false,
      "loc": "net/ipv6/mcast.c:2627",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event"
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
  "name": "ipv6_mc_rejoin_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589761194,
      "name": "ipv6_mc_rejoin_groups",
      "external": false,
      "loc": "net/ipv6/mcast.c:2627",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event"
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
void ipv6_mc_rejoin_groups(struct inet6_dev * idev)
```

```json
{
  "name": "ipv6_mc_rejoin_groups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590782384,
      "name": "ipv6_mc_rejoin_groups",
      "external": false,
      "loc": "net/ipv6/mcast.c:2625",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590782384,
      "name": "ipv6_mc_rejoin_groups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
void ipv6_mc_rejoin_groups(struct inet6_dev * idev)
```

```json
{
  "name": "ipv6_mc_rejoin_groups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590843168,
      "name": "ipv6_mc_rejoin_groups",
      "external": false,
      "loc": "net/ipv6/mcast.c:2625",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590843168,
      "name": "ipv6_mc_rejoin_groups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
  "name": "ipv6_mc_rejoin_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590769340,
      "name": "ipv6_mc_rejoin_groups",
      "external": false,
      "loc": "net/ipv6/mcast.c:2814",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event"
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
  "name": "ipv6_mc_rejoin_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591586412,
      "name": "ipv6_mc_rejoin_groups",
      "external": false,
      "loc": "net/ipv6/mcast.c:2813",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event"
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
  "name": "ipv6_mc_rejoin_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593276898,
      "name": "ipv6_mc_rejoin_groups",
      "external": false,
      "loc": "net/ipv6/mcast.c:2815",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event"
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
  "name": "ipv6_mc_rejoin_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595181938,
      "name": "ipv6_mc_rejoin_groups",
      "external": false,
      "loc": "net/ipv6/mcast.c:2815",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event"
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
  "name": "ipv6_mc_rejoin_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595577586,
      "name": "ipv6_mc_rejoin_groups",
      "external": false,
      "loc": "net/ipv6/mcast.c:2815",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event"
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
  "name": "ipv6_mc_rejoin_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596420290,
      "name": "ipv6_mc_rejoin_groups",
      "external": false,
      "loc": "net/ipv6/mcast.c:2816",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event"
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
  "name": "ipv6_mc_rejoin_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503462428,
      "name": "ipv6_mc_rejoin_groups",
      "external": false,
      "loc": "net/ipv6/mcast.c:2627",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event"
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
  "name": "ipv6_mc_rejoin_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236118604,
      "name": "ipv6_mc_rejoin_groups",
      "external": false,
      "loc": "net/ipv6/mcast.c:2627",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event"
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
  "name": "ipv6_mc_rejoin_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297246792,
      "name": "ipv6_mc_rejoin_groups",
      "external": false,
      "loc": "net/ipv6/mcast.c:2627",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event"
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
  "name": "ipv6_mc_rejoin_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279446018,
      "name": "ipv6_mc_rejoin_groups",
      "external": false,
      "loc": "net/ipv6/mcast.c:2627",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event"
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
  "name": "ipv6_mc_rejoin_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589365562,
      "name": "ipv6_mc_rejoin_groups",
      "external": false,
      "loc": "net/ipv6/mcast.c:2627",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event"
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
  "name": "ipv6_mc_rejoin_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589090554,
      "name": "ipv6_mc_rejoin_groups",
      "external": false,
      "loc": "net/ipv6/mcast.c:2627",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event"
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
  "name": "ipv6_mc_rejoin_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589802426,
      "name": "ipv6_mc_rejoin_groups",
      "external": false,
      "loc": "net/ipv6/mcast.c:2627",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event"
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
  "name": "ipv6_mc_rejoin_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589853242,
      "name": "ipv6_mc_rejoin_groups",
      "external": false,
      "loc": "net/ipv6/mcast.c:2627",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event"
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
void ipv6_mc_rejoin_groups(struct inet6_dev * idev)
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
void ipv6_mc_rejoin_groups(struct inet6_dev * idev)
```
</details>
</li>
</ul>
