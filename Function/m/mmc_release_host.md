# Function: <code>mmc_release_host</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585914112,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:986",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_interrupt_hpi",
        "drivers/mmc/core/core.c:mmc_read_bkops_status",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_resume",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_power_restore",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio_irq.c:sdio_run_irqs",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585914112,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586314512,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:987",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_read_bkops_status",
        "drivers/mmc/core/core.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_power_restore",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_run_irqs",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586314512,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586521504,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1059",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_read_bkops_status",
        "drivers/mmc/core/core.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_power_restore",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_io.c:sdio_release_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_run_irqs",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586521504,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586647040,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:891",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_start_bkops",
        "drivers/mmc/core/mmc_ops.c:mmc_start_bkops",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_power_restore",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio_io.c:sdio_release_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_run_irqs",
        "drivers/mmc/core/sdio_irq.c:sdio_run_irqs",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586647040,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587129664,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1074",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_power_restore",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio_io.c:sdio_release_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_run_irqs",
        "drivers/mmc/core/sdio_irq.c:sdio_run_irqs",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587129664,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587429520,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:873",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_power_restore",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio_io.c:sdio_release_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_run_irqs",
        "drivers/mmc/core/sdio_irq.c:sdio_run_irqs",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587429520,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587610368,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:873",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_power_restore",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio_io.c:sdio_release_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_run_irqs",
        "drivers/mmc/core/sdio_irq.c:sdio_run_irqs",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587610368,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:844",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio_io.c:sdio_release_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587904746,
      "name": "mmc_release_host.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071587888576,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588094768,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:844",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio_io.c:sdio_release_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588094768,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588956784,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:827",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_io.c:sdio_release_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588956784,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588969232,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:827",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_io.c:sdio_release_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588969232,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588857872,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:828",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_io.c:sdio_release_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588857872,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589559920,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:828",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_io.c:sdio_release_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589559920,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591053888,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:828",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_io.c:sdio_release_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591053888,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592766592,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:827",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_io.c:sdio_release_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592766592,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593202800,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:827",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_io.c:sdio_release_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593202800,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593957376,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:832",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_io.c:sdio_release_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593957376,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501352424,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:844",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio_io.c:sdio_release_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set",
        "drivers/mmc/core/block.c:mmc_blk_remove",
        "drivers/mmc/core/queue.c:mmc_queue_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501352424,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233836128,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:844",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio_io.c:sdio_release_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set",
        "drivers/mmc/core/block.c:mmc_blk_remove",
        "drivers/mmc/core/queue.c:mmc_queue_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233836128,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294893648,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:844",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_io.c:sdio_release_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294893648,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277960368,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:844",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_io.c:sdio_release_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set",
        "drivers/mmc/core/block.c:mmc_blk_remove",
        "drivers/mmc/core/queue.c:mmc_queue_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277960368,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587716336,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:844",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio_io.c:sdio_release_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587716336,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588049296,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:844",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio_io.c:sdio_release_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588049296,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void mmc_release_host(struct mmc_host * host)
```

```json
{
  "name": "mmc_release_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588166720,
      "name": "mmc_release_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:844",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio_io.c:sdio_release_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588166720,
      "name": "mmc_release_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void mmc_release_host(struct mmc_host * host)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
