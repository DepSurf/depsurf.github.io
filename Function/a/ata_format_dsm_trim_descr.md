# Function: <code>ata_format_dsm_trim_descr</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_format_dsm_trim_descr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585509992,
      "name": "ata_format_dsm_trim_descr",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3387",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_format_dsm_trim_descr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585593198,
      "name": "ata_format_dsm_trim_descr",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3396",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_format_dsm_trim_descr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586024782,
      "name": "ata_format_dsm_trim_descr",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3403",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_format_dsm_trim_descr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586283098,
      "name": "ata_format_dsm_trim_descr",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3406",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_format_dsm_trim_descr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586424138,
      "name": "ata_format_dsm_trim_descr",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3401",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat"
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
  "name": "ata_format_dsm_trim_descr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586658269,
      "name": "ata_format_dsm_trim_descr",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3405",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat"
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
  "name": "ata_format_dsm_trim_descr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586805565,
      "name": "ata_format_dsm_trim_descr",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3405",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat"
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
size_t ata_format_dsm_trim_descr(struct scsi_cmnd * cmd, u32 trmax, u64 sector, u32 count)
```

```json
{
  "name": "ata_format_dsm_trim_descr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587603888,
      "name": "ata_format_dsm_trim_descr",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3117",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587603888,
      "name": "ata_format_dsm_trim_descr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
size_t ata_format_dsm_trim_descr(struct scsi_cmnd * cmd, u32 trmax, u64 sector, u32 count)
```

```json
{
  "name": "ata_format_dsm_trim_descr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587665584,
      "name": "ata_format_dsm_trim_descr",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3117",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587665584,
      "name": "ata_format_dsm_trim_descr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
  "name": "ata_format_dsm_trim_descr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587554490,
      "name": "ata_format_dsm_trim_descr",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3113",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat"
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
  "name": "ata_format_dsm_trim_descr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588133671,
      "name": "ata_format_dsm_trim_descr",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3084",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat"
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
  "name": "ata_format_dsm_trim_descr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589512434,
      "name": "ata_format_dsm_trim_descr",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3092",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat"
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
  "name": "ata_format_dsm_trim_descr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591099122,
      "name": "ata_format_dsm_trim_descr",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3105",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat"
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
  "name": "ata_format_dsm_trim_descr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591457819,
      "name": "ata_format_dsm_trim_descr",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3253",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat"
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
  "name": "ata_format_dsm_trim_descr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591806203,
      "name": "ata_format_dsm_trim_descr",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3125",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat"
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
  "name": "ata_format_dsm_trim_descr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499742568,
      "name": "ata_format_dsm_trim_descr",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3405",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat"
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
  "name": "ata_format_dsm_trim_descr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232180912,
      "name": "ata_format_dsm_trim_descr",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3405",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat"
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
  "name": "ata_format_dsm_trim_descr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293069320,
      "name": "ata_format_dsm_trim_descr",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3405",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ata_format_dsm_trim_descr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276895558,
      "name": "ata_format_dsm_trim_descr",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3405",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_format_dsm_trim_descr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586564173,
      "name": "ata_format_dsm_trim_descr",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3405",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat"
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
  "name": "ata_format_dsm_trim_descr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586432749,
      "name": "ata_format_dsm_trim_descr",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3405",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat"
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
  "name": "ata_format_dsm_trim_descr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586760125,
      "name": "ata_format_dsm_trim_descr",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3405",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat"
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
  "name": "ata_format_dsm_trim_descr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586866189,
      "name": "ata_format_dsm_trim_descr",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3405",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat"
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
size_t ata_format_dsm_trim_descr(struct scsi_cmnd * cmd, u32 trmax, u64 sector, u32 count)
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
size_t ata_format_dsm_trim_descr(struct scsi_cmnd * cmd, u32 trmax, u64 sector, u32 count)
```
</details>
</li>
</ul>
