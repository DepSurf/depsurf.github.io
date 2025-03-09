# Function: <code>call_netdevice_notifiers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586269168,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:1653",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo"
      ],
      "caller_func": [
        "net/core/dev_addr_lists.c:dev_addr_add",
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586269168,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586740130,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:1657",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/dev_addr_lists.c:dev_addr_add",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/net-sysfs.c:change_tx_queue_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586695040,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586925922,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:1656",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/dev_addr_lists.c:dev_addr_add",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/net-sysfs.c:change_tx_queue_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586881264,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587051767,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:1690",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/dev_addr_lists.c:dev_addr_add",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/net-sysfs.c:change_tx_queue_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587005760,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587552720,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:1703",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/dev_addr_lists.c:dev_addr_add",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/net-sysfs.c:change_tx_queue_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587504496,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587822971,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:1747",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/dev_addr_lists.c:dev_addr_add",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587808640,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587956450,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:1763",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/dev_addr_lists.c:dev_addr_add",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587944288,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588271160,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:1773",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/dev_addr_lists.c:dev_addr_add",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588253808,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588477523,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:1691",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588458960,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589350385,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:2051",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_wait_allrefs",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:netdev_sync_lower_features",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/dev_addr_lists.c:dev_addr_add",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589326512,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589351953,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:2076",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_wait_allrefs",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:netdev_sync_lower_features",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/dev_addr_lists.c:dev_addr_add",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589325664,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589254333,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:2145",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/dev_addr_lists.c:dev_addr_add",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589221376,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589979869,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:2020",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/dev_addr_lists.c:dev_addr_add",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589949744,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591523259,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:1995",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:netdev_wait_allrefs_any",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/dev_addr_lists.c:dev_addr_add",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591485536,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593296827,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:1986",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:netdev_wait_allrefs_any",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/dev_addr_lists.c:dev_addr_add",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593254912,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593756528,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:2012",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:netdev_wait_allrefs_any",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/net_failover.c:net_failover_slave_register",
        "drivers/net/net_failover.c:net_failover_slave_register",
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/dev_addr_lists.c:dev_addr_add",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/xdp.c:xdp_features_clear_redirect_target",
        "net/core/xdp.c:xdp_features_set_redirect_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593754336,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594535051,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:2016",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:netdev_wait_allrefs_any",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/net_failover.c:net_failover_slave_register",
        "drivers/net/net_failover.c:net_failover_slave_register",
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/dev_addr_lists.c:dev_addr_add",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/xdp.c:xdp_features_clear_redirect_target",
        "net/core/xdp.c:xdp_features_set_redirect_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594532656,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502005568,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:1691",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501983984,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234761076,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:1691",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234738504,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295446280,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:1691",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295415024,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278296138,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:1691",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278282374,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588084307,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:1691",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588065744,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587797875,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:1691",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587778832,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588416083,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:1691",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588397520,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int call_netdevice_notifiers(long unsigned int val, struct net_device * dev)
```

```json
{
  "name": "call_netdevice_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588554723,
      "name": "call_netdevice_notifiers",
      "external": true,
      "loc": "net/core/dev.c:1691",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": [
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588533936,
      "name": "call_netdevice_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
