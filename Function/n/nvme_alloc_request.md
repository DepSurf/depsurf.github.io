# Function: <code>nvme_alloc_request</code>

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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct request * nvme_alloc_request(struct request_queue * q, struct nvme_command * cmd, blk_mq_req_flags_t flags, int qid)
```

```json
{
  "name": "nvme_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586453808,
      "name": "nvme_alloc_request",
      "external": true,
      "loc": "drivers/nvme/host/core.c:478",
      "file": "drivers/nvme/host/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvme/host/core.c:nvme_submit_user_cmd",
        "drivers/nvme/host/core.c:__nvme_submit_sync_cmd",
        "drivers/nvme/host/lightnvm.c:nvme_nvm_submit_io",
        "drivers/nvme/host/pci.c:__nvme_disable_io_queues",
        "drivers/nvme/host/pci.c:nvme_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586453808,
      "name": "nvme_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct request * nvme_alloc_request(struct request_queue * q, struct nvme_command * cmd, blk_mq_req_flags_t flags, int qid)
```

```json
{
  "name": "nvme_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586330048,
      "name": "nvme_alloc_request",
      "external": true,
      "loc": "drivers/nvme/host/core.c:478",
      "file": "drivers/nvme/host/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvme/host/core.c:nvme_submit_user_cmd",
        "drivers/nvme/host/core.c:__nvme_submit_sync_cmd",
        "drivers/nvme/host/pci.c:__nvme_disable_io_queues",
        "drivers/nvme/host/pci.c:nvme_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586330048,
      "name": "nvme_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct request * nvme_alloc_request(struct request_queue * q, struct nvme_command * cmd, blk_mq_req_flags_t flags, int qid)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
struct request * nvme_alloc_request(struct request_queue * q, struct nvme_command * cmd, blk_mq_req_flags_t flags, int qid)
```
</details>
</li>
</ul>
