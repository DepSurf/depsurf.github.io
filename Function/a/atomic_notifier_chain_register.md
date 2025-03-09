# Function: <code>atomic_notifier_chain_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505712,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:121",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:register_kernel_offset_dumper",
        "arch/x86/kernel/process.c:idle_notifier_register",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init",
        "kernel/notifier.c:register_die_notifier",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/update.c:check_cpu_stall_init",
        "kernel/profile.c:task_handoff_register",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/trace.c:trace_init",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier",
        "drivers/base/memory.c:register_memory_isolate_notifier",
        "drivers/power/power_supply_core.c:power_supply_reg_notifier",
        "net/core/netevent.c:register_netevent_notifier",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505712,
      "name": "atomic_notifier_chain_register",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579519824,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:121",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:register_kernel_offset_dumper",
        "arch/x86/kernel/process.c:idle_notifier_register",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init",
        "kernel/notifier.c:register_die_notifier",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/update.c:check_cpu_stall_init",
        "kernel/profile.c:task_handoff_register",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/trace.c:trace_init",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier",
        "drivers/base/memory.c:register_memory_isolate_notifier",
        "drivers/power/power_supply_core.c:power_supply_reg_notifier",
        "drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init",
        "net/core/netevent.c:register_netevent_notifier",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519824,
      "name": "atomic_notifier_chain_register",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579543472,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:121",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:register_kernel_offset_dumper",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_register_decode_chain",
        "kernel/notifier.c:register_die_notifier",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/update.c:check_cpu_stall_init",
        "kernel/profile.c:task_handoff_register",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/trace.c:trace_init",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier",
        "drivers/base/memory.c:register_memory_isolate_notifier",
        "drivers/power/supply/power_supply_core.c:power_supply_reg_notifier",
        "drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init",
        "net/core/netevent.c:register_netevent_notifier",
        "net/ipv4/fib_trie.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543472,
      "name": "atomic_notifier_chain_register",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579530032,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:121",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_panic_handler_init",
        "arch/x86/kernel/setup.c:register_kernel_offset_dumper",
        "kernel/notifier.c:register_die_notifier",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/update.c:check_cpu_stall_init",
        "kernel/profile.c:task_handoff_register",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/trace.c:early_trace_init",
        "security/security.c:register_lsm_notifier",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier",
        "drivers/base/memory.c:register_memory_isolate_notifier",
        "drivers/power/supply/power_supply_core.c:power_supply_reg_notifier",
        "drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init",
        "net/core/netevent.c:register_netevent_notifier",
        "net/ipv4/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530032,
      "name": "atomic_notifier_chain_register",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556528,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:121",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_panic_handler_init",
        "arch/x86/kernel/setup.c:register_kernel_offset_dumper",
        "kernel/notifier.c:register_die_notifier",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/update.c:check_cpu_stall_init",
        "kernel/profile.c:task_handoff_register",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/trace.c:early_trace_init",
        "security/security.c:register_lsm_notifier",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier",
        "drivers/base/memory.c:register_memory_isolate_notifier",
        "drivers/power/supply/power_supply_core.c:power_supply_reg_notifier",
        "drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init",
        "net/core/netevent.c:register_netevent_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556528,
      "name": "atomic_notifier_chain_register",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579584800,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:121",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_panic_handler_init",
        "arch/x86/kernel/setup.c:register_kernel_offset_dumper",
        "kernel/notifier.c:register_die_notifier",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/update.c:check_cpu_stall_init",
        "kernel/profile.c:task_handoff_register",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/trace.c:early_trace_init",
        "security/security.c:register_lsm_notifier",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier",
        "drivers/base/memory.c:register_memory_isolate_notifier",
        "drivers/power/supply/power_supply_core.c:power_supply_reg_notifier",
        "drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init",
        "net/core/netevent.c:register_netevent_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579584800,
      "name": "atomic_notifier_chain_register",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579622000,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:121",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_panic_handler_init",
        "arch/x86/kernel/setup.c:register_kernel_offset_dumper",
        "kernel/notifier.c:register_die_notifier",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/update.c:check_cpu_stall_init",
        "kernel/profile.c:task_handoff_register",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/trace.c:early_trace_init",
        "security/security.c:register_lsm_notifier",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier",
        "drivers/base/memory.c:register_memory_isolate_notifier",
        "drivers/power/supply/power_supply_core.c:power_supply_reg_notifier",
        "drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init",
        "net/core/netevent.c:register_netevent_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579622000,
      "name": "atomic_notifier_chain_register",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579647088,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:123",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_panic_handler_init",
        "arch/x86/kernel/setup.c:register_kernel_offset_dumper",
        "kernel/notifier.c:register_die_notifier",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/tree.c:check_cpu_stall_init",
        "kernel/profile.c:task_handoff_register",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier",
        "drivers/base/memory.c:register_memory_isolate_notifier",
        "drivers/power/supply/power_supply_core.c:power_supply_reg_notifier",
        "drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init",
        "net/core/netevent.c:register_netevent_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579647088,
      "name": "atomic_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579684224,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:123",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_panic_handler_init",
        "arch/x86/kernel/setup.c:register_kernel_offset_dumper",
        "kernel/notifier.c:register_die_notifier",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/tree.c:check_cpu_stall_init",
        "kernel/profile.c:task_handoff_register",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier",
        "drivers/base/memory.c:register_memory_isolate_notifier",
        "drivers/power/supply/power_supply_core.c:power_supply_reg_notifier",
        "drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init",
        "net/core/netevent.c:register_netevent_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684224,
      "name": "atomic_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579725013,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:111",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:register_die_notifier"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_panic_handler_init",
        "arch/x86/kernel/setup.c:register_kernel_offset_dumper",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/tree.c:check_cpu_stall_init",
        "kernel/profile.c:task_handoff_register",
        "kernel/hung_task.c:hung_task_init",
        "drivers/gpio/gpiolib.c:gpio_chrdev_open",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/iommu/amd/iommu.c:amd_iommu_register_ppr_notifier",
        "drivers/power/supply/power_supply_core.c:power_supply_reg_notifier",
        "drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_init",
        "net/core/netevent.c:register_netevent_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv4/nexthop.c:register_nexthop_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724160,
      "name": "atomic_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579703152,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:139",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:register_die_notifier"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_panic_handler_init",
        "arch/x86/kernel/setup.c:register_kernel_offset_dumper",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/tree.c:check_cpu_stall_init",
        "kernel/profile.c:task_handoff_register",
        "kernel/hung_task.c:hung_task_init",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/iommu/amd/iommu.c:amd_iommu_register_ppr_notifier",
        "drivers/power/supply/power_supply_core.c:power_supply_reg_notifier",
        "drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_init",
        "net/core/netevent.c:register_netevent_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702400,
      "name": "atomic_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579710288,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:139",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:register_die_notifier"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_panic_handler_init",
        "arch/x86/kernel/setup.c:register_kernel_offset_dumper",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/tree.c:check_cpu_stall_init",
        "kernel/profile.c:task_handoff_register",
        "kernel/hung_task.c:hung_task_init",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/iommu/amd/iommu.c:amd_iommu_register_ppr_notifier",
        "drivers/power/supply/power_supply_core.c:power_supply_reg_notifier",
        "drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_init",
        "net/core/netevent.c:register_netevent_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579709536,
      "name": "atomic_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579788373,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:139",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:register_die_notifier"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_panic_handler_init",
        "arch/x86/kernel/setup.c:register_kernel_offset_dumper",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/tree.c:check_cpu_stall_init",
        "kernel/profile.c:task_handoff_register",
        "kernel/hung_task.c:hung_task_init",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/iommu/amd/iommu.c:amd_iommu_register_ppr_notifier",
        "drivers/power/supply/power_supply_core.c:power_supply_reg_notifier",
        "drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_init",
        "net/core/netevent.c:register_netevent_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788240,
      "name": "atomic_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579895407,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:143",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:register_die_notifier"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_panic_handler_init",
        "arch/x86/kernel/setup.c:register_kernel_offset_dumper",
        "kernel/reboot.c:register_sys_off_handler",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/tree.c:check_cpu_stall_init",
        "kernel/hung_task.c:hung_task_init",
        "mm/kfence/core.c:kfence_init_enable",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/iommu/amd/iommu.c:amd_iommu_register_ppr_notifier",
        "drivers/power/supply/power_supply_core.c:power_supply_reg_notifier",
        "drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_init",
        "net/core/netevent.c:register_netevent_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895088,
      "name": "atomic_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580046751,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:143",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:register_die_notifier"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_panic_handler_init",
        "arch/x86/kernel/setup.c:register_kernel_offset_dumper",
        "kernel/reboot.c:register_sys_off_handler",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/tree.c:check_cpu_stall_init",
        "kernel/hung_task.c:hung_task_init",
        "mm/kfence/core.c:kfence_init_enable",
        "drivers/acpi/apei/ghes.c:ghes_register_report_chain",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/iommu/amd/iommu.c:amd_iommu_register_ppr_notifier",
        "drivers/power/supply/power_supply_core.c:power_supply_reg_notifier",
        "drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_init",
        "net/core/netevent.c:register_netevent_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046400,
      "name": "atomic_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580102367,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:149",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:register_die_notifier"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_panic_handler_init",
        "arch/x86/kernel/setup.c:register_kernel_offset_dumper",
        "kernel/reboot.c:register_sys_off_handler",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/tree.c:check_cpu_stall_init",
        "kernel/hung_task.c:hung_task_init",
        "mm/kfence/core.c:kfence_init_enable",
        "drivers/acpi/apei/ghes.c:ghes_register_report_chain",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/iommu/amd/iommu.c:amd_iommu_register_ppr_notifier",
        "drivers/power/supply/power_supply_core.c:power_supply_reg_notifier",
        "drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_init",
        "drivers/hv/hv_common.c:hv_common_init",
        "net/core/netevent.c:register_netevent_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580099824,
      "name": "atomic_notifier_chain_register",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580147183,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:149",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:register_die_notifier"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_panic_handler_init",
        "arch/x86/kernel/setup.c:register_kernel_offset_dumper",
        "kernel/reboot.c:register_sys_off_handler",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/tree.c:check_cpu_stall_init",
        "kernel/hung_task.c:hung_task_init",
        "mm/kfence/core.c:kfence_init_enable",
        "drivers/acpi/apei/ghes.c:ghes_register_report_chain",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_init",
        "drivers/hv/hv_common.c:hv_common_init",
        "net/core/netevent.c:register_netevent_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580144640,
      "name": "atomic_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490861368,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:123",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/setup.c:register_kernel_offset_dumper",
        "arch/arm64/kernel/cpufeature.c:register_cpu_hwcaps_dumper",
        "arch/arm64/mm/init.c:register_mem_limit_dumper",
        "kernel/notifier.c:register_die_notifier",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/tree.c:check_cpu_stall_init",
        "kernel/profile.c:task_handoff_register",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/cpu_pm.c:cpu_pm_register_notifier",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/base/memory.c:register_memory_isolate_notifier",
        "drivers/usb/phy/phy.c:devm_usb_get_phy_by_node",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_reg_notifier",
        "drivers/edac/altera_edac.c:altr_edac_a10_probe",
        "drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init",
        "drivers/firmware/imx/imx-scu-irq.c:imx_scu_irq_register_notifier",
        "drivers/mailbox/pl320-ipc.c:pl320_ipc_register_notifier",
        "net/core/netevent.c:register_netevent_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490861368,
      "name": "atomic_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224879216,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:123",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/vfp/vfpmodule.c:vfp_init",
        "arch/arm/kernel/thumbee.c:thumbee_init",
        "arch/arm/kernel/pj4-cp0.c:pj4_cp0_init",
        "kernel/notifier.c:register_die_notifier",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/tree.c:check_cpu_stall_init",
        "kernel/profile.c:task_handoff_register",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/cpu_pm.c:cpu_pm_register_notifier",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/usb/phy/phy.c:devm_usb_get_phy_by_node",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_reg_notifier",
        "drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init",
        "drivers/firmware/imx/imx-scu-irq.c:imx_scu_irq_register_notifier",
        "drivers/mailbox/pl320-ipc.c:pl320_ipc_register_notifier",
        "net/core/netevent.c:register_netevent_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224879216,
      "name": "atomic_notifier_chain_register",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283689408,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:123",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/setup-common.c:setup_panic",
        "kernel/notifier.c:register_die_notifier",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/tree.c:check_cpu_stall_init",
        "kernel/profile.c:task_handoff_register",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/base/memory.c:register_memory_isolate_notifier",
        "drivers/usb/phy/phy.c:devm_usb_get_phy_by_node",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_reg_notifier",
        "drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init",
        "net/core/netevent.c:register_netevent_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283689408,
      "name": "atomic_notifier_chain_register",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271517774,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:123",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/mm/sifive_l2_cache.c:register_sifive_l2_error_notifier",
        "kernel/notifier.c:register_die_notifier",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/tree.c:check_cpu_stall_init",
        "kernel/profile.c:task_handoff_register",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/usb/phy/phy.c:devm_usb_get_phy_by_node",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_reg_notifier",
        "drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init",
        "net/core/netevent.c:register_netevent_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271517774,
      "name": "atomic_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660544,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:123",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_panic_handler_init",
        "arch/x86/kernel/setup.c:register_kernel_offset_dumper",
        "kernel/notifier.c:register_die_notifier",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/tree.c:check_cpu_stall_init",
        "kernel/profile.c:task_handoff_register",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier",
        "drivers/base/memory.c:register_memory_isolate_notifier",
        "drivers/power/supply/power_supply_core.c:power_supply_reg_notifier",
        "net/core/netevent.c:register_netevent_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660544,
      "name": "atomic_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588896,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:123",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:register_kernel_offset_dumper",
        "kernel/notifier.c:register_die_notifier",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/tree.c:check_cpu_stall_init",
        "kernel/profile.c:task_handoff_register",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier",
        "drivers/base/memory.c:register_memory_isolate_notifier",
        "drivers/power/supply/power_supply_core.c:power_supply_reg_notifier",
        "drivers/hv/vmbus_drv.c:hv_acpi_init",
        "net/core/netevent.c:register_netevent_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588896,
      "name": "atomic_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579657808,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:123",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_panic_handler_init",
        "arch/x86/kernel/setup.c:register_kernel_offset_dumper",
        "kernel/notifier.c:register_die_notifier",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/tree.c:check_cpu_stall_init",
        "kernel/profile.c:task_handoff_register",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier",
        "drivers/base/memory.c:register_memory_isolate_notifier",
        "drivers/power/supply/power_supply_core.c:power_supply_reg_notifier",
        "drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init",
        "net/core/netevent.c:register_netevent_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579657808,
      "name": "atomic_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int atomic_notifier_chain_register(struct atomic_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "atomic_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579691520,
      "name": "atomic_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:123",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_panic_handler_init",
        "arch/x86/kernel/setup.c:register_kernel_offset_dumper",
        "kernel/notifier.c:register_die_notifier",
        "kernel/reboot.c:register_restart_handler",
        "kernel/rcu/tree.c:check_cpu_stall_init",
        "kernel/profile.c:task_handoff_register",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "drivers/tty/vt/keyboard.c:register_keyboard_notifier",
        "drivers/tty/vt/vt.c:register_vt_notifier",
        "drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier",
        "drivers/base/memory.c:register_memory_isolate_notifier",
        "drivers/power/supply/power_supply_core.c:power_supply_reg_notifier",
        "drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init",
        "net/core/netevent.c:register_netevent_notifier",
        "net/core/fib_notifier.c:register_fib_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_notifier",
        "net/dcb/dcbevent.c:register_dcbevent_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691520,
      "name": "atomic_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
