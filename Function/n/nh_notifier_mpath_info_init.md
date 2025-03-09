# Function: <code>nh_notifier_mpath_info_init</code>

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
int nh_notifier_mpath_info_init(struct nh_notifier_info * info, struct nh_group * nhg)
```

```json
{
  "name": "nh_notifier_mpath_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590337552,
      "name": "nh_notifier_mpath_info_init",
      "external": false,
      "loc": "net/ipv4/nexthop.c:119",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:register_nexthop_notifier",
        "net/ipv4/nexthop.c:replace_nexthop_grp",
        "net/ipv4/nexthop.c:call_nexthop_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590337552,
      "name": "nh_notifier_mpath_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int nh_notifier_mpath_info_init(struct nh_notifier_info * info, struct nh_group * nhg)
```

```json
{
  "name": "nh_notifier_mpath_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nh_notifier_mpath_info_init",
      "external": false,
      "loc": "net/ipv4/nexthop.c:119",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop_grp",
        "net/ipv4/nexthop.c:nh_notifier_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591131952,
      "name": "nh_notifier_mpath_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
    },
    {
      "addr": 18446744071592731410,
      "name": "nh_notifier_mpath_info_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int nh_notifier_mpath_info_init(struct nh_notifier_info * info, struct nh_group * nhg)
```

```json
{
  "name": "nh_notifier_mpath_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nh_notifier_mpath_info_init",
      "external": false,
      "loc": "net/ipv4/nexthop.c:120",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop_grp",
        "net/ipv4/nexthop.c:nh_notifier_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592786128,
      "name": "nh_notifier_mpath_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    },
    {
      "addr": 18446744071594617840,
      "name": "nh_notifier_mpath_info_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int nh_notifier_mpath_info_init(struct nh_notifier_info * info, struct nh_group * nhg)
```

```json
{
  "name": "nh_notifier_mpath_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nh_notifier_mpath_info_init",
      "external": false,
      "loc": "net/ipv4/nexthop.c:120",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop_grp",
        "net/ipv4/nexthop.c:nh_notifier_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594661152,
      "name": "nh_notifier_mpath_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    },
    {
      "addr": 18446744071596352693,
      "name": "nh_notifier_mpath_info_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int nh_notifier_mpath_info_init(struct nh_notifier_info * info, struct nh_group * nhg)
```

```json
{
  "name": "nh_notifier_mpath_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nh_notifier_mpath_info_init",
      "external": false,
      "loc": "net/ipv4/nexthop.c:120",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop_grp",
        "net/ipv4/nexthop.c:nh_notifier_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595053488,
      "name": "nh_notifier_mpath_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    },
    {
      "addr": 18446744071596881517,
      "name": "nh_notifier_mpath_info_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int nh_notifier_mpath_info_init(struct nh_notifier_info * info, struct nh_group * nhg)
```

```json
{
  "name": "nh_notifier_mpath_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nh_notifier_mpath_info_init",
      "external": false,
      "loc": "net/ipv4/nexthop.c:120",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop_grp",
        "net/ipv4/nexthop.c:nh_notifier_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595865296,
      "name": "nh_notifier_mpath_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    },
    {
      "addr": 18446744071597805629,
      "name": "nh_notifier_mpath_info_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int nh_notifier_mpath_info_init(struct nh_notifier_info * info, struct nh_group * nhg)
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
