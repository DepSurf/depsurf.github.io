# Function: <code>netdev_err</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586291312,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:7619",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_push",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/core/dev.c:__netdev_update_features",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586291312,
      "name": "netdev_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586718544,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:8137",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_push",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "net/core/dev.c:__netdev_update_features",
        "net/core/net-sysfs.c:change_tx_queue_len",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586718544,
      "name": "netdev_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586905152,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:8302",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "net/core/dev.c:__netdev_update_features",
        "net/core/net-sysfs.c:change_tx_queue_len",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586905152,
      "name": "netdev_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587030208,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:8503",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "net/core/dev.c:__netdev_update_features",
        "net/core/net-sysfs.c:change_tx_queue_len",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587030208,
      "name": "netdev_err",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587528000,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:8686",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "net/core/dev.c:__netdev_update_features",
        "net/core/net-sysfs.c:change_tx_queue_len",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_dev_work",
        "net/ncsi/ncsi-manage.c:ncsi_enable_hwa",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587528000,
      "name": "netdev_err",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587826496,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:8937",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_dev_work",
        "net/ncsi/ncsi-manage.c:ncsi_enable_hwa",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587826496,
      "name": "netdev_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587962448,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:9570",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_dev_work",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587962448,
      "name": "netdev_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588310974,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:9675",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_dev_work",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588310974,
      "name": "netdev_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588517539,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:10026",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_dev_work",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588517539,
      "name": "netdev_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589391262,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:10486",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_probe_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589391262,
      "name": "netdev_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591628434,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:11195",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/xen-netfront.c:xennet_create_page_pool",
        "drivers/net/xen-netfront.c:xennet_create_page_pool",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_probe_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591628434,
      "name": "netdev_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591571864,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:11473",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/selftests.c:net_selftest",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_probe_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591571864,
      "name": "netdev_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592696925,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:11480",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/selftests.c:net_selftest",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_probe_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592696925,
      "name": "netdev_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594582828,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:11262",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:netdev_rx_csum_fault",
        "net/core/dev.c:dev_change_name",
        "net/core/selftests.c:net_selftest",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_vlan_rx_kill_vid",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_probe_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594582828,
      "name": "netdev_err",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593278656,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:11266",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:netdev_rx_csum_fault",
        "net/core/dev.c:dev_change_name",
        "net/core/selftests.c:net_selftest",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_vlan_rx_kill_vid",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_probe_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593278656,
      "name": "netdev_err",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593734496,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:11283",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_tx_timeout",
        "drivers/net/virtio_net.c:virtnet_set_ringparam",
        "drivers/net/virtio_net.c:virtnet_set_ringparam",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/net_failover.c:net_failover_slave_register",
        "drivers/net/net_failover.c:net_failover_slave_register",
        "drivers/net/net_failover.c:net_failover_slave_register",
        "drivers/net/net_failover.c:net_failover_slave_pre_register",
        "drivers/net/net_failover.c:net_failover_slave_pre_register",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_change_name",
        "net/core/dev_ioctl.c:dev_set_hwtstamp",
        "net/core/selftests.c:net_selftest",
        "net/core/failover.c:failover_slave_register",
        "net/core/failover.c:failover_slave_register",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_vlan_rx_kill_vid",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_probe_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593734496,
      "name": "netdev_err",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594513040,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:11511",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_tx_timeout",
        "drivers/net/virtio_net.c:virtnet_set_ringparam",
        "drivers/net/virtio_net.c:virtnet_set_ringparam",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/net_failover.c:net_failover_slave_register",
        "drivers/net/net_failover.c:net_failover_slave_register",
        "drivers/net/net_failover.c:net_failover_slave_register",
        "drivers/net/net_failover.c:net_failover_slave_pre_register",
        "drivers/net/net_failover.c:net_failover_slave_pre_register",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/core/dev.c:dev_change_name",
        "net/core/dev_ioctl.c:dev_set_hwtstamp",
        "net/core/dev_ioctl.c:dev_set_hwtstamp_phylib",
        "net/core/selftests.c:net_selftest",
        "net/core/failover.c:failover_slave_register",
        "net/core/failover.c:failover_slave_register",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_vlan_rx_kill_vid",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_probe_channel",
        "net/ncsi/ncsi-manage.c:ncsi_probe_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594513040,
      "name": "netdev_err",
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
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502052736,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:10026",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read",
        "drivers/net/ethernet/broadcom/bgmac-platform.c:bgmac_nicpm_speed_set",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mii_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mii_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue",
        "drivers/net/ethernet/freescale/fec_main.c:fec_stop",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/of/of_mdio.c:of_phy_get_and_connect",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_dev_work",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502052736,
      "name": "netdev_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234803812,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:10026",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mii_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mii_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue",
        "drivers/net/ethernet/freescale/fec_main.c:fec_stop",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/of/of_mdio.c:of_phy_get_and_connect",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_dev_work",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234803812,
      "name": "netdev_err",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295500772,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:10026",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/of/of_mdio.c:of_phy_get_and_connect",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_dev_work",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295500772,
      "name": "netdev_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278336612,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:10026",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/of/of_mdio.c:of_phy_get_and_connect",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_dev_work",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278336612,
      "name": "netdev_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588124275,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:10026",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_dev_work",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588124275,
      "name": "netdev_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587837107,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:10026",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_dev_work",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587837107,
      "name": "netdev_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588456099,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:10026",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_dev_work",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588456099,
      "name": "netdev_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void netdev_err(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588593095,
      "name": "netdev_err",
      "external": true,
      "loc": "net/core/dev.c:10026",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_change_tx_queue_len",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred",
        "net/switchdev/switchdev.c:switchdev_port_attr_set_deferred",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_dev_work",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588593095,
      "name": "netdev_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
