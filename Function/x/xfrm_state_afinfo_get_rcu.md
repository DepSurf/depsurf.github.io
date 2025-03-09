# Function: <code>xfrm_state_afinfo_get_rcu</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xfrm_state_afinfo * xfrm_state_afinfo_get_rcu(unsigned int family)
```

```json
{
  "name": "xfrm_state_afinfo_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587747066,
      "name": "xfrm_state_afinfo_get_rcu",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:2129",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587748288,
      "name": "xfrm_state_afinfo_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct xfrm_state_afinfo * xfrm_state_afinfo_get_rcu(unsigned int family)
```

```json
{
  "name": "xfrm_state_afinfo_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588275046,
      "name": "xfrm_state_afinfo_get_rcu",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:2158",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588276112,
      "name": "xfrm_state_afinfo_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct xfrm_state_afinfo * xfrm_state_afinfo_get_rcu(unsigned int family)
```

```json
{
  "name": "xfrm_state_afinfo_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588630180,
      "name": "xfrm_state_afinfo_get_rcu",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:2159",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588631136,
      "name": "xfrm_state_afinfo_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct xfrm_state_afinfo * xfrm_state_afinfo_get_rcu(unsigned int family)
```

```json
{
  "name": "xfrm_state_afinfo_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588845767,
      "name": "xfrm_state_afinfo_get_rcu",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:2191",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588847216,
      "name": "xfrm_state_afinfo_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo * xfrm_state_afinfo_get_rcu(unsigned int family)
```

```json
{
  "name": "xfrm_state_afinfo_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589256544,
      "name": "xfrm_state_afinfo_get_rcu",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:2366",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_inner_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589256544,
      "name": "xfrm_state_afinfo_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo * xfrm_state_afinfo_get_rcu(unsigned int family)
```

```json
{
  "name": "xfrm_state_afinfo_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589481600,
      "name": "xfrm_state_afinfo_get_rcu",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:2368",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_inner_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589481600,
      "name": "xfrm_state_afinfo_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct xfrm_state_afinfo * xfrm_state_afinfo_get_rcu(unsigned int family)
```

```json
{
  "name": "xfrm_state_afinfo_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590471856,
      "name": "xfrm_state_afinfo_get_rcu",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:2371",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590471856,
      "name": "xfrm_state_afinfo_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct xfrm_state_afinfo * xfrm_state_afinfo_get_rcu(unsigned int family)
```

```json
{
  "name": "xfrm_state_afinfo_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590529712,
      "name": "xfrm_state_afinfo_get_rcu",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:2480",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590529712,
      "name": "xfrm_state_afinfo_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct xfrm_state_afinfo * xfrm_state_afinfo_get_rcu(unsigned int family)
```

```json
{
  "name": "xfrm_state_afinfo_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590454992,
      "name": "xfrm_state_afinfo_get_rcu",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:2479",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590454992,
      "name": "xfrm_state_afinfo_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct xfrm_state_afinfo * xfrm_state_afinfo_get_rcu(unsigned int family)
```

```json
{
  "name": "xfrm_state_afinfo_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591257552,
      "name": "xfrm_state_afinfo_get_rcu",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:2539",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591257552,
      "name": "xfrm_state_afinfo_get_rcu",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo * xfrm_state_afinfo_get_rcu(unsigned int family)
```

```json
{
  "name": "xfrm_state_afinfo_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592922512,
      "name": "xfrm_state_afinfo_get_rcu",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:2541",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592922512,
      "name": "xfrm_state_afinfo_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct xfrm_state_afinfo * xfrm_state_afinfo_get_rcu(unsigned int family)
```

```json
{
  "name": "xfrm_state_afinfo_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594803600,
      "name": "xfrm_state_afinfo_get_rcu",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:2705",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594803600,
      "name": "xfrm_state_afinfo_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct xfrm_state_afinfo * xfrm_state_afinfo_get_rcu(unsigned int family)
```

```json
{
  "name": "xfrm_state_afinfo_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595195264,
      "name": "xfrm_state_afinfo_get_rcu",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:2702",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595195264,
      "name": "xfrm_state_afinfo_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct xfrm_state_afinfo * xfrm_state_afinfo_get_rcu(unsigned int family)
```

```json
{
  "name": "xfrm_state_afinfo_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596035824,
      "name": "xfrm_state_afinfo_get_rcu",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:2702",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596035824,
      "name": "xfrm_state_afinfo_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct xfrm_state_afinfo * xfrm_state_afinfo_get_rcu(unsigned int family)
```

```json
{
  "name": "xfrm_state_afinfo_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503141136,
      "name": "xfrm_state_afinfo_get_rcu",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:2368",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_inner_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503141136,
      "name": "xfrm_state_afinfo_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct xfrm_state_afinfo * xfrm_state_afinfo_get_rcu(unsigned int family)
```

```json
{
  "name": "xfrm_state_afinfo_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235819920,
      "name": "xfrm_state_afinfo_get_rcu",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:2368",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input",
        "net/xfrm/xfrm_output.c:xfrm_inner_extract_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output_state_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235819920,
      "name": "xfrm_state_afinfo_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct xfrm_state_afinfo * xfrm_state_afinfo_get_rcu(unsigned int family)
```

```json
{
  "name": "xfrm_state_afinfo_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296863440,
      "name": "xfrm_state_afinfo_get_rcu",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:2368",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_inner_extract_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output_state_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296863440,
      "name": "xfrm_state_afinfo_get_rcu",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct xfrm_state_afinfo * xfrm_state_afinfo_get_rcu(unsigned int family)
```

```json
{
  "name": "xfrm_state_afinfo_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279186102,
      "name": "xfrm_state_afinfo_get_rcu",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:2368",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_inner_extract_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output_state_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279186102,
      "name": "xfrm_state_afinfo_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo * xfrm_state_afinfo_get_rcu(unsigned int family)
```

```json
{
  "name": "xfrm_state_afinfo_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589085968,
      "name": "xfrm_state_afinfo_get_rcu",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:2368",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_inner_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589085968,
      "name": "xfrm_state_afinfo_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo * xfrm_state_afinfo_get_rcu(unsigned int family)
```

```json
{
  "name": "xfrm_state_afinfo_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588811008,
      "name": "xfrm_state_afinfo_get_rcu",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:2368",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_inner_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588811008,
      "name": "xfrm_state_afinfo_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo * xfrm_state_afinfo_get_rcu(unsigned int family)
```

```json
{
  "name": "xfrm_state_afinfo_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589522832,
      "name": "xfrm_state_afinfo_get_rcu",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:2368",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_inner_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589522832,
      "name": "xfrm_state_afinfo_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct xfrm_state_afinfo * xfrm_state_afinfo_get_rcu(unsigned int family)
```

```json
{
  "name": "xfrm_state_afinfo_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589569104,
      "name": "xfrm_state_afinfo_get_rcu",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:2368",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_output.c:__xfrm4_output",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_inner_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589569104,
      "name": "xfrm_state_afinfo_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct xfrm_state_afinfo * xfrm_state_afinfo_get_rcu(unsigned int family)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
