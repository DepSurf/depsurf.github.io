# Function: <code>pcie_config_aspm_l1ss</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_config_aspm_l1ss",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583823439,
      "name": "pcie_config_aspm_l1ss",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:609",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_config_aspm_l1ss",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584086479,
      "name": "pcie_config_aspm_l1ss",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:634",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_config_aspm_l1ss",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584290218,
      "name": "pcie_config_aspm_l1ss",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:659",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link"
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
  "name": "pcie_config_aspm_l1ss",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584385610,
      "name": "pcie_config_aspm_l1ss",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:657",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link"
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
  "name": "pcie_config_aspm_l1ss",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584582544,
      "name": "pcie_config_aspm_l1ss",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:672",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link"
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
  "name": "pcie_config_aspm_l1ss",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584719776,
      "name": "pcie_config_aspm_l1ss",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:676",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link"
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
void pcie_config_aspm_l1ss(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_l1ss",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585375552,
      "name": "pcie_config_aspm_l1ss",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:667",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585375552,
      "name": "pcie_config_aspm_l1ss",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
void pcie_config_aspm_l1ss(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_l1ss",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585533472,
      "name": "pcie_config_aspm_l1ss",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:685",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585533472,
      "name": "pcie_config_aspm_l1ss",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_config_aspm_l1ss",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585413053,
      "name": "pcie_config_aspm_l1ss",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:685",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link"
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
  "name": "pcie_config_aspm_l1ss",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585875277,
      "name": "pcie_config_aspm_l1ss",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:685",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link"
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
  "name": "pcie_config_aspm_l1ss",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587068989,
      "name": "pcie_config_aspm_l1ss",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:677",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link"
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
  "name": "pcie_config_aspm_l1ss",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588254333,
      "name": "pcie_config_aspm_l1ss",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:702",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_config_aspm_l1ss",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588529714,
      "name": "pcie_config_aspm_l1ss",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:663",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_config_aspm_l1ss",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588826768,
      "name": "pcie_config_aspm_l1ss",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:664",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_config_aspm_l1ss",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496979144,
      "name": "pcie_config_aspm_l1ss",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:676",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link"
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
  "name": "pcie_config_aspm_l1ss",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230243032,
      "name": "pcie_config_aspm_l1ss",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:676",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link"
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_config_aspm_l1ss",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275646992,
      "name": "pcie_config_aspm_l1ss",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:676",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link"
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
  "name": "pcie_config_aspm_l1ss",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584670256,
      "name": "pcie_config_aspm_l1ss",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:676",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link"
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
  "name": "pcie_config_aspm_l1ss",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584599408,
      "name": "pcie_config_aspm_l1ss",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:676",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link"
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
  "name": "pcie_config_aspm_l1ss",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584669936,
      "name": "pcie_config_aspm_l1ss",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:676",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link"
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
  "name": "pcie_config_aspm_l1ss",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584777632,
      "name": "pcie_config_aspm_l1ss",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:676",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link"
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
void pcie_config_aspm_l1ss(struct pcie_link_state * link, u32 state)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void pcie_config_aspm_l1ss(struct pcie_link_state * link, u32 state)
```
</details>
</li>
</ul>
