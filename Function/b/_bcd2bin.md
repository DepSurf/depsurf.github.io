# Function: <code>_bcd2bin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583006176,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:4",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
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
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583006176,
      "name": "_bcd2bin",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583296672,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:4",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
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
      "addr": 18446744071583296672,
      "name": "_bcd2bin",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583415536,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:4",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
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
      "addr": 18446744071583415536,
      "name": "_bcd2bin",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583437264,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:4",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583437264,
      "name": "_bcd2bin",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583617184,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:5",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583617184,
      "name": "_bcd2bin",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583833632,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:5",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583833632,
      "name": "_bcd2bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583917328,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:5",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583917328,
      "name": "_bcd2bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584097216,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:5",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584097216,
      "name": "_bcd2bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584219856,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:5",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584219856,
      "name": "_bcd2bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584625792,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:5",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584625792,
      "name": "_bcd2bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584744192,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:5",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584744192,
      "name": "_bcd2bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584772336,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:5",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584772336,
      "name": "_bcd2bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585202224,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:5",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585202224,
      "name": "_bcd2bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586038672,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:5",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586038672,
      "name": "_bcd2bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587020912,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:5",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587020912,
      "name": "_bcd2bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587275952,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:5",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587275952,
      "name": "_bcd2bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587564688,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:5",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587564688,
      "name": "_bcd2bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496093152,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:5",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mv.c:mv_rtc_read_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_time",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496093152,
      "name": "_bcd2bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229420080,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:5",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_time",
        "drivers/rtc/rtc-omap.c:bcd2tm",
        "drivers/rtc/rtc-omap.c:bcd2tm",
        "drivers/rtc/rtc-omap.c:bcd2tm",
        "drivers/rtc/rtc-omap.c:bcd2tm",
        "drivers/rtc/rtc-omap.c:bcd2tm",
        "drivers/rtc/rtc-omap.c:bcd2tm",
        "drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_read_time",
        "drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_read_time",
        "drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_read_time",
        "drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_read_time",
        "drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_read_time",
        "drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_read_time",
        "drivers/rtc/rtc-pl031.c:pl031_stv2_time_to_tm",
        "drivers/rtc/rtc-pl031.c:pl031_stv2_time_to_tm",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_getalarm",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_getalarm",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_getalarm",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_getalarm",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_getalarm",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_getalarm",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_gettime",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_gettime",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_gettime",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_gettime",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_gettime",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_gettime",
        "drivers/rtc/rtc-twl.c:twl_rtc_read_alarm",
        "drivers/rtc/rtc-twl.c:twl_rtc_read_alarm",
        "drivers/rtc/rtc-twl.c:twl_rtc_read_alarm",
        "drivers/rtc/rtc-twl.c:twl_rtc_read_alarm",
        "drivers/rtc/rtc-twl.c:twl_rtc_read_alarm",
        "drivers/rtc/rtc-twl.c:twl_rtc_read_alarm",
        "drivers/rtc/rtc-twl.c:twl_rtc_read_time",
        "drivers/rtc/rtc-twl.c:twl_rtc_read_time",
        "drivers/rtc/rtc-twl.c:twl_rtc_read_time",
        "drivers/rtc/rtc-twl.c:twl_rtc_read_time",
        "drivers/rtc/rtc-twl.c:twl_rtc_read_time",
        "drivers/rtc/rtc-twl.c:twl_rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229420080,
      "name": "_bcd2bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290335472,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:5",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/opal-rtc.c:opal_get_boot_time",
        "arch/powerpc/platforms/powernv/opal-rtc.c:opal_get_boot_time",
        "arch/powerpc/platforms/powernv/opal-rtc.c:opal_get_boot_time",
        "arch/powerpc/platforms/powernv/opal-rtc.c:opal_get_boot_time",
        "arch/powerpc/platforms/powernv/opal-rtc.c:opal_get_boot_time",
        "arch/powerpc/platforms/powernv/opal-rtc.c:opal_get_boot_time",
        "arch/powerpc/platforms/powernv/opal-rtc.c:opal_get_boot_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-opal.c:opal_to_tm",
        "drivers/rtc/rtc-opal.c:opal_to_tm",
        "drivers/rtc/rtc-opal.c:opal_to_tm",
        "drivers/rtc/rtc-opal.c:opal_to_tm",
        "drivers/rtc/rtc-opal.c:opal_to_tm",
        "drivers/rtc/rtc-opal.c:opal_to_tm",
        "drivers/rtc/rtc-opal.c:opal_to_tm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290335472,
      "name": "_bcd2bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275162156,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:5",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275162156,
      "name": "_bcd2bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584188592,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:5",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
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
      "addr": 18446744071584188592,
      "name": "_bcd2bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584123824,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:5",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123824,
      "name": "_bcd2bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584172352,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:5",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584172352,
      "name": "_bcd2bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int _bcd2bin(unsigned char val)
```

```json
{
  "name": "_bcd2bin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584276656,
      "name": "_bcd2bin",
      "external": true,
      "loc": "lib/bcd.c:5",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584276656,
      "name": "_bcd2bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
