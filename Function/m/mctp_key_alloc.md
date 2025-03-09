# Function: <code>mctp_key_alloc</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mctp_sk_key * mctp_key_alloc(struct mctp_sock * msk, mctp_eid_t local, mctp_eid_t peer, u8 tag, gfp_t gfp)
```

```json
{
  "name": "mctp_key_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593757856,
      "name": "mctp_key_alloc",
      "external": false,
      "loc": "net/mctp/route.c:133",
      "file": "net/mctp/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mctp/route.c:mctp_alloc_local_tag",
        "net/mctp/route.c:mctp_route_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593757856,
      "name": "mctp_key_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
struct mctp_sk_key * mctp_key_alloc(struct mctp_sock * msk, mctp_eid_t local, mctp_eid_t peer, u8 tag, gfp_t gfp)
```

```json
{
  "name": "mctp_key_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595700336,
      "name": "mctp_key_alloc",
      "external": false,
      "loc": "net/mctp/route.c:133",
      "file": "net/mctp/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mctp/route.c:mctp_alloc_local_tag",
        "net/mctp/route.c:mctp_route_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595700336,
      "name": "mctp_key_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
struct mctp_sk_key * mctp_key_alloc(struct mctp_sock * msk, mctp_eid_t local, mctp_eid_t peer, u8 tag, gfp_t gfp)
```

```json
{
  "name": "mctp_key_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596211856,
      "name": "mctp_key_alloc",
      "external": false,
      "loc": "net/mctp/route.c:133",
      "file": "net/mctp/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mctp/route.c:mctp_alloc_local_tag",
        "net/mctp/route.c:mctp_route_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596211856,
      "name": "mctp_key_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
struct mctp_sk_key * mctp_key_alloc(struct mctp_sock * msk, mctp_eid_t local, mctp_eid_t peer, u8 tag, gfp_t gfp)
```

```json
{
  "name": "mctp_key_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597089696,
      "name": "mctp_key_alloc",
      "external": false,
      "loc": "net/mctp/route.c:133",
      "file": "net/mctp/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mctp/route.c:mctp_alloc_local_tag",
        "net/mctp/route.c:mctp_route_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597089696,
      "name": "mctp_key_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct mctp_sk_key * mctp_key_alloc(struct mctp_sock * msk, mctp_eid_t local, mctp_eid_t peer, u8 tag, gfp_t gfp)
```
</details>
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
