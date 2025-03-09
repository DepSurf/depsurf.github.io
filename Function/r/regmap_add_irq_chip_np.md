# Function: <code>regmap_add_irq_chip_np</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int regmap_add_irq_chip_np(struct device_node * np, struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip_np",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regmap_add_irq_chip_np",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:560",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip_np",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587124854,
      "name": "regmap_add_irq_chip_np.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071587121776,
      "name": "regmap_add_irq_chip_np",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2289
    }
  ]
}
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int regmap_add_irq_chip_np(struct device_node * np, struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int regmap_add_irq_chip_np(struct device_node * np, struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```
</details>
</li>
</ul>
