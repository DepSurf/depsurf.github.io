# Struct: <code>apic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct apic {
    char * name;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(int) apic_id_valid;
    int (*)() apic_id_registered;
    u32 irq_delivery_mode;
    u32 irq_dest_mode;
    const struct cpumask * (*)() target_cpus;
    int disable_esr;
    int dest_logical;
    long unsigned int (*)(physid_mask_t *, int) check_apicid_used;
    void (*)(int, struct cpumask *, const struct cpumask *) vector_allocation_domain;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    unsigned int (*)(long unsigned int) get_apic_id;
    long unsigned int (*)(unsigned int) set_apic_id;
    long unsigned int apic_id_mask;
    int (*)(const struct cpumask *, const struct cpumask *, unsigned int *) cpu_mask_to_apicid_and;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    void (*)(int) inquire_remote_apic;
    u32 (*)(u32) read;
    void (*)(u32, u32) write;
    void (*)(u32, u32) eoi_write;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct apic {
    char * name;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(int) apic_id_valid;
    int (*)() apic_id_registered;
    u32 irq_delivery_mode;
    u32 irq_dest_mode;
    const struct cpumask * (*)() target_cpus;
    int disable_esr;
    int dest_logical;
    long unsigned int (*)(physid_mask_t *, int) check_apicid_used;
    void (*)(int, struct cpumask *, const struct cpumask *) vector_allocation_domain;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    unsigned int (*)(long unsigned int) get_apic_id;
    long unsigned int (*)(unsigned int) set_apic_id;
    int (*)(const struct cpumask *, const struct cpumask *, unsigned int *) cpu_mask_to_apicid_and;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    void (*)(int) inquire_remote_apic;
    u32 (*)(u32) read;
    void (*)(u32, u32) write;
    void (*)(u32, u32) eoi_write;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct apic {
    char * name;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(int) apic_id_valid;
    int (*)() apic_id_registered;
    u32 irq_delivery_mode;
    u32 irq_dest_mode;
    const struct cpumask * (*)() target_cpus;
    int disable_esr;
    int dest_logical;
    long unsigned int (*)(physid_mask_t *, int) check_apicid_used;
    void (*)(int, struct cpumask *, const struct cpumask *) vector_allocation_domain;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    unsigned int (*)(long unsigned int) get_apic_id;
    long unsigned int (*)(unsigned int) set_apic_id;
    int (*)(const struct cpumask *, const struct cpumask *, unsigned int *) cpu_mask_to_apicid_and;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    void (*)(int) inquire_remote_apic;
    u32 (*)(u32) read;
    void (*)(u32, u32) write;
    void (*)(u32, u32) eoi_write;
    void (*)(u32, u32) native_eoi_write;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct apic {
    char * name;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(int) apic_id_valid;
    int (*)() apic_id_registered;
    u32 irq_delivery_mode;
    u32 irq_dest_mode;
    const struct cpumask * (*)() target_cpus;
    int disable_esr;
    int dest_logical;
    long unsigned int (*)(physid_mask_t *, int) check_apicid_used;
    void (*)(int, struct cpumask *, const struct cpumask *) vector_allocation_domain;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    unsigned int (*)(long unsigned int) get_apic_id;
    long unsigned int (*)(unsigned int) set_apic_id;
    int (*)(const struct cpumask *, struct irq_data *, unsigned int *) cpu_mask_to_apicid;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    void (*)(int) inquire_remote_apic;
    u32 (*)(u32) read;
    void (*)(u32, u32) write;
    void (*)(u32, u32) eoi_write;
    void (*)(u32, u32) native_eoi_write;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct apic {
    void (*)(u32, u32) eoi_write;
    void (*)(u32, u32) native_eoi_write;
    void (*)(u32, u32) write;
    u32 (*)(u32) read;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    u32 dest_logical;
    u32 disable_esr;
    u32 irq_delivery_mode;
    u32 irq_dest_mode;
    void (*)(int, struct cpumask *, const struct cpumask *) vector_allocation_domain;
    int (*)(const struct cpumask *, struct irq_data *, unsigned int *) cpu_mask_to_apicid;
    u32 (*)(unsigned int) calc_dest_apicid;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(int) apic_id_valid;
    int (*)() apic_id_registered;
    bool (*)(physid_mask_t *, int) check_apicid_used;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    u32 (*)(long unsigned int) get_apic_id;
    u32 (*)(unsigned int) set_apic_id;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    void (*)(int) inquire_remote_apic;
    char * name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct apic {
    void (*)(u32, u32) eoi_write;
    void (*)(u32, u32) native_eoi_write;
    void (*)(u32, u32) write;
    u32 (*)(u32) read;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    u32 dest_logical;
    u32 disable_esr;
    u32 irq_delivery_mode;
    u32 irq_dest_mode;
    u32 (*)(unsigned int) calc_dest_apicid;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(u32) apic_id_valid;
    int (*)() apic_id_registered;
    bool (*)(physid_mask_t *, int) check_apicid_used;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    u32 (*)(long unsigned int) get_apic_id;
    u32 (*)(unsigned int) set_apic_id;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    void (*)(int) inquire_remote_apic;
    char * name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct apic {
    void (*)(u32, u32) eoi_write;
    void (*)(u32, u32) native_eoi_write;
    void (*)(u32, u32) write;
    u32 (*)(u32) read;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    u32 dest_logical;
    u32 disable_esr;
    u32 irq_delivery_mode;
    u32 irq_dest_mode;
    u32 (*)(unsigned int) calc_dest_apicid;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(u32) apic_id_valid;
    int (*)() apic_id_registered;
    bool (*)(physid_mask_t *, int) check_apicid_used;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    u32 (*)(long unsigned int) get_apic_id;
    u32 (*)(unsigned int) set_apic_id;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    void (*)(int) inquire_remote_apic;
    char * name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct apic {
    void (*)(u32, u32) eoi_write;
    void (*)(u32, u32) native_eoi_write;
    void (*)(u32, u32) write;
    u32 (*)(u32) read;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    u32 dest_logical;
    u32 disable_esr;
    u32 irq_delivery_mode;
    u32 irq_dest_mode;
    u32 (*)(unsigned int) calc_dest_apicid;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(u32) apic_id_valid;
    int (*)() apic_id_registered;
    bool (*)(physid_mask_t *, int) check_apicid_used;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    u32 (*)(long unsigned int) get_apic_id;
    u32 (*)(unsigned int) set_apic_id;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    void (*)(int) inquire_remote_apic;
    char * name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct apic {
    void (*)(u32, u32) eoi_write;
    void (*)(u32, u32) native_eoi_write;
    void (*)(u32, u32) write;
    u32 (*)(u32) read;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    u32 dest_logical;
    u32 disable_esr;
    u32 irq_delivery_mode;
    u32 irq_dest_mode;
    u32 (*)(unsigned int) calc_dest_apicid;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(u32) apic_id_valid;
    int (*)() apic_id_registered;
    bool (*)(physid_mask_t *, int) check_apicid_used;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    u32 (*)(long unsigned int) get_apic_id;
    u32 (*)(unsigned int) set_apic_id;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    void (*)(int) inquire_remote_apic;
    char * name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct apic {
    void (*)(u32, u32) eoi_write;
    void (*)(u32, u32) native_eoi_write;
    void (*)(u32, u32) write;
    u32 (*)(u32) read;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    u32 dest_logical;
    u32 disable_esr;
    u32 irq_delivery_mode;
    u32 irq_dest_mode;
    u32 (*)(unsigned int) calc_dest_apicid;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(u32) apic_id_valid;
    int (*)() apic_id_registered;
    bool (*)(physid_mask_t *, int) check_apicid_used;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    u32 (*)(long unsigned int) get_apic_id;
    u32 (*)(unsigned int) set_apic_id;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    void (*)(int) inquire_remote_apic;
    char * name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct apic {
    void (*)(u32, u32) eoi_write;
    void (*)(u32, u32) native_eoi_write;
    void (*)(u32, u32) write;
    u32 (*)(u32) read;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    u32 disable_esr;
    enum apic_delivery_modes delivery_mode;
    bool dest_mode_logical;
    u32 (*)(unsigned int) calc_dest_apicid;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(u32) apic_id_valid;
    int (*)() apic_id_registered;
    bool (*)(physid_mask_t *, int) check_apicid_used;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    u32 (*)(long unsigned int) get_apic_id;
    u32 (*)(unsigned int) set_apic_id;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    void (*)(int) inquire_remote_apic;
    char * name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct apic {
    void (*)(u32, u32) eoi_write;
    void (*)(u32, u32) native_eoi_write;
    void (*)(u32, u32) write;
    u32 (*)(u32) read;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    u32 disable_esr;
    enum apic_delivery_modes delivery_mode;
    bool dest_mode_logical;
    u32 (*)(unsigned int) calc_dest_apicid;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(u32) apic_id_valid;
    int (*)() apic_id_registered;
    bool (*)(physid_mask_t *, int) check_apicid_used;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    u32 (*)(long unsigned int) get_apic_id;
    u32 (*)(unsigned int) set_apic_id;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    void (*)(int) inquire_remote_apic;
    char * name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct apic {
    void (*)(u32, u32) eoi_write;
    void (*)(u32, u32) native_eoi_write;
    void (*)(u32, u32) write;
    u32 (*)(u32) read;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    u32 disable_esr;
    enum apic_delivery_modes delivery_mode;
    bool dest_mode_logical;
    u32 (*)(unsigned int) calc_dest_apicid;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(u32) apic_id_valid;
    int (*)() apic_id_registered;
    bool (*)(physid_mask_t *, int) check_apicid_used;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    u32 (*)(long unsigned int) get_apic_id;
    u32 (*)(unsigned int) set_apic_id;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    void (*)(int) inquire_remote_apic;
    char * name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct apic {
    void (*)(u32, u32) eoi_write;
    void (*)(u32, u32) native_eoi_write;
    void (*)(u32, u32) write;
    u32 (*)(u32) read;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    u32 disable_esr;
    enum apic_delivery_modes delivery_mode;
    bool dest_mode_logical;
    u32 (*)(unsigned int) calc_dest_apicid;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(u32) apic_id_valid;
    int (*)() apic_id_registered;
    bool (*)(physid_mask_t *, int) check_apicid_used;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    u32 (*)(long unsigned int) get_apic_id;
    u32 (*)(unsigned int) set_apic_id;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    int (*)(int, long unsigned int) wakeup_secondary_cpu_64;
    void (*)(int) inquire_remote_apic;
    char * name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct apic {
    void (*)(u32, u32) eoi_write;
    void (*)(u32, u32) native_eoi_write;
    void (*)(u32, u32) write;
    u32 (*)(u32) read;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    u32 disable_esr;
    enum apic_delivery_modes delivery_mode;
    bool dest_mode_logical;
    u32 (*)(unsigned int) calc_dest_apicid;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(u32) apic_id_valid;
    int (*)() apic_id_registered;
    bool (*)(physid_mask_t *, int) check_apicid_used;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    u32 (*)(long unsigned int) get_apic_id;
    u32 (*)(unsigned int) set_apic_id;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    int (*)(int, long unsigned int) wakeup_secondary_cpu_64;
    void (*)(int) inquire_remote_apic;
    char * name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct apic {
    void (*)(u32, u32) eoi_write;
    void (*)(u32, u32) native_eoi_write;
    void (*)(u32, u32) write;
    u32 (*)(u32) read;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    u32 disable_esr;
    enum apic_delivery_modes delivery_mode;
    bool dest_mode_logical;
    u32 (*)(unsigned int) calc_dest_apicid;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(u32) apic_id_valid;
    int (*)() apic_id_registered;
    bool (*)(physid_mask_t *, int) check_apicid_used;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    u32 (*)(long unsigned int) get_apic_id;
    u32 (*)(unsigned int) set_apic_id;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    int (*)(int, long unsigned int) wakeup_secondary_cpu_64;
    void (*)(int) inquire_remote_apic;
    char * name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct apic {
    void (*)() eoi;
    void (*)() native_eoi;
    void (*)(u32, u32) write;
    u32 (*)(u32) read;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    u32 disable_esr;
    u32 dest_mode_logical;
    u32 x2apic_set_max_apicid;
    u32 nmi_to_offline_cpu;
    u32 (*)(unsigned int) calc_dest_apicid;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    u32 max_apic_id;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    bool (*)() apic_id_registered;
    bool (*)(physid_mask_t *, u32) check_apicid_used;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    u32 (*)(int) cpu_present_to_apicid;
    u32 (*)(u32, int) phys_pkg_id;
    u32 (*)(u32) get_apic_id;
    u32 (*)(u32) set_apic_id;
    int (*)(u32, long unsigned int) wakeup_secondary_cpu;
    int (*)(u32, long unsigned int) wakeup_secondary_cpu_64;
    char * name;
}
```
</details>
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct apic {
    void (*)(u32, u32) eoi_write;
    void (*)(u32, u32) native_eoi_write;
    void (*)(u32, u32) write;
    u32 (*)(u32) read;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    u32 dest_logical;
    u32 disable_esr;
    u32 irq_delivery_mode;
    u32 irq_dest_mode;
    u32 (*)(unsigned int) calc_dest_apicid;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(u32) apic_id_valid;
    int (*)() apic_id_registered;
    bool (*)(physid_mask_t *, int) check_apicid_used;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    u32 (*)(long unsigned int) get_apic_id;
    u32 (*)(unsigned int) set_apic_id;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    void (*)(int) inquire_remote_apic;
    char * name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct apic {
    void (*)(u32, u32) eoi_write;
    void (*)(u32, u32) native_eoi_write;
    void (*)(u32, u32) write;
    u32 (*)(u32) read;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    u32 dest_logical;
    u32 disable_esr;
    u32 irq_delivery_mode;
    u32 irq_dest_mode;
    u32 (*)(unsigned int) calc_dest_apicid;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(u32) apic_id_valid;
    int (*)() apic_id_registered;
    bool (*)(physid_mask_t *, int) check_apicid_used;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    u32 (*)(long unsigned int) get_apic_id;
    u32 (*)(unsigned int) set_apic_id;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    void (*)(int) inquire_remote_apic;
    char * name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct apic {
    void (*)(u32, u32) eoi_write;
    void (*)(u32, u32) native_eoi_write;
    void (*)(u32, u32) write;
    u32 (*)(u32) read;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    u32 dest_logical;
    u32 disable_esr;
    u32 irq_delivery_mode;
    u32 irq_dest_mode;
    u32 (*)(unsigned int) calc_dest_apicid;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(u32) apic_id_valid;
    int (*)() apic_id_registered;
    bool (*)(physid_mask_t *, int) check_apicid_used;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    u32 (*)(long unsigned int) get_apic_id;
    u32 (*)(unsigned int) set_apic_id;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    void (*)(int) inquire_remote_apic;
    char * name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct apic {
    void (*)(u32, u32) eoi_write;
    void (*)(u32, u32) native_eoi_write;
    void (*)(u32, u32) write;
    u32 (*)(u32) read;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    u32 dest_logical;
    u32 disable_esr;
    u32 irq_delivery_mode;
    u32 irq_dest_mode;
    u32 (*)(unsigned int) calc_dest_apicid;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(u32) apic_id_valid;
    int (*)() apic_id_registered;
    bool (*)(physid_mask_t *, int) check_apicid_used;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    u32 (*)(long unsigned int) get_apic_id;
    u32 (*)(unsigned int) set_apic_id;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    void (*)(int) inquire_remote_apic;
    char * name;
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
<code>void (*)(int, int) send_IPI</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int apic_id_mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(u32, u32) native_eoi_write</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(const struct cpumask *, struct irq_data *, unsigned int *) cpu_mask_to_apicid</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(const struct cpumask *, const struct cpumask *, unsigned int *) cpu_mask_to_apicid_and</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 (*)(unsigned int) calc_dest_apicid</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct cpumask * (*)() target_cpus</code>
</li>
<li>
<b>Field type changed. </b>
<code>int disable_esr</code> ➡️ <code>u32 disable_esr</code>
</li>
<li>
<b>Field type changed. </b>
<code>int dest_logical</code> ➡️ <code>u32 dest_logical</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int (*)(physid_mask_t *, int) check_apicid_used</code> ➡️ <code>bool (*)(physid_mask_t *, int) check_apicid_used</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int (*)(long unsigned int) get_apic_id</code> ➡️ <code>u32 (*)(long unsigned int) get_apic_id</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int (*)(unsigned int) set_apic_id</code> ➡️ <code>u32 (*)(unsigned int) set_apic_id</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>void (*)(int, struct cpumask *, const struct cpumask *) vector_allocation_domain</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(const struct cpumask *, struct irq_data *, unsigned int *) cpu_mask_to_apicid</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(int) apic_id_valid</code> ➡️ <code>int (*)(u32) apic_id_valid</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>enum apic_delivery_modes delivery_mode</code>
</li>
<li>
<b>Field added. </b>
<code>bool dest_mode_logical</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 dest_logical</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 irq_delivery_mode</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 irq_dest_mode</code>
</li>
</ul>
</details>
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
<b>Field added. </b>
<code>int (*)(int, long unsigned int) wakeup_secondary_cpu_64</code>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)() eoi</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)() native_eoi</code>
</li>
<li>
<b>Field added. </b>
<code>u32 x2apic_set_max_apicid</code>
</li>
<li>
<b>Field added. </b>
<code>u32 nmi_to_offline_cpu</code>
</li>
<li>
<b>Field added. </b>
<code>u32 max_apic_id</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(u32, u32) eoi_write</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(u32, u32) native_eoi_write</code>
</li>
<li>
<b>Field removed. </b>
<code>enum apic_delivery_modes delivery_mode</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(u32) apic_id_valid</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)() setup_apic_routing</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(int, physid_mask_t *) apicid_to_cpu_present</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(int) check_phys_apicid_present</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(int) inquire_remote_apic</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool dest_mode_logical</code> ➡️ <code>u32 dest_mode_logical</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)() apic_id_registered</code> ➡️ <code>bool (*)() apic_id_registered</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool (*)(physid_mask_t *, int) check_apicid_used</code> ➡️ <code>bool (*)(physid_mask_t *, u32) check_apicid_used</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(int) cpu_present_to_apicid</code> ➡️ <code>u32 (*)(int) cpu_present_to_apicid</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(int, int) phys_pkg_id</code> ➡️ <code>u32 (*)(u32, int) phys_pkg_id</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 (*)(long unsigned int) get_apic_id</code> ➡️ <code>u32 (*)(u32) get_apic_id</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 (*)(unsigned int) set_apic_id</code> ➡️ <code>u32 (*)(u32) set_apic_id</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(int, long unsigned int) wakeup_secondary_cpu</code> ➡️ <code>int (*)(u32, long unsigned int) wakeup_secondary_cpu</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(int, long unsigned int) wakeup_secondary_cpu_64</code> ➡️ <code>int (*)(u32, long unsigned int) wakeup_secondary_cpu_64</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct apic {
    void (*)(u32, u32) eoi_write;
    void (*)(u32, u32) native_eoi_write;
    void (*)(u32, u32) write;
    u32 (*)(u32) read;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    u32 dest_logical;
    u32 disable_esr;
    u32 irq_delivery_mode;
    u32 irq_dest_mode;
    u32 (*)(unsigned int) calc_dest_apicid;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(u32) apic_id_valid;
    int (*)() apic_id_registered;
    bool (*)(physid_mask_t *, int) check_apicid_used;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    u32 (*)(long unsigned int) get_apic_id;
    u32 (*)(unsigned int) set_apic_id;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    void (*)(int) inquire_remote_apic;
    char * name;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct apic {
    void (*)(u32, u32) eoi_write;
    void (*)(u32, u32) native_eoi_write;
    void (*)(u32, u32) write;
    u32 (*)(u32) read;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    u32 dest_logical;
    u32 disable_esr;
    u32 irq_delivery_mode;
    u32 irq_dest_mode;
    u32 (*)(unsigned int) calc_dest_apicid;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(u32) apic_id_valid;
    int (*)() apic_id_registered;
    bool (*)(physid_mask_t *, int) check_apicid_used;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    u32 (*)(long unsigned int) get_apic_id;
    u32 (*)(unsigned int) set_apic_id;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    void (*)(int) inquire_remote_apic;
    char * name;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct apic {
    void (*)(u32, u32) eoi_write;
    void (*)(u32, u32) native_eoi_write;
    void (*)(u32, u32) write;
    u32 (*)(u32) read;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    u32 dest_logical;
    u32 disable_esr;
    u32 irq_delivery_mode;
    u32 irq_dest_mode;
    u32 (*)(unsigned int) calc_dest_apicid;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(u32) apic_id_valid;
    int (*)() apic_id_registered;
    bool (*)(physid_mask_t *, int) check_apicid_used;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    u32 (*)(long unsigned int) get_apic_id;
    u32 (*)(unsigned int) set_apic_id;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    void (*)(int) inquire_remote_apic;
    char * name;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct apic {
    void (*)(u32, u32) eoi_write;
    void (*)(u32, u32) native_eoi_write;
    void (*)(u32, u32) write;
    u32 (*)(u32) read;
    void (*)() wait_icr_idle;
    u32 (*)() safe_wait_icr_idle;
    void (*)(int, int) send_IPI;
    void (*)(const struct cpumask *, int) send_IPI_mask;
    void (*)(const struct cpumask *, int) send_IPI_mask_allbutself;
    void (*)(int) send_IPI_allbutself;
    void (*)(int) send_IPI_all;
    void (*)(int) send_IPI_self;
    u32 dest_logical;
    u32 disable_esr;
    u32 irq_delivery_mode;
    u32 irq_dest_mode;
    u32 (*)(unsigned int) calc_dest_apicid;
    u64 (*)() icr_read;
    void (*)(u32, u32) icr_write;
    int (*)() probe;
    int (*)(char *, char *) acpi_madt_oem_check;
    int (*)(u32) apic_id_valid;
    int (*)() apic_id_registered;
    bool (*)(physid_mask_t *, int) check_apicid_used;
    void (*)() init_apic_ldr;
    void (*)(physid_mask_t *, physid_mask_t *) ioapic_phys_id_map;
    void (*)() setup_apic_routing;
    int (*)(int) cpu_present_to_apicid;
    void (*)(int, physid_mask_t *) apicid_to_cpu_present;
    int (*)(int) check_phys_apicid_present;
    int (*)(int, int) phys_pkg_id;
    u32 (*)(long unsigned int) get_apic_id;
    u32 (*)(unsigned int) set_apic_id;
    int (*)(int, long unsigned int) wakeup_secondary_cpu;
    void (*)(int) inquire_remote_apic;
    char * name;
}
```
</details>
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
