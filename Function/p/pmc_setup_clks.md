# Function: <code>pmc_setup_clks</code>

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
  "name": "pmc_setup_clks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596698097,
      "name": "pmc_setup_clks",
      "external": false,
      "loc": "drivers/platform/x86/pmc_atom.c:424",
      "file": "drivers/platform/x86/pmc_atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
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
  "name": "pmc_setup_clks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603028814,
      "name": "pmc_setup_clks",
      "external": false,
      "loc": "drivers/platform/x86/pmc_atom.c:424",
      "file": "drivers/platform/x86/pmc_atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
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
  "name": "pmc_setup_clks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603201522,
      "name": "pmc_setup_clks",
      "external": false,
      "loc": "drivers/platform/x86/pmc_atom.c:394",
      "file": "drivers/platform/x86/pmc_atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
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
  "name": "pmc_setup_clks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605011923,
      "name": "pmc_setup_clks",
      "external": false,
      "loc": "drivers/platform/x86/pmc_atom.c:394",
      "file": "drivers/platform/x86/pmc_atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
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
  "name": "pmc_setup_clks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605124720,
      "name": "pmc_setup_clks",
      "external": false,
      "loc": "drivers/platform/x86/pmc_atom.c:421",
      "file": "drivers/platform/x86/pmc_atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
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
  "name": "pmc_setup_clks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605164932,
      "name": "pmc_setup_clks",
      "external": false,
      "loc": "drivers/platform/x86/pmc_atom.c:451",
      "file": "drivers/platform/x86/pmc_atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
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
int pmc_setup_clks(struct pci_dev * pdev, void * pmc_regmap, const struct pmc_data * pmc_data)
```

```json
{
  "name": "pmc_setup_clks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589092319,
      "name": "pmc_setup_clks",
      "external": false,
      "loc": "drivers/platform/x86/pmc_atom.c:451",
      "file": "drivers/platform/x86/pmc_atom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589092319,
      "name": "pmc_setup_clks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int pmc_setup_clks(struct pci_dev * pdev, void * pmc_regmap, const struct pmc_data * pmc_data)
```

```json
{
  "name": "pmc_setup_clks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591613862,
      "name": "pmc_setup_clks",
      "external": false,
      "loc": "drivers/platform/x86/pmc_atom.c:451",
      "file": "drivers/platform/x86/pmc_atom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591613862,
      "name": "pmc_setup_clks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
  "name": "pmc_setup_clks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591557499,
      "name": "pmc_setup_clks",
      "external": false,
      "loc": "drivers/platform/x86/pmc_atom.c:427",
      "file": "drivers/platform/x86/pmc_atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "pmc_setup_clks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592677879,
      "name": "pmc_setup_clks",
      "external": false,
      "loc": "drivers/platform/x86/pmc_atom.c:427",
      "file": "drivers/platform/x86/pmc_atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "pmc_setup_clks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594563140,
      "name": "pmc_setup_clks",
      "external": false,
      "loc": "drivers/platform/x86/pmc_atom.c:424",
      "file": "drivers/platform/x86/pmc_atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "pmc_setup_clks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592940387,
      "name": "pmc_setup_clks",
      "external": false,
      "loc": "drivers/platform/x86/pmc_atom.c:423",
      "file": "drivers/platform/x86/pmc_atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "pmc_setup_clks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593390124,
      "name": "pmc_setup_clks",
      "external": false,
      "loc": "drivers/platform/x86/pmc_atom.c:423",
      "file": "drivers/platform/x86/pmc_atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "pmc_setup_clks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594135369,
      "name": "pmc_setup_clks",
      "external": false,
      "loc": "drivers/platform/x86/pmc_atom.c:423",
      "file": "drivers/platform/x86/pmc_atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmc_setup_clks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605054605,
      "name": "pmc_setup_clks",
      "external": false,
      "loc": "drivers/platform/x86/pmc_atom.c:451",
      "file": "drivers/platform/x86/pmc_atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
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
  "name": "pmc_setup_clks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605020656,
      "name": "pmc_setup_clks",
      "external": false,
      "loc": "drivers/platform/x86/pmc_atom.c:451",
      "file": "drivers/platform/x86/pmc_atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
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
  "name": "pmc_setup_clks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605141279,
      "name": "pmc_setup_clks",
      "external": false,
      "loc": "drivers/platform/x86/pmc_atom.c:451",
      "file": "drivers/platform/x86/pmc_atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
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
  "name": "pmc_setup_clks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605169126,
      "name": "pmc_setup_clks",
      "external": false,
      "loc": "drivers/platform/x86/pmc_atom.c:451",
      "file": "drivers/platform/x86/pmc_atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
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
int pmc_setup_clks(struct pci_dev * pdev, void * pmc_regmap, const struct pmc_data * pmc_data)
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
int pmc_setup_clks(struct pci_dev * pdev, void * pmc_regmap, const struct pmc_data * pmc_data)
```
</details>
</li>
</ul>
