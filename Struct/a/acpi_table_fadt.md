# Struct: <code>acpi_table_fadt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
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
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
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
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct acpi_table_fadt {
    struct acpi_table_header header;
    u32 facs;
    u32 dsdt;
    u8 model;
    u8 preferred_profile;
    u16 sci_interrupt;
    u32 smi_command;
    u8 acpi_enable;
    u8 acpi_disable;
    u8 s4_bios_request;
    u8 pstate_control;
    u32 pm1a_event_block;
    u32 pm1b_event_block;
    u32 pm1a_control_block;
    u32 pm1b_control_block;
    u32 pm2_control_block;
    u32 pm_timer_block;
    u32 gpe0_block;
    u32 gpe1_block;
    u8 pm1_event_length;
    u8 pm1_control_length;
    u8 pm2_control_length;
    u8 pm_timer_length;
    u8 gpe0_block_length;
    u8 gpe1_block_length;
    u8 gpe1_base;
    u8 cst_control;
    u16 c2_latency;
    u16 c3_latency;
    u16 flush_size;
    u16 flush_stride;
    u8 duty_offset;
    u8 duty_width;
    u8 day_alarm;
    u8 month_alarm;
    u8 century;
    u16 boot_flags;
    u8 reserved;
    u32 flags;
    struct acpi_generic_address reset_register;
    u8 reset_value;
    u16 arm_boot_flags;
    u8 minor_revision;
    u64 Xfacs;
    u64 Xdsdt;
    struct acpi_generic_address xpm1a_event_block;
    struct acpi_generic_address xpm1b_event_block;
    struct acpi_generic_address xpm1a_control_block;
    struct acpi_generic_address xpm1b_control_block;
    struct acpi_generic_address xpm2_control_block;
    struct acpi_generic_address xpm_timer_block;
    struct acpi_generic_address xgpe0_block;
    struct acpi_generic_address xgpe1_block;
    struct acpi_generic_address sleep_control;
    struct acpi_generic_address sleep_status;
    u64 hypervisor_id;
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
