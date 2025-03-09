# Function: <code>sd_validate_opt_xfer_size</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_validate_opt_xfer_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586331225,
      "name": "sd_validate_opt_xfer_size",
      "external": false,
      "loc": "drivers/scsi/sd.c:3050",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
  "name": "sd_validate_opt_xfer_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586574001,
      "name": "sd_validate_opt_xfer_size",
      "external": false,
      "loc": "drivers/scsi/sd.c:3036",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
  "name": "sd_validate_opt_xfer_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586721297,
      "name": "sd_validate_opt_xfer_size",
      "external": false,
      "loc": "drivers/scsi/sd.c:3046",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
bool sd_validate_opt_xfer_size(struct scsi_disk * sdkp, unsigned int dev_max)
```

```json
{
  "name": "sd_validate_opt_xfer_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587505552,
      "name": "sd_validate_opt_xfer_size",
      "external": false,
      "loc": "drivers/scsi/sd.c:3076",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587505552,
      "name": "sd_validate_opt_xfer_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
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
bool sd_validate_opt_xfer_size(struct scsi_disk * sdkp, unsigned int dev_max)
```

```json
{
  "name": "sd_validate_opt_xfer_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587569648,
      "name": "sd_validate_opt_xfer_size",
      "external": false,
      "loc": "drivers/scsi/sd.c:3118",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587569648,
      "name": "sd_validate_opt_xfer_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
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
bool sd_validate_opt_xfer_size(struct scsi_disk * sdkp, unsigned int dev_max)
```

```json
{
  "name": "sd_validate_opt_xfer_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587451008,
      "name": "sd_validate_opt_xfer_size",
      "external": false,
      "loc": "drivers/scsi/sd.c:3133",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587451008,
      "name": "sd_validate_opt_xfer_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
bool sd_validate_opt_xfer_size(struct scsi_disk * sdkp, unsigned int dev_max)
```

```json
{
  "name": "sd_validate_opt_xfer_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588025296,
      "name": "sd_validate_opt_xfer_size",
      "external": false,
      "loc": "drivers/scsi/sd.c:3103",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588025296,
      "name": "sd_validate_opt_xfer_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
bool sd_validate_opt_xfer_size(struct scsi_disk * sdkp, unsigned int dev_max)
```

```json
{
  "name": "sd_validate_opt_xfer_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589387088,
      "name": "sd_validate_opt_xfer_size",
      "external": false,
      "loc": "drivers/scsi/sd.c:3146",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589387088,
      "name": "sd_validate_opt_xfer_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
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
bool sd_validate_opt_xfer_size(struct scsi_disk * sdkp, unsigned int dev_max)
```

```json
{
  "name": "sd_validate_opt_xfer_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590959792,
      "name": "sd_validate_opt_xfer_size",
      "external": false,
      "loc": "drivers/scsi/sd.c:3187",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590959792,
      "name": "sd_validate_opt_xfer_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
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
bool sd_validate_opt_xfer_size(struct scsi_disk * sdkp, unsigned int dev_max)
```

```json
{
  "name": "sd_validate_opt_xfer_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591312192,
      "name": "sd_validate_opt_xfer_size",
      "external": false,
      "loc": "drivers/scsi/sd.c:3305",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591312192,
      "name": "sd_validate_opt_xfer_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
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
bool sd_validate_opt_xfer_size(struct scsi_disk * sdkp, unsigned int dev_max)
```

```json
{
  "name": "sd_validate_opt_xfer_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591661040,
      "name": "sd_validate_opt_xfer_size",
      "external": false,
      "loc": "drivers/scsi/sd.c:3352",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591661040,
      "name": "sd_validate_opt_xfer_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sd_validate_opt_xfer_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499632652,
      "name": "sd_validate_opt_xfer_size",
      "external": false,
      "loc": "drivers/scsi/sd.c:3046",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
  "name": "sd_validate_opt_xfer_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232086900,
      "name": "sd_validate_opt_xfer_size",
      "external": false,
      "loc": "drivers/scsi/sd.c:3046",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
  "name": "sd_validate_opt_xfer_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292951820,
      "name": "sd_validate_opt_xfer_size",
      "external": false,
      "loc": "drivers/scsi/sd.c:3046",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
  "name": "sd_validate_opt_xfer_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276814948,
      "name": "sd_validate_opt_xfer_size",
      "external": false,
      "loc": "drivers/scsi/sd.c:3046",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
  "name": "sd_validate_opt_xfer_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586411777,
      "name": "sd_validate_opt_xfer_size",
      "external": false,
      "loc": "drivers/scsi/sd.c:3046",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
  "name": "sd_validate_opt_xfer_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586288033,
      "name": "sd_validate_opt_xfer_size",
      "external": false,
      "loc": "drivers/scsi/sd.c:3046",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
  "name": "sd_validate_opt_xfer_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586675857,
      "name": "sd_validate_opt_xfer_size",
      "external": false,
      "loc": "drivers/scsi/sd.c:3046",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
  "name": "sd_validate_opt_xfer_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586781873,
      "name": "sd_validate_opt_xfer_size",
      "external": false,
      "loc": "drivers/scsi/sd.c:3046",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
bool sd_validate_opt_xfer_size(struct scsi_disk * sdkp, unsigned int dev_max)
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
