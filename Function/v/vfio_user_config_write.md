# Function: <code>vfio_user_config_write</code>

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
int vfio_user_config_write(struct pci_dev * pdev, int offset, __le32 val, int count)
```

```json
{
  "name": "vfio_user_config_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587078976,
      "name": "vfio_user_config_write",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:153",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587078976,
      "name": "vfio_user_config_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfio_user_config_write(struct pci_dev * pdev, int offset, __le32 val, int count)
```

```json
{
  "name": "vfio_user_config_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587926045,
      "name": "vfio_user_config_write",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:153",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write"
      ],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587922464,
      "name": "vfio_user_config_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfio_user_config_write(struct pci_dev * pdev, int offset, __le32 val, int count)
```

```json
{
  "name": "vfio_user_config_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587987277,
      "name": "vfio_user_config_write",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:153",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write"
      ],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587983440,
      "name": "vfio_user_config_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfio_user_config_write(struct pci_dev * pdev, int offset, __le32 val, int count)
```

```json
{
  "name": "vfio_user_config_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587869614,
      "name": "vfio_user_config_write",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:153",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write"
      ],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587865888,
      "name": "vfio_user_config_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfio_user_config_write(struct pci_dev * pdev, int offset, __le32 val, int count)
```

```json
{
  "name": "vfio_user_config_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588476078,
      "name": "vfio_user_config_write",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:153",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write"
      ],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588471408,
      "name": "vfio_user_config_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfio_user_config_write(struct pci_dev * pdev, int offset, __le32 val, int count)
```

```json
{
  "name": "vfio_user_config_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589879345,
      "name": "vfio_user_config_write",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:153",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write"
      ],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589874256,
      "name": "vfio_user_config_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
int vfio_user_config_write(struct pci_dev * pdev, int offset, __le32 val, int count)
```

```json
{
  "name": "vfio_user_config_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293413408,
      "name": "vfio_user_config_write",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:153",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293413408,
      "name": "vfio_user_config_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int vfio_user_config_write(struct pci_dev * pdev, int offset, __le32 val, int count)
```

```json
{
  "name": "vfio_user_config_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586726896,
      "name": "vfio_user_config_write",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:153",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586726896,
      "name": "vfio_user_config_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int vfio_user_config_write(struct pci_dev * pdev, int offset, __le32 val, int count)
```

```json
{
  "name": "vfio_user_config_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587033536,
      "name": "vfio_user_config_write",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:153",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587033536,
      "name": "vfio_user_config_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int vfio_user_config_write(struct pci_dev * pdev, int offset, __le32 val, int count)
```

```json
{
  "name": "vfio_user_config_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587140704,
      "name": "vfio_user_config_write",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:153",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587140704,
      "name": "vfio_user_config_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int vfio_user_config_write(struct pci_dev * pdev, int offset, __le32 val, int count)
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
int vfio_user_config_write(struct pci_dev * pdev, int offset, __le32 val, int count)
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
int vfio_user_config_write(struct pci_dev * pdev, int offset, __le32 val, int count)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int vfio_user_config_write(struct pci_dev * pdev, int offset, __le32 val, int count)
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
int vfio_user_config_write(struct pci_dev * pdev, int offset, __le32 val, int count)
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
int vfio_user_config_write(struct pci_dev * pdev, int offset, __le32 val, int count)
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
