# Function: <code>__rhashtable_lookup</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rhashtable_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582798354,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:560",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587137416,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:560",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587909684,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:560",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
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
  "name": "__rhashtable_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582889471,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:600",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587268427,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:600",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587671959,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:600",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_cache_find_parent",
        "net/ipv4/ipmr.c:ipmr_cache_find_any",
        "net/ipv4/ipmr.c:ipmr_cache_find_any_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588067988,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:600",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
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
  "name": "__rhashtable_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582677247,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:600",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583047851,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:600",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587768066,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:600",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_egdev_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587788235,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:600",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588198199,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:600",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_cache_find_parent",
        "net/ipv4/ipmr.c:ipmr_cache_find_any",
        "net/ipv4/ipmr.c:ipmr_cache_find_any_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588612148,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:600",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
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
  "name": "__rhashtable_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582870754,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:616",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583248166,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:616",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587997835,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:616",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588109650,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:616",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_egdev_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588129947,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:616",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588516595,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:616",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588564170,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:616",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588977967,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:616",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rhashtable_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580807958,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:477",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582978777,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:477",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583366136,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:477",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588157371,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:477",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588278261,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:477",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_indr_block_dev_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588312443,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:477",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588712107,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:477",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588761130,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:477",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588806324,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:477",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589201999,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:477",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rhashtable_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580896502,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583159676,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583550986,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588478992,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:__mem_id_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588673545,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_indr_block_dev_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588710445,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589133702,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589194122,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589239866,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589655711,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rhashtable_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580949766,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583265740,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583656666,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588684400,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:mem_id_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588690265,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_indr_block_dev_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588934349,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589357846,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589419578,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589465226,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589880111,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
