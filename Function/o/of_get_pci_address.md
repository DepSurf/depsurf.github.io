# Function: <code>of_get_pci_address</code>

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
const __be32 * of_get_pci_address(struct device_node * dev, int bar_no, u64 * size, unsigned int * flags)
```

```json
{
  "name": "of_get_pci_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501637672,
      "name": "of_get_pci_address",
      "external": true,
      "loc": "drivers/of/address.c:177",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/address.c:of_pci_address_to_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501637672,
      "name": "of_get_pci_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
const __be32 * of_get_pci_address(struct device_node * dev, int bar_no, u64 * size, unsigned int * flags)
```

```json
{
  "name": "of_get_pci_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234155236,
      "name": "of_get_pci_address",
      "external": true,
      "loc": "drivers/of/address.c:177",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/address.c:of_pci_address_to_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234155236,
      "name": "of_get_pci_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
const __be32 * of_get_pci_address(struct device_node * dev, int bar_no, u64 * size, unsigned int * flags)
```

```json
{
  "name": "of_get_pci_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295068928,
      "name": "of_get_pci_address",
      "external": true,
      "loc": "drivers/of/address.c:177",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports",
        "drivers/video/fbdev/offb.c:offb_map_reg",
        "drivers/of/address.c:of_pci_address_to_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295068928,
      "name": "of_get_pci_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 880
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
const __be32 * of_get_pci_address(struct device_node * dev, int bar_no, u64 * size, unsigned int * flags)
```

```json
{
  "name": "of_get_pci_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278097594,
      "name": "of_get_pci_address",
      "external": true,
      "loc": "drivers/of/address.c:177",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/address.c:of_pci_address_to_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278097594,
      "name": "of_get_pci_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
const __be32 * of_get_pci_address(struct device_node * dev, int bar_no, u64 * size, unsigned int * flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
const __be32 * of_get_pci_address(struct device_node * dev, int bar_no, u64 * size, unsigned int * flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
const __be32 * of_get_pci_address(struct device_node * dev, int bar_no, u64 * size, unsigned int * flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
const __be32 * of_get_pci_address(struct device_node * dev, int bar_no, u64 * size, unsigned int * flags)
```
</details>
</li>
</ul>
