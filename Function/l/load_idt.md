# Function: <code>load_idt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594939464,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:233",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594989361,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:233",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:early_trap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579108166,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:233",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_reset",
        "arch/x86/kernel/cpu/common.c:debug_stack_reset",
        "arch/x86/kernel/cpu/common.c:debug_stack_reset",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174424,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:233",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579263958,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:233",
      "file": "arch/x86/kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tracepoint.c:switch_idt",
        "arch/x86/kernel/tracepoint.c:switch_idt",
        "arch/x86/kernel/tracepoint.c:switch_idt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586164980,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:233",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state"
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
  "name": "load_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595103201,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:232",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595152800,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:232",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:early_trap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111557,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:232",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:debug_stack_reset",
        "arch/x86/kernel/cpu/common.c:debug_stack_reset",
        "arch/x86/kernel/cpu/common.c:debug_stack_reset",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174852,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:232",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579263334,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:232",
      "file": "arch/x86/kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tracepoint.c:switch_idt",
        "arch/x86/kernel/tracepoint.c:switch_idt",
        "arch/x86/kernel/tracepoint.c:switch_idt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586579284,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:232",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state"
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
  "name": "load_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595348961,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:223",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595395508,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:223",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:early_trap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579110098,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:223",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:debug_stack_reset",
        "arch/x86/kernel/cpu/common.c:debug_stack_reset",
        "arch/x86/kernel/cpu/common.c:debug_stack_reset",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579185204,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:223",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579276934,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:223",
      "file": "arch/x86/kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tracepoint.c:switch_idt",
        "arch/x86/kernel/tracepoint.c:switch_idt",
        "arch/x86/kernel/tracepoint.c:switch_idt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586763604,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:223",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state"
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
  "name": "load_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596266445,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:223",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596314789,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:223",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:early_trap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579101795,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:223",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:debug_stack_reset",
        "arch/x86/kernel/cpu/common.c:debug_stack_reset",
        "arch/x86/kernel/cpu/common.c:debug_stack_reset",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183930,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:223",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579273472,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:223",
      "file": "arch/x86/kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tracepoint.c:switch_idt",
        "arch/x86/kernel/tracepoint.c:switch_idt",
        "arch/x86/kernel/tracepoint.c:switch_idt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586886865,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:223",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state"
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
  "name": "load_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579033746,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:idt_invalidate",
        "arch/x86/kernel/idt.c:idt_setup_early_handler",
        "arch/x86/kernel/idt.c:idt_setup_early_traps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113282,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:debug_stack_reset",
        "arch/x86/kernel/cpu/common.c:debug_stack_reset",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203414,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587375569,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state"
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
  "name": "load_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579037970,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:idt_invalidate",
        "arch/x86/kernel/idt.c:idt_setup_early_handler",
        "arch/x86/kernel/idt.c:idt_setup_early_traps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119634,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579215414,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587679217,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state"
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
  "name": "load_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579042722,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:267",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:idt_invalidate",
        "arch/x86/kernel/idt.c:idt_setup_early_handler",
        "arch/x86/kernel/idt.c:idt_setup_early_traps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579125370,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:267",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239094,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:267",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587810305,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:267",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state"
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
  "name": "load_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579050370,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:267",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:idt_invalidate",
        "arch/x86/kernel/idt.c:idt_setup_early_handler",
        "arch/x86/kernel/idt.c:idt_setup_early_traps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579135016,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:267",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579253693,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:267",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588116195,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:267",
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
  "name": "load_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579052610,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:255",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:idt_invalidate",
        "arch/x86/kernel/idt.c:idt_setup_early_handler",
        "arch/x86/kernel/idt.c:idt_setup_early_traps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136936,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:255",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579255405,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:255",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588321091,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:255",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void load_idt(const struct desc_ptr * dtr)
```

```json
{
  "name": "load_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579060274,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:261",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:idt_invalidate",
        "arch/x86/kernel/idt.c:load_current_idt"
      ],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_early_handler",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_early_traps"
      ]
    },
    {
      "addr": 18446744071591142133,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:261",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579060192,
      "name": "load_idt",
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
void load_idt(const struct desc_ptr * dtr)
```

```json
{
  "name": "load_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579062338,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:259",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:idt_invalidate",
        "arch/x86/kernel/idt.c:load_current_idt"
      ],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_early_handler",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_early_traps"
      ]
    },
    {
      "addr": 18446744071591226213,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:259",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579062256,
      "name": "load_idt",
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
void load_idt(const struct desc_ptr * dtr)
```

```json
{
  "name": "load_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579069058,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:276",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:idt_invalidate",
        "arch/x86/kernel/idt.c:load_current_idt"
      ],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_early_handler",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_early_traps"
      ]
    },
    {
      "addr": 18446744071591175445,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:276",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068976,
      "name": "load_idt",
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
void load_idt(const struct desc_ptr * dtr)
```

```json
{
  "name": "load_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579090277,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:276",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:idt_invalidate",
        "arch/x86/kernel/idt.c:load_current_idt"
      ],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_early_handler",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_early_traps"
      ]
    },
    {
      "addr": 18446744071592029091,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:276",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579090224,
      "name": "load_idt",
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
void load_idt(const struct desc_ptr * dtr)
```

```json
{
  "name": "load_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579119093,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:282",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:idt_invalidate",
        "arch/x86/kernel/idt.c:load_current_idt"
      ],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_early_handler",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_early_traps"
      ]
    },
    {
      "addr": 18446744071593796878,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:282",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579118976,
      "name": "load_idt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
  "name": "load_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579158613,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:282",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:idt_invalidate",
        "arch/x86/kernel/idt.c:idt_setup_early_handler",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_early_traps",
        "arch/x86/kernel/idt.c:load_current_idt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595740910,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:282",
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
  "name": "load_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579160773,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:284",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:idt_invalidate",
        "arch/x86/kernel/idt.c:idt_setup_early_handler",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_early_traps",
        "arch/x86/kernel/idt.c:load_current_idt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596266878,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:284",
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
  "name": "load_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579190085,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:286",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:idt_invalidate",
        "arch/x86/kernel/idt.c:idt_setup_early_handler",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_early_traps",
        "arch/x86/kernel/idt.c:load_current_idt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597149566,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:286",
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
  "name": "load_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579052962,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:255",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:idt_invalidate",
        "arch/x86/kernel/idt.c:idt_setup_early_handler",
        "arch/x86/kernel/idt.c:idt_setup_early_traps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579137320,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:255",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579254109,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:255",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587924739,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:255",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579052546,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:255",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:idt_invalidate",
        "arch/x86/kernel/idt.c:idt_setup_early_handler",
        "arch/x86/kernel/idt.c:idt_setup_early_traps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136872,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:255",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579255309,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:255",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588258147,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:255",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579056482,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:255",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:idt_invalidate",
        "arch/x86/kernel/idt.c:idt_setup_early_handler",
        "arch/x86/kernel/idt.c:idt_setup_early_traps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579141992,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:255",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579260877,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:255",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588393667,
      "name": "load_idt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:255",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void load_idt(const struct desc_ptr * dtr)
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
void load_idt(const struct desc_ptr * dtr)
```
</details>
</li>
</ul>
