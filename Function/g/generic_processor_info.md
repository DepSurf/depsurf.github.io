# Function: <code>generic_processor_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int generic_processor_info(int apicid, int version)
```

```json
{
  "name": "generic_processor_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579190336,
      "name": "generic_processor_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1991",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/sfi/sfi.c:sfi_parse_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579190336,
      "name": "generic_processor_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
int generic_processor_info(int apicid, int version)
```

```json
{
  "name": "generic_processor_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579190736,
      "name": "generic_processor_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2030",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/sfi/sfi.c:sfi_parse_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579190736,
      "name": "generic_processor_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 682
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
int generic_processor_info(int apicid, int version)
```

```json
{
  "name": "generic_processor_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579203136,
      "name": "generic_processor_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2200",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/platform/sfi/sfi.c:sfi_parse_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579203136,
      "name": "generic_processor_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int generic_processor_info(int apicid, int version)
```

```json
{
  "name": "generic_processor_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579200032,
      "name": "generic_processor_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2150",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/platform/sfi/sfi.c:sfi_parse_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579200032,
      "name": "generic_processor_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 864
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
int generic_processor_info(int apicid, int version)
```

```json
{
  "name": "generic_processor_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579215744,
      "name": "generic_processor_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2212",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/platform/sfi/sfi.c:sfi_parse_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579215744,
      "name": "generic_processor_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 874
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int generic_processor_info(int apicid, int version)
```

```json
{
  "name": "generic_processor_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_processor_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2242",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/mpparse.c:MP_processor_info",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/platform/sfi/sfi.c:sfi_parse_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579228962,
      "name": "generic_processor_info.cold.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 18446744071579227760,
      "name": "generic_processor_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 680
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int generic_processor_info(int apicid, int version)
```

```json
{
  "name": "generic_processor_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_processor_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2250",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/mpparse.c:MP_processor_info",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/platform/sfi/sfi.c:sfi_parse_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579252659,
      "name": "generic_processor_info.cold.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 18446744071579251456,
      "name": "generic_processor_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 680
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int generic_processor_info(int apicid, int version)
```

```json
{
  "name": "generic_processor_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_processor_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2339",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/mpparse.c:MP_processor_info",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/platform/sfi/sfi.c:sfi_parse_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579266672,
      "name": "generic_processor_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071579265440,
      "name": "generic_processor_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 650
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int generic_processor_info(int apicid, int version)
```

```json
{
  "name": "generic_processor_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_processor_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2396",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/mpparse.c:MP_processor_info",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/platform/sfi/sfi.c:sfi_parse_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268325,
      "name": "generic_processor_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071579267088,
      "name": "generic_processor_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 650
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int generic_processor_info(int apicid, int version)
```

```json
{
  "name": "generic_processor_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_processor_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2357",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_lapic",
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/mpparse.c:MP_processor_info",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/platform/sfi/sfi.c:sfi_parse_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579296313,
      "name": "generic_processor_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071579294752,
      "name": "generic_processor_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int generic_processor_info(int apicid, int version)
```

```json
{
  "name": "generic_processor_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_processor_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2388",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_lapic",
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/mpparse.c:MP_processor_info",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/platform/sfi/sfi.c:sfi_parse_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591260051,
      "name": "generic_processor_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    },
    {
      "addr": 18446744071579300800,
      "name": "generic_processor_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 642
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int generic_processor_info(int apicid, int version)
```

```json
{
  "name": "generic_processor_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_processor_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2396",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_lapic",
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/mpparse.c:MP_processor_info",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591203149,
      "name": "generic_processor_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071579303664,
      "name": "generic_processor_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int generic_processor_info(int apicid, int version)
```

```json
{
  "name": "generic_processor_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_processor_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2393",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_lapic",
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/mpparse.c:MP_processor_info",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592074188,
      "name": "generic_processor_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    },
    {
      "addr": 18446744071579351392,
      "name": "generic_processor_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 819
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int generic_processor_info(int apicid, int version)
```

```json
{
  "name": "generic_processor_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_processor_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2401",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_lapic",
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/mpparse.c:MP_processor_info",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593840722,
      "name": "generic_processor_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071579413312,
      "name": "generic_processor_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 905
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int generic_processor_info(int apicid, int version)
```

```json
{
  "name": "generic_processor_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_processor_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2435",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_lapic",
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/mpparse.c:MP_processor_info",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595965556,
      "name": "generic_processor_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071579495488,
      "name": "generic_processor_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1090
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int generic_processor_info(int apicid, int version)
```

```json
{
  "name": "generic_processor_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_processor_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2449",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_lapic",
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/mpparse.c:MP_processor_info",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596483179,
      "name": "generic_processor_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071579507632,
      "name": "generic_processor_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int generic_processor_info(int apicid)
```

```json
{
  "name": "generic_processor_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_processor_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2415",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_lapic",
        "arch/x86/kernel/mpparse.c:MP_processor_info",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597379339,
      "name": "generic_processor_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579536384,
      "name": "generic_processor_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int generic_processor_info(int apicid, int version)
```

```json
{
  "name": "generic_processor_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_processor_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2396",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/mpparse.c:MP_processor_info",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/platform/sfi/sfi.c:sfi_parse_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579267029,
      "name": "generic_processor_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071579265792,
      "name": "generic_processor_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 650
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int generic_processor_info(int apicid, int version)
```

```json
{
  "name": "generic_processor_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_processor_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2396",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/mpparse.c:MP_processor_info",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/platform/sfi/sfi.c:sfi_parse_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579202450,
      "name": "generic_processor_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071579201232,
      "name": "generic_processor_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 650
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int generic_processor_info(int apicid, int version)
```

```json
{
  "name": "generic_processor_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_processor_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2396",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/mpparse.c:MP_processor_info",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/platform/sfi/sfi.c:sfi_parse_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268229,
      "name": "generic_processor_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071579266992,
      "name": "generic_processor_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 650
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int generic_processor_info(int apicid, int version)
```

```json
{
  "name": "generic_processor_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_processor_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2396",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/mpparse.c:MP_processor_info",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/platform/sfi/sfi.c:sfi_parse_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579273829,
      "name": "generic_processor_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071579272592,
      "name": "generic_processor_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 650
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int version</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int generic_processor_info(int apicid, int version)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int generic_processor_info(int apicid, int version)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int generic_processor_info(int apicid, int version)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int generic_processor_info(int apicid, int version)
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
