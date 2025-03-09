# Function: <code>atomic_notifier_call_chain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579505840,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:190",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:exit_idle",
        "arch/x86/kernel/process.c:arch_cpu_idle_enter",
        "arch/x86/kernel/process.c:arch_cpu_idle_exit",
        "arch/x86/kernel/cpu/mcheck/mce.c:print_mce",
        "arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_process",
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_restart",
        "kernel/profile.c:profile_handoff_task",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/base/memory.c:memory_isolate_notify",
        "drivers/usb/phy/phy-generic.c:nop_gpio_vbus_thread",
        "drivers/usb/phy/phy-generic.c:nop_gpio_vbus_thread",
        "drivers/power/power_supply_core.c:power_supply_changed_work",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/netlink/af_netlink.c:netlink_release",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505840,
      "name": "atomic_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579520188,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:190",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:arch_cpu_idle_exit",
        "arch/x86/kernel/process.c:arch_cpu_idle_enter",
        "arch/x86/kernel/process.c:exit_idle",
        "arch/x86/kernel/cpu/mcheck/mce.c:print_mce",
        "arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_process",
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_restart",
        "kernel/profile.c:profile_handoff_task",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/base/memory.c:memory_isolate_notify",
        "drivers/power/power_supply_core.c:power_supply_changed_work",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/netlink/af_netlink.c:netlink_release",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519952,
      "name": "atomic_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579543836,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:190",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_process",
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_restart",
        "kernel/profile.c:profile_handoff_task",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/base/memory.c:memory_isolate_notify",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/ipv4/fib_trie.c:call_fib_entry_notifiers",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543600,
      "name": "atomic_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579530396,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:190",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_restart",
        "kernel/profile.c:profile_handoff_task",
        "security/security.c:call_lsm_notifier",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/base/memory.c:memory_isolate_notify",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/ipv4/fib_notifier.c:call_fib_notifiers",
        "net/ipv6/addrconf_core.c:inet6addr_validator_notifier_call_chain",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530160,
      "name": "atomic_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579556892,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:190",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_restart",
        "kernel/profile.c:profile_handoff_task",
        "security/security.c:call_lsm_notifier",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/base/memory.c:memory_isolate_notify",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/core/fib_notifier.c:call_fib_notifiers",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556656,
      "name": "atomic_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579585216,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:190",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_restart",
        "kernel/profile.c:profile_handoff_task",
        "security/security.c:call_lsm_notifier",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/base/memory.c:memory_isolate_notify",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/core/fib_notifier.c:call_fib_notifiers",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579584928,
      "name": "atomic_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579622416,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:190",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_restart",
        "kernel/profile.c:profile_handoff_task",
        "security/security.c:call_lsm_notifier",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/base/memory.c:memory_isolate_notify",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/core/fib_notifier.c:call_fib_notifiers",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579622128,
      "name": "atomic_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579646907,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:192",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_restart",
        "kernel/profile.c:profile_handoff_task",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/base/memory.c:memory_isolate_notify",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/core/fib_notifier.c:call_fib_notifiers",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579646704,
      "name": "atomic_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579684043,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:192",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_restart",
        "kernel/profile.c:profile_handoff_task",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/base/memory.c:memory_isolate_notify",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/core/fib_notifier.c:call_fib_notifiers",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683840,
      "name": "atomic_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579725456,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:180",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_restart",
        "kernel/profile.c:profile_handoff_task",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:lineevent_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_set_config",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init_notify",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_linkup",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/iommu/amd/iommu.c:amd_iommu_int_thread",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/core/fib_notifier.c:call_fib_notifiers",
        "net/ipv4/nexthop.c:__remove_nexthop_fib",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579725312,
      "name": "atomic_notifier_call_chain",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579703600,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:211",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_restart",
        "kernel/profile.c:profile_handoff_task",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init_notify",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_linkup",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/iommu/amd/iommu.c:amd_iommu_int_thread",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/core/fib_notifier.c:call_fib_notifiers",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579703440,
      "name": "atomic_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579710736,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:211",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_restart",
        "kernel/profile.c:profile_handoff_task",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init_notify",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_linkup",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/iommu/amd/iommu.c:amd_iommu_int_thread",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/core/fib_notifier.c:call_fib_notifiers",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579710576,
      "name": "atomic_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579788960,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:192",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_restart",
        "kernel/profile.c:profile_handoff_task",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init_notify",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_linkup",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/iommu/amd/iommu.c:amd_iommu_int_thread",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/core/fib_notifier.c:call_fib_notifiers",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788800,
      "name": "atomic_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579895603,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:219",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_power_off",
        "kernel/reboot.c:do_kernel_restart",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init_notify",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_linkup",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/iommu/amd/iommu.c:amd_iommu_int_thread",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/core/fib_notifier.c:call_fib_notifiers",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894944,
      "name": "atomic_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580046963,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:219",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_power_off",
        "kernel/reboot.c:do_kernel_restart",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init_notify",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_linkup",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/iommu/amd/iommu.c:amd_iommu_int_thread",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/core/fib_notifier.c:call_fib_notifiers",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046240,
      "name": "atomic_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580101342,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:225",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_power_off",
        "kernel/reboot.c:do_kernel_restart",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/iommu/amd/iommu.c:iommu_poll_ppr_log",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/core/fib_notifier.c:call_fib_notifiers",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580100912,
      "name": "atomic_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580146158,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:225",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_power_off",
        "kernel/reboot.c:do_kernel_restart",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/core/fib_notifier.c:call_fib_notifiers",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580145728,
      "name": "atomic_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490859324,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:192",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_restart",
        "kernel/profile.c:profile_handoff_task",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/base/memory.c:memory_isolate_notify",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work",
        "drivers/firmware/imx/imx-scu-irq.c:imx_scu_irq_work_handler",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/core/fib_notifier.c:call_fib_notifiers",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490858904,
      "name": "atomic_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224878972,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:192",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "arch/arm/kernel/process.c:copy_thread_tls",
        "arch/arm/kernel/process.c:flush_thread",
        "arch/arm/kernel/process.c:exit_thread",
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_restart",
        "kernel/profile.c:profile_handoff_task",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/usb/phy/phy-generic.c:nop_gpio_vbus_thread",
        "drivers/usb/phy/phy-generic.c:nop_gpio_vbus_thread",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work",
        "drivers/firmware/imx/imx-scu-irq.c:imx_scu_irq_work_handler",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/core/fib_notifier.c:call_fib_notifiers",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224878656,
      "name": "atomic_notifier_call_chain",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283689092,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:192",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "arch/powerpc/platforms/powernv/opal.c:opal_message_notify",
        "arch/powerpc/platforms/pseries/io_event_irq.c:ioei_interrupt",
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_restart",
        "kernel/profile.c:profile_handoff_task",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/base/memory.c:memory_isolate_notify",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/core/fib_notifier.c:call_fib_notifiers",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283688816,
      "name": "atomic_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271519342,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:192",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "arch/riscv/mm/sifive_l2_cache.c:l2_int_handler",
        "arch/riscv/mm/sifive_l2_cache.c:l2_int_handler",
        "arch/riscv/mm/sifive_l2_cache.c:l2_int_handler",
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_restart",
        "kernel/profile.c:profile_handoff_task",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/core/fib_notifier.c:call_fib_notifiers",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271517350,
      "name": "atomic_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579660363,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:192",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_restart",
        "kernel/profile.c:profile_handoff_task",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/base/memory.c:memory_isolate_notify",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/core/fib_notifier.c:call_fib_notifiers",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660160,
      "name": "atomic_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579588715,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:192",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_restart",
        "kernel/profile.c:profile_handoff_task",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/base/memory.c:memory_isolate_notify",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/core/fib_notifier.c:call_fib_notifiers",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588512,
      "name": "atomic_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579657627,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:192",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notify_die"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/reboot.c:do_kernel_restart",
        "kernel/profile.c:profile_handoff_task",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/base/memory.c:memory_isolate_notify",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/core/fib_notifier.c:call_fib_notifiers",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579657424,
      "name": "atomic_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int atomic_notifier_call_chain(struct atomic_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "atomic_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579691872,
      "name": "atomic_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:192",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/notifier.c:notify_die",
        "kernel/reboot.c:do_kernel_restart",
        "kernel/profile.c:profile_handoff_task",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/vt.c:vcs_scr_updated",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:lf",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/base/memory.c:memory_isolate_notify",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work",
        "net/core/netevent.c:call_netevent_notifiers",
        "net/core/fib_notifier.c:call_fib_notifiers",
        "net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain",
        "net/dcb/dcbevent.c:call_dcbevent_notifiers",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691872,
      "name": "atomic_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
