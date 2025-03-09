# Function: <code>__set_fixmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_fixmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594954421,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:683",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578965468,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:683",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_setup_shared_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594990078,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:683",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:trap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579068388,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:683",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595009418,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:683",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595039025,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:683",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595044795,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:683",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595051453,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:683",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pvclock.c:pvclock_init_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595155039,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:683",
      "file": "mm/early_ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:__early_ioremap",
        "mm/early_ioremap.c:early_iounmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595257118,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:683",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595298090,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:683",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_fixmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595118086,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:656",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578962297,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:656",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_setup_shared_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595153517,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:656",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:trap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579064801,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:656",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595173865,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:656",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595204880,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:656",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579207471,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:656",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595329103,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:656",
      "file": "mm/early_ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:early_iounmap",
        "mm/early_ioremap.c:__early_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595438792,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:656",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595481175,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:656",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_fixmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595360794,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:647",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578964137,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:647",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_setup_shared_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595396225,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:647",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:trap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579064064,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:647",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595416248,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:647",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595447783,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:647",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579219135,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:647",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595577281,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:647",
      "file": "mm/early_ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:early_iounmap",
        "mm/early_ioremap.c:__early_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595691144,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:647",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595734126,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:647",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_fixmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596278778,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:694",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578975005,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:694",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_setup_shared_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596315516,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:694",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:trap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579055820,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:694",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596335367,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:694",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579102336,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:694",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596368664,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:694",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216455,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:694",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596504889,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:694",
      "file": "mm/early_ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:early_iounmap",
        "mm/early_ioremap.c:__early_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596615608,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:694",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596662025,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:694",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_fixmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602595095,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:658",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578978190,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:658",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_setup_shared_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579064836,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:658",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602652775,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:658",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602686740,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:658",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234183,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:658",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602832311,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:658",
      "file": "mm/early_ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:early_iounmap",
        "mm/early_ioremap.c:__early_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584739570,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:658",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602945972,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:658",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602992629,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:658",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_fixmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602763421,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:663",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980906,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:663",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_setup_shared_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579068814,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:663",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602822777,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:663",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602858203,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:663",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579246127,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:663",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603005634,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:663",
      "file": "mm/early_ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:early_iounmap",
        "mm/early_ioremap.c:__early_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584968202,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:663",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603118788,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:663",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603164408,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:663",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_fixmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604557514,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:641",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578968069,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:641",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604580176,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:641",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579073436,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:641",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604617916,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:641",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604655140,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:641",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269903,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:641",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604804262,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:641",
      "file": "mm/early_ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:early_iounmap",
        "mm/early_ioremap.c:__early_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585070963,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:641",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604921506,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:641",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604969900,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:641",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_fixmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604651848,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:642",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578975125,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:642",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604675600,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:642",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604714107,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:642",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604753618,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:642",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579284092,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:642",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604907662,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:642",
      "file": "mm/early_ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:early_iounmap",
        "mm/early_ioremap.c:__early_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585275148,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:642",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605030603,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:642",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605078996,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:642",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_fixmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604664120,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977525,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604687952,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604726409,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604767036,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579286556,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604941508,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "mm/early_ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:early_iounmap",
        "mm/early_ioremap.c:__early_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585413100,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605067214,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605118490,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_fixmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609015334,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:644",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578987349,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:644",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609038656,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:644",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609071989,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:644",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609113036,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:644",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579315981,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:644",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609255344,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:644",
      "file": "mm/early_ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:early_iounmap",
        "mm/early_ioremap.c:__early_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586122822,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:644",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609356297,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:644",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609395118,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:644",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_fixmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612077338,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:542",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578988841,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:542",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612102179,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:542",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612135326,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:542",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612177779,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:542",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321197,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:542",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612321653,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:542",
      "file": "mm/early_ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:early_iounmap",
        "mm/early_ioremap.c:__early_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586242278,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:542",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612427314,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:542",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612466599,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:542",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_fixmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614215845,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:573",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578997817,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:573",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614242251,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:573",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614275418,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:573",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614318220,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:573",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323933,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:573",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614461865,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:573",
      "file": "mm/early_ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:early_iounmap",
        "mm/early_ioremap.c:__early_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586117254,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:573",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614568476,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:573",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614608498,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:573",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_fixmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615134690,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:573",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579015497,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:573",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615162393,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:573",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615198043,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:573",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615246872,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:573",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579378003,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:573",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615407359,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:573",
      "file": "mm/early_ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:early_iounmap",
        "mm/early_ioremap.c:__early_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586617062,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:573",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615523039,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:573",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615566278,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:573",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_fixmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071616898027,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579034105,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616928079,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616967468,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617023373,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579442355,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617199482,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "mm/early_ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:early_iounmap",
        "mm/early_ioremap.c:__early_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587881048,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617327624,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617372869,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_fixmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627491957,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579063833,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627531784,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627585102,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627658857,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579527868,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627898899,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "mm/early_ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:early_iounmap",
        "mm/early_ioremap.c:__early_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589228568,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628053570,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:register_earlycon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628112240,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_fixmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619236085,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:574",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579063705,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:574",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619279352,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:574",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619337438,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:574",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619415801,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:574",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579540702,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:574",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619661934,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:574",
      "file": "mm/early_ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:early_iounmap",
        "mm/early_ioremap.c:__early_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589525288,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:574",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619819850,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:574",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:register_earlycon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619878778,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:574",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_fixmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621526165,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:572",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579088793,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:572",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621572328,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:572",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621630110,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:572",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621709181,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:572",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579569518,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:572",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621967982,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:572",
      "file": "mm/early_ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:early_iounmap",
        "mm/early_ioremap.c:__early_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589833320,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:572",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622128554,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:572",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:register_earlycon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622188458,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:572",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void __set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags)
