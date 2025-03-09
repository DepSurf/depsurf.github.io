# Function: <code>nh_res_table_upkeep</code>

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
void nh_res_table_upkeep(struct nh_res_table * res_table, bool notify, bool notify_nl)
```

```json
{
  "name": "nh_res_table_upkeep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590345104,
      "name": "nh_res_table_upkeep",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1555",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop_grp_res",
        "net/ipv4/nexthop.c:nh_res_table_upkeep_dw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590345104,
      "name": "nh_res_table_upkeep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
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
void nh_res_table_upkeep(struct nh_res_table * res_table, bool notify, bool notify_nl)
```

```json
{
  "name": "nh_res_table_upkeep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nh_res_table_upkeep",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1555",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop_grp_res",
        "net/ipv4/nexthop.c:nh_res_table_upkeep_dw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591130432,
      "name": "nh_res_table_upkeep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1114
    },
    {
      "addr": 18446744071592731200,
      "name": "nh_res_table_upkeep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
void nh_res_table_upkeep(struct nh_res_table * res_table, bool notify, bool notify_nl)
```

```json
{
  "name": "nh_res_table_upkeep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nh_res_table_upkeep",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1556",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop_grp_res",
        "net/ipv4/nexthop.c:nh_res_table_upkeep_dw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592784496,
      "name": "nh_res_table_upkeep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1169
    },
    {
      "addr": 18446744071594617630,
      "name": "nh_res_table_upkeep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
void nh_res_table_upkeep(struct nh_res_table * res_table, bool notify, bool notify_nl)
```

```json
{
  "name": "nh_res_table_upkeep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nh_res_table_upkeep",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1556",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop_grp_res",
        "net/ipv4/nexthop.c:nh_res_table_upkeep_dw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594658992,
      "name": "nh_res_table_upkeep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
    },
    {
      "addr": 18446744071596352515,
      "name": "nh_res_table_upkeep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void nh_res_table_upkeep(struct nh_res_table * res_table, bool notify, bool notify_nl)
```

```json
{
  "name": "nh_res_table_upkeep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nh_res_table_upkeep",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1556",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop_grp_res",
        "net/ipv4/nexthop.c:nh_res_table_upkeep_dw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595051392,
      "name": "nh_res_table_upkeep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
    },
    {
      "addr": 18446744071596881331,
      "name": "nh_res_table_upkeep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void nh_res_table_upkeep(struct nh_res_table * res_table, bool notify, bool notify_nl)
```

```json
{
  "name": "nh_res_table_upkeep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nh_res_table_upkeep",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1579",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop_grp_res",
        "net/ipv4/nexthop.c:nh_res_table_upkeep_dw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595864352,
      "name": "nh_res_table_upkeep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
    },
    {
      "addr": 18446744071597805503,
      "name": "nh_res_table_upkeep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void nh_res_table_upkeep(struct nh_res_table * res_table, bool notify, bool notify_nl)
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
