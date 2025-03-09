# Function: <code>ata_scsi_find_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584946576,
      "name": "ata_scsi_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:2881",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_activity_show",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_store",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:__ata_change_queue_depth",
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584946576,
      "name": "ata_scsi_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585312304,
      "name": "ata_scsi_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3021",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:__ata_change_queue_depth",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_store",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_show",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585312304,
      "name": "ata_scsi_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585513664,
      "name": "ata_scsi_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3102",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:__ata_change_queue_depth",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_store",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_show",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585513664,
      "name": "ata_scsi_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585601312,
      "name": "ata_scsi_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3081",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:__ata_change_queue_depth",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_store",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_show",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585601312,
      "name": "ata_scsi_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586032896,
      "name": "ata_scsi_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3082",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:__ata_change_queue_depth",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_store",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_show",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586032896,
      "name": "ata_scsi_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586279920,
      "name": "ata_scsi_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3085",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:__ata_change_queue_depth",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_store",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_show",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586279920,
      "name": "ata_scsi_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586420800,
      "name": "ata_scsi_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3080",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:__ata_change_queue_depth",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_store",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_show",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586420800,
      "name": "ata_scsi_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586666560,
      "name": "ata_scsi_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3084",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_store",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_show",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586666560,
      "name": "ata_scsi_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586813872,
      "name": "ata_scsi_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3084",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_store",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_show",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586813872,
      "name": "ata_scsi_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587621008,
      "name": "ata_scsi_find_dev",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:2796",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:ata_get_identity",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-sata.c:ata_scsi_activity_store",
        "drivers/ata/libata-sata.c:ata_scsi_activity_show",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587621008,
      "name": "ata_scsi_find_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587682480,
      "name": "ata_scsi_find_dev",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:2796",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:ata_get_identity",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-sata.c:ata_scsi_activity_store",
        "drivers/ata/libata-sata.c:ata_scsi_activity_show",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587682480,
      "name": "ata_scsi_find_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587565056,
      "name": "ata_scsi_find_dev",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:2792",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show"
      ],
      "caller_func": [
        "drivers/ata/libata-sata.c:ata_scsi_activity_store",
        "drivers/ata/libata-sata.c:ata_scsi_activity_show",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587563408,
      "name": "ata_scsi_find_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588145552,
      "name": "ata_scsi_find_dev",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:2752",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show"
      ],
      "caller_func": [
        "drivers/ata/libata-sata.c:ata_scsi_activity_store",
        "drivers/ata/libata-sata.c:ata_scsi_activity_show",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_show",
        "drivers/ata/libata-sata.c:ata_ncq_prio_supported_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588142992,
      "name": "ata_scsi_find_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589522752,
      "name": "ata_scsi_find_dev",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:2756",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-sata.c:ata_scsi_activity_store",
        "drivers/ata/libata-sata.c:ata_scsi_activity_show",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_show",
        "drivers/ata/libata-sata.c:ata_ncq_prio_supported_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589522752,
      "name": "ata_scsi_find_dev",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591109200,
      "name": "ata_scsi_find_dev",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:2769",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-sata.c:ata_scsi_change_queue_depth",
        "drivers/ata/libata-sata.c:ata_scsi_activity_store",
        "drivers/ata/libata-sata.c:ata_scsi_activity_show",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_show",
        "drivers/ata/libata-sata.c:ata_ncq_prio_supported_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591109200,
      "name": "ata_scsi_find_dev",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591466880,
      "name": "ata_scsi_find_dev",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:2917",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-sata.c:ata_change_queue_depth",
        "drivers/ata/libata-sata.c:ata_scsi_activity_store",
        "drivers/ata/libata-sata.c:ata_scsi_activity_show",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_show",
        "drivers/ata/libata-sata.c:ata_ncq_prio_supported_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591466880,
      "name": "ata_scsi_find_dev",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591815232,
      "name": "ata_scsi_find_dev",
      "external": true,
      "loc": "drivers/ata/libata-scsi.c:2789",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-sata.c:ata_change_queue_depth",
        "drivers/ata/libata-sata.c:ata_scsi_activity_store",
        "drivers/ata/libata-sata.c:ata_scsi_activity_show",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_show",
        "drivers/ata/libata-sata.c:ata_ncq_prio_supported_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591815232,
      "name": "ata_scsi_find_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499728976,
      "name": "ata_scsi_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3084",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:__ata_change_queue_depth",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_store",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_show",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499728976,
      "name": "ata_scsi_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232186632,
      "name": "ata_scsi_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3084",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:__ata_change_queue_depth",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_store",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_show",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232186632,
      "name": "ata_scsi_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293078848,
      "name": "ata_scsi_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3084",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_store",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_show",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293078848,
      "name": "ata_scsi_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276899002,
      "name": "ata_scsi_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3084",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:__ata_change_queue_depth",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_store",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_show",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276899002,
      "name": "ata_scsi_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586572448,
      "name": "ata_scsi_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3084",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_store",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_show",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586572448,
      "name": "ata_scsi_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586441024,
      "name": "ata_scsi_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3084",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_store",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_show",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586441024,
      "name": "ata_scsi_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586768432,
      "name": "ata_scsi_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3084",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_store",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_show",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586768432,
      "name": "ata_scsi_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
struct ata_device * ata_scsi_find_dev(struct ata_port * ap, const struct scsi_device * scsidev)
```

```json
{
  "name": "ata_scsi_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586874496,
      "name": "ata_scsi_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3084",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_store",
        "drivers/ata/libata-scsi.c:ata_scsi_activity_show",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586874496,
      "name": "ata_scsi_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
