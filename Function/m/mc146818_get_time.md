# Function: <code>mc146818_get_time</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
unsigned int mc146818_get_time(struct rtc_time * time)
```

```json
{
  "name": "mc146818_get_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586017184,
      "name": "mc146818_get_time",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:24",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586017184,
      "name": "mc146818_get_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
unsigned int mc146818_get_time(struct rtc_time * time)
```

```json
{
  "name": "mc146818_get_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586212992,
      "name": "mc146818_get_time",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:24",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586212992,
      "name": "mc146818_get_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
unsigned int mc146818_get_time(struct rtc_time * time)
```

```json
{
  "name": "mc146818_get_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586302080,
      "name": "mc146818_get_time",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:24",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586302080,
      "name": "mc146818_get_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
unsigned int mc146818_get_time(struct rtc_time * time)
```

```json
{
  "name": "mc146818_get_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586765568,
      "name": "mc146818_get_time",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:24",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586765568,
      "name": "mc146818_get_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
unsigned int mc146818_get_time(struct rtc_time * time)
```

```json
{
  "name": "mc146818_get_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587037456,
      "name": "mc146818_get_time",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:24",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587037456,
      "name": "mc146818_get_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
unsigned int mc146818_get_time(struct rtc_time * time)
```

```json
{
  "name": "mc146818_get_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587197552,
      "name": "mc146818_get_time",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:24",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587197552,
      "name": "mc146818_get_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
unsigned int mc146818_get_time(struct rtc_time * time)
```

```json
{
  "name": "mc146818_get_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587463056,
      "name": "mc146818_get_time",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:25",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587463056,
      "name": "mc146818_get_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
unsigned int mc146818_get_time(struct rtc_time * time)
```

```json
{
  "name": "mc146818_get_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587666176,
      "name": "mc146818_get_time",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:25",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587666176,
      "name": "mc146818_get_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
unsigned int mc146818_get_time(struct rtc_time * time)
```

```json
{
  "name": "mc146818_get_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588533600,
      "name": "mc146818_get_time",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:25",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/rtc/rtc-cmos.c:cmos_check_wkalrm",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588533600,
      "name": "mc146818_get_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
unsigned int mc146818_get_time(struct rtc_time * time)
```

```json
{
  "name": "mc146818_get_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588558176,
      "name": "mc146818_get_time",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:11",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/rtc/rtc-cmos.c:cmos_check_wkalrm",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588558176,
      "name": "mc146818_get_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
unsigned int mc146818_get_time(struct rtc_time * time)
```

```json
{
  "name": "mc146818_get_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588441488,
      "name": "mc146818_get_time",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:11",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588441488,
      "name": "mc146818_get_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
unsigned int mc146818_get_time(struct rtc_time * time)
```

```json
{
  "name": "mc146818_get_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589108944,
      "name": "mc146818_get_time",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:11",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589108944,
      "name": "mc146818_get_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
int mc146818_get_time(struct rtc_time * time)
```

```json
{
  "name": "mc146818_get_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590556432,
      "name": "mc146818_get_time",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:133",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/rtc/rtc-cmos.c:cmos_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590556432,
      "name": "mc146818_get_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int mc146818_get_time(struct rtc_time * time)
```

```json
{
  "name": "mc146818_get_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592210656,
      "name": "mc146818_get_time",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:133",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/rtc/rtc-cmos.c:cmos_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592210656,
      "name": "mc146818_get_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
int mc146818_get_time(struct rtc_time * time)
```

```json
{
  "name": "mc146818_get_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592634944,
      "name": "mc146818_get_time",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:133",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/rtc/rtc-cmos.c:cmos_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592634944,
      "name": "mc146818_get_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
int mc146818_get_time(struct rtc_time * time, int timeout)
```

```json
{
  "name": "mc146818_get_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593379888,
      "name": "mc146818_get_time",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:154",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/rtc/rtc-cmos.c:cmos_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593379888,
      "name": "mc146818_get_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
unsigned int mc146818_get_time(struct rtc_time * time)
```

```json
{
  "name": "mc146818_get_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233327012,
      "name": "mc146818_get_time",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:25",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233327012,
      "name": "mc146818_get_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
unsigned int mc146818_get_time(struct rtc_time * time)
```

```json
{
  "name": "mc146818_get_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294281296,
      "name": "mc146818_get_time",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:25",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294281296,
      "name": "mc146818_get_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2332
    }
  ]
}
```
</details>
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
unsigned int mc146818_get_time(struct rtc_time * time)
```

```json
{
  "name": "mc146818_get_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587349936,
      "name": "mc146818_get_time",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:25",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587349936,
      "name": "mc146818_get_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
unsigned int mc146818_get_time(struct rtc_time * time)
```

```json
{
  "name": "mc146818_get_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587118240,
      "name": "mc146818_get_time",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:25",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587118240,
      "name": "mc146818_get_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
unsigned int mc146818_get_time(struct rtc_time * time)
```

```json
{
  "name": "mc146818_get_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587617424,
      "name": "mc146818_get_time",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:25",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587617424,
      "name": "mc146818_get_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
unsigned int mc146818_get_time(struct rtc_time * time)
```

```json
{
  "name": "mc146818_get_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587728640,
      "name": "mc146818_get_time",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:25",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587728640,
      "name": "mc146818_get_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
unsigned int mc146818_get_time(struct rtc_time * time)
```
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned int</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
<b>Param added. </b>
<code>int timeout</code>
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
unsigned int mc146818_get_time(struct rtc_time * time)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
unsigned int mc146818_get_time(struct rtc_time * time)
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
