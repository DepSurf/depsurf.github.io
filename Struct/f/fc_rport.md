# Struct: <code>fc_rport</code>

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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fc_rport {
    u32 maxframe_size;
    u32 supported_classes;
    u32 dev_loss_tmo;
    u64 node_name;
    u64 port_name;
    u32 port_id;
    u32 roles;
    enum fc_port_state port_state;
    u32 scsi_target_id;
    u32 fast_io_fail_tmo;
    void * dd_data;
    unsigned int channel;
    u32 number;
    u8 flags;
    struct list_head peers;
    struct device dev;
    struct delayed_work dev_loss_work;
    struct work_struct scan_work;
    struct delayed_work fail_io_work;
    struct work_struct stgt_delete_work;
    struct work_struct rport_delete_work;
    struct request_queue * rqst_q;
}
```
</details>
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
struct fc_rport {
    u32 maxframe_size;
    u32 supported_classes;
    u32 dev_loss_tmo;
    u64 node_name;
    u64 port_name;
    u32 port_id;
    u32 roles;
    enum fc_port_state port_state;
    u32 scsi_target_id;
    u32 fast_io_fail_tmo;
    void * dd_data;
    unsigned int channel;
    u32 number;
    u8 flags;
    struct list_head peers;
    struct device dev;
    struct delayed_work dev_loss_work;
    struct work_struct scan_work;
    struct delayed_work fail_io_work;
    struct work_struct stgt_delete_work;
    struct work_struct rport_delete_work;
    struct request_queue * rqst_q;
}
```
</details>
</li>
</ul>
