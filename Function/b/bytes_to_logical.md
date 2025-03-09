# Function: <code>bytes_to_logical</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bytes_to_logical",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585497978,
      "name": "bytes_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:182",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes"
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
  "name": "bytes_to_logical",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585939482,
      "name": "bytes_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:183",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_config_write_same"
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
  "name": "bytes_to_logical",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586186624,
      "name": "bytes_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:182",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_config_write_same"
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
  "name": "bytes_to_logical",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586329424,
      "name": "bytes_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:181",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_config_write_same"
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
  "name": "bytes_to_logical",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586572703,
      "name": "bytes_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:181",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_config_write_same"
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
  "name": "bytes_to_logical",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586720063,
      "name": "bytes_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:181",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_config_write_same"
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
sector_t bytes_to_logical(struct scsi_device * sdev, unsigned int bytes)
```

```json
{
  "name": "bytes_to_logical",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587503680,
      "name": "bytes_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:187",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_config_write_same"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587503680,
      "name": "bytes_to_logical",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bytes_to_logical",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587574428,
      "name": "bytes_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:190",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_config_write_same"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bytes_to_logical",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587458236,
      "name": "bytes_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:190",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_config_write_same"
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
  "name": "bytes_to_logical",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588037794,
      "name": "bytes_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:190",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_config_write_same"
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
  "name": "bytes_to_logical",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589400357,
      "name": "bytes_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:215",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_config_write_same"
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
  "name": "bytes_to_logical",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590973845,
      "name": "bytes_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:215",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_config_write_same"
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
  "name": "bytes_to_logical",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591327429,
      "name": "bytes_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:215",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_config_write_same"
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
  "name": "bytes_to_logical",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591676981,
      "name": "bytes_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:216",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_config_write_same"
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
  "name": "bytes_to_logical",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499631492,
      "name": "bytes_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:181",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_config_write_same"
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
  "name": "bytes_to_logical",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232085696,
      "name": "bytes_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:181",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_config_write_same"
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
  "name": "bytes_to_logical",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292950316,
      "name": "bytes_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:181",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_config_write_same"
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
  "name": "bytes_to_logical",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276813930,
      "name": "bytes_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:181",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_config_write_same"
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
  "name": "bytes_to_logical",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586410543,
      "name": "bytes_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:181",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_config_write_same"
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
  "name": "bytes_to_logical",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586286799,
      "name": "bytes_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:181",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_config_write_same"
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
  "name": "bytes_to_logical",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586674623,
      "name": "bytes_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:181",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_config_write_same"
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
  "name": "bytes_to_logical",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586780639,
      "name": "bytes_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:181",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_config_write_same"
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
sector_t bytes_to_logical(struct scsi_device * sdev, unsigned int bytes)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
sector_t bytes_to_logical(struct scsi_device * sdev, unsigned int bytes)
```
</details>
</li>
</ul>
