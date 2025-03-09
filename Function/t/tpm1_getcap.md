# Function: <code>tpm1_getcap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
ssize_t tpm1_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```

```json
{
  "name": "tpm1_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585623552,
      "name": "tpm1_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:473",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:temp_deactivated_show",
        "drivers/char/tpm/tpm-sysfs.c:owned_show",
        "drivers/char/tpm/tpm-sysfs.c:active_show",
        "drivers/char/tpm/tpm-sysfs.c:enabled_show",
        "drivers/char/tpm/tpm-sysfs.c:pcrs_show",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585623552,
      "name": "tpm1_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
ssize_t tpm1_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```

```json
{
  "name": "tpm1_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585843616,
      "name": "tpm1_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:467",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585843616,
      "name": "tpm1_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 586
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
ssize_t tpm1_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```

```json
{
  "name": "tpm1_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585986176,
      "name": "tpm1_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:467",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585986176,
      "name": "tpm1_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 586
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
ssize_t tpm1_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```

```json
{
  "name": "tpm1_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586727424,
      "name": "tpm1_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:482",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586727424,
      "name": "tpm1_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 567
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
ssize_t tpm1_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```

```json
{
  "name": "tpm1_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586822720,
      "name": "tpm1_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:482",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586822720,
      "name": "tpm1_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 567
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
ssize_t tpm1_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```

```json
{
  "name": "tpm1_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586702704,
      "name": "tpm1_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:482",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586702704,
      "name": "tpm1_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 567
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
ssize_t tpm1_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```

```json
{
  "name": "tpm1_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587252080,
      "name": "tpm1_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:482",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587252080,
      "name": "tpm1_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 567
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
ssize_t tpm1_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```

```json
{
  "name": "tpm1_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588561040,
      "name": "tpm1_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:482",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:temp_deactivated_show",
        "drivers/char/tpm/tpm-sysfs.c:owned_show",
        "drivers/char/tpm/tpm-sysfs.c:active_show",
        "drivers/char/tpm/tpm-sysfs.c:enabled_show",
        "drivers/char/tpm/tpm-sysfs.c:pcrs_show",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588561040,
      "name": "tpm1_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 598
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
ssize_t tpm1_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```

```json
{
  "name": "tpm1_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590014288,
      "name": "tpm1_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:482",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:temp_deactivated_show",
        "drivers/char/tpm/tpm-sysfs.c:owned_show",
        "drivers/char/tpm/tpm-sysfs.c:active_show",
        "drivers/char/tpm/tpm-sysfs.c:enabled_show",
        "drivers/char/tpm/tpm-sysfs.c:pcrs_show",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590014288,
      "name": "tpm1_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 598
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
ssize_t tpm1_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```

```json
{
  "name": "tpm1_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590323600,
      "name": "tpm1_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:482",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:temp_deactivated_show",
        "drivers/char/tpm/tpm-sysfs.c:owned_show",
        "drivers/char/tpm/tpm-sysfs.c:active_show",
        "drivers/char/tpm/tpm-sysfs.c:enabled_show",
        "drivers/char/tpm/tpm-sysfs.c:pcrs_show",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590323600,
      "name": "tpm1_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 598
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
ssize_t tpm1_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```

```json
{
  "name": "tpm1_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590664992,
      "name": "tpm1_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:482",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:temp_deactivated_show",
        "drivers/char/tpm/tpm-sysfs.c:owned_show",
        "drivers/char/tpm/tpm-sysfs.c:active_show",
        "drivers/char/tpm/tpm-sysfs.c:enabled_show",
        "drivers/char/tpm/tpm-sysfs.c:pcrs_show",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590664992,
      "name": "tpm1_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 598
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
ssize_t tpm1_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```

```json
{
  "name": "tpm1_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498781144,
      "name": "tpm1_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:467",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498781144,
      "name": "tpm1_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
ssize_t tpm1_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```

```json
{
  "name": "tpm1_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231395752,
      "name": "tpm1_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:467",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231395752,
      "name": "tpm1_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
ssize_t tpm1_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```

```json
{
  "name": "tpm1_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291972736,
      "name": "tpm1_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:467",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291972736,
      "name": "tpm1_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 848
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
ssize_t tpm1_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```

```json
{
  "name": "tpm1_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276275274,
      "name": "tpm1_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:467",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276275274,
      "name": "tpm1_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1330
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
ssize_t tpm1_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```

```json
{
  "name": "tpm1_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585747152,
      "name": "tpm1_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:467",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585747152,
      "name": "tpm1_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 586
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
ssize_t tpm1_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```

```json
{
  "name": "tpm1_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585606336,
      "name": "tpm1_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:467",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585606336,
      "name": "tpm1_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 586
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
ssize_t tpm1_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```

```json
{
  "name": "tpm1_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585936192,
      "name": "tpm1_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:467",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585936192,
      "name": "tpm1_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 586
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
ssize_t tpm1_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```

```json
{
  "name": "tpm1_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586044176,
      "name": "tpm1_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:467",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586044176,
      "name": "tpm1_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
ssize_t tpm1_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```
</details>
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
