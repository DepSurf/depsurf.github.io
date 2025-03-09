# Function: <code>sg_miter_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583015376,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:609",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_miter_skip",
        "lib/scatterlist.c:sg_copy_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583015376,
      "name": "sg_miter_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583306272,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:609",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583306272,
      "name": "sg_miter_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583425472,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:609",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583425472,
      "name": "sg_miter_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583446016,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:609",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583446016,
      "name": "sg_miter_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583626000,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:650",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583626000,
      "name": "sg_miter_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583842080,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:765",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583842080,
      "name": "sg_miter_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583925776,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:765",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583925776,
      "name": "sg_miter_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:800",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584108955,
      "name": "sg_miter_stop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071584106032,
      "name": "sg_miter_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584230256,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:800",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584230256,
      "name": "sg_miter_stop",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584635824,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:800",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584635824,
      "name": "sg_miter_stop",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584754832,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:881",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584754832,
      "name": "sg_miter_stop",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584783296,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:881",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584783296,
      "name": "sg_miter_stop",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585212672,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:912",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585212672,
      "name": "sg_miter_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586051200,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:909",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586051200,
      "name": "sg_miter_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587034816,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:919",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587034816,
      "name": "sg_miter_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587289968,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:921",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587289968,
      "name": "sg_miter_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587575840,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:923",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/crypto/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/crypto/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/crypto/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/crypto/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587575840,
      "name": "sg_miter_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496103448,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:800",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete",
        "drivers/mmc/host/mmci.c:mmci_pio_irq",
        "drivers/mmc/host/mmci.c:mmci_pio_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496103448,
      "name": "sg_miter_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229429072,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:800",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete",
        "drivers/usb/musb/musb_host.c:musb_host_rx",
        "drivers/usb/musb/musb_host.c:musb_host_rx",
        "drivers/usb/musb/musb_host.c:musb_host_tx",
        "drivers/usb/musb/musb_host.c:musb_host_tx",
        "drivers/mmc/host/mmci.c:mmci_pio_irq",
        "drivers/mmc/host/sdhci.c:sdhci_irq",
        "drivers/mmc/host/sdhci.c:sdhci_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229429072,
      "name": "sg_miter_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290349632,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:800",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290349632,
      "name": "sg_miter_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275169810,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:800",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275169810,
      "name": "sg_miter_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584198992,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:800",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584198992,
      "name": "sg_miter_stop",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584134208,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:800",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584134208,
      "name": "sg_miter_stop",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584182752,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:800",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584182752,
      "name": "sg_miter_stop",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter * miter)
```

```json
{
  "name": "sg_miter_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584287088,
      "name": "sg_miter_stop",
      "external": true,
      "loc": "lib/scatterlist.c:800",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_zero_buffer",
        "lib/scatterlist.c:sg_copy_buffer",
        "lib/scatterlist.c:sg_miter_skip",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584287088,
      "name": "sg_miter_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
