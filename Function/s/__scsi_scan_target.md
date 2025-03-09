# Function: <code>__scsi_scan_target</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, int rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584823088,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1533",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584823088,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585184656,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1555",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585184656,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 589
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
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585379376,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1549",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585379376,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 589
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
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585462272,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1532",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585462272,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1531
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
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585893888,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1538",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585893888,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1541
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1538",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_host_selected",
        "drivers/scsi/scsi_scan.c:scsi_scan_host_selected",
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586140480,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1558
    },
    {
      "addr": 18446744071586144077,
      "name": "__scsi_scan_target.cold.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1530",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586282144,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1496
    },
    {
      "addr": 18446744071586285661,
      "name": "__scsi_scan_target.cold.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1531",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586526672,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
    },
    {
      "addr": 18446744071586529164,
      "name": "__scsi_scan_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1531",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586674768,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
    },
    {
      "addr": 18446744071586677260,
      "name": "__scsi_scan_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1530",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587473328,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
    },
    {
      "addr": 18446744071587475812,
      "name": "__scsi_scan_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1530",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587541360,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
    },
    {
      "addr": 18446744071591520784,
      "name": "__scsi_scan_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1548",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587423456,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
    },
    {
      "addr": 18446744071591462573,
      "name": "__scsi_scan_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1557",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587996336,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
    },
    {
      "addr": 18446744071592527762,
      "name": "__scsi_scan_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1633",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589354768,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
    },
    {
      "addr": 18446744071594399377,
      "name": "__scsi_scan_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590922912,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1633",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590922912,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591266320,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1645",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591266320,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591613712,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1662",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591613712,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499576272,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1531",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499576272,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 588
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
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232036648,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1531",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232036648,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
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
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292875072,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1531",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292875072,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 740
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
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276770574,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1531",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276770574,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1531",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586365248,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
    },
    {
      "addr": 18446744071586367740,
      "name": "__scsi_scan_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1531",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586206560,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
    },
    {
      "addr": 18446744071586209052,
      "name": "__scsi_scan_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1531",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586622736,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
    },
    {
      "addr": 18446744071586625228,
      "name": "__scsi_scan_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void __scsi_scan_target(struct device * parent, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan)
```

```json
{
  "name": "__scsi_scan_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__scsi_scan_target",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:1531",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_scan_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586735200,
      "name": "__scsi_scan_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
    },
    {
      "addr": 18446744071586737676,
      "name": "__scsi_scan_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
