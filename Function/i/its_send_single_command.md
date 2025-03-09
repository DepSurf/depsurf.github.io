# Function: <code>its_send_single_command</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void its_send_single_command(struct its_node * its, its_cmd_builder_t builder, struct its_cmd_desc * desc)
```

```json
{
  "name": "its_send_single_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496389280,
      "name": "its_send_single_command",
      "external": false,
      "loc": "drivers/irqchip/irq-gic-v3-its.c:845",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_deactivate",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_activate",
        "drivers/irqchip/irq-gic-v3-its.c:its_create_device",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_set_irqchip_state",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_set_irqchip_state",
        "drivers/irqchip/irq-gic-v3-its.c:its_set_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:lpi_update_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496389280,
      "name": "its_send_single_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
void its_send_single_command(struct its_node * its, its_cmd_builder_t builder, struct its_cmd_desc * desc)
```

```json
{
  "name": "its_send_single_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229716980,
      "name": "its_send_single_command",
      "external": false,
      "loc": "drivers/irqchip/irq-gic-v3-its.c:845",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_db_proxy_unmap_locked",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_deactivate",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_activate",
        "drivers/irqchip/irq-gic-v3-its.c:its_create_device",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_set_vcpu_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_set_vcpu_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_set_vcpu_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_set_irqchip_state",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_set_irqchip_state",
        "drivers/irqchip/irq-gic-v3-its.c:its_set_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:lpi_update_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229716980,
      "name": "its_send_single_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void its_send_single_command(struct its_node * its, its_cmd_builder_t builder, struct its_cmd_desc * desc)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void its_send_single_command(struct its_node * its, its_cmd_builder_t builder, struct its_cmd_desc * desc)
```
</details>
</li>
</ul>
