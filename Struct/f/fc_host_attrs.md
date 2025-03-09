# Struct: <code>fc_host_attrs</code>

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
struct fc_host_attrs {
    u64 node_name;
    u64 port_name;
    u64 permanent_port_name;
    u32 supported_classes;
    u8[32] supported_fc4s;
    u32 supported_speeds;
    u32 maxframe_size;
    u16 max_npiv_vports;
    char[80] serial_number;
    char[80] manufacturer;
    char[256] model;
    char[256] model_description;
    char[64] hardware_version;
    char[64] driver_version;
    char[64] firmware_version;
    char[64] optionrom_version;
    u32 port_id;
    enum fc_port_type port_type;
    enum fc_port_state port_state;
    u8[32] active_fc4s;
    u32 speed;
    u64 fabric_name;
    char[256] symbolic_name;
    char[256] system_hostname;
    u32 dev_loss_tmo;
    enum fc_tgtid_binding_type tgtid_bind_type;
    struct list_head rports;
    struct list_head rport_bindings;
    struct list_head vports;
    u32 next_rport_number;
    u32 next_target_id;
    u32 next_vport_number;
    u16 npiv_vports_inuse;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    char[20] devloss_work_q_name;
    struct workqueue_struct * devloss_work_q;
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
struct fc_host_attrs {
    u64 node_name;
    u64 port_name;
    u64 permanent_port_name;
    u32 supported_classes;
    u8[32] supported_fc4s;
    u32 supported_speeds;
    u32 maxframe_size;
    u16 max_npiv_vports;
    char[80] serial_number;
    char[80] manufacturer;
    char[256] model;
    char[256] model_description;
    char[64] hardware_version;
    char[64] driver_version;
    char[64] firmware_version;
    char[64] optionrom_version;
    u32 port_id;
    enum fc_port_type port_type;
    enum fc_port_state port_state;
    u8[32] active_fc4s;
    u32 speed;
    u64 fabric_name;
    char[256] symbolic_name;
    char[256] system_hostname;
    u32 dev_loss_tmo;
    enum fc_tgtid_binding_type tgtid_bind_type;
    struct list_head rports;
    struct list_head rport_bindings;
    struct list_head vports;
    u32 next_rport_number;
    u32 next_target_id;
    u32 next_vport_number;
    u16 npiv_vports_inuse;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    char[20] devloss_work_q_name;
    struct workqueue_struct * devloss_work_q;
    struct request_queue * rqst_q;
}
```
</details>
</li>
</ul>
