# Function: <code>round_jiffies_relative</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579809520,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:283",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn",
        "arch/x86/kernel/check.c:check_corruption",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:setup_vmstat",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "net/core/dst.c:dst_gc_task",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579809520,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579837472,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:381",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn",
        "arch/x86/kernel/check.c:check_corruption",
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "net/core/dst.c:dst_gc_task",
        "net/core/dst.c:dst_gc_task",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579837472,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579866528,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:381",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn",
        "arch/x86/kernel/check.c:check_corruption",
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "net/core/dst.c:dst_gc_task",
        "net/core/dst.c:dst_gc_task",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866528,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579876032,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:384",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/edac/edac_device.c:edac_device_reset_delay_period",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876032,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579919280,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:384",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/edac/edac_device.c:edac_device_reset_delay_period",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579919280,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579965904,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:401",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/edac/edac_device.c:edac_device_reset_delay_period",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965904,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012560,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:400",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/edac/edac_device.c:edac_device_reset_delay_period",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012560,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580056720,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:400",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/edac/edac_device.c:edac_device_reset_delay_period",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580056720,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580105776,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:404",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/edac/edac_device.c:edac_device_reset_delay_period",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580105776,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580175744,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:404",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "mm/vmstat.c:start_shepherd_timer",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/edac/edac_device.c:edac_device_add_device",
        "drivers/edac/edac_device.c:edac_device_reset_delay_period",
        "drivers/edac/edac_device.c:edac_device_workq_function",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580175744,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580159616,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:405",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "mm/vmstat.c:start_shepherd_timer",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/edac/edac_device.c:edac_device_add_device",
        "drivers/edac/edac_device.c:edac_device_reset_delay_period",
        "drivers/edac/edac_device.c:edac_device_workq_function",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580159616,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580162096,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:406",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/edac/edac_device.c:edac_device_add_device",
        "drivers/edac/edac_device.c:edac_device_reset_delay_period",
        "drivers/edac/edac_device.c:edac_device_workq_function",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580162096,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580306672,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:406",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/edac/edac_device.c:edac_device_add_device",
        "drivers/edac/edac_device.c:edac_device_reset_delay_period",
        "drivers/edac/edac_device.c:edac_device_workq_function",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580306672,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580522352,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:429",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/edac/edac_device.c:edac_device_add_device",
        "drivers/edac/edac_device.c:edac_device_reset_delay_period",
        "drivers/edac/edac_device.c:edac_device_workq_function",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580522352,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580777888,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:429",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/edac/edac_device.c:edac_device_add_device",
        "drivers/edac/edac_device.c:edac_device_reset_delay_period",
        "drivers/edac/edac_device.c:edac_device_workq_function",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580777888,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580860944,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:429",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/edac/edac_device.c:edac_device_add_device",
        "drivers/edac/edac_device.c:edac_device_reset_delay_period",
        "drivers/edac/edac_device.c:edac_device_workq_function",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860944,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580951104,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:429",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/edac/edac_device.c:edac_device_add_device",
        "drivers/edac/edac_device.c:edac_device_reset_delay_period",
        "drivers/edac/edac_device.c:edac_device_workq_function",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580951104,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491325544,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:404",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/edac/edac_device.c:edac_device_reset_delay_period",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491325544,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225313204,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:404",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/edac/edac_device.c:edac_device_reset_delay_period",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225313204,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284244048,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:404",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/edac/edac_device.c:edac_device_reset_delay_period",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284244048,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271822364,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:404",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/edac/edac_device.c:edac_device_reset_delay_period",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271822364,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580074976,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:404",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/edac/edac_device.c:edac_device_reset_delay_period",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580074976,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580019792,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:404",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/edac/edac_device.c:edac_device_reset_delay_period",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019792,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580066048,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:404",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/edac/edac_device.c:edac_device_reset_delay_period",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580066048,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
long unsigned int round_jiffies_relative(long unsigned int j)
```

```json
{
  "name": "round_jiffies_relative",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580116816,
      "name": "round_jiffies_relative",
      "external": true,
      "loc": "kernel/time/timer.c:404",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/edac/edac_device.c:edac_device_reset_delay_period",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580116816,
      "name": "round_jiffies_relative",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
