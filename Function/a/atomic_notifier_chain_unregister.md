# Function: <code>atomic_notifier_chain_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579506160,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:143",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:idle_notifier_unregister",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_unregister_decode_chain",
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/reboot.c:unregister_restart_handler",
        "kernel/profile.c:task_handoff_unregister",
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier",
        "drivers/base/memory.c:unregister_memory_isolate_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/power/power_supply_core.c:power_supply_unreg_notifier",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506160,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579520272,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:143",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:idle_notifier_unregister",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_unregister_decode_chain",
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/reboot.c:unregister_restart_handler",
        "kernel/profile.c:task_handoff_unregister",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier",
        "drivers/base/memory.c:unregister_memory_isolate_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/power/power_supply_core.c:power_supply_unreg_notifier",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579520272,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579543920,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:143",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_unregister_decode_chain",
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/reboot.c:unregister_restart_handler",
        "kernel/profile.c:task_handoff_unregister",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier",
        "drivers/base/memory.c:unregister_memory_isolate_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/ipv4/fib_trie.c:unregister_fib_notifier",
        "net/ipv4/fib_trie.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543920,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579530480,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:143",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/reboot.c:unregister_restart_handler",
        "kernel/profile.c:task_handoff_unregister",
        "security/security.c:unregister_lsm_notifier",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier",
        "drivers/base/memory.c:unregister_memory_isolate_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/ipv4/fib_notifier.c:unregister_fib_notifier",
        "net/ipv4/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530480,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556976,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:143",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/reboot.c:unregister_restart_handler",
        "kernel/profile.c:task_handoff_unregister",
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "security/security.c:unregister_lsm_notifier",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier",
        "drivers/base/memory.c:unregister_memory_isolate_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/core/fib_notifier.c:unregister_fib_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556976,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579585248,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:143",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/reboot.c:unregister_restart_handler",
        "kernel/profile.c:task_handoff_unregister",
        "security/security.c:unregister_lsm_notifier",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier",
        "drivers/base/memory.c:unregister_memory_isolate_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/core/fib_notifier.c:unregister_fib_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579585248,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579622448,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:143",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/reboot.c:unregister_restart_handler",
        "kernel/profile.c:task_handoff_unregister",
        "security/security.c:unregister_lsm_notifier",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier",
        "drivers/base/memory.c:unregister_memory_isolate_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/core/fib_notifier.c:unregister_fib_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579622448,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579647184,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:145",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/reboot.c:unregister_restart_handler",
        "kernel/profile.c:task_handoff_unregister",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier",
        "drivers/base/memory.c:unregister_memory_isolate_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/core/fib_notifier.c:unregister_fib_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579647184,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579684320,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:145",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/reboot.c:unregister_restart_handler",
        "kernel/profile.c:task_handoff_unregister",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier",
        "drivers/base/memory.c:unregister_memory_isolate_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/core/fib_notifier.c:unregister_fib_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684320,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579725093,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:133",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:unregister_die_notifier"
      ],
      "caller_func": [
        "kernel/reboot.c:unregister_restart_handler",
        "kernel/profile.c:task_handoff_unregister",
        "drivers/gpio/gpiolib.c:gpio_chrdev_release",
        "drivers/gpio/gpiolib.c:gpio_chrdev_open",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/iommu/amd/iommu.c:amd_iommu_unregister_ppr_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier",
        "drivers/remoteproc/remoteproc_core.c:rproc_exit_panic",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/core/fib_notifier.c:unregister_fib_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv4/nexthop.c:unregister_nexthop_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579723792,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579703231,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:161",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:unregister_die_notifier"
      ],
      "caller_func": [
        "kernel/reboot.c:unregister_restart_handler",
        "kernel/profile.c:task_handoff_unregister",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/iommu/amd/iommu.c:amd_iommu_unregister_ppr_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier",
        "drivers/remoteproc/remoteproc_core.c:rproc_exit_panic",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/core/fib_notifier.c:unregister_fib_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702192,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579710367,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:161",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:unregister_die_notifier"
      ],
      "caller_func": [
        "kernel/reboot.c:unregister_restart_handler",
        "kernel/profile.c:task_handoff_unregister",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/iommu/amd/iommu.c:amd_iommu_unregister_ppr_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier",
        "drivers/remoteproc/remoteproc_core.c:rproc_exit_panic",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/core/fib_notifier.c:unregister_fib_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579709328,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579788047,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:161",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:unregister_die_notifier"
      ],
      "caller_func": [
        "kernel/reboot.c:unregister_restart_handler",
        "kernel/profile.c:task_handoff_unregister",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/iommu/amd/iommu.c:amd_iommu_unregister_ppr_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier",
        "drivers/remoteproc/remoteproc_core.c:rproc_exit_panic",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/core/fib_notifier.c:unregister_fib_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787472,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579894589,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:188",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:unregister_die_notifier"
      ],
      "caller_func": [
        "kernel/reboot.c:unregister_sys_off_handler",
        "kernel/reboot.c:unregister_restart_handler",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/iommu/amd/iommu.c:amd_iommu_unregister_ppr_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier",
        "drivers/remoteproc/remoteproc_core.c:rproc_exit_panic",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/core/fib_notifier.c:unregister_fib_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893600,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580045837,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:188",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:unregister_die_notifier"
      ],
      "caller_func": [
        "kernel/reboot.c:unregister_sys_off_handler",
        "kernel/reboot.c:unregister_restart_handler",
        "drivers/acpi/apei/ghes.c:ghes_unregister_report_chain",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/iommu/amd/iommu.c:amd_iommu_unregister_ppr_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_exit",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/core/fib_notifier.c:unregister_fib_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580044736,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580102479,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:194",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:unregister_die_notifier"
      ],
      "caller_func": [
        "kernel/reboot.c:unregister_sys_off_handler",
        "kernel/reboot.c:unregister_restart_handler",
        "drivers/acpi/apei/ghes.c:ghes_unregister_report_chain",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/iommu/amd/iommu.c:amd_iommu_unregister_ppr_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_exit",
        "drivers/hv/hv_common.c:hv_common_free",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/core/fib_notifier.c:unregister_fib_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580101680,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580147295,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:194",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:unregister_die_notifier"
      ],
      "caller_func": [
        "kernel/reboot.c:unregister_sys_off_handler",
        "kernel/reboot.c:unregister_restart_handler",
        "drivers/acpi/apei/ghes.c:ghes_unregister_report_chain",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_exit",
        "drivers/hv/hv_common.c:hv_common_free",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/core/fib_notifier.c:unregister_fib_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146496,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490860936,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:145",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/reboot.c:unregister_restart_handler",
        "kernel/profile.c:task_handoff_unregister",
        "kernel/cpu_pm.c:cpu_pm_unregister_notifier",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/base/memory.c:unregister_memory_isolate_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove",
        "drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier",
        "drivers/firmware/imx/imx-scu-irq.c:imx_scu_irq_unregister_notifier",
        "drivers/mailbox/pl320-ipc.c:pl320_ipc_unregister_notifier",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/core/fib_notifier.c:unregister_fib_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490860936,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224879320,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:145",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/reboot.c:unregister_restart_handler",
        "kernel/profile.c:task_handoff_unregister",
        "kernel/cpu_pm.c:cpu_pm_unregister_notifier",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove",
        "drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier",
        "drivers/firmware/imx/imx-scu-irq.c:imx_scu_irq_unregister_notifier",
        "drivers/mailbox/pl320-ipc.c:pl320_ipc_unregister_notifier",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/core/fib_notifier.c:unregister_fib_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224879320,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283689568,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:145",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/opal.c:opal_message_notifier_unregister",
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/reboot.c:unregister_restart_handler",
        "kernel/profile.c:task_handoff_unregister",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/base/memory.c:unregister_memory_isolate_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove",
        "drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/core/fib_notifier.c:unregister_fib_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283689568,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271517908,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:145",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/mm/sifive_l2_cache.c:unregister_sifive_l2_error_notifier",
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/reboot.c:unregister_restart_handler",
        "kernel/profile.c:task_handoff_unregister",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove",
        "drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/core/fib_notifier.c:unregister_fib_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271517908,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660640,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:145",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/reboot.c:unregister_restart_handler",
        "kernel/profile.c:task_handoff_unregister",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier",
        "drivers/base/memory.c:unregister_memory_isolate_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/core/fib_notifier.c:unregister_fib_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660640,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588992,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:145",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/reboot.c:unregister_restart_handler",
        "kernel/profile.c:task_handoff_unregister",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier",
        "drivers/base/memory.c:unregister_memory_isolate_notifier",
        "drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier",
        "drivers/hv/vmbus_drv.c:vmbus_exit",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/core/fib_notifier.c:unregister_fib_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588992,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579657904,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:145",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/reboot.c:unregister_restart_handler",
        "kernel/profile.c:task_handoff_unregister",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier",
        "drivers/base/memory.c:unregister_memory_isolate_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/core/fib_notifier.c:unregister_fib_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579657904,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579691616,
      "name": "atomic_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:145",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/reboot.c:unregister_restart_handler",
        "kernel/profile.c:task_handoff_unregister",
        "drivers/tty/vt/keyboard.c:unregister_keyboard_notifier",
        "drivers/tty/vt/vt.c:unregister_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier",
        "drivers/base/memory.c:unregister_memory_isolate_notifier",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier",
        "net/core/netevent.c:unregister_netevent_notifier",
        "net/core/fib_notifier.c:unregister_fib_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_notifier",
        "net/dcb/dcbevent.c:unregister_dcbevent_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691616,
      "name": "atomic_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
