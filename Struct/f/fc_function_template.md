# Struct: <code>fc_function_template</code>

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
struct fc_function_template {
    void (*)(struct fc_rport *) get_rport_dev_loss_tmo;
    void (*)(struct fc_rport *, u32) set_rport_dev_loss_tmo;
    void (*)(struct scsi_target *) get_starget_node_name;
    void (*)(struct scsi_target *) get_starget_port_name;
    void (*)(struct scsi_target *) get_starget_port_id;
    void (*)(struct Scsi_Host *) get_host_port_id;
    void (*)(struct Scsi_Host *) get_host_port_type;
    void (*)(struct Scsi_Host *) get_host_port_state;
    void (*)(struct Scsi_Host *) get_host_active_fc4s;
    void (*)(struct Scsi_Host *) get_host_speed;
    void (*)(struct Scsi_Host *) get_host_fabric_name;
    void (*)(struct Scsi_Host *) get_host_symbolic_name;
    void (*)(struct Scsi_Host *) set_host_system_hostname;
    struct fc_host_statistics * (*)(struct Scsi_Host *) get_fc_host_stats;
    void (*)(struct Scsi_Host *) reset_fc_host_stats;
    int (*)(struct Scsi_Host *) issue_fc_host_lip;
    void (*)(struct fc_rport *) dev_loss_tmo_callbk;
    void (*)(struct fc_rport *) terminate_rport_io;
    void (*)(struct fc_vport *) set_vport_symbolic_name;
    int (*)(struct fc_vport *, bool) vport_create;
    int (*)(struct fc_vport *, bool) vport_disable;
    int (*)(struct fc_vport *) vport_delete;
    int (*)(struct bsg_job *) bsg_request;
    int (*)(struct bsg_job *) bsg_timeout;
    u32 dd_fcrport_size;
    u32 dd_fcvport_size;
    u32 dd_bsg_size;
    long unsigned int show_rport_maxframe_size;
    long unsigned int show_rport_supported_classes;
    long unsigned int show_rport_dev_loss_tmo;
    long unsigned int show_starget_node_name;
    long unsigned int show_starget_port_name;
    long unsigned int show_starget_port_id;
    long unsigned int show_host_node_name;
    long unsigned int show_host_port_name;
    long unsigned int show_host_permanent_port_name;
    long unsigned int show_host_supported_classes;
    long unsigned int show_host_supported_fc4s;
    long unsigned int show_host_supported_speeds;
    long unsigned int show_host_maxframe_size;
    long unsigned int show_host_serial_number;
    long unsigned int show_host_manufacturer;
    long unsigned int show_host_model;
    long unsigned int show_host_model_description;
    long unsigned int show_host_hardware_version;
    long unsigned int show_host_driver_version;
    long unsigned int show_host_firmware_version;
    long unsigned int show_host_optionrom_version;
    long unsigned int show_host_port_id;
    long unsigned int show_host_port_type;
    long unsigned int show_host_port_state;
    long unsigned int show_host_active_fc4s;
    long unsigned int show_host_speed;
    long unsigned int show_host_fabric_name;
    long unsigned int show_host_symbolic_name;
    long unsigned int show_host_system_hostname;
    long unsigned int disable_target_scan;
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
struct fc_function_template {
    void (*)(struct fc_rport *) get_rport_dev_loss_tmo;
    void (*)(struct fc_rport *, u32) set_rport_dev_loss_tmo;
    void (*)(struct scsi_target *) get_starget_node_name;
    void (*)(struct scsi_target *) get_starget_port_name;
    void (*)(struct scsi_target *) get_starget_port_id;
    void (*)(struct Scsi_Host *) get_host_port_id;
    void (*)(struct Scsi_Host *) get_host_port_type;
    void (*)(struct Scsi_Host *) get_host_port_state;
    void (*)(struct Scsi_Host *) get_host_active_fc4s;
    void (*)(struct Scsi_Host *) get_host_speed;
    void (*)(struct Scsi_Host *) get_host_fabric_name;
    void (*)(struct Scsi_Host *) get_host_symbolic_name;
    void (*)(struct Scsi_Host *) set_host_system_hostname;
    struct fc_host_statistics * (*)(struct Scsi_Host *) get_fc_host_stats;
    void (*)(struct Scsi_Host *) reset_fc_host_stats;
    int (*)(struct Scsi_Host *) issue_fc_host_lip;
    void (*)(struct fc_rport *) dev_loss_tmo_callbk;
    void (*)(struct fc_rport *) terminate_rport_io;
    void (*)(struct fc_vport *) set_vport_symbolic_name;
    int (*)(struct fc_vport *, bool) vport_create;
    int (*)(struct fc_vport *, bool) vport_disable;
    int (*)(struct fc_vport *) vport_delete;
    int (*)(struct bsg_job *) bsg_request;
    int (*)(struct bsg_job *) bsg_timeout;
    u32 dd_fcrport_size;
    u32 dd_fcvport_size;
    u32 dd_bsg_size;
    long unsigned int show_rport_maxframe_size;
    long unsigned int show_rport_supported_classes;
    long unsigned int show_rport_dev_loss_tmo;
    long unsigned int show_starget_node_name;
    long unsigned int show_starget_port_name;
    long unsigned int show_starget_port_id;
    long unsigned int show_host_node_name;
    long unsigned int show_host_port_name;
    long unsigned int show_host_permanent_port_name;
    long unsigned int show_host_supported_classes;
    long unsigned int show_host_supported_fc4s;
    long unsigned int show_host_supported_speeds;
    long unsigned int show_host_maxframe_size;
    long unsigned int show_host_serial_number;
    long unsigned int show_host_manufacturer;
    long unsigned int show_host_model;
    long unsigned int show_host_model_description;
    long unsigned int show_host_hardware_version;
    long unsigned int show_host_driver_version;
    long unsigned int show_host_firmware_version;
    long unsigned int show_host_optionrom_version;
    long unsigned int show_host_port_id;
    long unsigned int show_host_port_type;
    long unsigned int show_host_port_state;
    long unsigned int show_host_active_fc4s;
    long unsigned int show_host_speed;
    long unsigned int show_host_fabric_name;
    long unsigned int show_host_symbolic_name;
    long unsigned int show_host_system_hostname;
    long unsigned int disable_target_scan;
}
```
</details>
</li>
</ul>
