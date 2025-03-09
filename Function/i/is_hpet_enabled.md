# Function: <code>is_hpet_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int is_hpet_enabled()
```

```json
{
  "name": "is_hpet_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579246565,
      "name": "is_hpet_enabled",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:133",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_register_irq_handler",
        "arch/x86/kernel/hpet.c:hpet_unregister_irq_handler",
        "arch/x86/kernel/hpet.c:hpet_set_alarm_time",
        "arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579246832,
      "name": "is_hpet_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int is_hpet_enabled()
```

```json
{
  "name": "is_hpet_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579246325,
      "name": "is_hpet_enabled",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:133",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq",
        "arch/x86/kernel/hpet.c:hpet_set_alarm_time",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "arch/x86/kernel/hpet.c:hpet_unregister_irq_handler",
        "arch/x86/kernel/hpet.c:hpet_register_irq_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579246368,
      "name": "is_hpet_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int is_hpet_enabled()
```

```json
{
  "name": "is_hpet_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579258757,
      "name": "is_hpet_enabled",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:133",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq",
        "arch/x86/kernel/hpet.c:hpet_set_alarm_time",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "arch/x86/kernel/hpet.c:hpet_unregister_irq_handler",
        "arch/x86/kernel/hpet.c:hpet_register_irq_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579258800,
      "name": "is_hpet_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int is_hpet_enabled()
```

```json
{
  "name": "is_hpet_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579254501,
      "name": "is_hpet_enabled",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:133",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "arch/x86/kernel/hpet.c:hpet_register_irq_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579253888,
      "name": "is_hpet_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int is_hpet_enabled()
```

```json
{
  "name": "is_hpet_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579271269,
      "name": "is_hpet_enabled",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:133",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "arch/x86/kernel/hpet.c:hpet_register_irq_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270656,
      "name": "is_hpet_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int is_hpet_enabled()
```

```json
{
  "name": "is_hpet_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579282677,
      "name": "is_hpet_enabled",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:134",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq",
        "arch/x86/kernel/hpet.c:hpet_set_alarm_time",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "arch/x86/kernel/hpet.c:hpet_unregister_irq_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579281984,
      "name": "is_hpet_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int is_hpet_enabled()
```

```json
{
  "name": "is_hpet_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579306629,
      "name": "is_hpet_enabled",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:130",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq",
        "arch/x86/kernel/hpet.c:hpet_set_alarm_time",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "arch/x86/kernel/hpet.c:hpet_unregister_irq_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305936,
      "name": "is_hpet_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int is_hpet_enabled()
```

```json
{
  "name": "is_hpet_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579322901,
      "name": "is_hpet_enabled",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:133",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq",
        "arch/x86/kernel/hpet.c:hpet_set_alarm_time",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "arch/x86/kernel/hpet.c:hpet_unregister_irq_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322384,
      "name": "is_hpet_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int is_hpet_enabled()
```

```json
{
  "name": "is_hpet_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579326949,
      "name": "is_hpet_enabled",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:133",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq",
        "arch/x86/kernel/hpet.c:hpet_set_alarm_time",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "arch/x86/kernel/hpet.c:hpet_unregister_irq_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326432,
      "name": "is_hpet_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int is_hpet_enabled()
```

```json
{
  "name": "is_hpet_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579358517,
      "name": "is_hpet_enabled",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:133",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq",
        "arch/x86/kernel/hpet.c:hpet_set_alarm_time",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "arch/x86/kernel/hpet.c:hpet_unregister_irq_handler",
        "arch/x86/kernel/hpet.c:hpet_register_irq_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579355600,
      "name": "is_hpet_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int is_hpet_enabled()
```

```json
{
  "name": "is_hpet_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579358373,
      "name": "is_hpet_enabled",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:134",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq",
        "arch/x86/kernel/hpet.c:hpet_set_alarm_time",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "arch/x86/kernel/hpet.c:hpet_unregister_irq_handler",
        "arch/x86/kernel/hpet.c:hpet_register_irq_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579355104,
      "name": "is_hpet_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int is_hpet_enabled()
```

```json
{
  "name": "is_hpet_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579362325,
      "name": "is_hpet_enabled",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:134",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq",
        "arch/x86/kernel/hpet.c:hpet_set_alarm_time",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "arch/x86/kernel/hpet.c:hpet_unregister_irq_handler",
        "arch/x86/kernel/hpet.c:hpet_register_irq_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359632,
      "name": "is_hpet_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int is_hpet_enabled()
```

```json
{
  "name": "is_hpet_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579422549,
      "name": "is_hpet_enabled",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:135",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq",
        "arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq",
        "arch/x86/kernel/hpet.c:hpet_set_alarm_time",
        "arch/x86/kernel/hpet.c:hpet_set_alarm_time",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "arch/x86/kernel/hpet.c:hpet_unregister_irq_handler",
        "arch/x86/kernel/hpet.c:hpet_unregister_irq_handler",
        "arch/x86/kernel/hpet.c:hpet_register_irq_handler",
        "arch/x86/kernel/hpet.c:hpet_register_irq_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592078782,
      "name": "is_hpet_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579422256,
      "name": "is_hpet_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int is_hpet_enabled()
```

```json
{
  "name": "is_hpet_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579491269,
      "name": "is_hpet_enabled",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:135",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq",
        "arch/x86/kernel/hpet.c:hpet_set_alarm_time",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "arch/x86/kernel/hpet.c:hpet_register_irq_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593845260,
      "name": "is_hpet_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579490944,
      "name": "is_hpet_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int is_hpet_enabled()
```

```json
{
  "name": "is_hpet_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579585957,
      "name": "is_hpet_enabled",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:135",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq",
        "arch/x86/kernel/hpet.c:hpet_set_alarm_time",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "arch/x86/kernel/hpet.c:hpet_register_irq_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595966977,
      "name": "is_hpet_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579585600,
      "name": "is_hpet_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int is_hpet_enabled()
```

```json
{
  "name": "is_hpet_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579598453,
      "name": "is_hpet_enabled",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:135",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq",
        "arch/x86/kernel/hpet.c:hpet_set_alarm_time",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "arch/x86/kernel/hpet.c:hpet_register_irq_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596484546,
      "name": "is_hpet_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579598096,
      "name": "is_hpet_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int is_hpet_enabled()
```

```json
{
  "name": "is_hpet_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579628213,
      "name": "is_hpet_enabled",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:135",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq",
        "arch/x86/kernel/hpet.c:hpet_set_alarm_time",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "arch/x86/kernel/hpet.c:hpet_register_irq_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597381160,
      "name": "is_hpet_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579627856,
      "name": "is_hpet_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int is_hpet_enabled()
```

```json
{
  "name": "is_hpet_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579322853,
      "name": "is_hpet_enabled",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:133",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq",
        "arch/x86/kernel/hpet.c:hpet_set_alarm_time",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "arch/x86/kernel/hpet.c:hpet_unregister_irq_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322336,
      "name": "is_hpet_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int is_hpet_enabled()
```

```json
{
  "name": "is_hpet_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579257365,
      "name": "is_hpet_enabled",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:133",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq",
        "arch/x86/kernel/hpet.c:hpet_set_alarm_time",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "arch/x86/kernel/hpet.c:hpet_unregister_irq_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256848,
      "name": "is_hpet_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int is_hpet_enabled()
```

```json
{
  "name": "is_hpet_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579322773,
      "name": "is_hpet_enabled",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:133",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq",
        "arch/x86/kernel/hpet.c:hpet_set_alarm_time",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "arch/x86/kernel/hpet.c:hpet_unregister_irq_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322256,
      "name": "is_hpet_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int is_hpet_enabled()
```

```json
{
  "name": "is_hpet_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579331061,
      "name": "is_hpet_enabled",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:133",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq",
        "arch/x86/kernel/hpet.c:hpet_set_alarm_time",
        "arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit",
        "arch/x86/kernel/hpet.c:hpet_unregister_irq_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_interrupt",
        "drivers/rtc/rtc-cmos.c:cmos_procfs",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_irq_disable",
        "drivers/rtc/rtc-cmos.c:cmos_checkintr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579330544,
      "name": "is_hpet_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int is_hpet_enabled()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int is_hpet_enabled()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int is_hpet_enabled()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int is_hpet_enabled()
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
