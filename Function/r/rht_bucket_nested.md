# Function: <code>rht_bucket_nested</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rhash_head * * rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583477456,
      "name": "rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1090",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:rhashtable_walk_next",
        "lib/rhashtable.c:rhashtable_lookup_one",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:__netlink_lookup",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_cache_find_parent",
        "net/ipv4/ipmr.c:ipmr_cache_find_any",
        "net/ipv4/ipmr.c:ipmr_cache_find_any_parent",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583477456,
      "name": "rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct rhash_head * * rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583658416,
      "name": "rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1093",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:rhashtable_walk_next",
        "lib/rhashtable.c:rhashtable_lookup_one",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "net/sched/act_api.c:tcf_action_egdev_lookup",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:__netlink_lookup",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_cache_find_parent",
        "net/ipv4/ipmr.c:ipmr_cache_find_any",
        "net/ipv4/ipmr.c:ipmr_cache_find_any_parent",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583658416,
      "name": "rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct rhash_head * * rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583875440,
      "name": "rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1191",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/util.c:ipc_set_key_private",
        "ipc/util.c:ipc_rmid",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_lookup_one",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg",
        "net/core/xdp.c:xdp_rxq_info_unreg",
        "net/sched/act_api.c:tcf_action_egdev_lookup",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:__netlink_lookup",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583875440,
      "name": "rht_bucket_nested",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rhash_head * * rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583959184,
      "name": "rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1182",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev",
        "ipc/util.c:ipcget",
        "ipc/util.c:ipc_set_key_private",
        "ipc/util.c:ipc_rmid",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_lookup_one",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/sched/cls_api.c:tc_indr_block_dev_lookup",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:__netlink_lookup",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583959184,
      "name": "rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct rhash_lock_head * * rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584139698,
      "name": "rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1196",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev",
        "ipc/util.c:ipcget",
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:__mem_id_disconnect",
        "net/sched/cls_api.c:tc_indr_block_dev_lookup",
        "net/netlink/af_netlink.c:__netlink_lookup",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584139168,
      "name": "rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct rhash_lock_head * * rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584262146,
      "name": "rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1196",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev",
        "ipc/util.c:ipcget",
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/flow_offload.c:flow_indr_block_dev_lookup",
        "net/netlink/af_netlink.c:__netlink_lookup",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584261616,
      "name": "rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct rhash_lock_head * * rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584673645,
      "name": "rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1203",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check"
      ],
      "caller_func": [
        "ipc/util.c:ipc_findkey",
        "net/core/xdp.c:__xdp_release_frame",
        "net/netlink/af_netlink.c:__netlink_lookup",
        "net/ipv4/ipmr_base.c:__rhashtable_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup_rcu",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584669488,
      "name": "rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct rhash_lock_head * * rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584791261,
      "name": "rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1203",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_find_netdev",
        "ipc/util.c:ipc_findkey",
        "net/netlink/af_netlink.c:__netlink_lookup",
        "net/ipv4/ipmr_base.c:__rhashtable_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584787136,
      "name": "rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct rhash_lock_head * * rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584833476,
      "name": "rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1203",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_find_netdev",
        "ipc/util.c:ipc_findkey",
        "net/netlink/af_netlink.c:__netlink_lookup",
        "net/ipv4/ipmr_base.c:__rhashtable_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584831200,
      "name": "rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct rhash_lock_head * * rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585252465,
      "name": "rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1203",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_find_netdev",
        "ipc/util.c:ipc_findkey",
        "net/netlink/af_netlink.c:__netlink_lookup",
        "net/ipv4/ipmr_base.c:__rhashtable_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/ioam6.c:ioam6_namespace",
        "net/ipv6/ioam6.c:ioam6_genl_ns_set_schema",
        "net/ipv6/ioam6.c:ioam6_genl_delsc",
        "net/ipv6/ioam6.c:ioam6_genl_delns",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585250112,
      "name": "rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct rhash_lock_head * * rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586094095,
      "name": "rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1203",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev",
        "ipc/util.c:ipc_findkey",
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_unreg_mem_model",
        "net/ipv4/inet_fragment.c:inet_frag_find",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/ioam6.c:ioam6_namespace",
        "net/ipv6/ioam6.c:ioam6_genl_ns_set_schema",
        "net/ipv6/ioam6.c:ioam6_genl_ns_set_schema",
        "net/ipv6/ioam6.c:ioam6_genl_delsc",
        "net/ipv6/ioam6.c:ioam6_genl_addsc",
        "net/ipv6/ioam6.c:ioam6_genl_delns",
        "net/ipv6/ioam6.c:ioam6_genl_addns",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586092240,
      "name": "rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct rhash_lock_head * * rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587077583,
      "name": "rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1207",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_find_netdev",
        "ipc/util.c:ipc_findkey",
        "net/ipv4/inet_fragment.c:inet_frag_find",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/ioam6.c:ioam6_namespace",
        "net/ipv6/ioam6.c:ioam6_genl_ns_set_schema",
        "net/ipv6/ioam6.c:ioam6_genl_ns_set_schema",
        "net/ipv6/ioam6.c:ioam6_genl_delsc",
        "net/ipv6/ioam6.c:ioam6_genl_addsc",
        "net/ipv6/ioam6.c:ioam6_genl_delns",
        "net/ipv6/ioam6.c:ioam6_genl_addns",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587075616,
      "name": "rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct rhash_lock_head * * rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587336527,
      "name": "rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1207",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev",
        "ipc/util.c:ipc_findkey",
        "net/core/xdp.c:xdp_unreg_mem_model",
        "net/ipv4/inet_fragment.c:inet_frag_find",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/ioam6.c:ioam6_namespace",
        "net/ipv6/ioam6.c:ioam6_genl_ns_set_schema",
        "net/ipv6/ioam6.c:ioam6_genl_ns_set_schema",
        "net/ipv6/ioam6.c:ioam6_genl_delsc",
        "net/ipv6/ioam6.c:ioam6_genl_addsc",
        "net/ipv6/ioam6.c:ioam6_genl_delns",
        "net/ipv6/ioam6.c:ioam6_genl_addns",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup",
        "net/handshake/request.c:handshake_req_hash_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587334176,
      "name": "rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct rhash_lock_head * * rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587619999,
      "name": "rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1207",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev",
        "ipc/util.c:ipc_findkey",
        "net/core/xdp.c:xdp_unreg_mem_model",
        "net/ipv4/inet_fragment.c:inet_frag_find",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/ioam6.c:ioam6_namespace",
        "net/ipv6/ioam6.c:ioam6_genl_ns_set_schema",
        "net/ipv6/ioam6.c:ioam6_genl_ns_set_schema",
        "net/ipv6/ioam6.c:ioam6_genl_delsc",
        "net/ipv6/ioam6.c:ioam6_genl_addsc",
        "net/ipv6/ioam6.c:ioam6_genl_delns",
        "net/ipv6/ioam6.c:ioam6_genl_addns",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup",
        "net/handshake/request.c:handshake_req_hash_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587617568,
      "name": "rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct rhash_lock_head * * rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496146784,
      "name": "rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1196",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_find_netdev",
        "ipc/util.c:ipcget",
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/flow_offload.c:flow_indr_block_dev_lookup",
        "net/netlink/af_netlink.c:__netlink_lookup",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496142960,
      "name": "rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct rhash_lock_head * * rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229468188,
      "name": "rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1196",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev",
        "ipc/util.c:ipcget",
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/flow_offload.c:flow_indr_block_call",
        "net/core/flow_offload.c:__flow_indr_block_cb_unregister",
        "net/core/flow_offload.c:__flow_indr_block_cb_register",
        "net/netlink/af_netlink.c:netlink_autobind",
        "net/netlink/af_netlink.c:netlink_lookup",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup_rcu",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229464972,
      "name": "rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct rhash_lock_head * * rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290402912,
      "name": "rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1196",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_find_netdev",
        "ipc/util.c:ipcget",
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/flow_offload.c:flow_indr_block_dev_lookup",
        "net/netlink/af_netlink.c:__netlink_lookup",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290401488,
      "name": "rht_bucket_nested",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct rhash_lock_head * * rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275198844,
      "name": "rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1196",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_find_netdev",
        "ipc/util.c:ipcget",
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/flow_offload.c:flow_indr_block_dev_lookup",
        "net/netlink/af_netlink.c:__netlink_lookup",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275198516,
      "name": "rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct rhash_lock_head * * rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584230882,
      "name": "rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1196",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev",
        "ipc/util.c:ipcget",
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/flow_offload.c:flow_indr_block_dev_lookup",
        "net/netlink/af_netlink.c:__netlink_lookup",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584230352,
      "name": "rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct rhash_lock_head * * rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584166082,
      "name": "rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1196",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev",
        "ipc/util.c:ipcget",
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/flow_offload.c:flow_indr_block_dev_lookup",
        "net/netlink/af_netlink.c:__netlink_lookup",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584165552,
      "name": "rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct rhash_lock_head * * rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584214642,
      "name": "rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1196",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev",
        "ipc/util.c:ipcget",
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/flow_offload.c:flow_indr_block_dev_lookup",
        "net/netlink/af_netlink.c:__netlink_lookup",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584214112,
      "name": "rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct rhash_lock_head * * rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584319631,
      "name": "rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1196",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/offload.c:bpf_prog_offload_init",
        "ipc/util.c:ipcget",
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/flow_offload.c:flow_indr_block_call",
        "net/core/flow_offload.c:__flow_indr_block_cb_unregister",
        "net/core/flow_offload.c:__flow_indr_block_cb_register",
        "net/netlink/af_netlink.c:netlink_lookup",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/seg6_hmac.c:seg6_push_hmac",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584318976,
      "name": "rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct rhash_head * * rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct rhash_head * *</code> ➡️ <code>struct rhash_lock_head * *</code>
</li>
</ul>
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
