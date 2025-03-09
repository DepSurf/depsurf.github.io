# Function: <code>scsi_eh_finish_cmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584781744,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1128",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense",
        "drivers/scsi/scsi_error.c:scsi_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler",
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584781744,
      "name": "scsi_eh_finish_cmd",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585156357,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1129",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585142016,
      "name": "scsi_eh_finish_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585350631,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1129",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585336304,
      "name": "scsi_eh_finish_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585426748,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1116",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585421792,
      "name": "scsi_eh_finish_cmd",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585856924,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1142",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585851824,
      "name": "scsi_eh_finish_cmd",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586103645,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1170",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586098528,
      "name": "scsi_eh_finish_cmd",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586249885,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1167",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586244624,
      "name": "scsi_eh_finish_cmd",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586493684,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1187",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586488240,
      "name": "scsi_eh_finish_cmd",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586641524,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1190",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586636048,
      "name": "scsi_eh_finish_cmd",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587440743,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1190",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_host_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_target_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587432144,
      "name": "scsi_eh_finish_cmd",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587509367,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1198",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_host_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_target_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587500848,
      "name": "scsi_eh_finish_cmd",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587390784,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1211",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_target_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587382560,
      "name": "scsi_eh_finish_cmd",
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
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587962464,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1230",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_target_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587954080,
      "name": "scsi_eh_finish_cmd",
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
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589318372,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1235",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_target_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589309552,
      "name": "scsi_eh_finish_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590883700,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1242",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_target_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590874288,
      "name": "scsi_eh_finish_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591227012,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1275",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_target_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591217472,
      "name": "scsi_eh_finish_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591574180,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1278",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_target_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591564656,
      "name": "scsi_eh_finish_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499538232,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1190",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499531872,
      "name": "scsi_eh_finish_cmd",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232002444,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1190",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231997084,
      "name": "scsi_eh_finish_cmd",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292829724,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1190",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292822736,
      "name": "scsi_eh_finish_cmd",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276740418,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1190",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276735592,
      "name": "scsi_eh_finish_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586332004,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1190",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586326528,
      "name": "scsi_eh_finish_cmd",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586173332,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1190",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586167856,
      "name": "scsi_eh_finish_cmd",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586589492,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1190",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586584016,
      "name": "scsi_eh_finish_cmd",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd * scmd, struct list_head * done_q)
```

```json
{
  "name": "scsi_eh_finish_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586701716,
      "name": "scsi_eh_finish_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:1190",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_get_sense"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586696240,
      "name": "scsi_eh_finish_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
