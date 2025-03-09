# Struct: <code>acpi_madt_generic_interrupt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[3] reserved2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[3] reserved2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[3] reserved2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[3] reserved2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[3] reserved2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[3] reserved2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[3] reserved2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[1] reserved2;
    u16 spe_interrupt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[1] reserved2;
    u16 spe_interrupt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[1] reserved2;
    u16 spe_interrupt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[1] reserved2;
    u16 spe_interrupt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[1] reserved2;
    u16 spe_interrupt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[1] reserved2;
    u16 spe_interrupt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[1] reserved2;
    u16 spe_interrupt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[1] reserved2;
    u16 spe_interrupt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[1] reserved2;
    u16 spe_interrupt;
    u16 trbe_interrupt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[1] reserved2;
    u16 spe_interrupt;
    u16 trbe_interrupt;
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
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[1] reserved2;
    u16 spe_interrupt;
}
```
</details>
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
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[1] reserved2;
    u16 spe_interrupt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[1] reserved2;
    u16 spe_interrupt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[1] reserved2;
    u16 spe_interrupt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[1] reserved2;
    u16 spe_interrupt;
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u16 spe_interrupt</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8[3] reserved2</code> ➡️ <code>u8[1] reserved2</code>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u16 trbe_interrupt</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[1] reserved2;
    u16 spe_interrupt;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[1] reserved2;
    u16 spe_interrupt;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct acpi_madt_generic_interrupt {
    struct acpi_subtable_header header;
    u16 reserved;
    u32 cpu_interface_number;
    u32 uid;
    u32 flags;
    u32 parking_version;
    u32 performance_interrupt;
    u64 parked_address;
    u64 base_address;
    u64 gicv_base_address;
    u64 gich_base_address;
    u32 vgic_interrupt;
    u64 gicr_base_address;
    u64 arm_mpidr;
    u8 efficiency_class;
    u8[1] reserved2;
    u16 spe_interrupt;
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
