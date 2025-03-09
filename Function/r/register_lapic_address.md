# Function: <code>register_lapic_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void register_lapic_address(long unsigned int address)
```

```json
{
  "name": "register_lapic_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595038984,
      "name": "register_lapic_address",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1785",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:early_acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/platform/sfi/sfi.c:sfi_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595038984,
      "name": "register_lapic_address",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void register_lapic_address(long unsigned int address)
```

```json
{
  "name": "register_lapic_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595204839,
      "name": "register_lapic_address",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1824",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:early_acpi_boot_init",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/platform/sfi/sfi.c:sfi_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595204839,
      "name": "register_lapic_address",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void register_lapic_address(long unsigned int address)
```

```json
{
  "name": "register_lapic_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595447745,
      "name": "register_lapic_address",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1825",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:early_acpi_boot_init",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/platform/sfi/sfi.c:sfi_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595447745,
      "name": "register_lapic_address",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void register_lapic_address(long unsigned int address)
```

```json
{
  "name": "register_lapic_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596368621,
      "name": "register_lapic_address",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1901",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:early_acpi_boot_init",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/platform/sfi/sfi.c:sfi_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596368621,
      "name": "register_lapic_address",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void register_lapic_address(long unsigned int address)
```

```json
{
  "name": "register_lapic_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602686697,
      "name": "register_lapic_address",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1986",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:early_acpi_boot_init",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/platform/sfi/sfi.c:sfi_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602686697,
      "name": "register_lapic_address",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void register_lapic_address(long unsigned int address)
```

```json
{
  "name": "register_lapic_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602858132,
      "name": "register_lapic_address",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1999",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:early_acpi_boot_init",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/platform/sfi/sfi.c:sfi_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602858132,
      "name": "register_lapic_address",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void register_lapic_address(long unsigned int address)
```

```json
{
  "name": "register_lapic_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604655069,
      "name": "register_lapic_address",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2007",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:early_acpi_boot_init",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/platform/sfi/sfi.c:sfi_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604655069,
      "name": "register_lapic_address",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void register_lapic_address(long unsigned int address)
```

```json
{
  "name": "register_lapic_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604753546,
      "name": "register_lapic_address",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2085",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:early_acpi_boot_init",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/platform/sfi/sfi.c:sfi_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604753546,
      "name": "register_lapic_address",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void register_lapic_address(long unsigned int address)
```

```json
{
  "name": "register_lapic_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604766964,
      "name": "register_lapic_address",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2142",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:early_acpi_boot_init",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/platform/sfi/sfi.c:sfi_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604766964,
      "name": "register_lapic_address",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void register_lapic_address(long unsigned int address)
```

```json
{
  "name": "register_lapic_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609112961,
      "name": "register_lapic_address",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2095",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:early_acpi_process_madt",
        "arch/x86/kernel/mpparse.c:smp_read_mpc",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/platform/sfi/sfi.c:sfi_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609112961,
      "name": "register_lapic_address",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void register_lapic_address(long unsigned int address)
```

```json
{
  "name": "register_lapic_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612177704,
      "name": "register_lapic_address",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2121",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:early_acpi_process_madt",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/platform/sfi/sfi.c:sfi_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612177704,
      "name": "register_lapic_address",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void register_lapic_address(long unsigned int address)
```

```json
{
  "name": "register_lapic_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614318145,
      "name": "register_lapic_address",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2122",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:early_acpi_boot_init",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614318145,
      "name": "register_lapic_address",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void register_lapic_address(long unsigned int address)
```

```json
{
  "name": "register_lapic_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615246797,
      "name": "register_lapic_address",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2119",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:early_acpi_boot_init",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615246797,
      "name": "register_lapic_address",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void register_lapic_address(long unsigned int address)
```

```json
{
  "name": "register_lapic_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617023296,
      "name": "register_lapic_address",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2127",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:early_acpi_boot_init",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617023296,
      "name": "register_lapic_address",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void register_lapic_address(long unsigned int address)
```

```json
{
  "name": "register_lapic_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627658752,
      "name": "register_lapic_address",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2161",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:early_acpi_boot_init",
        "arch/x86/kernel/mpparse.c:check_physptr",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627658752,
      "name": "register_lapic_address",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void register_lapic_address(long unsigned int address)
```

```json
{
  "name": "register_lapic_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619415696,
      "name": "register_lapic_address",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2163",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:early_acpi_boot_init",
        "arch/x86/kernel/mpparse.c:check_physptr",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619415696,
      "name": "register_lapic_address",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void register_lapic_address(long unsigned int address)
```

```json
{
  "name": "register_lapic_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621712081,
      "name": "register_lapic_address",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2107",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:init_apic_mappings"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:early_acpi_boot_init",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:check_physptr",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621712192,
      "name": "register_lapic_address",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void register_lapic_address(long unsigned int address)
```

```json
{
  "name": "register_lapic_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604693243,
      "name": "register_lapic_address",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2142",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:early_acpi_boot_init",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/platform/sfi/sfi.c:sfi_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604693243,
      "name": "register_lapic_address",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void register_lapic_address(long unsigned int address)
```

```json
{
  "name": "register_lapic_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604660763,
      "name": "register_lapic_address",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2142",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:early_acpi_boot_init",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/platform/sfi/sfi.c:sfi_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604660763,
      "name": "register_lapic_address",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void register_lapic_address(long unsigned int address)
```

```json
{
  "name": "register_lapic_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604770827,
      "name": "register_lapic_address",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2142",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:early_acpi_boot_init",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/platform/sfi/sfi.c:sfi_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604770827,
      "name": "register_lapic_address",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void register_lapic_address(long unsigned int address)
```

```json
{
  "name": "register_lapic_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604771084,
      "name": "register_lapic_address",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2142",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:early_acpi_boot_init",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/platform/sfi/sfi.c:sfi_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604771084,
      "name": "register_lapic_address",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 184
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void register_lapic_address(long unsigned int address)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void register_lapic_address(long unsigned int address)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void register_lapic_address(long unsigned int address)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void register_lapic_address(long unsigned int address)
```
</details>
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
