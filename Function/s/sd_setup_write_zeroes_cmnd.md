# Function: <code>sd_setup_write_zeroes_cmnd</code>

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
  "name": "sd_setup_write_zeroes_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585506448,
      "name": "sd_setup_write_zeroes_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:831",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command"
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
  "name": "sd_setup_write_zeroes_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585936974,
      "name": "sd_setup_write_zeroes_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:847",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command"
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
  "name": "sd_setup_write_zeroes_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586183352,
      "name": "sd_setup_write_zeroes_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:847",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command"
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
  "name": "sd_setup_write_zeroes_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586328739,
      "name": "sd_setup_write_zeroes_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:859",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command"
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
  "name": "sd_setup_write_zeroes_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586579226,
      "name": "sd_setup_write_zeroes_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:920",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command"
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
  "name": "sd_setup_write_zeroes_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586726522,
      "name": "sd_setup_write_zeroes_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:920",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command"
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
blk_status_t sd_setup_write_zeroes_cmnd(struct scsi_cmnd * cmd)
```

```json
{
  "name": "sd_setup_write_zeroes_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587513808,
      "name": "sd_setup_write_zeroes_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:934",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587513808,
      "name": "sd_setup_write_zeroes_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
blk_status_t sd_setup_write_zeroes_cmnd(struct scsi_cmnd * cmd)
```

```json
{
  "name": "sd_setup_write_zeroes_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587580160,
      "name": "sd_setup_write_zeroes_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:970",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587580160,
      "name": "sd_setup_write_zeroes_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
  "name": "sd_setup_write_zeroes_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587464037,
      "name": "sd_setup_write_zeroes_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:970",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command"
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
  "name": "sd_setup_write_zeroes_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588039941,
      "name": "sd_setup_write_zeroes_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:970",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command"
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
  "name": "sd_setup_write_zeroes_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589403187,
      "name": "sd_setup_write_zeroes_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:933",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command"
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
  "name": "sd_setup_write_zeroes_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590976766,
      "name": "sd_setup_write_zeroes_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:933",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command"
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
  "name": "sd_setup_write_zeroes_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591330143,
      "name": "sd_setup_write_zeroes_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:933",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command"
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
  "name": "sd_setup_write_zeroes_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591679619,
      "name": "sd_setup_write_zeroes_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:973",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command"
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
  "name": "sd_setup_write_zeroes_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499636792,
      "name": "sd_setup_write_zeroes_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:920",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command"
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
  "name": "sd_setup_write_zeroes_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232091616,
      "name": "sd_setup_write_zeroes_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:920",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command"
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
  "name": "sd_setup_write_zeroes_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292958128,
      "name": "sd_setup_write_zeroes_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:920",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command"
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
  "name": "sd_setup_write_zeroes_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276819880,
      "name": "sd_setup_write_zeroes_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:920",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command"
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
  "name": "sd_setup_write_zeroes_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586417002,
      "name": "sd_setup_write_zeroes_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:920",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command"
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
  "name": "sd_setup_write_zeroes_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586293258,
      "name": "sd_setup_write_zeroes_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:920",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command"
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
  "name": "sd_setup_write_zeroes_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586681082,
      "name": "sd_setup_write_zeroes_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:920",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command"
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
  "name": "sd_setup_write_zeroes_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586787098,
      "name": "sd_setup_write_zeroes_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:920",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command"
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
blk_status_t sd_setup_write_zeroes_cmnd(struct scsi_cmnd * cmd)
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
blk_status_t sd_setup_write_zeroes_cmnd(struct scsi_cmnd * cmd)
```
</details>
</li>
</ul>
