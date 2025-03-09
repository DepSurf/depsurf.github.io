# Function: <code>scsi_build_sense</code>

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
void scsi_build_sense(struct scsi_cmnd * scmd, int desc, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587403344,
      "name": "scsi_build_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:3235",
      "file": "drivers/scsi/scsi_lib.c",
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
      "addr": 18446744071587403344,
      "name": "scsi_build_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void scsi_build_sense(struct scsi_cmnd * scmd, int desc, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587974976,
      "name": "scsi_build_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:3228",
      "file": "drivers/scsi/scsi_lib.c",
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
      "addr": 18446744071587974976,
      "name": "scsi_build_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void scsi_build_sense(struct scsi_cmnd * scmd, int desc, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589330624,
      "name": "scsi_build_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:3312",
      "file": "drivers/scsi/scsi_lib.c",
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
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense",
        "drivers/ata/libata-scsi.c:ata_gen_passthru_sense"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589330624,
      "name": "scsi_build_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void scsi_build_sense(struct scsi_cmnd * scmd, int desc, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590895824,
      "name": "scsi_build_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:3317",
      "file": "drivers/scsi/scsi_lib.c",
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
      "addr": 18446744071590895824,
      "name": "scsi_build_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void scsi_build_sense(struct scsi_cmnd * scmd, int desc, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591239344,
      "name": "scsi_build_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:3336",
      "file": "drivers/scsi/scsi_lib.c",
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
      "addr": 18446744071591239344,
      "name": "scsi_build_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void scsi_build_sense(struct scsi_cmnd * scmd, int desc, u8 key, u8 asc, u8 ascq)
```

```json
{
  "name": "scsi_build_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591586592,
      "name": "scsi_build_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:3333",
      "file": "drivers/scsi/scsi_lib.c",
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
      "addr": 18446744071591586592,
      "name": "scsi_build_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void scsi_build_sense(struct scsi_cmnd * scmd, int desc, u8 key, u8 asc, u8 ascq)
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
