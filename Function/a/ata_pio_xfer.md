# Function: <code>ata_pio_xfer</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void ata_pio_xfer(struct ata_queued_cmd * qc, struct page * page, unsigned int offset, size_t xfer_size)
```

```json
{
  "name": "ata_pio_xfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587608096,
      "name": "ata_pio_xfer",
      "external": false,
      "loc": "drivers/ata/libata-sff.c:640",
      "file": "drivers/ata/libata-sff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587608096,
      "name": "ata_pio_xfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
void ata_pio_xfer(struct ata_queued_cmd * qc, struct page * page, unsigned int offset, size_t xfer_size)
```

```json
{
  "name": "ata_pio_xfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588192592,
      "name": "ata_pio_xfer",
      "external": false,
      "loc": "drivers/ata/libata-sff.c:640",
      "file": "drivers/ata/libata-sff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588192592,
      "name": "ata_pio_xfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ata_pio_xfer(struct ata_queued_cmd * qc, struct page * page, unsigned int offset, size_t xfer_size)
```

```json
{
  "name": "ata_pio_xfer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589574720,
      "name": "ata_pio_xfer",
      "external": false,
      "loc": "drivers/ata/libata-sff.c:634",
      "file": "drivers/ata/libata-sff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589574720,
      "name": "ata_pio_xfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ata_pio_xfer(struct ata_queued_cmd * qc, struct page * page, unsigned int offset, size_t xfer_size)
```

```json
{
  "name": "ata_pio_xfer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591169728,
      "name": "ata_pio_xfer",
      "external": false,
      "loc": "drivers/ata/libata-sff.c:578",
      "file": "drivers/ata/libata-sff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591169728,
      "name": "ata_pio_xfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
void ata_pio_xfer(struct ata_queued_cmd * qc, struct page * page, unsigned int offset, size_t xfer_size)
```

```json
{
  "name": "ata_pio_xfer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591529072,
      "name": "ata_pio_xfer",
      "external": false,
      "loc": "drivers/ata/libata-sff.c:578",
      "file": "drivers/ata/libata-sff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591529072,
      "name": "ata_pio_xfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
void ata_pio_xfer(struct ata_queued_cmd * qc, struct page * page, unsigned int offset, size_t xfer_size)
```

```json
{
  "name": "ata_pio_xfer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591876544,
      "name": "ata_pio_xfer",
      "external": false,
      "loc": "drivers/ata/libata-sff.c:578",
      "file": "drivers/ata/libata-sff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591876544,
      "name": "ata_pio_xfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void ata_pio_xfer(struct ata_queued_cmd * qc, struct page * page, unsigned int offset, size_t xfer_size)
```
</details>
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
