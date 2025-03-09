# Function: <code>devm_regmap_field_bulk_alloc</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int devm_regmap_field_bulk_alloc(struct device * dev, struct regmap * regmap, struct regmap_field * * rm_field, struct reg_field * reg_field, int num_fields)
```

```json
{
  "name": "devm_regmap_field_bulk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587165200,
      "name": "devm_regmap_field_bulk_alloc",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1321",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587165200,
      "name": "devm_regmap_field_bulk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int devm_regmap_field_bulk_alloc(struct device * dev, struct regmap * regmap, struct regmap_field * * rm_field, struct reg_field * reg_field, int num_fields)
```

```json
{
  "name": "devm_regmap_field_bulk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587052720,
      "name": "devm_regmap_field_bulk_alloc",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1321",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587052720,
      "name": "devm_regmap_field_bulk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int devm_regmap_field_bulk_alloc(struct device * dev, struct regmap * regmap, struct regmap_field * * rm_field, const struct reg_field * reg_field, int num_fields)
```

```json
{
  "name": "devm_regmap_field_bulk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devm_regmap_field_bulk_alloc",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1360",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592494593,
      "name": "devm_regmap_field_bulk_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071587623744,
      "name": "devm_regmap_field_bulk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int devm_regmap_field_bulk_alloc(struct device * dev, struct regmap * regmap, struct regmap_field * * rm_field, const struct reg_field * reg_field, int num_fields)
```

```json
{
  "name": "devm_regmap_field_bulk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devm_regmap_field_bulk_alloc",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1379",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594364849,
      "name": "devm_regmap_field_bulk_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071588968272,
      "name": "devm_regmap_field_bulk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int devm_regmap_field_bulk_alloc(struct device * dev, struct regmap * regmap, struct regmap_field * * rm_field, const struct reg_field * reg_field, int num_fields)
```

```json
{
  "name": "devm_regmap_field_bulk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590483904,
      "name": "devm_regmap_field_bulk_alloc",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1381",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590483904,
      "name": "devm_regmap_field_bulk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int devm_regmap_field_bulk_alloc(struct device * dev, struct regmap * regmap, struct regmap_field * * rm_field, const struct reg_field * reg_field, int num_fields)
```

```json
{
  "name": "devm_regmap_field_bulk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devm_regmap_field_bulk_alloc",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1381",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596777019,
      "name": "devm_regmap_field_bulk_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071590812288,
      "name": "devm_regmap_field_bulk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int devm_regmap_field_bulk_alloc(struct device * dev, struct regmap * regmap, struct regmap_field * * rm_field, const struct reg_field * reg_field, int num_fields)
```

```json
{
  "name": "devm_regmap_field_bulk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devm_regmap_field_bulk_alloc",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1287",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597685984,
      "name": "devm_regmap_field_bulk_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071591155520,
      "name": "devm_regmap_field_bulk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int devm_regmap_field_bulk_alloc(struct device * dev, struct regmap * regmap, struct regmap_field * * rm_field, struct reg_field * reg_field, int num_fields)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct reg_field * reg_field</code> ➡️ <code>const struct reg_field * reg_field</code>
</li>
</ul>
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
