# Function: <code>scsi_host_busy</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int scsi_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_host_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586238432,
      "name": "scsi_host_busy",
      "external": true,
      "loc": "drivers/scsi/hosts.c:557",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_sysfs.c:show_host_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586238432,
      "name": "scsi_host_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int scsi_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_host_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586481872,
      "name": "scsi_host_busy",
      "external": true,
      "loc": "drivers/scsi/hosts.c:561",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_sysfs.c:show_host_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586481872,
      "name": "scsi_host_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int scsi_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_host_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586629664,
      "name": "scsi_host_busy",
      "external": true,
      "loc": "drivers/scsi/hosts.c:561",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_sysfs.c:show_host_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586629664,
      "name": "scsi_host_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int scsi_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_host_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587425984,
      "name": "scsi_host_busy",
      "external": true,
      "loc": "drivers/scsi/hosts.c:574",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_sysfs.c:show_host_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587425984,
      "name": "scsi_host_busy",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int scsi_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_host_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587495648,
      "name": "scsi_host_busy",
      "external": true,
      "loc": "drivers/scsi/hosts.c:577",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_sysfs.c:show_host_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587495648,
      "name": "scsi_host_busy",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int scsi_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_host_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587377472,
      "name": "scsi_host_busy",
      "external": true,
      "loc": "drivers/scsi/hosts.c:581",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_sysfs.c:show_host_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587377472,
      "name": "scsi_host_busy",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int scsi_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_host_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587945056,
      "name": "scsi_host_busy",
      "external": true,
      "loc": "drivers/scsi/hosts.c:583",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_sysfs.c:show_host_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587945056,
      "name": "scsi_host_busy",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int scsi_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_host_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589300464,
      "name": "scsi_host_busy",
      "external": true,
      "loc": "drivers/scsi/hosts.c:585",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_sysfs.c:show_host_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589300464,
      "name": "scsi_host_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int scsi_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_host_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590863712,
      "name": "scsi_host_busy",
      "external": true,
      "loc": "drivers/scsi/hosts.c:600",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_sysfs.c:show_host_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590863712,
      "name": "scsi_host_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int scsi_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_host_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591206880,
      "name": "scsi_host_busy",
      "external": true,
      "loc": "drivers/scsi/hosts.c:600",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_sysfs.c:show_host_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591206880,
      "name": "scsi_host_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int scsi_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_host_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591554064,
      "name": "scsi_host_busy",
      "external": true,
      "loc": "drivers/scsi/hosts.c:600",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_dec_host_busy",
        "drivers/scsi/scsi_sysfs.c:show_host_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591554064,
      "name": "scsi_host_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int scsi_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_host_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499523288,
      "name": "scsi_host_busy",
      "external": true,
      "loc": "drivers/scsi/hosts.c:561",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_sysfs.c:show_host_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499523288,
      "name": "scsi_host_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int scsi_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_host_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231990428,
      "name": "scsi_host_busy",
      "external": true,
      "loc": "drivers/scsi/hosts.c:561",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_sysfs.c:show_host_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231990428,
      "name": "scsi_host_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int scsi_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_host_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292814064,
      "name": "scsi_host_busy",
      "external": true,
      "loc": "drivers/scsi/hosts.c:561",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_sysfs.c:show_host_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292814064,
      "name": "scsi_host_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int scsi_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_host_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276729818,
      "name": "scsi_host_busy",
      "external": true,
      "loc": "drivers/scsi/hosts.c:561",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_sysfs.c:show_host_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276729818,
      "name": "scsi_host_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int scsi_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_host_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586320144,
      "name": "scsi_host_busy",
      "external": true,
      "loc": "drivers/scsi/hosts.c:561",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_sysfs.c:show_host_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586320144,
      "name": "scsi_host_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int scsi_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_host_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586161472,
      "name": "scsi_host_busy",
      "external": true,
      "loc": "drivers/scsi/hosts.c:561",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_sysfs.c:show_host_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586161472,
      "name": "scsi_host_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int scsi_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_host_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586577632,
      "name": "scsi_host_busy",
      "external": true,
      "loc": "drivers/scsi/hosts.c:561",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_sysfs.c:show_host_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586577632,
      "name": "scsi_host_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int scsi_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_host_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586689856,
      "name": "scsi_host_busy",
      "external": true,
      "loc": "drivers/scsi/hosts.c:561",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_log_completion",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_sysfs.c:show_host_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586689856,
      "name": "scsi_host_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int scsi_host_busy(struct Scsi_Host * shost)
```
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
