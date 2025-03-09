# Struct: <code>dwc2_hw_params</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int host_rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int utmi_phy_data_width;
    u32 snpsid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int dma_desc_fs_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int host_rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int utmi_phy_data_width;
    u32 snpsid;
    u32 dev_ep_dirs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int utmi_phy_data_width;
    u32 snpsid;
    u32 dev_ep_dirs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int utmi_phy_data_width;
    u32 snpsid;
    u32 dev_ep_dirs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_in_eps;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int utmi_phy_data_width;
    u32 snpsid;
    u32 dev_ep_dirs;
    u32[16] g_tx_fifo_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int acg_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_in_eps;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int hibernation;
    unsigned int utmi_phy_data_width;
    unsigned int lpm_mode;
    unsigned int ipg_isoc_en;
    u32 snpsid;
    u32 dev_ep_dirs;
    u32[16] g_tx_fifo_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int acg_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_in_eps;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int hibernation;
    unsigned int utmi_phy_data_width;
    unsigned int lpm_mode;
    unsigned int ipg_isoc_en;
    unsigned int service_interval_mode;
    u32 snpsid;
    u32 dev_ep_dirs;
    u32[16] g_tx_fifo_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int acg_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_in_eps;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int hibernation;
    unsigned int utmi_phy_data_width;
    unsigned int lpm_mode;
    unsigned int ipg_isoc_en;
    unsigned int service_interval_mode;
    u32 snpsid;
    u32 dev_ep_dirs;
    u32[16] g_tx_fifo_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int acg_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_in_eps;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int hibernation;
    unsigned int utmi_phy_data_width;
    unsigned int lpm_mode;
    unsigned int ipg_isoc_en;
    unsigned int service_interval_mode;
    u32 snpsid;
    u32 dev_ep_dirs;
    u32[16] g_tx_fifo_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int acg_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_in_eps;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int hibernation;
    unsigned int utmi_phy_data_width;
    unsigned int lpm_mode;
    unsigned int ipg_isoc_en;
    unsigned int service_interval_mode;
    u32 snpsid;
    u32 dev_ep_dirs;
    u32[16] g_tx_fifo_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int acg_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_in_eps;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int hibernation;
    unsigned int utmi_phy_data_width;
    unsigned int lpm_mode;
    unsigned int ipg_isoc_en;
    unsigned int service_interval_mode;
    u32 snpsid;
    u32 dev_ep_dirs;
    u32[16] g_tx_fifo_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int acg_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_in_eps;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int hibernation;
    unsigned int utmi_phy_data_width;
    unsigned int lpm_mode;
    unsigned int ipg_isoc_en;
    unsigned int service_interval_mode;
    u32 snpsid;
    u32 dev_ep_dirs;
    u32[16] g_tx_fifo_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int acg_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_in_eps;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int hibernation;
    unsigned int utmi_phy_data_width;
    unsigned int lpm_mode;
    unsigned int ipg_isoc_en;
    unsigned int service_interval_mode;
    u32 snpsid;
    u32 dev_ep_dirs;
    u32[16] g_tx_fifo_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int acg_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_in_eps;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int hibernation;
    unsigned int utmi_phy_data_width;
    unsigned int lpm_mode;
    unsigned int ipg_isoc_en;
    unsigned int service_interval_mode;
    u32 snpsid;
    u32 dev_ep_dirs;
    u32[16] g_tx_fifo_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int acg_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_in_eps;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int hibernation;
    unsigned int utmi_phy_data_width;
    unsigned int lpm_mode;
    unsigned int ipg_isoc_en;
    unsigned int service_interval_mode;
    u32 snpsid;
    u32 dev_ep_dirs;
    u32[16] g_tx_fifo_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int acg_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_in_eps;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int hibernation;
    unsigned int utmi_phy_data_width;
    unsigned int lpm_mode;
    unsigned int ipg_isoc_en;
    unsigned int service_interval_mode;
    u32 snpsid;
    u32 dev_ep_dirs;
    u32[16] g_tx_fifo_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int acg_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_in_eps;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int hibernation;
    unsigned int utmi_phy_data_width;
    unsigned int lpm_mode;
    unsigned int ipg_isoc_en;
    unsigned int service_interval_mode;
    u32 snpsid;
    u32 dev_ep_dirs;
    u32[16] g_tx_fifo_size;
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
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int acg_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_in_eps;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int hibernation;
    unsigned int utmi_phy_data_width;
    unsigned int lpm_mode;
    unsigned int ipg_isoc_en;
    unsigned int service_interval_mode;
    u32 snpsid;
    u32 dev_ep_dirs;
    u32[16] g_tx_fifo_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int acg_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_in_eps;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int hibernation;
    unsigned int utmi_phy_data_width;
    unsigned int lpm_mode;
    unsigned int ipg_isoc_en;
    unsigned int service_interval_mode;
    u32 snpsid;
    u32 dev_ep_dirs;
    u32[16] g_tx_fifo_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int acg_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_in_eps;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int hibernation;
    unsigned int utmi_phy_data_width;
    unsigned int lpm_mode;
    unsigned int ipg_isoc_en;
    unsigned int service_interval_mode;
    u32 snpsid;
    u32 dev_ep_dirs;
    u32[16] g_tx_fifo_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int acg_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_in_eps;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int hibernation;
    unsigned int utmi_phy_data_width;
    unsigned int lpm_mode;
    unsigned int ipg_isoc_en;
    unsigned int service_interval_mode;
    u32 snpsid;
    u32 dev_ep_dirs;
    u32[16] g_tx_fifo_size;
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
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int acg_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_in_eps;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int hibernation;
    unsigned int utmi_phy_data_width;
    unsigned int lpm_mode;
    unsigned int ipg_isoc_en;
    unsigned int service_interval_mode;
    u32 snpsid;
    u32 dev_ep_dirs;
    u32[16] g_tx_fifo_size;
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
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int acg_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_in_eps;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int hibernation;
    unsigned int utmi_phy_data_width;
    unsigned int lpm_mode;
    unsigned int ipg_isoc_en;
    unsigned int service_interval_mode;
    u32 snpsid;
    u32 dev_ep_dirs;
    u32[16] g_tx_fifo_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int acg_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_in_eps;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int hibernation;
    unsigned int utmi_phy_data_width;
    unsigned int lpm_mode;
    unsigned int ipg_isoc_en;
    unsigned int service_interval_mode;
    u32 snpsid;
    u32 dev_ep_dirs;
    u32[16] g_tx_fifo_size;
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
<code>unsigned int dma_desc_fs_enable</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int dev_nperio_tx_fifo_size</code>
</li>
<li>
<b>Field added. </b>
<code>u32 dev_ep_dirs</code>
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
<code>unsigned int rx_fifo_size</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int dma_desc_fs_enable</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int host_rx_fifo_size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int num_dev_in_eps</code>
</li>
<li>
<b>Field added. </b>
<code>u32[16] g_tx_fifo_size</code>
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
<code>unsigned int acg_enable</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int hibernation</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int lpm_mode</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int ipg_isoc_en</code>
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
<code>unsigned int service_interval_mode</code>
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
struct dwc2_hw_params {
    unsigned int op_mode;
    unsigned int arch;
    unsigned int dma_desc_enable;
    unsigned int enable_dynamic_fifo;
    unsigned int en_multiple_tx_fifo;
    unsigned int rx_fifo_size;
    unsigned int host_nperio_tx_fifo_size;
    unsigned int dev_nperio_tx_fifo_size;
    unsigned int host_perio_tx_fifo_size;
    unsigned int nperio_tx_q_depth;
    unsigned int host_perio_tx_q_depth;
    unsigned int dev_token_q_depth;
    unsigned int max_transfer_size;
    unsigned int max_packet_count;
    unsigned int host_channels;
    unsigned int hs_phy_type;
    unsigned int fs_phy_type;
    unsigned int i2c_enable;
    unsigned int acg_enable;
    unsigned int num_dev_ep;
    unsigned int num_dev_in_eps;
    unsigned int num_dev_perio_in_ep;
    unsigned int total_fifo_size;
    unsigned int power_optimized;
    unsigned int hibernation;
    unsigned int utmi_phy_data_width;
    unsigned int lpm_mode;
    unsigned int ipg_isoc_en;
    unsigned int service_interval_mode;
    u32 snpsid;
    u32 dev_ep_dirs;
    u32[16] g_tx_fifo_size;
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
