# Function: <code>scsi_probe_and_add_lun</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, int * bflagsp, struct scsi_device * * sdevp, int rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584816800,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1049",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584816800,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3685
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
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, int * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585178336,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1061",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585178336,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3733
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
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, int * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585373120,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1059",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585373120,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3749
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
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, int * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585457984,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1046",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585457984,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3522
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
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, blist_flags_t * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585888736,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1051",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585888736,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3547
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
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, blist_flags_t * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586136064,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1051",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586136064,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3653
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
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, blist_flags_t * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586276944,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1043",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586276944,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3644
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
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, blist_flags_t * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1043",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586522880,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2125
    },
    {
      "addr": 18446744071586529093,
      "name": "scsi_probe_and_add_lun.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, blist_flags_t * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1043",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586670976,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2125
    },
    {
      "addr": 18446744071586677189,
      "name": "scsi_probe_and_add_lun.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, blist_flags_t * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587470448,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1042",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587470448,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1136
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
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, blist_flags_t * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587538480,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1042",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587538480,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1136
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
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, blist_flags_t * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587420624,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1062",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587420624,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1079
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
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, blist_flags_t * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587993504,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1071",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587993504,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1079
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
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, blist_flags_t * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589351664,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1147",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589351664,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1115
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
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, blist_flags_t * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590919648,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1147",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590919648,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1105
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
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, blist_flags_t * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591263040,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1154",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591263040,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1099
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
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, blist_flags_t * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591610336,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1154",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591610336,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1146
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
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, blist_flags_t * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499571840,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1043",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499571840,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2188
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
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, blist_flags_t * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232034316,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1043",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232034316,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1232
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
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, blist_flags_t * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292869472,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1043",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292869472,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3004
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
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, blist_flags_t * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276766192,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1043",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276766192,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1932
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, blist_flags_t * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1043",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586361456,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2125
    },
    {
      "addr": 18446744071586367669,
      "name": "scsi_probe_and_add_lun.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, blist_flags_t * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1043",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586202768,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2125
    },
    {
      "addr": 18446744071586208981,
      "name": "scsi_probe_and_add_lun.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, blist_flags_t * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1043",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586618944,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2125
    },
    {
      "addr": 18446744071586625157,
      "name": "scsi_probe_and_add_lun.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target * starget, u64 lun, blist_flags_t * bflagsp, struct scsi_device * * sdevp, enum scsi_scan_mode rescan, void * hostdata)
```

```json
{
  "name": "scsi_probe_and_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_probe_and_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1043",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586731408,
      "name": "scsi_probe_and_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2127
    },
    {
      "addr": 18446744071586737605,
      "name": "scsi_probe_and_add_lun.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int rescan</code> ➡️ <code>enum scsi_scan_mode rescan</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int * bflagsp</code> ➡️ <code>blist_flags_t * bflagsp</code>
</li>
</ul>
</details>
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
