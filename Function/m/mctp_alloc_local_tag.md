# Function: <code>mctp_alloc_local_tag</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct mctp_sk_key * mctp_alloc_local_tag(struct mctp_sock * msk, mctp_eid_t daddr, mctp_eid_t saddr, bool manual, u8 * tagp)
```

```json
{
  "name": "mctp_alloc_local_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mctp_alloc_local_tag",
      "external": true,
      "loc": "net/mctp/route.c:594",
      "file": "net/mctp/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mctp/af_mctp.c:mctp_ioctl",
        "net/mctp/route.c:mctp_local_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594642953,
      "name": "mctp_alloc_local_tag.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071593764528,
      "name": "mctp_alloc_local_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 715
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
struct mctp_sk_key * mctp_alloc_local_tag(struct mctp_sock * msk, mctp_eid_t daddr, mctp_eid_t saddr, bool manual, u8 * tagp)
```

```json
{
  "name": "mctp_alloc_local_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mctp_alloc_local_tag",
      "external": true,
      "loc": "net/mctp/route.c:602",
      "file": "net/mctp/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mctp/af_mctp.c:mctp_ioctl",
        "net/mctp/route.c:mctp_local_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596372153,
      "name": "mctp_alloc_local_tag.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071595703392,
      "name": "mctp_alloc_local_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 709
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
struct mctp_sk_key * mctp_alloc_local_tag(struct mctp_sock * msk, mctp_eid_t daddr, mctp_eid_t saddr, bool manual, u8 * tagp)
```

```json
{
  "name": "mctp_alloc_local_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mctp_alloc_local_tag",
      "external": true,
      "loc": "net/mctp/route.c:602",
      "file": "net/mctp/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mctp/af_mctp.c:mctp_ioctl",
        "net/mctp/route.c:mctp_local_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596901480,
      "name": "mctp_alloc_local_tag.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071596215008,
      "name": "mctp_alloc_local_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
struct mctp_sk_key * mctp_alloc_local_tag(struct mctp_sock * msk, mctp_eid_t daddr, mctp_eid_t saddr, bool manual, u8 * tagp)
```

```json
{
  "name": "mctp_alloc_local_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mctp_alloc_local_tag",
      "external": true,
      "loc": "net/mctp/route.c:602",
      "file": "net/mctp/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mctp/af_mctp.c:mctp_ioctl",
        "net/mctp/route.c:mctp_local_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597826821,
      "name": "mctp_alloc_local_tag.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071597092896,
      "name": "mctp_alloc_local_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
struct mctp_sk_key * mctp_alloc_local_tag(struct mctp_sock * msk, mctp_eid_t daddr, mctp_eid_t saddr, bool manual, u8 * tagp)
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
