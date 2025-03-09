# Function: <code>icc_set_bw</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int icc_set_bw(struct icc_path * path, u32 avg_bw, u32 peak_bw)
```

```json
{
  "name": "icc_set_bw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589186480,
      "name": "icc_set_bw",
      "external": true,
      "loc": "drivers/interconnect/core.c:591",
      "file": "drivers/interconnect/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/interconnect/core.c:icc_put",
        "drivers/interconnect/core.c:__icc_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589186480,
      "name": "icc_set_bw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
int icc_set_bw(struct icc_path * path, u32 avg_bw, u32 peak_bw)
```

```json
{
  "name": "icc_set_bw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589184304,
      "name": "icc_set_bw",
      "external": true,
      "loc": "drivers/interconnect/core.c:622",
      "file": "drivers/interconnect/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/interconnect/core.c:icc_put",
        "drivers/interconnect/core.c:__icc_enable",
        "drivers/interconnect/bulk.c:icc_bulk_set_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589184304,
      "name": "icc_set_bw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
int icc_set_bw(struct icc_path * path, u32 avg_bw, u32 peak_bw)
```

```json
{
  "name": "icc_set_bw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589078448,
      "name": "icc_set_bw",
      "external": true,
      "loc": "drivers/interconnect/core.c:622",
      "file": "drivers/interconnect/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/interconnect/core.c:icc_put",
        "drivers/interconnect/core.c:__icc_enable",
        "drivers/interconnect/bulk.c:icc_bulk_set_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589078448,
      "name": "icc_set_bw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int icc_set_bw(struct icc_path * path, u32 avg_bw, u32 peak_bw)
```

```json
{
  "name": "icc_set_bw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589797472,
      "name": "icc_set_bw",
      "external": true,
      "loc": "drivers/interconnect/core.c:622",
      "file": "drivers/interconnect/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/interconnect/core.c:icc_put",
        "drivers/interconnect/bulk.c:icc_bulk_set_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589797472,
      "name": "icc_set_bw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int icc_set_bw(struct icc_path * path, u32 avg_bw, u32 peak_bw)
```

```json
{
  "name": "icc_set_bw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591311632,
      "name": "icc_set_bw",
      "external": true,
      "loc": "drivers/interconnect/core.c:622",
      "file": "drivers/interconnect/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_set_opp_bw",
        "drivers/interconnect/core.c:icc_put",
        "drivers/interconnect/bulk.c:icc_bulk_set_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591311632,
      "name": "icc_set_bw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
int icc_set_bw(struct icc_path * path, u32 avg_bw, u32 peak_bw)
```

```json
{
  "name": "icc_set_bw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593063904,
      "name": "icc_set_bw",
      "external": true,
      "loc": "drivers/interconnect/core.c:622",
      "file": "drivers/interconnect/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_set_opp_bw",
        "drivers/opp/core.c:_set_opp_bw",
        "drivers/interconnect/core.c:icc_put",
        "drivers/interconnect/bulk.c:icc_bulk_set_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593063904,
      "name": "icc_set_bw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int icc_set_bw(struct icc_path * path, u32 avg_bw, u32 peak_bw)
```

```json
{
  "name": "icc_set_bw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593515968,
      "name": "icc_set_bw",
      "external": true,
      "loc": "drivers/interconnect/core.c:621",
      "file": "drivers/interconnect/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_set_opp_bw",
        "drivers/opp/core.c:_set_opp_bw",
        "drivers/interconnect/bulk.c:icc_bulk_set_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593515968,
      "name": "icc_set_bw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int icc_set_bw(struct icc_path * path, u32 avg_bw, u32 peak_bw)
```

```json
{
  "name": "icc_set_bw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594264096,
      "name": "icc_set_bw",
      "external": true,
      "loc": "drivers/interconnect/core.c:688",
      "file": "drivers/interconnect/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_set_opp_bw",
        "drivers/opp/core.c:_set_opp_bw",
        "drivers/interconnect/bulk.c:icc_bulk_set_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594264096,
      "name": "icc_set_bw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
int icc_set_bw(struct icc_path * path, u32 avg_bw, u32 peak_bw)
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
