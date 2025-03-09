# Function: <code>xfrm_bundle_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586915389,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1653",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
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
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587361825,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1657",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
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
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587564673,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1685",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587715997,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1675",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588244625,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1545",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588597138,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1548",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dst_entry * xfrm_bundle_create(struct xfrm_policy * policy, struct xfrm_state * * xfrm, struct xfrm_dst * * bundle, int nx, const struct flowi * fl, struct dst_entry * dst)
```

```json
{
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588800064,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:2541",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588800064,
      "name": "xfrm_bundle_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2233
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct dst_entry * xfrm_bundle_create(struct xfrm_policy * policy, struct xfrm_state * * xfrm, struct xfrm_dst * * bundle, int nx, const struct flowi * fl, struct dst_entry * dst)
```

```json
{
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:2532",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589229984,
      "name": "xfrm_bundle_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2219
    },
    {
      "addr": 18446744071589255093,
      "name": "xfrm_bundle_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
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
struct dst_entry * xfrm_bundle_create(struct xfrm_policy * policy, struct xfrm_state * * xfrm, struct xfrm_dst * * bundle, int nx, const struct flowi * fl, struct dst_entry * dst)
```

```json
{
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589455248,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:2534",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589455248,
      "name": "xfrm_bundle_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2233
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
struct dst_entry * xfrm_bundle_create(struct xfrm_policy * policy, struct xfrm_state * * xfrm, struct xfrm_dst * * bundle, int nx, const struct flowi * fl, struct dst_entry * dst)
```

```json
{
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590449392,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:2525",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590449392,
      "name": "xfrm_bundle_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2043
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
struct dst_entry * xfrm_bundle_create(struct xfrm_policy * policy, struct xfrm_state * * xfrm, struct xfrm_dst * * bundle, int nx, const struct flowi * fl, struct dst_entry * dst)
```

```json
{
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590508944,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:2535",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590508944,
      "name": "xfrm_bundle_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2100
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
struct dst_entry * xfrm_bundle_create(struct xfrm_policy * policy, struct xfrm_state * * xfrm, struct xfrm_dst * * bundle, int nx, const struct flowi * fl, struct dst_entry * dst)
```

```json
{
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590434928,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:2534",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590434928,
      "name": "xfrm_bundle_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2102
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
struct dst_entry * xfrm_bundle_create(struct xfrm_policy * policy, struct xfrm_state * * xfrm, struct xfrm_dst * * bundle, int nx, const struct flowi * fl, struct dst_entry * dst)
```

```json
{
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591232560,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:2534",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591232560,
      "name": "xfrm_bundle_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2170
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
struct dst_entry * xfrm_bundle_create(struct xfrm_policy * policy, struct xfrm_state * * xfrm, struct xfrm_dst * * bundle, int nx, const struct flowi * fl, struct dst_entry * dst)
```

```json
{
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592896896,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:2532",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592896896,
      "name": "xfrm_bundle_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2328
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
struct dst_entry * xfrm_bundle_create(struct xfrm_policy * policy, struct xfrm_state * * xfrm, struct xfrm_dst * * bundle, int nx, const struct flowi * fl, struct dst_entry * dst)
```

```json
{
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594776320,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:2606",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594776320,
      "name": "xfrm_bundle_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2204
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
struct dst_entry * xfrm_bundle_create(struct xfrm_policy * policy, struct xfrm_state * * xfrm, struct xfrm_dst * * bundle, int nx, const struct flowi * fl, struct dst_entry * dst)
```

```json
{
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595166960,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:2608",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595166960,
      "name": "xfrm_bundle_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2209
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
struct dst_entry * xfrm_bundle_create(struct xfrm_policy * policy, struct xfrm_state * * xfrm, struct xfrm_dst * * bundle, int nx, const struct flowi * fl, struct dst_entry * dst)
```

```json
{
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596010080,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:2628",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596010080,
      "name": "xfrm_bundle_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2205
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
struct dst_entry * xfrm_bundle_create(struct xfrm_policy * policy, struct xfrm_state * * xfrm, struct xfrm_dst * * bundle, int nx, const struct flowi * fl, struct dst_entry * dst)
```

```json
{
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503110168,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:2534",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503110168,
      "name": "xfrm_bundle_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2080
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
struct dst_entry * xfrm_bundle_create(struct xfrm_policy * policy, struct xfrm_state * * xfrm, struct xfrm_dst * * bundle, int nx, const struct flowi * fl, struct dst_entry * dst)
```

```json
{
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235793056,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:2534",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235793056,
      "name": "xfrm_bundle_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2008
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
struct dst_entry * xfrm_bundle_create(struct xfrm_policy * policy, struct xfrm_state * * xfrm, struct xfrm_dst * * bundle, int nx, const struct flowi * fl, struct dst_entry * dst)
```

```json
{
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296842064,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:2534",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296842064,
      "name": "xfrm_bundle_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2448
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
struct dst_entry * xfrm_bundle_create(struct xfrm_policy * policy, struct xfrm_state * * xfrm, struct xfrm_dst * * bundle, int nx, const struct flowi * fl, struct dst_entry * dst)
```

```json
{
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279168594,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:2534",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279168594,
      "name": "xfrm_bundle_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1596
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
struct dst_entry * xfrm_bundle_create(struct xfrm_policy * policy, struct xfrm_state * * xfrm, struct xfrm_dst * * bundle, int nx, const struct flowi * fl, struct dst_entry * dst)
```

```json
{
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589059616,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:2534",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589059616,
      "name": "xfrm_bundle_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2233
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
struct dst_entry * xfrm_bundle_create(struct xfrm_policy * policy, struct xfrm_state * * xfrm, struct xfrm_dst * * bundle, int nx, const struct flowi * fl, struct dst_entry * dst)
```

```json
{
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588784656,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:2534",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588784656,
      "name": "xfrm_bundle_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2233
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
struct dst_entry * xfrm_bundle_create(struct xfrm_policy * policy, struct xfrm_state * * xfrm, struct xfrm_dst * * bundle, int nx, const struct flowi * fl, struct dst_entry * dst)
```

```json
{
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589496480,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:2534",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589496480,
      "name": "xfrm_bundle_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2233
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
struct dst_entry * xfrm_bundle_create(struct xfrm_policy * policy, struct xfrm_state * * xfrm, struct xfrm_dst * * bundle, int nx, const struct flowi * fl, struct dst_entry * dst)
```

```json
{
  "name": "xfrm_bundle_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589543056,
      "name": "xfrm_bundle_create",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:2534",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589543056,
      "name": "xfrm_bundle_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2344
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
struct dst_entry * xfrm_bundle_create(struct xfrm_policy * policy, struct xfrm_state * * xfrm, struct xfrm_dst * * bundle, int nx, const struct flowi * fl, struct dst_entry * dst)
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
