# Function: <code>scsi_build_sense_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584814224,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:231",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_invalid_field",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584814224,
      "name": "scsi_build_sense_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585175312,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:231",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585175312,
      "name": "scsi_build_sense_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585370096,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:231",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585370096,
      "name": "scsi_build_sense_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585454864,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:231",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585454864,
      "name": "scsi_build_sense_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585885664,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:232",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585885664,
      "name": "scsi_build_sense_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586132304,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:232",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586132304,
      "name": "scsi_build_sense_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586310832,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:232",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586310832,
      "name": "scsi_build_sense_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586554256,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:232",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586554256,
      "name": "scsi_build_sense_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586701472,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:232",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586701472,
      "name": "scsi_build_sense_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587501616,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:232",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat",
        "drivers/ata/libata-scsi.c:ata_gen_ata_sense",
        "drivers/ata/libata-scsi.c:ata_gen_ata_sense",
        "drivers/ata/libata-scsi.c:ata_gen_ata_sense",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587501616,
      "name": "scsi_build_sense_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587568464,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:232",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat",
        "drivers/ata/libata-scsi.c:ata_gen_ata_sense",
        "drivers/ata/libata-scsi.c:ata_gen_ata_sense",
        "drivers/ata/libata-scsi.c:ata_gen_ata_sense",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587568464,
      "name": "scsi_build_sense_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587449824,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:232",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_build_sense"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587449824,
      "name": "scsi_build_sense_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588024080,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:241",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_build_sense"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588024080,
      "name": "scsi_build_sense_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589385760,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:241",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_build_sense"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589385760,
      "name": "scsi_build_sense_buffer",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590958272,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:241",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_build_sense"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590958272,
      "name": "scsi_build_sense_buffer",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591302688,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:283",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_build_sense",
        "drivers/ata/libata-eh.c:ata_eh_request_sense",
        "drivers/ata/libata-sata.c:ata_eh_read_sense_success_ncq_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591302688,
      "name": "scsi_build_sense_buffer",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591650896,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:283",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_build_sense",
        "drivers/ata/libata-eh.c:ata_eh_request_sense",
        "drivers/ata/libata-sata.c:ata_eh_read_sense_success_ncq_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591650896,
      "name": "scsi_build_sense_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499611232,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:232",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499611232,
      "name": "scsi_build_sense_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232066664,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:232",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232066664,
      "name": "scsi_build_sense_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292916944,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:232",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292916944,
      "name": "scsi_build_sense_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276796380,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:232",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276796380,
      "name": "scsi_build_sense_buffer",
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
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586391952,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:232",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586391952,
      "name": "scsi_build_sense_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586233264,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:232",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586233264,
      "name": "scsi_build_sense_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586649440,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:232",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586649440,
      "name": "scsi_build_sense_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void scsi_build_sense_buffer(int desc, u8 * buf, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586761984,
      "name": "scsi_build_sense_buffer",
      "external": true,
      "loc": "drivers/scsi/scsi_common.c:232",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586761984,
      "name": "scsi_build_sense_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
