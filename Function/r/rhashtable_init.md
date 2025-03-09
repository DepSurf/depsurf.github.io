# Function: <code>rhashtable_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583040080,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:725",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583040080,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 736
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583333136,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:730",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583333136,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 722
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583458400,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:836",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/rhashtable.c:rhltable_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583458400,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 719
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583481152,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:930",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/rhashtable.c:rhltable_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583481152,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 591
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583662144,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:933",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init_ids",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/rhashtable.c:rhltable_init",
        "net/sched/act_api.c:tcf_action_net_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583662144,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 591
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583878064,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:1027",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init_ids",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/rhashtable.c:rhltable_init",
        "net/sched/act_api.c:tcf_action_net_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/ip_fragment.c:ipv4_frags_init_net",
        "net/ipv6/reassembly.c:ipv6_frags_init_net",
        "net/ipv6/seg6_hmac.c:seg6_hmac_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583878064,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583961440,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:1018",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_create",
        "ipc/util.c:ipc_init_ids",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/rhashtable.c:rhltable_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/ip_fragment.c:ipv4_frags_init_net",
        "net/ipv6/reassembly.c:ipv6_frags_init_net",
        "net/ipv6/seg6_hmac.c:seg6_hmac_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583961440,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584141136,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:1008",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_create",
        "ipc/util.c:ipc_init_ids",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/rhashtable.c:rhltable_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/inet_fragment.c:fqdir_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584141136,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584263584,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:1008",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_create",
        "ipc/util.c:ipc_init_ids",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/rhashtable.c:rhltable_init",
        "net/core/flow_offload.c:init_flow_indr_rhashtable",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/inet_fragment.c:fqdir_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584263584,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584670560,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:1015",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_create",
        "ipc/util.c:ipc_init_ids",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/rhashtable.c:rhltable_init",
        "net/core/xdp.c:xdp_rxq_info_reg_mem_model",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/inet_fragment.c:fqdir_init",
        "net/xfrm/xfrm_policy.c:xfrm_policy_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584670560,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 587
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584788176,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:1015",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_create",
        "ipc/util.c:ipc_init_ids",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/rhashtable.c:rhltable_init",
        "net/core/xdp.c:xdp_rxq_info_reg_mem_model",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/inet_fragment.c:fqdir_init",
        "net/xfrm/xfrm_policy.c:xfrm_policy_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584788176,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 587
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584831968,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:1015",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_create",
        "ipc/util.c:ipc_init_ids",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/rhashtable.c:rhltable_init",
        "net/core/xdp.c:xdp_rxq_info_reg_mem_model",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/inet_fragment.c:fqdir_init",
        "net/xfrm/xfrm_policy.c:xfrm_policy_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584831968,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:1015",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_create",
        "ipc/util.c:ipc_init_ids",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/rhashtable.c:rhltable_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/inet_fragment.c:fqdir_init",
        "net/ipv6/ioam6.c:ioam6_net_init",
        "net/ipv6/ioam6.c:ioam6_net_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592323980,
      "name": "rhashtable_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071585250928,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 605
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:1015",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_create",
        "ipc/util.c:ipc_init_ids",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/rhashtable.c:rhltable_init",
        "net/core/xdp.c:__xdp_reg_mem_model",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/inet_fragment.c:fqdir_init",
        "net/ipv6/ioam6.c:ioam6_net_init",
        "net/ipv6/ioam6.c:ioam6_net_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594128476,
      "name": "rhashtable_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071586093136,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:1019",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_create",
        "ipc/util.c:ipc_init_ids",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/rhashtable.c:rhltable_init",
        "net/core/xdp.c:__xdp_reg_mem_model",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/inet_fragment.c:fqdir_init",
        "net/ipv6/ioam6.c:ioam6_net_init",
        "net/ipv6/ioam6.c:ioam6_net_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596115400,
      "name": "rhashtable_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071587076592,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:1019",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_init",
        "ipc/util.c:ipc_init_ids",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/rhashtable.c:rhltable_init",
        "net/core/xdp.c:__xdp_reg_mem_model",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/inet_fragment.c:fqdir_init",
        "net/ipv6/ioam6.c:ioam6_net_init",
        "net/ipv6/ioam6.c:ioam6_net_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_net_init",
        "net/handshake/request.c:handshake_req_hash_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596641092,
      "name": "rhashtable_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071587335536,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:1019",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_init",
        "ipc/util.c:ipc_init_ids",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/rhashtable.c:rhltable_init",
        "net/core/xdp.c:__xdp_reg_mem_model",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/inet_fragment.c:fqdir_init",
        "net/ipv6/ioam6.c:ioam6_net_init",
        "net/ipv6/ioam6.c:ioam6_net_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_net_init",
        "net/handshake/request.c:handshake_req_hash_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597549157,
      "name": "rhashtable_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071587619008,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496144024,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:1008",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_create",
        "ipc/util.c:ipc_init_ids",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/rhashtable.c:rhltable_init",
        "net/core/flow_offload.c:init_flow_indr_rhashtable",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/inet_fragment.c:fqdir_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496144024,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229466100,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:1008",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_create",
        "ipc/util.c:ipc_init_ids",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/rhashtable.c:rhltable_init",
        "net/core/flow_offload.c:init_flow_indr_rhashtable",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/inet_fragment.c:fqdir_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229466100,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290406096,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:1008",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_create",
        "ipc/util.c:ipc_init_ids",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/rhashtable.c:rhltable_init",
        "net/core/flow_offload.c:init_flow_indr_rhashtable",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/inet_fragment.c:fqdir_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290406096,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 672
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275201474,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:1008",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_create",
        "ipc/util.c:ipc_init_ids",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/rhashtable.c:rhltable_init",
        "net/core/flow_offload.c:init_flow_indr_rhashtable",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/inet_fragment.c:fqdir_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275201474,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584232320,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:1008",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_create",
        "ipc/util.c:ipc_init_ids",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/rhashtable.c:rhltable_init",
        "net/core/flow_offload.c:init_flow_indr_rhashtable",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/inet_fragment.c:fqdir_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584232320,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584167520,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:1008",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_create",
        "ipc/util.c:ipc_init_ids",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/rhashtable.c:rhltable_init",
        "net/core/flow_offload.c:init_flow_indr_rhashtable",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/inet_fragment.c:fqdir_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584167520,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584216080,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:1008",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_create",
        "ipc/util.c:ipc_init_ids",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/rhashtable.c:rhltable_init",
        "net/core/flow_offload.c:init_flow_indr_rhashtable",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/inet_fragment.c:fqdir_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584216080,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
int rhashtable_init(struct rhashtable * ht, const struct rhashtable_params * params)
```

```json
{
  "name": "rhashtable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584321072,
      "name": "rhashtable_init",
      "external": true,
      "loc": "lib/rhashtable.c:1008",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_create",
        "ipc/util.c:ipc_init_ids",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/rhashtable.c:rhltable_init",
        "net/core/flow_offload.c:init_flow_indr_rhashtable",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/inet_fragment.c:fqdir_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584321072,
      "name": "rhashtable_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
