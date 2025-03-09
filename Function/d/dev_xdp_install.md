# Function: <code>dev_xdp_install</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587047543,
      "name": "dev_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:6965",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_xdp_fd"
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
  "name": "dev_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587548096,
      "name": "dev_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:7129",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_xdp_fd"
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
  "name": "dev_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587852013,
      "name": "dev_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:7301",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_xdp_uninstall",
        "net/core/dev.c:dev_xdp_uninstall"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dev_xdp_install(struct net_device * dev, bpf_op_t bpf_op, struct netlink_ext_ack * extack, u32 flags, struct bpf_prog * prog)
```

```json
{
  "name": "dev_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587996532,
      "name": "dev_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:7917",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:rollback_registered_many"
      ],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587941584,
      "name": "dev_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
int dev_xdp_install(struct net_device * dev, bpf_op_t bpf_op, struct netlink_ext_ack * extack, u32 flags, struct bpf_prog * prog)
```

```json
{
  "name": "dev_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588250704,
      "name": "dev_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:8014",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588250704,
      "name": "dev_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
int dev_xdp_install(struct net_device * dev, bpf_op_t bpf_op, struct netlink_ext_ack * extack, u32 flags, struct bpf_prog * prog)
```

```json
{
  "name": "dev_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588455920,
      "name": "dev_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:8313",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588455920,
      "name": "dev_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
int dev_xdp_install(struct net_device * dev, bpf_op_t bpf_op, struct netlink_ext_ack * extack, u32 flags, struct bpf_prog * prog)
```

```json
{
  "name": "dev_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589385223,
      "name": "dev_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:8726",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_xdp_uninstall"
      ],
      "caller_func": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_xdp_uninstall",
        "net/core/dev.c:dev_xdp_uninstall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589332528,
      "name": "dev_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
int dev_xdp_install(struct net_device * dev, enum bpf_xdp_mode mode, bpf_op_t bpf_op, struct netlink_ext_ack * extack, u32 flags, struct bpf_prog * prog)
```

```json
{
  "name": "dev_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589330160,
      "name": "dev_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:9099",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:bpf_xdp_link_update",
        "net/core/dev.c:dev_xdp_attach",
        "net/core/dev.c:dev_xdp_uninstall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589330160,
      "name": "dev_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
int dev_xdp_install(struct net_device * dev, enum bpf_xdp_mode mode, bpf_op_t bpf_op, struct netlink_ext_ack * extack, u32 flags, struct bpf_prog * prog)
```

```json
{
  "name": "dev_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589225520,
      "name": "dev_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:9358",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:bpf_xdp_link_update",
        "net/core/dev.c:bpf_xdp_link_release",
        "net/core/dev.c:dev_xdp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589225520,
      "name": "dev_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
int dev_xdp_install(struct net_device * dev, enum bpf_xdp_mode mode, bpf_op_t bpf_op, struct netlink_ext_ack * extack, u32 flags, struct bpf_prog * prog)
```

```json
{
  "name": "dev_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589947744,
      "name": "dev_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:9349",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:bpf_xdp_link_update",
        "net/core/dev.c:bpf_xdp_link_release",
        "net/core/dev.c:dev_xdp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589947744,
      "name": "dev_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
int dev_xdp_install(struct net_device * dev, enum bpf_xdp_mode mode, bpf_op_t bpf_op, struct netlink_ext_ack * extack, u32 flags, struct bpf_prog * prog)
```

```json
{
  "name": "dev_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591483360,
      "name": "dev_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:9087",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:bpf_xdp_link_update",
        "net/core/dev.c:bpf_xdp_link_release",
        "net/core/dev.c:dev_xdp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591483360,
      "name": "dev_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
int dev_xdp_install(struct net_device * dev, enum bpf_xdp_mode mode, bpf_op_t bpf_op, struct netlink_ext_ack * extack, u32 flags, struct bpf_prog * prog)
```

```json
{
  "name": "dev_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593251904,
      "name": "dev_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:9074",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:bpf_xdp_link_update",
        "net/core/dev.c:bpf_xdp_link_release",
        "net/core/dev.c:dev_xdp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593251904,
      "name": "dev_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
int dev_xdp_install(struct net_device * dev, enum bpf_xdp_mode mode, bpf_op_t bpf_op, struct netlink_ext_ack * extack, u32 flags, struct bpf_prog * prog)
```

```json
{
  "name": "dev_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593712752,
      "name": "dev_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:9082",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:bpf_xdp_link_update",
        "net/core/dev.c:bpf_xdp_link_release",
        "net/core/dev.c:dev_xdp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593712752,
      "name": "dev_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
int dev_xdp_install(struct net_device * dev, enum bpf_xdp_mode mode, bpf_op_t bpf_op, struct netlink_ext_ack * extack, u32 flags, struct bpf_prog * prog)
```

```json
{
  "name": "dev_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594491840,
      "name": "dev_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:9200",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:bpf_xdp_link_update",
        "net/core/dev.c:bpf_xdp_link_release",
        "net/core/dev.c:dev_xdp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594491840,
      "name": "dev_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
int dev_xdp_install(struct net_device * dev, bpf_op_t bpf_op, struct netlink_ext_ack * extack, u32 flags, struct bpf_prog * prog)
```

```json
{
  "name": "dev_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501981208,
      "name": "dev_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:8313",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501981208,
      "name": "dev_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int dev_xdp_install(struct net_device * dev, bpf_op_t bpf_op, struct netlink_ext_ack * extack, u32 flags, struct bpf_prog * prog)
```

```json
{
  "name": "dev_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234735032,
      "name": "dev_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:8313",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234735032,
      "name": "dev_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int dev_xdp_install(struct net_device * dev, bpf_op_t bpf_op, struct netlink_ext_ack * extack, u32 flags, struct bpf_prog * prog)
```

```json
{
  "name": "dev_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295409408,
      "name": "dev_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:8313",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295409408,
      "name": "dev_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int dev_xdp_install(struct net_device * dev, bpf_op_t bpf_op, struct netlink_ext_ack * extack, u32 flags, struct bpf_prog * prog)
```

```json
{
  "name": "dev_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278279418,
      "name": "dev_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:8313",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278279418,
      "name": "dev_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int dev_xdp_install(struct net_device * dev, bpf_op_t bpf_op, struct netlink_ext_ack * extack, u32 flags, struct bpf_prog * prog)
```

```json
{
  "name": "dev_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588062704,
      "name": "dev_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:8313",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588062704,
      "name": "dev_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
int dev_xdp_install(struct net_device * dev, bpf_op_t bpf_op, struct netlink_ext_ack * extack, u32 flags, struct bpf_prog * prog)
```

```json
{
  "name": "dev_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587775792,
      "name": "dev_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:8313",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587775792,
      "name": "dev_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
int dev_xdp_install(struct net_device * dev, bpf_op_t bpf_op, struct netlink_ext_ack * extack, u32 flags, struct bpf_prog * prog)
```

```json
{
  "name": "dev_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588394480,
      "name": "dev_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:8313",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588394480,
      "name": "dev_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
int dev_xdp_install(struct net_device * dev, bpf_op_t bpf_op, struct netlink_ext_ack * extack, u32 flags, struct bpf_prog * prog)
```

```json
{
  "name": "dev_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588530160,
      "name": "dev_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:8313",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588530160,
      "name": "dev_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int dev_xdp_install(struct net_device * dev, bpf_op_t bpf_op, struct netlink_ext_ack * extack, u32 flags, struct bpf_prog * prog)
```
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum bpf_xdp_mode mode</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, bpf_op, extack, flags, prog</code> ➡️ <code>dev, mode, bpf_op, extack, flags, prog</code>
</li>
</ul>
</details>
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
