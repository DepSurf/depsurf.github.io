# Function: <code>scsi_host_set_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584775568,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:66",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584775568,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585135632,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:66",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585135632,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585329776,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:66",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585329776,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585415248,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:66",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585415248,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585845232,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:66",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585845232,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586094080,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:72",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586094080,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586240208,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:72",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586240208,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586483632,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:73",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586483632,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586631424,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:73",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586631424,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587427520,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:74",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_restart_operations",
        "drivers/scsi/scsi_error.c:scsi_restart_operations",
        "drivers/scsi/scsi_error.c:scsi_restart_operations",
        "drivers/scsi/scsi_error.c:scsi_restart_operations",
        "drivers/scsi/scsi_error.c:scsi_restart_operations",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587427520,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587497200,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:74",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_restart_operations",
        "drivers/scsi/scsi_error.c:scsi_restart_operations",
        "drivers/scsi/scsi_error.c:scsi_restart_operations",
        "drivers/scsi/scsi_error.c:scsi_restart_operations",
        "drivers/scsi/scsi_error.c:scsi_restart_operations",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587497200,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587378992,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:74",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587378992,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587946592,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:74",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587946592,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589302032,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:75",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589302032,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590865648,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:75",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590865648,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591208816,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:75",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591208816,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591556000,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:75",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591556000,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499525096,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:73",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499525096,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231992120,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:73",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231992120,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292816432,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:73",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292816432,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276731628,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:73",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276731628,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586321904,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:73",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586321904,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586163232,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:73",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586163232,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586579392,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:73",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586579392,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int scsi_host_set_state(struct Scsi_Host * shost, enum scsi_host_state state)
```

```json
{
  "name": "scsi_host_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586691616,
      "name": "scsi_host_set_state",
      "external": true,
      "loc": "drivers/scsi/hosts.c:73",
      "file": "drivers/scsi/hosts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh",
        "drivers/scsi/scsi_sysfs.c:store_shost_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586691616,
      "name": "scsi_host_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
