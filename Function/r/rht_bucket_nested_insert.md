# Function: <code>rht_bucket_nested_insert</code>

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
struct rhash_head * * rht_bucket_nested_insert(struct rhashtable * ht, struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583479120,
      "name": "rht_bucket_nested_insert",
      "external": true,
      "loc": "lib/rhashtable.c:1121",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583479120,
      "name": "rht_bucket_nested_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct rhash_head * * rht_bucket_nested_insert(struct rhashtable * ht, struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583660096,
      "name": "rht_bucket_nested_insert",
      "external": true,
      "loc": "lib/rhashtable.c:1124",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_addid",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "net/sched/act_api.c:tc_setup_cb_egdev_register",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583660096,
      "name": "rht_bucket_nested_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct rhash_head * * rht_bucket_nested_insert(struct rhashtable * ht, struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583876992,
      "name": "rht_bucket_nested_insert",
      "external": true,
      "loc": "lib/rhashtable.c:1222",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_addid",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "net/sched/act_api.c:tc_setup_cb_egdev_register",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583876992,
      "name": "rht_bucket_nested_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rhash_head * * rht_bucket_nested_insert(struct rhashtable * ht, struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583960528,
      "name": "rht_bucket_nested_insert",
      "external": true,
      "loc": "lib/rhashtable.c:1215",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "ipc/util.c:ipc_addid",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "net/sched/cls_api.c:__tc_indr_block_cb_register",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583960528,
      "name": "rht_bucket_nested_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct rhash_lock_head * * rht_bucket_nested_insert(struct rhashtable * ht, struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584140448,
      "name": "rht_bucket_nested_insert",
      "external": true,
      "loc": "lib/rhashtable.c:1207",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "ipc/util.c:ipc_addid",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "net/sched/cls_api.c:__tc_indr_block_cb_register",
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/ipv4/inet_fragment.c:inet_frag_create",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584140448,
      "name": "rht_bucket_nested_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
struct rhash_lock_head * * rht_bucket_nested_insert(struct rhashtable * ht, struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584262896,
      "name": "rht_bucket_nested_insert",
      "external": true,
      "loc": "lib/rhashtable.c:1207",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "ipc/util.c:ipc_addid",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "net/core/flow_offload.c:__flow_indr_block_cb_register",
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/ipv4/inet_fragment.c:inet_frag_create",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584262896,
      "name": "rht_bucket_nested_insert",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rhash_lock_head * * rht_bucket_nested_insert(struct rhashtable * ht, struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584670000,
      "name": "rht_bucket_nested_insert",
      "external": true,
      "loc": "lib/rhashtable.c:1214",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_try_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584670000,
      "name": "rht_bucket_nested_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
struct rhash_lock_head * * rht_bucket_nested_insert(struct rhashtable * ht, struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584787648,
      "name": "rht_bucket_nested_insert",
      "external": true,
      "loc": "lib/rhashtable.c:1214",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_try_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584787648,
      "name": "rht_bucket_nested_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
struct rhash_lock_head * * rht_bucket_nested_insert(struct rhashtable * ht, struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584831440,
      "name": "rht_bucket_nested_insert",
      "external": true,
      "loc": "lib/rhashtable.c:1214",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_try_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584831440,
      "name": "rht_bucket_nested_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
struct rhash_lock_head * * rht_bucket_nested_insert(struct rhashtable * ht, struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rht_bucket_nested_insert",
      "external": true,
      "loc": "lib/rhashtable.c:1214",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_try_insert",
        "net/ipv6/ioam6.c:ioam6_genl_addsc",
        "net/ipv6/ioam6.c:ioam6_genl_addns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592323872,
      "name": "rht_bucket_nested_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071585250352,
      "name": "rht_bucket_nested_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
struct rhash_lock_head * * rht_bucket_nested_insert(struct rhashtable * ht, struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rht_bucket_nested_insert",
      "external": true,
      "loc": "lib/rhashtable.c:1214",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_try_insert",
        "net/ipv6/ioam6.c:ioam6_genl_addsc",
        "net/ipv6/ioam6.c:ioam6_genl_addns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594128368,
      "name": "rht_bucket_nested_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071586092544,
      "name": "rht_bucket_nested_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
struct rhash_lock_head * * rht_bucket_nested_insert(struct rhashtable * ht, struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rht_bucket_nested_insert",
      "external": true,
      "loc": "lib/rhashtable.c:1218",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_try_insert",
        "net/ipv6/ioam6.c:ioam6_genl_addsc",
        "net/ipv6/ioam6.c:ioam6_genl_addns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596115292,
      "name": "rht_bucket_nested_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071587075968,
      "name": "rht_bucket_nested_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
struct rhash_lock_head * * rht_bucket_nested_insert(struct rhashtable * ht, struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rht_bucket_nested_insert",
      "external": true,
      "loc": "lib/rhashtable.c:1218",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_try_insert",
        "net/ipv6/ioam6.c:ioam6_genl_addsc",
        "net/ipv6/ioam6.c:ioam6_genl_addns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596640978,
      "name": "rht_bucket_nested_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071587334960,
      "name": "rht_bucket_nested_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
struct rhash_lock_head * * rht_bucket_nested_insert(struct rhashtable * ht, struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rht_bucket_nested_insert",
      "external": true,
      "loc": "lib/rhashtable.c:1218",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_try_insert",
        "net/ipv6/ioam6.c:ioam6_genl_addsc",
        "net/ipv6/ioam6.c:ioam6_genl_addns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597549043,
      "name": "rht_bucket_nested_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071587618400,
      "name": "rht_bucket_nested_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
struct rhash_lock_head * * rht_bucket_nested_insert(struct rhashtable * ht, struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496143432,
      "name": "rht_bucket_nested_insert",
      "external": true,
      "loc": "lib/rhashtable.c:1207",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "ipc/util.c:ipc_addid",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "net/core/flow_offload.c:__flow_indr_block_cb_register",
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/ipv4/inet_fragment.c:inet_frag_create",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496143432,
      "name": "rht_bucket_nested_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct rhash_lock_head * * rht_bucket_nested_insert(struct rhashtable * ht, struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229465556,
      "name": "rht_bucket_nested_insert",
      "external": true,
      "loc": "lib/rhashtable.c:1207",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "ipc/util.c:ipc_addid",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "net/core/flow_offload.c:__flow_indr_block_cb_register",
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/ipv4/inet_fragment.c:inet_frag_create",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229465556,
      "name": "rht_bucket_nested_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
struct rhash_lock_head * * rht_bucket_nested_insert(struct rhashtable * ht, struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290405056,
      "name": "rht_bucket_nested_insert",
      "external": true,
      "loc": "lib/rhashtable.c:1207",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "ipc/util.c:ipc_addid",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "net/core/flow_offload.c:__flow_indr_block_cb_register",
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/ipv4/inet_fragment.c:inet_frag_create",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290405056,
      "name": "rht_bucket_nested_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
struct rhash_lock_head * * rht_bucket_nested_insert(struct rhashtable * ht, struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275199666,
      "name": "rht_bucket_nested_insert",
      "external": true,
      "loc": "lib/rhashtable.c:1207",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "ipc/util.c:ipc_addid",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "net/core/flow_offload.c:__flow_indr_block_cb_register",
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/ipv4/inet_fragment.c:inet_frag_create",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275199666,
      "name": "rht_bucket_nested_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct rhash_lock_head * * rht_bucket_nested_insert(struct rhashtable * ht, struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584231632,
      "name": "rht_bucket_nested_insert",
      "external": true,
      "loc": "lib/rhashtable.c:1207",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "ipc/util.c:ipc_addid",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "net/core/flow_offload.c:__flow_indr_block_cb_register",
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/ipv4/inet_fragment.c:inet_frag_create",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584231632,
      "name": "rht_bucket_nested_insert",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rhash_lock_head * * rht_bucket_nested_insert(struct rhashtable * ht, struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584166832,
      "name": "rht_bucket_nested_insert",
      "external": true,
      "loc": "lib/rhashtable.c:1207",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "ipc/util.c:ipc_addid",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "net/core/flow_offload.c:__flow_indr_block_cb_register",
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/ipv4/inet_fragment.c:inet_frag_create",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584166832,
      "name": "rht_bucket_nested_insert",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rhash_lock_head * * rht_bucket_nested_insert(struct rhashtable * ht, struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584215392,
      "name": "rht_bucket_nested_insert",
      "external": true,
      "loc": "lib/rhashtable.c:1207",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "ipc/util.c:ipc_addid",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "net/core/flow_offload.c:__flow_indr_block_cb_register",
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/ipv4/inet_fragment.c:inet_frag_create",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584215392,
      "name": "rht_bucket_nested_insert",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rhash_lock_head * * rht_bucket_nested_insert(struct rhashtable * ht, struct bucket_table * tbl, unsigned int hash)
```

```json
{
  "name": "rht_bucket_nested_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584320384,
      "name": "rht_bucket_nested_insert",
      "external": true,
      "loc": "lib/rhashtable.c:1207",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "ipc/util.c:ipc_addid",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "net/core/flow_offload.c:__flow_indr_block_cb_register",
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/ipv4/inet_fragment.c:inet_frag_create",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584320384,
      "name": "rht_bucket_nested_insert",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct rhash_head * * rht_bucket_nested_insert(struct rhashtable * ht, struct bucket_table * tbl, unsigned int hash)
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
