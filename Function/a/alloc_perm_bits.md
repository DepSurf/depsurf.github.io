# Function: <code>alloc_perm_bits</code>

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
int alloc_perm_bits(struct perm_bits * perm, int size)
```

```json
{
  "name": "alloc_perm_bits",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587082544,
      "name": "alloc_perm_bits",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:346",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587082544,
      "name": "alloc_perm_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int alloc_perm_bits(struct perm_bits * perm, int size)
```

```json
{
  "name": "alloc_perm_bits",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587926272,
      "name": "alloc_perm_bits",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:346",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587926272,
      "name": "alloc_perm_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int alloc_perm_bits(struct perm_bits * perm, int size)
```

```json
{
  "name": "alloc_perm_bits",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587987504,
      "name": "alloc_perm_bits",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:346",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587987504,
      "name": "alloc_perm_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int alloc_perm_bits(struct perm_bits * perm, int size)
```

```json
{
  "name": "alloc_perm_bits",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587869696,
      "name": "alloc_perm_bits",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:346",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587869696,
      "name": "alloc_perm_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int alloc_perm_bits(struct perm_bits * perm, int size)
```

```json
{
  "name": "alloc_perm_bits",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588476160,
      "name": "alloc_perm_bits",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:346",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588476160,
      "name": "alloc_perm_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int alloc_perm_bits(struct perm_bits * perm, int size)
```

```json
{
  "name": "alloc_perm_bits",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589879440,
      "name": "alloc_perm_bits",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:346",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589879440,
      "name": "alloc_perm_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int alloc_perm_bits(struct perm_bits * perm, int size)
```

```json
{
  "name": "alloc_perm_bits",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293419856,
      "name": "alloc_perm_bits",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:346",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293419856,
      "name": "alloc_perm_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int alloc_perm_bits(struct perm_bits * perm, int size)
```

```json
{
  "name": "alloc_perm_bits",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586730464,
      "name": "alloc_perm_bits",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:346",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586730464,
      "name": "alloc_perm_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int alloc_perm_bits(struct perm_bits * perm, int size)
```

```json
{
  "name": "alloc_perm_bits",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587037104,
      "name": "alloc_perm_bits",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:346",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587037104,
      "name": "alloc_perm_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int alloc_perm_bits(struct perm_bits * perm, int size)
```

```json
{
  "name": "alloc_perm_bits",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587144272,
      "name": "alloc_perm_bits",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:346",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587144272,
      "name": "alloc_perm_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int alloc_perm_bits(struct perm_bits * perm, int size)
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
int alloc_perm_bits(struct perm_bits * perm, int size)
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
int alloc_perm_bits(struct perm_bits * perm, int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int alloc_perm_bits(struct perm_bits * perm, int size)
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
int alloc_perm_bits(struct perm_bits * perm, int size)
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
int alloc_perm_bits(struct perm_bits * perm, int size)
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
