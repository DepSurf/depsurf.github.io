# Function: <code>vfio_virqfd_enable</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int vfio_virqfd_enable(void * opaque, int (*)(void *, void *) handler, void (*)(void *, void *) thread, void * data, struct virqfd * * pvirqfd, int fd)
```

```json
{
  "name": "vfio_virqfd_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587047344,
      "name": "vfio_virqfd_enable",
      "external": true,
      "loc": "drivers/vfio/virqfd.c:104",
      "file": "drivers/vfio/virqfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587047344,
      "name": "vfio_virqfd_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int vfio_virqfd_enable(void * opaque, int (*)(void *, void *) handler, void (*)(void *, void *) thread, void * data, struct virqfd * * pvirqfd, int fd)
```

```json
{
  "name": "vfio_virqfd_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587879184,
      "name": "vfio_virqfd_enable",
      "external": true,
      "loc": "drivers/vfio/virqfd.c:104",
      "file": "drivers/vfio/virqfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587879184,
      "name": "vfio_virqfd_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int vfio_virqfd_enable(void * opaque, int (*)(void *, void *) handler, void (*)(void *, void *) thread, void * data, struct virqfd * * pvirqfd, int fd)
```

```json
{
  "name": "vfio_virqfd_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587939632,
      "name": "vfio_virqfd_enable",
      "external": true,
      "loc": "drivers/vfio/virqfd.c:107",
      "file": "drivers/vfio/virqfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587939632,
      "name": "vfio_virqfd_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int vfio_virqfd_enable(void * opaque, int (*)(void *, void *) handler, void (*)(void *, void *) thread, void * data, struct virqfd * * pvirqfd, int fd)
```

```json
{
  "name": "vfio_virqfd_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587821136,
      "name": "vfio_virqfd_enable",
      "external": true,
      "loc": "drivers/vfio/virqfd.c:107",
      "file": "drivers/vfio/virqfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587821136,
      "name": "vfio_virqfd_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int vfio_virqfd_enable(void * opaque, int (*)(void *, void *) handler, void (*)(void *, void *) thread, void * data, struct virqfd * * pvirqfd, int fd)
```

```json
{
  "name": "vfio_virqfd_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588425552,
      "name": "vfio_virqfd_enable",
      "external": true,
      "loc": "drivers/vfio/virqfd.c:107",
      "file": "drivers/vfio/virqfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588425552,
      "name": "vfio_virqfd_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int vfio_virqfd_enable(void * opaque, int (*)(void *, void *) handler, void (*)(void *, void *) thread, void * data, struct virqfd * * pvirqfd, int fd)
```

```json
{
  "name": "vfio_virqfd_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589824848,
      "name": "vfio_virqfd_enable",
      "external": true,
      "loc": "drivers/vfio/virqfd.c:107",
      "file": "drivers/vfio/virqfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_unmask",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589824848,
      "name": "vfio_virqfd_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int vfio_virqfd_enable(void * opaque, int (*)(void *, void *) handler, void (*)(void *, void *) thread, void * data, struct virqfd * * pvirqfd, int fd)
```

```json
{
  "name": "vfio_virqfd_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293377264,
      "name": "vfio_virqfd_enable",
      "external": true,
      "loc": "drivers/vfio/virqfd.c:104",
      "file": "drivers/vfio/virqfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293377264,
      "name": "vfio_virqfd_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 900
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int vfio_virqfd_enable(void * opaque, int (*)(void *, void *) handler, void (*)(void *, void *) thread, void * data, struct virqfd * * pvirqfd, int fd)
```

```json
{
  "name": "vfio_virqfd_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586695264,
      "name": "vfio_virqfd_enable",
      "external": true,
      "loc": "drivers/vfio/virqfd.c:104",
      "file": "drivers/vfio/virqfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586695264,
      "name": "vfio_virqfd_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int vfio_virqfd_enable(void * opaque, int (*)(void *, void *) handler, void (*)(void *, void *) thread, void * data, struct virqfd * * pvirqfd, int fd)
```

```json
{
  "name": "vfio_virqfd_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587001904,
      "name": "vfio_virqfd_enable",
      "external": true,
      "loc": "drivers/vfio/virqfd.c:104",
      "file": "drivers/vfio/virqfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587001904,
      "name": "vfio_virqfd_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int vfio_virqfd_enable(void * opaque, int (*)(void *, void *) handler, void (*)(void *, void *) thread, void * data, struct virqfd * * pvirqfd, int fd)
```

```json
{
  "name": "vfio_virqfd_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587108960,
      "name": "vfio_virqfd_enable",
      "external": true,
      "loc": "drivers/vfio/virqfd.c:104",
      "file": "drivers/vfio/virqfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587108960,
      "name": "vfio_virqfd_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 517
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int vfio_virqfd_enable(void * opaque, int (*)(void *, void *) handler, void (*)(void *, void *) thread, void * data, struct virqfd * * pvirqfd, int fd)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int vfio_virqfd_enable(void * opaque, int (*)(void *, void *) handler, void (*)(void *, void *) thread, void * data, struct virqfd * * pvirqfd, int fd)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int vfio_virqfd_enable(void * opaque, int (*)(void *, void *) handler, void (*)(void *, void *) thread, void * data, struct virqfd * * pvirqfd, int fd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int vfio_virqfd_enable(void * opaque, int (*)(void *, void *) handler, void (*)(void *, void *) thread, void * data, struct virqfd * * pvirqfd, int fd)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int vfio_virqfd_enable(void * opaque, int (*)(void *, void *) handler, void (*)(void *, void *) thread, void * data, struct virqfd * * pvirqfd, int fd)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int vfio_virqfd_enable(void * opaque, int (*)(void *, void *) handler, void (*)(void *, void *) thread, void * data, struct virqfd * * pvirqfd, int fd)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
