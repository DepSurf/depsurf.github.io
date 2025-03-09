# Function: <code>nh_notifier_info_init</code>

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
  "name": "nh_notifier_info_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590423836,
      "name": "nh_notifier_info_init",
      "external": false,
      "loc": "net/ipv4/nexthop.c:111",
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
  "name": "nh_notifier_info_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590338619,
      "name": "nh_notifier_info_init",
      "external": false,
      "loc": "net/ipv4/nexthop.c:202",
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
int nh_notifier_info_init(struct nh_notifier_info * info, const struct nexthop * nh)
```

```json
{
  "name": "nh_notifier_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nh_notifier_info_init",
      "external": false,
      "loc": "net/ipv4/nexthop.c:202",
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
      "addr": 18446744071591133424,
      "name": "nh_notifier_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
    },
    {
      "addr": 18446744071592731595,
      "name": "nh_notifier_info_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int nh_notifier_info_init(struct nh_notifier_info * info, const struct nexthop * nh)
```

```json
{
  "name": "nh_notifier_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nh_notifier_info_init",
      "external": false,
      "loc": "net/ipv4/nexthop.c:203",
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
      "addr": 18446744071592787712,
      "name": "nh_notifier_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
    },
    {
      "addr": 18446744071594618025,
      "name": "nh_notifier_info_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int nh_notifier_info_init(struct nh_notifier_info * info, const struct nexthop * nh)
```

```json
{
  "name": "nh_notifier_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nh_notifier_info_init",
      "external": false,
      "loc": "net/ipv4/nexthop.c:203",
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
      "addr": 18446744071594661568,
      "name": "nh_notifier_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
    },
    {
      "addr": 18446744071596352818,
      "name": "nh_notifier_info_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int nh_notifier_info_init(struct nh_notifier_info * info, const struct nexthop * nh)
```

```json
{
  "name": "nh_notifier_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nh_notifier_info_init",
      "external": false,
      "loc": "net/ipv4/nexthop.c:203",
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
      "addr": 18446744071595053904,
      "name": "nh_notifier_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
    },
    {
      "addr": 18446744071596881642,
      "name": "nh_notifier_info_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int nh_notifier_info_init(struct nh_notifier_info * info, const struct nexthop * nh)
```

```json
{
  "name": "nh_notifier_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nh_notifier_info_init",
      "external": false,
      "loc": "net/ipv4/nexthop.c:203",
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
      "addr": 18446744071595866864,
      "name": "nh_notifier_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
    },
    {
      "addr": 18446744071597805814,
      "name": "nh_notifier_info_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int nh_notifier_info_init(struct nh_notifier_info * info, const struct nexthop * nh)
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
