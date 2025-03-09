# Function: <code>ata_scsi_set_sense</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584942241,
      "name": "ata_scsi_set_sense",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:273",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585322769,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:273",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585319648,
      "name": "ata_scsi_set_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585523560,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:351",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585520656,
      "name": "ata_scsi_set_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585607981,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:351",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585605200,
      "name": "ata_scsi_set_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586039581,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:352",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586036800,
      "name": "ata_scsi_set_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586287245,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:352",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586284480,
      "name": "ata_scsi_set_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586428221,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:353",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586425360,
      "name": "ata_scsi_set_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586672994,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:337",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586670176,
      "name": "ata_scsi_set_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586820290,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:337",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586817472,
      "name": "ata_scsi_set_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587622844,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:191",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
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
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587619008,
      "name": "ata_scsi_set_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587684328,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:191",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
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
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587680496,
      "name": "ata_scsi_set_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587563596,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:191",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
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
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587560592,
      "name": "ata_scsi_set_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588143182,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:191",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
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
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588140032,
      "name": "ata_scsi_set_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589524739,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:191",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat",
        "drivers/ata/libata-scsi.c:ata_gen_ata_sense",
        "drivers/ata/libata-eh.c:ata_eh_request_sense",
        "drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589519056,
      "name": "ata_scsi_set_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591111287,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:207",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_request_sense",
        "drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591106736,
      "name": "ata_scsi_set_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591468967,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:211",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
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
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_get_success_sense",
        "drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591464352,
      "name": "ata_scsi_set_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591817308,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:211",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
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
        "drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat",
        "drivers/ata/libata-scsi.c:ata_gen_ata_sense",
        "drivers/ata/libata-scsi.c:ata_gen_ata_sense",
        "drivers/ata/libata-scsi.c:ata_gen_ata_sense",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_get_success_sense",
        "drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591812736,
      "name": "ata_scsi_set_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499747600,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:337",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499743112,
      "name": "ata_scsi_set_sense",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232193616,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:337",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232189808,
      "name": "ata_scsi_set_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293090168,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:337",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293086176,
      "name": "ata_scsi_set_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276908052,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:337",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276905474,
      "name": "ata_scsi_set_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586578866,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:337",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586576048,
      "name": "ata_scsi_set_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586447378,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:337",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586444560,
      "name": "ata_scsi_set_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586774850,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:337",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586772032,
      "name": "ata_scsi_set_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
```

```json
{
  "name": "ata_scsi_set_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586880898,
      "name": "ata_scsi_set_sense",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:337",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586878080,
      "name": "ata_scsi_set_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void ata_scsi_set_sense(struct ata_device * dev, struct scsi_cmnd * cmd, u8 sk, u8 asc, u8 ascq)
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
