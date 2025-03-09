# Function: <code>virq_to_hw</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
irq_hw_number_t virq_to_hw(unsigned int virq)
```

```json
{
  "name": "virq_to_hw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282273552,
      "name": "virq_to_hw",
      "external": true,
      "loc": "arch/powerpc/kernel/irq.c:687",
      "file": "arch/powerpc/kernel/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/sysdev/mpic.c:mpic_irq_set_priority",
        "arch/powerpc/sysdev/mpic.c:mpic_irq_set_priority",
        "arch/powerpc/sysdev/mpic.c:mpic_host_map",
        "arch/powerpc/sysdev/mpic.c:mpic_set_vector",
        "arch/powerpc/sysdev/mpic.c:mpic_mask_tm",
        "arch/powerpc/sysdev/mpic.c:mpic_unmask_tm",
        "arch/powerpc/sysdev/mpic.c:mpic_unmask_ipi",
        "arch/powerpc/sysdev/mpic_u3msi.c:u3msi_teardown_msi_irqs",
        "arch/powerpc/sysdev/xics/ics-rtas.c:ics_rtas_map",
        "arch/powerpc/sysdev/xics/ics-opal.c:ics_opal_map",
        "arch/powerpc/platforms/powernv/opal-irqchip.c:opal_interrupt",
        "arch/powerpc/platforms/powernv/pci.c:pnv_teardown_msi_irqs",
        "arch/powerpc/platforms/pseries/ras.c:ras_error_interrupt",
        "arch/powerpc/platforms/pseries/ras.c:ras_epow_interrupt",
        "arch/powerpc/platforms/pseries/ras.c:ras_hotplug_interrupt",
        "arch/powerpc/platforms/pseries/io_event_irq.c:ioei_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282273552,
      "name": "virq_to_hw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
irq_hw_number_t virq_to_hw(unsigned int virq)
```
</details>
</li>
</ul>
