# Function: <code>rhashtable_insert_slow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct bucket_table * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj, struct bucket_table * tbl)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583042304,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:441",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583042304,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 531
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
struct bucket_table * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj, struct bucket_table * tbl)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583335056,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:444",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "net/netlink/af_netlink.c:netlink_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583335056,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 557
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
void * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583459408,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:575",
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
      "addr": 18446744071583459408,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
void * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583482016,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:669",
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
      "addr": 18446744071583482016,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
void * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583663008,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:671",
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
      "addr": 18446744071583663008,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 707
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
void * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583880576,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:641",
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
      "addr": 18446744071583880576,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
void * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583963008,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:633",
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
      "addr": 18446744071583963008,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 658
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
void * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584142752,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:622",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "ipc/util.c:ipc_addid",
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
      "addr": 18446744071584142752,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1169
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
void * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584265200,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:622",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "ipc/util.c:ipc_addid",
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
      "addr": 18446744071584265200,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1169
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
void * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584673120,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:629",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_rxq_info_reg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584673120,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584790720,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:629",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_rxq_info_reg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584790720,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584835520,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:629",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_rxq_info_reg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584835520,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585254704,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:629",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ioam6.c:ioam6_genl_addsc",
        "net/ipv6/ioam6.c:ioam6_genl_addns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585254704,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586096528,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:629",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_reg_mem_model",
        "net/ipv6/ioam6.c:ioam6_genl_addsc",
        "net/ipv6/ioam6.c:ioam6_genl_addns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586096528,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587080128,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:633",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_reg_mem_model",
        "net/ipv6/ioam6.c:ioam6_genl_addsc",
        "net/ipv6/ioam6.c:ioam6_genl_addns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587080128,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587338768,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:633",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_reg_mem_model",
        "net/ipv6/ioam6.c:ioam6_genl_addsc",
        "net/ipv6/ioam6.c:ioam6_genl_addns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587338768,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587622240,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:633",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_reg_mem_model",
        "net/ipv6/ioam6.c:ioam6_genl_addsc",
        "net/ipv6/ioam6.c:ioam6_genl_addns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587622240,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496147120,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:622",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "ipc/util.c:ipc_addid",
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
      "addr": 18446603336496147120,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1176
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
void * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229468644,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:622",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "ipc/util.c:ipc_addid",
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
      "addr": 3229468644,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1372
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
void * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290407200,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:622",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "ipc/util.c:ipc_addid",
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
      "addr": 13835058055290407200,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1608
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
void * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275202156,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:622",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "ipc/util.c:ipc_addid",
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
      "addr": 18446743936275202156,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1066
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
void * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584233936,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:622",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "ipc/util.c:ipc_addid",
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
      "addr": 18446744071584233936,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1169
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
void * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584169136,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:622",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "ipc/util.c:ipc_addid",
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
      "addr": 18446744071584169136,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1169
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
void * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584217696,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:622",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "ipc/util.c:ipc_addid",
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
      "addr": 18446744071584217696,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1169
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
void * rhashtable_insert_slow(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_insert_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584322368,
      "name": "rhashtable_insert_slow",
      "external": true,
      "loc": "lib/rhashtable.c:622",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "ipc/util.c:ipc_addid",
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
      "addr": 18446744071584322368,
      "name": "rhashtable_insert_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1237
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct bucket_table * tbl</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct bucket_table *</code> ➡️ <code>void *</code>
</li>
</ul>
</details>
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
