# Struct: <code>sdma_script_start_addrs</code>

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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sdma_script_start_addrs {
    s32 ap_2_ap_addr;
    s32 ap_2_bp_addr;
    s32 ap_2_ap_fixed_addr;
    s32 bp_2_ap_addr;
    s32 loopback_on_dsp_side_addr;
    s32 mcu_interrupt_only_addr;
    s32 firi_2_per_addr;
    s32 firi_2_mcu_addr;
    s32 per_2_firi_addr;
    s32 mcu_2_firi_addr;
    s32 uart_2_per_addr;
    s32 uart_2_mcu_addr;
    s32 per_2_app_addr;
    s32 mcu_2_app_addr;
    s32 per_2_per_addr;
    s32 uartsh_2_per_addr;
    s32 uartsh_2_mcu_addr;
    s32 per_2_shp_addr;
    s32 mcu_2_shp_addr;
    s32 ata_2_mcu_addr;
    s32 mcu_2_ata_addr;
    s32 app_2_per_addr;
    s32 app_2_mcu_addr;
    s32 shp_2_per_addr;
    s32 shp_2_mcu_addr;
    s32 mshc_2_mcu_addr;
    s32 mcu_2_mshc_addr;
    s32 spdif_2_mcu_addr;
    s32 mcu_2_spdif_addr;
    s32 asrc_2_mcu_addr;
    s32 ext_mem_2_ipu_addr;
    s32 descrambler_addr;
    s32 dptc_dvfs_addr;
    s32 utra_addr;
    s32 ram_code_start_addr;
    s32 mcu_2_ssish_addr;
    s32 ssish_2_mcu_addr;
    s32 hdmi_dma_addr;
    s32 zcanfd_2_mcu_addr;
    s32 zqspi_2_mcu_addr;
    s32 mcu_2_ecspi_addr;
    s32 mcu_2_zqspi_addr;
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct sdma_script_start_addrs {
    s32 ap_2_ap_addr;
    s32 ap_2_bp_addr;
    s32 ap_2_ap_fixed_addr;
    s32 bp_2_ap_addr;
    s32 loopback_on_dsp_side_addr;
    s32 mcu_interrupt_only_addr;
    s32 firi_2_per_addr;
    s32 firi_2_mcu_addr;
    s32 per_2_firi_addr;
    s32 mcu_2_firi_addr;
    s32 uart_2_per_addr;
    s32 uart_2_mcu_addr;
    s32 per_2_app_addr;
    s32 mcu_2_app_addr;
    s32 per_2_per_addr;
    s32 uartsh_2_per_addr;
    s32 uartsh_2_mcu_addr;
    s32 per_2_shp_addr;
    s32 mcu_2_shp_addr;
    s32 ata_2_mcu_addr;
    s32 mcu_2_ata_addr;
    s32 app_2_per_addr;
    s32 app_2_mcu_addr;
    s32 shp_2_per_addr;
    s32 shp_2_mcu_addr;
    s32 mshc_2_mcu_addr;
    s32 mcu_2_mshc_addr;
    s32 spdif_2_mcu_addr;
    s32 mcu_2_spdif_addr;
    s32 asrc_2_mcu_addr;
    s32 ext_mem_2_ipu_addr;
    s32 descrambler_addr;
    s32 dptc_dvfs_addr;
    s32 utra_addr;
    s32 ram_code_start_addr;
    s32 mcu_2_ssish_addr;
    s32 ssish_2_mcu_addr;
    s32 hdmi_dma_addr;
    s32 zcanfd_2_mcu_addr;
    s32 zqspi_2_mcu_addr;
    s32 mcu_2_ecspi_addr;
    s32 mcu_2_zqspi_addr;
}
```
</details>
</li>
</ul>
