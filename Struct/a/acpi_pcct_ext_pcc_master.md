# Struct: <code>acpi_pcct_ext_pcc_master</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct acpi_pcct_ext_pcc_master {
    struct acpi_subtable_header header;
    u32 platform_interrupt;
    u8 flags;
    u8 reserved1;
    u64 base_address;
    u32 length;
    struct acpi_generic_address doorbell_register;
    u64 preserve_mask;
    u64 write_mask;
    u32 latency;
    u32 max_access_rate;
    u32 min_turnaround_time;
    struct acpi_generic_address platform_ack_register;
    u64 ack_preserve_mask;
    u64 ack_set_mask;
    u64 reserved2;
    struct acpi_generic_address cmd_complete_register;
    u64 cmd_complete_mask;
    struct acpi_generic_address cmd_update_register;
    u64 cmd_update_preserve_mask;
    u64 cmd_update_set_mask;
    struct acpi_generic_address error_status_register;
    u64 error_status_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct acpi_pcct_ext_pcc_master {
    struct acpi_subtable_header header;
    u32 platform_interrupt;
    u8 flags;
    u8 reserved1;
    u64 base_address;
    u32 length;
    struct acpi_generic_address doorbell_register;
    u64 preserve_mask;
    u64 write_mask;
    u32 latency;
    u32 max_access_rate;
    u32 min_turnaround_time;
    struct acpi_generic_address platform_ack_register;
    u64 ack_preserve_mask;
    u64 ack_set_mask;
    u64 reserved2;
    struct acpi_generic_address cmd_complete_register;
    u64 cmd_complete_mask;
    struct acpi_generic_address cmd_update_register;
    u64 cmd_update_preserve_mask;
    u64 cmd_update_set_mask;
    struct acpi_generic_address error_status_register;
    u64 error_status_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct acpi_pcct_ext_pcc_master {
    struct acpi_subtable_header header;
    u32 platform_interrupt;
    u8 flags;
    u8 reserved1;
    u64 base_address;
    u32 length;
    struct acpi_generic_address doorbell_register;
    u64 preserve_mask;
    u64 write_mask;
    u32 latency;
    u32 max_access_rate;
    u32 min_turnaround_time;
    struct acpi_generic_address platform_ack_register;
    u64 ack_preserve_mask;
    u64 ack_set_mask;
    u64 reserved2;
    struct acpi_generic_address cmd_complete_register;
    u64 cmd_complete_mask;
    struct acpi_generic_address cmd_update_register;
    u64 cmd_update_preserve_mask;
    u64 cmd_update_set_mask;
    struct acpi_generic_address error_status_register;
    u64 error_status_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct acpi_pcct_ext_pcc_master {
    struct acpi_subtable_header header;
    u32 platform_interrupt;
    u8 flags;
    u8 reserved1;
    u64 base_address;
    u32 length;
    struct acpi_generic_address doorbell_register;
    u64 preserve_mask;
    u64 write_mask;
    u32 latency;
    u32 max_access_rate;
    u32 min_turnaround_time;
    struct acpi_generic_address platform_ack_register;
    u64 ack_preserve_mask;
    u64 ack_set_mask;
    u64 reserved2;
    struct acpi_generic_address cmd_complete_register;
    u64 cmd_complete_mask;
    struct acpi_generic_address cmd_update_register;
    u64 cmd_update_preserve_mask;
    u64 cmd_update_set_mask;
    struct acpi_generic_address error_status_register;
    u64 error_status_mask;
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct acpi_pcct_ext_pcc_master {
    struct acpi_subtable_header header;
    u32 platform_interrupt;
    u8 flags;
    u8 reserved1;
    u64 base_address;
    u32 length;
    struct acpi_generic_address doorbell_register;
    u64 preserve_mask;
    u64 write_mask;
    u32 latency;
    u32 max_access_rate;
    u32 min_turnaround_time;
    struct acpi_generic_address platform_ack_register;
    u64 ack_preserve_mask;
    u64 ack_set_mask;
    u64 reserved2;
    struct acpi_generic_address cmd_complete_register;
    u64 cmd_complete_mask;
    struct acpi_generic_address cmd_update_register;
    u64 cmd_update_preserve_mask;
    u64 cmd_update_set_mask;
    struct acpi_generic_address error_status_register;
    u64 error_status_mask;
}
```
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
