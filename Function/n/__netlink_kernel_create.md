# Function: <code>__netlink_kernel_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586501376,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2619",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "lib/kobject_uevent.c:uevent_net_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586501376,
      "name": "__netlink_kernel_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 601
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
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586944752,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1894",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "lib/kobject_uevent.c:uevent_net_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586944752,
      "name": "__netlink_kernel_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587139728,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1911",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "lib/kobject_uevent.c:uevent_net_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587139728,
      "name": "__netlink_kernel_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587270016,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1962",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init",
        "lib/kobject_uevent.c:uevent_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587270016,
      "name": "__netlink_kernel_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 607
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
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587789904,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1975",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init",
        "lib/kobject_uevent.c:uevent_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587789904,
      "name": "__netlink_kernel_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 607
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
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588132416,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2016",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init",
        "lib/kobject_uevent.c:uevent_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588132416,
      "name": "__netlink_kernel_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 607
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
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588314944,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2025",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init",
        "lib/kobject_uevent.c:uevent_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588314944,
      "name": "__netlink_kernel_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 659
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
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588712992,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2025",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init",
        "lib/kobject_uevent.c:uevent_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588712992,
      "name": "__netlink_kernel_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 611
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
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588936896,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2026",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init",
        "lib/kobject_uevent.c:uevent_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588936896,
      "name": "__netlink_kernel_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 611
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
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589827648,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2026",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "lib/kobject_uevent.c:uevent_net_init",
        "drivers/connector/connector.c:cn_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589827648,
      "name": "__netlink_kernel_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
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
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589864016,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2027",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "lib/kobject_uevent.c:uevent_net_init",
        "drivers/connector/connector.c:cn_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589864016,
      "name": "__netlink_kernel_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
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
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589770032,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2037",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "lib/kobject_uevent.c:uevent_net_init",
        "drivers/connector/connector.c:cn_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589770032,
      "name": "__netlink_kernel_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590529376,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2048",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "lib/kobject_uevent.c:uevent_net_init",
        "drivers/connector/connector.c:cn_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590529376,
      "name": "__netlink_kernel_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592133552,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2027",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "lib/kobject_uevent.c:uevent_net_init",
        "drivers/connector/connector.c:cn_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592133552,
      "name": "__netlink_kernel_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593959328,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2048",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "drivers/connector/connector.c:cn_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init",
        "lib/kobject_uevent.c:uevent_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593959328,
      "name": "__netlink_kernel_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594336112,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2021",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "drivers/connector/connector.c:cn_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init",
        "lib/kobject_uevent.c:uevent_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594336112,
      "name": "__netlink_kernel_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 684
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
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595135440,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2015",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "drivers/connector/connector.c:cn_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init",
        "lib/kobject_uevent.c:uevent_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595135440,
      "name": "__netlink_kernel_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502534536,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2026",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init",
        "lib/kobject_uevent.c:uevent_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502534536,
      "name": "__netlink_kernel_create",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235242980,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2026",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init",
        "lib/kobject_uevent.c:uevent_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235242980,
      "name": "__netlink_kernel_create",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296107824,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2026",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init",
        "lib/kobject_uevent.c:uevent_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296107824,
      "name": "__netlink_kernel_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 820
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
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278700778,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2026",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init",
        "lib/kobject_uevent.c:uevent_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278700778,
      "name": "__netlink_kernel_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588543280,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2026",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init",
        "lib/kobject_uevent.c:uevent_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588543280,
      "name": "__netlink_kernel_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 611
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
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588255264,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2026",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init",
        "lib/kobject_uevent.c:uevent_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588255264,
      "name": "__netlink_kernel_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 611
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
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588875456,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2026",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init",
        "net/netfilter/nfnetlink.c:nfnetlink_net_init",
        "lib/kobject_uevent.c:uevent_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588875456,
      "name": "__netlink_kernel_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 611
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
struct sock * __netlink_kernel_create(struct net * net, int unit, struct module * module, struct netlink_kernel_cfg * cfg)
```

```json
{
  "name": "__netlink_kernel_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589017408,
      "name": "__netlink_kernel_create",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2026",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "security/selinux/netlink.c:selnl_init",
        "drivers/scsi/scsi_netlink.c:scsi_netlink_init",
        "net/core/rtnetlink.c:rtnetlink_net_init",
        "net/core/sock_diag.c:diag_net_init",
        "net/netlink/genetlink.c:genl_pernet_init",
        "lib/kobject_uevent.c:uevent_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589017408,
      "name": "__netlink_kernel_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 611
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
