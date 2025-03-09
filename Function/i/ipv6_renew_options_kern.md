# Function: <code>ipv6_renew_options_kern</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ipv6_txoptions * ipv6_renew_options_kern(struct sock * sk, struct ipv6_txoptions * opt, int newtype, struct ipv6_opt_hdr * newopt, int newoptlen)
```

```json
{
  "name": "ipv6_renew_options_kern",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587639136,
      "name": "ipv6_renew_options_kern",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:894",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/calipso.c:calipso_req_delattr",
        "net/ipv6/calipso.c:calipso_req_setattr",
        "net/ipv6/calipso.c:calipso_opt_update",
        "net/ipv6/calipso.c:calipso_opt_update",
        "net/ipv6/calipso.c:calipso_opt_update",
        "net/ipv6/calipso.c:calipso_opt_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587639136,
      "name": "ipv6_renew_options_kern",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ipv6_txoptions * ipv6_renew_options_kern(struct sock * sk, struct ipv6_txoptions * opt, int newtype, struct ipv6_opt_hdr * newopt, int newoptlen)
```

```json
{
  "name": "ipv6_renew_options_kern",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587845488,
      "name": "ipv6_renew_options_kern",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1110",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/calipso.c:calipso_req_delattr",
        "net/ipv6/calipso.c:calipso_req_setattr",
        "net/ipv6/calipso.c:calipso_opt_update",
        "net/ipv6/calipso.c:calipso_opt_update",
        "net/ipv6/calipso.c:calipso_opt_update",
        "net/ipv6/calipso.c:calipso_opt_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587845488,
      "name": "ipv6_renew_options_kern",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ipv6_txoptions * ipv6_renew_options_kern(struct sock * sk, struct ipv6_txoptions * opt, int newtype, struct ipv6_opt_hdr * newopt, int newoptlen)
```

```json
{
  "name": "ipv6_renew_options_kern",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588002512,
      "name": "ipv6_renew_options_kern",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1112",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/calipso.c:calipso_req_delattr",
        "net/ipv6/calipso.c:calipso_req_setattr",
        "net/ipv6/calipso.c:calipso_opt_update",
        "net/ipv6/calipso.c:calipso_opt_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588002512,
      "name": "ipv6_renew_options_kern",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ipv6_txoptions * ipv6_renew_options_kern(struct sock * sk, struct ipv6_txoptions * opt, int newtype, struct ipv6_opt_hdr * newopt, int newoptlen)
```

```json
{
  "name": "ipv6_renew_options_kern",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588539280,
      "name": "ipv6_renew_options_kern",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1162",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/calipso.c:calipso_req_delattr",
        "net/ipv6/calipso.c:calipso_req_setattr",
        "net/ipv6/calipso.c:calipso_opt_update",
        "net/ipv6/calipso.c:calipso_opt_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588539280,
      "name": "ipv6_renew_options_kern",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct ipv6_txoptions * ipv6_renew_options_kern(struct sock * sk, struct ipv6_txoptions * opt, int newtype, struct ipv6_opt_hdr * newopt, int newoptlen)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
struct ipv6_txoptions * ipv6_renew_options_kern(struct sock * sk, struct ipv6_txoptions * opt, int newtype, struct ipv6_opt_hdr * newopt, int newoptlen)
```
</details>
</li>
</ul>
