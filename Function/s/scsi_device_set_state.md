# Function: <code>scsi_device_set_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584800400,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2568",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584800400,
      "name": "scsi_device_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585160544,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2441",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585160544,
      "name": "scsi_device_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585354528,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2482",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585354528,
      "name": "scsi_device_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585440992,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2554",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_device_resume",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585440992,
      "name": "scsi_device_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585871712,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2632",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_device_resume",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585871712,
      "name": "scsi_device_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586117696,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2648",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_device_resume",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586117696,
      "name": "scsi_device_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586262960,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2239",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_device_resume",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586262960,
      "name": "scsi_device_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586506896,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2192",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_device_resume",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586506896,
      "name": "scsi_device_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586654784,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2239",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_device_resume",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586654784,
      "name": "scsi_device_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587450752,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2220",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/scsi/scsi_lib.c:device_resume_fn",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/ata/libata-scsi.c:ata_scsi_remove_dev",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587450752,
      "name": "scsi_device_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587518656,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2228",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/scsi/scsi_lib.c:device_resume_fn",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/ata/libata-scsi.c:ata_scsi_remove_dev",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587518656,
      "name": "scsi_device_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587400544,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2245",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/scsi/scsi_lib.c:device_resume_fn",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587400544,
      "name": "scsi_device_set_state",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587972416,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2238",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/scsi/scsi_lib.c:device_resume_fn",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587972416,
      "name": "scsi_device_set_state",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589328256,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2304",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/scsi/scsi_lib.c:device_resume_fn",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589328256,
      "name": "scsi_device_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590894432,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2309",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/scsi/scsi_lib.c:device_resume_fn",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590894432,
      "name": "scsi_device_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591237888,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2325",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_device_block",
        "drivers/scsi/scsi_lib.c:scsi_device_block",
        "drivers/scsi/scsi_lib.c:device_resume_fn",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591237888,
      "name": "scsi_device_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591585136,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2322",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_device_block",
        "drivers/scsi/scsi_lib.c:scsi_device_block",
        "drivers/scsi/scsi_lib.c:device_resume_fn",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591585136,
      "name": "scsi_device_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499552088,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2239",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_device_resume",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499552088,
      "name": "scsi_device_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232016560,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2239",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_device_resume",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232016560,
      "name": "scsi_device_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292847344,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2239",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_device_resume",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292847344,
      "name": "scsi_device_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276752056,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2239",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_device_resume",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276752056,
      "name": "scsi_device_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586345264,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2239",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_device_resume",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586345264,
      "name": "scsi_device_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586186592,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2239",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_device_resume",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586186592,
      "name": "scsi_device_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586602752,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2239",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_device_resume",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586602752,
      "name": "scsi_device_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int scsi_device_set_state(struct scsi_device * sdev, enum scsi_device_state state)
```

```json
{
  "name": "scsi_device_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586715056,
      "name": "scsi_device_set_state",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2239",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait",
        "drivers/scsi/scsi_lib.c:scsi_device_resume",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:store_state_field",
        "drivers/scsi/sd.c:sd_eh_action",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_offline_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586715056,
      "name": "scsi_device_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
