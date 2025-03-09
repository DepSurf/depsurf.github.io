# Function: <code>dev_pm_enable_wake_irq_complete</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void dev_pm_enable_wake_irq_complete(struct device * dev)
```

```json
{
  "name": "dev_pm_enable_wake_irq_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588883472,
      "name": "dev_pm_enable_wake_irq_complete",
      "external": true,
      "loc": "drivers/base/power/wakeirq.c:353",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/runtime.c:rpm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588883472,
      "name": "dev_pm_enable_wake_irq_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void dev_pm_enable_wake_irq_complete(struct device * dev)
```

```json
{
  "name": "dev_pm_enable_wake_irq_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590392208,
      "name": "dev_pm_enable_wake_irq_complete",
      "external": true,
      "loc": "drivers/base/power/wakeirq.c:353",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:rpm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590392208,
      "name": "dev_pm_enable_wake_irq_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void dev_pm_enable_wake_irq_complete(struct device * dev)
```

```json
{
  "name": "dev_pm_enable_wake_irq_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590711696,
      "name": "dev_pm_enable_wake_irq_complete",
      "external": true,
      "loc": "drivers/base/power/wakeirq.c:308",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:rpm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590711696,
      "name": "dev_pm_enable_wake_irq_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void dev_pm_enable_wake_irq_complete(struct device * dev)
```

```json
{
  "name": "dev_pm_enable_wake_irq_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591073664,
      "name": "dev_pm_enable_wake_irq_complete",
      "external": true,
      "loc": "drivers/base/power/wakeirq.c:308",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:rpm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591073664,
      "name": "dev_pm_enable_wake_irq_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void dev_pm_enable_wake_irq_complete(struct device * dev)
```
</details>
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
