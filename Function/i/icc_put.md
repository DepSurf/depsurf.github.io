# Function: <code>icc_put</code>

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
void icc_put(struct icc_path * path)
```

```json
{
  "name": "icc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "icc_put",
      "external": true,
      "loc": "drivers/interconnect/core.c:732",
      "file": "drivers/interconnect/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/interconnect/core.c:devm_icc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589189127,
      "name": "icc_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589187216,
      "name": "icc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void icc_put(struct icc_path * path)
```

```json
{
  "name": "icc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "icc_put",
      "external": true,
      "loc": "drivers/interconnect/core.c:763",
      "file": "drivers/interconnect/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/interconnect/core.c:devm_icc_release",
        "drivers/interconnect/bulk.c:of_icc_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591625415,
      "name": "icc_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589184944,
      "name": "icc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void icc_put(struct icc_path * path)
```

```json
{
  "name": "icc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "icc_put",
      "external": true,
      "loc": "drivers/interconnect/core.c:763",
      "file": "drivers/interconnect/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/interconnect/core.c:devm_icc_release",
        "drivers/interconnect/bulk.c:of_icc_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591568805,
      "name": "icc_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589079088,
      "name": "icc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void icc_put(struct icc_path * path)
```

```json
{
  "name": "icc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "icc_put",
      "external": true,
      "loc": "drivers/interconnect/core.c:763",
      "file": "drivers/interconnect/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/interconnect/core.c:devm_icc_release",
        "drivers/interconnect/bulk.c:of_icc_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592691981,
      "name": "icc_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589798112,
      "name": "icc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void icc_put(struct icc_path * path)
```

```json
{
  "name": "icc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "icc_put",
      "external": true,
      "loc": "drivers/interconnect/core.c:763",
      "file": "drivers/interconnect/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/interconnect/core.c:devm_icc_release",
        "drivers/interconnect/bulk.c:of_icc_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594577162,
      "name": "icc_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071591312336,
      "name": "icc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
void icc_put(struct icc_path * path)
```

```json
{
  "name": "icc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593064704,
      "name": "icc_put",
      "external": true,
      "loc": "drivers/interconnect/core.c:763",
      "file": "drivers/interconnect/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/interconnect/core.c:devm_icc_release",
        "drivers/interconnect/bulk.c:devm_icc_bulk_release",
        "drivers/interconnect/bulk.c:of_icc_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593064704,
      "name": "icc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void icc_put(struct icc_path * path)
```

```json
{
  "name": "icc_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593516768,
      "name": "icc_put",
      "external": true,
      "loc": "drivers/interconnect/core.c:714",
      "file": "drivers/interconnect/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/interconnect/core.c:devm_icc_release",
        "drivers/interconnect/bulk.c:devm_icc_bulk_release",
        "drivers/interconnect/bulk.c:of_icc_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593516768,
      "name": "icc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void icc_put(struct icc_path * path)
```

```json
{
  "name": "icc_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594264896,
      "name": "icc_put",
      "external": true,
      "loc": "drivers/interconnect/core.c:781",
      "file": "drivers/interconnect/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/interconnect/core.c:devm_icc_release",
        "drivers/interconnect/bulk.c:devm_icc_bulk_release",
        "drivers/interconnect/bulk.c:of_icc_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594264896,
      "name": "icc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void icc_put(struct icc_path * path)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
