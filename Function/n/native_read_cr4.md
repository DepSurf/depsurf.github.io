# Function: <code>native_read_cr4</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int native_read_cr4()
```

```json
{
  "name": "native_read_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578958132,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:59",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579256148,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:59",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578962336,
      "name": "native_read_cr4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579257648,
      "name": "native_read_cr4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int native_read_cr4()
```

```json
{
  "name": "native_read_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578955044,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:59",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579255204,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:59",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578958864,
      "name": "native_read_cr4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579257088,
      "name": "native_read_cr4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate ❓</summary>

```c
long unsigned int native_read_cr4()
```

```json
{
  "name": "native_read_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578956880,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579268752,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578956880,
      "name": "native_read_cr4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579268752,
      "name": "native_read_cr4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate ❓</summary>

```c
long unsigned int native_read_cr4()
```

```json
{
  "name": "native_read_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578969408,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579265360,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578969408,
      "name": "native_read_cr4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579265360,
      "name": "native_read_cr4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "native_read_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602582748,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602620253,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579021832,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602637030,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113070,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579180671,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196531,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579199877,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201164,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203382,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579252876,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579316265,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587375244,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "native_read_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602750645,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602788510,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579029365,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602806663,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119422,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192111,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208435,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211709,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213044,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579215382,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579264317,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326976,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587678924,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state"
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
  "name": "native_read_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604544704,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604582724,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579034051,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604601708,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579125022,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579181551,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579232051,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579235389,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579236724,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239062,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288909,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579350983,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587810012,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state"
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
  "name": "native_read_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604638796,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604678013,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579041612,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604697933,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579130640,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cr4_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194077,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245363,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579248754,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250132,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305293,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579366122,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588115532,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/power/cpu.c",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "native_read_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604651084,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604690480,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579044012,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604710309,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579132528,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cr4_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196381,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579247587,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250914,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251860,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309389,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579370362,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588322012,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state"
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
  "name": "native_read_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578845696,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__startup_64",
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609041182,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579053779,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609057176,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579148832,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cr4_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579217302,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272129,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275157,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:emergency_vmx_disable_all",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275985,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338505,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398664,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:show_fault_oops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591141900,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:55",
      "file": "arch/x86/power/cpu.c",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "native_read_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578845936,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__startup_64",
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612104540,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591244016,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612120536,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145920,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cr4_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212022,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579279521,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282428,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:emergency_vmx_disable_all",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579283185,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338510,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579379028,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/sev-es.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev-es.c:vc_handle_cpuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579400328,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:show_fault_oops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591225985,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/power/cpu.c",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "native_read_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578845936,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__startup_64",
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614244511,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591187680,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614260369,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151936,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cr4_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579214454,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282289,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579285585,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579286744,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579342277,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579388075,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:vc_handle_exitcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579403364,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:show_fault_oops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591175217,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/power/cpu.c",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "native_read_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578845936,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__startup_64",
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615164557,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592050944,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615181559,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579180768,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cr4_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579252422,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579325649,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329358,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330488,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579399717,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579449963,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:vc_handle_exitcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579465732,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:show_fault_oops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592028829,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/power/cpu.c",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "native_read_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578846016,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__startup_64",
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616930487,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593817502,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616947707,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579228112,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cr4_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579304771,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579385648,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390104,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390863,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579465614,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579524247,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit",
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess",
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess",
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579542322,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:show_fault_oops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593796581,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/power/cpu.c",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "native_read_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578846064,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__startup_64",
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627534574,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579148785,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627557237,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282356,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579286800,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cr4_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579463104,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579467439,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:crash_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579620832,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit",
        "arch/x86/kernel/sev.c:vc_handle_cpuid",
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess",
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess",
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579647367,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:show_fault_oops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595740597,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/power/cpu.c",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "native_read_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619280952,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578846336,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__startup_64",
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150897,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619306567,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288868,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293376,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cr4_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579475680,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579479896,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:crash_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579634768,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit",
        "arch/x86/kernel/sev.c:vc_handle_cpuid",
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess",
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess",
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579661767,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:show_fault_oops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596266565,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/power/cpu.c",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "native_read_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621573512,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578846352,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__startup_64",
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579180193,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621599389,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579318132,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322640,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cr4_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579506448,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579664560,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit",
        "arch/x86/kernel/sev.c:vc_handle_cpuid",
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess",
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess",
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess",
        "arch/x86/kernel/sev.c:__sev_cpuid_hv_ghcb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579695767,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:show_fault_oops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597149253,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:57",
      "file": "arch/x86/power/cpu.c",
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
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "native_read_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604577356,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604616761,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579044364,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604636597,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579132912,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cr4_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579195229,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579246435,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579249618,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250564,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305293,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579366266,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587925660,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state"
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
  "name": "native_read_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604569072,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977422,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604604613,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579064032,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cr4_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579130095,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579181854,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579185023,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579185831,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239738,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296597,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587640882,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state"
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
  "name": "native_read_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604655180,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604694576,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579043948,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604714405,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579132464,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cr4_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196301,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579247491,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250818,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251764,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305293,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579366186,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588259068,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state"
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
  "name": "native_read_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604655180,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604694532,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579047676,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604714421,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579137584,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cr4_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201581,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579253059,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256386,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579257332,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313511,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579374618,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588394588,
      "name": "native_read_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state"
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
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
long unsigned int native_read_cr4()
```
</details>
</li>
</ul>
