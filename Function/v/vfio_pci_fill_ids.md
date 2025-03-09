# Function: <code>vfio_pci_fill_ids</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_pci_fill_ids",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605111316,
      "name": "vfio_pci_fill_ids",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1636",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_init"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void vfio_pci_fill_ids()
```

```json
{
  "name": "vfio_pci_fill_ids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609390531,
      "name": "vfio_pci_fill_ids",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:2291",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609390531,
      "name": "vfio_pci_fill_ids",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 310
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
void vfio_pci_fill_ids()
```

```json
{
  "name": "vfio_pci_fill_ids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612461998,
      "name": "vfio_pci_fill_ids",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:2369",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612461998,
      "name": "vfio_pci_fill_ids",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 310
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
void vfio_pci_fill_ids()
```

```json
{
  "name": "vfio_pci_fill_ids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614604258,
      "name": "vfio_pci_fill_ids",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:2388",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614604258,
      "name": "vfio_pci_fill_ids",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 310
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
void vfio_pci_fill_ids()
```

```json
{
  "name": "vfio_pci_fill_ids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615562654,
      "name": "vfio_pci_fill_ids",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:198",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615562654,
      "name": "vfio_pci_fill_ids",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 310
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
void vfio_pci_fill_ids()
```

```json
{
  "name": "vfio_pci_fill_ids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617369036,
      "name": "vfio_pci_fill_ids",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:202",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617369036,
      "name": "vfio_pci_fill_ids",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 349
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "vfio_pci_fill_ids",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302809224,
      "name": "vfio_pci_fill_ids",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1636",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_init"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_pci_fill_ids",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604975772,
      "name": "vfio_pci_fill_ids",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1636",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_init"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_pci_fill_ids",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605091855,
      "name": "vfio_pci_fill_ids",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1636",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_init"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_pci_fill_ids",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605115510,
      "name": "vfio_pci_fill_ids",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1636",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void vfio_pci_fill_ids()
```
</details>
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
void vfio_pci_fill_ids()
```
</details>
</li>
</ul>
