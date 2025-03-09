# Function: <code>pci_eisa_init</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_eisa_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604987520,
      "name": "pci_eisa_init",
      "external": false,
      "loc": "drivers/eisa/pci_eisa.c:22",
      "file": "drivers/eisa/pci_eisa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
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
  "name": "pci_eisa_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605099290,
      "name": "pci_eisa_init",
      "external": false,
      "loc": "drivers/eisa/pci_eisa.c:21",
      "file": "drivers/eisa/pci_eisa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
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
  "name": "pci_eisa_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605138719,
      "name": "pci_eisa_init",
      "external": false,
      "loc": "drivers/eisa/pci_eisa.c:21",
      "file": "drivers/eisa/pci_eisa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
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
int pci_eisa_init(struct pci_dev * pdev)
```

```json
{
  "name": "pci_eisa_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609409694,
      "name": "pci_eisa_init",
      "external": false,
      "loc": "drivers/eisa/pci_eisa.c:21",
      "file": "drivers/eisa/pci_eisa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609409694,
      "name": "pci_eisa_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 213
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
int pci_eisa_init(struct pci_dev * pdev)
```

```json
{
  "name": "pci_eisa_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612483194,
      "name": "pci_eisa_init",
      "external": false,
      "loc": "drivers/eisa/pci_eisa.c:21",
      "file": "drivers/eisa/pci_eisa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612483194,
      "name": "pci_eisa_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 216
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
  "name": "pci_eisa_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614625612,
      "name": "pci_eisa_init",
      "external": false,
      "loc": "drivers/eisa/pci_eisa.c:21",
      "file": "drivers/eisa/pci_eisa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
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
  "name": "pci_eisa_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615581947,
      "name": "pci_eisa_init",
      "external": false,
      "loc": "drivers/eisa/pci_eisa.c:21",
      "file": "drivers/eisa/pci_eisa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
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
  "name": "pci_eisa_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071617389848,
      "name": "pci_eisa_init",
      "external": false,
      "loc": "drivers/eisa/pci_eisa.c:21",
      "file": "drivers/eisa/pci_eisa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
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
  "name": "pci_eisa_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071628136393,
      "name": "pci_eisa_init",
      "external": false,
      "loc": "drivers/eisa/pci_eisa.c:21",
      "file": "drivers/eisa/pci_eisa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
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
  "name": "pci_eisa_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619903053,
      "name": "pci_eisa_init",
      "external": false,
      "loc": "drivers/eisa/pci_eisa.c:21",
      "file": "drivers/eisa/pci_eisa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
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
  "name": "pci_eisa_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071622213133,
      "name": "pci_eisa_init",
      "external": false,
      "loc": "drivers/eisa/pci_eisa.c:21",
      "file": "drivers/eisa/pci_eisa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
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
  "name": "pci_eisa_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605031731,
      "name": "pci_eisa_init",
      "external": false,
      "loc": "drivers/eisa/pci_eisa.c:21",
      "file": "drivers/eisa/pci_eisa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
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
  "name": "pci_eisa_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604997660,
      "name": "pci_eisa_init",
      "external": false,
      "loc": "drivers/eisa/pci_eisa.c:21",
      "file": "drivers/eisa/pci_eisa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
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
  "name": "pci_eisa_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605115755,
      "name": "pci_eisa_init",
      "external": false,
      "loc": "drivers/eisa/pci_eisa.c:21",
      "file": "drivers/eisa/pci_eisa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
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
  "name": "pci_eisa_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605142913,
      "name": "pci_eisa_init",
      "external": false,
      "loc": "drivers/eisa/pci_eisa.c:21",
      "file": "drivers/eisa/pci_eisa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
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
int pci_eisa_init(struct pci_dev * pdev)
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
int pci_eisa_init(struct pci_dev * pdev)
```
</details>
</li>
</ul>
