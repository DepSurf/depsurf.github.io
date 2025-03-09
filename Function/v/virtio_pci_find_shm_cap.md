# Function: <code>virtio_pci_find_shm_cap</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int virtio_pci_find_shm_cap(struct pci_dev * dev, u8 required_id, u8 * bar, u64 * offset, u64 * len)
```

```json
{
  "name": "virtio_pci_find_shm_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtio_pci_find_shm_cap",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:447",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_get_shm_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586356928,
      "name": "virtio_pci_find_shm_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    },
    {
      "addr": 18446744071591446477,
      "name": "virtio_pci_find_shm_cap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtio_pci_find_shm_cap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586244535,
      "name": "virtio_pci_find_shm_cap",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:289",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:vp_get_shm_region"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtio_pci_find_shm_cap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586754631,
      "name": "virtio_pci_find_shm_cap",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:289",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:vp_get_shm_region"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int virtio_pci_find_shm_cap(struct pci_dev * dev, u8 required_id, u8 * bar, u64 * offset, u64 * len)
```

```json
{
  "name": "virtio_pci_find_shm_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtio_pci_find_shm_cap",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:289",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_get_shm_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588030960,
      "name": "virtio_pci_find_shm_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
    },
    {
      "addr": 18446744071594299752,
      "name": "virtio_pci_find_shm_cap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int virtio_pci_find_shm_cap(struct pci_dev * dev, u8 required_id, u8 * bar, u64 * offset, u64 * len)
```

```json
{
  "name": "virtio_pci_find_shm_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589407808,
      "name": "virtio_pci_find_shm_cap",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:385",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_get_shm_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589407808,
      "name": "virtio_pci_find_shm_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
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
int virtio_pci_find_shm_cap(struct pci_dev * dev, u8 required_id, u8 * bar, u64 * offset, u64 * len)
```

```json
{
  "name": "virtio_pci_find_shm_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589706928,
      "name": "virtio_pci_find_shm_cap",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:395",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_get_shm_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589706928,
      "name": "virtio_pci_find_shm_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
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
int virtio_pci_find_shm_cap(struct pci_dev * dev, u8 required_id, u8 * bar, u64 * offset, u64 * len)
```

```json
{
  "name": "virtio_pci_find_shm_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590039360,
      "name": "virtio_pci_find_shm_cap",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:640",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_get_shm_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590039360,
      "name": "virtio_pci_find_shm_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int virtio_pci_find_shm_cap(struct pci_dev * dev, u8 required_id, u8 * bar, u64 * offset, u64 * len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int virtio_pci_find_shm_cap(struct pci_dev * dev, u8 required_id, u8 * bar, u64 * offset, u64 * len)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int virtio_pci_find_shm_cap(struct pci_dev * dev, u8 required_id, u8 * bar, u64 * offset, u64 * len)
```
</details>
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
