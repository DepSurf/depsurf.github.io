# Function: <code>async_synchronize_full</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513248,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:237",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/module.c:SyS_delete_module",
        "kernel/module.c:do_init_module",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513248,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579527344,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:237",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/power/hibernate.c:software_resume",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/module.c:do_init_module",
        "kernel/module.c:SyS_delete_module",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579527344,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579550992,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:237",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/power/hibernate.c:software_resume",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/module.c:do_init_module",
        "kernel/module.c:SyS_delete_module",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550992,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579537632,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:237",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/power/hibernate.c:software_resume",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/module.c:do_init_module",
        "kernel/module.c:SyS_delete_module",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579537632,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579564384,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:241",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/power/hibernate.c:software_resume",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/module.c:do_init_module",
        "kernel/module.c:SyS_delete_module",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564384,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579592640,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:241",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/power/hibernate.c:software_resume",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579592640,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579630608,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:241",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/power/hibernate.c:software_resume",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module",
        "drivers/base/dd.c:driver_detach",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579630608,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579655488,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:242",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/power/hibernate.c:software_resume",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module",
        "drivers/base/dd.c:driver_detach",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579655488,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579692576,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:242",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/power/hibernate.c:software_resume",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module",
        "drivers/base/dd.c:driver_detach",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/ata/libata-core.c:ata_host_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579692576,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579732768,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:242",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/power/hibernate.c:software_resume",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/module.c:do_init_module",
        "drivers/base/dd.c:driver_detach",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579732768,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579712704,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:242",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/module.c:do_init_module",
        "drivers/base/dd.c:driver_detach",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579712704,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579720016,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:242",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/module.c:do_init_module",
        "drivers/base/dd.c:driver_detach",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579720016,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579798384,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:239",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/module.c:do_init_module",
        "drivers/base/dd.c:driver_detach",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579798384,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579907632,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:239",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/module/main.c:do_init_module",
        "drivers/base/dd.c:driver_detach",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579907632,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580060912,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:239",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/module/main.c:do_init_module",
        "drivers/base/dd.c:driver_detach",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580060912,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580115360,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:239",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/power/hibernate.c:find_resume_device",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/module/main.c:do_init_module",
        "drivers/base/dd.c:driver_detach",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580115360,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580160848,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:281",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/power/hibernate.c:find_resume_device",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/module/main.c:do_init_module",
        "drivers/base/dd.c:driver_detach",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580160848,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490870736,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:242",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__arm64_sys_delete_module",
        "drivers/base/dd.c:driver_detach",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/ata/libata-core.c:ata_host_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490870736,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224889588,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:242",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/power/hibernate.c:software_resume",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__se_sys_delete_module",
        "drivers/base/dd.c:driver_detach",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/ata/libata-core.c:ata_host_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224889588,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283702288,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:242",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__se_sys_delete_module",
        "drivers/base/dd.c:driver_detach",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/ata/libata-core.c:ata_host_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283702288,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271526236,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:242",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__se_sys_delete_module",
        "drivers/base/dd.c:driver_detach",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/ata/libata-core.c:ata_host_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271526236,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579668896,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:242",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/power/hibernate.c:software_resume",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module",
        "drivers/base/dd.c:driver_detach",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/ata/libata-core.c:ata_host_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579668896,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579597248,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:242",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/power/hibernate.c:software_resume",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module",
        "drivers/base/dd.c:driver_detach",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/ata/libata-core.c:ata_host_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579597248,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579666128,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:242",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/power/hibernate.c:software_resume",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module",
        "drivers/base/dd.c:driver_detach",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/ata/libata-core.c:ata_host_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579666128,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void async_synchronize_full()
```

```json
{
  "name": "async_synchronize_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579700240,
      "name": "async_synchronize_full",
      "external": true,
      "loc": "kernel/async.c:242",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "init/do_mounts.c:prepare_namespace",
        "kernel/power/hibernate.c:software_resume",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module",
        "drivers/base/dd.c:driver_detach",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/ata/libata-core.c:ata_host_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579700240,
      "name": "async_synchronize_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
