# Struct: <code>dwc2_core_params</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dwc2_core_params {
    int otg_cap;
    int otg_ver;
    int dma_enable;
    int dma_desc_enable;
    int speed;
    int enable_dynamic_fifo;
    int en_multiple_tx_fifo;
    int host_rx_fifo_size;
    int host_nperio_tx_fifo_size;
    int host_perio_tx_fifo_size;
    int max_transfer_size;
    int max_packet_count;
    int host_channels;
    int phy_type;
    int phy_utmi_width;
    int phy_ulpi_ddr;
    int phy_ulpi_ext_vbus;
    int i2c_enable;
    int ulpi_fs_ls;
    int host_support_fs_ls_low_power;
    int host_ls_low_power_phy_clk;
    int ts_dline;
    int reload_ctl;
    int ahbcfg;
    int uframe_sched;
    int external_id_pin_ctl;
    int hibernation;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dwc2_core_params {
    int otg_cap;
    int otg_ver;
    int dma_enable;
    int dma_desc_enable;
    int dma_desc_fs_enable;
    int speed;
    int enable_dynamic_fifo;
    int en_multiple_tx_fifo;
    int host_rx_fifo_size;
    int host_nperio_tx_fifo_size;
    int host_perio_tx_fifo_size;
    int max_transfer_size;
    int max_packet_count;
    int host_channels;
    int phy_type;
    int phy_utmi_width;
    int phy_ulpi_ddr;
    int phy_ulpi_ext_vbus;
    int i2c_enable;
    int ulpi_fs_ls;
    int host_support_fs_ls_low_power;
    int host_ls_low_power_phy_clk;
    int ts_dline;
    int reload_ctl;
    int ahbcfg;
    int uframe_sched;
    int external_id_pin_ctl;
    int hibernation;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dwc2_core_params {
    int otg_cap;
    int otg_ver;
    int dma_desc_enable;
    int dma_desc_fs_enable;
    int speed;
    int enable_dynamic_fifo;
    int en_multiple_tx_fifo;
    int host_rx_fifo_size;
    int host_nperio_tx_fifo_size;
    int host_perio_tx_fifo_size;
    int max_transfer_size;
    int max_packet_count;
    int host_channels;
    int phy_type;
    int phy_utmi_width;
    int phy_ulpi_ddr;
    int phy_ulpi_ext_vbus;
    int i2c_enable;
    int ulpi_fs_ls;
    int host_support_fs_ls_low_power;
    int host_ls_low_power_phy_clk;
    int ts_dline;
    int reload_ctl;
    int ahbcfg;
    int uframe_sched;
    int external_id_pin_ctl;
    int hibernation;
    bool host_dma;
    bool g_dma;
    bool g_dma_desc;
    u32 g_rx_fifo_size;
    u32 g_np_tx_fifo_size;
    u32[16] g_tx_fifo_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dwc2_core_params {
    u8 otg_cap;
    u8 phy_type;
    u8 speed;
    u8 phy_utmi_width;
    bool phy_ulpi_ddr;
    bool phy_ulpi_ext_vbus;
    bool enable_dynamic_fifo;
    bool en_multiple_tx_fifo;
    bool i2c_enable;
    bool ulpi_fs_ls;
    bool ts_dline;
    bool reload_ctl;
    bool uframe_sched;
    bool external_id_pin_ctl;
    bool hibernation;
    bool activate_stm_fs_transceiver;
    u16 max_packet_count;
    u32 max_transfer_size;
    u32 ahbcfg;
    bool host_dma;
    bool dma_desc_enable;
    bool dma_desc_fs_enable;
    bool host_support_fs_ls_low_power;
    bool host_ls_low_power_phy_clk;
    u8 host_channels;
    u16 host_rx_fifo_size;
    u16 host_nperio_tx_fifo_size;
    u16 host_perio_tx_fifo_size;
    bool g_dma;
    bool g_dma_desc;
    u32 g_rx_fifo_size;
    u32 g_np_tx_fifo_size;
    u32[16] g_tx_fifo_size;
    bool change_speed_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dwc2_core_params {
    u8 otg_cap;
    u8 phy_type;
    u8 speed;
    u8 phy_utmi_width;
    bool phy_ulpi_ddr;
    bool phy_ulpi_ext_vbus;
    bool enable_dynamic_fifo;
    bool en_multiple_tx_fifo;
    bool i2c_enable;
    bool ulpi_fs_ls;
    bool ts_dline;
    bool reload_ctl;
    bool uframe_sched;
    bool external_id_pin_ctl;
    bool hibernation;
    bool activate_stm_fs_transceiver;
    u16 max_packet_count;
    u32 max_transfer_size;
    u32 ahbcfg;
    bool host_dma;
    bool dma_desc_enable;
    bool dma_desc_fs_enable;
    bool host_support_fs_ls_low_power;
    bool host_ls_low_power_phy_clk;
    bool oc_disable;
    u8 host_channels;
    u16 host_rx_fifo_size;
    u16 host_nperio_tx_fifo_size;
    u16 host_perio_tx_fifo_size;
    bool g_dma;
    bool g_dma_desc;
    u32 g_rx_fifo_size;
    u32 g_np_tx_fifo_size;
    u32[16] g_tx_fifo_size;
    bool change_speed_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dwc2_core_params {
    u8 otg_cap;
    u8 phy_type;
    u8 speed;
    u8 phy_utmi_width;
    bool phy_ulpi_ddr;
    bool phy_ulpi_ext_vbus;
    bool enable_dynamic_fifo;
    bool en_multiple_tx_fifo;
    bool i2c_enable;
    bool acg_enable;
    bool ulpi_fs_ls;
    bool ts_dline;
    bool reload_ctl;
    bool uframe_sched;
    bool external_id_pin_ctl;
    int power_down;
    bool lpm;
    bool lpm_clock_gating;
    bool besl;
    bool hird_threshold_en;
    u8 hird_threshold;
    bool activate_stm_fs_transceiver;
    bool ipg_isoc_en;
    u16 max_packet_count;
    u32 max_transfer_size;
    u32 ahbcfg;
    bool host_dma;
    bool dma_desc_enable;
    bool dma_desc_fs_enable;
    bool host_support_fs_ls_low_power;
    bool host_ls_low_power_phy_clk;
    bool oc_disable;
    u8 host_channels;
    u16 host_rx_fifo_size;
    u16 host_nperio_tx_fifo_size;
    u16 host_perio_tx_fifo_size;
    bool g_dma;
    bool g_dma_desc;
    u32 g_rx_fifo_size;
    u32 g_np_tx_fifo_size;
    u32[16] g_tx_fifo_size;
    bool change_speed_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dwc2_core_params {
    u8 otg_cap;
    u8 phy_type;
    u8 speed;
    u8 phy_utmi_width;
    bool phy_ulpi_ddr;
    bool phy_ulpi_ext_vbus;
    bool enable_dynamic_fifo;
    bool en_multiple_tx_fifo;
    bool i2c_enable;
    bool acg_enable;
    bool ulpi_fs_ls;
    bool ts_dline;
    bool reload_ctl;
    bool uframe_sched;
    bool external_id_pin_ctl;
    int power_down;
    bool lpm;
    bool lpm_clock_gating;
    bool besl;
    bool hird_threshold_en;
    bool service_interval;
    u8 hird_threshold;
    bool activate_stm_fs_transceiver;
    bool ipg_isoc_en;
    u16 max_packet_count;
    u32 max_transfer_size;
    u32 ahbcfg;
    u32 ref_clk_per;
    u16 sof_cnt_wkup_alert;
    bool host_dma;
    bool dma_desc_enable;
    bool dma_desc_fs_enable;
    bool host_support_fs_ls_low_power;
    bool host_ls_low_power_phy_clk;
    bool oc_disable;
    u8 host_channels;
    u16 host_rx_fifo_size;
    u16 host_nperio_tx_fifo_size;
    u16 host_perio_tx_fifo_size;
    bool g_dma;
    bool g_dma_desc;
    u32 g_rx_fifo_size;
    u32 g_np_tx_fifo_size;
    u32[16] g_tx_fifo_size;
    bool change_speed_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dwc2_core_params {
    u8 otg_cap;
    u8 phy_type;
    u8 speed;
    u8 phy_utmi_width;
    bool phy_ulpi_ddr;
    bool phy_ulpi_ext_vbus;
    bool enable_dynamic_fifo;
    bool en_multiple_tx_fifo;
    bool i2c_enable;
    bool acg_enable;
    bool ulpi_fs_ls;
    bool ts_dline;
    bool reload_ctl;
    bool uframe_sched;
    bool external_id_pin_ctl;
    int power_down;
    bool lpm;
    bool lpm_clock_gating;
    bool besl;
    bool hird_threshold_en;
    bool service_interval;
    u8 hird_threshold;
    bool activate_stm_fs_transceiver;
    bool ipg_isoc_en;
    u16 max_packet_count;
    u32 max_transfer_size;
    u32 ahbcfg;
    u32 ref_clk_per;
    u16 sof_cnt_wkup_alert;
    bool host_dma;
    bool dma_desc_enable;
    bool dma_desc_fs_enable;
    bool host_support_fs_ls_low_power;
    bool host_ls_low_power_phy_clk;
    bool oc_disable;
    u8 host_channels;
    u16 host_rx_fifo_size;
    u16 host_nperio_tx_fifo_size;
    u16 host_perio_tx_fifo_size;
    bool g_dma;
    bool g_dma_desc;
    u32 g_rx_fifo_size;
    u32 g_np_tx_fifo_size;
    u32[16] g_tx_fifo_size;
    bool change_speed_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dwc2_core_params {
    u8 otg_cap;
    u8 phy_type;
    u8 speed;
    u8 phy_utmi_width;
    bool phy_ulpi_ddr;
    bool phy_ulpi_ext_vbus;
    bool enable_dynamic_fifo;
    bool en_multiple_tx_fifo;
    bool i2c_enable;
    bool acg_enable;
    bool ulpi_fs_ls;
    bool ts_dline;
    bool reload_ctl;
    bool uframe_sched;
    bool external_id_pin_ctl;
    int power_down;
    bool lpm;
    bool lpm_clock_gating;
    bool besl;
    bool hird_threshold_en;
    bool service_interval;
    u8 hird_threshold;
    bool activate_stm_fs_transceiver;
    bool ipg_isoc_en;
    u16 max_packet_count;
    u32 max_transfer_size;
    u32 ahbcfg;
    u32 ref_clk_per;
    u16 sof_cnt_wkup_alert;
    bool host_dma;
    bool dma_desc_enable;
    bool dma_desc_fs_enable;
    bool host_support_fs_ls_low_power;
    bool host_ls_low_power_phy_clk;
    bool oc_disable;
    u8 host_channels;
    u16 host_rx_fifo_size;
    u16 host_nperio_tx_fifo_size;
    u16 host_perio_tx_fifo_size;
    bool g_dma;
    bool g_dma_desc;
    u32 g_rx_fifo_size;
    u32 g_np_tx_fifo_size;
    u32[16] g_tx_fifo_size;
    bool change_speed_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dwc2_core_params {
    u8 otg_cap;
    u8 phy_type;
    u8 speed;
    u8 phy_utmi_width;
    bool phy_ulpi_ddr;
    bool phy_ulpi_ext_vbus;
    bool enable_dynamic_fifo;
    bool en_multiple_tx_fifo;
    bool i2c_enable;
    bool acg_enable;
    bool ulpi_fs_ls;
    bool ts_dline;
    bool reload_ctl;
    bool uframe_sched;
    bool external_id_pin_ctl;
    int power_down;
    bool lpm;
    bool lpm_clock_gating;
    bool besl;
    bool hird_threshold_en;
    bool service_interval;
    u8 hird_threshold;
    bool activate_stm_fs_transceiver;
    bool activate_stm_id_vb_detection;
    bool ipg_isoc_en;
    u16 max_packet_count;
    u32 max_transfer_size;
    u32 ahbcfg;
    u32 ref_clk_per;
    u16 sof_cnt_wkup_alert;
    bool host_dma;
    bool dma_desc_enable;
    bool dma_desc_fs_enable;
    bool host_support_fs_ls_low_power;
    bool host_ls_low_power_phy_clk;
    bool oc_disable;
    u8 host_channels;
    u16 host_rx_fifo_size;
    u16 host_nperio_tx_fifo_size;
    u16 host_perio_tx_fifo_size;
    bool g_dma;
    bool g_dma_desc;
    u32 g_rx_fifo_size;
    u32 g_np_tx_fifo_size;
    u32[16] g_tx_fifo_size;
    bool change_speed_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dwc2_core_params {
    u8 otg_cap;
    u8 phy_type;
    u8 speed;
    u8 phy_utmi_width;
    bool phy_ulpi_ddr;
    bool phy_ulpi_ext_vbus;
    bool enable_dynamic_fifo;
    bool en_multiple_tx_fifo;
    bool i2c_enable;
    bool acg_enable;
    bool ulpi_fs_ls;
    bool ts_dline;
    bool reload_ctl;
    bool uframe_sched;
    bool external_id_pin_ctl;
    int power_down;
    bool lpm;
    bool lpm_clock_gating;
    bool besl;
    bool hird_threshold_en;
    bool service_interval;
    u8 hird_threshold;
    bool activate_stm_fs_transceiver;
    bool activate_stm_id_vb_detection;
    bool ipg_isoc_en;
    u16 max_packet_count;
    u32 max_transfer_size;
    u32 ahbcfg;
    u32 ref_clk_per;
    u16 sof_cnt_wkup_alert;
    bool host_dma;
    bool dma_desc_enable;
    bool dma_desc_fs_enable;
    bool host_support_fs_ls_low_power;
    bool host_ls_low_power_phy_clk;
    bool oc_disable;
    u8 host_channels;
    u16 host_rx_fifo_size;
    u16 host_nperio_tx_fifo_size;
    u16 host_perio_tx_fifo_size;
    bool g_dma;
    bool g_dma_desc;
    u32 g_rx_fifo_size;
    u32 g_np_tx_fifo_size;
    u32[16] g_tx_fifo_size;
    bool change_speed_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dwc2_core_params {
    u8 otg_cap;
    u8 phy_type;
    u8 speed;
    u8 phy_utmi_width;
    bool phy_ulpi_ddr;
    bool phy_ulpi_ext_vbus;
    bool enable_dynamic_fifo;
    bool en_multiple_tx_fifo;
    bool i2c_enable;
    bool acg_enable;
    bool ulpi_fs_ls;
    bool ts_dline;
    bool reload_ctl;
    bool uframe_sched;
    bool external_id_pin_ctl;
    int power_down;
    bool no_clock_gating;
    bool lpm;
    bool lpm_clock_gating;
    bool besl;
    bool hird_threshold_en;
    bool service_interval;
    u8 hird_threshold;
    bool activate_stm_fs_transceiver;
    bool activate_stm_id_vb_detection;
    bool ipg_isoc_en;
    u16 max_packet_count;
    u32 max_transfer_size;
    u32 ahbcfg;
    u32 ref_clk_per;
    u16 sof_cnt_wkup_alert;
    bool host_dma;
    bool dma_desc_enable;
    bool dma_desc_fs_enable;
    bool host_support_fs_ls_low_power;
    bool host_ls_low_power_phy_clk;
    bool oc_disable;
    u8 host_channels;
    u16 host_rx_fifo_size;
    u16 host_nperio_tx_fifo_size;
    u16 host_perio_tx_fifo_size;
    bool g_dma;
    bool g_dma_desc;
    u32 g_rx_fifo_size;
    u32 g_np_tx_fifo_size;
    u32[16] g_tx_fifo_size;
    bool change_speed_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dwc2_core_params {
    u8 otg_cap;
    u8 phy_type;
    u8 speed;
    u8 phy_utmi_width;
    bool phy_ulpi_ddr;
    bool phy_ulpi_ext_vbus;
    bool enable_dynamic_fifo;
    bool en_multiple_tx_fifo;
    bool i2c_enable;
    bool acg_enable;
    bool ulpi_fs_ls;
    bool ts_dline;
    bool reload_ctl;
    bool uframe_sched;
    bool external_id_pin_ctl;
    int power_down;
    bool no_clock_gating;
    bool lpm;
    bool lpm_clock_gating;
    bool besl;
    bool hird_threshold_en;
    bool service_interval;
    u8 hird_threshold;
    bool activate_stm_fs_transceiver;
    bool activate_stm_id_vb_detection;
    bool ipg_isoc_en;
    u16 max_packet_count;
    u32 max_transfer_size;
    u32 ahbcfg;
    u32 ref_clk_per;
    u16 sof_cnt_wkup_alert;
    bool host_dma;
    bool dma_desc_enable;
    bool dma_desc_fs_enable;
    bool host_support_fs_ls_low_power;
    bool host_ls_low_power_phy_clk;
    bool oc_disable;
    u8 host_channels;
    u16 host_rx_fifo_size;
    u16 host_nperio_tx_fifo_size;
    u16 host_perio_tx_fifo_size;
    bool g_dma;
    bool g_dma_desc;
    u32 g_rx_fifo_size;
    u32 g_np_tx_fifo_size;
    u32[16] g_tx_fifo_size;
    bool change_speed_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dwc2_core_params {
    struct usb_otg_caps otg_caps;
    u8 phy_type;
    u8 speed;
    u8 phy_utmi_width;
    bool phy_ulpi_ddr;
    bool phy_ulpi_ext_vbus;
    bool enable_dynamic_fifo;
    bool en_multiple_tx_fifo;
    bool i2c_enable;
    bool acg_enable;
    bool ulpi_fs_ls;
    bool ts_dline;
    bool reload_ctl;
    bool uframe_sched;
    bool external_id_pin_ctl;
    int power_down;
    bool no_clock_gating;
    bool lpm;
    bool lpm_clock_gating;
    bool besl;
    bool hird_threshold_en;
    bool service_interval;
    u8 hird_threshold;
    bool activate_stm_fs_transceiver;
    bool activate_stm_id_vb_detection;
    bool activate_ingenic_overcurrent_detection;
    bool ipg_isoc_en;
    u16 max_packet_count;
    u32 max_transfer_size;
    u32 ahbcfg;
    u32 ref_clk_per;
    u16 sof_cnt_wkup_alert;
    bool host_dma;
    bool dma_desc_enable;
    bool dma_desc_fs_enable;
    bool host_support_fs_ls_low_power;
    bool host_ls_low_power_phy_clk;
    bool oc_disable;
    u8 host_channels;
    u16 host_rx_fifo_size;
    u16 host_nperio_tx_fifo_size;
    u16 host_perio_tx_fifo_size;
    bool g_dma;
    bool g_dma_desc;
    u32 g_rx_fifo_size;
    u32 g_np_tx_fifo_size;
    u32[16] g_tx_fifo_size;
    bool change_speed_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dwc2_core_params {
    struct usb_otg_caps otg_caps;
    u8 phy_type;
    u8 speed;
    u8 phy_utmi_width;
    bool phy_ulpi_ddr;
    bool phy_ulpi_ext_vbus;
    bool enable_dynamic_fifo;
    bool en_multiple_tx_fifo;
    bool i2c_enable;
    bool acg_enable;
    bool ulpi_fs_ls;
    bool ts_dline;
    bool reload_ctl;
    bool uframe_sched;
    bool external_id_pin_ctl;
    int power_down;
    bool no_clock_gating;
    bool lpm;
    bool lpm_clock_gating;
    bool besl;
    bool hird_threshold_en;
    bool service_interval;
    u8 hird_threshold;
    bool activate_stm_fs_transceiver;
    bool activate_stm_id_vb_detection;
    bool activate_ingenic_overcurrent_detection;
    bool ipg_isoc_en;
    u16 max_packet_count;
    u32 max_transfer_size;
    u32 ahbcfg;
    u32 ref_clk_per;
    u16 sof_cnt_wkup_alert;
    bool host_dma;
    bool dma_desc_enable;
    bool dma_desc_fs_enable;
    bool host_support_fs_ls_low_power;
    bool host_ls_low_power_phy_clk;
    bool oc_disable;
    u8 host_channels;
    u16 host_rx_fifo_size;
    u16 host_nperio_tx_fifo_size;
    u16 host_perio_tx_fifo_size;
    bool g_dma;
    bool g_dma_desc;
    u32 g_rx_fifo_size;
    u32 g_np_tx_fifo_size;
    u32[16] g_tx_fifo_size;
    bool change_speed_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dwc2_core_params {
    struct usb_otg_caps otg_caps;
    u8 phy_type;
    u8 speed;
    u8 phy_utmi_width;
    bool phy_ulpi_ddr;
    bool phy_ulpi_ext_vbus;
    bool enable_dynamic_fifo;
    bool en_multiple_tx_fifo;
    bool i2c_enable;
    bool acg_enable;
    bool ulpi_fs_ls;
    bool ts_dline;
    bool reload_ctl;
    bool uframe_sched;
    bool external_id_pin_ctl;
    int power_down;
    bool no_clock_gating;
    bool lpm;
    bool lpm_clock_gating;
    bool besl;
    bool hird_threshold_en;
    bool service_interval;
    u8 hird_threshold;
    bool activate_stm_fs_transceiver;
    bool activate_stm_id_vb_detection;
    bool activate_ingenic_overcurrent_detection;
    bool ipg_isoc_en;
    u16 max_packet_count;
    u32 max_transfer_size;
    u32 ahbcfg;
    u32 ref_clk_per;
    u16 sof_cnt_wkup_alert;
    bool host_dma;
    bool dma_desc_enable;
    bool dma_desc_fs_enable;
    bool host_support_fs_ls_low_power;
    bool host_ls_low_power_phy_clk;
    bool oc_disable;
    u8 host_channels;
    u16 host_rx_fifo_size;
    u16 host_nperio_tx_fifo_size;
    u16 host_perio_tx_fifo_size;
    bool g_dma;
    bool g_dma_desc;
    u32 g_rx_fifo_size;
    u32 g_np_tx_fifo_size;
    u32[16] g_tx_fifo_size;
    bool change_speed_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dwc2_core_params {
    struct usb_otg_caps otg_caps;
    u8 phy_type;
    u8 speed;
    u8 phy_utmi_width;
    bool phy_ulpi_ddr;
    bool phy_ulpi_ext_vbus;
    bool enable_dynamic_fifo;
    bool en_multiple_tx_fifo;
    bool i2c_enable;
    bool acg_enable;
    bool ulpi_fs_ls;
    bool ts_dline;
    bool reload_ctl;
    bool uframe_sched;
    bool external_id_pin_ctl;
    int power_down;
    bool no_clock_gating;
    bool lpm;
    bool lpm_clock_gating;
    bool besl;
    bool hird_threshold_en;
    bool service_interval;
    u8 hird_threshold;
    bool activate_stm_fs_transceiver;
    bool activate_stm_id_vb_detection;
    bool activate_ingenic_overcurrent_detection;
    bool ipg_isoc_en;
    u16 max_packet_count;
    u32 max_transfer_size;
    u32 ahbcfg;
    u32 ref_clk_per;
    u16 sof_cnt_wkup_alert;
    bool host_dma;
    bool dma_desc_enable;
    bool dma_desc_fs_enable;
    bool host_support_fs_ls_low_power;
    bool host_ls_low_power_phy_clk;
    bool oc_disable;
    u8 host_channels;
    u16 host_rx_fifo_size;
    u16 host_nperio_tx_fifo_size;
    u16 host_perio_tx_fifo_size;
    bool g_dma;
    bool g_dma_desc;
    u32 g_rx_fifo_size;
    u32 g_np_tx_fifo_size;
    u32[16] g_tx_fifo_size;
    bool change_speed_quirk;
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
struct dwc2_core_params {
    u8 otg_cap;
    u8 phy_type;
    u8 speed;
    u8 phy_utmi_width;
    bool phy_ulpi_ddr;
    bool phy_ulpi_ext_vbus;
    bool enable_dynamic_fifo;
    bool en_multiple_tx_fifo;
    bool i2c_enable;
    bool acg_enable;
    bool ulpi_fs_ls;
    bool ts_dline;
    bool reload_ctl;
    bool uframe_sched;
    bool external_id_pin_ctl;
    int power_down;
    bool lpm;
    bool lpm_clock_gating;
    bool besl;
    bool hird_threshold_en;
    bool service_interval;
    u8 hird_threshold;
    bool activate_stm_fs_transceiver;
    bool ipg_isoc_en;
    u16 max_packet_count;
    u32 max_transfer_size;
    u32 ahbcfg;
    u32 ref_clk_per;
    u16 sof_cnt_wkup_alert;
    bool host_dma;
    bool dma_desc_enable;
    bool dma_desc_fs_enable;
    bool host_support_fs_ls_low_power;
    bool host_ls_low_power_phy_clk;
    bool oc_disable;
    u8 host_channels;
    u16 host_rx_fifo_size;
    u16 host_nperio_tx_fifo_size;
    u16 host_perio_tx_fifo_size;
    bool g_dma;
    bool g_dma_desc;
    u32 g_rx_fifo_size;
    u32 g_np_tx_fifo_size;
    u32[16] g_tx_fifo_size;
    bool change_speed_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dwc2_core_params {
    u8 otg_cap;
    u8 phy_type;
    u8 speed;
    u8 phy_utmi_width;
    bool phy_ulpi_ddr;
    bool phy_ulpi_ext_vbus;
    bool enable_dynamic_fifo;
    bool en_multiple_tx_fifo;
    bool i2c_enable;
    bool acg_enable;
    bool ulpi_fs_ls;
    bool ts_dline;
    bool reload_ctl;
    bool uframe_sched;
    bool external_id_pin_ctl;
    int power_down;
    bool lpm;
    bool lpm_clock_gating;
    bool besl;
    bool hird_threshold_en;
    bool service_interval;
    u8 hird_threshold;
    bool activate_stm_fs_transceiver;
    bool ipg_isoc_en;
    u16 max_packet_count;
    u32 max_transfer_size;
    u32 ahbcfg;
    u32 ref_clk_per;
    u16 sof_cnt_wkup_alert;
    bool host_dma;
    bool dma_desc_enable;
    bool dma_desc_fs_enable;
    bool host_support_fs_ls_low_power;
    bool host_ls_low_power_phy_clk;
    bool oc_disable;
    u8 host_channels;
    u16 host_rx_fifo_size;
    u16 host_nperio_tx_fifo_size;
    u16 host_perio_tx_fifo_size;
    bool g_dma;
    bool g_dma_desc;
    u32 g_rx_fifo_size;
    u32 g_np_tx_fifo_size;
    u32[16] g_tx_fifo_size;
    bool change_speed_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dwc2_core_params {
    u8 otg_cap;
    u8 phy_type;
    u8 speed;
    u8 phy_utmi_width;
    bool phy_ulpi_ddr;
    bool phy_ulpi_ext_vbus;
    bool enable_dynamic_fifo;
    bool en_multiple_tx_fifo;
    bool i2c_enable;
    bool acg_enable;
    bool ulpi_fs_ls;
    bool ts_dline;
    bool reload_ctl;
    bool uframe_sched;
    bool external_id_pin_ctl;
    int power_down;
    bool lpm;
    bool lpm_clock_gating;
    bool besl;
    bool hird_threshold_en;
    bool service_interval;
    u8 hird_threshold;
    bool activate_stm_fs_transceiver;
    bool ipg_isoc_en;
    u16 max_packet_count;
    u32 max_transfer_size;
    u32 ahbcfg;
    u32 ref_clk_per;
    u16 sof_cnt_wkup_alert;
    bool host_dma;
    bool dma_desc_enable;
    bool dma_desc_fs_enable;
    bool host_support_fs_ls_low_power;
    bool host_ls_low_power_phy_clk;
    bool oc_disable;
    u8 host_channels;
    u16 host_rx_fifo_size;
    u16 host_nperio_tx_fifo_size;
    u16 host_perio_tx_fifo_size;
    bool g_dma;
    bool g_dma_desc;
    u32 g_rx_fifo_size;
    u32 g_np_tx_fifo_size;
    u32[16] g_tx_fifo_size;
    bool change_speed_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dwc2_core_params {
    u8 otg_cap;
    u8 phy_type;
    u8 speed;
    u8 phy_utmi_width;
    bool phy_ulpi_ddr;
    bool phy_ulpi_ext_vbus;
    bool enable_dynamic_fifo;
    bool en_multiple_tx_fifo;
    bool i2c_enable;
    bool acg_enable;
    bool ulpi_fs_ls;
    bool ts_dline;
    bool reload_ctl;
    bool uframe_sched;
    bool external_id_pin_ctl;
    int power_down;
    bool lpm;
    bool lpm_clock_gating;
    bool besl;
    bool hird_threshold_en;
    bool service_interval;
    u8 hird_threshold;
    bool activate_stm_fs_transceiver;
    bool ipg_isoc_en;
    u16 max_packet_count;
    u32 max_transfer_size;
    u32 ahbcfg;
    u32 ref_clk_per;
    u16 sof_cnt_wkup_alert;
    bool host_dma;
    bool dma_desc_enable;
    bool dma_desc_fs_enable;
    bool host_support_fs_ls_low_power;
    bool host_ls_low_power_phy_clk;
    bool oc_disable;
    u8 host_channels;
    u16 host_rx_fifo_size;
    u16 host_nperio_tx_fifo_size;
    u16 host_perio_tx_fifo_size;
    bool g_dma;
    bool g_dma_desc;
    u32 g_rx_fifo_size;
    u32 g_np_tx_fifo_size;
    u32[16] g_tx_fifo_size;
    bool change_speed_quirk;
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
struct dwc2_core_params {
    u8 otg_cap;
    u8 phy_type;
    u8 speed;
    u8 phy_utmi_width;
    bool phy_ulpi_ddr;
    bool phy_ulpi_ext_vbus;
    bool enable_dynamic_fifo;
    bool en_multiple_tx_fifo;
    bool i2c_enable;
    bool acg_enable;
    bool ulpi_fs_ls;
    bool ts_dline;
    bool reload_ctl;
    bool uframe_sched;
    bool external_id_pin_ctl;
    int power_down;
    bool lpm;
    bool lpm_clock_gating;
    bool besl;
    bool hird_threshold_en;
    bool service_interval;
    u8 hird_threshold;
    bool activate_stm_fs_transceiver;
    bool ipg_isoc_en;
    u16 max_packet_count;
    u32 max_transfer_size;
    u32 ahbcfg;
    u32 ref_clk_per;
    u16 sof_cnt_wkup_alert;
    bool host_dma;
    bool dma_desc_enable;
    bool dma_desc_fs_enable;
    bool host_support_fs_ls_low_power;
    bool host_ls_low_power_phy_clk;
    bool oc_disable;
    u8 host_channels;
    u16 host_rx_fifo_size;
    u16 host_nperio_tx_fifo_size;
    u16 host_perio_tx_fifo_size;
    bool g_dma;
    bool g_dma_desc;
    u32 g_rx_fifo_size;
    u32 g_np_tx_fifo_size;
    u32[16] g_tx_fifo_size;
    bool change_speed_quirk;
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dwc2_core_params {
    u8 otg_cap;
    u8 phy_type;
    u8 speed;
    u8 phy_utmi_width;
    bool phy_ulpi_ddr;
    bool phy_ulpi_ext_vbus;
    bool enable_dynamic_fifo;
    bool en_multiple_tx_fifo;
    bool i2c_enable;
    bool acg_enable;
    bool ulpi_fs_ls;
    bool ts_dline;
    bool reload_ctl;
    bool uframe_sched;
    bool external_id_pin_ctl;
    int power_down;
    bool lpm;
    bool lpm_clock_gating;
    bool besl;
    bool hird_threshold_en;
    bool service_interval;
    u8 hird_threshold;
    bool activate_stm_fs_transceiver;
    bool ipg_isoc_en;
    u16 max_packet_count;
    u32 max_transfer_size;
    u32 ahbcfg;
    u32 ref_clk_per;
    u16 sof_cnt_wkup_alert;
    bool host_dma;
    bool dma_desc_enable;
    bool dma_desc_fs_enable;
    bool host_support_fs_ls_low_power;
    bool host_ls_low_power_phy_clk;
    bool oc_disable;
    u8 host_channels;
    u16 host_rx_fifo_size;
    u16 host_nperio_tx_fifo_size;
    u16 host_perio_tx_fifo_size;
    bool g_dma;
    bool g_dma_desc;
    u32 g_rx_fifo_size;
    u32 g_np_tx_fifo_size;
    u32[16] g_tx_fifo_size;
    bool change_speed_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dwc2_core_params {
    u8 otg_cap;
    u8 phy_type;
    u8 speed;
    u8 phy_utmi_width;
    bool phy_ulpi_ddr;
    bool phy_ulpi_ext_vbus;
    bool enable_dynamic_fifo;
    bool en_multiple_tx_fifo;
    bool i2c_enable;
    bool acg_enable;
    bool ulpi_fs_ls;
    bool ts_dline;
    bool reload_ctl;
    bool uframe_sched;
    bool external_id_pin_ctl;
    int power_down;
    bool lpm;
    bool lpm_clock_gating;
    bool besl;
    bool hird_threshold_en;
    bool service_interval;
    u8 hird_threshold;
    bool activate_stm_fs_transceiver;
    bool ipg_isoc_en;
    u16 max_packet_count;
    u32 max_transfer_size;
    u32 ahbcfg;
    u32 ref_clk_per;
    u16 sof_cnt_wkup_alert;
    bool host_dma;
    bool dma_desc_enable;
    bool dma_desc_fs_enable;
    bool host_support_fs_ls_low_power;
    bool host_ls_low_power_phy_clk;
    bool oc_disable;
    u8 host_channels;
    u16 host_rx_fifo_size;
    u16 host_nperio_tx_fifo_size;
    u16 host_perio_tx_fifo_size;
    bool g_dma;
    bool g_dma_desc;
    u32 g_rx_fifo_size;
    u32 g_np_tx_fifo_size;
    u32[16] g_tx_fifo_size;
    bool change_speed_quirk;
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
<code>int dma_desc_fs_enable</code>
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
<code>bool host_dma</code>
</li>
<li>
<b>Field added. </b>
<code>bool g_dma</code>
</li>
<li>
<b>Field added. </b>
<code>bool g_dma_desc</code>
</li>
<li>
<b>Field added. </b>
<code>u32 g_rx_fifo_size</code>
</li>
<li>
<b>Field added. </b>
<code>u32 g_np_tx_fifo_size</code>
</li>
<li>
<b>Field added. </b>
<code>u32[16] g_tx_fifo_size</code>
</li>
<li>
<b>Field removed. </b>
<code>int dma_enable</code>
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
<code>bool activate_stm_fs_transceiver</code>
</li>
<li>
<b>Field added. </b>
<code>bool change_speed_quirk</code>
</li>
<li>
<b>Field removed. </b>
<code>int otg_ver</code>
</li>
<li>
<b>Field type changed. </b>
<code>int otg_cap</code> ➡️ <code>u8 otg_cap</code>
</li>
<li>
<b>Field type changed. </b>
<code>int dma_desc_enable</code> ➡️ <code>bool dma_desc_enable</code>
</li>
<li>
<b>Field type changed. </b>
<code>int dma_desc_fs_enable</code> ➡️ <code>bool dma_desc_fs_enable</code>
</li>
<li>
<b>Field type changed. </b>
<code>int speed</code> ➡️ <code>u8 speed</code>
</li>
<li>
<b>Field type changed. </b>
<code>int enable_dynamic_fifo</code> ➡️ <code>bool enable_dynamic_fifo</code>
</li>
<li>
<b>Field type changed. </b>
<code>int en_multiple_tx_fifo</code> ➡️ <code>bool en_multiple_tx_fifo</code>
</li>
<li>
<b>Field type changed. </b>
<code>int host_rx_fifo_size</code> ➡️ <code>u16 host_rx_fifo_size</code>
</li>
<li>
<b>Field type changed. </b>
<code>int host_nperio_tx_fifo_size</code> ➡️ <code>u16 host_nperio_tx_fifo_size</code>
</li>
<li>
<b>Field type changed. </b>
<code>int host_perio_tx_fifo_size</code> ➡️ <code>u16 host_perio_tx_fifo_size</code>
</li>
<li>
<b>Field type changed. </b>
<code>int max_transfer_size</code> ➡️ <code>u32 max_transfer_size</code>
</li>
<li>
<b>Field type changed. </b>
<code>int max_packet_count</code> ➡️ <code>u16 max_packet_count</code>
</li>
<li>
<b>Field type changed. </b>
<code>int host_channels</code> ➡️ <code>u8 host_channels</code>
</li>
<li>
<b>Field type changed. </b>
<code>int phy_type</code> ➡️ <code>u8 phy_type</code>
</li>
<li>
<b>Field type changed. </b>
<code>int phy_utmi_width</code> ➡️ <code>u8 phy_utmi_width</code>
</li>
<li>
<b>Field type changed. </b>
<code>int phy_ulpi_ddr</code> ➡️ <code>bool phy_ulpi_ddr</code>
</li>
<li>
<b>Field type changed. </b>
<code>int phy_ulpi_ext_vbus</code> ➡️ <code>bool phy_ulpi_ext_vbus</code>
</li>
<li>
<b>Field type changed. </b>
<code>int i2c_enable</code> ➡️ <code>bool i2c_enable</code>
</li>
<li>
<b>Field type changed. </b>
<code>int ulpi_fs_ls</code> ➡️ <code>bool ulpi_fs_ls</code>
</li>
<li>
<b>Field type changed. </b>
<code>int host_support_fs_ls_low_power</code> ➡️ <code>bool host_support_fs_ls_low_power</code>
</li>
<li>
<b>Field type changed. </b>
<code>int host_ls_low_power_phy_clk</code> ➡️ <code>bool host_ls_low_power_phy_clk</code>
</li>
<li>
<b>Field type changed. </b>
<code>int ts_dline</code> ➡️ <code>bool ts_dline</code>
</li>
<li>
<b>Field type changed. </b>
<code>int reload_ctl</code> ➡️ <code>bool reload_ctl</code>
</li>
<li>
<b>Field type changed. </b>
<code>int ahbcfg</code> ➡️ <code>u32 ahbcfg</code>
</li>
<li>
<b>Field type changed. </b>
<code>int uframe_sched</code> ➡️ <code>bool uframe_sched</code>
</li>
<li>
<b>Field type changed. </b>
<code>int external_id_pin_ctl</code> ➡️ <code>bool external_id_pin_ctl</code>
</li>
<li>
<b>Field type changed. </b>
<code>int hibernation</code> ➡️ <code>bool hibernation</code>
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
<code>bool oc_disable</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool acg_enable</code>
</li>
<li>
<b>Field added. </b>
<code>int power_down</code>
</li>
<li>
<b>Field added. </b>
<code>bool lpm</code>
</li>
<li>
<b>Field added. </b>
<code>bool lpm_clock_gating</code>
</li>
<li>
<b>Field added. </b>
<code>bool besl</code>
</li>
<li>
<b>Field added. </b>
<code>bool hird_threshold_en</code>
</li>
<li>
<b>Field added. </b>
<code>u8 hird_threshold</code>
</li>
<li>
<b>Field added. </b>
<code>bool ipg_isoc_en</code>
</li>
<li>
<b>Field removed. </b>
<code>bool hibernation</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool service_interval</code>
</li>
<li>
<b>Field added. </b>
<code>u32 ref_clk_per</code>
</li>
<li>
<b>Field added. </b>
<code>u16 sof_cnt_wkup_alert</code>
</li>
</ul>
</details>
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
<code>bool activate_stm_id_vb_detection</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool no_clock_gating</code>
</li>
</ul>
</details>
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
<code>struct usb_otg_caps otg_caps</code>
</li>
<li>
<b>Field added. </b>
<code>bool activate_ingenic_overcurrent_detection</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 otg_cap</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct dwc2_core_params {
    u8 otg_cap;
    u8 phy_type;
    u8 speed;
    u8 phy_utmi_width;
    bool phy_ulpi_ddr;
    bool phy_ulpi_ext_vbus;
    bool enable_dynamic_fifo;
    bool en_multiple_tx_fifo;
    bool i2c_enable;
    bool acg_enable;
    bool ulpi_fs_ls;
    bool ts_dline;
    bool reload_ctl;
    bool uframe_sched;
    bool external_id_pin_ctl;
    int power_down;
    bool lpm;
    bool lpm_clock_gating;
    bool besl;
    bool hird_threshold_en;
    bool service_interval;
    u8 hird_threshold;
    bool activate_stm_fs_transceiver;
    bool ipg_isoc_en;
    u16 max_packet_count;
    u32 max_transfer_size;
    u32 ahbcfg;
    u32 ref_clk_per;
    u16 sof_cnt_wkup_alert;
    bool host_dma;
    bool dma_desc_enable;
    bool dma_desc_fs_enable;
    bool host_support_fs_ls_low_power;
    bool host_ls_low_power_phy_clk;
    bool oc_disable;
    u8 host_channels;
    u16 host_rx_fifo_size;
    u16 host_nperio_tx_fifo_size;
    u16 host_perio_tx_fifo_size;
    bool g_dma;
    bool g_dma_desc;
    u32 g_rx_fifo_size;
    u32 g_np_tx_fifo_size;
    u32[16] g_tx_fifo_size;
    bool change_speed_quirk;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
