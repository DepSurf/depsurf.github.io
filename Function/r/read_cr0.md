# Function: <code>read_cr0</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578963308,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:59",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579030207,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:59",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579080897,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:59",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_ctx_switch",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic",
        "arch/x86/kernel/fpu/init.c:fpu__init_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595006382,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:59",
      "file": "arch/x86/kernel/fpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579081144,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:59",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:irq_fpu_usable",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_end",
        "arch/x86/kernel/fpu/core.c:fpu__drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156552,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:59",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579171636,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:59",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586164715,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:59",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578959756,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:49",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579027950,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:49",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595169436,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:49",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_ctx_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595169945,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:49",
      "file": "arch/x86/kernel/fpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579081067,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:49",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__drop",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_end",
        "arch/x86/kernel/fpu/core.c:irq_fpu_usable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156950,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:49",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579172014,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:49",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586578943,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:49",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578961820,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:44",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579026063,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:44",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579033878,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:44",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595412021,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:44",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579166246,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:44",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579182286,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:44",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586763263,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:44",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579018367,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:44",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579025988,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:44",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596331567,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:44",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579166102,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:44",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579181038,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:44",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586886511,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:44",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579021799,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:45",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579029846,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:45",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602649792,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:45",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579180806,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:45",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196510,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:45",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587375202,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:45",
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
  "name": "read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579029332,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:45",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579033909,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:45",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602819749,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:45",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192246,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:45",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208414,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:45",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587678882,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:45",
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
  "name": "read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579034018,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038373,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604614893,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579181686,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579232030,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587809970,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
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
  "name": "read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579041579,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579046037,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604710677,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194230,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245342,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588115490,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
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
  "name": "read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579043979,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579048277,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604723077,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196534,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579247566,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588321970,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int read_cr0()
```

```json
{
  "name": "read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579053750,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591156005,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111905,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579217364,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272108,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591141858,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111824,
      "name": "read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int read_cr0()
```

```json
{
  "name": "read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591243987,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591649415,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111601,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212084,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579279500,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591225943,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111520,
      "name": "read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int read_cr0()
```

```json
{
  "name": "read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591187651,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:126",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591593255,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:126",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118236,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:126",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system"
      ]
    },
    {
      "addr": 18446744071579214516,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:126",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282268,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:126",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586803047,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:126",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591175175,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:126",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579118160,
      "name": "read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int read_cr0()
```

```json
{
  "name": "read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592050915,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:126",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592765079,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:126",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579143692,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:126",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system"
      ]
    },
    {
      "addr": 18446744071579252484,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:126",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579325628,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:126",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587360026,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:126",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592028787,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:126",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143616,
      "name": "read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int read_cr0()
```

```json
{
  "name": "read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593817476,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594658196,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616962385,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system"
      ]
    },
    {
      "addr": 18446744071579304868,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579385628,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588671561,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593796542,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579181376,
      "name": "read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579148755,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596391764,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627578345,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282520,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_enable",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579463084,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590145147,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595740558,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
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
  "name": "read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579150867,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596921988,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619330825,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289032,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_enable",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579475660,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596266526,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
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
  "name": "read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579180163,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:136",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597847716,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:136",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621623785,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:136",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579318296,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:136",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_enable",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579506428,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:136",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597149214,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:136",
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
  "name": "read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579044331,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579048629,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604649380,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579195382,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579246414,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587925618,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
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
  "name": "read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578977406,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:143",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578981797,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:143",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604617288,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:143",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579130166,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:143",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579181837,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:143",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587640852,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:143",
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
  "name": "read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579043915,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579048213,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604727143,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196454,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579247470,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588259026,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
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
  "name": "read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579047643,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579051989,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604727189,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201734,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579253038,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588394546,
      "name": "read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long unsigned int read_cr0()
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
long unsigned int read_cr0()
```
</details>
</li>
</ul>
