# Function: <code>__xfrm_state_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __xfrm_state_destroy(struct xfrm_state * x)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586935824,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:501",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_input.c:__secpath_destroy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586935824,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void __xfrm_state_destroy(struct xfrm_state * x)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587382352,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:502",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/xfrm/xfrm_input.c:__secpath_destroy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587382352,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void __xfrm_state_destroy(struct xfrm_state * x)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587586176,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:513",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/xfrm/xfrm_input.c:__secpath_destroy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587586176,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void __xfrm_state_destroy(struct xfrm_state * x)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587732704,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:586",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/xfrm/xfrm_input.c:__secpath_destroy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587732704,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __xfrm_state_destroy(struct xfrm_state * x)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588259648,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:594",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/xfrm/xfrm_input.c:__secpath_destroy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588259648,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __xfrm_state_destroy(struct xfrm_state * x)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588614720,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:595",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/xfrm/xfrm_input.c:__secpath_destroy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588614720,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void __xfrm_state_destroy(struct xfrm_state * x, bool sync)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588826080,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:601",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_put",
        "net/core/skbuff.c:__skb_ext_del",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588826080,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __xfrm_state_destroy(struct xfrm_state * x, bool sync)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589260569,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:639",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589282747,
      "name": "__xfrm_state_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589260512,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void __xfrm_state_destroy(struct xfrm_state * x, bool sync)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589485504,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:641",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589485504,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void __xfrm_state_destroy(struct xfrm_state * x, bool sync)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590475296,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:641",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_put",
        "net/core/skbuff.c:__skb_ext_del",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590475296,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void __xfrm_state_destroy(struct xfrm_state * x, bool sync)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590532832,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:641",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_put",
        "net/core/skbuff.c:__skb_ext_del",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590532832,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void __xfrm_state_destroy(struct xfrm_state * x, bool sync)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590457856,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:640",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_put",
        "net/core/skbuff.c:__skb_ext_del",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590457856,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void __xfrm_state_destroy(struct xfrm_state * x, bool sync)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591260416,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:662",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_put",
        "net/core/skbuff.c:__skb_ext_del",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591260416,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void __xfrm_state_destroy(struct xfrm_state * x, bool sync)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592925936,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:663",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_put",
        "net/core/skbuff.c:__skb_ext_del",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592925936,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void __xfrm_state_destroy(struct xfrm_state * x, bool sync)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594807552,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:686",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_put",
        "net/core/skbuff.c:__skb_ext_del",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594807552,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void __xfrm_state_destroy(struct xfrm_state * x, bool sync)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595199552,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:686",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_put",
        "net/core/skbuff.c:__skb_ext_del",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595199552,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void __xfrm_state_destroy(struct xfrm_state * x, bool sync)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596040096,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:686",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_put",
        "net/core/skbuff.c:__skb_ext_del",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/xfrm/xfrm_state_bpf.c:bpf_xdp_xfrm_state_release",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596040096,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void __xfrm_state_destroy(struct xfrm_state * x, bool sync)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503156240,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:641",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_put",
        "net/core/skbuff.c:__skb_ext_del",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503156240,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void __xfrm_state_destroy(struct xfrm_state * x, bool sync)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235825760,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:641",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_put",
        "net/core/skbuff.c:__skb_ext_del",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235825760,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void __xfrm_state_destroy(struct xfrm_state * x, bool sync)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296869792,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:641",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_put",
        "net/core/skbuff.c:__skb_ext_del",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296869792,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void __xfrm_state_destroy(struct xfrm_state * x, bool sync)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279189808,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:641",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_ext_put_sp",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279189808,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void __xfrm_state_destroy(struct xfrm_state * x, bool sync)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589089872,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:641",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589089872,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void __xfrm_state_destroy(struct xfrm_state * x, bool sync)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588814912,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:641",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588814912,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void __xfrm_state_destroy(struct xfrm_state * x, bool sync)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589526736,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:641",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589526736,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void __xfrm_state_destroy(struct xfrm_state * x, bool sync)
```

```json
{
  "name": "__xfrm_state_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589574256,
      "name": "__xfrm_state_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:641",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve",
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589574256,
      "name": "__xfrm_state_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool sync</code>
</li>
</ul>
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
