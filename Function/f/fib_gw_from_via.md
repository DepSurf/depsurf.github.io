# Function: <code>fib_gw_from_via</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fib_gw_from_via(struct fib_config * cfg, struct nlattr * nla, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_gw_from_via",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589094256,
      "name": "fib_gw_from_via",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:682",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589094256,
      "name": "fib_gw_from_via",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fib_gw_from_via(struct fib_config * cfg, struct nlattr * nla, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_gw_from_via",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589318432,
      "name": "fib_gw_from_via",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:683",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589318432,
      "name": "fib_gw_from_via",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int fib_gw_from_via(struct fib_config * cfg, struct nlattr * nla, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_gw_from_via",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590295872,
      "name": "fib_gw_from_via",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:675",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590295872,
      "name": "fib_gw_from_via",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int fib_gw_from_via(struct fib_config * cfg, struct nlattr * nla, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_gw_from_via",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590348880,
      "name": "fib_gw_from_via",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:675",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590348880,
      "name": "fib_gw_from_via",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int fib_gw_from_via(struct fib_config * cfg, struct nlattr * nla, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_gw_from_via",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590264688,
      "name": "fib_gw_from_via",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:677",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590264688,
      "name": "fib_gw_from_via",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int fib_gw_from_via(struct fib_config * cfg, struct nlattr * nla, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_gw_from_via",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591049408,
      "name": "fib_gw_from_via",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:677",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591049408,
      "name": "fib_gw_from_via",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int fib_gw_from_via(struct fib_config * cfg, struct nlattr * nla, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_gw_from_via",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592698176,
      "name": "fib_gw_from_via",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:680",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592698176,
      "name": "fib_gw_from_via",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int fib_gw_from_via(struct fib_config * cfg, struct nlattr * nla, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_gw_from_via",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594567520,
      "name": "fib_gw_from_via",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:680",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594567520,
      "name": "fib_gw_from_via",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int fib_gw_from_via(struct fib_config * cfg, struct nlattr * nla, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_gw_from_via",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594959344,
      "name": "fib_gw_from_via",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:683",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594959344,
      "name": "fib_gw_from_via",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int fib_gw_from_via(struct fib_config * cfg, struct nlattr * nla, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_gw_from_via",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595771824,
      "name": "fib_gw_from_via",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:683",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595771824,
      "name": "fib_gw_from_via",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int fib_gw_from_via(struct fib_config * cfg, struct nlattr * nla, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_gw_from_via",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502956080,
      "name": "fib_gw_from_via",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:683",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502956080,
      "name": "fib_gw_from_via",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int fib_gw_from_via(struct fib_config * cfg, struct nlattr * nla, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_gw_from_via",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235645904,
      "name": "fib_gw_from_via",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:683",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235645904,
      "name": "fib_gw_from_via",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int fib_gw_from_via(struct fib_config * cfg, struct nlattr * nla, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_gw_from_via",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296633296,
      "name": "fib_gw_from_via",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:683",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296633296,
      "name": "fib_gw_from_via",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int fib_gw_from_via(struct fib_config * cfg, struct nlattr * nla, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_gw_from_via",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279038702,
      "name": "fib_gw_from_via",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:683",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279038702,
      "name": "fib_gw_from_via",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int fib_gw_from_via(struct fib_config * cfg, struct nlattr * nla, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_gw_from_via",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588924608,
      "name": "fib_gw_from_via",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:683",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588924608,
      "name": "fib_gw_from_via",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int fib_gw_from_via(struct fib_config * cfg, struct nlattr * nla, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_gw_from_via",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588636544,
      "name": "fib_gw_from_via",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:683",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588636544,
      "name": "fib_gw_from_via",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int fib_gw_from_via(struct fib_config * cfg, struct nlattr * nla, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_gw_from_via",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589360992,
      "name": "fib_gw_from_via",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:683",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589360992,
      "name": "fib_gw_from_via",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int fib_gw_from_via(struct fib_config * cfg, struct nlattr * nla, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_gw_from_via",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589403808,
      "name": "fib_gw_from_via",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:683",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589403808,
      "name": "fib_gw_from_via",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int fib_gw_from_via(struct fib_config * cfg, struct nlattr * nla, struct netlink_ext_ack * extack)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
