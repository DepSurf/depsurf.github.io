# Function: <code>rtc_cmos_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr)
```

```json
{
  "name": "rtc_cmos_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579076560,
      "name": "rtc_cmos_read",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:116",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss",
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss",
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/power/trace.c:generate_pm_trace",
        "drivers/base/power/trace.c:generate_pm_trace",
        "drivers/base/power/trace.c:generate_pm_trace",
        "drivers/base/power/trace.c:generate_pm_trace",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579076560,
      "name": "rtc_cmos_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned char rtc_cmos_read(unsigned char addr)
```

```json
{
  "name": "rtc_cmos_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579073336,
      "name": "rtc_cmos_read",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:116",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073072,
      "name": "rtc_cmos_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned char rtc_cmos_read(unsigned char addr)
```

```json
{
  "name": "rtc_cmos_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579072785,
      "name": "rtc_cmos_read",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:125",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579072496,
      "name": "rtc_cmos_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr)
```

```json
{
  "name": "rtc_cmos_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579064769,
      "name": "rtc_cmos_read",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:125",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579064480,
      "name": "rtc_cmos_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned char rtc_cmos_read(unsigned char addr)
```

```json
{
  "name": "rtc_cmos_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579073761,
      "name": "rtc_cmos_read",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:126",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073472,
      "name": "rtc_cmos_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned char rtc_cmos_read(unsigned char addr)
```

```json
{
  "name": "rtc_cmos_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579078113,
      "name": "rtc_cmos_read",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:126",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077872,
      "name": "rtc_cmos_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned char rtc_cmos_read(unsigned char addr)
```

```json
{
  "name": "rtc_cmos_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579082737,
      "name": "rtc_cmos_read",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:126",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579082496,
      "name": "rtc_cmos_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned char rtc_cmos_read(unsigned char addr)
```

```json
{
  "name": "rtc_cmos_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579092431,
      "name": "rtc_cmos_read",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:126",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579092160,
      "name": "rtc_cmos_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned char rtc_cmos_read(unsigned char addr)
```

```json
{
  "name": "rtc_cmos_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579094415,
      "name": "rtc_cmos_read",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:126",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579094144,
      "name": "rtc_cmos_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned char rtc_cmos_read(unsigned char addr)
```

```json
{
  "name": "rtc_cmos_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579106319,
      "name": "rtc_cmos_read",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:126",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579106064,
      "name": "rtc_cmos_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned char rtc_cmos_read(unsigned char addr)
```

```json
{
  "name": "rtc_cmos_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579105935,
      "name": "rtc_cmos_read",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:126",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579105680,
      "name": "rtc_cmos_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned char rtc_cmos_read(unsigned char addr)
```

```json
{
  "name": "rtc_cmos_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579112495,
      "name": "rtc_cmos_read",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:126",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579112240,
      "name": "rtc_cmos_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned char rtc_cmos_read(unsigned char addr)
```

```json
{
  "name": "rtc_cmos_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579137726,
      "name": "rtc_cmos_read",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:126",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579137456,
      "name": "rtc_cmos_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned char rtc_cmos_read(unsigned char addr)
```

```json
{
  "name": "rtc_cmos_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579174306,
      "name": "rtc_cmos_read",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:126",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579173968,
      "name": "rtc_cmos_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
unsigned char rtc_cmos_read(unsigned char addr)
```

```json
{
  "name": "rtc_cmos_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579228336,
      "name": "rtc_cmos_read",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:81",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579228336,
      "name": "rtc_cmos_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
unsigned char rtc_cmos_read(unsigned char addr)
```

```json
{
  "name": "rtc_cmos_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579234048,
      "name": "rtc_cmos_read",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:81",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579234048,
      "name": "rtc_cmos_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr)
```

```json
{
  "name": "rtc_cmos_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579262896,
      "name": "rtc_cmos_read",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:81",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579262896,
      "name": "rtc_cmos_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr)
```

```json
{
  "name": "rtc_cmos_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579094799,
      "name": "rtc_cmos_read",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:126",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579094528,
      "name": "rtc_cmos_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned char rtc_cmos_read(unsigned char addr)
```

```json
{
  "name": "rtc_cmos_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579026847,
      "name": "rtc_cmos_read",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:126",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579026576,
      "name": "rtc_cmos_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned char rtc_cmos_read(unsigned char addr)
```

```json
{
  "name": "rtc_cmos_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579094351,
      "name": "rtc_cmos_read",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:126",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579094080,
      "name": "rtc_cmos_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned char rtc_cmos_read(unsigned char addr)
```

```json
{
  "name": "rtc_cmos_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579098591,
      "name": "rtc_cmos_read",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:126",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579098320,
      "name": "rtc_cmos_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned char rtc_cmos_read(unsigned char addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr)
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
