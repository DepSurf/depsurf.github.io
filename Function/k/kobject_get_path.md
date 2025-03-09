# Function: <code>kobject_get_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
char * kobject_get_path(struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582954784,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:146",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582954784,
      "name": "kobject_get_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
char * kobject_get_path(struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583242352,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:146",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "drivers/base/power/domain.c:pm_genpd_summary_show",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583242352,
      "name": "kobject_get_path",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
char * kobject_get_path(struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583357664,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:146",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "drivers/base/power/domain.c:pm_genpd_summary_show",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583357664,
      "name": "kobject_get_path",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
char * kobject_get_path(struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588208032,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:146",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_summary_show",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588208032,
      "name": "kobject_get_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
char * kobject_get_path(struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588757440,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:146",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_devices_show",
        "drivers/base/power/domain.c:genpd_summary_show",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588757440,
      "name": "kobject_get_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
char * kobject_get_path(struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589135632,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:163",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_devices_show",
        "drivers/base/power/domain.c:genpd_summary_show",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589135632,
      "name": "kobject_get_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
char * kobject_get_path(struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589370480,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:163",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:devices_show",
        "drivers/base/power/domain.c:summary_show",
        "drivers/usb/core/hub.c:port_event",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589370480,
      "name": "kobject_get_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
char * kobject_get_path(struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589828992,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:171",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:devices_show",
        "drivers/base/power/domain.c:summary_show",
        "drivers/usb/core/hub.c:port_event",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589828992,
      "name": "kobject_get_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
char * kobject_get_path(struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590055136,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:171",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:devices_show",
        "drivers/base/power/domain.c:summary_show",
        "drivers/usb/core/hub.c:port_event",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590055136,
      "name": "kobject_get_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
char * kobject_get_path(struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585048768,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:171",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "drivers/base/power/domain.c:devices_show",
        "drivers/base/power/domain.c:genpd_summary_one",
        "drivers/usb/core/hub.c:port_over_current_notify",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585048768,
      "name": "kobject_get_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
char * kobject_get_path(struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585198560,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:171",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "drivers/base/power/domain.c:devices_show",
        "drivers/base/power/domain.c:genpd_summary_one",
        "drivers/usb/core/hub.c:port_over_current_notify",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585198560,
      "name": "kobject_get_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
char * kobject_get_path(struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585081536,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:171",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "drivers/base/power/domain.c:devices_show",
        "drivers/base/power/domain.c:genpd_summary_one",
        "drivers/usb/core/hub.c:port_event",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585081536,
      "name": "kobject_get_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
char * kobject_get_path(struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585528480,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:171",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "drivers/base/power/domain.c:devices_show",
        "drivers/base/power/domain.c:genpd_summary_one",
        "drivers/usb/core/hub.c:port_event",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585528480,
      "name": "kobject_get_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
char * kobject_get_path(struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586682352,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:139",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "drivers/base/power/domain.c:devices_show",
        "drivers/base/power/domain.c:genpd_summary_one",
        "drivers/usb/core/hub.c:port_event",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586682352,
      "name": "kobject_get_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
char * kobject_get_path(const struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595763184,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:143",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:devices_show",
        "drivers/base/power/domain.c:genpd_summary_one",
        "drivers/usb/core/hub.c:port_event",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595763184,
      "name": "kobject_get_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
char * kobject_get_path(const struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596287568,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:145",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:devices_show",
        "drivers/base/power/domain.c:genpd_summary_one",
        "drivers/usb/core/hub.c:port_event",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596287568,
      "name": "kobject_get_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
char * kobject_get_path(const struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597172432,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:152",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pmdomain/core.c:devices_show",
        "drivers/pmdomain/core.c:genpd_summary_one",
        "drivers/usb/core/hub.c:port_event",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597172432,
      "name": "kobject_get_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
char * kobject_get_path(struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503830232,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:171",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:devices_show",
        "drivers/base/power/domain.c:summary_show",
        "drivers/usb/core/hub.c:port_event",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503830232,
      "name": "kobject_get_path",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
char * kobject_get_path(struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236451260,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:171",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:devices_show",
        "drivers/base/power/domain.c:summary_show",
        "drivers/usb/core/hub.c:port_event",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236451260,
      "name": "kobject_get_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
char * kobject_get_path(struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297679792,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:171",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:devices_show",
        "drivers/base/power/domain.c:summary_show",
        "drivers/usb/core/hub.c:port_event",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297679792,
      "name": "kobject_get_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
char * kobject_get_path(struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279723298,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:171",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:devices_show",
        "drivers/base/power/domain.c:summary_show",
        "drivers/usb/core/hub.c:port_event",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279723298,
      "name": "kobject_get_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
char * kobject_get_path(struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589657392,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:171",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:devices_show",
        "drivers/base/power/domain.c:summary_show",
        "drivers/usb/core/hub.c:port_event",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589657392,
      "name": "kobject_get_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
char * kobject_get_path(struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589383216,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:171",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:devices_show",
        "drivers/base/power/domain.c:summary_show",
        "drivers/usb/core/hub.c:port_event",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589383216,
      "name": "kobject_get_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
char * kobject_get_path(struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590100768,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:171",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:devices_show",
        "drivers/base/power/domain.c:summary_show",
        "drivers/usb/core/hub.c:port_event",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590100768,
      "name": "kobject_get_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
char * kobject_get_path(struct kobject * kobj, gfp_t gfp_mask)
```

```json
{
  "name": "kobject_get_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590151072,
      "name": "kobject_get_path",
      "external": true,
      "loc": "lib/kobject.c:171",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:devices_show",
        "drivers/base/power/domain.c:summary_show",
        "drivers/usb/core/hub.c:port_event",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_devices_seq_show",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590151072,
      "name": "kobject_get_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct kobject * kobj</code> ➡️ <code>const struct kobject * kobj</code>
</li>
</ul>
</details>
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
