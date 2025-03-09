# Function: <code>__irq_set_affinity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __irq_set_affinity(unsigned int irq, const struct cpumask * mask, bool force)
```

```json
{
  "name": "__irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579746704,
      "name": "__irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:236",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_resume",
        "arch/x86/kernel/hpet.c:hpet_work",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579746704,
      "name": "__irq_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int __irq_set_affinity(unsigned int irq, const struct cpumask * mask, bool force)
```

```json
{
  "name": "__irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579768992,
      "name": "__irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:249",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_work",
        "arch/x86/kernel/hpet.c:hpet_resume",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579768992,
      "name": "__irq_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int __irq_set_affinity(unsigned int irq, const struct cpumask * mask, bool force)
```

```json
{
  "name": "__irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579795952,
      "name": "__irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:249",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_work",
        "arch/x86/kernel/hpet.c:hpet_msi_resume",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579795952,
      "name": "__irq_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int __irq_set_affinity(unsigned int irq, const struct cpumask * mask, bool force)
```

```json
{
  "name": "__irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579792912,
      "name": "__irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:223",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_work",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579792912,
      "name": "__irq_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int __irq_set_affinity(unsigned int irq, const struct cpumask * mask, bool force)
```

```json
{
  "name": "__irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579826576,
      "name": "__irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:240",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_work",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579826576,
      "name": "__irq_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int __irq_set_affinity(unsigned int irq, const struct cpumask * mask, bool force)
```

```json
{
  "name": "__irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579860416,
      "name": "__irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:273",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_work",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579860416,
      "name": "__irq_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int __irq_set_affinity(unsigned int irq, const struct cpumask * mask, bool force)
```

```json
{
  "name": "__irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579907344,
      "name": "__irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:273",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_work",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579907344,
      "name": "__irq_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int __irq_set_affinity(unsigned int irq, const struct cpumask * mask, bool force)
```

```json
{
  "name": "__irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579942688,
      "name": "__irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:300",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942688,
      "name": "__irq_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int __irq_set_affinity(unsigned int irq, const struct cpumask * mask, bool force)
```

```json
{
  "name": "__irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579992912,
      "name": "__irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:304",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992912,
      "name": "__irq_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int __irq_set_affinity(unsigned int irq, const struct cpumask * mask, bool force)
```

```json
{
  "name": "__irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580040313,
      "name": "__irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:380",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_hint"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580040416,
      "name": "__irq_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int __irq_set_affinity(unsigned int irq, const struct cpumask * mask, bool force)
```

```json
{
  "name": "__irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580023497,
      "name": "__irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:450",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_hint"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580023616,
      "name": "__irq_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int __irq_set_affinity(unsigned int irq, const struct cpumask * mask, bool force)
```

```json
{
  "name": "__irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580024185,
      "name": "__irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:450",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_hint"
      ],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580024304,
      "name": "__irq_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__irq_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580156441,
      "name": "__irq_set_affinity",
      "external": false,
      "loc": "kernel/irq/manage.c:443",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/manage.c:irq_force_affinity",
        "kernel/irq/manage.c:irq_set_affinity"
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
  "name": "__irq_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580302214,
      "name": "__irq_set_affinity",
      "external": false,
      "loc": "kernel/irq/manage.c:458",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__irq_apply_affinity_hint",
        "kernel/irq/manage.c:irq_force_affinity",
        "kernel/irq/manage.c:irq_set_affinity"
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
  "name": "__irq_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580514406,
      "name": "__irq_set_affinity",
      "external": false,
      "loc": "kernel/irq/manage.c:450",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__irq_apply_affinity_hint",
        "kernel/irq/manage.c:irq_force_affinity",
        "kernel/irq/manage.c:irq_set_affinity"
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
  "name": "__irq_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580587302,
      "name": "__irq_set_affinity",
      "external": false,
      "loc": "kernel/irq/manage.c:453",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__irq_apply_affinity_hint",
        "kernel/irq/manage.c:irq_force_affinity",
        "kernel/irq/manage.c:irq_set_affinity"
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
  "name": "__irq_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580651654,
      "name": "__irq_set_affinity",
      "external": false,
      "loc": "kernel/irq/manage.c:455",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__irq_apply_affinity_hint",
        "kernel/irq/manage.c:irq_force_affinity",
        "kernel/irq/manage.c:irq_set_affinity"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __irq_set_affinity(unsigned int irq, const struct cpumask * mask, bool force)
```

```json
{
  "name": "__irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491182920,
      "name": "__irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:304",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_flush_hwstate",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_hwirq_alloc",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init",
        "drivers/soc/fsl/qbman/bman_portal.c:bman_online_cpu",
        "drivers/soc/fsl/qbman/bman_portal.c:bman_offline_cpu",
        "drivers/soc/fsl/qbman/qman_portal.c:qman_online_cpu",
        "drivers/soc/fsl/qbman/qman_portal.c:qman_offline_cpu",
        "drivers/soc/fsl/qbman/bman.c:bman_create_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_create_portal",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/perf/arm_pmu.c:armpmu_request_irq",
        "drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_offline_cpu",
        "drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_online_cpu",
        "drivers/perf/qcom_l2_pmu.c:l2cache_pmu_offline_cpu",
        "drivers/perf/qcom_l2_pmu.c:l2cache_pmu_online_cpu",
        "drivers/perf/xgene_pmu.c:xgene_pmu_offline_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491182920,
      "name": "__irq_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int __irq_set_affinity(unsigned int irq, const struct cpumask * mask, bool force)
```

```json
{
  "name": "__irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225206212,
      "name": "__irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:304",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "drivers/clocksource/timer-tegra.c:tegra_timer_setup",
        "drivers/clocksource/exynos_mct.c:exynos4_mct_starting_cpu",
        "drivers/perf/arm_pmu.c:armpmu_request_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225206212,
      "name": "__irq_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int __irq_set_affinity(unsigned int irq, const struct cpumask * mask, bool force)
```

```json
{
  "name": "__irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284084912,
      "name": "__irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:304",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/sysdev/xics/xics-common.c:xics_migrate_irqs_away",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284084912,
      "name": "__irq_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int __irq_set_affinity(unsigned int irq, const struct cpumask * mask, bool force)
```

```json
{
  "name": "__irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271730952,
      "name": "__irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:304",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_hint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271730952,
      "name": "__irq_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int __irq_set_affinity(unsigned int irq, const struct cpumask * mask, bool force)
```

```json
{
  "name": "__irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579961648,
      "name": "__irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:304",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579961648,
      "name": "__irq_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int __irq_set_affinity(unsigned int irq, const struct cpumask * mask, bool force)
```

```json
{
  "name": "__irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579899488,
      "name": "__irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:304",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899488,
      "name": "__irq_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int __irq_set_affinity(unsigned int irq, const struct cpumask * mask, bool force)
```

```json
{
  "name": "__irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579953184,
      "name": "__irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:304",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579953184,
      "name": "__irq_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int __irq_set_affinity(unsigned int irq, const struct cpumask * mask, bool force)
```

```json
{
  "name": "__irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579999568,
      "name": "__irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:304",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579999568,
      "name": "__irq_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int __irq_set_affinity(unsigned int irq, const struct cpumask * mask, bool force)
```
</details>
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
