# Function: <code>pcs_irq_handle</code>

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
int pcs_irq_handle(struct pcs_soc_data * pcs_soc)
```

```json
{
  "name": "pcs_irq_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496569040,
      "name": "pcs_irq_handle",
      "external": false,
      "loc": "drivers/pinctrl/pinctrl-single.c:1447",
      "file": "drivers/pinctrl/pinctrl-single.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-single.c:pcs_irq_chain_handler",
        "drivers/pinctrl/pinctrl-single.c:pcs_irq_chain_handler",
        "drivers/pinctrl/pinctrl-single.c:pcs_irq_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496569040,
      "name": "pcs_irq_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int pcs_irq_handle(struct pcs_soc_data * pcs_soc)
```

```json
{
  "name": "pcs_irq_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229872912,
      "name": "pcs_irq_handle",
      "external": false,
      "loc": "drivers/pinctrl/pinctrl-single.c:1447",
      "file": "drivers/pinctrl/pinctrl-single.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-single.c:pcs_irq_chain_handler",
        "drivers/pinctrl/pinctrl-single.c:pcs_irq_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229872912,
      "name": "pcs_irq_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
int pcs_irq_handle(struct pcs_soc_data * pcs_soc)
```

```json
{
  "name": "pcs_irq_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290764736,
      "name": "pcs_irq_handle",
      "external": false,
      "loc": "drivers/pinctrl/pinctrl-single.c:1447",
      "file": "drivers/pinctrl/pinctrl-single.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-single.c:pcs_irq_chain_handler",
        "drivers/pinctrl/pinctrl-single.c:pcs_irq_chain_handler",
        "drivers/pinctrl/pinctrl-single.c:pcs_irq_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290764736,
      "name": "pcs_irq_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
int pcs_irq_handle(struct pcs_soc_data * pcs_soc)
```

```json
{
  "name": "pcs_irq_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275452762,
      "name": "pcs_irq_handle",
      "external": false,
      "loc": "drivers/pinctrl/pinctrl-single.c:1447",
      "file": "drivers/pinctrl/pinctrl-single.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-single.c:pcs_irq_chain_handler",
        "drivers/pinctrl/pinctrl-single.c:pcs_irq_chain_handler",
        "drivers/pinctrl/pinctrl-single.c:pcs_irq_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275452762,
      "name": "pcs_irq_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
int pcs_irq_handle(struct pcs_soc_data * pcs_soc)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int pcs_irq_handle(struct pcs_soc_data * pcs_soc)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int pcs_irq_handle(struct pcs_soc_data * pcs_soc)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int pcs_irq_handle(struct pcs_soc_data * pcs_soc)
```
</details>
</li>
</ul>
