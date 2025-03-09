# Function: <code>pci_bus_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583250517,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:4138",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_try_reset_bus"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583581196,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:4459",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_try_reset_bus",
        "drivers/pci/pci.c:pci_probe_reset_bus"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583718252,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:4497",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_try_reset_bus",
        "drivers/pci/pci.c:pci_probe_reset_bus"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583758572,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:4655",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_try_reset_bus",
        "drivers/pci/pci.c:pci_reset_bus",
        "drivers/pci/pci.c:pci_reset_bus",
        "drivers/pci/pci.c:pci_probe_reset_bus"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_bus_reset(struct pci_bus * bus, int probe)
```

```json
{
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584017712,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:4679",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584017712,
      "name": "pci_bus_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584214085,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:4928",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_try_reset_bus",
        "drivers/pci/pci.c:pci_reset_bus",
        "drivers/pci/pci.c:pci_reset_bus",
        "drivers/pci/pci.c:pci_probe_reset_bus"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584278837,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:5194",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_bus_error_reset"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584473301,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:5292",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_bus_error_reset"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584608581,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:5422",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_bus_error_reset"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585293797,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:5452",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_bus_error_reset"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585448693,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:5520",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_bus_error_reset"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585328853,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:5569",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_bus_error_reset"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585809317,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:5759",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_bus_error_reset"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586998213,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:5855",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_bus_error_reset"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588166549,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:5792",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_bus_error_reset"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_bus_reset(struct pci_bus * bus, bool probe)
```

```json
{
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588442501,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:5914",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_bus"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588442560,
      "name": "pci_bus_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_bus_reset(struct pci_bus * bus, bool probe)
```

```json
{
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588739365,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:6024",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_bus"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588739424,
      "name": "pci_bus_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496847592,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:5422",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_bus_error_reset"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230127992,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:5422",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_bus_error_reset"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290925200,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:5422",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_bus_error_reset"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275551964,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:5422",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_bus_error_reset"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584560741,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:5422",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_bus_error_reset"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584488901,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:5422",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_bus_error_reset"
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
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584558741,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:5422",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_bus_error_reset"
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
  "name": "pci_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584666485,
      "name": "pci_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:5422",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_bus_error_reset"
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int pci_bus_reset(struct pci_bus * bus, int probe)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int pci_bus_reset(struct pci_bus * bus, int probe)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int pci_bus_reset(struct pci_bus * bus, bool probe)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
