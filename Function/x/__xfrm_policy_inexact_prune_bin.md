# Function: <code>__xfrm_policy_inexact_prune_bin</code>

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
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin * b, bool net_exit)
```

```json
{
  "name": "__xfrm_policy_inexact_prune_bin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588805488,
      "name": "__xfrm_policy_inexact_prune_bin",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1066",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588805488,
      "name": "__xfrm_policy_inexact_prune_bin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
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
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin * b, bool net_exit)
```

```json
{
  "name": "__xfrm_policy_inexact_prune_bin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589238848,
      "name": "__xfrm_policy_inexact_prune_bin",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1070",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589238848,
      "name": "__xfrm_policy_inexact_prune_bin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin * b, bool net_exit)
```

```json
{
  "name": "__xfrm_policy_inexact_prune_bin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589464176,
      "name": "__xfrm_policy_inexact_prune_bin",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1072",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589464176,
      "name": "__xfrm_policy_inexact_prune_bin.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    },
    {
      "addr": 18446744071589464656,
      "name": "__xfrm_policy_inexact_prune_bin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin * b, bool net_exit)
```

```json
{
  "name": "__xfrm_policy_inexact_prune_bin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590457856,
      "name": "__xfrm_policy_inexact_prune_bin",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1075",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_flush",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590457856,
      "name": "__xfrm_policy_inexact_prune_bin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin * b, bool net_exit)
```

```json
{
  "name": "__xfrm_policy_inexact_prune_bin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590516240,
      "name": "__xfrm_policy_inexact_prune_bin",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1085",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_flush",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590516240,
      "name": "__xfrm_policy_inexact_prune_bin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin * b, bool net_exit)
```

```json
{
  "name": "__xfrm_policy_inexact_prune_bin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590441520,
      "name": "__xfrm_policy_inexact_prune_bin",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1084",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_flush",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590441520,
      "name": "__xfrm_policy_inexact_prune_bin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin * b, bool net_exit)
```

```json
{
  "name": "__xfrm_policy_inexact_prune_bin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591241280,
      "name": "__xfrm_policy_inexact_prune_bin",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1086",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_flush",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591241280,
      "name": "__xfrm_policy_inexact_prune_bin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin * b, bool net_exit)
```

```json
{
  "name": "__xfrm_policy_inexact_prune_bin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592903520,
      "name": "__xfrm_policy_inexact_prune_bin",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1086",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_flush",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592903520,
      "name": "__xfrm_policy_inexact_prune_bin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin * b, bool net_exit)
```

```json
{
  "name": "__xfrm_policy_inexact_prune_bin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594783728,
      "name": "__xfrm_policy_inexact_prune_bin",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1087",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_dev_policy_flush",
        "net/xfrm/xfrm_policy.c:xfrm_policy_flush",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594783728,
      "name": "__xfrm_policy_inexact_prune_bin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin * b, bool net_exit)
```

```json
{
  "name": "__xfrm_policy_inexact_prune_bin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595173744,
      "name": "__xfrm_policy_inexact_prune_bin",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1087",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_dev_policy_flush",
        "net/xfrm/xfrm_policy.c:xfrm_policy_flush",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595173744,
      "name": "__xfrm_policy_inexact_prune_bin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin * b, bool net_exit)
```

```json
{
  "name": "__xfrm_policy_inexact_prune_bin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596016864,
      "name": "__xfrm_policy_inexact_prune_bin",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1102",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_dev_policy_flush",
        "net/xfrm/xfrm_policy.c:xfrm_policy_flush",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596016864,
      "name": "__xfrm_policy_inexact_prune_bin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin * b, bool net_exit)
```

```json
{
  "name": "__xfrm_policy_inexact_prune_bin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503118976,
      "name": "__xfrm_policy_inexact_prune_bin",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1072",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503118976,
      "name": "__xfrm_policy_inexact_prune_bin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 772
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin * b, bool net_exit)
```

```json
{
  "name": "__xfrm_policy_inexact_prune_bin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235802076,
      "name": "__xfrm_policy_inexact_prune_bin",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1072",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235802076,
      "name": "__xfrm_policy_inexact_prune_bin.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 840
    },
    {
      "addr": 3235802916,
      "name": "__xfrm_policy_inexact_prune_bin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin * b, bool net_exit)
```

```json
{
  "name": "__xfrm_policy_inexact_prune_bin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296828816,
      "name": "__xfrm_policy_inexact_prune_bin",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1072",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296828816,
      "name": "__xfrm_policy_inexact_prune_bin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 920
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
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin * b, bool net_exit)
```

```json
{
  "name": "__xfrm_policy_inexact_prune_bin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279161330,
      "name": "__xfrm_policy_inexact_prune_bin",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1072",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279161330,
      "name": "__xfrm_policy_inexact_prune_bin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin * b, bool net_exit)
```

```json
{
  "name": "__xfrm_policy_inexact_prune_bin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589068544,
      "name": "__xfrm_policy_inexact_prune_bin",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1072",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589068544,
      "name": "__xfrm_policy_inexact_prune_bin.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    },
    {
      "addr": 18446744071589069024,
      "name": "__xfrm_policy_inexact_prune_bin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin * b, bool net_exit)
```

```json
{
  "name": "__xfrm_policy_inexact_prune_bin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588793584,
      "name": "__xfrm_policy_inexact_prune_bin",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1072",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588793584,
      "name": "__xfrm_policy_inexact_prune_bin.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    },
    {
      "addr": 18446744071588794064,
      "name": "__xfrm_policy_inexact_prune_bin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin * b, bool net_exit)
```

```json
{
  "name": "__xfrm_policy_inexact_prune_bin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589505408,
      "name": "__xfrm_policy_inexact_prune_bin",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1072",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589505408,
      "name": "__xfrm_policy_inexact_prune_bin.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    },
    {
      "addr": 18446744071589505888,
      "name": "__xfrm_policy_inexact_prune_bin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin * b, bool net_exit)
```

```json
{
  "name": "__xfrm_policy_inexact_prune_bin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589551904,
      "name": "__xfrm_policy_inexact_prune_bin",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1072",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589551904,
      "name": "__xfrm_policy_inexact_prune_bin.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
    },
    {
      "addr": 18446744071589552496,
      "name": "__xfrm_policy_inexact_prune_bin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin * b, bool net_exit)
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
