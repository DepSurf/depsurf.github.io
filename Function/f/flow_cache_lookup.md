# Function: <code>flow_cache_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct flow_cache_object * flow_cache_lookup(struct net * net, const struct flowi * key, u16 family, u8 dir, flow_resolve_t resolver, void * ctx)
```

```json
{
  "name": "flow_cache_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586400080,
      "name": "flow_cache_lookup",
      "external": true,
      "loc": "net/core/flow.c:192",
      "file": "net/core/flow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586400080,
      "name": "flow_cache_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1052
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct flow_cache_object * flow_cache_lookup(struct net * net, const struct flowi * key, u16 family, u8 dir, flow_resolve_t resolver, void * ctx)
```

```json
{
  "name": "flow_cache_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586842688,
      "name": "flow_cache_lookup",
      "external": true,
      "loc": "net/core/flow.c:196",
      "file": "net/core/flow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586842688,
      "name": "flow_cache_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1096
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
struct flow_cache_object * flow_cache_lookup(struct net * net, const struct flowi * key, u16 family, u8 dir, flow_resolve_t resolver, void * ctx)
```

```json
{
  "name": "flow_cache_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587034240,
      "name": "flow_cache_lookup",
      "external": true,
      "loc": "net/core/flow.c:195",
      "file": "net/core/flow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587034240,
      "name": "flow_cache_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1087
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
struct flow_cache_object * flow_cache_lookup(struct net * net, const struct flowi * key, u16 family, u8 dir, flow_resolve_t resolver, void * ctx)
```

```json
{
  "name": "flow_cache_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587162064,
      "name": "flow_cache_lookup",
      "external": true,
      "loc": "net/core/flow.c:197",
      "file": "net/core/flow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587162064,
      "name": "flow_cache_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1206
    }
  ]
}
```
</details>
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
struct flow_cache_object * flow_cache_lookup(struct net * net, const struct flowi * key, u16 family, u8 dir, flow_resolve_t resolver, void * ctx)
```
</details>
</li>
</ul>
