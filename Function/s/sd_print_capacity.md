# Function: <code>sd_print_capacity</code>

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
  "name": "sd_print_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585426151,
      "name": "sd_print_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2393",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_print_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585510987,
      "name": "sd_print_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2543",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_print_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585942725,
      "name": "sd_print_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2581",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_print_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586189550,
      "name": "sd_print_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2554",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_print_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586332554,
      "name": "sd_print_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2541",
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
  "name": "sd_print_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586574623,
      "name": "sd_print_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2528",
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
  "name": "sd_print_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586721884,
      "name": "sd_print_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2538",
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
void sd_print_capacity(struct scsi_disk * sdkp, sector_t old_capacity)
```

```json
{
  "name": "sd_print_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587509200,
      "name": "sd_print_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2558",
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
      "addr": 18446744071587509200,
      "name": "sd_print_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
void sd_print_capacity(struct scsi_disk * sdkp, sector_t old_capacity)
```

```json
{
  "name": "sd_print_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587573376,
      "name": "sd_print_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2602",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587573376,
      "name": "sd_print_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
  "name": "sd_print_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587472073,
      "name": "sd_print_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2617",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "sd_print_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588047225,
      "name": "sd_print_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2580",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "sd_print_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589410114,
      "name": "sd_print_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2520",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "sd_print_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590983928,
      "name": "sd_print_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2561",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "sd_print_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591337509,
      "name": "sd_print_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2675",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "sd_print_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591687108,
      "name": "sd_print_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2725",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "sd_print_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499633148,
      "name": "sd_print_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2538",
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
  "name": "sd_print_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232087488,
      "name": "sd_print_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2538",
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
  "name": "sd_print_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292952476,
      "name": "sd_print_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2538",
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
  "name": "sd_print_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276815608,
      "name": "sd_print_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2538",
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
  "name": "sd_print_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586412364,
      "name": "sd_print_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2538",
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
  "name": "sd_print_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586288620,
      "name": "sd_print_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2538",
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
  "name": "sd_print_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586676444,
      "name": "sd_print_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2538",
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
  "name": "sd_print_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586782460,
      "name": "sd_print_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2538",
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
void sd_print_capacity(struct scsi_disk * sdkp, sector_t old_capacity)
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
void sd_print_capacity(struct scsi_disk * sdkp, sector_t old_capacity)
```
</details>
</li>
</ul>
