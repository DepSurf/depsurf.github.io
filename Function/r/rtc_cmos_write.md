# Function: <code>rtc_cmos_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rtc_cmos_write(unsigned char val, unsigned char addr)
```

```json
{
  "name": "rtc_cmos_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579076592,
      "name": "rtc_cmos_write",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:129",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss",
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss",
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss",
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss",
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss",
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss",
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss",
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss",
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss",
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss",
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss"
      ],
      "caller_func": [
        "arch/x86/kernel/reboot.c:machine_real_restart",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/base/power/trace.c:generate_pm_trace",
        "drivers/base/power/trace.c:generate_pm_trace",
        "drivers/base/power/trace.c:generate_pm_trace",
        "drivers/base/power/trace.c:generate_pm_trace",
        "drivers/base/power/trace.c:generate_pm_trace",
        "drivers/base/power/trace.c:generate_pm_trace",
        "drivers/base/power/trace.c:generate_pm_trace",
        "drivers/base/power/trace.c:generate_pm_trace",
        "drivers/base/power/trace.c:generate_pm_trace",
        "drivers/base/power/trace.c:generate_pm_trace",
        "drivers/base/power/trace.c:generate_pm_trace",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_write",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579076592,
      "name": "rtc_cmos_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void rtc_cmos_write(unsigned char val, unsigned char addr)
```

```json
{
  "name": "rtc_cmos_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579073104,
      "name": "rtc_cmos_write",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:129",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:machine_real_restart",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_write",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073104,
      "name": "rtc_cmos_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void rtc_cmos_write(unsigned char val, unsigned char addr)
```

```json
{
  "name": "rtc_cmos_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579072528,
      "name": "rtc_cmos_write",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:138",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:machine_real_restart",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_write",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579072528,
      "name": "rtc_cmos_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void rtc_cmos_write(unsigned char val, unsigned char addr)
```

```json
{
  "name": "rtc_cmos_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579064512,
      "name": "rtc_cmos_write",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:138",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:machine_real_restart",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_write",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579064512,
      "name": "rtc_cmos_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void rtc_cmos_write(unsigned char val, unsigned char addr)
```

```json
{
  "name": "rtc_cmos_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579073504,
      "name": "rtc_cmos_write",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:139",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:machine_real_restart",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_write",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073504,
      "name": "rtc_cmos_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void rtc_cmos_write(unsigned char val, unsigned char addr)
```

```json
{
  "name": "rtc_cmos_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579077904,
      "name": "rtc_cmos_write",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:139",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/reboot.c:machine_real_restart",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_write",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077904,
      "name": "rtc_cmos_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void rtc_cmos_write(unsigned char val, unsigned char addr)
```

```json
{
  "name": "rtc_cmos_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579082528,
      "name": "rtc_cmos_write",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:139",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/reboot.c:machine_real_restart",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_write",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579082528,
      "name": "rtc_cmos_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void rtc_cmos_write(unsigned char val, unsigned char addr)
```

```json
{
  "name": "rtc_cmos_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579092192,
      "name": "rtc_cmos_write",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:139",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/reboot.c:machine_real_restart",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_write",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579092192,
      "name": "rtc_cmos_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void rtc_cmos_write(unsigned char val, unsigned char addr)
```

```json
{
  "name": "rtc_cmos_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579094176,
      "name": "rtc_cmos_write",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:139",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/reboot.c:machine_real_restart",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_write",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579094176,
      "name": "rtc_cmos_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void rtc_cmos_write(unsigned char val, unsigned char addr)
```

```json
{
  "name": "rtc_cmos_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579106096,
      "name": "rtc_cmos_write",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:139",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/reboot.c:machine_real_restart",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_write",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579106096,
      "name": "rtc_cmos_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void rtc_cmos_write(unsigned char val, unsigned char addr)
```

```json
{
  "name": "rtc_cmos_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579105712,
      "name": "rtc_cmos_write",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:139",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/reboot.c:machine_real_restart",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_write",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579105712,
      "name": "rtc_cmos_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void rtc_cmos_write(unsigned char val, unsigned char addr)
```

```json
{
  "name": "rtc_cmos_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579112272,
      "name": "rtc_cmos_write",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:139",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/reboot.c:machine_real_restart",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_write",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579112272,
      "name": "rtc_cmos_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void rtc_cmos_write(unsigned char val, unsigned char addr)
```

```json
{
  "name": "rtc_cmos_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579137488,
      "name": "rtc_cmos_write",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:139",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/reboot.c:machine_real_restart",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_write",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579137488,
      "name": "rtc_cmos_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void rtc_cmos_write(unsigned char val, unsigned char addr)
```

```json
{
  "name": "rtc_cmos_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579174000,
      "name": "rtc_cmos_write",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:139",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/reboot.c:machine_real_restart",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_write",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579174000,
      "name": "rtc_cmos_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void rtc_cmos_write(unsigned char val, unsigned char addr)
```

```json
{
  "name": "rtc_cmos_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579228384,
      "name": "rtc_cmos_write",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:94",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/reboot.c:machine_real_restart",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_write",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579228384,
      "name": "rtc_cmos_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void rtc_cmos_write(unsigned char val, unsigned char addr)
```

```json
{
  "name": "rtc_cmos_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579234096,
      "name": "rtc_cmos_write",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:94",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/reboot.c:machine_real_restart",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_write",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579234096,
      "name": "rtc_cmos_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void rtc_cmos_write(unsigned char val, unsigned char addr)
```

```json
{
  "name": "rtc_cmos_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579262944,
      "name": "rtc_cmos_write",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:94",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/reboot.c:machine_real_restart",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_write",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579262944,
      "name": "rtc_cmos_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void rtc_cmos_write(unsigned char val, unsigned char addr)
```

```json
{
  "name": "rtc_cmos_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579094560,
      "name": "rtc_cmos_write",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:139",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/reboot.c:machine_real_restart",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_write",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579094560,
      "name": "rtc_cmos_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void rtc_cmos_write(unsigned char val, unsigned char addr)
```

```json
{
  "name": "rtc_cmos_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579026608,
      "name": "rtc_cmos_write",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:139",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/reboot.c:machine_real_restart",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_write",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579026608,
      "name": "rtc_cmos_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void rtc_cmos_write(unsigned char val, unsigned char addr)
```

```json
{
  "name": "rtc_cmos_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579094112,
      "name": "rtc_cmos_write",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:139",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/reboot.c:machine_real_restart",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_write",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579094112,
      "name": "rtc_cmos_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void rtc_cmos_write(unsigned char val, unsigned char addr)
```

```json
{
  "name": "rtc_cmos_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579098352,
      "name": "rtc_cmos_write",
      "external": true,
      "loc": "arch/x86/kernel/rtc.c:139",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/bootflag.c:sbf_init",
        "arch/x86/kernel/reboot.c:machine_real_restart",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_nvram_write",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579098352,
      "name": "rtc_cmos_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void rtc_cmos_write(unsigned char val, unsigned char addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void rtc_cmos_write(unsigned char val, unsigned char addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void rtc_cmos_write(unsigned char val, unsigned char addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void rtc_cmos_write(unsigned char val, unsigned char addr)
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
