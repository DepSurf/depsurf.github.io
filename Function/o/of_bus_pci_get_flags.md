# Function: <code>of_bus_pci_get_flags</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
unsigned int of_bus_pci_get_flags(const __be32 * addr)
```

```json
{
  "name": "of_bus_pci_get_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501634304,
      "name": "of_bus_pci_get_flags",
      "external": false,
      "loc": "drivers/of/address.c:126",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_bus_pci_map",
        "drivers/of/address.c:of_bus_pci_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501634304,
      "name": "of_bus_pci_get_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
unsigned int of_bus_pci_get_flags(const __be32 * addr)
```

```json
{
  "name": "of_bus_pci_get_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234160444,
      "name": "of_bus_pci_get_flags",
      "external": false,
      "loc": "drivers/of/address.c:126",
      "file": "drivers/of/address.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_bus_pci_map",
        "drivers/of/address.c:of_bus_pci_map"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234155024,
      "name": "of_bus_pci_get_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
unsigned int of_bus_pci_get_flags(const __be32 * addr)
```

```json
{
  "name": "of_bus_pci_get_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295076832,
      "name": "of_bus_pci_get_flags",
      "external": false,
      "loc": "drivers/of/address.c:126",
      "file": "drivers/of/address.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_bus_pci_map",
        "drivers/of/address.c:of_bus_pci_map"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295068608,
      "name": "of_bus_pci_get_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
unsigned int of_bus_pci_get_flags(const __be32 * addr)
```

```json
{
  "name": "of_bus_pci_get_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278094246,
      "name": "of_bus_pci_get_flags",
      "external": false,
      "loc": "drivers/of/address.c:126",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_bus_pci_map",
        "drivers/of/address.c:of_bus_pci_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278094246,
      "name": "of_bus_pci_get_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
unsigned int of_bus_pci_get_flags(const __be32 * addr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
unsigned int of_bus_pci_get_flags(const __be32 * addr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
unsigned int of_bus_pci_get_flags(const __be32 * addr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
unsigned int of_bus_pci_get_flags(const __be32 * addr)
```
</details>
</li>
</ul>
