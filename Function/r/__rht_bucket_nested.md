# Function: <code>__rht_bucket_nested</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rhash_lock_head * * __rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "__rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584139072,
      "name": "__rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1167",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:rhashtable_rehash_table",
        "net/netlink/af_netlink.c:netlink_remove",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584139072,
      "name": "__rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct rhash_lock_head * * __rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "__rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584261520,
      "name": "__rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1167",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:rhashtable_rehash_table",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/xdp.c:mem_xa_remove",
        "net/netlink/af_netlink.c:netlink_remove",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584261520,
      "name": "__rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct rhash_lock_head * * __rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "__rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584669392,
      "name": "__rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1174",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:__rhashtable_remove_fast_one",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_try_insert",
        "lib/rhashtable.c:rhashtable_rehash_chain",
        "net/core/xdp.c:__rhashtable_remove_fast_one",
        "net/netlink/af_netlink.c:__rhashtable_remove_fast_one",
        "net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one",
        "net/ipv4/ipmr.c:__rhashtable_remove_fast_one",
        "net/ipv6/ip6mr.c:__rhashtable_remove_fast_one",
        "net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584669392,
      "name": "__rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct rhash_lock_head * * __rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "__rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584787040,
      "name": "__rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1174",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:__rhashtable_remove_fast_one",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_try_insert",
        "lib/rhashtable.c:rhashtable_rehash_chain",
        "net/core/xdp.c:__rhashtable_remove_fast_one",
        "net/netlink/af_netlink.c:__rhashtable_remove_fast_one",
        "net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one",
        "net/ipv4/ipmr.c:__rhashtable_remove_fast_one",
        "net/ipv6/ip6mr.c:__rhashtable_remove_fast_one",
        "net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584787040,
      "name": "__rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct rhash_lock_head * * __rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "__rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584831104,
      "name": "__rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1174",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:__rhashtable_remove_fast_one",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_try_insert",
        "lib/rhashtable.c:rhashtable_rehash_table",
        "net/core/xdp.c:__rhashtable_remove_fast_one",
        "net/netlink/af_netlink.c:__rhashtable_remove_fast_one",
        "net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one",
        "net/ipv4/ipmr.c:__rhashtable_remove_fast_one",
        "net/ipv6/ip6mr.c:__rhashtable_remove_fast_one",
        "net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584831104,
      "name": "__rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct rhash_lock_head * * __rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "__rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1174",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:__rhashtable_remove_fast_one",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_try_insert",
        "lib/rhashtable.c:rhashtable_rehash_table",
        "net/core/xdp.c:__rhashtable_remove_fast_one",
        "net/netlink/af_netlink.c:__rhashtable_remove_fast_one",
        "net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one",
        "net/ipv4/ipmr.c:__rhashtable_remove_fast_one",
        "net/ipv6/ioam6.c:__rhashtable_remove_fast_one",
        "net/ipv6/ip6mr.c:__rhashtable_remove_fast_one",
        "net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592323743,
      "name": "__rht_bucket_nested.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071585249968,
      "name": "__rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
struct rhash_lock_head * * __rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "__rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1174",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_try_insert",
        "lib/rhashtable.c:rhashtable_rehash_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594128239,
      "name": "__rht_bucket_nested.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071586092080,
      "name": "__rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
struct rhash_lock_head * * __rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "__rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1178",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_try_insert",
        "lib/rhashtable.c:rhashtable_rehash_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596115163,
      "name": "__rht_bucket_nested.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071587075440,
      "name": "__rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
struct rhash_lock_head * * __rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "__rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1178",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_try_insert",
        "lib/rhashtable.c:rhashtable_rehash_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596640823,
      "name": "__rht_bucket_nested.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071587334016,
      "name": "__rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct rhash_lock_head * * __rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "__rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1178",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_try_insert",
        "lib/rhashtable.c:rhashtable_rehash_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597548888,
      "name": "__rht_bucket_nested.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071587617408,
      "name": "__rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct rhash_lock_head * * __rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "__rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496142864,
      "name": "__rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1167",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:rhashtable_rehash_table",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/xdp.c:mem_xa_remove",
        "net/netlink/af_netlink.c:netlink_remove",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496142864,
      "name": "__rht_bucket_nested",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rhash_lock_head * * __rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "__rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229464876,
      "name": "__rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1167",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:rhashtable_rehash_table",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/xdp.c:mem_xa_remove",
        "net/netlink/af_netlink.c:netlink_remove",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_delete",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229464876,
      "name": "__rht_bucket_nested",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rhash_lock_head * * __rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "__rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290401344,
      "name": "__rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1167",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:rhashtable_rehash_table",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/xdp.c:mem_allocator_disconnect",
        "net/netlink/af_netlink.c:netlink_remove",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290401344,
      "name": "__rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct rhash_lock_head * * __rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "__rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275198418,
      "name": "__rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1167",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:rhashtable_rehash_table",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/xdp.c:mem_allocator_disconnect",
        "net/netlink/af_netlink.c:netlink_remove",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275198418,
      "name": "__rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
struct rhash_lock_head * * __rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "__rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584230256,
      "name": "__rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1167",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:rhashtable_rehash_table",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/xdp.c:mem_xa_remove",
        "net/netlink/af_netlink.c:netlink_remove",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584230256,
      "name": "__rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct rhash_lock_head * * __rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "__rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584165456,
      "name": "__rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1167",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:rhashtable_rehash_table",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/xdp.c:mem_xa_remove",
        "net/netlink/af_netlink.c:netlink_remove",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584165456,
      "name": "__rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct rhash_lock_head * * __rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "__rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584214016,
      "name": "__rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1167",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:rhashtable_rehash_table",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/xdp.c:mem_xa_remove",
        "net/netlink/af_netlink.c:netlink_remove",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584214016,
      "name": "__rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct rhash_lock_head * * __rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "__rht_bucket_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584318880,
      "name": "__rht_bucket_nested",
      "external": true,
      "loc": "lib/rhashtable.c:1167",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:__rhashtable_walk_find_next",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:rhashtable_rehash_table",
        "net/core/xdp.c:mem_xa_remove",
        "net/netlink/af_netlink.c:netlink_remove",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584318880,
      "name": "__rht_bucket_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct rhash_lock_head * * __rht_bucket_nested(const struct bucket_table * tbl, unsigned int hash)
```
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
