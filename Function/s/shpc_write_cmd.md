# Function: <code>shpc_write_cmd</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int shpc_write_cmd(struct slot * slot, u8 t_slot, u8 cmd)
```

```json
{
  "name": "shpc_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584343616,
      "name": "shpc_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:293",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584343616,
      "name": "shpc_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
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
int shpc_write_cmd(struct slot * slot, u8 t_slot, u8 cmd)
```

```json
{
  "name": "shpc_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584438800,
      "name": "shpc_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:293",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584438800,
      "name": "shpc_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
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
int shpc_write_cmd(struct slot * slot, u8 t_slot, u8 cmd)
```

```json
{
  "name": "shpc_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:293",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584635408,
      "name": "shpc_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
    },
    {
      "addr": 18446744071584637353,
      "name": "shpc_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
int shpc_write_cmd(struct slot * slot, u8 t_slot, u8 cmd)
```

```json
{
  "name": "shpc_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:293",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584773104,
      "name": "shpc_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
    },
    {
      "addr": 18446744071584775049,
      "name": "shpc_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
int shpc_write_cmd(struct slot * slot, u8 t_slot, u8 cmd)
```

```json
{
  "name": "shpc_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:293",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585464560,
      "name": "shpc_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
    },
    {
      "addr": 18446744071585466686,
      "name": "shpc_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int shpc_write_cmd(struct slot * slot, u8 t_slot, u8 cmd)
```

```json
{
  "name": "shpc_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:293",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585609104,
      "name": "shpc_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
    },
    {
      "addr": 18446744071591416424,
      "name": "shpc_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int shpc_write_cmd(struct slot * slot, u8 t_slot, u8 cmd)
```

```json
{
  "name": "shpc_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:288",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585487536,
      "name": "shpc_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 622
    },
    {
      "addr": 18446744071591358551,
      "name": "shpc_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int shpc_write_cmd(struct slot * slot, u8 t_slot, u8 cmd)
```

```json
{
  "name": "shpc_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:288",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585954704,
      "name": "shpc_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    },
    {
      "addr": 18446744071592387110,
      "name": "shpc_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int shpc_write_cmd(struct slot * slot, u8 t_slot, u8 cmd)
```

```json
{
  "name": "shpc_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:288",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587158688,
      "name": "shpc_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
    },
    {
      "addr": 18446744071594250900,
      "name": "shpc_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
int shpc_write_cmd(struct slot * slot, u8 t_slot, u8 cmd)
```

```json
{
  "name": "shpc_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:288",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588368064,
      "name": "shpc_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
    },
    {
      "addr": 18446744071596211423,
      "name": "shpc_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int shpc_write_cmd(struct slot * slot, u8 t_slot, u8 cmd)
```

```json
{
  "name": "shpc_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:288",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588644064,
      "name": "shpc_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 900
    },
    {
      "addr": 18446744071596736563,
      "name": "shpc_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int shpc_write_cmd(struct slot * slot, u8 t_slot, u8 cmd)
```

```json
{
  "name": "shpc_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:288",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588944464,
      "name": "shpc_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 900
    },
    {
      "addr": 18446744071597645147,
      "name": "shpc_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "shpc_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497035944,
      "name": "shpc_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:293",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497035944,
      "name": "shpc_write_cmd.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 944
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int shpc_write_cmd(struct slot * slot, u8 t_slot, u8 cmd)
```

```json
{
  "name": "shpc_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275694700,
      "name": "shpc_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:293",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275694700,
      "name": "shpc_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 800
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
int shpc_write_cmd(struct slot * slot, u8 t_slot, u8 cmd)
```

```json
{
  "name": "shpc_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:293",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584721920,
      "name": "shpc_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
    },
    {
      "addr": 18446744071584723865,
      "name": "shpc_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
int shpc_write_cmd(struct slot * slot, u8 t_slot, u8 cmd)
```

```json
{
  "name": "shpc_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:293",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584652688,
      "name": "shpc_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
    },
    {
      "addr": 18446744071584654633,
      "name": "shpc_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
int shpc_write_cmd(struct slot * slot, u8 t_slot, u8 cmd)
```

```json
{
  "name": "shpc_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:293",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584723264,
      "name": "shpc_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
    },
    {
      "addr": 18446744071584725209,
      "name": "shpc_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
int shpc_write_cmd(struct slot * slot, u8 t_slot, u8 cmd)
```

```json
{
  "name": "shpc_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:293",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584830848,
      "name": "shpc_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 581
    },
    {
      "addr": 18446744071584832777,
      "name": "shpc_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int shpc_write_cmd(struct slot * slot, u8 t_slot, u8 cmd)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int shpc_write_cmd(struct slot * slot, u8 t_slot, u8 cmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int shpc_write_cmd(struct slot * slot, u8 t_slot, u8 cmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int shpc_write_cmd(struct slot * slot, u8 t_slot, u8 cmd)
```
</details>
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
