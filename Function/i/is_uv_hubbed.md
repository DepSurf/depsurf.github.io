# Function: <code>is_uv_hubbed</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int is_uv_hubbed(int uvtype)
```

```json
{
  "name": "is_uv_hubbed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609128218,
      "name": "is_uv_hubbed",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:365",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables",
        "arch/x86/kernel/apic/x2apic_uv_x.c:decode_uv_systab",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_mn",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_mn",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_mn",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_mn",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_mn",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_mn",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_tsc_check_sync",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_tsc_check_sync",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_tsc_check_sync",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr"
      ],
      "caller_func": [
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:init_per_cpu",
        "arch/x86/platform/uv/tlb_uv.c:init_per_cpu",
        "arch/x86/platform/uv/tlb_uv.c:init_per_cpu",
        "arch/x86/platform/uv/tlb_uv.c:scan_sock",
        "arch/x86/platform/uv/tlb_uv.c:scan_sock",
        "arch/x86/platform/uv/tlb_uv.c:scan_sock",
        "arch/x86/platform/uv/tlb_uv.c:scan_sock",
        "arch/x86/platform/uv/tlb_uv.c:scan_sock",
        "arch/x86/platform/uv/tlb_uv.c:scan_sock",
        "arch/x86/platform/uv/tlb_uv.c:scan_sock",
        "arch/x86/platform/uv/tlb_uv.c:scan_sock",
        "arch/x86/platform/uv/tlb_uv.c:scan_sock",
        "arch/x86/platform/uv/tlb_uv.c:scan_sock",
        "arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout",
        "arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout",
        "arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout",
        "arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout",
        "arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout",
        "arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout",
        "arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout",
        "arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout",
        "arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout",
        "arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout",
        "arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout",
        "arch/x86/platform/uv/tlb_uv.c:pq_init",
        "arch/x86/platform/uv/tlb_uv.c:pq_init",
        "arch/x86/platform/uv/tlb_uv.c:pq_init",
        "arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init",
        "arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init",
        "arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init",
        "arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init",
        "arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init",
        "arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init",
        "arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init",
        "arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init",
        "arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init",
        "arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init",
        "arch/x86/platform/uv/tlb_uv.c:enable_timeouts",
        "arch/x86/platform/uv/tlb_uv.c:enable_timeouts",
        "arch/x86/platform/uv/tlb_uv.c:enable_timeouts",
        "arch/x86/platform/uv/tlb_uv.c:enable_timeouts",
        "arch/x86/platform/uv/tlb_uv.c:enable_timeouts",
        "arch/x86/platform/uv/tlb_uv.c:enable_timeouts",
        "arch/x86/platform/uv/tlb_uv.c:enable_timeouts",
        "arch/x86/platform/uv/tlb_uv.c:enable_timeouts",
        "arch/x86/platform/uv/tlb_uv.c:enable_timeouts",
        "arch/x86/platform/uv/tlb_uv.c:enable_timeouts",
        "arch/x86/platform/uv/tlb_uv.c:enable_timeouts",
        "arch/x86/platform/uv/tlb_uv.c:enable_timeouts",
        "arch/x86/platform/uv/tlb_uv.c:enable_timeouts",
        "arch/x86/platform/uv/tlb_uv.c:enable_timeouts",
        "arch/x86/platform/uv/tlb_uv.c:enable_timeouts",
        "arch/x86/platform/uv/tlb_uv.c:enable_timeouts",
        "arch/x86/platform/uv/tlb_uv.c:enable_timeouts",
        "arch/x86/platform/uv/tlb_uv.c:enable_timeouts",
        "arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others",
        "arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others",
        "arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others",
        "arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others",
        "arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others",
        "arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others",
        "arch/x86/platform/uv/tlb_uv.c:read_status",
        "arch/x86/platform/uv/tlb_uv.c:read_status",
        "arch/x86/platform/uv/tlb_uv.c:read_status",
        "arch/x86/platform/uv/tlb_uv.c:read_status",
        "arch/x86/platform/uv/tlb_uv.c:read_status",
        "arch/x86/platform/uv/tlb_uv.c:read_status",
        "arch/x86/platform/uv/tlb_uv.c:read_status",
        "arch/x86/platform/uv/tlb_uv.c:read_status",
        "arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:read_mmr_proc_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:read_mmr_proc_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:read_mmr_proc_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:read_gmmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:read_gmmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:read_gmmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_gmmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_gmmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_gmmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_misc_control",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_misc_control",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_misc_control",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_last",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_last",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_last",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_first",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_first",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_first",
        "arch/x86/platform/uv/uv_time.c:uv_read_rtc",
        "arch/x86/platform/uv/uv_time.c:uv_read_rtc",
        "arch/x86/platform/uv/uv_time.c:uv_read_rtc",
        "arch/x86/platform/uv/uv_time.c:uv_read_rtc",
        "arch/x86/platform/uv/uv_time.c:uv_read_rtc",
        "arch/x86/platform/uv/uv_time.c:uv_read_rtc",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579321232,
      "name": "is_uv_hubbed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int is_uv_hubbed(int uvtype)
```

```json
{
  "name": "is_uv_hubbed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579324192,
      "name": "is_uv_hubbed",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:523",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579324192,
      "name": "is_uv_hubbed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int is_uv_hubbed(int uvtype)
```

```json
{
  "name": "is_uv_hubbed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579326912,
      "name": "is_uv_hubbed",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:519",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326912,
      "name": "is_uv_hubbed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int is_uv_hubbed(int uvtype)
```

```json
{
  "name": "is_uv_hubbed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579381392,
      "name": "is_uv_hubbed",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:519",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579381392,
      "name": "is_uv_hubbed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int is_uv_hubbed(int uvtype)
```

```json
{
  "name": "is_uv_hubbed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579446304,
      "name": "is_uv_hubbed",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:525",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579446304,
      "name": "is_uv_hubbed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int is_uv_hubbed(int uvtype)
```

```json
{
  "name": "is_uv_hubbed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579532832,
      "name": "is_uv_hubbed",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:525",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579532832,
      "name": "is_uv_hubbed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int is_uv_hubbed(int uvtype)
```

```json
{
  "name": "is_uv_hubbed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579545744,
      "name": "is_uv_hubbed",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:525",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545744,
      "name": "is_uv_hubbed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int is_uv_hubbed(int uvtype)
```

```json
{
  "name": "is_uv_hubbed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579574320,
      "name": "is_uv_hubbed",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:526",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579574320,
      "name": "is_uv_hubbed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int is_uv_hubbed(int uvtype)
```
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
