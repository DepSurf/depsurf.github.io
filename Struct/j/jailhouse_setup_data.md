# Struct: <code>jailhouse_setup_data</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct jailhouse_setup_data {
    __u16 version;
    __u16 compatible_version;
    __u16 pm_timer_address;
    __u16 num_cpus;
    __u64 pci_mmconfig_base;
    __u32 tsc_khz;
    __u32 apic_khz;
    __u8 standard_ioapic;
    __u8[255] cpu_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct jailhouse_setup_data {
    __u16 version;
    __u16 compatible_version;
    __u16 pm_timer_address;
    __u16 num_cpus;
    __u64 pci_mmconfig_base;
    __u32 tsc_khz;
    __u32 apic_khz;
    __u8 standard_ioapic;
    __u8[255] cpu_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct jailhouse_setup_data {
    __u16 version;
    __u16 compatible_version;
    __u16 pm_timer_address;
    __u16 num_cpus;
    __u64 pci_mmconfig_base;
    __u32 tsc_khz;
    __u32 apic_khz;
    __u8 standard_ioapic;
    __u8[255] cpu_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct jailhouse_setup_data {
    __u16 version;
    __u16 compatible_version;
    __u16 pm_timer_address;
    __u16 num_cpus;
    __u64 pci_mmconfig_base;
    __u32 tsc_khz;
    __u32 apic_khz;
    __u8 standard_ioapic;
    __u8[255] cpu_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct jailhouse_setup_data {
    struct (anon) hdr;
    struct (anon) v1;
    struct (anon) v2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct jailhouse_setup_data {
    struct (anon) hdr;
    struct (anon) v1;
    struct (anon) v2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct jailhouse_setup_data {
    struct (anon) hdr;
    struct (anon) v1;
    struct (anon) v2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct jailhouse_setup_data {
    struct (anon) hdr;
    struct (anon) v1;
    struct (anon) v2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct jailhouse_setup_data {
    struct (anon) hdr;
    struct (anon) v1;
    struct (anon) v2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct jailhouse_setup_data {
    struct (anon) hdr;
    struct (anon) v1;
    struct (anon) v2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct jailhouse_setup_data {
    struct (anon) hdr;
    struct (anon) v1;
    struct (anon) v2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct jailhouse_setup_data {
    struct (anon) hdr;
    struct (anon) v1;
    struct (anon) v2;
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
struct jailhouse_setup_data {
    __u16 version;
    __u16 compatible_version;
    __u16 pm_timer_address;
    __u16 num_cpus;
    __u64 pci_mmconfig_base;
    __u32 tsc_khz;
    __u32 apic_khz;
    __u8 standard_ioapic;
    __u8[255] cpu_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct jailhouse_setup_data {
    __u16 version;
    __u16 compatible_version;
    __u16 pm_timer_address;
    __u16 num_cpus;
    __u64 pci_mmconfig_base;
    __u32 tsc_khz;
    __u32 apic_khz;
    __u8 standard_ioapic;
    __u8[255] cpu_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct jailhouse_setup_data {
    __u16 version;
    __u16 compatible_version;
    __u16 pm_timer_address;
    __u16 num_cpus;
    __u64 pci_mmconfig_base;
    __u32 tsc_khz;
    __u32 apic_khz;
    __u8 standard_ioapic;
    __u8[255] cpu_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct jailhouse_setup_data {
    __u16 version;
    __u16 compatible_version;
    __u16 pm_timer_address;
    __u16 num_cpus;
    __u64 pci_mmconfig_base;
    __u32 tsc_khz;
    __u32 apic_khz;
    __u8 standard_ioapic;
    __u8[255] cpu_ids;
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct jailhouse_setup_data {
    __u16 version;
    __u16 compatible_version;
    __u16 pm_timer_address;
    __u16 num_cpus;
    __u64 pci_mmconfig_base;
    __u32 tsc_khz;
    __u32 apic_khz;
    __u8 standard_ioapic;
    __u8[255] cpu_ids;
}
```
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct (anon) hdr</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) v1</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) v2</code>
</li>
<li>
<b>Field removed. </b>
<code>__u16 version</code>
</li>
<li>
<b>Field removed. </b>
<code>__u16 compatible_version</code>
</li>
<li>
<b>Field removed. </b>
<code>__u16 pm_timer_address</code>
</li>
<li>
<b>Field removed. </b>
<code>__u16 num_cpus</code>
</li>
<li>
<b>Field removed. </b>
<code>__u64 pci_mmconfig_base</code>
</li>
<li>
<b>Field removed. </b>
<code>__u32 tsc_khz</code>
</li>
<li>
<b>Field removed. </b>
<code>__u32 apic_khz</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 standard_ioapic</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8[255] cpu_ids</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct jailhouse_setup_data {
    __u16 version;
    __u16 compatible_version;
    __u16 pm_timer_address;
    __u16 num_cpus;
    __u64 pci_mmconfig_base;
    __u32 tsc_khz;
    __u32 apic_khz;
    __u8 standard_ioapic;
    __u8[255] cpu_ids;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct jailhouse_setup_data {
    __u16 version;
    __u16 compatible_version;
    __u16 pm_timer_address;
    __u16 num_cpus;
    __u64 pci_mmconfig_base;
    __u32 tsc_khz;
    __u32 apic_khz;
    __u8 standard_ioapic;
    __u8[255] cpu_ids;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct jailhouse_setup_data {
    __u16 version;
    __u16 compatible_version;
    __u16 pm_timer_address;
    __u16 num_cpus;
    __u64 pci_mmconfig_base;
    __u32 tsc_khz;
    __u32 apic_khz;
    __u8 standard_ioapic;
    __u8[255] cpu_ids;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct jailhouse_setup_data {
    __u16 version;
    __u16 compatible_version;
    __u16 pm_timer_address;
    __u16 num_cpus;
    __u64 pci_mmconfig_base;
    __u32 tsc_khz;
    __u32 apic_khz;
    __u8 standard_ioapic;
    __u8[255] cpu_ids;
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
