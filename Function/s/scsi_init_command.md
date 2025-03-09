# Function: <code>scsi_init_command</code>

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
void scsi_init_command(struct scsi_device * dev, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585450976,
      "name": "scsi_init_command",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1152",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_prep_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585450976,
      "name": "scsi_init_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void scsi_init_command(struct scsi_device * dev, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585881904,
      "name": "scsi_init_command",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1190",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_prep_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585881904,
      "name": "scsi_init_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
void scsi_init_command(struct scsi_device * dev, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586128352,
      "name": "scsi_init_command",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1226",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_prep_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586128352,
      "name": "scsi_init_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
void scsi_init_command(struct scsi_device * dev, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586270880,
      "name": "scsi_init_command",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1157",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586270880,
      "name": "scsi_init_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
void scsi_init_command(struct scsi_device * dev, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586514544,
      "name": "scsi_init_command",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1122",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586514544,
      "name": "scsi_init_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
void scsi_init_command(struct scsi_device * dev, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586662544,
      "name": "scsi_init_command",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1134",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586662544,
      "name": "scsi_init_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
void scsi_init_command(struct scsi_device * dev, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587461616,
      "name": "scsi_init_command",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1106",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_lib.c:scsi_mq_prep_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587461616,
      "name": "scsi_init_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
void scsi_init_command(struct scsi_device * dev, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587529664,
      "name": "scsi_init_command",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1136",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_lib.c:scsi_prepare_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587529664,
      "name": "scsi_init_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
void scsi_init_command(struct scsi_device * dev, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587411680,
      "name": "scsi_init_command",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1108",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_lib.c:scsi_prepare_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587411680,
      "name": "scsi_init_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
void scsi_init_command(struct scsi_device * dev, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587984032,
      "name": "scsi_init_command",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1113",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_lib.c:scsi_prepare_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587984032,
      "name": "scsi_init_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
void scsi_init_command(struct scsi_device * dev, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589341616,
      "name": "scsi_init_command",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1153",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_lib.c:scsi_prepare_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589341616,
      "name": "scsi_init_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void scsi_init_command(struct scsi_device * dev, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590908800,
      "name": "scsi_init_command",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1158",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_lib.c:scsi_prepare_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590908800,
      "name": "scsi_init_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void scsi_init_command(struct scsi_device * dev, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591252096,
      "name": "scsi_init_command",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1159",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_lib.c:scsi_prepare_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591252096,
      "name": "scsi_init_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void scsi_init_command(struct scsi_device * dev, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591599328,
      "name": "scsi_init_command",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1158",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_lib.c:scsi_prepare_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591599328,
      "name": "scsi_init_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void scsi_init_command(struct scsi_device * dev, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499562888,
      "name": "scsi_init_command",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1134",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499562888,
      "name": "scsi_init_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void scsi_init_command(struct scsi_device * dev, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232024652,
      "name": "scsi_init_command",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1134",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232024652,
      "name": "scsi_init_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void scsi_init_command(struct scsi_device * dev, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292858384,
      "name": "scsi_init_command",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1134",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292858384,
      "name": "scsi_init_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
void scsi_init_command(struct scsi_device * dev, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276759258,
      "name": "scsi_init_command",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1134",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276759258,
      "name": "scsi_init_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void scsi_init_command(struct scsi_device * dev, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586353024,
      "name": "scsi_init_command",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1134",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586353024,
      "name": "scsi_init_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
void scsi_init_command(struct scsi_device * dev, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586194352,
      "name": "scsi_init_command",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1134",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586194352,
      "name": "scsi_init_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
void scsi_init_command(struct scsi_device * dev, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586610512,
      "name": "scsi_init_command",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1134",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586610512,
      "name": "scsi_init_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
void scsi_init_command(struct scsi_device * dev, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586722960,
      "name": "scsi_init_command",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1134",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586722960,
      "name": "scsi_init_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
void scsi_init_command(struct scsi_device * dev, struct scsi_cmnd * cmd)
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
