# Function: <code>__seg6_end_dt_vrf_build</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __seg6_end_dt_vrf_build(struct seg6_local_lwt * slwt, const void * cfg, u16 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__seg6_end_dt_vrf_build",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590964448,
      "name": "__seg6_end_dt_vrf_build",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:465",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_end_dt4_build"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590963152,
      "name": "__seg6_end_dt_vrf_build",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int __seg6_end_dt_vrf_build(struct seg6_local_lwt * slwt, const void * cfg, u16 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__seg6_end_dt_vrf_build",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590893488,
      "name": "__seg6_end_dt_vrf_build",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:494",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:seg6_end_dt4_build"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590893488,
      "name": "__seg6_end_dt_vrf_build",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
int __seg6_end_dt_vrf_build(struct seg6_local_lwt * slwt, const void * cfg, u16 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__seg6_end_dt_vrf_build",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591725344,
      "name": "__seg6_end_dt_vrf_build",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:497",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:seg6_end_dt46_build",
        "net/ipv6/seg6_local.c:seg6_end_dt4_build"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591725344,
      "name": "__seg6_end_dt_vrf_build",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
int __seg6_end_dt_vrf_build(struct seg6_local_lwt * slwt, const void * cfg, u16 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__seg6_end_dt_vrf_build",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593426928,
      "name": "__seg6_end_dt_vrf_build",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:499",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:seg6_end_dt46_build",
        "net/ipv6/seg6_local.c:seg6_end_dt4_build"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593426928,
      "name": "__seg6_end_dt_vrf_build",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
int __seg6_end_dt_vrf_build(struct seg6_local_lwt * slwt, const void * cfg, u16 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__seg6_end_dt_vrf_build",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595339072,
      "name": "__seg6_end_dt_vrf_build",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:624",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:seg6_end_dt46_build",
        "net/ipv6/seg6_local.c:seg6_end_dt4_build"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595339072,
      "name": "__seg6_end_dt_vrf_build",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __seg6_end_dt_vrf_build(struct seg6_local_lwt * slwt, const void * cfg, u16 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__seg6_end_dt_vrf_build",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595742448,
      "name": "__seg6_end_dt_vrf_build",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:951",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_end_dt46_build",
        "net/ipv6/seg6_local.c:seg6_end_dt4_build"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595734144,
      "name": "__seg6_end_dt_vrf_build",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __seg6_end_dt_vrf_build(struct seg6_local_lwt * slwt, const void * cfg, u16 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__seg6_end_dt_vrf_build",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596590288,
      "name": "__seg6_end_dt_vrf_build",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:1011",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_end_dt46_build",
        "net/ipv6/seg6_local.c:seg6_end_dt4_build"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596581952,
      "name": "__seg6_end_dt_vrf_build",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
int __seg6_end_dt_vrf_build(struct seg6_local_lwt * slwt, const void * cfg, u16 family, struct netlink_ext_ack * extack)
```
</details>
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
