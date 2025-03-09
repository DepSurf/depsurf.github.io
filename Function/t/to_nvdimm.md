# Function: <code>to_nvdimm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584712480,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:203",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:validate_dimm",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:commands_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/bus.c:nvdimm_ioctl",
        "drivers/nvdimm/dimm_devs.c:validate_dimm",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:commands_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584712480,
      "name": "to_nvdimm.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584712512,
      "name": "to_nvdimm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585063708,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:203",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:validate_dimm"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_ioctl",
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:validate_dimm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585063376,
      "name": "to_nvdimm.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585063408,
      "name": "to_nvdimm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585248092,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:212",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_ioctl",
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585247920,
      "name": "to_nvdimm.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585247952,
      "name": "to_nvdimm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585330172,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:221",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_ioctl",
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585330016,
      "name": "to_nvdimm.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071585330032,
      "name": "to_nvdimm",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585758172,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:228",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_ioctl",
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585757904,
      "name": "to_nvdimm.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071585757920,
      "name": "to_nvdimm",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586004277,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:230",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_ioctl",
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586004016,
      "name": "to_nvdimm.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586004032,
      "name": "to_nvdimm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586141413,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:218",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:security_store",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_ioctl",
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:security_store",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586141040,
      "name": "to_nvdimm.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586141056,
      "name": "to_nvdimm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586377061,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:215",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:__security_store",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:__security_store",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586381977,
      "name": "to_nvdimm.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071586382002,
      "name": "to_nvdimm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071586376720,
      "name": "to_nvdimm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586525349,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:215",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586524880,
      "name": "to_nvdimm.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586524896,
      "name": "to_nvdimm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587306469,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:205",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:security_show",
        "drivers/nvdimm/dimm_devs.c:security_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:validate_dimm",
        "drivers/nvdimm/dimm_devs.c:validate_dimm"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_ioctl",
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587305600,
      "name": "to_nvdimm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587368405,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:205",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible",
        "drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible",
        "drivers/nvdimm/dimm_devs.c:activate_store",
        "drivers/nvdimm/dimm_devs.c:activate_store",
        "drivers/nvdimm/dimm_devs.c:activate_show",
        "drivers/nvdimm/dimm_devs.c:activate_show",
        "drivers/nvdimm/dimm_devs.c:result_show",
        "drivers/nvdimm/dimm_devs.c:result_show",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:security_show",
        "drivers/nvdimm/dimm_devs.c:security_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:validate_dimm",
        "drivers/nvdimm/dimm_devs.c:validate_dimm"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_ioctl",
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587366720,
      "name": "to_nvdimm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587250389,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:205",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible",
        "drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible",
        "drivers/nvdimm/dimm_devs.c:activate_store",
        "drivers/nvdimm/dimm_devs.c:activate_store",
        "drivers/nvdimm/dimm_devs.c:activate_show",
        "drivers/nvdimm/dimm_devs.c:activate_show",
        "drivers/nvdimm/dimm_devs.c:result_show",
        "drivers/nvdimm/dimm_devs.c:result_show",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:security_show",
        "drivers/nvdimm/dimm_devs.c:security_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:commands_show",
        "drivers/nvdimm/dimm_devs.c:commands_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:validate_dimm",
        "drivers/nvdimm/dimm_devs.c:validate_dimm"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_ioctl",
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587248672,
      "name": "to_nvdimm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587817381,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:205",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible",
        "drivers/nvdimm/dimm_devs.c:activate_store",
        "drivers/nvdimm/dimm_devs.c:activate_show",
        "drivers/nvdimm/dimm_devs.c:result_show",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:security_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:commands_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:validate_dimm"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_ioctl",
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587814528,
      "name": "to_nvdimm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589166613,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:201",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible",
        "drivers/nvdimm/dimm_devs.c:activate_store",
        "drivers/nvdimm/dimm_devs.c:activate_show",
        "drivers/nvdimm/dimm_devs.c:result_show",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:security_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:commands_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:validate_dimm"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_ioctl",
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589163504,
      "name": "to_nvdimm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590718629,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:201",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible",
        "drivers/nvdimm/dimm_devs.c:activate_store",
        "drivers/nvdimm/dimm_devs.c:activate_show",
        "drivers/nvdimm/dimm_devs.c:result_show",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:security_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:validate_dimm"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_ioctl",
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590715248,
      "name": "to_nvdimm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591059797,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:201",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible",
        "drivers/nvdimm/dimm_devs.c:activate_store",
        "drivers/nvdimm/dimm_devs.c:activate_show",
        "drivers/nvdimm/dimm_devs.c:result_show",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:security_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:validate_dimm"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_ioctl",
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591056464,
      "name": "to_nvdimm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591404501,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:203",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible",
        "drivers/nvdimm/dimm_devs.c:activate_store",
        "drivers/nvdimm/dimm_devs.c:activate_show",
        "drivers/nvdimm/dimm_devs.c:result_show",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:security_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:validate_dimm"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_ioctl",
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591401168,
      "name": "to_nvdimm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499411252,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:215",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499410640,
      "name": "to_nvdimm.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446603336499410672,
      "name": "to_nvdimm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292650192,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:215",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_ioctl",
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:nvdimm_visible",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:commands_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292650192,
      "name": "to_nvdimm",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276640210,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:215",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_ioctl",
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276639640,
      "name": "to_nvdimm.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446743936276639668,
      "name": "to_nvdimm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586215829,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:215",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586215360,
      "name": "to_nvdimm.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586215376,
      "name": "to_nvdimm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586034197,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:215",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data"
      ],
      "caller_func": [
        "drivers/acpi/nfit/core.c:acpi_nfit_dimm_attr_visible",
        "drivers/acpi/nfit/core.c:acpi_nfit_dimm_attr_visible",
        "drivers/acpi/nfit/core.c:dirty_shutdown_show",
        "drivers/acpi/nfit/core.c:id_show",
        "drivers/acpi/nfit/core.c:flags_show",
        "drivers/acpi/nfit/core.c:dsm_mask_show",
        "drivers/acpi/nfit/core.c:family_show",
        "drivers/acpi/nfit/core.c:serial_show",
        "drivers/acpi/nfit/core.c:formats_show",
        "drivers/acpi/nfit/core.c:format1_show",
        "drivers/acpi/nfit/core.c:format1_show",
        "drivers/acpi/nfit/core.c:format_show",
        "drivers/acpi/nfit/core.c:subsystem_device_show",
        "drivers/acpi/nfit/core.c:subsystem_rev_id_show",
        "drivers/acpi/nfit/core.c:subsystem_vendor_show",
        "drivers/acpi/nfit/core.c:device_show",
        "drivers/acpi/nfit/core.c:rev_id_show",
        "drivers/acpi/nfit/core.c:vendor_show",
        "drivers/acpi/nfit/core.c:to_nfit_memdev",
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586033728,
      "name": "to_nvdimm.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586033744,
      "name": "to_nvdimm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586473317,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:215",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586472848,
      "name": "to_nvdimm.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586472864,
      "name": "to_nvdimm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nvdimm * to_nvdimm(struct device * dev)
```

```json
{
  "name": "to_nvdimm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586584997,
      "name": "to_nvdimm",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:215",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:match_dimm",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/dimm_devs.c:frozen_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:flags_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586584528,
      "name": "to_nvdimm.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586584544,
      "name": "to_nvdimm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct nvdimm * to_nvdimm(struct device * dev)
```
</details>
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
