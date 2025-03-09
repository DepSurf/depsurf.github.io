# Function: <code>of_irq_parse_raw</code>

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
int of_irq_parse_raw(const __be32 * addr, struct of_phandle_args * out_irq)
```

```json
{
  "name": "of_irq_parse_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501643024,
      "name": "of_irq_parse_raw",
      "external": true,
      "loc": "drivers/of/irq.c:93",
      "file": "drivers/of/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:of_irq_parse_and_map_pci",
        "drivers/of/irq.c:of_irq_parse_one",
        "drivers/of/irq.c:of_irq_parse_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501643024,
      "name": "of_irq_parse_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1752
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
int of_irq_parse_raw(const __be32 * addr, struct of_phandle_args * out_irq)
```

```json
{
  "name": "of_irq_parse_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234163504,
      "name": "of_irq_parse_raw",
      "external": true,
      "loc": "drivers/of/irq.c:93",
      "file": "drivers/of/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:of_irq_parse_and_map_pci",
        "drivers/of/irq.c:of_irq_parse_one",
        "drivers/of/irq.c:of_irq_parse_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234163504,
      "name": "of_irq_parse_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1892
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
int of_irq_parse_raw(const __be32 * addr, struct of_phandle_args * out_irq)
```

```json
{
  "name": "of_irq_parse_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295080480,
      "name": "of_irq_parse_raw",
      "external": true,
      "loc": "drivers/of/irq.c:93",
      "file": "drivers/of/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:of_irq_parse_and_map_pci",
        "drivers/of/irq.c:of_irq_parse_one",
        "drivers/of/irq.c:of_irq_parse_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295080480,
      "name": "of_irq_parse_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2348
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
int of_irq_parse_raw(const __be32 * addr, struct of_phandle_args * out_irq)
```

```json
{
  "name": "of_irq_parse_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278102044,
      "name": "of_irq_parse_raw",
      "external": true,
      "loc": "drivers/of/irq.c:93",
      "file": "drivers/of/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:of_irq_parse_and_map_pci",
        "drivers/of/irq.c:of_irq_parse_one",
        "drivers/of/irq.c:of_irq_parse_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278102044,
      "name": "of_irq_parse_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1748
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
int of_irq_parse_raw(const __be32 * addr, struct of_phandle_args * out_irq)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int of_irq_parse_raw(const __be32 * addr, struct of_phandle_args * out_irq)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int of_irq_parse_raw(const __be32 * addr, struct of_phandle_args * out_irq)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int of_irq_parse_raw(const __be32 * addr, struct of_phandle_args * out_irq)
```
</details>
</li>
</ul>
