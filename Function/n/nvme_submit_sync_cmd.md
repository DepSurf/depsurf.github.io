# Function: <code>nvme_submit_sync_cmd</code>

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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int nvme_submit_sync_cmd(struct request_queue * q, struct nvme_command * cmd, void * buffer, unsigned int bufflen)
```

```json
{
  "name": "nvme_submit_sync_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586482166,
      "name": "nvme_submit_sync_cmd",
      "external": true,
      "loc": "drivers/nvme/host/core.c:853",
      "file": "drivers/nvme/host/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/core.c:nvme_scan_work",
        "drivers/nvme/host/core.c:nvme_get_log",
        "drivers/nvme/host/core.c:nvme_pr_command",
        "drivers/nvme/host/core.c:nvme_report_ns_ids",
        "drivers/nvme/host/core.c:nvme_toggle_streams"
      ],
      "caller_func": [
        "drivers/nvme/host/lightnvm.c:nvme_nvm_set_bb_tbl",
        "drivers/nvme/host/lightnvm.c:nvme_nvm_get_bb_tbl",
        "drivers/nvme/host/lightnvm.c:nvme_nvm_identity",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_setup_io_queues",
        "drivers/nvme/host/pci.c:nvme_setup_io_queues",
        "drivers/nvme/host/pci.c:adapter_delete_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586462640,
      "name": "nvme_submit_sync_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int nvme_submit_sync_cmd(struct request_queue * q, struct nvme_command * cmd, void * buffer, unsigned int bufflen)
```

```json
{
  "name": "nvme_submit_sync_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586358294,
      "name": "nvme_submit_sync_cmd",
      "external": true,
      "loc": "drivers/nvme/host/core.c:853",
      "file": "drivers/nvme/host/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/core.c:nvme_scan_work",
        "drivers/nvme/host/core.c:nvme_get_log",
        "drivers/nvme/host/core.c:nvme_pr_command",
        "drivers/nvme/host/core.c:nvme_report_ns_ids",
        "drivers/nvme/host/core.c:nvme_toggle_streams"
      ],
      "caller_func": [
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_setup_io_queues",
        "drivers/nvme/host/pci.c:nvme_setup_io_queues",
        "drivers/nvme/host/pci.c:adapter_delete_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586338880,
      "name": "nvme_submit_sync_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➕</summary>

```c
int nvme_submit_sync_cmd(struct request_queue * q, struct nvme_command * cmd, void * buffer, unsigned int bufflen)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
int nvme_submit_sync_cmd(struct request_queue * q, struct nvme_command * cmd, void * buffer, unsigned int bufflen)
```
</details>
</li>
</ul>
