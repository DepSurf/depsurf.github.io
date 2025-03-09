# Function: <code>pci_has_p2pmem</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pci_has_p2pmem(struct pci_dev * pdev)
```

```json
{
  "name": "pci_has_p2pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588401736,
      "name": "pci_has_p2pmem",
      "external": true,
      "loc": "drivers/pci/p2pdma.c:731",
      "file": "drivers/pci/p2pdma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:pci_p2pdma_enable_store",
        "drivers/pci/p2pdma.c:pci_p2pmem_find_many"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596212010,
      "name": "pci_has_p2pmem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588395936,
      "name": "pci_has_p2pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pci_has_p2pmem(struct pci_dev * pdev)
```

```json
{
  "name": "pci_has_p2pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588677640,
      "name": "pci_has_p2pmem",
      "external": true,
      "loc": "drivers/pci/p2pdma.c:733",
      "file": "drivers/pci/p2pdma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:pci_p2pdma_enable_store",
        "drivers/pci/p2pdma.c:pci_p2pmem_find_many"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596737165,
      "name": "pci_has_p2pmem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588671920,
      "name": "pci_has_p2pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pci_has_p2pmem(struct pci_dev * pdev)
```

```json
{
  "name": "pci_has_p2pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588978472,
      "name": "pci_has_p2pmem",
      "external": true,
      "loc": "drivers/pci/p2pdma.c:732",
      "file": "drivers/pci/p2pdma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:pci_p2pdma_enable_store",
        "drivers/pci/p2pdma.c:pci_p2pmem_find_many"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597645749,
      "name": "pci_has_p2pmem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588972560,
      "name": "pci_has_p2pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
bool pci_has_p2pmem(struct pci_dev * pdev)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
