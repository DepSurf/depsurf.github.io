# Function: <code>write_cr0</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578963315,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:64",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579031757,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:64",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579080904,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:64",
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
      "addr": 18446744071595006389,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:64",
      "file": "arch/x86/kernel/fpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs",
        "arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579081460,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:64",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_end",
        "arch/x86/kernel/fpu/core.c:fpu__drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156559,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:64",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586164966,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:64",
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
  "name": "write_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578959772,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:54",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579027964,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:54",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595169450,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:54",
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
      "addr": 18446744071595169961,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:54",
      "file": "arch/x86/kernel/fpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs",
        "arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579081081,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:54",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__drop",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156966,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:54",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586579270,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:54",
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
  "name": "write_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578961836,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:49",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579033955,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:49",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595412035,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:49",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579166262,
      "name": "write_cr0",
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
      "addr": 18446744071586763590,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:49",
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
  "name": "write_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579026048,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:49",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596331581,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:49",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579166118,
      "name": "write_cr0",
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
      "addr": 18446744071586886851,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:49",
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
  "name": "write_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579029913,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:50",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602649806,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:50",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579180822,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:50",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587375555,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:50",
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
  "name": "write_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579033982,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:50",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602819756,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:50",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192253,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:50",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587679203,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:50",
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
  "name": "write_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579038446,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604614900,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579181693,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587810291,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
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
  "name": "write_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579046112,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604710684,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194237,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588116181,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
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
  "name": "write_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579048352,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604723084,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196541,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588321077,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
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
void write_cr0(long unsigned int x)
```

```json
{
  "name": "write_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591156071,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111912,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579217371,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591142119,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111840,
      "name": "write_cr0",
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
void write_cr0(long unsigned int x)
```

```json
{
  "name": "write_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591649482,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111608,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212091,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591226199,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111536,
      "name": "write_cr0",
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
void write_cr0(long unsigned int x)
```

```json
{
  "name": "write_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591593322,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:131",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118243,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:131",
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
      "addr": 18446744071579214523,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:131",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591175431,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:131",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579118176,
      "name": "write_cr0",
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
void write_cr0(long unsigned int x)
```

```json
{
  "name": "write_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592765146,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:131",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579143699,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:131",
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
      "addr": 18446744071579252491,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:131",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592029077,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:131",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143632,
      "name": "write_cr0",
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
void write_cr0(long unsigned int x)
```

```json
{
  "name": "write_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594658298,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616962391,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
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
      "addr": 18446744071579304874,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593796865,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579181424,
      "name": "write_cr0",
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
  "name": "write_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596391866,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627578351,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282526,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_enable",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595740897,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
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
  "name": "write_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596922090,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619330831,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289038,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_enable",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596266865,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
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
  "name": "write_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597847818,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:141",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621623791,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:141",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579318302,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:141",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_enable",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597149553,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:141",
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
  "name": "write_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579048704,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604649387,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579195389,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587924725,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578981845,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:148",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604617291,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:148",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579130169,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:148",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587641260,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:148",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579048288,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604727150,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196461,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588258133,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
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
  "name": "write_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579052064,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604727196,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201741,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588393653,
      "name": "write_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:112",
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
void write_cr0(long unsigned int x)
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
void write_cr0(long unsigned int x)
```
</details>
</li>
</ul>
