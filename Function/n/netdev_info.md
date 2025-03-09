# Function: <code>netdev_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586291744,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:7622",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586291744,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586718976,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:8140",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586718976,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586905584,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:8305",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_name",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586905584,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587030592,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:8506",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_name",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587030592,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587528384,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:8689",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_name",
        "net/sched/sch_api.c:qdisc_create",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587528384,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587826928,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:8940",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_name",
        "net/sched/sch_api.c:qdisc_create",
        "net/ncsi/ncsi-manage.c:ncsi_choose_active_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587826928,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587962880,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:9573",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_name",
        "net/sched/sch_api.c:qdisc_create",
        "net/ncsi/ncsi-manage.c:ncsi_choose_active_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587962880,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588311367,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:9678",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_name",
        "net/sched/sch_api.c:qdisc_create",
        "net/ncsi/ncsi-manage.c:ncsi_choose_active_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588311367,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588517932,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:10029",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_name",
        "net/sched/sch_api.c:qdisc_create",
        "net/ncsi/ncsi-manage.c:ncsi_choose_active_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588517932,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589391676,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:10489",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_print_status",
        "drivers/net/phy/phy.c:phy_print_status",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_flush",
        "net/core/dev.c:dev_change_name",
        "net/sched/sch_api.c:qdisc_create",
        "net/ncsi/ncsi-manage.c:ncsi_choose_active_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589391676,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591628848,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:11198",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_print_status",
        "drivers/net/phy/phy.c:phy_print_status",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_flush",
        "net/core/dev.c:dev_change_name",
        "net/sched/sch_api.c:qdisc_create",
        "net/ncsi/ncsi-manage.c:ncsi_choose_active_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591628848,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591572278,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:11476",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_print_status",
        "drivers/net/phy/phy.c:phy_print_status",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_flush",
        "net/core/dev.c:dev_change_name",
        "net/sched/sch_api.c:qdisc_create",
        "net/ncsi/ncsi-manage.c:ncsi_choose_active_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591572278,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592697339,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:11483",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_print_status",
        "drivers/net/phy/phy.c:phy_print_status",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_flush",
        "net/core/dev.c:dev_change_name",
        "net/core/rtnetlink.c:ndo_dflt_fdb_del",
        "net/core/rtnetlink.c:ndo_dflt_fdb_add",
        "net/core/rtnetlink.c:ndo_dflt_fdb_add",
        "net/sched/sch_api.c:qdisc_create",
        "net/ncsi/ncsi-manage.c:ncsi_choose_active_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592697339,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594583423,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:11265",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_print_status",
        "drivers/net/phy/phy.c:phy_print_status",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_flush",
        "net/core/dev.c:dev_change_name",
        "net/core/rtnetlink.c:ndo_dflt_fdb_del",
        "net/core/rtnetlink.c:ndo_dflt_fdb_add",
        "net/core/rtnetlink.c:ndo_dflt_fdb_add",
        "net/ncsi/ncsi-manage.c:ncsi_choose_active_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594583423,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593280256,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:11269",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_flush",
        "net/core/dev.c:dev_change_name",
        "net/core/rtnetlink.c:ndo_dflt_fdb_del",
        "net/core/rtnetlink.c:ndo_dflt_fdb_add",
        "net/core/rtnetlink.c:ndo_dflt_fdb_add",
        "net/core/rtnetlink.c:ndo_dflt_fdb_add",
        "net/sched/sch_api.c:qdisc_create",
        "net/ncsi/ncsi-manage.c:ncsi_choose_active_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593280256,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593736160,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:11286",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_flush",
        "drivers/net/net_failover.c:net_failover_slave_unregister",
        "drivers/net/net_failover.c:net_failover_slave_register",
        "net/core/dev.c:__dev_set_allmulti",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:dev_change_name",
        "net/core/rtnetlink.c:ndo_dflt_fdb_del",
        "net/core/rtnetlink.c:ndo_dflt_fdb_add",
        "net/core/rtnetlink.c:ndo_dflt_fdb_add",
        "net/core/rtnetlink.c:ndo_dflt_fdb_add",
        "net/core/failover.c:failover_unregister",
        "net/sched/sch_api.c:qdisc_create",
        "net/ncsi/ncsi-manage.c:ncsi_choose_active_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593736160,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594514704,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:11514",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_flush",
        "drivers/net/net_failover.c:net_failover_slave_unregister",
        "drivers/net/net_failover.c:net_failover_slave_register",
        "net/core/dev.c:__dev_set_allmulti",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:dev_change_name",
        "net/core/rtnetlink.c:ndo_dflt_fdb_del",
        "net/core/rtnetlink.c:ndo_dflt_fdb_add",
        "net/core/rtnetlink.c:ndo_dflt_fdb_add",
        "net/core/rtnetlink.c:ndo_dflt_fdb_add",
        "net/core/failover.c:failover_unregister",
        "net/sched/sch_api.c:qdisc_create",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gmcma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gmcma",
        "net/ncsi/ncsi-manage.c:ncsi_choose_active_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594514704,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502053180,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:10029",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mii_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_timeout",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_10bt_check_media",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "net/core/dev.c:dev_change_name",
        "net/sched/sch_api.c:qdisc_create",
        "net/ncsi/ncsi-manage.c:ncsi_choose_active_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502053180,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234804196,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:10029",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mii_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_timeout",
        "net/core/dev.c:dev_change_name",
        "net/sched/sch_api.c:qdisc_create",
        "net/ncsi/ncsi-manage.c:ncsi_choose_active_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234804196,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295501264,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:10029",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_name",
        "net/sched/sch_api.c:qdisc_create",
        "net/ncsi/ncsi-manage.c:ncsi_choose_active_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295501264,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278336888,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:10029",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_name",
        "net/sched/sch_api.c:qdisc_create",
        "net/ncsi/ncsi-manage.c:ncsi_choose_active_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278336888,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588124668,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:10029",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_name",
        "net/sched/sch_api.c:qdisc_create",
        "net/ncsi/ncsi-manage.c:ncsi_choose_active_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588124668,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587837500,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:10029",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/vxlan.c:vxlan_snoop",
        "net/core/dev.c:dev_change_name",
        "net/sched/sch_api.c:qdisc_create",
        "net/ncsi/ncsi-manage.c:ncsi_choose_active_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587837500,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588456492,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:10029",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_name",
        "net/sched/sch_api.c:qdisc_create",
        "net/ncsi/ncsi-manage.c:ncsi_choose_active_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588456492,
      "name": "netdev_info",
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
void netdev_info(const struct net_device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "netdev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588593488,
      "name": "netdev_info",
      "external": true,
      "loc": "net/core/dev.c:10029",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_name",
        "net/sched/sch_api.c:qdisc_create",
        "net/ncsi/ncsi-manage.c:ncsi_choose_active_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588593488,
      "name": "netdev_info",
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
