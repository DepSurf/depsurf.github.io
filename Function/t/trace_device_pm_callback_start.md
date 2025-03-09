# Function: <code>trace_device_pm_callback_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_device_pm_callback_start(struct device * dev, const char * pm_ops, int event)
```

```json
{
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584450528,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:145",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_prepare"
      ],
      "caller_func": [
        "drivers/base/power/main.c:legacy_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584450528,
      "name": "trace_device_pm_callback_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void trace_device_pm_callback_start(struct device * dev, const char * pm_ops, int event)
```

```json
{
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584797816,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:145",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/base/power/main.c:legacy_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584786752,
      "name": "trace_device_pm_callback_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void trace_device_pm_callback_start(struct device * dev, const char * pm_ops, int event)
```

```json
{
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584989752,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:150",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/base/power/main.c:legacy_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584978624,
      "name": "trace_device_pm_callback_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585074609,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:150",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:legacy_suspend",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_run_callback"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585497857,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:151",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_run_callback"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585742099,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:151",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_run_callback"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585874835,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:176",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586112094,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:176",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
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
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586259518,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:176",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587027950,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:176",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587112264,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:176",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586998568,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:176",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587564772,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:176",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588898644,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:176",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590409307,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:198",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590728875,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:198",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
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
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591090795,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:198",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499080264,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:176",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231633504,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:176",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292260816,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:176",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
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
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586022846,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:176",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
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
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585868830,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:176",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
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
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586209534,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:176",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
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
  "name": "trace_device_pm_callback_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586318537,
      "name": "trace_device_pm_callback_start",
      "external": false,
      "loc": "include/trace/events/power.h:176",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
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
void trace_device_pm_callback_start(struct device * dev, const char * pm_ops, int event)
```
</details>
</li>
</ul>
