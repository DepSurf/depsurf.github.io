# Function: <code>xfrm_pol_bin_key</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
u32 xfrm_pol_bin_key(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xfrm_pol_bin_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588790080,
      "name": "xfrm_pol_bin_key",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1440",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_pol_bin_obj",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588790080,
      "name": "xfrm_pol_bin_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
u32 xfrm_pol_bin_key(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xfrm_pol_bin_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589221408,
      "name": "xfrm_pol_bin_key",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1446",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_pol_bin_obj",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589221408,
      "name": "xfrm_pol_bin_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
u32 xfrm_pol_bin_key(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xfrm_pol_bin_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589446736,
      "name": "xfrm_pol_bin_key",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1448",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_pol_bin_obj",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589446736,
      "name": "xfrm_pol_bin_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
u32 xfrm_pol_bin_key(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xfrm_pol_bin_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590442624,
      "name": "xfrm_pol_bin_key",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1442",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590442624,
      "name": "xfrm_pol_bin_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 xfrm_pol_bin_key(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xfrm_pol_bin_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590500720,
      "name": "xfrm_pol_bin_key",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1452",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590500720,
      "name": "xfrm_pol_bin_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 xfrm_pol_bin_key(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xfrm_pol_bin_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590425024,
      "name": "xfrm_pol_bin_key",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1451",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590425024,
      "name": "xfrm_pol_bin_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 xfrm_pol_bin_key(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xfrm_pol_bin_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591223440,
      "name": "xfrm_pol_bin_key",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1453",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591223440,
      "name": "xfrm_pol_bin_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
u32 xfrm_pol_bin_key(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xfrm_pol_bin_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592886624,
      "name": "xfrm_pol_bin_key",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1453",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592886624,
      "name": "xfrm_pol_bin_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
u32 xfrm_pol_bin_key(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xfrm_pol_bin_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594766048,
      "name": "xfrm_pol_bin_key",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1454",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594766048,
      "name": "xfrm_pol_bin_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
u32 xfrm_pol_bin_key(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xfrm_pol_bin_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595160608,
      "name": "xfrm_pol_bin_key",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1454",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595160608,
      "name": "xfrm_pol_bin_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
u32 xfrm_pol_bin_key(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xfrm_pol_bin_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596003344,
      "name": "xfrm_pol_bin_key",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1470",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596003344,
      "name": "xfrm_pol_bin_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
u32 xfrm_pol_bin_key(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xfrm_pol_bin_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503109176,
      "name": "xfrm_pol_bin_key",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1448",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_pol_bin_obj",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503109176,
      "name": "xfrm_pol_bin_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
u32 xfrm_pol_bin_key(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xfrm_pol_bin_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235783256,
      "name": "xfrm_pol_bin_key",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1448",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235783256,
      "name": "xfrm_pol_bin_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
u32 xfrm_pol_bin_key(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xfrm_pol_bin_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296814576,
      "name": "xfrm_pol_bin_key",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1448",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_pol_bin_obj",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296814576,
      "name": "xfrm_pol_bin_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
u32 xfrm_pol_bin_key(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xfrm_pol_bin_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279163588,
      "name": "xfrm_pol_bin_key",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1448",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_pol_bin_obj",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279163588,
      "name": "xfrm_pol_bin_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
u32 xfrm_pol_bin_key(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xfrm_pol_bin_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589051104,
      "name": "xfrm_pol_bin_key",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1448",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_pol_bin_obj",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589051104,
      "name": "xfrm_pol_bin_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
u32 xfrm_pol_bin_key(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xfrm_pol_bin_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588776144,
      "name": "xfrm_pol_bin_key",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1448",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_pol_bin_obj",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588776144,
      "name": "xfrm_pol_bin_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
u32 xfrm_pol_bin_key(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xfrm_pol_bin_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589487968,
      "name": "xfrm_pol_bin_key",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1448",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_pol_bin_obj",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589487968,
      "name": "xfrm_pol_bin_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
u32 xfrm_pol_bin_key(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xfrm_pol_bin_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589534224,
      "name": "xfrm_pol_bin_key",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1448",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_pol_bin_obj",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589534224,
      "name": "xfrm_pol_bin_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
u32 xfrm_pol_bin_key(const void * data, u32 len, u32 seed)
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