struct rhash_head * __rhashtable_lookup(struct rhashtable * ht, const void * key, const struct rhashtable_params params)
```

```json
{
  "name": "__rhashtable_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581109776,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ]
    },
    {
      "addr": 18446744071583589985,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_findkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584017621,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589553071,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame"
      ],
      "caller_func": [
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model"
      ]
    },
    {
      "addr": 18446744071589824182,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590339399,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590405520,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent"
      ]
    },
    {
      "addr": 18446744071590456083,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup_rcu",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590909507,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581109776,
      "name": "__rhashtable_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    },
    {
      "addr": 18446744071589550880,
      "name": "__rhashtable_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071590405520,
      "name": "__rhashtable_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
struct rhash_head * __rhashtable_lookup(struct rhashtable * ht, const void * key, const struct rhashtable_params params)
```

```json
{
  "name": "__rhashtable_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581141546,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister"
      ]
    },
    {
      "addr": 18446744071583710276,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_findkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584137546,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589559193,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589861842,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590392251,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590463360,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent"
      ]
    },
    {
      "addr": 18446744071590514835,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590973043,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581141968,
      "name": "__rhashtable_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    },
    {
      "addr": 18446744071590463360,
      "name": "__rhashtable_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
struct rhash_head * __rhashtable_lookup(struct rhashtable * ht, const void * key, const struct rhashtable_params params)
```

```json
{
  "name": "__rhashtable_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581158362,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister"
      ]
    },
    {
      "addr": 18446744071583734852,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_findkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584164570,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589457193,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589767890,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590308211,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590389120,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent"
      ]
    },
    {
      "addr": 18446744071590440131,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590903923,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581158784,
      "name": "__rhashtable_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    },
    {
      "addr": 18446744071590389120,
      "name": "__rhashtable_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
struct rhash_head * __rhashtable_lookup(struct rhashtable * ht, const void * key, const struct rhashtable_params params)
```

```json
{
  "name": "__rhashtable_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581396214,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister"
      ]
    },
    {
      "addr": 18446744071584096500,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_findkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584548570,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590194633,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590527186,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591095619,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591183600,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent"
      ]
    },
    {
      "addr": 18446744071591239875,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591667605,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6.c:ioam6_namespace",
        "net/ipv6/ioam6.c:ioam6_genl_ns_set_schema",
        "net/ipv6/ioam6.c:ioam6_genl_delsc",
        "net/ipv6/ioam6.c:ioam6_genl_delns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591737635,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581396656,
      "name": "__rhashtable_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    },
    {
      "addr": 18446744071591183600,
      "name": "__rhashtable_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rhashtable_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581722028,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584691993,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_findkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585187155,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591760105,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_unreg_mem_model"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592134388,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592747158,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592842608,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent"
      ]
    },
    {
      "addr": 18446744071592904301,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593363002,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6.c:ioam6_namespace",
        "net/ipv6/ioam6.c:ioam6_genl_ns_set_schema",
        "net/ipv6/ioam6.c:ioam6_genl_ns_set_schema",
        "net/ipv6/ioam6.c:ioam6_genl_delsc",
        "net/ipv6/ioam6.c:ioam6_genl_addsc",
        "net/ipv6/ioam6.c:ioam6_genl_delns",
        "net/ipv6/ioam6.c:ioam6_genl_addns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593440011,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:581",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592842608,
      "name": "__rhashtable_lookup.isra.0",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rhashtable_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582126667,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister"
      ]
    },
    {
      "addr": 18446744071582306596,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585382761,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_findkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585918008,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593549209,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593960180,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594618582,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594719664,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent"
      ]
    },
    {
      "addr": 18446744071594784525,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595270218,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6.c:ioam6_namespace",
        "net/ipv6/ioam6.c:ioam6_genl_ns_set_schema",
        "net/ipv6/ioam6.c:ioam6_genl_ns_set_schema",
        "net/ipv6/ioam6.c:ioam6_genl_delsc",
        "net/ipv6/ioam6.c:ioam6_genl_addsc",
        "net/ipv6/ioam6.c:ioam6_genl_delns",
        "net/ipv6/ioam6.c:ioam6_genl_addns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595355899,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582127216,
      "name": "__rhashtable_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    },
    {
      "addr": 18446744071594719664,
      "name": "__rhashtable_lookup.isra.0",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rhashtable_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582325167,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582506867,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585613569,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_findkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586150140,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594019508,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_unreg_mem_model"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594336964,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595010582,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595111680,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent"
      ]
    },
    {
      "addr": 18446744071595174541,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595665808,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6.c:ioam6_namespace",
        "net/ipv6/ioam6.c:ioam6_genl_ns_set_schema",
        "net/ipv6/ioam6.c:ioam6_genl_ns_set_schema",
        "net/ipv6/ioam6.c:ioam6_genl_delsc",
        "net/ipv6/ioam6.c:ioam6_genl_addsc",
        "net/ipv6/ioam6.c:ioam6_genl_delns",
        "net/ipv6/ioam6.c:ioam6_genl_addns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595752221,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596225999,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "net/handshake/request.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/handshake/request.c:handshake_req_hash_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595111680,
      "name": "__rhashtable_lookup.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rhashtable_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582486159,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582675411,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585860289,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_findkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586399343,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594805636,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_unreg_mem_model"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595136308,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595823302,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595924400,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent"
      ]
    },
    {
      "addr": 18446744071596003574,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596513632,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6.c:ioam6_namespace",
        "net/ipv6/ioam6.c:ioam6_genl_ns_set_schema",
        "net/ipv6/ioam6.c:ioam6_genl_ns_set_schema",
        "net/ipv6/ioam6.c:ioam6_genl_delsc",
        "net/ipv6/ioam6.c:ioam6_genl_addsc",
        "net/ipv6/ioam6.c:ioam6_genl_delns",
        "net/ipv6/ioam6.c:ioam6_genl_addns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596600397,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597104767,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:589",
      "file": "net/handshake/request.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/handshake/request.c:handshake_req_hash_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595924400,
      "name": "__rhashtable_lookup.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__rhashtable_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492295692,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister"
      ]
    },
    {
      "addr": 18446603336494996432,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495451380,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502240580,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:mem_id_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502247104,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_indr_block_dev_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502529532,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502998964,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503072272,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503125664,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503600800,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492293064,
      "name": "__rhashtable_lookup.isra.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    },
    {
      "addr": 18446603336503598096,
      "name": "__rhashtable_lookup.isra.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
struct rhash_head * __rhashtable_lookup(struct rhashtable * ht, const void * key, const struct rhashtable_params params)
```

```json
{
  "name": "__rhashtable_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226179380,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": []
    },
    {
      "addr": 3228409964,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget"
      ],
      "caller_func": []
    },
    {
      "addr": 3228817892,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234985456,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:mem_id_disconnect"
      ],
      "caller_func": [
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model"
      ]
    },
    {
      "addr": 3234991524,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_indr_block_call",
        "net/core/flow_offload.c:__flow_indr_block_cb_unregister",
        "net/core/flow_offload.c:__flow_indr_block_cb_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3235241920,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_autobind",
        "net/netlink/af_netlink.c:netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 3235688848,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235755240,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 3235801832,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup_rcu",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ],
      "caller_func": []
    },
    {
      "addr": 3236244116,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234987104,
      "name": "__rhashtable_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__rhashtable_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285530812,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister"
      ]
    },
    {
      "addr": 13835058055288876956,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289498912,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295732224,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:mem_id_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295738536,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_indr_block_dev_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296105432,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296689476,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296776104,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296837784,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297412348,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285527184,
      "name": "__rhashtable_lookup.isra.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    },
    {
      "addr": 13835058055297409792,
      "name": "__rhashtable_lookup.isra.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__rhashtable_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272426546,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister"
      ]
    },
    {
      "addr": 18446743936274289634,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274640862,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278481632,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:mem_id_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278486880,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_indr_block_dev_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278699226,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279073932,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279129010,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279174092,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279553740,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279552784,
      "name": "__rhashtable_lookup.isra.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    },
    {
      "addr": 18446743936272425188,
      "name": "__rhashtable_lookup.isra.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rhashtable_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580918566,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583234476,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583625402,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588291136,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:mem_id_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588297001,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_indr_block_dev_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588540733,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588964022,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589023946,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589069594,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589484479,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rhashtable_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580864630,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583171628,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583562458,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588003952,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:mem_id_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588009817,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_indr_block_dev_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588252733,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588675958,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588747002,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588794634,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589209471,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rhashtable_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580909814,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583218508,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583609178,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588622960,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:mem_id_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588628825,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_indr_block_dev_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588872909,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589400406,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589460330,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589506458,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589921343,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rhashtable_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580968011,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/offload.c:bpf_prog_offload_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583312742,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583707218,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588760956,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588767252,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_indr_block_call",
        "net/core/flow_offload.c:__flow_indr_block_cb_unregister",
        "net/core/flow_offload.c:__flow_indr_block_cb_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589014461,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589443771,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589506666,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_mfc_find_any",
        "net/ipv4/ipmr_base.c:mr_mfc_find_any_parent",
        "net/ipv4/ipmr_base.c:mr_mfc_find_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589553087,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589975224,
      "name": "__rhashtable_lookup",
      "external": false,
      "loc": "include/linux/rhashtable.h:588",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_push_hmac",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct rhash_head * __rhashtable_lookup(struct rhashtable * ht, const void * key, const struct rhashtable_params params)
```
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct rhash_head * __rhashtable_lookup(struct rhashtable * ht, const void * key, const struct rhashtable_params params)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct rhash_head * __rhashtable_lookup(struct rhashtable * ht, const void * key, const struct rhashtable_params params)
```
</details>
</li>
</ul>
