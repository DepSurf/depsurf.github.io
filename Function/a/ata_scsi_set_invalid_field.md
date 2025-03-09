# Function: <code>ata_scsi_set_invalid_field</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void ata_scsi_set_invalid_field(struct ata_device * dev, struct scsi_cmnd * cmd, u16 field, u8 bit)
```

```json
{
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585306240,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:303",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585306240,
      "name": "ata_scsi_set_invalid_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void ata_scsi_set_invalid_field(struct ata_device * dev, struct scsi_cmnd * cmd, u16 field, u8 bit)
```

```json
{
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585506192,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:381",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585506192,
      "name": "ata_scsi_set_invalid_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void ata_scsi_set_invalid_field(struct ata_device * dev, struct scsi_cmnd * cmd, u16 field, u8 bit)
```

```json
{
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585590480,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:381",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585590480,
      "name": "ata_scsi_set_invalid_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void ata_scsi_set_invalid_field(struct ata_device * dev, struct scsi_cmnd * cmd, u16 field, u8 bit)
```

```json
{
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586022064,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:382",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586022064,
      "name": "ata_scsi_set_invalid_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void ata_scsi_set_invalid_field(struct ata_device * dev, struct scsi_cmnd * cmd, u16 field, u8 bit)
```

```json
{
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586270288,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:382",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586270288,
      "name": "ata_scsi_set_invalid_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void ata_scsi_set_invalid_field(struct ata_device * dev, struct scsi_cmnd * cmd, u16 field, u8 bit)
```

```json
{
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586411024,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:383",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586411024,
      "name": "ata_scsi_set_invalid_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void ata_scsi_set_invalid_field(struct ata_device * dev, struct scsi_cmnd * cmd, u16 field, u8 bit)
```

```json
{
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586655600,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:367",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586655600,
      "name": "ata_scsi_set_invalid_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void ata_scsi_set_invalid_field(struct ata_device * dev, struct scsi_cmnd * cmd, u16 field, u8 bit)
```

```json
{
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586802896,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:367",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586802896,
      "name": "ata_scsi_set_invalid_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587622844,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:221",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587684328,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:221",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
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
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587563596,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:219",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
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
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588143182,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:219",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ata_scsi_set_invalid_field(struct ata_device * dev, struct scsi_cmnd * cmd, u16 field, u8 bit)
```

```json
{
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589524739,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:219",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
      ],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594407484,
      "name": "ata_scsi_set_invalid_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591111287,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:235",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
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
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591468967,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:233",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
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
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591817308,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:233",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
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
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499730392,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:367",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499730392,
      "name": "ata_scsi_set_invalid_field.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void ata_scsi_set_invalid_field(struct ata_device * dev, struct scsi_cmnd * cmd, u16 field, u8 bit)
```

```json
{
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232175948,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:367",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232175948,
      "name": "ata_scsi_set_invalid_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void ata_scsi_set_invalid_field(struct ata_device * dev, struct scsi_cmnd * cmd, u16 field, u8 bit)
```

```json
{
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293065920,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:367",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293065920,
      "name": "ata_scsi_set_invalid_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void ata_scsi_set_invalid_field(struct ata_device * dev, struct scsi_cmnd * cmd, u16 field, u8 bit)
```

```json
{
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276891864,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:367",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276891864,
      "name": "ata_scsi_set_invalid_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void ata_scsi_set_invalid_field(struct ata_device * dev, struct scsi_cmnd * cmd, u16 field, u8 bit)
```

```json
{
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586561504,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:367",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586561504,
      "name": "ata_scsi_set_invalid_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void ata_scsi_set_invalid_field(struct ata_device * dev, struct scsi_cmnd * cmd, u16 field, u8 bit)
```

```json
{
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586430080,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:367",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586430080,
      "name": "ata_scsi_set_invalid_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void ata_scsi_set_invalid_field(struct ata_device * dev, struct scsi_cmnd * cmd, u16 field, u8 bit)
```

```json
{
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586757456,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:367",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586757456,
      "name": "ata_scsi_set_invalid_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void ata_scsi_set_invalid_field(struct ata_device * dev, struct scsi_cmnd * cmd, u16 field, u8 bit)
```

```json
{
  "name": "ata_scsi_set_invalid_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586863520,
      "name": "ata_scsi_set_invalid_field",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:367",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_pass_thru",
        "drivers/ata/libata-scsi.c:ata_scsiop_mode_sense",
        "drivers/ata/libata-scsi.c:ata_scsi_rw_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_verify_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586863520,
      "name": "ata_scsi_set_invalid_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void ata_scsi_set_invalid_field(struct ata_device * dev, struct scsi_cmnd * cmd, u16 field, u8 bit)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void ata_scsi_set_invalid_field(struct ata_device * dev, struct scsi_cmnd * cmd, u16 field, u8 bit)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void ata_scsi_set_invalid_field(struct ata_device * dev, struct scsi_cmnd * cmd, u16 field, u8 bit)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void ata_scsi_set_invalid_field(struct ata_device * dev, struct scsi_cmnd * cmd, u16 field, u8 bit)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void ata_scsi_set_invalid_field(struct ata_device * dev, struct scsi_cmnd * cmd, u16 field, u8 bit)
```
</details>
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
