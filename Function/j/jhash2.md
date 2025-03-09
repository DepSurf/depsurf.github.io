# Function: <code>jhash2</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579893029,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:hash_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580799407,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault_mutex_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580835933,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583041120,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586256633,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:skb_get_hash_perturb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586400226,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586494529,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586913835,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587116343,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp6_portaddr_hash"
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
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579922070,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:hash_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580451915,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580923026,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault_mutex_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580962535,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583333872,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586686598,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:skb_get_hash_perturb",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586842840,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586940961,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587360090,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587568697,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp6_portaddr_hash"
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
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579952726,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:hash_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580513019,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580991378,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault_mutex_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581028719,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583459168,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586872430,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:skb_get_hash_perturb",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587034392,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587136209,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587562973,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587772921,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp6_portaddr_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587909701,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 jhash2(const u32 * k, u32 length, u32 initval)
```

```json
{
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579959014,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:hash_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580544833,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581038148,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault_mutex_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581074736,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583481792,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586996869,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:skb_get_hash_perturb",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587162297,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587266557,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587671980,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
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
      "addr": 18446744071587710239,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587929264,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp6_portaddr_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588068005,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583476784,
      "name": "jhash2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071587259456,
      "name": "jhash2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071587659904,
      "name": "jhash2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071588068876,
      "name": "jhash2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 jhash2(const u32 * k, u32 length, u32 initval)
```

```json
{
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580004838,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:hash_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580622561,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147892,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault_mutex_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581185904,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582673760,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/util.c:ipc_addid"
      ]
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583662784,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587495557,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:skb_get_hash_perturb",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587768070,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_egdev_lookup"
      ],
      "caller_func": [
        "net/sched/act_api.c:tc_setup_cb_egdev_register"
      ]
    },
    {
      "addr": 18446744071587785197,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588198220,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
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
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_mfc_add"
      ]
    },
    {
      "addr": 18446744071588235913,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588464304,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp6_portaddr_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588612165,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582673760,
      "name": "jhash2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071583657744,
      "name": "jhash2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071587763712,
      "name": "jhash2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071587778928,
      "name": "jhash2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071588184304,
      "name": "jhash2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071588613047,
      "name": "jhash2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580057461,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:hash_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580750190,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581291321,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault_mutex_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330715,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582870758,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget",
        "ipc/util.c:ipc_addid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583879408,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587800059,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:skb_get_hash_perturb",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588111615,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_setup_cb_egdev_register",
        "net/sched/act_api.c:tcf_action_egdev_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588127597,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588187029,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip4_obj_hashfn",
        "net/ipv4/ip_fragment.c:ip4_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588224731,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588554935,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_mfc_add"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588590675,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588828574,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp_v6_rehash",
        "net/ipv6/udp.c:udp_v6_get_port",
        "net/ipv6/udp.c:udp_v6_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588873232,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_obj_hashfn",
        "net/ipv6/reassembly.c:ip6_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588933836,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588977987,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588989479,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
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
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580104629,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:hash_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580807965,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580814494,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581374233,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault_mutex_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582978777,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget",
        "ipc/util.c:ipc_addid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583962784,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587934977,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:skb_get_hash_perturb",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588288746,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:__tc_indr_block_cb_register",
        "net/sched/cls_api.c:tc_indr_block_dev_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588310445,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588376885,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip4_obj_hashfn",
        "net/ipv4/ip_fragment.c:ip4_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588412379,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588751751,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_mfc_add"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588797715,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588837949,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589051662,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp_v6_rehash",
        "net/ipv6/udp.c:udp_v6_get_port",
        "net/ipv6/udp.c:udp_v6_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589100858,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6frag_obj_hashfn",
        "net/ipv6/reassembly.c:ip6frag_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589157868,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589202019,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589213482,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
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
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580149605,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:hash_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580896509,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580903581,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581496270,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583159695,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584142544,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588244589,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:skb_get_hash_perturb",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588673552,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_indr_block_dev_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588708429,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588776757,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip4_obj_hashfn",
        "net/ipv4/ip_fragment.c:ip4_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588816072,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589228840,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589271519,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589504856,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp_v6_rehash",
        "net/ipv6/udp.c:udp_v6_get_port",
        "net/ipv6/udp.c:udp_v6_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589554170,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6frag_obj_hashfn",
        "net/ipv6/reassembly.c:ip6frag_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589655733,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589667034,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
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
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580197589,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:hash_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580949773,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580956765,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581560798,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583265759,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584264992,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588690272,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_indr_block_dev_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588932333,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589000357,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip4_obj_hashfn",
        "net/ipv4/ip_fragment.c:ip4_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589039419,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589454104,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589496495,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589728939,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp_v6_rehash",
        "net/ipv6/udp.c:udp_v6_get_port",
        "net/ipv6/udp.c:udp_v6_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589778202,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6frag_obj_hashfn",
        "net/ipv6/reassembly.c:ip6frag_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589880133,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589891293,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580265461,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:hash_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581120180,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581759509,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault_mutex_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584674800,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589820276,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589957029,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip4_obj_hashfn",
        "net/ipv4/ip_fragment.c:ip4_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590000738,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590445448,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer",
        "net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590489380,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590654628,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:__rt6_find_exception_spinlock",
        "net/ipv6/route.c:__rt6_find_exception_spinlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590747433,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590795306,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6frag_obj_hashfn",
        "net/ipv6/reassembly.c:ip6frag_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590919545,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580249413,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:hash_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581153061,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:__bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581807493,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault_mutex_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584791760,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589856836,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589997845,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip4_obj_hashfn",
        "net/ipv4/ip_fragment.c:ip4_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590043298,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590503544,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer",
        "net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590548779,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590713748,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:__rt6_find_exception_spinlock",
        "net/ipv6/route.c:__rt6_find_exception_spinlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590806409,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590854538,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6frag_obj_hashfn",
        "net/ipv6/reassembly.c:ip6frag_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590983129,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580254565,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:hash_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581168869,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:__bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581835461,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault_mutex_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584833739,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589764308,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589912053,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip4_obj_hashfn",
        "net/ipv4/ip_fragment.c:ip4_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589957225,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590428980,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer",
        "net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590474086,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590733447,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590783469,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6frag_obj_hashfn",
        "net/ipv6/reassembly.c:ip6frag_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590913783,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580405877,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:hash_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581407925,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:__bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582125701,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault_mutex_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585252843,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590523588,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590678501,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip4_obj_hashfn",
        "net/ipv4/ip_fragment.c:ip4_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590724395,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591227756,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer",
        "net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591277846,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591543111,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591601277,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6frag_obj_hashfn",
        "net/ipv6/reassembly.c:ip6frag_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591749575,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580623445,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:futex_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581617323,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/bpf/bloom_filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bloom_filter.c:bloom_map_peek_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581719184,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581731840,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:__bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582571557,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault_mutex_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584691872,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586094539,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586641666,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "lib/stackdepot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/stackdepot.c:__stack_depot_save"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592129636,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592305797,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip4_obj_hashfn",
        "net/ipv4/ip_fragment.c:ip4_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592354976,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592828280,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592890712,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer",
        "net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592944218,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593232681,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593297981,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6frag_obj_hashfn",
        "net/ipv6/reassembly.c:ip6frag_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593374758,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593437632,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593455833,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580889285,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:futex_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582001707,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/bpf/bloom_filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bloom_filter.c:bloom_map_peek_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582125984,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582139552,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:__bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582305552,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583091077,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault_mutex_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585382624,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587078075,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587885639,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "lib/stackdepot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/stackdepot.c:__stack_depot_save"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593955652,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594142149,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip4_obj_hashfn",
        "net/ipv4/ip_fragment.c:ip4_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594193945,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594204623,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594222717,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594706088,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594770619,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer",
        "net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594827400,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595133289,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595202029,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6frag_obj_hashfn",
        "net/ipv6/reassembly.c:ip6frag_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595286566,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595352608,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595372921,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580973125,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:futex_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582146180,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582192052,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/bpf/bloom_filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bloom_filter.c:hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582325174,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582336768,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:__bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582506867,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583301029,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault_mutex_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585613573,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_findkey"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587337019,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588157442,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "lib/stackdepot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/stackdepot.c:__stack_depot_save"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594332125,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594529269,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip4_obj_hashfn",
        "net/ipv4/ip_fragment.c:ip4_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594581081,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594591521,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594609833,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595098022,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595158049,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer",
        "net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595218819,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595537692,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_rehash",
        "net/ipv6/udp.c:udp_v6_get_port",
        "net/ipv6/udp.c:udp6_ehashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595593821,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6frag_obj_hashfn",
        "net/ipv6/reassembly.c:ip6frag_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595681746,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595752221,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595773018,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596226006,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/handshake/request.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/handshake/request.c:handshake_req_hash_lookup"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581067861,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:futex_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582294980,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582340948,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/bpf/bloom_filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bloom_filter.c:hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582486166,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582503024,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:__bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582675411,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583538261,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault_mutex_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585860293,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_findkey"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587620491,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588448362,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "lib/stackdepot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/stackdepot.c:stack_depot_save_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595131837,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595332005,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip4_obj_hashfn",
        "net/ipv4/ip_fragment.c:ip4_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595384089,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595395143,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595413460,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595910694,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596001073,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer",
        "net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596059363,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596380636,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_rehash",
        "net/ipv6/udp.c:udp_v6_get_port",
        "net/ipv6/udp.c:udp6_ehashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596436701,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6frag_obj_hashfn",
        "net/ipv6/reassembly.c:ip6frag_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596529506,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596600397,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596621513,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597104774,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:117",
      "file": "net/handshake/request.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/handshake/request.c:handshake_req_hash_lookup"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491427880,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:hash_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492294508,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492302292,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492994048,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494996440,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget",
        "ipc/util.c:ipc_addid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496146832,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502248852,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:__flow_indr_block_cb_register",
        "net/core/flow_offload.c:flow_indr_block_dev_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502523868,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502604908,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip4_obj_hashfn",
        "net/ipv4/ip_fragment.c:ip4_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502649732,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503049892,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503126740,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503164416,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503412520,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp_v6_rehash",
        "net/ipv6/udp.c:udp_v6_get_port",
        "net/ipv6/udp.c:udp_v6_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503479944,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6frag_obj_hashfn",
        "net/ipv6/reassembly.c:ip6frag_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503544400,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503598568,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503614456,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225423988,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:hash_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226187428,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229468364,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235240628,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 3235313884,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip4_obj_hashfn",
        "net/ipv4/ip_fragment.c:ip4_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 3235354480,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235791516,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel"
      ],
      "caller_func": []
    },
    {
      "addr": 3235836056,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 3236083084,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp_v6_rehash",
        "net/ipv6/udp.c:udp_v6_get_port",
        "net/ipv6/udp.c:udp_v6_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 3236130076,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6frag_obj_hashfn",
        "net/ipv6/reassembly.c:ip6frag_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236258296,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284376128,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:hash_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285527844,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285539084,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286416612,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288876960,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget",
        "ipc/util.c:ipc_addid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290406832,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295740876,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:__flow_indr_block_cb_register",
        "net/core/flow_offload.c:flow_indr_block_dev_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296104700,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296200488,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip4_obj_hashfn",
        "net/ipv4/ip_fragment.c:ip4_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296251728,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296758676,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296825216,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bydst_resize",
        "net/xfrm/xfrm_policy.c:xfrm_bydst_resize",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296884440,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297200128,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp_v6_rehash",
        "net/ipv6/udp.c:udp_v6_get_port",
        "net/ipv6/udp.c:udp_v6_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297264376,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6frag_obj_hashfn",
        "net/ipv6/reassembly.c:ip6frag_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297340696,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297411488,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297427884,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271894048,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:hash_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272425632,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272431724,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272897508,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274289634,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget",
        "ipc/util.c:ipc_addid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275201120,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278488008,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:__flow_indr_block_cb_register",
        "net/core/flow_offload.c:flow_indr_block_dev_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278699042,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278756716,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip4_obj_hashfn",
        "net/ipv4/ip_fragment.c:ip4_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278790460,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279119884,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279164482,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279205376,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279413464,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp_v6_rehash",
        "net/ipv6/udp.c:udp_v6_get_port",
        "net/ipv6/udp.c:udp_v6_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279454538,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6frag_obj_hashfn",
        "net/ipv6/reassembly.c:ip6frag_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279507918,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279553196,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279565034,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580166389,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:hash_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580918573,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580925565,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581529534,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583234495,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584233728,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588297008,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_indr_block_dev_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588538717,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588606741,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip4_obj_hashfn",
        "net/ipv4/ip_fragment.c:ip4_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588645803,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589058472,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589100863,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589333307,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp_v6_rehash",
        "net/ipv6/udp.c:udp_v6_get_port",
        "net/ipv6/udp.c:udp_v6_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589382570,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6frag_obj_hashfn",
        "net/ipv6/reassembly.c:ip6frag_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589484501,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589495661,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
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
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580114005,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:hash_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580864637,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580871629,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581471374,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583171647,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584168928,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588009824,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_indr_block_dev_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588250717,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588318725,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip4_obj_hashfn",
        "net/ipv4/ip_fragment.c:ip4_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588357787,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588783512,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588825903,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589058299,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp_v6_rehash",
        "net/ipv6/udp.c:udp_v6_get_port",
        "net/ipv6/udp.c:udp_v6_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589107562,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6frag_obj_hashfn",
        "net/ipv6/reassembly.c:ip6frag_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589209493,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589220653,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
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
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580157861,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:hash_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580909821,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_find_netdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580916813,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581520846,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583218527,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584217488,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588628832,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_indr_block_dev_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588870893,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588925482,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/netfilter/nf_conntrack_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_core.c:hash_conntrack_raw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588947338,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/netfilter/nf_conntrack_expect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_expect.c:nf_ct_expect_dst_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589042917,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip4_obj_hashfn",
        "net/ipv4/ip_fragment.c:ip4_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589081979,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589495336,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589537727,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589770171,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp_v6_rehash",
        "net/ipv6/udp.c:udp_v6_get_port",
        "net/ipv6/udp.c:udp_v6_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589819434,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6frag_obj_hashfn",
        "net/ipv6/reassembly.c:ip6frag_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589921365,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589926170,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/netfilter/nf_conntrack_reasm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter/nf_conntrack_reasm.c:ip6frag_obj_hashfn",
        "net/ipv6/netfilter/nf_conntrack_reasm.c:ip6frag_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589936925,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
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
  "name": "jhash2",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580211653,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:hash_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580968018,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/offload.c:bpf_prog_offload_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580976909,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581585814,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583312757,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget",
        "ipc/util.c:ipc_addid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584322160,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_jhash2"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588767259,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_indr_block_call",
        "net/core/flow_offload.c:__flow_indr_block_cb_unregister",
        "net/core/flow_offload.c:__flow_indr_block_cb_register",
        "net/core/flow_offload.c:__flow_indr_block_cb_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589012621,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:netlink_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589083413,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip4_obj_hashfn",
        "net/ipv4/ip_fragment.c:ip4_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589122123,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589496347,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_mfc_add"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589541976,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel",
        "net/xfrm/xfrm_policy.c:policy_hash_bysel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589585133,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_bump_genids",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589820875,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp_v6_rehash",
        "net/ipv6/udp.c:udp_v6_get_port",
        "net/ipv6/udp.c:udp_v6_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589867130,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6frag_obj_hashfn",
        "net/ipv6/reassembly.c:ip6frag_key_hashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589930008,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589975244,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_push_hmac",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589986413,
      "name": "jhash2",
      "external": false,
      "loc": "include/linux/jhash.h:116",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
u32 jhash2(const u32 * k, u32 length, u32 initval)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
u32 jhash2(const u32 * k, u32 length, u32 initval)
```
</details>
</li>
</ul>
