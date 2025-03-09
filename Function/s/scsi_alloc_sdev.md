# Function: <code>scsi_alloc_sdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584815888,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:210",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584815888,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 751
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
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585177360,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:214",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585177360,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 762
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
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585372144,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:214",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585372144,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 762
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
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585457008,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:214",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585457008,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 765
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
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585887760,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:215",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585887760,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
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
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586135312,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:215",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586135312,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 751
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
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586276080,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:215",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586276080,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
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
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586522160,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:215",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586522160,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
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
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586670256,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:215",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586670256,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
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
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587469760,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:215",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587469760,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 685
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
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587537792,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:215",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587537792,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 685
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
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587419088,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:215",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587419088,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 844
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:215",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587992608,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 893
    },
    {
      "addr": 18446744071592527688,
      "name": "scsi_alloc_sdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589350144,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:278",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589350144,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 723
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
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590918000,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:278",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590918000,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
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
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591261392,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:278",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591261392,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
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
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591608688,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:278",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591608688,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
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
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499571256,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:215",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499571256,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232033672,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:215",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232033672,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
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
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292868688,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:215",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292868688,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
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
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276765642,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:215",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276765642,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
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
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586360736,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:215",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586360736,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
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
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586202048,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:215",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586202048,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
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
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586618224,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:215",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586618224,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
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
struct scsi_device * scsi_alloc_sdev(struct scsi_target * starget, u64 lun, void * hostdata)
```

```json
{
  "name": "scsi_alloc_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586730688,
      "name": "scsi_alloc_sdev",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:215",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586730688,
      "name": "scsi_alloc_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
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
