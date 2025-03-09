# Function: <code>sd_setup_write_same10_cmnd</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int sd_setup_write_same10_cmnd(struct scsi_cmnd * cmd, bool unmap)
```

```json
{
  "name": "sd_setup_write_same10_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585495856,
      "name": "sd_setup_write_same10_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:801",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585495856,
      "name": "sd_setup_write_same10_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
int sd_setup_write_same10_cmnd(struct scsi_cmnd * cmd, bool unmap)
```

```json
{
  "name": "sd_setup_write_same10_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585927152,
      "name": "sd_setup_write_same10_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:817",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585927152,
      "name": "sd_setup_write_same10_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
int sd_setup_write_same10_cmnd(struct scsi_cmnd * cmd, bool unmap)
```

```json
{
  "name": "sd_setup_write_same10_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586174544,
      "name": "sd_setup_write_same10_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:817",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586174544,
      "name": "sd_setup_write_same10_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd * cmd, bool unmap)
```

```json
{
  "name": "sd_setup_write_same10_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586327792,
      "name": "sd_setup_write_same10_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:827",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586327792,
      "name": "sd_setup_write_same10_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd * cmd, bool unmap)
```

```json
{
  "name": "sd_setup_write_same10_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586569920,
      "name": "sd_setup_write_same10_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:889",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586569920,
      "name": "sd_setup_write_same10_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd * cmd, bool unmap)
```

```json
{
  "name": "sd_setup_write_same10_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586717744,
      "name": "sd_setup_write_same10_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:889",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586717744,
      "name": "sd_setup_write_same10_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd * cmd, bool unmap)
```

```json
{
  "name": "sd_setup_write_same10_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587513088,
      "name": "sd_setup_write_same10_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:903",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_zeroes_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_zeroes_cmnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587513088,
      "name": "sd_setup_write_same10_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd * cmd, bool unmap)
```

```json
{
  "name": "sd_setup_write_same10_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587579408,
      "name": "sd_setup_write_same10_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:938",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_zeroes_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_zeroes_cmnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587579408,
      "name": "sd_setup_write_same10_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd * cmd, bool unmap)
```

```json
{
  "name": "sd_setup_write_same10_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587463600,
      "name": "sd_setup_write_same10_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:938",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587463600,
      "name": "sd_setup_write_same10_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd * cmd, bool unmap)
```

```json
{
  "name": "sd_setup_write_same10_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_setup_write_same10_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:938",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588036768,
      "name": "sd_setup_write_same10_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    },
    {
      "addr": 18446744071592529205,
      "name": "sd_setup_write_same10_cmnd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd * cmd, bool unmap)
```

```json
{
  "name": "sd_setup_write_same10_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_setup_write_same10_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:901",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589395920,
      "name": "sd_setup_write_same10_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071594400590,
      "name": "sd_setup_write_same10_cmnd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd * cmd, bool unmap)
```

```json
{
  "name": "sd_setup_write_same10_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_setup_write_same10_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:901",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590969328,
      "name": "sd_setup_write_same10_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071596260600,
      "name": "sd_setup_write_same10_cmnd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd * cmd, bool unmap)
```

```json
{
  "name": "sd_setup_write_same10_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_setup_write_same10_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:906",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591322800,
      "name": "sd_setup_write_same10_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    },
    {
      "addr": 18446744071596788824,
      "name": "sd_setup_write_same10_cmnd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd * cmd, bool unmap)
```

```json
{
  "name": "sd_setup_write_same10_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_setup_write_same10_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:946",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591671936,
      "name": "sd_setup_write_same10_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    },
    {
      "addr": 18446744071597697779,
      "name": "sd_setup_write_same10_cmnd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd * cmd, bool unmap)
```

```json
{
  "name": "sd_setup_write_same10_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499629048,
      "name": "sd_setup_write_same10_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:889",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499629048,
      "name": "sd_setup_write_same10_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd * cmd, bool unmap)
```

```json
{
  "name": "sd_setup_write_same10_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232082632,
      "name": "sd_setup_write_same10_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:889",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232082632,
      "name": "sd_setup_write_same10_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd * cmd, bool unmap)
```

```json
{
  "name": "sd_setup_write_same10_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292947504,
      "name": "sd_setup_write_same10_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:889",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292947504,
      "name": "sd_setup_write_same10_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd * cmd, bool unmap)
```

```json
{
  "name": "sd_setup_write_same10_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276811050,
      "name": "sd_setup_write_same10_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:889",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276811050,
      "name": "sd_setup_write_same10_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd * cmd, bool unmap)
```

```json
{
  "name": "sd_setup_write_same10_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586408224,
      "name": "sd_setup_write_same10_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:889",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586408224,
      "name": "sd_setup_write_same10_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd * cmd, bool unmap)
```

```json
{
  "name": "sd_setup_write_same10_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586284480,
      "name": "sd_setup_write_same10_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:889",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586284480,
      "name": "sd_setup_write_same10_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd * cmd, bool unmap)
```

```json
{
  "name": "sd_setup_write_same10_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586672304,
      "name": "sd_setup_write_same10_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:889",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586672304,
      "name": "sd_setup_write_same10_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd * cmd, bool unmap)
```

```json
{
  "name": "sd_setup_write_same10_cmnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586777904,
      "name": "sd_setup_write_same10_cmnd",
      "external": false,
      "loc": "drivers/scsi/sd.c:889",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586777904,
      "name": "sd_setup_write_same10_cmnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int sd_setup_write_same10_cmnd(struct scsi_cmnd * cmd, bool unmap)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>blk_status_t</code>
</li>
</ul>
</details>
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
