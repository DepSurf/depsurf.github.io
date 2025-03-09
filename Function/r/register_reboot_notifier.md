# Function: <code>register_reboot_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579510816,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:86",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/events/core.c:perf_event_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/base/firmware_class.c:firmware_class_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579510816,
      "name": "register_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579524912,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:86",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/events/core.c:perf_event_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/base/firmware_class.c:firmware_class_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/md/md.c:md_init",
        "drivers/firmware/efi/capsule.c:capsule_reboot_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579524912,
      "name": "register_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579548560,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:86",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/events/core.c:perf_event_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/base/firmware_class.c:firmware_class_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/md/md.c:md_init",
        "drivers/firmware/efi/capsule.c:capsule_reboot_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579548560,
      "name": "register_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579535200,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:86",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/events/core.c:perf_event_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/base/firmware_class.c:firmware_class_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/md/md.c:md_init",
        "drivers/firmware/efi/capsule.c:capsule_reboot_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535200,
      "name": "register_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579561862,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:86",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_reboot_notifier"
      ],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/events/core.c:perf_event_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/base/firmware_class.c:firmware_class_init",
        "drivers/md/md.c:md_init",
        "drivers/firmware/efi/capsule.c:capsule_reboot_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561744,
      "name": "register_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579590099,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:86",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_reboot_notifier"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/events/core.c:perf_event_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/md/md.c:md_init",
        "drivers/firmware/efi/capsule.c:capsule_reboot_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579589968,
      "name": "register_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579627619,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:87",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_reboot_notifier"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/events/core.c:perf_event_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/md/md.c:md_init",
        "drivers/firmware/efi/capsule.c:capsule_reboot_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579627488,
      "name": "register_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579652467,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:89",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_reboot_notifier"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/events/core.c:perf_event_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/md/md.c:md_init",
        "drivers/firmware/efi/capsule.c:capsule_reboot_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579652336,
      "name": "register_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579689587,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:89",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_reboot_notifier"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/events/core.c:perf_event_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/md/md.c:md_init",
        "drivers/firmware/efi/capsule.c:capsule_reboot_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579689456,
      "name": "register_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579729987,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:89",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_reboot_notifier"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_paravirt_ops_setup",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/events/core.c:perf_event_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/md/md.c:md_init",
        "drivers/firmware/efi/efi.c:register_update_efi_random_seed",
        "drivers/firmware/efi/capsule.c:capsule_reboot_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579729856,
      "name": "register_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579709091,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:89",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_reboot_notifier"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_paravirt_ops_setup",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/events/core.c:perf_event_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/md/md.c:md_init",
        "drivers/firmware/efi/efi.c:register_update_efi_random_seed",
        "drivers/firmware/efi/capsule.c:capsule_reboot_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579708960,
      "name": "register_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579716515,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:89",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_reboot_notifier"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/events/core.c:perf_event_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/md/md.c:md_init",
        "drivers/firmware/efi/efi.c:register_update_efi_random_seed",
        "drivers/firmware/efi/capsule.c:capsule_reboot_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579716384,
      "name": "register_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579794794,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:90",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_reboot_notifier"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/events/core.c:perf_event_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/md/md.c:md_init",
        "drivers/firmware/efi/efi.c:register_update_efi_random_seed",
        "drivers/firmware/efi/capsule.c:capsule_reboot_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579794656,
      "name": "register_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579902186,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:99",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_reboot_notifier"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/events/core.c:perf_event_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/md/md.c:md_init",
        "drivers/firmware/efi/efi.c:register_update_efi_random_seed",
        "drivers/firmware/efi/capsule.c:capsule_reboot_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579902016,
      "name": "register_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580054394,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:99",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_reboot_notifier"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/events/core.c:perf_event_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/md/md.c:md_init",
        "drivers/firmware/efi/efi.c:register_update_efi_random_seed",
        "drivers/firmware/efi/capsule.c:capsule_reboot_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054192,
      "name": "register_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580108826,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:99",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_reboot_notifier"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/events/core.c:perf_event_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/md/md.c:md_init",
        "drivers/firmware/efi/efi.c:register_update_efi_random_seed",
        "drivers/firmware/efi/capsule.c:capsule_reboot_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580108624,
      "name": "register_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580153866,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:109",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_reboot_notifier"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/events/core.c:perf_event_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/md/md.c:md_init",
        "drivers/firmware/efi/efi.c:register_update_efi_random_seed",
        "drivers/firmware/efi/capsule.c:capsule_reboot_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580153664,
      "name": "register_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490867744,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:89",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_reboot_notifier"
      ],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_init",
        "kernel/events/core.c:perf_event_init",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/md/md.c:md_init",
        "drivers/firmware/arm_sdei.c:sdei_probe",
        "drivers/firmware/efi/capsule.c:capsule_reboot_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490867568,
      "name": "register_reboot_notifier",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224885936,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:89",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_reboot_notifier"
      ],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/events/core.c:perf_event_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/mtd/mtdcore.c:mtd_device_parse_register",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/md/md.c:md_init",
        "drivers/firmware/efi/capsule.c:capsule_reboot_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224885796,
      "name": "register_reboot_notifier",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283698344,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:89",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_reboot_notifier"
      ],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/events/core.c:perf_event_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/md/md.c:md_init",
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283698048,
      "name": "register_reboot_notifier",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271523044,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:89",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_reboot_notifier"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271522884,
      "name": "register_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579665907,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:89",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_reboot_notifier"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/events/core.c:perf_event_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/md/md.c:md_init",
        "drivers/firmware/efi/capsule.c:capsule_reboot_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579665776,
      "name": "register_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579594259,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:89",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_reboot_notifier"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/events/core.c:perf_event_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/md/md.c:md_init",
        "drivers/firmware/efi/capsule.c:capsule_reboot_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579594128,
      "name": "register_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579663139,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:89",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_reboot_notifier"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/events/core.c:perf_event_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/md/md.c:md_init",
        "drivers/firmware/efi/capsule.c:capsule_reboot_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663008,
      "name": "register_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int register_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579697171,
      "name": "register_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:89",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_reboot_notifier"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/events/core.c:perf_event_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/md/md.c:md_init",
        "drivers/firmware/efi/capsule.c:capsule_reboot_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579697040,
      "name": "register_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
