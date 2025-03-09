# Function: <code>scsi_check_sense</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584784464,
      "name": "scsi_check_sense",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:455",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584784464,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1048
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
int scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585144768,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:455",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585144768,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1028
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
int scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585339056,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:455",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585339056,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1028
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
int scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585423808,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:440",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585423808,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1150
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
int scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585853856,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:461",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585853856,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1239
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
int scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586100560,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:483",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586100560,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1230
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
int scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586246640,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:480",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586246640,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1308
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
int scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586490240,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:481",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586490240,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1315
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
int scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586638064,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:481",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586638064,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1315
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
int scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587434832,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:481",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587434832,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 800
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
int scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587503504,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:489",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587503504,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
enum scsi_disposition scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587385232,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:501",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587385232,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
enum scsi_disposition scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587956752,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:526",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587956752,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
enum scsi_disposition scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589312832,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:530",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589312832,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
enum scsi_disposition scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590877824,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:537",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-eh.c:ata_eh_analyze_tf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590877824,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
enum scsi_disposition scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591221008,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:537",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-eh.c:ata_eh_get_success_sense",
        "drivers/ata/libata-eh.c:ata_eh_analyze_tf",
        "drivers/ata/libata-sata.c:ata_eh_read_sense_success_ncq_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591221008,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 817
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
enum scsi_disposition scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591568192,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:539",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-eh.c:ata_eh_get_success_sense",
        "drivers/ata/libata-eh.c:ata_eh_analyze_tf",
        "drivers/ata/libata-sata.c:ata_eh_read_sense_success_ncq_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591568192,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 812
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
int scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499533272,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:481",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499533272,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1424
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
int scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231999004,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:481",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231999004,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1360
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
int scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292825456,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:481",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292825456,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1636
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
int scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276737482,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:481",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276737482,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1150
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
int scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586328544,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:481",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586328544,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1315
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
int scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586169872,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:481",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586169872,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1315
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
int scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586586032,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:481",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586586032,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1315
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
int scsi_check_sense(struct scsi_cmnd * scmd)
```

```json
{
  "name": "scsi_check_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586698256,
      "name": "scsi_check_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_error.c:481",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_decide_disposition",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586698256,
      "name": "scsi_check_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1315
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>enum scsi_disposition</code>
</li>
</ul>
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
