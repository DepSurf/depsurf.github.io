# Function: <code>netlink_kernel_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586489536,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2694",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586489536,
      "name": "netlink_kernel_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586945025,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1969",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586936128,
      "name": "netlink_kernel_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587140001,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1986",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587131360,
      "name": "netlink_kernel_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587270290,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2037",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587261760,
      "name": "netlink_kernel_release",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587790178,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2050",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587781152,
      "name": "netlink_kernel_release",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588132680,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2091",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588123584,
      "name": "netlink_kernel_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588315385,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2100",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588305840,
      "name": "netlink_kernel_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588713258,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2100",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588703760,
      "name": "netlink_kernel_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588937162,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2101",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588927632,
      "name": "netlink_kernel_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589828108,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2101",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/connector/connector.c:cn_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589816432,
      "name": "netlink_kernel_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589864476,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2102",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/connector/connector.c:cn_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589852608,
      "name": "netlink_kernel_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589770495,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2112",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/connector/connector.c:cn_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589758352,
      "name": "netlink_kernel_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590529839,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2123",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/connector/connector.c:cn_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590517504,
      "name": "netlink_kernel_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592134197,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2102",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/connector/connector.c:cn_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592125280,
      "name": "netlink_kernel_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593959973,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2123",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/connector/connector.c:cn_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593948272,
      "name": "netlink_kernel_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594336745,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2094",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/connector/connector.c:cn_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594324560,
      "name": "netlink_kernel_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595136081,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2089",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/connector/connector.c:cn_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595124128,
      "name": "netlink_kernel_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502534796,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2101",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502521184,
      "name": "netlink_kernel_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235243260,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2101",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235231984,
      "name": "netlink_kernel_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296108144,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2101",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296093904,
      "name": "netlink_kernel_release",
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
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278701008,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2101",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278691974,
      "name": "netlink_kernel_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588543546,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2101",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588534016,
      "name": "netlink_kernel_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588255530,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2101",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588246016,
      "name": "netlink_kernel_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588875722,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2101",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/netfilter/nfnetlink.c:nfnetlink_net_exit_batch",
        "net/ipv4/fib_frontend.c:fib_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588866192,
      "name": "netlink_kernel_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void netlink_kernel_release(struct sock * sk)
```

```json
{
  "name": "netlink_kernel_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589017674,
      "name": "netlink_kernel_release",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2101",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_kernel_create"
      ],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_exit",
        "net/core/rtnetlink.c:rtnetlink_net_exit",
        "net/core/sock_diag.c:diag_net_exit",
        "net/netlink/genetlink.c:genl_pernet_exit",
        "net/ipv4/fib_frontend.c:fib_net_exit",
        "lib/kobject_uevent.c:uevent_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589007680,
      "name": "netlink_kernel_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
