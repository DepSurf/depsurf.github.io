# Function: <code>blocking_notifier_chain_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579506912,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:266",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:unregister_reboot_notifier",
        "kernel/power/qos.c:pm_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "kernel/padata.c:padata_unregister_cpumask_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/acpi/event.c:unregister_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_unregister",
        "drivers/acpi/hed.c:unregister_acpi_hed_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/iommu/iommu.c:iommu_group_unregister_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_global_notifier",
        "drivers/base/memory.c:unregister_memory_notifier",
        "drivers/mfd/da903x.c:da903x_unregister_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_unregister",
        "drivers/mfd/adp5520.c:adp5520_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506912,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579521024,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:266",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:unregister_reboot_notifier",
        "kernel/power/qos.c:pm_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "kernel/padata.c:padata_unregister_cpumask_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_unregister",
        "drivers/acpi/event.c:unregister_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_unregister",
        "drivers/acpi/hed.c:unregister_acpi_hed_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/iommu/iommu.c:iommu_group_unregister_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_global_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/memory.c:unregister_memory_notifier",
        "drivers/mfd/da903x.c:da903x_unregister_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_unregister",
        "drivers/mfd/adp5520.c:adp5520_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579521024,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579544672,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:266",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:unregister_reboot_notifier",
        "kernel/power/qos.c:pm_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "kernel/padata.c:padata_unregister_cpumask_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_unregister",
        "drivers/acpi/event.c:unregister_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_unregister",
        "drivers/acpi/hed.c:unregister_acpi_hed_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/iommu/iommu.c:iommu_group_unregister_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_global_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/memory.c:unregister_memory_notifier",
        "drivers/mfd/da903x.c:da903x_unregister_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_unregister",
        "drivers/mfd/adp5520.c:adp5520_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544672,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579531104,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:266",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_unregister_decode_chain",
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_unregister_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier",
        "kernel/reboot.c:unregister_reboot_notifier",
        "kernel/power/qos.c:pm_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "kernel/padata.c:padata_unregister_cpumask_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_unregister",
        "drivers/acpi/event.c:unregister_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_unregister",
        "drivers/acpi/hed.c:unregister_acpi_hed_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/iommu/iommu.c:iommu_group_unregister_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/memory.c:unregister_memory_notifier",
        "drivers/mfd/da903x.c:da903x_unregister_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_unregister",
        "drivers/mfd/adp5520.c:adp5520_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579531104,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579557600,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:266",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_unregister_decode_chain",
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_unregister_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier",
        "kernel/power/qos.c:pm_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "kernel/padata.c:padata_unregister_cpumask_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_unregister",
        "drivers/acpi/event.c:unregister_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_unregister",
        "drivers/acpi/hed.c:unregister_acpi_hed_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/iommu/iommu.c:iommu_group_unregister_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/memory.c:unregister_memory_notifier",
        "drivers/mfd/da903x.c:da903x_unregister_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_unregister",
        "drivers/mfd/adp5520.c:adp5520_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579557600,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579585872,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:266",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_unregister_decode_chain",
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_unregister_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
        "kernel/power/qos.c:pm_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "kernel/padata.c:padata_unregister_cpumask_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_unregister",
        "drivers/acpi/event.c:unregister_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_unregister",
        "drivers/acpi/hed.c:unregister_acpi_hed_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/iommu/iommu.c:iommu_group_unregister_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/memory.c:unregister_memory_notifier",
        "drivers/mfd/da903x.c:da903x_unregister_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_unregister",
        "drivers/mfd/adp5520.c:adp5520_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579585872,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579623072,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:266",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
        "kernel/power/qos.c:pm_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "kernel/padata.c:padata_unregister_cpumask_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_unregister",
        "drivers/acpi/event.c:unregister_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_unregister",
        "drivers/acpi/hed.c:unregister_acpi_hed_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/iommu/iommu.c:iommu_group_unregister_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/memory.c:unregister_memory_notifier",
        "drivers/mfd/da903x.c:da903x_unregister_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_unregister",
        "drivers/mfd/adp5520.c:adp5520_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/nvmem/core.c:nvmem_unregister_notifier",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579623072,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579647856,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:268",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
        "kernel/power/qos.c:pm_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "kernel/padata.c:padata_unregister_cpumask_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "security/security.c:unregister_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_unregister",
        "drivers/acpi/event.c:unregister_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_unregister",
        "drivers/acpi/hed.c:unregister_acpi_hed_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/iommu/iommu.c:iommu_group_unregister_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/memory.c:unregister_memory_notifier",
        "drivers/mfd/da903x.c:da903x_unregister_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_unregister",
        "drivers/mfd/adp5520.c:adp5520_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/nvmem/core.c:nvmem_unregister_notifier",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579647856,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579684992,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:268",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
        "kernel/power/qos.c:pm_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "kernel/padata.c:padata_unregister_cpumask_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "security/security.c:unregister_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_unregister",
        "drivers/acpi/event.c:unregister_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_unregister",
        "drivers/acpi/hed.c:unregister_acpi_hed_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/iommu/iommu.c:iommu_group_unregister_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/memory.c:unregister_memory_notifier",
        "drivers/mfd/da903x.c:da903x_unregister_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_unregister",
        "drivers/mfd/adp5520.c:adp5520_unregister_notifier",
        "drivers/vfio/vfio.c:vfio_unregister_notifier",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/nvmem/core.c:nvmem_unregister_notifier",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684992,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579724464,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:233",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier",
        "kernel/power/qos.c:freq_qos_remove_notifier",
        "kernel/power/qos.c:freq_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "security/security.c:unregister_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_unregister",
        "drivers/acpi/event.c:unregister_acpi_notifier",
        "drivers/acpi/hed.c:unregister_acpi_hed_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/iommu/iommu.c:iommu_group_unregister_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/memory.c:unregister_memory_notifier",
        "drivers/mfd/da903x.c:da903x_unregister_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_unregister",
        "drivers/mfd/adp5520.c:adp5520_unregister_notifier",
        "drivers/vfio/vfio.c:vfio_unregister_notifier",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/nvmem/core.c:nvmem_unregister_notifier",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724464,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579702704,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:270",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier",
        "kernel/power/qos.c:freq_qos_remove_notifier",
        "kernel/power/qos.c:freq_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "security/security.c:unregister_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_unregister",
        "drivers/acpi/event.c:unregister_acpi_notifier",
        "drivers/acpi/hed.c:unregister_acpi_hed_notifier",
        "drivers/acpi/apei/ghes.c:ghes_unregister_vendor_record_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/iommu/iommu.c:iommu_group_unregister_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/memory.c:unregister_memory_notifier",
        "drivers/mfd/da903x.c:da903x_unregister_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_unregister",
        "drivers/mfd/adp5520.c:adp5520_unregister_notifier",
        "drivers/vfio/vfio.c:vfio_unregister_notifier",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/nvmem/core.c:nvmem_unregister_notifier",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier",
        "net/ipv4/nexthop.c:unregister_nexthop_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702704,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579709840,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:270",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier",
        "kernel/power/qos.c:freq_qos_remove_notifier",
        "kernel/power/qos.c:freq_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "security/security.c:unregister_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_unregister",
        "drivers/acpi/event.c:unregister_acpi_notifier",
        "drivers/acpi/hed.c:unregister_acpi_hed_notifier",
        "drivers/acpi/apei/ghes.c:ghes_unregister_vendor_record_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/iommu/iommu.c:iommu_group_unregister_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/memory.c:unregister_memory_notifier",
        "drivers/mfd/da903x.c:da903x_unregister_notifier",
        "drivers/mfd/adp5520.c:adp5520_unregister_notifier",
        "drivers/vfio/vfio.c:vfio_unregister_notifier",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/nvmem/core.c:nvmem_unregister_notifier",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier",
        "net/ipv4/nexthop.c:unregister_nexthop_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579709840,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579787664,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:251",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier",
        "kernel/reboot.c:devm_unregister_reboot_notifier",
        "kernel/power/qos.c:freq_qos_remove_notifier",
        "kernel/power/qos.c:freq_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "security/security.c:unregister_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_unregister",
        "drivers/acpi/event.c:unregister_acpi_notifier",
        "drivers/acpi/hed.c:unregister_acpi_hed_notifier",
        "drivers/acpi/apei/ghes.c:ghes_unregister_vendor_record_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/iommu/iommu.c:iommu_group_unregister_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/memory.c:unregister_memory_notifier",
        "drivers/mfd/da903x.c:da903x_unregister_notifier",
        "drivers/mfd/adp5520.c:adp5520_unregister_notifier",
        "drivers/vfio/vfio.c:vfio_unregister_notifier",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/nvmem/core.c:nvmem_unregister_notifier",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier",
        "net/ipv4/nexthop.c:unregister_nexthop_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787664,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579893808,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:315",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier",
        "kernel/reboot.c:unregister_sys_off_handler",
        "kernel/reboot.c:devm_unregister_reboot_notifier",
        "kernel/power/qos.c:freq_qos_remove_notifier",
        "kernel/power/qos.c:freq_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module/main.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "security/security.c:unregister_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_unregister",
        "drivers/acpi/event.c:unregister_acpi_notifier",
        "drivers/acpi/hed.c:unregister_acpi_hed_notifier",
        "drivers/acpi/apei/ghes.c:ghes_unregister_vendor_record_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/char/random.c:unregister_random_vmfork_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/memory.c:unregister_memory_notifier",
        "drivers/mfd/da903x.c:da903x_unregister_notifier",
        "drivers/mfd/adp5520.c:adp5520_unregister_notifier",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/nvmem/core.c:nvmem_unregister_notifier",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier",
        "net/ipv4/nexthop.c:unregister_nexthop_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893808,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580044976,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:315",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier",
        "kernel/reboot.c:unregister_sys_off_handler",
        "kernel/reboot.c:devm_unregister_reboot_notifier",
        "kernel/power/qos.c:freq_qos_remove_notifier",
        "kernel/power/qos.c:freq_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module/main.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "security/security.c:unregister_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_unregister",
        "drivers/acpi/event.c:unregister_acpi_notifier",
        "drivers/acpi/hed.c:unregister_acpi_hed_notifier",
        "drivers/acpi/apei/ghes.c:ghes_unregister_vendor_record_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/char/random.c:unregister_random_vmfork_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/memory.c:unregister_memory_notifier",
        "drivers/mfd/da903x.c:da903x_unregister_notifier",
        "drivers/mfd/adp5520.c:adp5520_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/nvmem/core.c:nvmem_unregister_notifier",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier",
        "net/ipv4/nexthop.c:unregister_nexthop_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580044976,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580101776,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:321",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier",
        "kernel/reboot.c:unregister_sys_off_handler",
        "kernel/reboot.c:devm_unregister_reboot_notifier",
        "kernel/power/qos.c:freq_qos_remove_notifier",
        "kernel/power/qos.c:freq_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module/main.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "security/security.c:unregister_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_unregister",
        "drivers/acpi/event.c:unregister_acpi_notifier",
        "drivers/acpi/hed.c:unregister_acpi_hed_notifier",
        "drivers/acpi/apei/ghes.c:ghes_unregister_vendor_record_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/char/random.c:unregister_random_vmfork_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/memory.c:unregister_memory_notifier",
        "drivers/mfd/da903x.c:da903x_unregister_notifier",
        "drivers/mfd/adp5520.c:adp5520_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/nvmem/core.c:nvmem_unregister_notifier",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier",
        "net/ipv4/nexthop.c:unregister_nexthop_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580101776,
      "name": "blocking_notifier_chain_unregister",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580146592,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:321",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier",
        "kernel/reboot.c:unregister_sys_off_handler",
        "kernel/reboot.c:devm_unregister_reboot_notifier",
        "kernel/power/qos.c:freq_qos_remove_notifier",
        "kernel/power/qos.c:freq_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module/main.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "mm/memory-tiers.c:unregister_mt_adistance_algorithm",
        "fs/efivarfs/super.c:efivarfs_kill_sb",
        "security/security.c:unregister_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/gpio/gpiolib-cdev.c:lineevent_free",
        "drivers/gpio/gpiolib-cdev.c:linereq_free",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_unregister",
        "drivers/acpi/event.c:unregister_acpi_notifier",
        "drivers/acpi/hed.c:unregister_acpi_hed_notifier",
        "drivers/acpi/apei/ghes.c:ghes_unregister_vendor_record_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/char/random.c:unregister_random_vmfork_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/memory.c:unregister_memory_notifier",
        "drivers/mfd/da903x.c:da903x_unregister_notifier",
        "drivers/mfd/adp5520.c:adp5520_unregister_notifier",
        "drivers/gpu/drm/drm_privacy_screen.c:drm_privacy_screen_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/platform/x86/amd/wbrf.c:amd_wbrf_unregister_notifier",
        "drivers/nvmem/core.c:nvmem_unregister_notifier",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier",
        "net/ipv4/nexthop.c:unregister_nexthop_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146592,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490860248,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:268",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "kernel/padata.c:padata_unregister_cpumask_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "security/security.c:unregister_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_unregister",
        "drivers/acpi/event.c:unregister_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_unregister",
        "drivers/acpi/hed.c:unregister_acpi_hed_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/iommu/iommu.c:iommu_group_unregister_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/memory.c:unregister_memory_notifier",
        "drivers/mfd/da903x.c:da903x_unregister_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_unregister",
        "drivers/mfd/adp5520.c:adp5520_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/of/dynamic.c:of_reconfig_notifier_unregister",
        "drivers/of/overlay.c:of_overlay_notifier_unregister",
        "drivers/nvmem/core.c:nvmem_unregister_notifier",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490860248,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224880120,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:268",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/common/bL_switcher.c:bL_switcher_unregister_notifier",
        "kernel/power/qos.c:pm_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "kernel/padata.c:padata_unregister_cpumask_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "security/security.c:unregister_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/iommu/iommu.c:iommu_group_unregister_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/mfd/da903x.c:da903x_unregister_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_unregister",
        "drivers/mfd/adp5520.c:adp5520_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/of/dynamic.c:of_reconfig_notifier_unregister",
        "drivers/of/overlay.c:of_overlay_notifier_unregister",
        "drivers/nvmem/core.c:nvmem_unregister_notifier",
        "sound/soc/soc-jack.c:snd_soc_jack_notifier_unregister",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224880120,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283690704,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:268",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:devm_unregister_reboot_notifier",
        "kernel/power/qos.c:pm_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "kernel/padata.c:padata_unregister_cpumask_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "security/security.c:unregister_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/iommu/iommu.c:iommu_group_unregister_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/memory.c:unregister_memory_notifier",
        "drivers/mfd/da903x.c:da903x_unregister_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_unregister",
        "drivers/mfd/adp5520.c:adp5520_unregister_notifier",
        "drivers/vfio/vfio.c:vfio_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/of/dynamic.c:of_reconfig_notifier_unregister",
        "drivers/of/overlay.c:of_overlay_notifier_unregister",
        "drivers/nvmem/core.c:nvmem_unregister_notifier",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283690704,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271518672,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:268",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_remove_notifier",
        "kernel/module.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "kernel/padata.c:padata_unregister_cpumask_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "security/security.c:unregister_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/mfd/da903x.c:da903x_unregister_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_unregister",
        "drivers/mfd/adp5520.c:adp5520_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/of/dynamic.c:of_reconfig_notifier_unregister",
        "drivers/of/overlay.c:of_overlay_notifier_unregister",
        "drivers/nvmem/core.c:nvmem_unregister_notifier",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271518672,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579661312,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:268",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
        "kernel/power/qos.c:pm_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "kernel/padata.c:padata_unregister_cpumask_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "security/security.c:unregister_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_unregister",
        "drivers/acpi/event.c:unregister_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_unregister",
        "drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/iommu/iommu.c:iommu_group_unregister_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/memory.c:unregister_memory_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/nvmem/core.c:nvmem_unregister_notifier",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661312,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579589664,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:268",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
        "kernel/power/qos.c:pm_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "kernel/padata.c:padata_unregister_cpumask_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "security/security.c:unregister_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_unregister",
        "drivers/acpi/event.c:unregister_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_unregister",
        "drivers/acpi/hed.c:unregister_acpi_hed_notifier",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/iommu/iommu.c:iommu_group_unregister_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/memory.c:unregister_memory_notifier",
        "drivers/vfio/vfio.c:vfio_unregister_notifier",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/nvmem/core.c:nvmem_unregister_notifier",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579589664,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579658576,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:268",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
        "kernel/power/qos.c:pm_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "kernel/padata.c:padata_unregister_cpumask_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "security/security.c:unregister_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_unregister",
        "drivers/acpi/event.c:unregister_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_unregister",
        "drivers/acpi/hed.c:unregister_acpi_hed_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/iommu/iommu.c:iommu_group_unregister_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/memory.c:unregister_memory_notifier",
        "drivers/mfd/da903x.c:da903x_unregister_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_unregister",
        "drivers/mfd/adp5520.c:adp5520_unregister_notifier",
        "drivers/vfio/vfio.c:vfio_unregister_notifier",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/nvmem/core.c:nvmem_unregister_notifier",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579658576,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "blocking_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579692560,
      "name": "blocking_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:268",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
        "kernel/power/qos.c:pm_qos_remove_notifier",
        "kernel/power/main.c:unregister_pm_notifier",
        "kernel/module.c:unregister_module_notifier",
        "kernel/tracepoint.c:unregister_tracepoint_module_notifier",
        "kernel/padata.c:padata_unregister_cpumask_notifier",
        "mm/oom_kill.c:unregister_oom_notifier",
        "mm/vmalloc.c:unregister_vmap_purge_notifier",
        "security/security.c:unregister_blocking_lsm_notifier",
        "crypto/algapi.c:crypto_unregister_notifier",
        "drivers/video/backlight/backlight.c:backlight_unregister_notifier",
        "drivers/video/fbdev/core/fb_notify.c:fb_unregister_client",
        "drivers/acpi/scan.c:acpi_reconfig_notifier_unregister",
        "drivers/acpi/event.c:unregister_acpi_notifier",
        "drivers/acpi/button.c:acpi_lid_notifier_unregister",
        "drivers/acpi/hed.c:unregister_acpi_hed_notifier",
        "drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier",
        "drivers/regulator/core.c:regulator_unregister_notifier",
        "drivers/iommu/iommu.c:iommu_group_unregister_notifier",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/memory.c:unregister_memory_notifier",
        "drivers/mfd/da903x.c:da903x_unregister_notifier",
        "drivers/mfd/ab3100-core.c:ab3100_event_unregister",
        "drivers/mfd/adp5520.c:adp5520_unregister_notifier",
        "drivers/vfio/vfio.c:vfio_unregister_notifier",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unregister_notifier",
        "drivers/usb/core/notify.c:usb_unregister_notify",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/nvmem/core.c:nvmem_unregister_notifier",
        "net/netlink/af_netlink.c:netlink_unregister_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_validator_notifier",
        "net/ipv4/devinet.c:unregister_inetaddr_notifier",
        "net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579692560,
      "name": "blocking_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
