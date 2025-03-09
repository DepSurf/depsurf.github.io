# Function: <code>wbinvd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void wbinvd()
```

```json
{
  "name": "wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579156575,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183148,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595054541,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271627,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/kernel/tce_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tce_64.c:tce_build",
        "arch/x86/kernel/tce_64.c:tce_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288942,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583152553,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:__wbinvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583544963,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_hibernation_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ]
    },
    {
      "addr": 18446744071583671269,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "drivers/acpi/acpica/hwesleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583674492,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "drivers/acpi/acpica/hwsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583677017,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "drivers/acpi/acpica/hwxfsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583745356,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_freeze",
        "drivers/acpi/processor_idle.c:acpi_idle_enter"
      ]
    },
    {
      "addr": 18446744071584205577,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:ipi_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583544963,
      "name": "wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071583745356,
      "name": "wbinvd",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void wbinvd()
```

```json
{
  "name": "wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579156796,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:115",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183488,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:115",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595220365,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:115",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271027,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:115",
      "file": "arch/x86/kernel/tce_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tce_64.c:tce_free",
        "arch/x86/kernel/tce_64.c:tce_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289239,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:115",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583447913,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:115",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:__wbinvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583865995,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:115",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_hibernation_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ]
    },
    {
      "addr": 18446744071583994605,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:115",
      "file": "drivers/acpi/acpica/hwesleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583998190,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:115",
      "file": "drivers/acpi/acpica/hwsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584000710,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:115",
      "file": "drivers/acpi/acpica/hwxfsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584069798,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:115",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_freeze",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ]
    },
    {
      "addr": 18446744071584544857,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:115",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:ipi_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583865995,
      "name": "wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071584069798,
      "name": "wbinvd",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void wbinvd()
```

```json
{
  "name": "wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579166092,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579193993,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595463449,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579286467,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "arch/x86/kernel/tce_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tce_64.c:tce_free",
        "arch/x86/kernel/tce_64.c:tce_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579303998,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583575561,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:__wbinvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584005071,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_hibernation_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ]
    },
    {
      "addr": 18446744071584135996,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "drivers/acpi/acpica/hwesleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584139638,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "drivers/acpi/acpica/hwsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584142158,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "drivers/acpi/acpica/hwxfsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584212346,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_freeze",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ]
    },
    {
      "addr": 18446744071584726809,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:ipi_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584005071,
      "name": "wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071584212346,
      "name": "wbinvd",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579165948,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192207,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596384630,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579283331,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "arch/x86/kernel/tce_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tce_64.c:tce_free",
        "arch/x86/kernel/tce_64.c:tce_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579301726,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583614313,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:__wbinvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584055818,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_hibernation_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584203139,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "drivers/acpi/acpica/hwesleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584206924,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "drivers/acpi/acpica/hwsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584209444,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "drivers/acpi/acpica/hwxfsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584287101,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_freeze",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584808793,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:106",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:ipi_handler"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void wbinvd()
```

```json
{
  "name": "wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579180652,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208027,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ]
    },
    {
      "addr": 18446744071602703141,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302019,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "arch/x86/kernel/tce_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tce_64.c:tce_free",
        "arch/x86/kernel/tce_64.c:tce_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322625,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__cpa_flush_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602723807,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583860313,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:__wbinvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584325866,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_hibernation_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584531598,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "drivers/acpi/acpica/hwesleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584537154,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "drivers/acpi/acpica/hwsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584541036,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "drivers/acpi/acpica/hwxfsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584684477,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585229561,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:ipi_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579201296,
      "name": "wbinvd",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void wbinvd()
```

```json
{
  "name": "wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579192092,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219399,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ]
    },
    {
      "addr": 18446744071602875712,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579314003,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "arch/x86/kernel/tce_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tce_64.c:tce_free",
        "arch/x86/kernel/tce_64.c:tce_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333505,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__cpa_flush_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602895554,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584060917,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:__wbinvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584546421,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_hibernation_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584755937,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "drivers/acpi/acpica/hwesleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584761488,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "drivers/acpi/acpica/hwsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584765516,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "drivers/acpi/acpica/hwxfsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584910621,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585466389,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:102",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:ipi_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213184,
      "name": "wbinvd",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void wbinvd()
```

```json
{
  "name": "wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579181532,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579243089,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ]
    },
    {
      "addr": 18446744071604672987,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338659,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/tce_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tce_64.c:tce_free",
        "arch/x86/kernel/tce_64.c:tce_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579360049,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__cpa_flush_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604692863,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584145045,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:__wbinvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584643637,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_hibernation_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584857511,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "drivers/acpi/acpica/hwesleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584862284,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "drivers/acpi/acpica/hwsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584866312,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "drivers/acpi/acpica/hwxfsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585014509,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585589717,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:ipi_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236864,
      "name": "wbinvd",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579194161,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579257097,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604771913,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579353875,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/tce_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tce_64.c:tce_free",
        "arch/x86/kernel/tce_64.c:tce_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579374650,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__cpa_flush_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604792858,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584335109,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:__wbinvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584842869,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_hibernation_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585061253,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "drivers/acpi/acpica/hwesleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585066066,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "drivers/acpi/acpica/hwsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585070067,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "drivers/acpi/acpica/hwxfsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585218880,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585809893,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:ipi_handler"
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
  "name": "wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579196465,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258761,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604797751,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579358211,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/tce_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tce_64.c:tce_free",
        "arch/x86/kernel/tce_64.c:tce_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579378938,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__cpa_flush_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604818579,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584469781,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:__wbinvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584978661,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_hibernation_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585197338,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/acpi/acpica/hwesleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585202400,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/acpi/acpica/hwsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585206401,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/acpi/acpica/hwxfsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585355312,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585952533,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:ipi_handler"
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
void wbinvd()
```

```json
{
  "name": "wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579217274,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579285175,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ]
    },
    {
      "addr": 18446744071609140362,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417670,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609156711,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585033605,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:__wbinvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585675813,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585902712,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "drivers/acpi/acpica/hwesleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585907918,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "drivers/acpi/acpica/hwsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585911886,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "drivers/acpi/acpica/hwxfsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586062416,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586692565,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:ipi_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276992,
      "name": "wbinvd",
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
void wbinvd()
```

```json
{
  "name": "wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579211994,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292503,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ]
    },
    {
      "addr": 18446744071612210411,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417702,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612227206,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585185493,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:__wbinvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585798421,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586024048,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "drivers/acpi/acpica/hwesleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586029532,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "drivers/acpi/acpica/hwsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586033648,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "drivers/acpi/acpica/hwxfsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586185159,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586795301,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:158",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:ipi_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579284128,
      "name": "wbinvd",
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
void wbinvd()
```

```json
{
  "name": "wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579214422,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295175,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ]
    },
    {
      "addr": 18446744071614351776,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579420774,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614368002,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585067445,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:__wbinvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585679573,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585901064,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "drivers/acpi/acpica/hwesleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585906546,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "drivers/acpi/acpica/hwsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585910663,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "drivers/acpi/acpica/hwxfsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586061015,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586675669,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:ipi_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579286816,
      "name": "wbinvd",
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
void wbinvd()
```

```json
{
  "name": "wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579252390,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579342295,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ]
    },
    {
      "addr": 18446744071615281750,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579484358,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615299552,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585514181,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:__wbinvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586159493,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586388576,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "drivers/acpi/acpica/hwesleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586394397,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "drivers/acpi/acpica/hwsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586553942,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587223653,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:ipi_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579330560,
      "name": "wbinvd",
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
void wbinvd()
```

```json
{
  "name": "wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579304753,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579403368,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ]
    },
    {
      "addr": 18446744071617060696,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579563856,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617079709,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586665205,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:__wbinvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587637105,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "drivers/acpi/acpica/hwesleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587643354,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "drivers/acpi/acpica/hwsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594744134,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588530261,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:ipi_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579391504,
      "name": "wbinvd",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void wbinvd()
```

```json
{
  "name": "wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579282458,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_disable",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579483944,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ]
    },
    {
      "addr": 18446744071627706987,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579671728,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627733824,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587913397,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:__wbinvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588937114,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "drivers/acpi/acpica/hwesleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588945353,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "drivers/acpi/acpica/hwsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596496790,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589974837,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:ipi_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579470144,
      "name": "wbinvd",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579288970,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:183",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_disable",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579496084,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:183",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead",
        "arch/x86/kernel/smpboot.c:mwait_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619464331,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:183",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579685824,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:183",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071619493035,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:183",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588187333,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:183",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:__wbinvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589227118,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:183",
      "file": "drivers/acpi/acpica/hwesleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589235369,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:183",
      "file": "drivers/acpi/acpica/hwsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596948737,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:183",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590284437,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:183",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:ipi_handler"
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
  "name": "wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579318234,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_disable",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579525828,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead",
        "arch/x86/kernel/smpboot.c:mwait_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621760843,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579720352,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071621789995,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588479333,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:__wbinvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589533630,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "drivers/acpi/acpica/hwesleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589541881,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "drivers/acpi/acpica/hwsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597876257,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590625573,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:ipi_handler"
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
  "name": "wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579195313,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579257465,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604711693,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354115,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/tce_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tce_64.c:tce_free",
        "arch/x86/kernel/tce_64.c:tce_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579374842,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__cpa_flush_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604732459,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584438533,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:__wbinvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584924261,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_hibernation_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585072401,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/acpi/acpica/hwesleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585076010,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/acpi/acpica/hwsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585078156,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/acpi/acpica/hwxfsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585156640,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585713509,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:ipi_handler"
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
  "name": "wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579130081,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:182",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192659,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:182",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604679641,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:182",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579286305,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:182",
      "file": "arch/x86/kernel/tce_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tce_64.c:tce_free",
        "arch/x86/kernel/tce_64.c:tce_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305774,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:182",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__cpa_flush_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604700182,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:182",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584373717,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:182",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:__wbinvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584829781,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:182",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_hibernation_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584987880,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:182",
      "file": "drivers/acpi/acpica/hwesleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584991484,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:182",
      "file": "drivers/acpi/acpica/hwsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584993582,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:182",
      "file": "drivers/acpi/acpica/hwxfsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585070109,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:182",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585572709,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:182",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:ipi_handler"
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
  "name": "wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579196385,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258665,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604789260,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354035,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/tce_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tce_64.c:tce_free",
        "arch/x86/kernel/tce_64.c:tce_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579374762,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__cpa_flush_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604810026,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584421445,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:__wbinvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584930245,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_hibernation_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585148922,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/acpi/acpica/hwesleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585153984,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/acpi/acpica/hwsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585157985,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/acpi/acpica/hwxfsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585306896,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585902549,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:ipi_handler"
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
  "name": "wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579201665,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579264265,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604801881,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362483,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/tce_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tce_64.c:tce_free",
        "arch/x86/kernel/tce_64.c:tce_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383242,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__cpa_flush_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604822736,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584527525,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:__wbinvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585036389,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_hibernation_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585255082,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/acpi/acpica/hwesleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585260144,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/acpi/acpica/hwsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585264145,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/acpi/acpica/hwxfsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585413040,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586010533,
      "name": "wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:ipi_handler"
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void wbinvd()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void wbinvd()
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void wbinvd()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void wbinvd()
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void wbinvd()
```
</details>
</li>
</ul>
