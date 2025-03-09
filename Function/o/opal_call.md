# Function: <code>opal_call</code>

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
int64_t opal_call(int64_t a0, int64_t a1, int64_t a2, int64_t a3, int64_t a4, int64_t a5, int64_t a6, int64_t a7, int64_t opcode)
```

```json
{
  "name": "opal_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282958736,
      "name": "opal_call",
      "external": false,
      "loc": "arch/powerpc/platforms/powernv/opal-call.c:95",
      "file": "arch/powerpc/platforms/powernv/opal-call.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/opal-call.c:opal_secvar_enqueue_update",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_secvar_get_next",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_secvar_get",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_mpipl_query_tag",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_mpipl_register_tag",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_mpipl_update",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_nx_coproc_init",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_sensor_group_enable",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_sensor_read_u64",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_set_pbcq_tunnel_bar",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_get_pbcq_tunnel_bar",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_npu_tl_set",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_npu_spa_clear_cache",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_npu_spa_setup",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_quiesce",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_sensor_group_clear",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_set_power_shift_ratio",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_get_power_shift_ratio",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_set_powercap",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_get_powercap",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_imc_counters_stop",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_imc_counters_start",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_imc_counters_init",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_npu_map_lpar",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_npu_destroy_context",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_npu_init_context",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_signal_system_reset",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_xive_get_vp_state",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_xive_set_queue_state",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_xive_get_queue_state",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_xive_dump",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_xive_sync",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_xive_set_vp_info",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_xive_get_vp_info",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_xive_free_irq",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_xive_allocate_irq_raw",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_xive_free_vp_block",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_xive_alloc_vp_block",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_xive_donate_page",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_xive_set_queue_info",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_xive_get_queue_info",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_xive_set_irq_config",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_xive_get_irq_config",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_xive_get_irq_info",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_xive_reset",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_nmmu_set_ptcr",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_tce_kill",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_int_set_mfrr",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_int_eoi",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_int_set_cppr",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_int_get_xirr",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_set_power_state",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_get_power_state",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_get_presence_state",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_get_device_tree",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_console_flush",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_leds_set_ind",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_leds_get_ind",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_prd_msg",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_flash_erase",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_flash_write",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_flash_read",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_i2c_request",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_ipmi_recv",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_ipmi_send",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_tpo_read",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_tpo_write",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_set_phb_cxl_mode",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_unregister_dump_region",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_register_dump_region",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_slw_set_reg",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_config_cpu_idle_state",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_handle_hmi2",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_handle_hmi",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_set_param",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_get_param",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_sensor_read",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_sync_host_reboot",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_dump_resend_notification",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_check_completion",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_write_oppanel_async",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_get_msg",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_dump_ack",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_dump_read",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_dump_info2",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_dump_info",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_dump_init",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_check_token",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_resync_timebase",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_update_flash",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_manage_flash",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_validate_flash",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_write_elog",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_resend_pending_logs",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_get_elog_size",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_send_ack_elog",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_read_elog",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_reinit_cpus",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_return_cpu",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_lpc_write",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_lpc_read",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_xscom_write",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_xscom_read",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_get_phb_diag_data2",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_msi_eoi",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_poll",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_next_error",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_set_system_attention_led",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_get_dpo_status",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_get_epow_status",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_set_slot_led_status",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_mask_pe_error",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_reinit",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_fence_phb",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_get_phb_diag_data",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_get_hub_diag_data",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_reset",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_map_pe_dma_window_real",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_map_pe_dma_window",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_write_oppanel",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_query_cpu_status",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_start_cpu",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_get_msi_64",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_get_msi_32",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_get_xive_source",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_set_xive_pe",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_set_xive_reissue",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_get_xive_reissue",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_set_mve_enable",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_set_mve",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_set_peltv",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_set_pe",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_set_phb_table_memory",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_map_pe_mmio_window",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_set_phb_mem_window",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_phb_mmio_enable",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_shpc",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_err_inject",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_eeh_freeze_set",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_eeh_freeze_clear",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_eeh_freeze_status",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_register_exception_handler",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_get_xive",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_set_xive",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_config_write_word",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_config_write_half_word",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_config_write_byte",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_config_read_word",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_config_read_half_word",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_config_read_byte",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_set_phb_tce_memory",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_pci_set_hub_tce_memory",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_poll_events",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_handle_interrupt",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_write_nvram",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_read_nvram",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_cec_reboot2",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_cec_reboot",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_cec_power_down",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_rtc_write",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_rtc_read",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_console_write_buffer_space",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_console_read",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_console_write",
        "arch/powerpc/platforms/powernv/opal-call.c:opal_invalid_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282958736,
      "name": "opal_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 916
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
int64_t opal_call(int64_t a0, int64_t a1, int64_t a2, int64_t a3, int64_t a4, int64_t a5, int64_t a6, int64_t a7, int64_t opcode)
```
</details>
</li>
</ul>
