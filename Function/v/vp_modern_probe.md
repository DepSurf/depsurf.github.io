# Function: <code>vp_modern_probe</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int vp_modern_probe(struct virtio_pci_modern_device * mdev)
```

```json
{
  "name": "vp_modern_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vp_modern_probe",
      "external": true,
      "loc": "drivers/virtio/virtio_pci_modern_dev.c:207",
      "file": "drivers/virtio/virtio_pci_modern_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591387980,
      "name": "vp_modern_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071586239120,
      "name": "vp_modern_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1465
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int vp_modern_probe(struct virtio_pci_modern_device * mdev)
```

```json
{
  "name": "vp_modern_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vp_modern_probe",
      "external": true,
      "loc": "drivers/virtio/virtio_pci_modern_dev.c:207",
      "file": "drivers/virtio/virtio_pci_modern_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592431174,
      "name": "vp_modern_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071586748480,
      "name": "vp_modern_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int vp_modern_probe(struct virtio_pci_modern_device * mdev)
```

```json
{
  "name": "vp_modern_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vp_modern_probe",
      "external": true,
      "loc": "drivers/virtio/virtio_pci_modern_dev.c:214",
      "file": "drivers/virtio/virtio_pci_modern_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594299279,
      "name": "vp_modern_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588023200,
      "name": "vp_modern_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int vp_modern_probe(struct virtio_pci_modern_device * mdev)
```

```json
{
  "name": "vp_modern_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589398816,
      "name": "vp_modern_probe",
      "external": true,
      "loc": "drivers/virtio/virtio_pci_modern_dev.c:215",
      "file": "drivers/virtio/virtio_pci_modern_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589398816,
      "name": "vp_modern_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2325
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
int vp_modern_probe(struct virtio_pci_modern_device * mdev)
```

```json
{
  "name": "vp_modern_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589697904,
      "name": "vp_modern_probe",
      "external": true,
      "loc": "drivers/virtio/virtio_pci_modern_dev.c:215",
      "file": "drivers/virtio/virtio_pci_modern_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589697904,
      "name": "vp_modern_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2195
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
int vp_modern_probe(struct virtio_pci_modern_device * mdev)
```

```json
{
  "name": "vp_modern_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590030768,
      "name": "vp_modern_probe",
      "external": true,
      "loc": "drivers/virtio/virtio_pci_modern_dev.c:223",
      "file": "drivers/virtio/virtio_pci_modern_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590030768,
      "name": "vp_modern_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2198
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int vp_modern_probe(struct virtio_pci_modern_device * mdev)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
