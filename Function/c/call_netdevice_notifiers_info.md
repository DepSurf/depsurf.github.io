# Function: <code>call_netdevice_notifiers_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct net_device * dev, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586269072,
      "name": "call_netdevice_notifiers_info",
      "external": false,
      "loc": "net/core/dev.c:1635",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:dev_set_mtu",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_change_features",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586269072,
      "name": "call_netdevice_notifiers_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int call_netdevice_notifiers_info(long unsigned int val, struct net_device * dev, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586694944,
      "name": "call_netdevice_notifiers_info",
      "external": false,
      "loc": "net/core/dev.c:1639",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586694944,
      "name": "call_netdevice_notifiers_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int call_netdevice_notifiers_info(long unsigned int val, struct net_device * dev, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586881168,
      "name": "call_netdevice_notifiers_info",
      "external": false,
      "loc": "net/core/dev.c:1638",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586881168,
      "name": "call_netdevice_notifiers_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int call_netdevice_notifiers_info(long unsigned int val, struct net_device * dev, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587005664,
      "name": "call_netdevice_notifiers_info",
      "external": false,
      "loc": "net/core/dev.c:1672",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587005664,
      "name": "call_netdevice_notifiers_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587504400,
      "name": "call_netdevice_notifiers_info",
      "external": false,
      "loc": "net/core/dev.c:1687",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587504400,
      "name": "call_netdevice_notifiers_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587808544,
      "name": "call_netdevice_notifiers_info",
      "external": false,
      "loc": "net/core/dev.c:1731",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587808544,
      "name": "call_netdevice_notifiers_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587944192,
      "name": "call_netdevice_notifiers_info",
      "external": false,
      "loc": "net/core/dev.c:1735",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587944192,
      "name": "call_netdevice_notifiers_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588253712,
      "name": "call_netdevice_notifiers_info",
      "external": false,
      "loc": "net/core/dev.c:1745",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588253712,
      "name": "call_netdevice_notifiers_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588458864,
      "name": "call_netdevice_notifiers_info",
      "external": false,
      "loc": "net/core/dev.c:1663",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588458864,
      "name": "call_netdevice_notifiers_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589326368,
      "name": "call_netdevice_notifiers_info",
      "external": false,
      "loc": "net/core/dev.c:2012",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589326368,
      "name": "call_netdevice_notifiers_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589325520,
      "name": "call_netdevice_notifiers_info",
      "external": false,
      "loc": "net/core/dev.c:2037",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589325520,
      "name": "call_netdevice_notifiers_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589221232,
      "name": "call_netdevice_notifiers_info",
      "external": false,
      "loc": "net/core/dev.c:2106",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589221232,
      "name": "call_netdevice_notifiers_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_netdevice_notifiers_info",
      "external": false,
      "loc": "net/core/dev.c:1981",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589949584,
      "name": "call_netdevice_notifiers_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071592695903,
      "name": "call_netdevice_notifiers_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_netdevice_notifiers_info",
      "external": false,
      "loc": "net/core/dev.c:1930",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_offload_xstats_get",
        "net/core/dev.c:netdev_offload_xstats_get_stats",
        "net/core/dev.c:netdev_offload_xstats_disable",
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591485376,
      "name": "call_netdevice_notifiers_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071594581601,
      "name": "call_netdevice_notifiers_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_netdevice_notifiers_info",
      "external": false,
      "loc": "net/core/dev.c:1921",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_offload_xstats_get",
        "net/core/dev.c:netdev_offload_xstats_get_stats",
        "net/core/dev.c:netdev_offload_xstats_disable",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593254736,
      "name": "call_netdevice_notifiers_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071596323299,
      "name": "call_netdevice_notifiers_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_netdevice_notifiers_info",
      "external": true,
      "loc": "net/core/dev.c:1947",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_offload_xstats_get",
        "net/core/dev.c:netdev_offload_xstats_get_stats",
        "net/core/dev.c:netdev_offload_xstats_disable",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596854267,
      "name": "call_netdevice_notifiers_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593753984,
      "name": "call_netdevice_notifiers_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_netdevice_notifiers_info",
      "external": true,
      "loc": "net/core/dev.c:1951",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_offload_xstats_get",
        "net/core/dev.c:netdev_offload_xstats_get_stats",
        "net/core/dev.c:netdev_offload_xstats_disable",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:__netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597779257,
      "name": "call_netdevice_notifiers_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071594532304,
      "name": "call_netdevice_notifiers_info",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501983856,
      "name": "call_netdevice_notifiers_info",
      "external": false,
      "loc": "net/core/dev.c:1663",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501983856,
      "name": "call_netdevice_notifiers_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234738368,
      "name": "call_netdevice_notifiers_info",
      "external": false,
      "loc": "net/core/dev.c:1663",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234738368,
      "name": "call_netdevice_notifiers_info",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295414848,
      "name": "call_netdevice_notifiers_info",
      "external": false,
      "loc": "net/core/dev.c:1663",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295414848,
      "name": "call_netdevice_notifiers_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278282254,
      "name": "call_netdevice_notifiers_info",
      "external": false,
      "loc": "net/core/dev.c:1663",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278282254,
      "name": "call_netdevice_notifiers_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588065648,
      "name": "call_netdevice_notifiers_info",
      "external": false,
      "loc": "net/core/dev.c:1663",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588065648,
      "name": "call_netdevice_notifiers_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587778736,
      "name": "call_netdevice_notifiers_info",
      "external": false,
      "loc": "net/core/dev.c:1663",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587778736,
      "name": "call_netdevice_notifiers_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588397424,
      "name": "call_netdevice_notifiers_info",
      "external": false,
      "loc": "net/core/dev.c:1663",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588397424,
      "name": "call_netdevice_notifiers_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info * info)
```

```json
{
  "name": "call_netdevice_notifiers_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588533840,
      "name": "call_netdevice_notifiers_info",
      "external": false,
      "loc": "net/core/dev.c:1663",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:netdev_bonding_info_change",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:netdev_notify_peers",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588533840,
      "name": "call_netdevice_notifiers_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct net_device * dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>val, dev, info</code> ➡️ <code>val, info</code>
</li>
</ul>
</details>
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
