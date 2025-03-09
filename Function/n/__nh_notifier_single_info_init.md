# Function: <code>__nh_notifier_single_info_init</code>

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
  "name": "__nh_notifier_single_info_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590416912,
      "name": "__nh_notifier_single_info_init",
      "external": false,
      "loc": "net/ipv4/nexthop.c:45",
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
      "addr": 18446744071590416912,
      "name": "__nh_notifier_single_info_init.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
  "name": "__nh_notifier_single_info_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590338875,
      "name": "__nh_notifier_single_info_init",
      "external": false,
      "loc": "net/ipv4/nexthop.c:84",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:register_nexthop_notifier",
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers",
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers",
        "net/ipv4/nexthop.c:call_nexthop_notifiers",
        "net/ipv4/nexthop.c:nh_notifier_res_table_info_init",
        "net/ipv4/nexthop.c:nh_notifier_mpath_info_init"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __nh_notifier_single_info_init(struct nh_notifier_single_info * nh_info, const struct nh_info * nhi)
```

```json
{
  "name": "__nh_notifier_single_info_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591133778,
      "name": "__nh_notifier_single_info_init",
      "external": false,
      "loc": "net/ipv4/nexthop.c:84",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nh_notifier_info_init",
        "net/ipv4/nexthop.c:nh_notifier_mpath_info_init"
      ],
      "caller_func": [
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers",
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers",
        "net/ipv4/nexthop.c:nh_notifier_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591117488,
      "name": "__nh_notifier_single_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071592729646,
      "name": "__nh_notifier_single_info_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void __nh_notifier_single_info_init(struct nh_notifier_single_info * nh_info, const struct nh_info * nhi)
```

```json
{
  "name": "__nh_notifier_single_info_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592788072,
      "name": "__nh_notifier_single_info_init",
      "external": false,
      "loc": "net/ipv4/nexthop.c:85",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nh_notifier_info_init",
        "net/ipv4/nexthop.c:nh_notifier_mpath_info_init"
      ],
      "caller_func": [
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers",
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers",
        "net/ipv4/nexthop.c:nh_notifier_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592770576,
      "name": "__nh_notifier_single_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071594616041,
      "name": "__nh_notifier_single_info_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void __nh_notifier_single_info_init(struct nh_notifier_single_info * nh_info, const struct nh_info * nhi)
```

```json
{
  "name": "__nh_notifier_single_info_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594661928,
      "name": "__nh_notifier_single_info_init",
      "external": false,
      "loc": "net/ipv4/nexthop.c:85",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nh_notifier_info_init",
        "net/ipv4/nexthop.c:nh_notifier_mpath_info_init"
      ],
      "caller_func": [
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers",
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers",
        "net/ipv4/nexthop.c:nh_notifier_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594643744,
      "name": "__nh_notifier_single_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071596350878,
      "name": "__nh_notifier_single_info_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void __nh_notifier_single_info_init(struct nh_notifier_single_info * nh_info, const struct nh_info * nhi)
```

```json
{
  "name": "__nh_notifier_single_info_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595054264,
      "name": "__nh_notifier_single_info_init",
      "external": false,
      "loc": "net/ipv4/nexthop.c:85",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nh_notifier_info_init",
        "net/ipv4/nexthop.c:nh_notifier_mpath_info_init"
      ],
      "caller_func": [
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers",
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers",
        "net/ipv4/nexthop.c:nh_notifier_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595036176,
      "name": "__nh_notifier_single_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071596879787,
      "name": "__nh_notifier_single_info_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void __nh_notifier_single_info_init(struct nh_notifier_single_info * nh_info, const struct nh_info * nhi)
```

```json
{
  "name": "__nh_notifier_single_info_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595867228,
      "name": "__nh_notifier_single_info_init",
      "external": false,
      "loc": "net/ipv4/nexthop.c:85",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nh_notifier_info_init",
        "net/ipv4/nexthop.c:nh_notifier_mpath_info_init"
      ],
      "caller_func": [
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers",
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers",
        "net/ipv4/nexthop.c:nh_notifier_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595849072,
      "name": "__nh_notifier_single_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071597803866,
      "name": "__nh_notifier_single_info_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void __nh_notifier_single_info_init(struct nh_notifier_single_info * nh_info, const struct nh_info * nhi)
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
