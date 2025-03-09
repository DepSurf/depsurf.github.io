# Function: <code>nvme_dev_disable</code>

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
void nvme_dev_disable(struct nvme_dev * dev, bool shutdown)
```

```json
{
  "name": "nvme_dev_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvme_dev_disable",
      "external": false,
      "loc": "drivers/nvme/host/pci.c:2415",
      "file": "drivers/nvme/host/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvme/host/pci.c:nvme_error_detected",
        "drivers/nvme/host/pci.c:nvme_simple_suspend",
        "drivers/nvme/host/pci.c:nvme_suspend",
        "drivers/nvme/host/pci.c:nvme_suspend",
        "drivers/nvme/host/pci.c:nvme_remove",
        "drivers/nvme/host/pci.c:nvme_remove",
        "drivers/nvme/host/pci.c:nvme_shutdown",
        "drivers/nvme/host/pci.c:nvme_reset_prepare",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_timeout",
        "drivers/nvme/host/pci.c:nvme_timeout",
        "drivers/nvme/host/pci.c:nvme_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586511520,
      "name": "nvme_dev_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1259
    },
    {
      "addr": 18446744071586518248,
      "name": "nvme_dev_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void nvme_dev_disable(struct nvme_dev * dev, bool shutdown)
```

```json
{
  "name": "nvme_dev_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvme_dev_disable",
      "external": false,
      "loc": "drivers/nvme/host/pci.c:2415",
      "file": "drivers/nvme/host/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvme/host/pci.c:nvme_error_detected",
        "drivers/nvme/host/pci.c:nvme_simple_suspend",
        "drivers/nvme/host/pci.c:nvme_suspend",
        "drivers/nvme/host/pci.c:nvme_suspend",
        "drivers/nvme/host/pci.c:nvme_remove",
        "drivers/nvme/host/pci.c:nvme_remove",
        "drivers/nvme/host/pci.c:nvme_shutdown",
        "drivers/nvme/host/pci.c:nvme_reset_prepare",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_timeout",
        "drivers/nvme/host/pci.c:nvme_timeout",
        "drivers/nvme/host/pci.c:nvme_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586380096,
      "name": "nvme_dev_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1259
    },
    {
      "addr": 18446744071586386824,
      "name": "nvme_dev_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void nvme_dev_disable(struct nvme_dev * dev, bool shutdown)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
void nvme_dev_disable(struct nvme_dev * dev, bool shutdown)
```
</details>
</li>
</ul>
