# Function: <code>scsi_target_reap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584822672,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:508",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584822672,
      "name": "scsi_target_reap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585184240,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:514",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585184240,
      "name": "scsi_target_reap",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585378960,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:512",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585378960,
      "name": "scsi_target_reap",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585464095,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:514",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device"
      ],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585461520,
      "name": "scsi_target_reap.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071585465104,
      "name": "scsi_target_reap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585893472,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:515",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585893472,
      "name": "scsi_target_reap",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586140064,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:515",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586140064,
      "name": "scsi_target_reap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586281728,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:507",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586281728,
      "name": "scsi_target_reap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586526272,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:507",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586526272,
      "name": "scsi_target_reap",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586674368,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:507",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586674368,
      "name": "scsi_target_reap",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587472848,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:506",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587472848,
      "name": "scsi_target_reap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587540880,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:506",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587540880,
      "name": "scsi_target_reap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587422960,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:525",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587422960,
      "name": "scsi_target_reap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587995840,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:531",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587995840,
      "name": "scsi_target_reap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589354208,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:590",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589354208,
      "name": "scsi_target_reap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590922304,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:590",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590922304,
      "name": "scsi_target_reap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591265712,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:590",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591265712,
      "name": "scsi_target_reap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591613104,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:590",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591613104,
      "name": "scsi_target_reap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499577236,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:507",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device"
      ],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499571232,
      "name": "scsi_target_reap.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446603336499578400,
      "name": "scsi_target_reap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232037696,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:507",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device"
      ],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232031748,
      "name": "scsi_target_reap.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 3232038720,
      "name": "scsi_target_reap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292874336,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:507",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292874336,
      "name": "scsi_target_reap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276770086,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:507",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276770086,
      "name": "scsi_target_reap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586364848,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:507",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586364848,
      "name": "scsi_target_reap",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586206160,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:507",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586206160,
      "name": "scsi_target_reap",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586622336,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:507",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586622336,
      "name": "scsi_target_reap",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_target_reap(struct scsi_target * starget)
```

```json
{
  "name": "scsi_target_reap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586734800,
      "name": "scsi_target_reap",
      "external": true,
      "loc": "drivers/scsi/scsi_scan.c:507",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_get_host_dev",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586734800,
      "name": "scsi_target_reap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
