# Function: <code>virtio_pci_sriov_configure</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int virtio_pci_sriov_configure(struct pci_dev * pci_dev, int num_vfs)
```

```json
{
  "name": "virtio_pci_sriov_configure",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585065440,
      "name": "virtio_pci_sriov_configure",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:594",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585065440,
      "name": "virtio_pci_sriov_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int virtio_pci_sriov_configure(struct pci_dev * pci_dev, int num_vfs)
```

```json
{
  "name": "virtio_pci_sriov_configure",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585173728,
      "name": "virtio_pci_sriov_configure",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:593",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585173728,
      "name": "virtio_pci_sriov_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int virtio_pci_sriov_configure(struct pci_dev * pci_dev, int num_vfs)
```

```json
{
  "name": "virtio_pci_sriov_configure",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585386304,
      "name": "virtio_pci_sriov_configure",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:592",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585386304,
      "name": "virtio_pci_sriov_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int virtio_pci_sriov_configure(struct pci_dev * pci_dev, int num_vfs)
```

```json
{
  "name": "virtio_pci_sriov_configure",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585526816,
      "name": "virtio_pci_sriov_configure",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:592",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585526816,
      "name": "virtio_pci_sriov_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int virtio_pci_sriov_configure(struct pci_dev * pci_dev, int num_vfs)
```

```json
{
  "name": "virtio_pci_sriov_configure",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586243712,
      "name": "virtio_pci_sriov_configure",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:592",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586243712,
      "name": "virtio_pci_sriov_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int virtio_pci_sriov_configure(struct pci_dev * pci_dev, int num_vfs)
```

```json
{
  "name": "virtio_pci_sriov_configure",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586361936,
      "name": "virtio_pci_sriov_configure",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:592",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586361936,
      "name": "virtio_pci_sriov_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int virtio_pci_sriov_configure(struct pci_dev * pci_dev, int num_vfs)
```

```json
{
  "name": "virtio_pci_sriov_configure",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586246608,
      "name": "virtio_pci_sriov_configure",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:599",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586246608,
      "name": "virtio_pci_sriov_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int virtio_pci_sriov_configure(struct pci_dev * pci_dev, int num_vfs)
```

```json
{
  "name": "virtio_pci_sriov_configure",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586756864,
      "name": "virtio_pci_sriov_configure",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:599",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586756864,
      "name": "virtio_pci_sriov_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int virtio_pci_sriov_configure(struct pci_dev * pci_dev, int num_vfs)
```

```json
{
  "name": "virtio_pci_sriov_configure",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588033680,
      "name": "virtio_pci_sriov_configure",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:600",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588033680,
      "name": "virtio_pci_sriov_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
int virtio_pci_sriov_configure(struct pci_dev * pci_dev, int num_vfs)
```

```json
{
  "name": "virtio_pci_sriov_configure",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589411520,
      "name": "virtio_pci_sriov_configure",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:609",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589411520,
      "name": "virtio_pci_sriov_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
int virtio_pci_sriov_configure(struct pci_dev * pci_dev, int num_vfs)
```

```json
{
  "name": "virtio_pci_sriov_configure",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589710624,
      "name": "virtio_pci_sriov_configure",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:607",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589710624,
      "name": "virtio_pci_sriov_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int virtio_pci_sriov_configure(struct pci_dev * pci_dev, int num_vfs)
```

```json
{
  "name": "virtio_pci_sriov_configure",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590045952,
      "name": "virtio_pci_sriov_configure",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:642",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590045952,
      "name": "virtio_pci_sriov_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int virtio_pci_sriov_configure(struct pci_dev * pci_dev, int num_vfs)
```

```json
{
  "name": "virtio_pci_sriov_configure",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498184664,
      "name": "virtio_pci_sriov_configure",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:592",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498184664,
      "name": "virtio_pci_sriov_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int virtio_pci_sriov_configure(struct pci_dev * pci_dev, int num_vfs)
```

```json
{
  "name": "virtio_pci_sriov_configure",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230949892,
      "name": "virtio_pci_sriov_configure",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:592",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230949892,
      "name": "virtio_pci_sriov_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int virtio_pci_sriov_configure(struct pci_dev * pci_dev, int num_vfs)
```

```json
{
  "name": "virtio_pci_sriov_configure",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291422288,
      "name": "virtio_pci_sriov_configure",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:592",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291422288,
      "name": "virtio_pci_sriov_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int virtio_pci_sriov_configure(struct pci_dev * pci_dev, int num_vfs)
```

```json
{
  "name": "virtio_pci_sriov_configure",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275965938,
      "name": "virtio_pci_sriov_configure",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:592",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275965938,
      "name": "virtio_pci_sriov_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int virtio_pci_sriov_configure(struct pci_dev * pci_dev, int num_vfs)
```

```json
{
  "name": "virtio_pci_sriov_configure",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585288848,
      "name": "virtio_pci_sriov_configure",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:592",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585288848,
      "name": "virtio_pci_sriov_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int virtio_pci_sriov_configure(struct pci_dev * pci_dev, int num_vfs)
```

```json
{
  "name": "virtio_pci_sriov_configure",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585241360,
      "name": "virtio_pci_sriov_configure",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:592",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585241360,
      "name": "virtio_pci_sriov_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int virtio_pci_sriov_configure(struct pci_dev * pci_dev, int num_vfs)
```

```json
{
  "name": "virtio_pci_sriov_configure",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585477216,
      "name": "virtio_pci_sriov_configure",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:592",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585477216,
      "name": "virtio_pci_sriov_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int virtio_pci_sriov_configure(struct pci_dev * pci_dev, int num_vfs)
```

```json
{
  "name": "virtio_pci_sriov_configure",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585585392,
      "name": "virtio_pci_sriov_configure",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:592",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585585392,
      "name": "virtio_pci_sriov_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int virtio_pci_sriov_configure(struct pci_dev * pci_dev, int num_vfs)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
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
