# Function: <code>nand_deselect_target</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void nand_deselect_target(struct nand_chip * chip)
```

```json
{
  "name": "nand_deselect_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232372736,
      "name": "nand_deselect_target",
      "external": true,
      "loc": "drivers/mtd/nand/raw/nand_base.c:259",
      "file": "drivers/mtd/nand/raw/nand_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mtd/nand/raw/nand_base.c:nand_scan_tail",
        "drivers/mtd/nand/raw/nand_base.c:rawnand_isbad",
        "drivers/mtd/nand/raw/nand_base.c:rawnand_erase",
        "drivers/mtd/nand/raw/nand_base.c:nand_block_isbad",
        "drivers/mtd/nand/raw/nand_base.c:nand_erase_nand",
        "drivers/mtd/nand/raw/nand_base.c:nand_erase_nand",
        "drivers/mtd/nand/raw/nand_base.c:nand_do_write_ops",
        "drivers/mtd/nand/raw/nand_base.c:nand_do_write_ops",
        "drivers/mtd/nand/raw/nand_base.c:nand_do_read_ops",
        "drivers/mtd/nand/raw/nand_base.c:nand_do_read_ops",
        "drivers/mtd/nand/raw/nand_base.c:nand_reset",
        "drivers/mtd/nand/raw/nand_base.c:nand_setup_data_interface",
        "drivers/mtd/nand/raw/nand_base.c:nand_setup_data_interface",
        "drivers/mtd/nand/raw/nand_base.c:nand_setup_data_interface",
        "drivers/mtd/nand/raw/nand_base.c:nand_do_write_oob",
        "drivers/mtd/nand/raw/nand_base.c:nand_do_write_oob"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3232342632,
      "name": "nand_deselect_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void nand_deselect_target(struct nand_chip * chip)
```
</details>
</li>
</ul>
