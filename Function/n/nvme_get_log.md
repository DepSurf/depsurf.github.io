# Function: <code>nvme_get_log</code>

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
int nvme_get_log(struct nvme_ctrl * ctrl, u32 nsid, u8 log_page, u8 lsp, void * log, size_t size, u64 offset)
```

```json
{
  "name": "nvme_get_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586477072,
      "name": "nvme_get_log",
      "external": true,
      "loc": "drivers/nvme/host/core.c:2688",
      "file": "drivers/nvme/host/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvme/host/core.c:nvme_fw_act_work",
        "drivers/nvme/host/core.c:nvme_scan_work",
        "drivers/nvme/host/core.c:nvme_init_identify",
        "drivers/nvme/host/multipath.c:nvme_read_ana_log",
        "drivers/nvme/host/lightnvm.c:nvme_nvm_get_chk_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586477072,
      "name": "nvme_get_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int nvme_get_log(struct nvme_ctrl * ctrl, u32 nsid, u8 log_page, u8 lsp, void * log, size_t size, u64 offset)
```

```json
{
  "name": "nvme_get_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586353248,
      "name": "nvme_get_log",
      "external": true,
      "loc": "drivers/nvme/host/core.c:2688",
      "file": "drivers/nvme/host/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvme/host/core.c:nvme_fw_act_work",
        "drivers/nvme/host/core.c:nvme_scan_work",
        "drivers/nvme/host/core.c:nvme_init_identify",
        "drivers/nvme/host/multipath.c:nvme_read_ana_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586353248,
      "name": "nvme_get_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int nvme_get_log(struct nvme_ctrl * ctrl, u32 nsid, u8 log_page, u8 lsp, void * log, size_t size, u64 offset)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
int nvme_get_log(struct nvme_ctrl * ctrl, u32 nsid, u8 log_page, u8 lsp, void * log, size_t size, u64 offset)
```
</details>
</li>
</ul>
