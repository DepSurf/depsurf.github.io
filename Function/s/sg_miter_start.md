# Function: <code>sg_miter_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583015248,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:484",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_copy_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583015248,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583306144,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:484",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583306144,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583425344,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:484",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583425344,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583446192,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:484",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583446192,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583626176,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:525",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583626176,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583842256,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:640",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583842256,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583925968,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:640",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583925968,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:674",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584108936,
      "name": "sg_miter_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071584105936,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584228800,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:674",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584228800,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584636571,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:674",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer"
      ],
      "caller_func": [
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584635168,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584755579,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:755",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer"
      ],
      "caller_func": [
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584754176,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584784043,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:755",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer"
      ],
      "caller_func": [
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584782640,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585214315,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:786",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer"
      ],
      "caller_func": [
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585213296,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586053083,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:786",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer"
      ],
      "caller_func": [
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586050688,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587035563,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:796",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer"
      ],
      "caller_func": [
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587034272,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587289424,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:798",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587289424,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587575296,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:800",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/crypto/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/crypto/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587575296,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496104000,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:674",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete",
        "drivers/mmc/host/mmci.c:mmci_start_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496104000,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229428788,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:674",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete",
        "drivers/usb/musb/musb_host.c:musb_host_rx",
        "drivers/mmc/host/mmci.c:mmci_start_data",
        "drivers/mmc/host/sdhci.c:sdhci_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229428788,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290350528,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:674",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290350528,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275170364,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:674",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275170364,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584197536,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:674",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584197536,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584132752,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:674",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132752,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584181296,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:674",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584181296,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter * miter, struct scatterlist * sgl, unsigned int nents, unsigned int flags)
```

```json
{
  "name": "sg_miter_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584285632,
      "name": "sg_miter_start",
      "external": true,
      "loc": "lib/scatterlist.c:674",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584285632,
      "name": "sg_miter_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
