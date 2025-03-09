# Struct: <code>irq_chip</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct irq_chip {
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_cpu_online;
    void (*)(struct irq_data *) irq_cpu_offline;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct irq_chip {
    struct device * parent_device;
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_cpu_online;
    void (*)(struct irq_data *) irq_cpu_offline;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct irq_chip {
    struct device * parent_device;
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_cpu_online;
    void (*)(struct irq_data *) irq_cpu_offline;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct irq_chip {
    struct device * parent_device;
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_cpu_online;
    void (*)(struct irq_data *) irq_cpu_offline;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct irq_chip {
    struct device * parent_device;
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_cpu_online;
    void (*)(struct irq_data *) irq_cpu_offline;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct irq_chip {
    struct device * parent_device;
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_cpu_online;
    void (*)(struct irq_data *) irq_cpu_offline;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct irq_chip {
    struct device * parent_device;
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_cpu_online;
    void (*)(struct irq_data *) irq_cpu_offline;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct irq_chip {
    struct device * parent_device;
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_cpu_online;
    void (*)(struct irq_data *) irq_cpu_offline;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    int (*)(struct irq_data *) irq_nmi_setup;
    void (*)(struct irq_data *) irq_nmi_teardown;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct irq_chip {
    struct device * parent_device;
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_cpu_online;
    void (*)(struct irq_data *) irq_cpu_offline;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    int (*)(struct irq_data *) irq_nmi_setup;
    void (*)(struct irq_data *) irq_nmi_teardown;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct irq_chip {
    struct device * parent_device;
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_cpu_online;
    void (*)(struct irq_data *) irq_cpu_offline;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    int (*)(struct irq_data *) irq_nmi_setup;
    void (*)(struct irq_data *) irq_nmi_teardown;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct irq_chip {
    struct device * parent_device;
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_cpu_online;
    void (*)(struct irq_data *) irq_cpu_offline;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    int (*)(struct irq_data *) irq_nmi_setup;
    void (*)(struct irq_data *) irq_nmi_teardown;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct irq_chip {
    struct device * parent_device;
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_cpu_online;
    void (*)(struct irq_data *) irq_cpu_offline;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    int (*)(struct irq_data *) irq_nmi_setup;
    void (*)(struct irq_data *) irq_nmi_teardown;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct irq_chip {
    struct device * parent_device;
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_cpu_online;
    void (*)(struct irq_data *) irq_cpu_offline;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    int (*)(struct irq_data *) irq_nmi_setup;
    void (*)(struct irq_data *) irq_nmi_teardown;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct irq_chip {
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    int (*)(struct irq_data *) irq_nmi_setup;
    void (*)(struct irq_data *) irq_nmi_teardown;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct irq_chip {
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    int (*)(struct irq_data *) irq_nmi_setup;
    void (*)(struct irq_data *) irq_nmi_teardown;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct irq_chip {
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    int (*)(struct irq_data *) irq_nmi_setup;
    void (*)(struct irq_data *) irq_nmi_teardown;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct irq_chip {
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    int (*)(struct irq_data *) irq_nmi_setup;
    void (*)(struct irq_data *) irq_nmi_teardown;
    long unsigned int flags;
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
struct irq_chip {
    struct device * parent_device;
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_cpu_online;
    void (*)(struct irq_data *) irq_cpu_offline;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    int (*)(struct irq_data *) irq_nmi_setup;
    void (*)(struct irq_data *) irq_nmi_teardown;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct irq_chip {
    struct device * parent_device;
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_cpu_online;
    void (*)(struct irq_data *) irq_cpu_offline;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    int (*)(struct irq_data *) irq_nmi_setup;
    void (*)(struct irq_data *) irq_nmi_teardown;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct irq_chip {
    struct device * parent_device;
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_cpu_online;
    void (*)(struct irq_data *) irq_cpu_offline;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    int (*)(struct irq_data *) irq_nmi_setup;
    void (*)(struct irq_data *) irq_nmi_teardown;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct irq_chip {
    struct device * parent_device;
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_cpu_online;
    void (*)(struct irq_data *) irq_cpu_offline;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    int (*)(struct irq_data *) irq_nmi_setup;
    void (*)(struct irq_data *) irq_nmi_teardown;
    long unsigned int flags;
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
struct irq_chip {
    struct device * parent_device;
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_cpu_online;
    void (*)(struct irq_data *) irq_cpu_offline;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    int (*)(struct irq_data *) irq_nmi_setup;
    void (*)(struct irq_data *) irq_nmi_teardown;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct irq_chip {
    struct device * parent_device;
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_cpu_online;
    void (*)(struct irq_data *) irq_cpu_offline;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    int (*)(struct irq_data *) irq_nmi_setup;
    void (*)(struct irq_data *) irq_nmi_teardown;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct irq_chip {
    struct device * parent_device;
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_cpu_online;
    void (*)(struct irq_data *) irq_cpu_offline;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    int (*)(struct irq_data *) irq_nmi_setup;
    void (*)(struct irq_data *) irq_nmi_teardown;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct irq_chip {
    struct device * parent_device;
    const char * name;
    unsigned int (*)(struct irq_data *) irq_startup;
    void (*)(struct irq_data *) irq_shutdown;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_ack;
    void (*)(struct irq_data *) irq_mask;
    void (*)(struct irq_data *) irq_mask_ack;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_eoi;
    int (*)(struct irq_data *, const struct cpumask *, bool) irq_set_affinity;
    int (*)(struct irq_data *) irq_retrigger;
    int (*)(struct irq_data *, unsigned int) irq_set_type;
    int (*)(struct irq_data *, unsigned int) irq_set_wake;
    void (*)(struct irq_data *) irq_bus_lock;
    void (*)(struct irq_data *) irq_bus_sync_unlock;
    void (*)(struct irq_data *) irq_cpu_online;
    void (*)(struct irq_data *) irq_cpu_offline;
    void (*)(struct irq_data *) irq_suspend;
    void (*)(struct irq_data *) irq_resume;
    void (*)(struct irq_data *) irq_pm_shutdown;
    void (*)(struct irq_data *) irq_calc_mask;
    void (*)(struct irq_data *, struct seq_file *) irq_print_chip;
    int (*)(struct irq_data *) irq_request_resources;
    void (*)(struct irq_data *) irq_release_resources;
    void (*)(struct irq_data *, struct msi_msg *) irq_compose_msi_msg;
    void (*)(struct irq_data *, struct msi_msg *) irq_write_msi_msg;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool *) irq_get_irqchip_state;
    int (*)(struct irq_data *, enum irqchip_irq_state, bool) irq_set_irqchip_state;
    int (*)(struct irq_data *, void *) irq_set_vcpu_affinity;
    void (*)(struct irq_data *, unsigned int) ipi_send_single;
    void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask;
    int (*)(struct irq_data *) irq_nmi_setup;
    void (*)(struct irq_data *) irq_nmi_teardown;
    long unsigned int flags;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct device * parent_device</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct irq_data *, unsigned int) ipi_send_single</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct irq_data *, const struct cpumask *) ipi_send_mask</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct irq_data *) irq_nmi_setup</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct irq_data *) irq_nmi_teardown</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct device * parent_device</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct irq_data *) irq_cpu_online</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct irq_data *) irq_cpu_offline</code>
</li>
</ul>
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
