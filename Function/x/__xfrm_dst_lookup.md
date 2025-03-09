# Function: <code>__xfrm_dst_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586916543,
      "name": "__xfrm_dst_lookup",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:118",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
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
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587363263,
      "name": "__xfrm_dst_lookup",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:118",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
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
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587566111,
      "name": "__xfrm_dst_lookup",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:124",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dst_entry * __xfrm_dst_lookup(struct net * net, int tos, int oif, const xfrm_address_t * saddr, const xfrm_address_t * daddr, int family)
```

```json
{
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587716714,
      "name": "__xfrm_dst_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:119",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587705616,
      "name": "__xfrm_dst_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dst_entry * __xfrm_dst_lookup(struct net * net, int tos, int oif, const xfrm_address_t * saddr, const xfrm_address_t * daddr, int family, u32 mark)
```

```json
{
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588245357,
      "name": "__xfrm_dst_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:122",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588232480,
      "name": "__xfrm_dst_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dst_entry * __xfrm_dst_lookup(struct net * net, int tos, int oif, const xfrm_address_t * saddr, const xfrm_address_t * daddr, int family, u32 mark)
```

```json
{
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588597698,
      "name": "__xfrm_dst_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:122",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588585760,
      "name": "__xfrm_dst_lookup",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dst_entry * __xfrm_dst_lookup(struct net * net, int tos, int oif, const xfrm_address_t * saddr, const xfrm_address_t * daddr, int family, u32 mark)
```

```json
{
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588800684,
      "name": "__xfrm_dst_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:245",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588789776,
      "name": "__xfrm_dst_lookup",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dst_entry * __xfrm_dst_lookup(struct net * net, int tos, int oif, const xfrm_address_t * saddr, const xfrm_address_t * daddr, int family, u32 mark)
```

```json
{
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589230777,
      "name": "__xfrm_dst_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:250",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589222656,
      "name": "__xfrm_dst_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct dst_entry * __xfrm_dst_lookup(struct net * net, int tos, int oif, const xfrm_address_t * saddr, const xfrm_address_t * daddr, int family, u32 mark)
```

```json
{
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589456041,
      "name": "__xfrm_dst_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:250",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589447984,
      "name": "__xfrm_dst_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct dst_entry * __xfrm_dst_lookup(struct net * net, int tos, int oif, const xfrm_address_t * saddr, const xfrm_address_t * daddr, int family, u32 mark)
```

```json
{
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590450192,
      "name": "__xfrm_dst_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:253",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590436000,
      "name": "__xfrm_dst_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct dst_entry * __xfrm_dst_lookup(struct net * net, int tos, int oif, const xfrm_address_t * saddr, const xfrm_address_t * daddr, int family, u32 mark)
```

```json
{
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590501216,
      "name": "__xfrm_dst_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:253",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590501216,
      "name": "__xfrm_dst_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct dst_entry * __xfrm_dst_lookup(struct net * net, int tos, int oif, const xfrm_address_t * saddr, const xfrm_address_t * daddr, int family, u32 mark)
```

```json
{
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590425856,
      "name": "__xfrm_dst_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:252",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590425856,
      "name": "__xfrm_dst_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct dst_entry * __xfrm_dst_lookup(struct net * net, int tos, int oif, const xfrm_address_t * saddr, const xfrm_address_t * daddr, int family, u32 mark)
```

```json
{
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591224272,
      "name": "__xfrm_dst_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:254",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591224272,
      "name": "__xfrm_dst_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dst_entry * __xfrm_dst_lookup(struct net * net, int tos, int oif, const xfrm_address_t * saddr, const xfrm_address_t * daddr, int family, u32 mark)
```

```json
{
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592897577,
      "name": "__xfrm_dst_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:254",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592887184,
      "name": "__xfrm_dst_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dst_entry * __xfrm_dst_lookup(struct net * net, int tos, int oif, const xfrm_address_t * saddr, const xfrm_address_t * daddr, int family, u32 mark)
```

```json
{
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594768761,
      "name": "__xfrm_dst_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:254",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_dst_lookup"
      ],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594766656,
      "name": "__xfrm_dst_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct dst_entry * __xfrm_dst_lookup(struct net * net, int tos, int oif, const xfrm_address_t * saddr, const xfrm_address_t * daddr, int family, u32 mark)
```

```json
{
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595164681,
      "name": "__xfrm_dst_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:254",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_dst_lookup"
      ],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595161904,
      "name": "__xfrm_dst_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
struct dst_entry * __xfrm_dst_lookup(struct net * net, int tos, int oif, const xfrm_address_t * saddr, const xfrm_address_t * daddr, int family, u32 mark)
```

```json
{
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596007785,
      "name": "__xfrm_dst_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:269",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_dst_lookup"
      ],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596005008,
      "name": "__xfrm_dst_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct dst_entry * __xfrm_dst_lookup(struct net * net, int tos, int oif, const xfrm_address_t * saddr, const xfrm_address_t * daddr, int family, u32 mark)
```

```json
{
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503110844,
      "name": "__xfrm_dst_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:250",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503102536,
      "name": "__xfrm_dst_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct dst_entry * __xfrm_dst_lookup(struct net * net, int tos, int oif, const xfrm_address_t * saddr, const xfrm_address_t * daddr, int family, u32 mark)
```

```json
{
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235793724,
      "name": "__xfrm_dst_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:250",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235784708,
      "name": "__xfrm_dst_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct dst_entry * __xfrm_dst_lookup(struct net * net, int tos, int oif, const xfrm_address_t * saddr, const xfrm_address_t * daddr, int family, u32 mark)
```

```json
{
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296842804,
      "name": "__xfrm_dst_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:250",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296816160,
      "name": "__xfrm_dst_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct dst_entry * __xfrm_dst_lookup(struct net * net, int tos, int oif, const xfrm_address_t * saddr, const xfrm_address_t * daddr, int family, u32 mark)
```

```json
{
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279169102,
      "name": "__xfrm_dst_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:250",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279155176,
      "name": "__xfrm_dst_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct dst_entry * __xfrm_dst_lookup(struct net * net, int tos, int oif, const xfrm_address_t * saddr, const xfrm_address_t * daddr, int family, u32 mark)
```

```json
{
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589060409,
      "name": "__xfrm_dst_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:250",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589052352,
      "name": "__xfrm_dst_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct dst_entry * __xfrm_dst_lookup(struct net * net, int tos, int oif, const xfrm_address_t * saddr, const xfrm_address_t * daddr, int family, u32 mark)
```

```json
{
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588785449,
      "name": "__xfrm_dst_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:250",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588777392,
      "name": "__xfrm_dst_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct dst_entry * __xfrm_dst_lookup(struct net * net, int tos, int oif, const xfrm_address_t * saddr, const xfrm_address_t * daddr, int family, u32 mark)
```

```json
{
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589497273,
      "name": "__xfrm_dst_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:250",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589489216,
      "name": "__xfrm_dst_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dst_entry * __xfrm_dst_lookup(struct net * net, int tos, int oif, const xfrm_address_t * saddr, const xfrm_address_t * daddr, int family, u32 mark)
```

```json
{
  "name": "__xfrm_dst_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589536160,
      "name": "__xfrm_dst_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:250",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589536160,
      "name": "__xfrm_dst_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct dst_entry * __xfrm_dst_lookup(struct net * net, int tos, int oif, const xfrm_address_t * saddr, const xfrm_address_t * daddr, int family)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 mark</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
