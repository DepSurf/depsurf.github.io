# Function: <code>ahci_platform_disable_resources</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void ahci_platform_disable_resources(struct ahci_host_priv * hpriv)
```

```json
{
  "name": "ahci_platform_disable_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499842640,
      "name": "ahci_platform_disable_resources",
      "external": true,
      "loc": "drivers/ata/libahci_platform.c:273",
      "file": "drivers/ata/libahci_platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libahci_platform.c:ahci_platform_suspend",
        "drivers/ata/libahci_platform.c:ahci_host_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499842640,
      "name": "ahci_platform_disable_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void ahci_platform_disable_resources(struct ahci_host_priv * hpriv)
```

```json
{
  "name": "ahci_platform_disable_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232267200,
      "name": "ahci_platform_disable_resources",
      "external": true,
      "loc": "drivers/ata/libahci_platform.c:273",
      "file": "drivers/ata/libahci_platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/ahci_platform.c:ahci_probe",
        "drivers/ata/libahci_platform.c:ahci_platform_suspend",
        "drivers/ata/libahci_platform.c:ahci_host_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232267200,
      "name": "ahci_platform_disable_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void ahci_platform_disable_resources(struct ahci_host_priv * hpriv)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void ahci_platform_disable_resources(struct ahci_host_priv * hpriv)
```
</details>
</li>
</ul>
