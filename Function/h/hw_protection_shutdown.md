# Function: <code>hw_protection_shutdown</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void hw_protection_shutdown(const char * reason, int ms_until_forced)
```

```json
{
  "name": "hw_protection_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592105773,
      "name": "hw_protection_shutdown",
      "external": true,
      "loc": "kernel/reboot.c:581",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/thermal/thermal_core.c:thermal_zone_device_critical"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592105773,
      "name": "hw_protection_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void hw_protection_shutdown(const char * reason, int ms_until_forced)
```

```json
{
  "name": "hw_protection_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593873360,
      "name": "hw_protection_shutdown",
      "external": true,
      "loc": "kernel/reboot.c:953",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/thermal/thermal_core.c:thermal_zone_device_critical"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593873360,
      "name": "hw_protection_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void hw_protection_shutdown(const char * reason, int ms_until_forced)
```

```json
{
  "name": "hw_protection_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580056128,
      "name": "hw_protection_shutdown",
      "external": true,
      "loc": "kernel/reboot.c:970",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/thermal/thermal_core.c:thermal_zone_device_critical"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580056128,
      "name": "hw_protection_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void hw_protection_shutdown(const char * reason, int ms_until_forced)
```

```json
{
  "name": "hw_protection_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580110560,
      "name": "hw_protection_shutdown",
      "external": true,
      "loc": "kernel/reboot.c:970",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/thermal/thermal_core.c:thermal_zone_device_critical"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110560,
      "name": "hw_protection_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hw_protection_shutdown",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590202352,
      "name": "hw_protection_shutdown",
      "external": false,
      "loc": "include/linux/reboot.h:187",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_notifier_call_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590257822,
      "name": "hw_protection_shutdown",
      "external": false,
      "loc": "include/linux/reboot.h:187",
      "file": "drivers/regulator/irq_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593513117,
      "name": "hw_protection_shutdown",
      "external": false,
      "loc": "include/linux/reboot.h:187",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_critical"
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void hw_protection_shutdown(const char * reason, int ms_until_forced)
```
</details>
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
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void hw_protection_shutdown(const char * reason, int ms_until_forced)
```
</details>
</li>
</ul>
