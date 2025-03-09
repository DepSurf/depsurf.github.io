# Function: <code>nexthops_dump</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int nexthops_dump(struct net * net, struct notifier_block * nb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nexthops_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590423728,
      "name": "nexthops_dump",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2148",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:register_nexthop_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590423728,
      "name": "nexthops_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
  "name": "nexthops_dump",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590338548,
      "name": "nexthops_dump",
      "external": false,
      "loc": "net/ipv4/nexthop.c:3565",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:register_nexthop_notifier"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int nexthops_dump(struct net * net, struct notifier_block * nb, enum nexthop_event_type event_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nexthops_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591133936,
      "name": "nexthops_dump",
      "external": false,
      "loc": "net/ipv4/nexthop.c:3594",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:unregister_nexthop_notifier",
        "net/ipv4/nexthop.c:register_nexthop_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591133936,
      "name": "nexthops_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
int nexthops_dump(struct net * net, struct notifier_block * nb, enum nexthop_event_type event_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nexthops_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592788272,
      "name": "nexthops_dump",
      "external": false,
      "loc": "net/ipv4/nexthop.c:3594",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:unregister_nexthop_notifier",
        "net/ipv4/nexthop.c:register_nexthop_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592788272,
      "name": "nexthops_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int nexthops_dump(struct net * net, struct notifier_block * nb, enum nexthop_event_type event_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nexthops_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594662144,
      "name": "nexthops_dump",
      "external": false,
      "loc": "net/ipv4/nexthop.c:3594",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:unregister_nexthop_notifier",
        "net/ipv4/nexthop.c:register_nexthop_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594662144,
      "name": "nexthops_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int nexthops_dump(struct net * net, struct notifier_block * nb, enum nexthop_event_type event_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nexthops_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595054480,
      "name": "nexthops_dump",
      "external": false,
      "loc": "net/ipv4/nexthop.c:3580",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:unregister_nexthop_notifier",
        "net/ipv4/nexthop.c:register_nexthop_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595054480,
      "name": "nexthops_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int nexthops_dump(struct net * net, struct notifier_block * nb, enum nexthop_event_type event_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nexthops_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595867488,
      "name": "nexthops_dump",
      "external": false,
      "loc": "net/ipv4/nexthop.c:3597",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:unregister_nexthop_notifier",
        "net/ipv4/nexthop.c:register_nexthop_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595867488,
      "name": "nexthops_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int nexthops_dump(struct net * net, struct notifier_block * nb, struct netlink_ext_ack * extack)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int nexthops_dump(struct net * net, struct notifier_block * nb, struct netlink_ext_ack * extack)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int nexthops_dump(struct net * net, struct notifier_block * nb, enum nexthop_event_type event_type, struct netlink_ext_ack * extack)
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
