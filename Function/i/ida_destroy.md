# Function: <code>ida_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582950832,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:1059",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/rtc/class.c:rtc_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582950832,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583238496,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:1059",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit",
        "drivers/nvdimm/region_devs.c:nd_region_devs_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583238496,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583353648,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:1062",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit",
        "drivers/nvdimm/region_devs.c:nd_region_devs_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583353648,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588204400,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:396",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit",
        "drivers/nvdimm/region_devs.c:nd_region_devs_exit",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/thermal/thermal_core.c:thermal_exit",
        "drivers/thermal/thermal_core.c:thermal_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588204400,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588753296,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:404",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit",
        "drivers/nvdimm/region_devs.c:nd_region_devs_exit",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/thermal/thermal_core.c:thermal_exit",
        "drivers/thermal/thermal_core.c:thermal_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588753296,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589131568,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:534",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit",
        "drivers/nvdimm/region_devs.c:nd_region_devs_exit",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/thermal/thermal_core.c:thermal_exit",
        "drivers/thermal/thermal_core.c:thermal_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_core.c:watchdog_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589131568,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589365408,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:534",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/base/swnode.c:software_node_release",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit",
        "drivers/nvdimm/region_devs.c:nd_region_devs_exit",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/thermal/thermal_core.c:thermal_exit",
        "drivers/thermal/thermal_core.c:thermal_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_core.c:watchdog_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589365408,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589822560,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:545",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/base/swnode.c:software_node_release",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit",
        "drivers/nvdimm/region_devs.c:nd_region_devs_exit",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_core.c:watchdog_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589822560,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590050064,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:536",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/base/swnode.c:software_node_release",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit",
        "drivers/nvdimm/region_devs.c:nd_region_devs_exit",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_core.c:watchdog_exit",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590050064,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585042768,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:536",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/base/swnode.c:software_node_release",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_core.c:watchdog_exit",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585042768,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585194496,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:540",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/base/swnode.c:software_node_release",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_core.c:watchdog_exit",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585194496,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585077584,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:540",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/base/swnode.c:software_node_release",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_core.c:watchdog_exit",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585077584,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585524416,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:540",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/base/swnode.c:software_node_release",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_core.c:watchdog_exit",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585524416,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586677616,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:541",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/base/swnode.c:software_node_release",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_core.c:watchdog_exit",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586677616,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595757824,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:541",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/base/swnode.c:software_node_release",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_core.c:watchdog_exit",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595757824,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596282144,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:541",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/base/swnode.c:software_node_release",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_exit",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596282144,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597166848,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:541",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/base/swnode.c:software_node_release",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/gpu/drm/drm_connector.c:drm_connector_ida_destroy",
        "drivers/gpu/drm/drm_mode_config.c:drm_mode_config_cleanup",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_exit",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597166848,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503823544,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:536",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/base/swnode.c:software_node_release",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit",
        "drivers/nvdimm/region_devs.c:nd_region_devs_exit",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_core.c:watchdog_exit",
        "drivers/firmware/arm_scmi/bus.c:scmi_bus_exit",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503823544,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236446496,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:536",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/base/swnode.c:software_node_release",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_core.c:watchdog_exit",
        "drivers/firmware/arm_scmi/bus.c:scmi_bus_exit",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236446496,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297668752,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:536",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/base/swnode.c:software_node_release",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit",
        "drivers/nvdimm/region_devs.c:nd_region_devs_exit",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_core.c:watchdog_exit",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297668752,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279719872,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:536",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/base/swnode.c:software_node_release",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit",
        "drivers/nvdimm/region_devs.c:nd_region_devs_exit",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_core.c:watchdog_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279719872,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589652320,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:536",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/base/swnode.c:software_node_release",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit",
        "drivers/nvdimm/region_devs.c:nd_region_devs_exit",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/nvme/host/core.c:nvme_destroy_subsystem",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_core.c:watchdog_exit",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589652320,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589378128,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:536",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/base/swnode.c:software_node_release",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit",
        "drivers/nvdimm/region_devs.c:nd_region_devs_exit",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/nvme/host/core.c:nvme_destroy_subsystem",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_core.c:watchdog_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589378128,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590095696,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:536",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/base/swnode.c:software_node_release",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit",
        "drivers/nvdimm/region_devs.c:nd_region_devs_exit",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_core.c:watchdog_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590095696,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
void ida_destroy(struct ida * ida)
```

```json
{
  "name": "ida_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590145952,
      "name": "ida_destroy",
      "external": true,
      "loc": "lib/idr.c:536",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rcu_free_pool",
        "fs/devpts/inode.c:devpts_kill_sb",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/base/swnode.c:software_node_release",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit",
        "drivers/nvdimm/region_devs.c:nd_region_devs_exit",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_core.c:watchdog_exit",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590145952,
      "name": "ida_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
