# Struct: <code>mmc_host_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *, bool) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *, bool) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *) ack_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *) ack_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *) ack_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *) ack_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    int (*)(struct mmc_host *) hs400_prepare_ddr;
    void (*)(struct mmc_host *) hs400_downgrade;
    void (*)(struct mmc_host *) hs400_complete;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *) ack_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    int (*)(struct mmc_host *) hs400_prepare_ddr;
    void (*)(struct mmc_host *) hs400_downgrade;
    void (*)(struct mmc_host *) hs400_complete;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *) ack_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    int (*)(struct mmc_host *) hs400_prepare_ddr;
    void (*)(struct mmc_host *) hs400_downgrade;
    void (*)(struct mmc_host *) hs400_complete;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    int (*)(struct mmc_host *, struct mmc_request *) request_atomic;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *) ack_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    int (*)(struct mmc_host *) hs400_prepare_ddr;
    void (*)(struct mmc_host *) hs400_downgrade;
    void (*)(struct mmc_host *) hs400_complete;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    int (*)(struct mmc_host *, struct mmc_request *) request_atomic;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *) ack_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    int (*)(struct mmc_host *) hs400_prepare_ddr;
    void (*)(struct mmc_host *) hs400_downgrade;
    void (*)(struct mmc_host *) hs400_complete;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
    int (*)(struct mmc_host *, struct mmc_ios *) init_sd_express;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    int (*)(struct mmc_host *, struct mmc_request *) request_atomic;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *) ack_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    int (*)(struct mmc_host *) hs400_prepare_ddr;
    void (*)(struct mmc_host *) hs400_downgrade;
    void (*)(struct mmc_host *) hs400_complete;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
    int (*)(struct mmc_host *, struct mmc_ios *) init_sd_express;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    int (*)(struct mmc_host *, struct mmc_request *) request_atomic;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *) ack_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    int (*)(struct mmc_host *) hs400_prepare_ddr;
    void (*)(struct mmc_host *) hs400_downgrade;
    void (*)(struct mmc_host *) hs400_complete;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
    int (*)(struct mmc_host *, struct mmc_ios *) init_sd_express;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    int (*)(struct mmc_host *, struct mmc_request *) request_atomic;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *) ack_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    int (*)(struct mmc_host *, struct mmc_card *) execute_hs400_tuning;
    int (*)(struct mmc_host *) hs400_prepare_ddr;
    void (*)(struct mmc_host *) hs400_downgrade;
    void (*)(struct mmc_host *) hs400_complete;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) card_hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
    int (*)(struct mmc_host *, struct mmc_ios *) init_sd_express;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    int (*)(struct mmc_host *, struct mmc_request *) request_atomic;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *) ack_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    int (*)(struct mmc_host *, struct mmc_card *) execute_hs400_tuning;
    int (*)(struct mmc_host *) hs400_prepare_ddr;
    void (*)(struct mmc_host *) hs400_downgrade;
    void (*)(struct mmc_host *) hs400_complete;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) card_hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
    int (*)(struct mmc_host *, struct mmc_ios *) init_sd_express;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    int (*)(struct mmc_host *, struct mmc_request *) request_atomic;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *) ack_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    int (*)(struct mmc_host *, struct mmc_card *) execute_hs400_tuning;
    int (*)(struct mmc_host *) hs400_prepare_ddr;
    void (*)(struct mmc_host *) hs400_downgrade;
    void (*)(struct mmc_host *) hs400_complete;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) card_hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
    int (*)(struct mmc_host *, struct mmc_ios *) init_sd_express;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    int (*)(struct mmc_host *, struct mmc_request *) request_atomic;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *) ack_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    int (*)(struct mmc_host *, struct mmc_card *) execute_hs400_tuning;
    int (*)(struct mmc_host *, struct mmc_card *) prepare_sd_hs_tuning;
    int (*)(struct mmc_host *, struct mmc_card *) execute_sd_hs_tuning;
    int (*)(struct mmc_host *) hs400_prepare_ddr;
    void (*)(struct mmc_host *) hs400_downgrade;
    void (*)(struct mmc_host *) hs400_complete;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) card_hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
    int (*)(struct mmc_host *, struct mmc_ios *) init_sd_express;
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
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *) ack_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    int (*)(struct mmc_host *) hs400_prepare_ddr;
    void (*)(struct mmc_host *) hs400_downgrade;
    void (*)(struct mmc_host *) hs400_complete;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *) ack_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    int (*)(struct mmc_host *) hs400_prepare_ddr;
    void (*)(struct mmc_host *) hs400_downgrade;
    void (*)(struct mmc_host *) hs400_complete;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *) ack_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    int (*)(struct mmc_host *) hs400_prepare_ddr;
    void (*)(struct mmc_host *) hs400_downgrade;
    void (*)(struct mmc_host *) hs400_complete;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *) ack_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    int (*)(struct mmc_host *) hs400_prepare_ddr;
    void (*)(struct mmc_host *) hs400_downgrade;
    void (*)(struct mmc_host *) hs400_complete;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
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
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *) ack_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    int (*)(struct mmc_host *) hs400_prepare_ddr;
    void (*)(struct mmc_host *) hs400_downgrade;
    void (*)(struct mmc_host *) hs400_complete;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
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
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *) ack_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    int (*)(struct mmc_host *) hs400_prepare_ddr;
    void (*)(struct mmc_host *) hs400_downgrade;
    void (*)(struct mmc_host *) hs400_complete;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *) ack_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    int (*)(struct mmc_host *) hs400_prepare_ddr;
    void (*)(struct mmc_host *) hs400_downgrade;
    void (*)(struct mmc_host *) hs400_complete;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
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
<code>void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>void (*)(struct mmc_host *, struct mmc_request *, bool) pre_req</code> ➡️ <code>void (*)(struct mmc_host *, struct mmc_request *) pre_req</code>
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
<code>void (*)(struct mmc_host *) ack_sdio_irq</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct mmc_host *) hs400_prepare_ddr</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct mmc_host *) hs400_downgrade</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct mmc_host *) hs400_complete</code>
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
<code>int (*)(struct mmc_host *, struct mmc_request *) request_atomic</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct mmc_host *, struct mmc_ios *) init_sd_express</code>
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
<code>int (*)(struct mmc_host *, struct mmc_card *) execute_hs400_tuning</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct mmc_host *) card_hw_reset</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct mmc_host *) hw_reset</code>
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
<code>int (*)(struct mmc_host *, struct mmc_card *) prepare_sd_hs_tuning</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct mmc_host *, struct mmc_card *) execute_sd_hs_tuning</code>
</li>
</ul>
</details>
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
struct mmc_host_ops {
    void (*)(struct mmc_host *, struct mmc_request *, int) post_req;
    void (*)(struct mmc_host *, struct mmc_request *) pre_req;
    void (*)(struct mmc_host *, struct mmc_request *) request;
    void (*)(struct mmc_host *, struct mmc_ios *) set_ios;
    int (*)(struct mmc_host *) get_ro;
    int (*)(struct mmc_host *) get_cd;
    void (*)(struct mmc_host *, int) enable_sdio_irq;
    void (*)(struct mmc_host *) ack_sdio_irq;
    void (*)(struct mmc_host *, struct mmc_card *) init_card;
    int (*)(struct mmc_host *, struct mmc_ios *) start_signal_voltage_switch;
    int (*)(struct mmc_host *) card_busy;
    int (*)(struct mmc_host *, u32) execute_tuning;
    int (*)(struct mmc_host *, struct mmc_ios *) prepare_hs400_tuning;
    int (*)(struct mmc_host *) hs400_prepare_ddr;
    void (*)(struct mmc_host *) hs400_downgrade;
    void (*)(struct mmc_host *) hs400_complete;
    void (*)(struct mmc_host *, struct mmc_ios *) hs400_enhanced_strobe;
    int (*)(struct mmc_card *, unsigned int, int, int, int *) select_drive_strength;
    void (*)(struct mmc_host *) hw_reset;
    void (*)(struct mmc_host *) card_event;
    int (*)(struct mmc_card *, unsigned int, int) multi_io_quirk;
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
