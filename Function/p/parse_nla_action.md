# Function: <code>parse_nla_action</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_nla_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588606178,
      "name": "parse_nla_action",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:750",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_build_state"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_nla_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588971460,
      "name": "parse_nla_action",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:906",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_build_state"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_nla_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589195540,
      "name": "parse_nla_action",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:918",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_build_state"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_nla_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589649021,
      "name": "parse_nla_action",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:914",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_build_state"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_nla_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589873229,
      "name": "parse_nla_action",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:927",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_build_state"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int parse_nla_action(struct nlattr * * attrs, struct seg6_local_lwt * slwt)
```

```json
{
  "name": "parse_nla_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590899120,
      "name": "parse_nla_action",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:941",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590899120,
      "name": "parse_nla_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
int parse_nla_action(struct nlattr * * attrs, struct seg6_local_lwt * slwt)
```

```json
{
  "name": "parse_nla_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590966816,
      "name": "parse_nla_action",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:1459",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590966816,
      "name": "parse_nla_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
int parse_nla_action(struct nlattr * * attrs, struct seg6_local_lwt * slwt)
```

```json
{
  "name": "parse_nla_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590896160,
      "name": "parse_nla_action",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:1643",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590896160,
      "name": "parse_nla_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
int parse_nla_action(struct nlattr * * attrs, struct seg6_local_lwt * slwt)
```

```json
{
  "name": "parse_nla_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_nla_action",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:1708",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591725616,
      "name": "parse_nla_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 627
    },
    {
      "addr": 18446744071592744484,
      "name": "parse_nla_action.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int parse_nla_action(struct nlattr * * attrs, struct seg6_local_lwt * slwt)
```

```json
{
  "name": "parse_nla_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_nla_action",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:1708",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593427248,
      "name": "parse_nla_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 570
    },
    {
      "addr": 18446744071594631064,
      "name": "parse_nla_action.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int parse_nla_action(struct nlattr * * attrs, struct seg6_local_lwt * slwt, struct netlink_ext_ack * extack)
```

```json
{
  "name": "parse_nla_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_nla_action",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:2036",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595339488,
      "name": "parse_nla_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
    },
    {
      "addr": 18446744071596364608,
      "name": "parse_nla_action.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int parse_nla_action(struct nlattr * * attrs, struct seg6_local_lwt * slwt, struct netlink_ext_ack * extack)
```

```json
{
  "name": "parse_nla_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_nla_action",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:2363",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595734432,
      "name": "parse_nla_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
    },
    {
      "addr": 18446744071596892625,
      "name": "parse_nla_action.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int parse_nla_action(struct nlattr * * attrs, struct seg6_local_lwt * slwt, struct netlink_ext_ack * extack)
```

```json
{
  "name": "parse_nla_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_nla_action",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:2426",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596582240,
      "name": "parse_nla_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
    },
    {
      "addr": 18446744071597817249,
      "name": "parse_nla_action.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "parse_nla_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503592512,
      "name": "parse_nla_action",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:927",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_build_state"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "parse_nla_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236237760,
      "name": "parse_nla_action",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:927",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_build_state"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "parse_nla_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297401320,
      "name": "parse_nla_action",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:927",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_build_state"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "parse_nla_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279546862,
      "name": "parse_nla_action",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:927",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_nla_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589477597,
      "name": "parse_nla_action",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:927",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_build_state"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_nla_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589202589,
      "name": "parse_nla_action",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:927",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_build_state"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_nla_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589914461,
      "name": "parse_nla_action",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:927",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_build_state"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_nla_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589967053,
      "name": "parse_nla_action",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:927",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int parse_nla_action(struct nlattr * * attrs, struct seg6_local_lwt * slwt)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack * extack</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
