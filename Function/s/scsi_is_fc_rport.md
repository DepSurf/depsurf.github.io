# Function: <code>scsi_is_fc_rport</code>

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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int scsi_is_fc_rport(const struct device * dev)
```

```json
{
  "name": "scsi_is_fc_rport",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586251576,
      "name": "scsi_is_fc_rport",
      "external": true,
      "loc": "drivers/scsi/scsi_transport_fc.c:1987",
      "file": "drivers/scsi/scsi_transport_fc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_transport_fc.c:fc_bsg_dispatch_prep",
        "drivers/scsi/scsi_transport_fc.c:fc_bsg_dispatch",
        "drivers/scsi/scsi_transport_fc.c:fc_bsg_job_timeout",
        "drivers/scsi/scsi_transport_fc.c:fc_block_scsi_eh",
        "drivers/scsi/scsi_transport_fc.c:fc_eh_timed_out",
        "drivers/scsi/scsi_transport_fc.c:show_fc_starget_port_id",
        "drivers/scsi/scsi_transport_fc.c:show_fc_starget_port_name",
        "drivers/scsi/scsi_transport_fc.c:show_fc_starget_node_name",
        "drivers/scsi/scsi_transport_fc.c:fc_target_setup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586234304,
      "name": "scsi_is_fc_rport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
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
int scsi_is_fc_rport(const struct device * dev)
```
</details>
</li>
</ul>
