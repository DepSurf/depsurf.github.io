# Function: <code>__mmc_claim_host</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host * host, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585913600,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:940",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/core.c:mmc_interrupt_hpi",
        "drivers/mmc/core/core.c:mmc_read_bkops_status",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_resume",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
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
      "addr": 18446744071585913600,
      "name": "__mmc_claim_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
int __mmc_claim_host(struct mmc_host * host, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586314016,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:941",
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
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/core.c:mmc_read_bkops_status",
        "drivers/mmc/core/core.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
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
      "addr": 18446744071586314016,
      "name": "__mmc_claim_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
int __mmc_claim_host(struct mmc_host * host, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586521008,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1013",
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
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/core.c:mmc_read_bkops_status",
        "drivers/mmc/core/core.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
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
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_io.c:sdio_claim_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_run_irqs",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586521008,
      "name": "__mmc_claim_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int __mmc_claim_host(struct mmc_host * host, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586646496,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:845",
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
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_start_bkops",
        "drivers/mmc/core/mmc_ops.c:mmc_start_bkops",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_power_restore",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio_io.c:sdio_claim_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_run_irqs",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586646496,
      "name": "__mmc_claim_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
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
int __mmc_claim_host(struct mmc_host * host, struct mmc_ctx * ctx, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587129008,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1026",
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
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_power_restore",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio_io.c:sdio_claim_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_run_irqs",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587129008,
      "name": "__mmc_claim_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 589
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
int __mmc_claim_host(struct mmc_host * host, struct mmc_ctx * ctx, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587428864,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:825",
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
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_power_restore",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio_io.c:sdio_claim_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_run_irqs",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587428864,
      "name": "__mmc_claim_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 589
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
int __mmc_claim_host(struct mmc_host * host, struct mmc_ctx * ctx, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587609712,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:825",
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
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_power_restore",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio_io.c:sdio_claim_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_run_irqs",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587609712,
      "name": "__mmc_claim_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
int __mmc_claim_host(struct mmc_host * host, struct mmc_ctx * ctx, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587887904,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:796",
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
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio_io.c:sdio_claim_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587887904,
      "name": "__mmc_claim_host",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host * host, struct mmc_ctx * ctx, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588094096,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:796",
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
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio_io.c:sdio_claim_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588094096,
      "name": "__mmc_claim_host",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host * host, struct mmc_ctx * ctx, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588956128,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:779",
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
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_io.c:sdio_claim_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588956128,
      "name": "__mmc_claim_host",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host * host, struct mmc_ctx * ctx, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588968544,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:779",
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
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_io.c:sdio_claim_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588968544,
      "name": "__mmc_claim_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
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
int __mmc_claim_host(struct mmc_host * host, struct mmc_ctx * ctx, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588857200,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:780",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_io.c:sdio_claim_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588857200,
      "name": "__mmc_claim_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
int __mmc_claim_host(struct mmc_host * host, struct mmc_ctx * ctx, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589559280,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:780",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_io.c:sdio_claim_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589559280,
      "name": "__mmc_claim_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
int __mmc_claim_host(struct mmc_host * host, struct mmc_ctx * ctx, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591053248,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:780",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_io.c:sdio_claim_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591053248,
      "name": "__mmc_claim_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
int __mmc_claim_host(struct mmc_host * host, struct mmc_ctx * ctx, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592765920,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:779",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_io.c:sdio_claim_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592765920,
      "name": "__mmc_claim_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
int __mmc_claim_host(struct mmc_host * host, struct mmc_ctx * ctx, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593202096,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:779",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_io.c:sdio_claim_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593202096,
      "name": "__mmc_claim_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int __mmc_claim_host(struct mmc_host * host, struct mmc_ctx * ctx, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593956672,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:784",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_io.c:sdio_claim_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593956672,
      "name": "__mmc_claim_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int __mmc_claim_host(struct mmc_host * host, struct mmc_ctx * ctx, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501351632,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:796",
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
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio_io.c:sdio_claim_host",
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
      "addr": 18446603336501351632,
      "name": "__mmc_claim_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
int __mmc_claim_host(struct mmc_host * host, struct mmc_ctx * ctx, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233835500,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:796",
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
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio_io.c:sdio_claim_host",
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
      "addr": 3233835500,
      "name": "__mmc_claim_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
int __mmc_claim_host(struct mmc_host * host, struct mmc_ctx * ctx, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294892784,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:796",
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
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_io.c:sdio_claim_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294892784,
      "name": "__mmc_claim_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 768
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
int __mmc_claim_host(struct mmc_host * host, struct mmc_ctx * ctx, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277959834,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:796",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_io.c:sdio_claim_host",
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
      "addr": 18446743936277959834,
      "name": "__mmc_claim_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int __mmc_claim_host(struct mmc_host * host, struct mmc_ctx * ctx, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587715664,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:796",
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
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio_io.c:sdio_claim_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587715664,
      "name": "__mmc_claim_host",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host * host, struct mmc_ctx * ctx, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588048624,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:796",
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
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio_io.c:sdio_claim_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588048624,
      "name": "__mmc_claim_host",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host * host, struct mmc_ctx * ctx, atomic_t * abort)
```

```json
{
  "name": "__mmc_claim_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588166048,
      "name": "__mmc_claim_host",
      "external": true,
      "loc": "drivers/mmc/core/core.c:796",
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
        "drivers/mmc/core/core.c:mmc_get_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio_io.c:sdio_claim_host",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_work",
        "drivers/mmc/core/debugfs.c:mmc_clock_opt_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588166048,
      "name": "__mmc_claim_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mmc_ctx * ctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>host, abort</code> ➡️ <code>host, ctx, abort</code>
</li>
</ul>
</details>
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
int __mmc_claim_host(struct mmc_host * host, struct mmc_ctx * ctx, atomic_t * abort)
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
