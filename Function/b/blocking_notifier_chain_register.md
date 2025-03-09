# Function: <code>blocking_notifier_chain_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579506752,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:213",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:register_reboot_notifier",
        "kernel/power/qos.c:pm_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "kernel/padata.c:padata_register_cpumask_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/acpi/event.c:register_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_register",
        "drivers/acpi/hed.c:register_acpi_hed_notifier",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/iommu/iommu.c:iommu_group_register_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_global_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/memory.c:register_memory_notifier",
        "drivers/mfd/da903x.c:da903x_register_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_register",
        "drivers/mfd/adp5520.c:adp5520_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "net/ipv4/devinet.c:register_inetaddr_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506752,
      "name": "blocking_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579520864,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:213",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:register_reboot_notifier",
        "kernel/power/qos.c:pm_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "kernel/padata.c:padata_register_cpumask_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_register",
        "drivers/acpi/event.c:register_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_register",
        "drivers/acpi/hed.c:register_acpi_hed_notifier",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/iommu/iommu.c:iommu_group_register_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_global_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/memory.c:register_memory_notifier",
        "drivers/mfd/da903x.c:da903x_register_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_register",
        "drivers/mfd/adp5520.c:adp5520_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "net/ipv4/devinet.c:register_inetaddr_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579520864,
      "name": "blocking_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579544512,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:213",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:register_reboot_notifier",
        "kernel/power/qos.c:pm_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "kernel/padata.c:padata_register_cpumask_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_register",
        "drivers/acpi/event.c:register_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_register",
        "drivers/acpi/hed.c:register_acpi_hed_notifier",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/iommu/iommu.c:iommu_group_register_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_global_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/memory.c:register_memory_notifier",
        "drivers/mfd/da903x.c:da903x_register_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_register",
        "drivers/mfd/adp5520.c:adp5520_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv4/devinet.c:register_inetaddr_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544512,
      "name": "blocking_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579530944,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:213",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_register_decode_chain",
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_register_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier",
        "kernel/reboot.c:register_reboot_notifier",
        "kernel/power/qos.c:pm_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "kernel/padata.c:padata_register_cpumask_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_register",
        "drivers/acpi/event.c:register_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_register",
        "drivers/acpi/hed.c:register_acpi_hed_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/iommu/iommu.c:iommu_group_register_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/memory.c:register_memory_notifier",
        "drivers/mfd/da903x.c:da903x_register_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_register",
        "drivers/mfd/adp5520.c:adp5520_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv4/devinet.c:register_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:register_inetaddr_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530944,
      "name": "blocking_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579557440,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:213",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_register_decode_chain",
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_register_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/power/qos.c:pm_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "kernel/padata.c:padata_register_cpumask_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_register",
        "drivers/acpi/event.c:register_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_register",
        "drivers/acpi/hed.c:register_acpi_hed_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/iommu/iommu.c:iommu_group_register_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/memory.c:register_memory_notifier",
        "drivers/mfd/da903x.c:da903x_register_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_register",
        "drivers/mfd/adp5520.c:adp5520_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv4/devinet.c:register_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:register_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579557440,
      "name": "blocking_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579585712,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:213",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_register_decode_chain",
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_register_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/power/qos.c:pm_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "kernel/padata.c:padata_register_cpumask_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_register",
        "drivers/acpi/event.c:register_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_register",
        "drivers/acpi/hed.c:register_acpi_hed_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/iommu/iommu.c:iommu_group_register_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/memory.c:register_memory_notifier",
        "drivers/mfd/da903x.c:da903x_register_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_register",
        "drivers/mfd/adp5520.c:adp5520_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv4/devinet.c:register_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:register_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579585712,
      "name": "blocking_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579622912,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:213",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_register_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/power/qos.c:pm_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "kernel/padata.c:padata_register_cpumask_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_register",
        "drivers/acpi/event.c:register_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_register",
        "drivers/acpi/hed.c:register_acpi_hed_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/iommu/iommu.c:iommu_group_register_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/memory.c:register_memory_notifier",
        "drivers/mfd/da903x.c:da903x_register_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_register",
        "drivers/mfd/adp5520.c:adp5520_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/nvmem/core.c:nvmem_register_notifier",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv4/devinet.c:register_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:register_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:register_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579622912,
      "name": "blocking_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579647344,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:215",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_register_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/power/qos.c:pm_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "kernel/padata.c:padata_register_cpumask_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "security/security.c:register_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_register",
        "drivers/acpi/event.c:register_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_register",
        "drivers/acpi/hed.c:register_acpi_hed_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/iommu/iommu.c:iommu_group_register_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/memory.c:register_memory_notifier",
        "drivers/mfd/da903x.c:da903x_register_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_register",
        "drivers/mfd/adp5520.c:adp5520_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/nvmem/core.c:nvmem_register_notifier",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv4/devinet.c:register_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:register_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:register_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579647344,
      "name": "blocking_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579684480,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:215",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_register_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/power/qos.c:pm_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "kernel/padata.c:padata_register_cpumask_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "security/security.c:register_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_register",
        "drivers/acpi/event.c:register_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_register",
        "drivers/acpi/hed.c:register_acpi_hed_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/iommu/iommu.c:iommu_group_register_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/memory.c:register_memory_notifier",
        "drivers/mfd/da903x.c:da903x_register_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_register",
        "drivers/mfd/adp5520.c:adp5520_register_notifier",
        "drivers/vfio/vfio.c:vfio_register_notifier",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/nvmem/core.c:nvmem_register_notifier",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv4/devinet.c:register_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:register_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:register_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684480,
      "name": "blocking_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579724256,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:203",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/power/qos.c:freq_qos_add_notifier",
        "kernel/power/qos.c:freq_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "security/security.c:register_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_register",
        "drivers/acpi/event.c:register_acpi_notifier",
        "drivers/acpi/hed.c:register_acpi_hed_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/iommu/iommu.c:iommu_group_register_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/memory.c:register_memory_notifier",
        "drivers/mfd/da903x.c:da903x_register_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_register",
        "drivers/mfd/adp5520.c:adp5520_register_notifier",
        "drivers/vfio/vfio.c:vfio_register_notifier",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/nvmem/core.c:nvmem_register_notifier",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv4/devinet.c:register_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:register_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:register_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724256,
      "name": "blocking_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579702496,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:240",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_register_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/power/qos.c:freq_qos_add_notifier",
        "kernel/power/qos.c:freq_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "security/security.c:register_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_register",
        "drivers/acpi/event.c:register_acpi_notifier",
        "drivers/acpi/hed.c:register_acpi_hed_notifier",
        "drivers/acpi/apei/ghes.c:ghes_register_vendor_record_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/iommu/iommu.c:iommu_group_register_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/memory.c:register_memory_notifier",
        "drivers/mfd/da903x.c:da903x_register_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_register",
        "drivers/mfd/adp5520.c:adp5520_register_notifier",
        "drivers/vfio/vfio.c:vfio_register_notifier",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/nvmem/core.c:nvmem_register_notifier",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv4/devinet.c:register_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:register_inetaddr_notifier",
        "net/ipv4/nexthop.c:register_nexthop_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:register_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702496,
      "name": "blocking_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579709632,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:240",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_register_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/power/qos.c:freq_qos_add_notifier",
        "kernel/power/qos.c:freq_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "security/security.c:register_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_register",
        "drivers/acpi/event.c:register_acpi_notifier",
        "drivers/acpi/hed.c:register_acpi_hed_notifier",
        "drivers/acpi/apei/ghes.c:ghes_register_vendor_record_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/iommu/iommu.c:iommu_group_register_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/memory.c:register_memory_notifier",
        "drivers/mfd/da903x.c:da903x_register_notifier",
        "drivers/mfd/adp5520.c:adp5520_register_notifier",
        "drivers/vfio/vfio.c:vfio_register_notifier",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/nvmem/core.c:nvmem_register_notifier",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv4/devinet.c:register_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:register_inetaddr_notifier",
        "net/ipv4/nexthop.c:register_nexthop_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:register_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579709632,
      "name": "blocking_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579788512,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:221",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_register_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/power/qos.c:freq_qos_add_notifier",
        "kernel/power/qos.c:freq_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "security/security.c:register_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_register",
        "drivers/acpi/event.c:register_acpi_notifier",
        "drivers/acpi/hed.c:register_acpi_hed_notifier",
        "drivers/acpi/apei/ghes.c:ghes_register_vendor_record_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/iommu/iommu.c:iommu_group_register_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/memory.c:register_memory_notifier",
        "drivers/mfd/da903x.c:da903x_register_notifier",
        "drivers/mfd/adp5520.c:adp5520_register_notifier",
        "drivers/vfio/vfio.c:vfio_register_notifier",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/nvmem/core.c:nvmem_register_notifier",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv4/devinet.c:register_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:register_inetaddr_notifier",
        "net/ipv4/nexthop.c:register_nexthop_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:register_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788512,
      "name": "blocking_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579894448,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:281",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_register_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier",
        "kernel/reboot.c:register_sys_off_handler",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/power/qos.c:freq_qos_add_notifier",
        "kernel/power/qos.c:freq_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module/main.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "security/security.c:register_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_register",
        "drivers/acpi/event.c:register_acpi_notifier",
        "drivers/acpi/hed.c:register_acpi_hed_notifier",
        "drivers/acpi/apei/ghes.c:ghes_register_vendor_record_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/char/random.c:register_random_vmfork_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/memory.c:register_memory_notifier",
        "drivers/mfd/da903x.c:da903x_register_notifier",
        "drivers/mfd/adp5520.c:adp5520_register_notifier",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/nvmem/core.c:nvmem_register_notifier",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv4/devinet.c:register_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:register_inetaddr_notifier",
        "net/ipv4/nexthop.c:register_nexthop_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:register_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894448,
      "name": "blocking_notifier_chain_register",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580045680,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:281",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier",
        "kernel/reboot.c:register_sys_off_handler",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/power/qos.c:freq_qos_add_notifier",
        "kernel/power/qos.c:freq_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module/main.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "security/security.c:register_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_register",
        "drivers/acpi/event.c:register_acpi_notifier",
        "drivers/acpi/hed.c:register_acpi_hed_notifier",
        "drivers/acpi/apei/ghes.c:ghes_register_vendor_record_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/char/random.c:register_random_vmfork_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/memory.c:register_memory_notifier",
        "drivers/mfd/da903x.c:da903x_register_notifier",
        "drivers/mfd/adp5520.c:adp5520_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/nvmem/core.c:nvmem_register_notifier",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv4/devinet.c:register_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:register_inetaddr_notifier",
        "net/ipv4/nexthop.c:register_nexthop_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:register_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580045680,
      "name": "blocking_notifier_chain_register",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580102048,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:287",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier",
        "kernel/reboot.c:register_sys_off_handler",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/power/qos.c:freq_qos_add_notifier",
        "kernel/power/qos.c:freq_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module/main.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "security/security.c:register_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_register",
        "drivers/acpi/event.c:register_acpi_notifier",
        "drivers/acpi/hed.c:register_acpi_hed_notifier",
        "drivers/acpi/apei/ghes.c:ghes_register_vendor_record_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/char/random.c:register_random_vmfork_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/memory.c:register_memory_notifier",
        "drivers/mfd/da903x.c:da903x_register_notifier",
        "drivers/mfd/adp5520.c:adp5520_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/nvmem/core.c:nvmem_register_notifier",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv4/devinet.c:register_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:register_inetaddr_notifier",
        "net/ipv4/nexthop.c:register_nexthop_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:register_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580102048,
      "name": "blocking_notifier_chain_register",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580146864,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:287",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier",
        "kernel/reboot.c:register_sys_off_handler",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/power/qos.c:freq_qos_add_notifier",
        "kernel/power/qos.c:freq_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module/main.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "mm/memory-tiers.c:register_mt_adistance_algorithm",
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "security/security.c:register_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_register",
        "drivers/acpi/event.c:register_acpi_notifier",
        "drivers/acpi/hed.c:register_acpi_hed_notifier",
        "drivers/acpi/apei/ghes.c:ghes_register_vendor_record_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/char/random.c:register_random_vmfork_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/memory.c:register_memory_notifier",
        "drivers/mfd/da903x.c:da903x_register_notifier",
        "drivers/mfd/adp5520.c:adp5520_register_notifier",
        "drivers/gpu/drm/drm_privacy_screen.c:drm_privacy_screen_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "drivers/power/supply/power_supply_core.c:power_supply_reg_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/platform/x86/amd/wbrf.c:amd_wbrf_register_notifier",
        "drivers/nvmem/core.c:nvmem_register_notifier",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv4/devinet.c:register_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:register_inetaddr_notifier",
        "net/ipv4/nexthop.c:register_nexthop_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:register_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146864,
      "name": "blocking_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490859616,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:215",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/power/qos.c:pm_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "kernel/padata.c:padata_register_cpumask_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "security/security.c:register_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_register",
        "drivers/acpi/event.c:register_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_register",
        "drivers/acpi/hed.c:register_acpi_hed_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/iommu/iommu.c:iommu_group_register_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/memory.c:register_memory_notifier",
        "drivers/mfd/da903x.c:da903x_register_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_register",
        "drivers/mfd/adp5520.c:adp5520_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/of/dynamic.c:of_reconfig_notifier_register",
        "drivers/of/overlay.c:of_overlay_notifier_register",
        "drivers/nvmem/core.c:nvmem_register_notifier",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv4/devinet.c:register_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:register_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:register_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490859616,
      "name": "blocking_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224879500,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:215",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/common/bL_switcher.c:bL_switcher_register_notifier",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/power/qos.c:pm_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "kernel/padata.c:padata_register_cpumask_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "security/security.c:register_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/iommu/iommu.c:iommu_group_register_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/mfd/da903x.c:da903x_register_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_register",
        "drivers/mfd/adp5520.c:adp5520_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/of/dynamic.c:of_reconfig_notifier_register",
        "drivers/of/overlay.c:of_overlay_notifier_register",
        "drivers/nvmem/core.c:nvmem_register_notifier",
        "sound/soc/soc-jack.c:snd_soc_jack_notifier_register",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv4/devinet.c:register_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:register_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:register_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224879500,
      "name": "blocking_notifier_chain_register",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283689840,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:215",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/power/qos.c:pm_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "kernel/padata.c:padata_register_cpumask_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "security/security.c:register_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/iommu/iommu.c:iommu_group_register_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/memory.c:register_memory_notifier",
        "drivers/mfd/da903x.c:da903x_register_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_register",
        "drivers/mfd/adp5520.c:adp5520_register_notifier",
        "drivers/vfio/vfio.c:vfio_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/of/dynamic.c:of_reconfig_notifier_register",
        "drivers/of/overlay.c:of_overlay_notifier_register",
        "drivers/nvmem/core.c:nvmem_register_notifier",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv4/devinet.c:register_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:register_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:register_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283689840,
      "name": "blocking_notifier_chain_register",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271518072,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:215",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/power/qos.c:pm_qos_add_notifier",
        "kernel/module.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "kernel/padata.c:padata_register_cpumask_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "security/security.c:register_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/mfd/da903x.c:da903x_register_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_register",
        "drivers/mfd/adp5520.c:adp5520_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/of/dynamic.c:of_reconfig_notifier_register",
        "drivers/of/overlay.c:of_overlay_notifier_register",
        "drivers/nvmem/core.c:nvmem_register_notifier",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv4/devinet.c:register_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:register_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:register_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271518072,
      "name": "blocking_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660800,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:215",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_register_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/power/qos.c:pm_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "kernel/padata.c:padata_register_cpumask_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "security/security.c:register_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_register",
        "drivers/acpi/event.c:register_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_register",
        "drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/iommu/iommu.c:iommu_group_register_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/memory.c:register_memory_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/nvmem/core.c:nvmem_register_notifier",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv4/devinet.c:register_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:register_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:register_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660800,
      "name": "blocking_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579589152,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:215",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_register_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/power/qos.c:pm_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "kernel/padata.c:padata_register_cpumask_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "security/security.c:register_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_register",
        "drivers/acpi/event.c:register_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_register",
        "drivers/acpi/hed.c:register_acpi_hed_notifier",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/iommu/iommu.c:iommu_group_register_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/memory.c:register_memory_notifier",
        "drivers/vfio/vfio.c:vfio_register_notifier",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/nvmem/core.c:nvmem_register_notifier",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv4/devinet.c:register_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:register_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:register_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579589152,
      "name": "blocking_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579658064,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:215",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_register_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/power/qos.c:pm_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "kernel/padata.c:padata_register_cpumask_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "security/security.c:register_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_register",
        "drivers/acpi/event.c:register_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_register",
        "drivers/acpi/hed.c:register_acpi_hed_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/iommu/iommu.c:iommu_group_register_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/memory.c:register_memory_notifier",
        "drivers/mfd/da903x.c:da903x_register_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_register",
        "drivers/mfd/adp5520.c:adp5520_register_notifier",
        "drivers/vfio/vfio.c:vfio_register_notifier",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/nvmem/core.c:nvmem_register_notifier",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv4/devinet.c:register_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:register_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:register_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579658064,
      "name": "blocking_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int blocking_notifier_chain_register(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579692048,
      "name": "blocking_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:215",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_register_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/power/qos.c:pm_qos_add_notifier",
        "kernel/power/main.c:register_pm_notifier",
        "kernel/module.c:register_module_notifier",
        "kernel/tracepoint.c:register_tracepoint_module_notifier",
        "kernel/padata.c:padata_register_cpumask_notifier",
        "mm/oom_kill.c:register_oom_notifier",
        "mm/vmalloc.c:register_vmap_purge_notifier",
        "security/security.c:register_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_register_notifier",
        "drivers/video/backlight/backlight.c:backlight_register_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_register_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_register",
        "drivers/acpi/event.c:register_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_register",
        "drivers/acpi/hed.c:register_acpi_hed_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier",
        "drivers/regulator/core.c:regulator_register_notifier",
        "drivers/iommu/iommu.c:iommu_group_register_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_add_notifier",
        "drivers/base/memory.c:register_memory_notifier",
        "drivers/mfd/da903x.c:da903x_register_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_register",
        "drivers/mfd/adp5520.c:adp5520_register_notifier",
        "drivers/vfio/vfio.c:vfio_register_notifier",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_register_notifier",
        "drivers/usb/core/notify.c:usb_register_notify",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/nvmem/core.c:nvmem_register_notifier",
        "net/netlink/af_netlink.c:netlink_register_notifier",
        "net/ipv4/devinet.c:register_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:register_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:register_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579692048,
      "name": "blocking_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
