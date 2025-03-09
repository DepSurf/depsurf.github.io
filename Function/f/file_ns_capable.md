# Function: <code>file_ns_capable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579411088,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:420",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_open",
        "fs/proc/task_mmu.c:pagemap_read",
        "net/core/sock.c:sk_ns_capable",
        "net/netlink/af_netlink.c:__netlink_ns_capable",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579411088,
      "name": "file_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579423168,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:446",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_open",
        "fs/proc/task_mmu.c:pagemap_read",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_ns_capable",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:__netlink_ns_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579423168,
      "name": "file_ns_capable",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579443568,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:447",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_open",
        "fs/proc/task_mmu.c:pagemap_read",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_ns_capable",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:__netlink_ns_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579443568,
      "name": "file_ns_capable",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579431712,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:447",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_open",
        "fs/proc/task_mmu.c:pagemap_read",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_ns_capable",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:__netlink_ns_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579431712,
      "name": "file_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579460064,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:448",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_open",
        "fs/proc/task_mmu.c:pagemap_read",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_ns_capable",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:__netlink_ns_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579460064,
      "name": "file_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579473632,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:448",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_open",
        "fs/proc/task_mmu.c:pagemap_read",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_ns_capable",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:__netlink_ns_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579473632,
      "name": "file_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579507312,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:449",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_open",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/base.c:proc_pid_stack",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_ns_capable",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:__netlink_ns_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507312,
      "name": "file_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579526304,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:466",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_open",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/base.c:proc_pid_stack",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_ns_capable",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:__netlink_ns_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579526304,
      "name": "file_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579552384,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:466",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/base.c:proc_pid_stack",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_ns_capable",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:__netlink_ns_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552384,
      "name": "file_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579584416,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:466",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/base.c:proc_pid_stack",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_net_capable",
        "net/core/sock.c:sk_capable",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579584416,
      "name": "file_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579564432,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:466",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/base.c:proc_pid_stack",
        "security/safesetid/securityfs.c:safesetid_gid_file_write",
        "security/safesetid/securityfs.c:safesetid_uid_file_write",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_net_capable",
        "net/core/sock.c:sk_capable",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564432,
      "name": "file_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579570000,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:466",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:map_write",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/base.c:proc_pid_stack",
        "security/safesetid/securityfs.c:safesetid_gid_file_write",
        "security/safesetid/securityfs.c:safesetid_uid_file_write",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_net_capable",
        "net/core/sock.c:sk_capable",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570000,
      "name": "file_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579641696,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:466",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:map_write",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/base.c:proc_pid_stack",
        "security/safesetid/securityfs.c:safesetid_gid_file_write",
        "security/safesetid/securityfs.c:safesetid_uid_file_write",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_net_capable",
        "net/core/sock.c:sk_capable",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641696,
      "name": "file_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579737072,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:467",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:map_write",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/base.c:proc_pid_stack",
        "security/safesetid/securityfs.c:safesetid_gid_file_write",
        "security/safesetid/securityfs.c:safesetid_uid_file_write",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_net_capable",
        "net/core/sock.c:sk_capable",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579737072,
      "name": "file_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579868032,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:467",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:map_write",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/base.c:proc_pid_stack",
        "security/safesetid/securityfs.c:safesetid_gid_file_write",
        "security/safesetid/securityfs.c:safesetid_uid_file_write",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_net_capable",
        "net/core/sock.c:sk_capable",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579868032,
      "name": "file_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579917968,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:453",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:map_write",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/base.c:proc_pid_stack",
        "security/safesetid/securityfs.c:safesetid_gid_file_write",
        "security/safesetid/securityfs.c:safesetid_uid_file_write",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_net_capable",
        "net/core/sock.c:sk_capable",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917968,
      "name": "file_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579957216,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:453",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:map_write",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/base.c:proc_pid_stack",
        "security/safesetid/securityfs.c:safesetid_gid_file_write",
        "security/safesetid/securityfs.c:safesetid_uid_file_write",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_net_capable",
        "net/core/sock.c:sk_capable",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579957216,
      "name": "file_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490703224,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:466",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/base.c:proc_pid_stack",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_ns_capable",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:__netlink_ns_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490703224,
      "name": "file_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224767944,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:466",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/base.c:proc_pid_stack",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_ns_capable",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:__netlink_ns_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224767944,
      "name": "file_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283527920,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:466",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/base.c:proc_pid_stack",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_ns_capable",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:__netlink_ns_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283527920,
      "name": "file_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271429516,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:466",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/base.c:proc_pid_stack",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_ns_capable",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:__netlink_ns_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271429516,
      "name": "file_ns_capable",
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
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579528688,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:466",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/base.c:proc_pid_stack",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_ns_capable",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:__netlink_ns_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579528688,
      "name": "file_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579457488,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:466",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/base.c:proc_pid_stack",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_ns_capable",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:__netlink_ns_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579457488,
      "name": "file_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579525968,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:466",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/base.c:proc_pid_stack",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_ns_capable",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:__netlink_ns_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525968,
      "name": "file_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool file_ns_capable(const struct file * file, struct user_namespace * ns, int cap)
```

```json
{
  "name": "file_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579558960,
      "name": "file_ns_capable",
      "external": true,
      "loc": "kernel/capability.c:466",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/base.c:proc_pid_stack",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "drivers/pci/pci-sysfs.c:pci_read_config",
        "net/core/sock.c:sk_ns_capable",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:__netlink_ns_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558960,
      "name": "file_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
