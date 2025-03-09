# Function: <code>nvme_report_ns_ids</code>

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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int nvme_report_ns_ids(struct nvme_ctrl * ctrl, unsigned int nsid, struct nvme_id_ns * id, struct nvme_ns_ids * ids)
```

```json
{
  "name": "nvme_report_ns_ids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvme_report_ns_ids",
      "external": false,
      "loc": "drivers/nvme/host/core.c:1717",
      "file": "drivers/nvme/host/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/core.c:nvme_alloc_ns_head",
        "drivers/nvme/host/core.c:nvme_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586467936,
      "name": "nvme_report_ns_ids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
    },
    {
      "addr": 18446744071586482979,
      "name": "nvme_report_ns_ids.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int nvme_report_ns_ids(struct nvme_ctrl * ctrl, unsigned int nsid, struct nvme_id_ns * id, struct nvme_ns_ids * ids)
```

```json
{
  "name": "nvme_report_ns_ids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvme_report_ns_ids",
      "external": false,
      "loc": "drivers/nvme/host/core.c:1717",
      "file": "drivers/nvme/host/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/core.c:nvme_alloc_ns_head",
        "drivers/nvme/host/core.c:nvme_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586344176,
      "name": "nvme_report_ns_ids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
    },
    {
      "addr": 18446744071586359107,
      "name": "nvme_report_ns_ids.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int nvme_report_ns_ids(struct nvme_ctrl * ctrl, unsigned int nsid, struct nvme_id_ns * id, struct nvme_ns_ids * ids)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
int nvme_report_ns_ids(struct nvme_ctrl * ctrl, unsigned int nsid, struct nvme_id_ns * id, struct nvme_ns_ids * ids)
```
</details>
</li>
</ul>
