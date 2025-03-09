# Function: <code>hpet_readl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int hpet_readl(unsigned int a)
```

```json
{
  "name": "hpet_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579246054,
      "name": "hpet_readl",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:62",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:hpet_legacy_shutdown",
        "arch/x86/kernel/hpet.c:hpet_legacy_set_oneshot",
        "arch/x86/kernel/hpet.c:hpet_legacy_next_event",
        "arch/x86/kernel/hpet.c:hpet_legacy_next_event",
        "arch/x86/kernel/hpet.c:hpet_msi_shutdown",
        "arch/x86/kernel/hpet.c:hpet_msi_set_oneshot",
        "arch/x86/kernel/hpet.c:hpet_msi_next_event",
        "arch/x86/kernel/hpet.c:hpet_msi_next_event",
        "arch/x86/kernel/hpet.c:read_hpet",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:hpet_resume",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_msi_unmask",
        "arch/x86/kernel/hpet.c:hpet_msi_mask",
        "arch/x86/kernel/hpet.c:hpet_msi_read",
        "arch/x86/kernel/hpet.c:hpet_msi_read",
        "arch/x86/kernel/hpet.c:hpet_disable",
        "arch/x86/kernel/hpet.c:hpet_disable"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_read_refs",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579250176,
      "name": "hpet_readl",
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
unsigned int hpet_readl(unsigned int a)
```

```json
{
  "name": "hpet_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579247934,
      "name": "hpet_readl",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:62",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_disable",
        "arch/x86/kernel/hpet.c:hpet_disable",
        "arch/x86/kernel/hpet.c:read_hpet",
        "arch/x86/kernel/hpet.c:hpet_msi_next_event",
        "arch/x86/kernel/hpet.c:hpet_msi_next_event",
        "arch/x86/kernel/hpet.c:hpet_msi_set_oneshot",
        "arch/x86/kernel/hpet.c:hpet_msi_shutdown",
        "arch/x86/kernel/hpet.c:hpet_msi_read",
        "arch/x86/kernel/hpet.c:hpet_msi_read",
        "arch/x86/kernel/hpet.c:hpet_msi_mask",
        "arch/x86/kernel/hpet.c:hpet_msi_unmask",
        "arch/x86/kernel/hpet.c:hpet_legacy_next_event",
        "arch/x86/kernel/hpet.c:hpet_legacy_next_event",
        "arch/x86/kernel/hpet.c:hpet_legacy_set_oneshot",
        "arch/x86/kernel/hpet.c:hpet_legacy_shutdown",
        "arch/x86/kernel/hpet.c:hpet_resume",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:tsc_read_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579249296,
      "name": "hpet_readl",
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
unsigned int hpet_readl(unsigned int a)
```

```json
{
  "name": "hpet_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579260334,
      "name": "hpet_readl",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:62",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_disable",
        "arch/x86/kernel/hpet.c:hpet_disable",
        "arch/x86/kernel/hpet.c:hpet_msi_next_event",
        "arch/x86/kernel/hpet.c:hpet_msi_next_event",
        "arch/x86/kernel/hpet.c:hpet_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_set_oneshot",
        "arch/x86/kernel/hpet.c:hpet_msi_shutdown",
        "arch/x86/kernel/hpet.c:hpet_msi_read",
        "arch/x86/kernel/hpet.c:hpet_msi_read",
        "arch/x86/kernel/hpet.c:hpet_msi_mask",
        "arch/x86/kernel/hpet.c:hpet_msi_unmask",
        "arch/x86/kernel/hpet.c:hpet_legacy_next_event",
        "arch/x86/kernel/hpet.c:hpet_legacy_next_event",
        "arch/x86/kernel/hpet.c:hpet_legacy_resume",
        "arch/x86/kernel/hpet.c:hpet_legacy_set_oneshot",
        "arch/x86/kernel/hpet.c:hpet_legacy_shutdown",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:tsc_read_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261984,
      "name": "hpet_readl",
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
unsigned int hpet_readl(unsigned int a)
```

```json
{
  "name": "hpet_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579256039,
      "name": "hpet_readl",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:62",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_disable",
        "arch/x86/kernel/hpet.c:hpet_disable",
        "arch/x86/kernel/hpet.c:hpet_msi_next_event",
        "arch/x86/kernel/hpet.c:hpet_msi_next_event",
        "arch/x86/kernel/hpet.c:hpet_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_set_oneshot",
        "arch/x86/kernel/hpet.c:hpet_msi_shutdown",
        "arch/x86/kernel/hpet.c:hpet_msi_read",
        "arch/x86/kernel/hpet.c:hpet_msi_read",
        "arch/x86/kernel/hpet.c:hpet_msi_mask",
        "arch/x86/kernel/hpet.c:hpet_legacy_next_event",
        "arch/x86/kernel/hpet.c:hpet_legacy_next_event",
        "arch/x86/kernel/hpet.c:hpet_legacy_resume",
        "arch/x86/kernel/hpet.c:hpet_legacy_set_oneshot",
        "arch/x86/kernel/hpet.c:hpet_legacy_shutdown",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:tsc_read_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579258096,
      "name": "hpet_readl",
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
unsigned int hpet_readl(unsigned int a)
```

```json
{
  "name": "hpet_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579272807,
      "name": "hpet_readl",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:62",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_disable",
        "arch/x86/kernel/hpet.c:hpet_disable",
        "arch/x86/kernel/hpet.c:hpet_msi_next_event",
        "arch/x86/kernel/hpet.c:hpet_msi_next_event",
        "arch/x86/kernel/hpet.c:hpet_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_set_oneshot",
        "arch/x86/kernel/hpet.c:hpet_msi_shutdown",
        "arch/x86/kernel/hpet.c:hpet_msi_read",
        "arch/x86/kernel/hpet.c:hpet_msi_read",
        "arch/x86/kernel/hpet.c:hpet_msi_mask",
        "arch/x86/kernel/hpet.c:hpet_legacy_next_event",
        "arch/x86/kernel/hpet.c:hpet_legacy_next_event",
        "arch/x86/kernel/hpet.c:hpet_legacy_resume",
        "arch/x86/kernel/hpet.c:hpet_legacy_set_oneshot",
        "arch/x86/kernel/hpet.c:hpet_legacy_shutdown",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:tsc_read_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274880,
      "name": "hpet_readl",
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
unsigned int hpet_readl(unsigned int a)
```

```json
{
  "name": "hpet_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579283905,
      "name": "hpet_readl",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:63",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_disable",
        "arch/x86/kernel/hpet.c:hpet_disable",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_msi_next_event",
        "arch/x86/kernel/hpet.c:hpet_msi_next_event",
        "arch/x86/kernel/hpet.c:hpet_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_set_oneshot",
        "arch/x86/kernel/hpet.c:hpet_msi_shutdown",
        "arch/x86/kernel/hpet.c:hpet_msi_read",
        "arch/x86/kernel/hpet.c:hpet_msi_read",
        "arch/x86/kernel/hpet.c:hpet_msi_mask",
        "arch/x86/kernel/hpet.c:hpet_legacy_next_event",
        "arch/x86/kernel/hpet.c:hpet_legacy_next_event",
        "arch/x86/kernel/hpet.c:hpet_legacy_resume",
        "arch/x86/kernel/hpet.c:hpet_legacy_set_oneshot",
        "arch/x86/kernel/hpet.c:hpet_legacy_shutdown",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:tsc_read_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579285792,
      "name": "hpet_readl",
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
unsigned int hpet_readl(unsigned int a)
```

```json
{
  "name": "hpet_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579307857,
      "name": "hpet_readl",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:59",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_disable",
        "arch/x86/kernel/hpet.c:hpet_disable",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_msi_next_event",
        "arch/x86/kernel/hpet.c:hpet_msi_next_event",
        "arch/x86/kernel/hpet.c:hpet_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_set_oneshot",
        "arch/x86/kernel/hpet.c:hpet_msi_shutdown",
        "arch/x86/kernel/hpet.c:hpet_msi_read",
        "arch/x86/kernel/hpet.c:hpet_msi_read",
        "arch/x86/kernel/hpet.c:hpet_msi_mask",
        "arch/x86/kernel/hpet.c:hpet_legacy_next_event",
        "arch/x86/kernel/hpet.c:hpet_legacy_next_event",
        "arch/x86/kernel/hpet.c:hpet_legacy_resume",
        "arch/x86/kernel/hpet.c:hpet_legacy_set_oneshot",
        "arch/x86/kernel/hpet.c:hpet_legacy_shutdown",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:tsc_read_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579309744,
      "name": "hpet_readl",
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
unsigned int hpet_readl(unsigned int a)
```

```json
{
  "name": "hpet_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579324116,
      "name": "hpet_readl",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:75",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_mask",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:tsc_read_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579325744,
      "name": "hpet_readl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
unsigned int hpet_readl(unsigned int a)
```

```json
{
  "name": "hpet_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579328164,
      "name": "hpet_readl",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:75",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_mask",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:tsc_read_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329792,
      "name": "hpet_readl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
unsigned int hpet_readl(unsigned int a)
```

```json
{
  "name": "hpet_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579356656,
      "name": "hpet_readl",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:75",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_timer_reinit",
        "arch/x86/kernel/hpet.c:hpet_rtc_timer_reinit",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_mask",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:tsc_read_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359168,
      "name": "hpet_readl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
unsigned int hpet_readl(unsigned int a)
```

```json
{
  "name": "hpet_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579356363,
      "name": "hpet_readl",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:76",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_timer_reinit",
        "arch/x86/kernel/hpet.c:hpet_rtc_timer_reinit",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_mask",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:tsc_read_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359024,
      "name": "hpet_readl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
unsigned int hpet_readl(unsigned int a)
```

```json
{
  "name": "hpet_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579360745,
      "name": "hpet_readl",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:76",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_mask",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:tsc_read_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579363424,
      "name": "hpet_readl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
unsigned int hpet_readl(unsigned int a)
```

```json
{
  "name": "hpet_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579420505,
      "name": "hpet_readl",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:77",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_mask",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:tsc_read_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579423968,
      "name": "hpet_readl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
unsigned int hpet_readl(unsigned int a)
```

```json
{
  "name": "hpet_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579488577,
      "name": "hpet_readl",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:77",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:read_hpet",
        "arch/x86/kernel/hpet.c:read_hpet",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_mask",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:tsc_read_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579492416,
      "name": "hpet_readl",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int hpet_readl(unsigned int a)
```

```json
{
  "name": "hpet_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579582945,
      "name": "hpet_readl",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:77",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:read_hpet",
        "arch/x86/kernel/hpet.c:read_hpet",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_mask",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:tsc_read_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587232,
      "name": "hpet_readl",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int hpet_readl(unsigned int a)
```

```json
{
  "name": "hpet_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579595489,
      "name": "hpet_readl",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:77",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:read_hpet",
        "arch/x86/kernel/hpet.c:read_hpet",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_mask",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:tsc_read_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599728,
      "name": "hpet_readl",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int hpet_readl(unsigned int a)
```

```json
{
  "name": "hpet_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579625249,
      "name": "hpet_readl",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:77",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:read_hpet",
        "arch/x86/kernel/hpet.c:read_hpet",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_mask",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:tsc_read_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629488,
      "name": "hpet_readl",
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
unsigned int hpet_readl(unsigned int a)
```

```json
{
  "name": "hpet_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579324068,
      "name": "hpet_readl",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:75",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_mask",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:tsc_read_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579325696,
      "name": "hpet_readl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
unsigned int hpet_readl(unsigned int a)
```

```json
{
  "name": "hpet_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579258580,
      "name": "hpet_readl",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:75",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_mask",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:tsc_read_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579260144,
      "name": "hpet_readl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
unsigned int hpet_readl(unsigned int a)
```

```json
{
  "name": "hpet_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579323988,
      "name": "hpet_readl",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:75",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_mask",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:tsc_read_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579325616,
      "name": "hpet_readl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
unsigned int hpet_readl(unsigned int a)
```

```json
{
  "name": "hpet_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579332276,
      "name": "hpet_readl",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:75",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_mask",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:hpet_restart_counter",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config",
        "arch/x86/kernel/hpet.c:_hpet_print_config"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:tsc_read_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579333904,
      "name": "hpet_readl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
unsigned int hpet_readl(unsigned int a)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
unsigned int hpet_readl(unsigned int a)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
unsigned int hpet_readl(unsigned int a)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
unsigned int hpet_readl(unsigned int a)
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
