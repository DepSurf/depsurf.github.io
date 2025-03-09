# Struct: <code>cec_adap_ops</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cec_adap_ops {
    int (*)(struct cec_adapter *, bool) adap_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_all_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_pin_enable;
    int (*)(struct cec_adapter *, u8) adap_log_addr;
    int (*)(struct cec_adapter *, u8, u32, struct cec_msg *) adap_transmit;
    void (*)(struct cec_adapter *, struct seq_file *) adap_status;
    void (*)(struct cec_adapter *) adap_free;
    int (*)(struct cec_adapter *, struct seq_file *) error_inj_show;
    bool (*)(struct cec_adapter *, char *) error_inj_parse_line;
    int (*)(struct cec_adapter *, struct cec_msg *) received;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cec_adap_ops {
    int (*)(struct cec_adapter *, bool) adap_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_all_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_pin_enable;
    int (*)(struct cec_adapter *, u8) adap_log_addr;
    int (*)(struct cec_adapter *, u8, u32, struct cec_msg *) adap_transmit;
    void (*)(struct cec_adapter *, struct seq_file *) adap_status;
    void (*)(struct cec_adapter *) adap_free;
    int (*)(struct cec_adapter *, struct seq_file *) error_inj_show;
    bool (*)(struct cec_adapter *, char *) error_inj_parse_line;
    int (*)(struct cec_adapter *, struct cec_msg *) received;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cec_adap_ops {
    int (*)(struct cec_adapter *, bool) adap_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_all_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_pin_enable;
    int (*)(struct cec_adapter *, u8) adap_log_addr;
    int (*)(struct cec_adapter *, u8, u32, struct cec_msg *) adap_transmit;
    void (*)(struct cec_adapter *, struct seq_file *) adap_status;
    void (*)(struct cec_adapter *) adap_free;
    int (*)(struct cec_adapter *, struct seq_file *) error_inj_show;
    bool (*)(struct cec_adapter *, char *) error_inj_parse_line;
    int (*)(struct cec_adapter *, struct cec_msg *) received;
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct cec_adap_ops {
    int (*)(struct cec_adapter *, bool) adap_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_all_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_pin_enable;
    int (*)(struct cec_adapter *, u8) adap_log_addr;
    int (*)(struct cec_adapter *, u8, u32, struct cec_msg *) adap_transmit;
    void (*)(struct cec_adapter *, struct seq_file *) adap_status;
    void (*)(struct cec_adapter *) adap_free;
    int (*)(struct cec_adapter *, struct seq_file *) error_inj_show;
    bool (*)(struct cec_adapter *, char *) error_inj_parse_line;
    int (*)(struct cec_adapter *, struct cec_msg *) received;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cec_adap_ops {
    int (*)(struct cec_adapter *, bool) adap_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_all_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_pin_enable;
    int (*)(struct cec_adapter *, u8) adap_log_addr;
    int (*)(struct cec_adapter *, u8, u32, struct cec_msg *) adap_transmit;
    void (*)(struct cec_adapter *, struct seq_file *) adap_status;
    void (*)(struct cec_adapter *) adap_free;
    int (*)(struct cec_adapter *, struct seq_file *) error_inj_show;
    bool (*)(struct cec_adapter *, char *) error_inj_parse_line;
    int (*)(struct cec_adapter *, struct cec_msg *) received;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cec_adap_ops {
    int (*)(struct cec_adapter *, bool) adap_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_all_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_pin_enable;
    int (*)(struct cec_adapter *, u8) adap_log_addr;
    int (*)(struct cec_adapter *, u8, u32, struct cec_msg *) adap_transmit;
    void (*)(struct cec_adapter *, struct seq_file *) adap_status;
    void (*)(struct cec_adapter *) adap_free;
    int (*)(struct cec_adapter *, struct seq_file *) error_inj_show;
    bool (*)(struct cec_adapter *, char *) error_inj_parse_line;
    int (*)(struct cec_adapter *, struct cec_msg *) received;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct cec_adap_ops {
    int (*)(struct cec_adapter *, bool) adap_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_all_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_pin_enable;
    int (*)(struct cec_adapter *, u8) adap_log_addr;
    int (*)(struct cec_adapter *, u8, u32, struct cec_msg *) adap_transmit;
    void (*)(struct cec_adapter *, struct seq_file *) adap_status;
    void (*)(struct cec_adapter *) adap_free;
    int (*)(struct cec_adapter *, struct seq_file *) error_inj_show;
    bool (*)(struct cec_adapter *, char *) error_inj_parse_line;
    int (*)(struct cec_adapter *, struct cec_msg *) received;
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
struct cec_adap_ops {
    int (*)(struct cec_adapter *, bool) adap_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_all_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_pin_enable;
    int (*)(struct cec_adapter *, u8) adap_log_addr;
    int (*)(struct cec_adapter *, u8, u32, struct cec_msg *) adap_transmit;
    void (*)(struct cec_adapter *, struct seq_file *) adap_status;
    void (*)(struct cec_adapter *) adap_free;
    int (*)(struct cec_adapter *, struct seq_file *) error_inj_show;
    bool (*)(struct cec_adapter *, char *) error_inj_parse_line;
    int (*)(struct cec_adapter *, struct cec_msg *) received;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cec_adap_ops {
    int (*)(struct cec_adapter *, bool) adap_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_all_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_pin_enable;
    int (*)(struct cec_adapter *, u8) adap_log_addr;
    int (*)(struct cec_adapter *, u8, u32, struct cec_msg *) adap_transmit;
    void (*)(struct cec_adapter *, struct seq_file *) adap_status;
    void (*)(struct cec_adapter *) adap_free;
    int (*)(struct cec_adapter *, struct seq_file *) error_inj_show;
    bool (*)(struct cec_adapter *, char *) error_inj_parse_line;
    int (*)(struct cec_adapter *, struct cec_msg *) received;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cec_adap_ops {
    int (*)(struct cec_adapter *, bool) adap_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_all_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_pin_enable;
    int (*)(struct cec_adapter *, u8) adap_log_addr;
    int (*)(struct cec_adapter *, u8, u32, struct cec_msg *) adap_transmit;
    void (*)(struct cec_adapter *, struct seq_file *) adap_status;
    void (*)(struct cec_adapter *) adap_free;
    int (*)(struct cec_adapter *, struct seq_file *) error_inj_show;
    bool (*)(struct cec_adapter *, char *) error_inj_parse_line;
    int (*)(struct cec_adapter *, struct cec_msg *) received;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cec_adap_ops {
    int (*)(struct cec_adapter *, bool) adap_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_all_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_pin_enable;
    int (*)(struct cec_adapter *, u8) adap_log_addr;
    int (*)(struct cec_adapter *, u8, u32, struct cec_msg *) adap_transmit;
    void (*)(struct cec_adapter *, struct seq_file *) adap_status;
    void (*)(struct cec_adapter *) adap_free;
    int (*)(struct cec_adapter *, struct seq_file *) error_inj_show;
    bool (*)(struct cec_adapter *, char *) error_inj_parse_line;
    int (*)(struct cec_adapter *, struct cec_msg *) received;
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct cec_adap_ops {
    int (*)(struct cec_adapter *, bool) adap_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_all_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_pin_enable;
    int (*)(struct cec_adapter *, u8) adap_log_addr;
    int (*)(struct cec_adapter *, u8, u32, struct cec_msg *) adap_transmit;
    void (*)(struct cec_adapter *, struct seq_file *) adap_status;
    void (*)(struct cec_adapter *) adap_free;
    int (*)(struct cec_adapter *, struct seq_file *) error_inj_show;
    bool (*)(struct cec_adapter *, char *) error_inj_parse_line;
    int (*)(struct cec_adapter *, struct cec_msg *) received;
}
```
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct cec_adap_ops {
    int (*)(struct cec_adapter *, bool) adap_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_all_enable;
    int (*)(struct cec_adapter *, bool) adap_monitor_pin_enable;
    int (*)(struct cec_adapter *, u8) adap_log_addr;
    int (*)(struct cec_adapter *, u8, u32, struct cec_msg *) adap_transmit;
    void (*)(struct cec_adapter *, struct seq_file *) adap_status;
    void (*)(struct cec_adapter *) adap_free;
    int (*)(struct cec_adapter *, struct seq_file *) error_inj_show;
    bool (*)(struct cec_adapter *, char *) error_inj_parse_line;
    int (*)(struct cec_adapter *, struct cec_msg *) received;
}
```
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
