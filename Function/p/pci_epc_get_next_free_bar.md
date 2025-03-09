# Function: <code>pci_epc_get_next_free_bar</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum pci_barno pci_epc_get_next_free_bar(const struct pci_epc_features * epc_features, enum pci_barno bar)
```

```json
{
  "name": "pci_epc_get_next_free_bar",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585514853,
      "name": "pci_epc_get_next_free_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:108",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585514656,
      "name": "pci_epc_get_next_free_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
enum pci_barno pci_epc_get_next_free_bar(const struct pci_epc_features * epc_features, enum pci_barno bar)
```

```json
{
  "name": "pci_epc_get_next_free_bar",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585983397,
      "name": "pci_epc_get_next_free_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:108",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592391007,
      "name": "pci_epc_get_next_free_bar.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071585983184,
      "name": "pci_epc_get_next_free_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
enum pci_barno pci_epc_get_next_free_bar(const struct pci_epc_features * epc_features, enum pci_barno bar)
```

```json
{
  "name": "pci_epc_get_next_free_bar",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_epc_get_next_free_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:108",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594255821,
      "name": "pci_epc_get_next_free_bar.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071587198752,
      "name": "pci_epc_get_next_free_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
enum pci_barno pci_epc_get_next_free_bar(const struct pci_epc_features * epc_features, enum pci_barno bar)
```

```json
{
  "name": "pci_epc_get_next_free_bar",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_epc_get_next_free_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:108",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596212529,
      "name": "pci_epc_get_next_free_bar.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071588426528,
      "name": "pci_epc_get_next_free_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
enum pci_barno pci_epc_get_next_free_bar(const struct pci_epc_features * epc_features, enum pci_barno bar)
```

```json
{
  "name": "pci_epc_get_next_free_bar",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588704501,
      "name": "pci_epc_get_next_free_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:108",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596737752,
      "name": "pci_epc_get_next_free_bar.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071588704256,
      "name": "pci_epc_get_next_free_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
enum pci_barno pci_epc_get_next_free_bar(const struct pci_epc_features * epc_features, enum pci_barno bar)
```

```json
{
  "name": "pci_epc_get_next_free_bar",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589005349,
      "name": "pci_epc_get_next_free_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:107",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597646336,
      "name": "pci_epc_get_next_free_bar.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071589005104,
      "name": "pci_epc_get_next_free_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
enum pci_barno pci_epc_get_next_free_bar(const struct pci_epc_features * epc_features, enum pci_barno bar)
```
</details>
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