```

```json
{
  "name": "__set_fixmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490345904,
      "name": "__set_fixmap",
      "external": true,
      "loc": "arch/arm64/mm/mmu.c:864",
      "file": "arch/arm64/mm/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/insn.c:__aarch64_insn_write",
        "arch/arm64/kernel/insn.c:__aarch64_insn_write",
        "arch/arm64/mm/mmu.c:paging_init",
        "arch/arm64/mm/mmu.c:paging_init",
        "arch/arm64/mm/mmu.c:map_entry_trampoline",
        "arch/arm64/mm/mmu.c:map_entry_trampoline",
        "arch/arm64/mm/mmu.c:alloc_init_pud",
        "arch/arm64/mm/mmu.c:alloc_init_pud",
        "arch/arm64/mm/mmu.c:init_pmd",
        "arch/arm64/mm/mmu.c:init_pmd",
        "arch/arm64/mm/mmu.c:init_pmd",
        "arch/arm64/mm/mmu.c:init_pmd",
        "arch/arm64/mm/mmu.c:early_pgtable_alloc",
        "arch/arm64/mm/mmu.c:early_pgtable_alloc",
        "arch/arm64/mm/mmu.c:set_swapper_pgd",
        "arch/arm64/mm/mmu.c:set_swapper_pgd",
        "mm/early_ioremap.c:early_iounmap",
        "mm/early_ioremap.c:__early_ioremap",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490345904,
      "name": "__set_fixmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void __set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t prot)
```

```json
{
  "name": "__set_fixmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224500912,
      "name": "__set_fixmap",
      "external": true,
      "loc": "arch/arm/mm/mmu.c:406",
      "file": "arch/arm/mm/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/patch.c:__patch_text_real",
        "arch/arm/kernel/patch.c:__patch_text_real",
        "mm/early_ioremap.c:early_iounmap",
        "mm/early_ioremap.c:__early_ioremap",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224500912,
      "name": "__set_fixmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void __set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t prot)
```

```json
{
  "name": "__set_fixmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936270613914,
      "name": "__set_fixmap",
      "external": true,
      "loc": "arch/riscv/mm/init.c:160",
      "file": "arch/riscv/mm/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/init.c:paging_init",
        "arch/riscv/mm/init.c:paging_init",
        "arch/riscv/mm/init.c:get_pmd_virt",
        "arch/riscv/mm/init.c:get_pmd_virt",
        "arch/riscv/mm/init.c:get_pte_virt",
        "arch/riscv/mm/init.c:get_pte_virt"
      ],
      "caller_func": [
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271358746,
      "name": "__set_fixmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_fixmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604590392,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977877,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604614233,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604652712,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604693315,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579285260,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604846968,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "mm/early_ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:early_iounmap",
        "mm/early_ioremap.c:__early_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604966837,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605016436,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_fixmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604581977,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/fixmap.h:163",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604620344,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/fixmap.h:163",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604660828,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/fixmap.h:163",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579220540,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/fixmap.h:163",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604816024,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/fixmap.h:163",
      "file": "mm/early_ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:early_iounmap",
        "mm/early_ioremap.c:__early_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604931162,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/fixmap.h:163",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604981889,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/fixmap.h:163",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_fixmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604668216,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977461,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604692048,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604730475,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604770899,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579286460,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604924152,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "mm/early_ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:early_iounmap",
        "mm/early_ioremap.c:__early_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585363500,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605047537,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605099029,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_fixmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604668221,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578978053,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604692004,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604730521,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604771156,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292348,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604945679,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "mm/early_ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:early_iounmap",
        "mm/early_ioremap.c:__early_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585470780,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605071408,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605122684,
      "name": "__set_fixmap",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void __set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void __set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t prot)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void __set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t prot)
```
</details>
</li>
</ul>
