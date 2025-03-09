# Function: <code>nh_notifier_info_fini</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nh_notifier_info_fini",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590423978,
      "name": "nh_notifier_info_fini",
      "external": false,
      "loc": "net/ipv4/nexthop.c:123",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nexthops_dump",
        "net/ipv4/nexthop.c:call_nexthop_notifiers"
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
  "name": "nh_notifier_info_fini",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590338699,
      "name": "nh_notifier_info_fini",
      "external": false,
      "loc": "net/ipv4/nexthop.c:213",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:register_nexthop_notifier",
        "net/ipv4/nexthop.c:call_nexthop_notifiers"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void nh_notifier_info_fini(struct nh_notifier_info * info, const struct nexthop * nh)
```

```json
{
  "name": "nh_notifier_info_fini",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nh_notifier_info_fini",
      "external": false,
      "loc": "net/ipv4/nexthop.c:213",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthops_dump",
        "net/ipv4/nexthop.c:call_nexthop_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591120416,
      "name": "nh_notifier_info_fini",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071592730531,
      "name": "nh_notifier_info_fini.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void nh_notifier_info_fini(struct nh_notifier_info * info, const struct nexthop * nh)
```

```json
{
  "name": "nh_notifier_info_fini",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592773935,
      "name": "nh_notifier_info_fini",
      "external": false,
      "loc": "net/ipv4/nexthop.c:214",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthops_dump",
        "net/ipv4/nexthop.c:call_nexthop_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592773824,
      "name": "nh_notifier_info_fini",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071594616959,
      "name": "nh_notifier_info_fini.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void nh_notifier_info_fini(struct nh_notifier_info * info, const struct nexthop * nh)
```

```json
{
  "name": "nh_notifier_info_fini",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594647263,
      "name": "nh_notifier_info_fini",
      "external": false,
      "loc": "net/ipv4/nexthop.c:214",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthops_dump",
        "net/ipv4/nexthop.c:call_nexthop_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594647152,
      "name": "nh_notifier_info_fini",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071596351796,
      "name": "nh_notifier_info_fini.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void nh_notifier_info_fini(struct nh_notifier_info * info, const struct nexthop * nh)
```

```json
{
  "name": "nh_notifier_info_fini",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595039695,
      "name": "nh_notifier_info_fini",
      "external": false,
      "loc": "net/ipv4/nexthop.c:214",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthops_dump",
        "net/ipv4/nexthop.c:call_nexthop_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595039584,
      "name": "nh_notifier_info_fini",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071596880660,
      "name": "nh_notifier_info_fini.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void nh_notifier_info_fini(struct nh_notifier_info * info, const struct nexthop * nh)
```

```json
{
  "name": "nh_notifier_info_fini",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595852511,
      "name": "nh_notifier_info_fini",
      "external": false,
      "loc": "net/ipv4/nexthop.c:214",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthops_dump",
        "net/ipv4/nexthop.c:call_nexthop_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595852400,
      "name": "nh_notifier_info_fini",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071597804839,
      "name": "nh_notifier_info_fini.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void nh_notifier_info_fini(struct nh_notifier_info * info, const struct nexthop * nh)
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
