# Function: <code>ipv6_addr_cmp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipv6_addr_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587287254,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:366",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipv6_addr_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587755203,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:383",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipv6_addr_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587970419,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:383",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipv6_addr_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588128518,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:384",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipv6_addr_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588676326,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:425",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
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
  "name": "ipv6_addr_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589042899,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:413",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
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
  "name": "ipv6_addr_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589268899,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:433",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ipv6_addr_cmp(const struct in6_addr * a1, const struct in6_addr * a2)
```

```json
{
  "name": "ipv6_addr_cmp",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589103950,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    },
    {
      "addr": 18446744071589724265,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589098352,
      "name": "ipv6_addr_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ipv6_addr_cmp(const struct in6_addr * a1, const struct in6_addr * a2)
```

```json
{
  "name": "ipv6_addr_cmp",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589328149,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    },
    {
      "addr": 18446744071589948569,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589322528,
      "name": "ipv6_addr_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ipv6_addr_cmp(const struct in6_addr * a1, const struct in6_addr * a2)
```

```json
{
  "name": "ipv6_addr_cmp",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590308478,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_find_info"
      ],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    },
    {
      "addr": 18446744071590978665,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591117404,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr",
        "net/mptcp/pm_netlink.c:lookup_subflow_by_saddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590300208,
      "name": "ipv6_addr_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ipv6_addr_cmp(const struct in6_addr * a1, const struct in6_addr * a2)
```

```json
{
  "name": "ipv6_addr_cmp",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590361566,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_find_info"
      ],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    },
    {
      "addr": 18446744071591043289,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591199815,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer",
        "net/mptcp/pm_netlink.c:lookup_subflow_by_saddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590353136,
      "name": "ipv6_addr_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ipv6_addr_cmp(const struct in6_addr * a1, const struct in6_addr * a2)
```

```json
{
  "name": "ipv6_addr_cmp",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590277440,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:492",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_find_info"
      ],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    },
    {
      "addr": 18446744071590973881,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:492",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591133396,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:492",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:addresses_equal"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590268912,
      "name": "ipv6_addr_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ipv6_addr_cmp(const struct in6_addr * a1, const struct in6_addr * a2)
```

```json
{
  "name": "ipv6_addr_cmp",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591063121,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:495",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_find_info"
      ],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    },
    {
      "addr": 18446744071591811417,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:495",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591982932,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:495",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:addresses_equal"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591053600,
      "name": "ipv6_addr_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ipv6_addr_cmp(const struct in6_addr * a1, const struct in6_addr * a2)
```

```json
{
  "name": "ipv6_addr_cmp",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592711957,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:549",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_find_info"
      ],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    },
    {
      "addr": 18446744071593523689,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:549",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593718682,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:549",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_addresses_equal"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592702608,
      "name": "ipv6_addr_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ipv6_addr_cmp(const struct in6_addr * a1, const struct in6_addr * a2)
```

```json
{
  "name": "ipv6_addr_cmp",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594582072,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:582",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_find_info"
      ],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    },
    {
      "addr": 18446744071595444073,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:582",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595653786,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:582",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_addresses_equal"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594572192,
      "name": "ipv6_addr_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ipv6_addr_cmp(const struct in6_addr * a1, const struct in6_addr * a2)
```

```json
{
  "name": "ipv6_addr_cmp",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594973848,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:583",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_find_info"
      ],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    },
    {
      "addr": 18446744071595951033,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:583",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596162586,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:583",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_addresses_equal"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594964000,
      "name": "ipv6_addr_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ipv6_addr_cmp(const struct in6_addr * a1, const struct in6_addr * a2)
```

```json
{
  "name": "ipv6_addr_cmp",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595786344,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:583",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_find_info"
      ],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    },
    {
      "addr": 18446744071595972399,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:583",
      "file": "net/ipv4/tcp_ao.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user",
        "net/ipv4/tcp_ao.c:tcp_ao_verify_ipv6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596812905,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:583",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597036634,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:583",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_addresses_equal"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595776496,
      "name": "ipv6_addr_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ipv6_addr_cmp(const struct in6_addr * a1, const struct in6_addr * a2)
```

```json
{
  "name": "ipv6_addr_cmp",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502966808,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    },
    {
      "addr": 18446603336503681376,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502960248,
      "name": "ipv6_addr_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
int ipv6_addr_cmp(const struct in6_addr * a1, const struct in6_addr * a2)
```

```json
{
  "name": "ipv6_addr_cmp",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235654516,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    },
    {
      "addr": 3236317704,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235650388,
      "name": "ipv6_addr_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
int ipv6_addr_cmp(const struct in6_addr * a1, const struct in6_addr * a2)
```

```json
{
  "name": "ipv6_addr_cmp",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296647456,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    },
    {
      "addr": 13835058055297507840,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296638768,
      "name": "ipv6_addr_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ipv6_addr_cmp",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279051160,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279616644,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ipv6_addr_cmp(const struct in6_addr * a1, const struct in6_addr * a2)
```

```json
{
  "name": "ipv6_addr_cmp",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588934325,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    },
    {
      "addr": 18446744071589552169,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588928704,
      "name": "ipv6_addr_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ipv6_addr_cmp(const struct in6_addr * a1, const struct in6_addr * a2)
```

```json
{
  "name": "ipv6_addr_cmp",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588646261,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    },
    {
      "addr": 18446744071589276745,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588640640,
      "name": "ipv6_addr_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ipv6_addr_cmp(const struct in6_addr * a1, const struct in6_addr * a2)
```

```json
{
  "name": "ipv6_addr_cmp",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589370709,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    },
    {
      "addr": 18446744071589994201,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589365088,
      "name": "ipv6_addr_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ipv6_addr_cmp(const struct in6_addr * a1, const struct in6_addr * a2)
```

```json
{
  "name": "ipv6_addr_cmp",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589413637,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs"
      ],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    },
    {
      "addr": 18446744071590044233,
      "name": "ipv6_addr_cmp",
      "external": false,
      "loc": "include/net/ipv6.h:491",
      "file": "net/netlabel/netlabel_addrlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_addrlist.c:netlbl_af6list_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589407920,
      "name": "ipv6_addr_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
int ipv6_addr_cmp(const struct in6_addr * a1, const struct in6_addr * a2)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int ipv6_addr_cmp(const struct in6_addr * a1, const struct in6_addr * a2)
```
</details>
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
