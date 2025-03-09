# Function: <code>trace_device_pm_callback_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_device_pm_callback_end(struct device * dev, int error)
```

```json
{
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584450640,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:173",
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
      "addr": 18446744071584450640,
      "name": "trace_device_pm_callback_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void trace_device_pm_callback_end(struct device * dev, int error)
```

```json
{
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584797834,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:173",
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
      "addr": 18446744071584786864,
      "name": "trace_device_pm_callback_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void trace_device_pm_callback_end(struct device * dev, int error)
```

```json
{
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584989770,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:178",
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
      "addr": 18446744071584978736,
      "name": "trace_device_pm_callback_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585074627,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:178",
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
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585498026,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:179",
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
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585742301,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:179",
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
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585875037,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:204",
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
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586112293,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:204",
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
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586259715,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:204",
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
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587027969,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:204",
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
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587112283,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:204",
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
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586998587,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:204",
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
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587564788,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:204",
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
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588898660,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:204",
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
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590409326,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:226",
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
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590728894,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:226",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591090814,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:226",
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499080496,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:204",
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
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231633764,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:204",
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
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292261080,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:204",
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
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586023043,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:204",
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
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585869021,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:204",
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
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586209731,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:204",
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
  "name": "trace_device_pm_callback_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586318725,
      "name": "trace_device_pm_callback_end",
      "external": false,
      "loc": "include/trace/events/power.h:204",
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
void trace_device_pm_callback_end(struct device * dev, int error)
```
</details>
</li>
</ul>
