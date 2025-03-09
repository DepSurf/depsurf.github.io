# Function: <code>pci_pm_default_resume_early</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583275265,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:508",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
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
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583586225,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:508",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
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
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583723377,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:506",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void pci_pm_default_resume_early(struct pci_dev * pci_dev)
```

```json
{
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583762112,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:522",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583762112,
      "name": "pci_pm_default_resume_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void pci_pm_default_resume_early(struct pci_dev * pci_dev)
```

```json
{
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584021520,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:522",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584021520,
      "name": "pci_pm_default_resume_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void pci_pm_default_resume_early(struct pci_dev * pci_dev)
```

```json
{
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584218336,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:522",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584218336,
      "name": "pci_pm_default_resume_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void pci_pm_default_resume_early(struct pci_dev * pci_dev)
```

```json
{
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584307984,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:522",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584307984,
      "name": "pci_pm_default_resume_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584507746,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:524",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
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
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584643778,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:524",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
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
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585325789,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:531",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
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
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585479128,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:536",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
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
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585358728,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:536",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
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
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585818056,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:549",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
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
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587009886,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:566",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
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
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588179695,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:566",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
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
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588455695,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:566",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
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
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588752431,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:566",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
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
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496885536,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:524",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
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
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230167616,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:524",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
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
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290971124,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:524",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584591250,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:524",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq"
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
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584524066,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:524",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
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
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584593938,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:524",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
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
  "name": "pci_pm_default_resume_early",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584701986,
      "name": "pci_pm_default_resume_early",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:524",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void pci_pm_default_resume_early(struct pci_dev * pci_dev)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void pci_pm_default_resume_early(struct pci_dev * pci_dev)
```
</details>
</li>
</ul>
