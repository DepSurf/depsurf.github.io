# Function: <code>vfio_user_config_read</code>

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
int vfio_user_config_read(struct pci_dev * pdev, int offset, __le32 * val, int count)
```

```json
{
  "name": "vfio_user_config_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587077680,
      "name": "vfio_user_config_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:122",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587077680,
      "name": "vfio_user_config_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int vfio_user_config_read(struct pci_dev * pdev, int offset, __le32 * val, int count)
```

```json
{
  "name": "vfio_user_config_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587928295,
      "name": "vfio_user_config_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:122",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read"
      ],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587921936,
      "name": "vfio_user_config_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int vfio_user_config_read(struct pci_dev * pdev, int offset, __le32 * val, int count)
```

```json
{
  "name": "vfio_user_config_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587989527,
      "name": "vfio_user_config_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:122",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read"
      ],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587982944,
      "name": "vfio_user_config_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int vfio_user_config_read(struct pci_dev * pdev, int offset, __le32 * val, int count)
```

```json
{
  "name": "vfio_user_config_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587871928,
      "name": "vfio_user_config_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:122",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read"
      ],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587865376,
      "name": "vfio_user_config_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int vfio_user_config_read(struct pci_dev * pdev, int offset, __le32 * val, int count)
```

```json
{
  "name": "vfio_user_config_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588478440,
      "name": "vfio_user_config_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:122",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read"
      ],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588471136,
      "name": "vfio_user_config_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int vfio_user_config_read(struct pci_dev * pdev, int offset, __le32 * val, int count)
```

```json
{
  "name": "vfio_user_config_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589883035,
      "name": "vfio_user_config_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:122",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_direct_config_read"
      ],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589873952,
      "name": "vfio_user_config_read",
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
int vfio_user_config_read(struct pci_dev * pdev, int offset, __le32 * val, int count)
```

```json
{
  "name": "vfio_user_config_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293412272,
      "name": "vfio_user_config_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:122",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293412272,
      "name": "vfio_user_config_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int vfio_user_config_read(struct pci_dev * pdev, int offset, __le32 * val, int count)
```

```json
{
  "name": "vfio_user_config_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586725600,
      "name": "vfio_user_config_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:122",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586725600,
      "name": "vfio_user_config_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int vfio_user_config_read(struct pci_dev * pdev, int offset, __le32 * val, int count)
```

```json
{
  "name": "vfio_user_config_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587032240,
      "name": "vfio_user_config_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:122",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587032240,
      "name": "vfio_user_config_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int vfio_user_config_read(struct pci_dev * pdev, int offset, __le32 * val, int count)
```

```json
{
  "name": "vfio_user_config_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587139408,
      "name": "vfio_user_config_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:122",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587139408,
      "name": "vfio_user_config_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int vfio_user_config_read(struct pci_dev * pdev, int offset, __le32 * val, int count)
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
int vfio_user_config_read(struct pci_dev * pdev, int offset, __le32 * val, int count)
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
int vfio_user_config_read(struct pci_dev * pdev, int offset, __le32 * val, int count)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int vfio_user_config_read(struct pci_dev * pdev, int offset, __le32 * val, int count)
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
int vfio_user_config_read(struct pci_dev * pdev, int offset, __le32 * val, int count)
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
int vfio_user_config_read(struct pci_dev * pdev, int offset, __le32 * val, int count)
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
