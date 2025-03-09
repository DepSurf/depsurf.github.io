# Function: <code>nvme_complete_async_event</code>

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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void nvme_complete_async_event(struct nvme_ctrl * ctrl, __le16 status, volatile union nvme_result * res)
```

```json
{
  "name": "nvme_complete_async_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586465743,
      "name": "nvme_complete_async_event",
      "external": true,
      "loc": "drivers/nvme/host/core.c:3929",
      "file": "drivers/nvme/host/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvme/host/pci.c:nvme_dev_disable",
        "drivers/nvme/host/pci.c:nvme_poll",
        "drivers/nvme/host/pci.c:nvme_poll_irqdisable",
        "drivers/nvme/host/pci.c:nvme_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586482945,
      "name": "nvme_complete_async_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071586465680,
      "name": "nvme_complete_async_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void nvme_complete_async_event(struct nvme_ctrl * ctrl, __le16 status, volatile union nvme_result * res)
```

```json
{
  "name": "nvme_complete_async_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586341983,
      "name": "nvme_complete_async_event",
      "external": true,
      "loc": "drivers/nvme/host/core.c:3929",
      "file": "drivers/nvme/host/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvme/host/pci.c:nvme_dev_disable",
        "drivers/nvme/host/pci.c:nvme_poll",
        "drivers/nvme/host/pci.c:nvme_poll_irqdisable",
        "drivers/nvme/host/pci.c:nvme_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586359073,
      "name": "nvme_complete_async_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071586341920,
      "name": "nvme_complete_async_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
void nvme_complete_async_event(struct nvme_ctrl * ctrl, __le16 status, volatile union nvme_result * res)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
void nvme_complete_async_event(struct nvme_ctrl * ctrl, __le16 status, volatile union nvme_result * res)
```
</details>
</li>
</ul>
