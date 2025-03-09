# Function: <code>aperture_remove_conflicting_pci_devices</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int aperture_remove_conflicting_pci_devices(struct pci_dev * pdev, const char * name)
```

```json
{
  "name": "aperture_remove_conflicting_pci_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588473632,
      "name": "aperture_remove_conflicting_pci_devices",
      "external": true,
      "loc": "drivers/video/aperture.c:325",
      "file": "drivers/video/aperture.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:resource5_resize_store",
        "drivers/pci/pci-sysfs.c:resource4_resize_store",
        "drivers/pci/pci-sysfs.c:resource3_resize_store",
        "drivers/pci/pci-sysfs.c:resource2_resize_store",
        "drivers/pci/pci-sysfs.c:resource1_resize_store",
        "drivers/pci/pci-sysfs.c:resource0_resize_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588473632,
      "name": "aperture_remove_conflicting_pci_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int aperture_remove_conflicting_pci_devices(struct pci_dev * pdev, const char * name)
```

```json
{
  "name": "aperture_remove_conflicting_pci_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588752864,
      "name": "aperture_remove_conflicting_pci_devices",
      "external": true,
      "loc": "drivers/video/aperture.c:347",
      "file": "drivers/video/aperture.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:resource5_resize_store",
        "drivers/pci/pci-sysfs.c:resource4_resize_store",
        "drivers/pci/pci-sysfs.c:resource3_resize_store",
        "drivers/pci/pci-sysfs.c:resource2_resize_store",
        "drivers/pci/pci-sysfs.c:resource1_resize_store",
        "drivers/pci/pci-sysfs.c:resource0_resize_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588752864,
      "name": "aperture_remove_conflicting_pci_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int aperture_remove_conflicting_pci_devices(struct pci_dev * pdev, const char * name)
```

```json
{
  "name": "aperture_remove_conflicting_pci_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589056080,
      "name": "aperture_remove_conflicting_pci_devices",
      "external": true,
      "loc": "drivers/video/aperture.c:347",
      "file": "drivers/video/aperture.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:resource5_resize_store",
        "drivers/pci/pci-sysfs.c:resource4_resize_store",
        "drivers/pci/pci-sysfs.c:resource3_resize_store",
        "drivers/pci/pci-sysfs.c:resource2_resize_store",
        "drivers/pci/pci-sysfs.c:resource1_resize_store",
        "drivers/pci/pci-sysfs.c:resource0_resize_store",
        "drivers/gpu/drm/drm_aperture.c:drm_aperture_remove_conflicting_pci_framebuffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589056080,
      "name": "aperture_remove_conflicting_pci_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
    }
  ]
}
```
</details>
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int aperture_remove_conflicting_pci_devices(struct pci_dev * pdev, const char * name)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
