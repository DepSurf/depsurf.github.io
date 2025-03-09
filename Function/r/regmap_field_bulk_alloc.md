# Function: <code>regmap_field_bulk_alloc</code>

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
int regmap_field_bulk_alloc(struct regmap * regmap, struct regmap_field * * rm_field, struct reg_field * reg_field, int num_fields)
```

```json
{
  "name": "regmap_field_bulk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587165568,
      "name": "regmap_field_bulk_alloc",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1286",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587165568,
      "name": "regmap_field_bulk_alloc",
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
int regmap_field_bulk_alloc(struct regmap * regmap, struct regmap_field * * rm_field, struct reg_field * reg_field, int num_fields)
```

```json
{
  "name": "regmap_field_bulk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587053088,
      "name": "regmap_field_bulk_alloc",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1286",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587053088,
      "name": "regmap_field_bulk_alloc",
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
int regmap_field_bulk_alloc(struct regmap * regmap, struct regmap_field * * rm_field, const struct reg_field * reg_field, int num_fields)
```

```json
{
  "name": "regmap_field_bulk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regmap_field_bulk_alloc",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1325",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592494653,
      "name": "regmap_field_bulk_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071587624720,
      "name": "regmap_field_bulk_alloc",
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
int regmap_field_bulk_alloc(struct regmap * regmap, struct regmap_field * * rm_field, const struct reg_field * reg_field, int num_fields)
```

```json
{
  "name": "regmap_field_bulk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regmap_field_bulk_alloc",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1344",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594364917,
      "name": "regmap_field_bulk_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071588968944,
      "name": "regmap_field_bulk_alloc",
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
int regmap_field_bulk_alloc(struct regmap * regmap, struct regmap_field * * rm_field, const struct reg_field * reg_field, int num_fields)
```

```json
{
  "name": "regmap_field_bulk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590487200,
      "name": "regmap_field_bulk_alloc",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1346",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590487200,
      "name": "regmap_field_bulk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int regmap_field_bulk_alloc(struct regmap * regmap, struct regmap_field * * rm_field, const struct reg_field * reg_field, int num_fields)
```

```json
{
  "name": "regmap_field_bulk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regmap_field_bulk_alloc",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1346",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596777130,
      "name": "regmap_field_bulk_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071590813936,
      "name": "regmap_field_bulk_alloc",
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
int regmap_field_bulk_alloc(struct regmap * regmap, struct regmap_field * * rm_field, const struct reg_field * reg_field, int num_fields)
```

```json
{
  "name": "regmap_field_bulk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regmap_field_bulk_alloc",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1252",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597686095,
      "name": "regmap_field_bulk_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071591157168,
      "name": "regmap_field_bulk_alloc",
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
int regmap_field_bulk_alloc(struct regmap * regmap, struct regmap_field * * rm_field, struct reg_field * reg_field, int num_fields)
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
