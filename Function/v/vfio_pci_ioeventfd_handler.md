# Function: <code>vfio_pci_ioeventfd_handler</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfio_pci_ioeventfd_handler(void * opaque, void * unused)
```

```json
{
  "name": "vfio_pci_ioeventfd_handler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587075776,
      "name": "vfio_pci_ioeventfd_handler",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:277",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587075776,
      "name": "vfio_pci_ioeventfd_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int vfio_pci_ioeventfd_handler(void * opaque, void * unused)
```

```json
{
  "name": "vfio_pci_ioeventfd_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587918176,
      "name": "vfio_pci_ioeventfd_handler",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:359",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587918176,
      "name": "vfio_pci_ioeventfd_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
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
int vfio_pci_ioeventfd_handler(void * opaque, void * unused)
```

```json
{
  "name": "vfio_pci_ioeventfd_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587979664,
      "name": "vfio_pci_ioeventfd_handler",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:384",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587979664,
      "name": "vfio_pci_ioeventfd_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int vfio_pci_ioeventfd_handler(void * opaque, void * unused)
```

```json
{
  "name": "vfio_pci_ioeventfd_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587862096,
      "name": "vfio_pci_ioeventfd_handler",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:384",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587862096,
      "name": "vfio_pci_ioeventfd_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int vfio_pci_ioeventfd_handler(void * opaque, void * unused)
```

```json
{
  "name": "vfio_pci_ioeventfd_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_ioeventfd_handler",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:384",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588467168,
      "name": "vfio_pci_ioeventfd_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071592551641,
      "name": "vfio_pci_ioeventfd_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int vfio_pci_ioeventfd_handler(void * opaque, void * unused)
```

```json
{
  "name": "vfio_pci_ioeventfd_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_ioeventfd_handler",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:386",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589869952,
      "name": "vfio_pci_ioeventfd_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071594430977,
      "name": "vfio_pci_ioeventfd_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int vfio_pci_ioeventfd_handler(void * opaque, void * unused)
```

```json
{
  "name": "vfio_pci_ioeventfd_handler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293409904,
      "name": "vfio_pci_ioeventfd_handler",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:277",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293409904,
      "name": "vfio_pci_ioeventfd_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int vfio_pci_ioeventfd_handler(void * opaque, void * unused)
```

```json
{
  "name": "vfio_pci_ioeventfd_handler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586723696,
      "name": "vfio_pci_ioeventfd_handler",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:277",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586723696,
      "name": "vfio_pci_ioeventfd_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int vfio_pci_ioeventfd_handler(void * opaque, void * unused)
```

```json
{
  "name": "vfio_pci_ioeventfd_handler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587030336,
      "name": "vfio_pci_ioeventfd_handler",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:277",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587030336,
      "name": "vfio_pci_ioeventfd_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int vfio_pci_ioeventfd_handler(void * opaque, void * unused)
```

```json
{
  "name": "vfio_pci_ioeventfd_handler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587137504,
      "name": "vfio_pci_ioeventfd_handler",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:277",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587137504,
      "name": "vfio_pci_ioeventfd_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int vfio_pci_ioeventfd_handler(void * opaque, void * unused)
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
int vfio_pci_ioeventfd_handler(void * opaque, void * unused)
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
int vfio_pci_ioeventfd_handler(void * opaque, void * unused)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int vfio_pci_ioeventfd_handler(void * opaque, void * unused)
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
int vfio_pci_ioeventfd_handler(void * opaque, void * unused)
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
int vfio_pci_ioeventfd_handler(void * opaque, void * unused)
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
