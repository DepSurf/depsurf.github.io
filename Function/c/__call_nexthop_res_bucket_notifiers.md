# Function: <code>__call_nexthop_res_bucket_notifiers</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int __call_nexthop_res_bucket_notifiers(struct net * net, u32 nhg_id, u16 bucket_index, bool force, struct nh_info * oldi, struct nh_info * newi, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__call_nexthop_res_bucket_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590340128,
      "name": "__call_nexthop_res_bucket_notifiers",
      "external": false,
      "loc": "net/ipv4/nexthop.c:324",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nh_res_bucket_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590340128,
      "name": "__call_nexthop_res_bucket_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 605
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
int __call_nexthop_res_bucket_notifiers(struct net * net, u32 nhg_id, u16 bucket_index, bool force, struct nh_info * oldi, struct nh_info * newi, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__call_nexthop_res_bucket_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591122624,
      "name": "__call_nexthop_res_bucket_notifiers",
      "external": false,
      "loc": "net/ipv4/nexthop.c:324",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop_single_notify",
        "net/ipv4/nexthop.c:replace_nexthop_single_notify",
        "net/ipv4/nexthop.c:nh_res_table_upkeep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591122624,
      "name": "__call_nexthop_res_bucket_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
int __call_nexthop_res_bucket_notifiers(struct net * net, u32 nhg_id, u16 bucket_index, bool force, struct nh_info * oldi, struct nh_info * newi, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__call_nexthop_res_bucket_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592778288,
      "name": "__call_nexthop_res_bucket_notifiers",
      "external": false,
      "loc": "net/ipv4/nexthop.c:325",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop_single_notify",
        "net/ipv4/nexthop.c:replace_nexthop_single_notify",
        "net/ipv4/nexthop.c:nh_res_table_upkeep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592778288,
      "name": "__call_nexthop_res_bucket_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
int __call_nexthop_res_bucket_notifiers(struct net * net, u32 nhg_id, u16 bucket_index, bool force, struct nh_info * oldi, struct nh_info * newi, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__call_nexthop_res_bucket_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594651776,
      "name": "__call_nexthop_res_bucket_notifiers",
      "external": false,
      "loc": "net/ipv4/nexthop.c:325",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop_single_notify",
        "net/ipv4/nexthop.c:replace_nexthop_single_notify",
        "net/ipv4/nexthop.c:nh_res_bucket_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594651776,
      "name": "__call_nexthop_res_bucket_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
int __call_nexthop_res_bucket_notifiers(struct net * net, u32 nhg_id, u16 bucket_index, bool force, struct nh_info * oldi, struct nh_info * newi, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__call_nexthop_res_bucket_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595044176,
      "name": "__call_nexthop_res_bucket_notifiers",
      "external": false,
      "loc": "net/ipv4/nexthop.c:325",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop_single_notify",
        "net/ipv4/nexthop.c:replace_nexthop_single_notify",
        "net/ipv4/nexthop.c:nh_res_bucket_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595044176,
      "name": "__call_nexthop_res_bucket_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
int __call_nexthop_res_bucket_notifiers(struct net * net, u32 nhg_id, u16 bucket_index, bool force, struct nh_info * oldi, struct nh_info * newi, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__call_nexthop_res_bucket_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595858624,
      "name": "__call_nexthop_res_bucket_notifiers",
      "external": false,
      "loc": "net/ipv4/nexthop.c:325",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop_single_notify",
        "net/ipv4/nexthop.c:replace_nexthop_single_notify",
        "net/ipv4/nexthop.c:nh_res_bucket_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595858624,
      "name": "__call_nexthop_res_bucket_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int __call_nexthop_res_bucket_notifiers(struct net * net, u32 nhg_id, u16 bucket_index, bool force, struct nh_info * oldi, struct nh_info * newi, struct netlink_ext_ack * extack)
```
</details>
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
