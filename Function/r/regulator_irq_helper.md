# Function: <code>regulator_irq_helper</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * regulator_irq_helper(struct device * dev, const struct regulator_irq_desc * d, int irq, int irq_flags, int common_errs, int * per_rdev_errs, struct regulator_dev * * rdev, int rdev_amount)
```

```json
{
  "name": "regulator_irq_helper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586914624,
      "name": "regulator_irq_helper",
      "external": true,
      "loc": "drivers/regulator/irq_helpers.c:336",
      "file": "drivers/regulator/irq_helpers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_irq_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586914128,
      "name": "regulator_irq_helper.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
    },
    {
      "addr": 18446744071592444988,
      "name": "regulator_irq_helper.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071586914624,
      "name": "regulator_irq_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * regulator_irq_helper(struct device * dev, const struct regulator_irq_desc * d, int irq, int irq_flags, int common_errs, int * per_rdev_errs, struct regulator_dev * * rdev, int rdev_amount)
```

```json
{
  "name": "regulator_irq_helper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588207264,
      "name": "regulator_irq_helper",
      "external": true,
      "loc": "drivers/regulator/irq_helpers.c:338",
      "file": "drivers/regulator/irq_helpers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_irq_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588206784,
      "name": "regulator_irq_helper.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
    },
    {
      "addr": 18446744071594313023,
      "name": "regulator_irq_helper.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588207264,
      "name": "regulator_irq_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * regulator_irq_helper(struct device * dev, const struct regulator_irq_desc * d, int irq, int irq_flags, int common_errs, int * per_rdev_errs, struct regulator_dev * * rdev, int rdev_amount)
```

```json
{
  "name": "regulator_irq_helper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589614544,
      "name": "regulator_irq_helper",
      "external": true,
      "loc": "drivers/regulator/irq_helpers.c:338",
      "file": "drivers/regulator/irq_helpers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_irq_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589614544,
      "name": "regulator_irq_helper.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
    },
    {
      "addr": 18446744071589615072,
      "name": "regulator_irq_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * regulator_irq_helper(struct device * dev, const struct regulator_irq_desc * d, int irq, int irq_flags, int common_errs, int * per_rdev_errs, struct regulator_dev * * rdev, int rdev_amount)
```

```json
{
  "name": "regulator_irq_helper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589918080,
      "name": "regulator_irq_helper",
      "external": true,
      "loc": "drivers/regulator/irq_helpers.c:338",
      "file": "drivers/regulator/irq_helpers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_irq_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589918080,
      "name": "regulator_irq_helper.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
    },
    {
      "addr": 18446744071589918608,
      "name": "regulator_irq_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * regulator_irq_helper(struct device * dev, const struct regulator_irq_desc * d, int irq, int irq_flags, int common_errs, int * per_rdev_errs, struct regulator_dev * * rdev, int rdev_amount)
```

```json
{
  "name": "regulator_irq_helper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590256112,
      "name": "regulator_irq_helper",
      "external": true,
      "loc": "drivers/regulator/irq_helpers.c:338",
      "file": "drivers/regulator/irq_helpers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_irq_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590256112,
      "name": "regulator_irq_helper.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
    },
    {
      "addr": 18446744071590256640,
      "name": "regulator_irq_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void * regulator_irq_helper(struct device * dev, const struct regulator_irq_desc * d, int irq, int irq_flags, int common_errs, int * per_rdev_errs, struct regulator_dev * * rdev, int rdev_amount)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
