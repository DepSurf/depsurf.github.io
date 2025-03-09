# Function: <code>vfio_intx_handler</code>

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
irqreturn_t vfio_intx_handler(int irq, void * dev_id)
```

```json
{
  "name": "vfio_intx_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587073072,
      "name": "vfio_intx_handler",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:116",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587073072,
      "name": "vfio_intx_handler",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
irqreturn_t vfio_intx_handler(int irq, void * dev_id)
```

```json
{
  "name": "vfio_intx_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587916320,
      "name": "vfio_intx_handler",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:116",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587916320,
      "name": "vfio_intx_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
irqreturn_t vfio_intx_handler(int irq, void * dev_id)
```

```json
{
  "name": "vfio_intx_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587977488,
      "name": "vfio_intx_handler",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:116",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587977488,
      "name": "vfio_intx_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
irqreturn_t vfio_intx_handler(int irq, void * dev_id)
```

```json
{
  "name": "vfio_intx_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587859904,
      "name": "vfio_intx_handler",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:116",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587859904,
      "name": "vfio_intx_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
irqreturn_t vfio_intx_handler(int irq, void * dev_id)
```

```json
{
  "name": "vfio_intx_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_intx_handler",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:116",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588464592,
      "name": "vfio_intx_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    },
    {
      "addr": 18446744071592551256,
      "name": "vfio_intx_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
irqreturn_t vfio_intx_handler(int irq, void * dev_id)
```

```json
{
  "name": "vfio_intx_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_intx_handler",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:116",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589867072,
      "name": "vfio_intx_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
    },
    {
      "addr": 18446744071594430606,
      "name": "vfio_intx_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
irqreturn_t vfio_intx_handler(int irq, void * dev_id)
```

```json
{
  "name": "vfio_intx_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293405216,
      "name": "vfio_intx_handler",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:116",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293405216,
      "name": "vfio_intx_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
irqreturn_t vfio_intx_handler(int irq, void * dev_id)
```

```json
{
  "name": "vfio_intx_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586720992,
      "name": "vfio_intx_handler",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:116",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586720992,
      "name": "vfio_intx_handler",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
irqreturn_t vfio_intx_handler(int irq, void * dev_id)
```

```json
{
  "name": "vfio_intx_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587027632,
      "name": "vfio_intx_handler",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:116",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587027632,
      "name": "vfio_intx_handler",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
irqreturn_t vfio_intx_handler(int irq, void * dev_id)
```

```json
{
  "name": "vfio_intx_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587134800,
      "name": "vfio_intx_handler",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:116",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587134800,
      "name": "vfio_intx_handler",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
irqreturn_t vfio_intx_handler(int irq, void * dev_id)
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
irqreturn_t vfio_intx_handler(int irq, void * dev_id)
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
irqreturn_t vfio_intx_handler(int irq, void * dev_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
irqreturn_t vfio_intx_handler(int irq, void * dev_id)
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
irqreturn_t vfio_intx_handler(int irq, void * dev_id)
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
irqreturn_t vfio_intx_handler(int irq, void * dev_id)
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
