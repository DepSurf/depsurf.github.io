# Function: <code>xfrm_policy_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586911680,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:316",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_flo_delete",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_policy.c:xfrm_policy_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586911680,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587357824,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:316",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_flo_delete",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587357824,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587560464,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:322",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_flo_delete",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587560464,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587707344,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:317",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_flo_delete",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587707344,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588234112,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:288",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588234112,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588587872,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:288",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588587872,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588794064,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:412",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588794064,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589225120,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:417",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589225120,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589450384,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:417",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589450384,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590436848,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:420",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590436848,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590495456,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:420",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590495456,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590420944,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:419",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590420944,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591219264,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:421",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591219264,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592882016,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:421",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592882016,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594761104,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:421",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594761104,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595153504,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:421",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595153504,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595995664,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:436",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595995664,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503105952,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:417",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503105952,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235788048,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:417",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235788048,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296821088,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:417",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296821088,
      "name": "xfrm_policy_destroy",
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
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279157578,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:417",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279157578,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589054752,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:417",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589054752,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588779792,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:417",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588779792,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589491616,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:417",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589491616,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void xfrm_policy_destroy(struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589538256,
      "name": "xfrm_policy_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:417",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589538256,
      "name": "xfrm_policy_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
