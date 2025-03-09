# Function: <code>xfrm_policy_addr_delta</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xfrm_policy_addr_delta(const xfrm_address_t * a, const xfrm_address_t * b, u8 prefixlen, u16 family)
```

```json
{
  "name": "xfrm_policy_addr_delta",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588793120,
      "name": "xfrm_policy_addr_delta",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:785",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588793120,
      "name": "xfrm_policy_addr_delta",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xfrm_policy_addr_delta(const xfrm_address_t * a, const xfrm_address_t * b, u8 prefixlen, u16 family)
```

```json
{
  "name": "xfrm_policy_addr_delta",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589224160,
      "name": "xfrm_policy_addr_delta",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:787",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589224160,
      "name": "xfrm_policy_addr_delta",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int xfrm_policy_addr_delta(const xfrm_address_t * a, const xfrm_address_t * b, u8 prefixlen, u16 family)
```

```json
{
  "name": "xfrm_policy_addr_delta",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589449424,
      "name": "xfrm_policy_addr_delta",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:789",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589449424,
      "name": "xfrm_policy_addr_delta",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xfrm_policy_addr_delta(const xfrm_address_t * a, const xfrm_address_t * b, u8 prefixlen, u16 family)
```

```json
{
  "name": "xfrm_policy_addr_delta",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590438320,
      "name": "xfrm_policy_addr_delta",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:792",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_reinsert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590438320,
      "name": "xfrm_policy_addr_delta",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int xfrm_policy_addr_delta(const xfrm_address_t * a, const xfrm_address_t * b, u8 prefixlen, u16 family)
```

```json
{
  "name": "xfrm_policy_addr_delta",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590493872,
      "name": "xfrm_policy_addr_delta",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:792",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_reinsert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590493872,
      "name": "xfrm_policy_addr_delta",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
int xfrm_policy_addr_delta(const xfrm_address_t * a, const xfrm_address_t * b, u8 prefixlen, u16 family)
```

```json
{
  "name": "xfrm_policy_addr_delta",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590419360,
      "name": "xfrm_policy_addr_delta",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:791",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590419360,
      "name": "xfrm_policy_addr_delta",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
int xfrm_policy_addr_delta(const xfrm_address_t * a, const xfrm_address_t * b, u8 prefixlen, u16 family)
```

```json
{
  "name": "xfrm_policy_addr_delta",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xfrm_policy_addr_delta",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:793",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591218032,
      "name": "xfrm_policy_addr_delta",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446744071592733989,
      "name": "xfrm_policy_addr_delta.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int xfrm_policy_addr_delta(const xfrm_address_t * a, const xfrm_address_t * b, u8 prefixlen, u16 family)
```

```json
{
  "name": "xfrm_policy_addr_delta",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xfrm_policy_addr_delta",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:793",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592880384,
      "name": "xfrm_policy_addr_delta",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    },
    {
      "addr": 18446744071594620526,
      "name": "xfrm_policy_addr_delta.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int xfrm_policy_addr_delta(const xfrm_address_t * a, const xfrm_address_t * b, u8 prefixlen, u16 family)
```

```json
{
  "name": "xfrm_policy_addr_delta",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xfrm_policy_addr_delta",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:794",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594759264,
      "name": "xfrm_policy_addr_delta",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    },
    {
      "addr": 18446744071596355244,
      "name": "xfrm_policy_addr_delta.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int xfrm_policy_addr_delta(const xfrm_address_t * a, const xfrm_address_t * b, u8 prefixlen, u16 family)
```

```json
{
  "name": "xfrm_policy_addr_delta",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xfrm_policy_addr_delta",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:794",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595151568,
      "name": "xfrm_policy_addr_delta",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071596884138,
      "name": "xfrm_policy_addr_delta.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int xfrm_policy_addr_delta(const xfrm_address_t * a, const xfrm_address_t * b, u8 prefixlen, u16 family)
```

```json
{
  "name": "xfrm_policy_addr_delta",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xfrm_policy_addr_delta",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:809",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595993696,
      "name": "xfrm_policy_addr_delta",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071597808817,
      "name": "xfrm_policy_addr_delta.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int xfrm_policy_addr_delta(const xfrm_address_t * a, const xfrm_address_t * b, u8 prefixlen, u16 family)
```

```json
{
  "name": "xfrm_policy_addr_delta",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503102312,
      "name": "xfrm_policy_addr_delta",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:789",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503102312,
      "name": "xfrm_policy_addr_delta",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
int xfrm_policy_addr_delta(const xfrm_address_t * a, const xfrm_address_t * b, u8 prefixlen, u16 family)
```

```json
{
  "name": "xfrm_policy_addr_delta",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235786924,
      "name": "xfrm_policy_addr_delta",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:789",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235786924,
      "name": "xfrm_policy_addr_delta",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int xfrm_policy_addr_delta(const xfrm_address_t * a, const xfrm_address_t * b, u8 prefixlen, u16 family)
```

```json
{
  "name": "xfrm_policy_addr_delta",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296819392,
      "name": "xfrm_policy_addr_delta",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:789",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296819392,
      "name": "xfrm_policy_addr_delta",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int xfrm_policy_addr_delta(const xfrm_address_t * a, const xfrm_address_t * b, u8 prefixlen, u16 family)
```

```json
{
  "name": "xfrm_policy_addr_delta",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279154830,
      "name": "xfrm_policy_addr_delta",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:789",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279154830,
      "name": "xfrm_policy_addr_delta",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
int xfrm_policy_addr_delta(const xfrm_address_t * a, const xfrm_address_t * b, u8 prefixlen, u16 family)
```

```json
{
  "name": "xfrm_policy_addr_delta",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589053792,
      "name": "xfrm_policy_addr_delta",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:789",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589053792,
      "name": "xfrm_policy_addr_delta",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int xfrm_policy_addr_delta(const xfrm_address_t * a, const xfrm_address_t * b, u8 prefixlen, u16 family)
```

```json
{
  "name": "xfrm_policy_addr_delta",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588778832,
      "name": "xfrm_policy_addr_delta",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:789",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588778832,
      "name": "xfrm_policy_addr_delta",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int xfrm_policy_addr_delta(const xfrm_address_t * a, const xfrm_address_t * b, u8 prefixlen, u16 family)
```

```json
{
  "name": "xfrm_policy_addr_delta",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589490656,
      "name": "xfrm_policy_addr_delta",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:789",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589490656,
      "name": "xfrm_policy_addr_delta",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int xfrm_policy_addr_delta(const xfrm_address_t * a, const xfrm_address_t * b, u8 prefixlen, u16 family)
```

```json
{
  "name": "xfrm_policy_addr_delta",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589537296,
      "name": "xfrm_policy_addr_delta",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:789",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589537296,
      "name": "xfrm_policy_addr_delta",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int xfrm_policy_addr_delta(const xfrm_address_t * a, const xfrm_address_t * b, u8 prefixlen, u16 family)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
