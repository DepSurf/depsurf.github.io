# Function: <code>read_apic_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579178444,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:494",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595039083,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:494",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:hard_smp_processor_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595040406,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:494",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201989,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:494",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_disable_io_apic"
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
  "name": "read_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595196418,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:501",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191429,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:501",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:hard_smp_processor_id",
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595206246,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:501",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579202661,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:501",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_disable_io_apic"
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
  "name": "read_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595439220,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:501",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203173,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:501",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:hard_smp_processor_id",
        "arch/x86/kernel/apic/apic.c:__generic_processor_info",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595449133,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:501",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579214325,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:501",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_disable_io_apic"
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
  "name": "read_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596359947,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:497",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200901,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:497",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:hard_smp_processor_id",
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596370088,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:497",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211845,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:497",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_disable_io_apic"
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
  "name": "read_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579203455,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:488",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216629,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:488",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:hard_smp_processor_id",
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602688457,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:488",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579229493,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:488",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_disable_io_apic"
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
  "name": "read_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579215455,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:485",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579228453,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:485",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:hard_smp_processor_id",
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602860314,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:485",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579241885,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:485",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode"
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
  "name": "read_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579239135,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:485",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579252149,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:485",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:hard_smp_processor_id",
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604657251,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:485",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579265661,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:485",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode"
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
  "name": "read_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579266101,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:486",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:hard_smp_processor_id",
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604755194,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:486",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579279922,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:486",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode"
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
  "name": "read_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579267749,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:493",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:hard_smp_processor_id",
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_select",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604768702,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:493",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282386,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:493",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode"
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
unsigned int read_apic_id()
```

```json
{
  "name": "read_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579295413,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:493",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:hard_smp_processor_id",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:__apic_intr_mode_select",
        "arch/x86/kernel/apic/apic.c:__apic_intr_mode_select"
      ]
    },
    {
      "addr": 18446744071609114564,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:493",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579312053,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:493",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579288480,
      "name": "read_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
unsigned int read_apic_id()
```

```json
{
  "name": "read_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579301461,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:483",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:hard_smp_processor_id",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:__apic_intr_mode_select",
        "arch/x86/kernel/apic/apic.c:__apic_intr_mode_select"
      ]
    },
    {
      "addr": 18446744071612179330,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:483",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579317329,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:483",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579294512,
      "name": "read_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
unsigned int read_apic_id()
```

```json
{
  "name": "read_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579304325,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:484",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:hard_smp_processor_id",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_select",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_select"
      ]
    },
    {
      "addr": 18446744071614319783,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:484",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579320097,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:484",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297184,
      "name": "read_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
unsigned int read_apic_id()
```

```json
{
  "name": "read_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579352229,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:484",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:hard_smp_processor_id",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_select",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_select"
      ]
    },
    {
      "addr": 18446744071615248417,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:484",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579375425,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:484",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579344624,
      "name": "read_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
unsigned int read_apic_id()
```

```json
{
  "name": "read_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579414229,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:486",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:hard_smp_processor_id",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_select",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_select"
      ]
    },
    {
      "addr": 18446744071617025177,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:486",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579439684,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:486",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579405648,
      "name": "read_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int read_apic_id()
```

```json
{
  "name": "read_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579496613,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:483",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:hard_smp_processor_id",
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_select"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_select"
      ]
    },
    {
      "addr": 18446744071627661117,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:483",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579524708,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:483",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579486592,
      "name": "read_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int read_apic_id()
```

```json
{
  "name": "read_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579508789,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:484",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:hard_smp_processor_id",
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_select"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_select"
      ]
    },
    {
      "addr": 18446744071619418077,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:484",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579537524,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:484",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579498656,
      "name": "read_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579359249,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:509",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362703,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:509",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621711744,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:509",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:apic_read_boot_cpu_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579537653,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:509",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_common.c:default_apic_id_registered"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621714077,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:509",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC",
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621718605,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:509",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579682501,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:509",
      "file": "arch/x86/kernel/vsmp_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id"
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
  "name": "read_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579266453,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:493",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:hard_smp_processor_id",
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_select",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604694981,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:493",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579281090,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:493",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode"
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
  "name": "read_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579201893,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:493",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:hard_smp_processor_id",
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_select",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604662460,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:493",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216418,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:493",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode"
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
  "name": "read_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579267653,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:493",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:hard_smp_processor_id",
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_select",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604772565,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:493",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282290,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:493",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode"
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
  "name": "read_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579273253,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:493",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:hard_smp_processor_id",
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_select",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604772843,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:493",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288178,
      "name": "read_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:493",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode"
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
unsigned int read_apic_id()
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
unsigned int read_apic_id()
```
</details>
</li>
</ul>
