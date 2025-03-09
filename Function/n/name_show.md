# Function: <code>name_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583927040,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:373",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585621232,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/rtc-sysfs.c:28",
      "file": "drivers/rtc/rtc-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585652080,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-dev.c:100",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585695488,
      "name": "name_show",
      "external": false,
      "loc": "drivers/thermal/thermal_hwmon.c:62",
      "file": "drivers/thermal/thermal_hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586110016,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:441",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586112096,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:210",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_update_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586126976,
      "name": "name_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:359",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587302944,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:585",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583927040,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071585621232,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071585652080,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071585695488,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071586110016,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071586112096,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586126976,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587302944,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584258224,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:349",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586016016,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/rtc-sysfs.c:28",
      "file": "drivers/rtc/rtc-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586050064,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-dev.c:102",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586092032,
      "name": "name_show",
      "external": false,
      "loc": "drivers/thermal/thermal_hwmon.c:62",
      "file": "drivers/thermal/thermal_hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586523472,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:440",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586527898,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:198",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_update_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586540704,
      "name": "name_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:359",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587773744,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:607",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258224,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071586016016,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071586050064,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071586092032,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071586523472,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071586526096,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586540704,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587773744,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579787008,
      "name": "name_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:203",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584439744,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:350",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586211824,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/rtc-sysfs.c:28",
      "file": "drivers/rtc/rtc-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586247664,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-dev.c:102",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586292320,
      "name": "name_show",
      "external": false,
      "loc": "drivers/thermal/thermal_hwmon.c:62",
      "file": "drivers/thermal/thermal_hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586703168,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:440",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586706711,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:384",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586722432,
      "name": "name_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:359",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587988944,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:607",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787008,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071584439744,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071586211824,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071586247664,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071586292320,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071586703168,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071586706240,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586722432,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587988944,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579784528,
      "name": "name_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:215",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584523136,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:350",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586301872,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/rtc-sysfs.c:28",
      "file": "drivers/rtc/rtc-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586337712,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-dev.c:102",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586365728,
      "name": "name_show",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:66",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586391344,
      "name": "name_show",
      "external": false,
      "loc": "drivers/thermal/thermal_hwmon.c:62",
      "file": "drivers/thermal/thermal_hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586828320,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:440",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586832401,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:387",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586848832,
      "name": "name_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:359",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588146976,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:665",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579784528,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071584523136,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071586301872,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071586337712,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071586365728,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071586391344,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071586828320,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071586831872,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586848832,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071588146976,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579818112,
      "name": "name_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:213",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584933200,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:350",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586765360,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/rtc-sysfs.c:28",
      "file": "drivers/rtc/rtc-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586801728,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-dev.c:103",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586830544,
      "name": "name_show",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:66",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586854560,
      "name": "name_show",
      "external": false,
      "loc": "drivers/thermal/thermal_hwmon.c:62",
      "file": "drivers/thermal/thermal_hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587316048,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:440",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587320177,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:375",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587336576,
      "name": "name_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:359",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588695216,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:665",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818112,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071584933200,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071586765360,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071586801728,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071586830544,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071586854560,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587316048,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071587319648,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071587336576,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071588695216,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579851856,
      "name": "name_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:229",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585166128,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:420",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587037264,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/rtc-sysfs.c:28",
      "file": "drivers/rtc/rtc-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587075184,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-dev.c:103",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587097296,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:78",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587122752,
      "name": "name_show",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:66",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587618848,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:440",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587623063,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:375",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587639856,
      "name": "name_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:359",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589061968,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:679",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851856,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071585166128,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071587037264,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071587075184,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071587097296,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587122752,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587618848,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071587622528,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071587639856,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071589061968,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579898736,
      "name": "name_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:229",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585277664,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:604",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587196896,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:28",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587236032,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-dev.c:103",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587274496,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:78",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587300880,
      "name": "name_show",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:69",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587748416,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:440",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587752503,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:375",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587768768,
      "name": "name_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:359",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589287664,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:681",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898736,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071585277664,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071587196896,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071587236032,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071587274496,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587300880,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587748416,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071587751968,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071587768768,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071589287664,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579933552,
      "name": "name_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:230",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585489856,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:586",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587462384,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:24",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587502128,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-dev.c:95",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587543984,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:64",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587571376,
      "name": "name_show",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:66",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588052960,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:437",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588057185,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:367",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588073536,
      "name": "name_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:347",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589744096,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:669",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933552,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071585489856,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071587462384,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071587502128,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071587543984,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587571376,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071588052960,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071588056736,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588073536,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071589744096,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579983680,
      "name": "name_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:230",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585630448,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:592",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586266480,
      "name": "name_show",
      "external": false,
      "loc": "drivers/base/power/wakeup_stats.c:89",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587665504,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:24",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587705264,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-dev.c:95",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587746752,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:64",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587774704,
      "name": "name_show",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:67",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588243824,
      "name": "name_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:117",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588250672,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1113",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588258928,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:437",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588263089,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:367",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588279344,
      "name": "name_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:347",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589967808,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:669",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579983680,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071585630448,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071586266480,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587665504,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071587705264,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071587746752,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587774704,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071588243824,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071588250672,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071588258928,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071588262640,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588279344,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071589967808,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580032096,
      "name": "name_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:230",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586354768,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:595",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587035216,
      "name": "name_show",
      "external": false,
      "loc": "drivers/base/power/wakeup_stats.c:89",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588532928,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:24",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588544944,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:469",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588574128,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-dev.c:97",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588591504,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:64",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588621280,
      "name": "name_show",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:68",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589120672,
      "name": "name_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:118",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589128416,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1260",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589138192,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:437",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589141504,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:367",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589160096,
      "name": "name_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:347",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590997840,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:669",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580032096,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071586354768,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071587035216,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588532928,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071588544944,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071588574128,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071588591504,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071588621280,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071589120672,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071589128416,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071589138192,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071589141504,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071589160096,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071590997840,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580015808,
      "name": "name_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:230",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586472288,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:618",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587118608,
      "name": "name_show",
      "external": false,
      "loc": "drivers/base/power/wakeup_stats.c:91",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588557520,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:24",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588569888,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:597",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588598208,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-dev.c:97",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588614560,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:64",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588641376,
      "name": "name_show",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:68",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589118560,
      "name": "name_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:219",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589126752,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1341",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589137360,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:439",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589140480,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:367",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589157056,
      "name": "name_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:346",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591062512,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:681",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015808,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071586472288,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071587118608,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588557520,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071588569888,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071588598208,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071588614560,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071588641376,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071589118560,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071589126752,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071589137360,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071589140480,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071589157056,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071591062512,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580016368,
      "name": "name_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:230",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586356176,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:619",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587005008,
      "name": "name_show",
      "external": false,
      "loc": "drivers/base/power/wakeup_stats.c:91",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588440816,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:24",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588453216,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:641",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588484112,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-dev.c:97",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588499488,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:64",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588525728,
      "name": "name_show",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:68",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589008336,
      "name": "name_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:224",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589016528,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1359",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589027392,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:439",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589030624,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:367",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589050768,
      "name": "name_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:346",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590993280,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:682",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016368,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071586356176,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071587005008,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588440816,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071588453216,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071588484112,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071588499488,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071588525728,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071589008336,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071589016528,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071589027392,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071589030624,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071589050768,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071590993280,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580148576,
      "name": "name_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:230",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586633552,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pnp/card.c:184",
      "file": "drivers/pnp/card.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586876608,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:609",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587571536,
      "name": "name_show",
      "external": false,
      "loc": "drivers/base/power/wakeup_stats.c:91",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589108272,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:24",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589121200,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:642",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589152496,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-dev.c:98",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589168192,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:64",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589199568,
      "name": "name_show",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:68",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589722800,
      "name": "name_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:224",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589731504,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1359",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589743024,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:439",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589746384,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:367",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589767952,
      "name": "name_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:346",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591831024,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:682",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580148576,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071586633552,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071586876608,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071587571536,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071589108272,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071589121200,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071589152496,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071589168192,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071589199568,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071589722800,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071589731504,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071589743024,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071589746384,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071589767952,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071591831024,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580291040,
      "name": "name_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:230",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587899488,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pnp/card.c:184",
      "file": "drivers/pnp/card.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588164544,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:610",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588906640,
      "name": "name_show",
      "external": false,
      "loc": "drivers/base/power/wakeup_stats.c:91",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590555264,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:24",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590570272,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:643",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590603616,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-dev.c:98",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590623248,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:64",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590660288,
      "name": "name_show",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:70",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591231072,
      "name": "name_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:213",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591242448,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1389",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591253632,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:439",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591259457,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:367",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591277600,
      "name": "name_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:346",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593545312,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:682",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580291040,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071587899488,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071588164544,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071588906640,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071590555264,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071590570272,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071590603616,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071590623248,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071590660288,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071591231072,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071591242448,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071591253632,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071591258800,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071591277600,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071593545312,
      "name": "name_show",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580501440,
      "name": "name_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:230",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589249216,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pnp/card.c:184",
      "file": "drivers/pnp/card.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589561568,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:610",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590418352,
      "name": "name_show",
      "external": false,
      "loc": "drivers/base/power/wakeup_stats.c:91",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592209232,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:25",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592224128,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:644",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592263248,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-dev.c:98",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592285808,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:64",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592327552,
      "name": "name_show",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:71",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592980416,
      "name": "name_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:213",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592995040,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1391",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593008256,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:439",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593014769,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:377",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593025456,
      "name": "name_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:347",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595466880,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:682",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580501440,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071589249216,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071589561568,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071590418352,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071592209232,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071592224128,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071592263248,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071592285808,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071592327552,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071592980416,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071592995040,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071593008256,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071593014080,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071593025456,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071595466880,
      "name": "name_show",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580573216,
      "name": "name_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:262",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589545968,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pnp/card.c:184",
      "file": "drivers/pnp/card.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589863472,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:676",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590737856,
      "name": "name_show",
      "external": false,
      "loc": "drivers/base/power/wakeup_stats.c:91",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592633440,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:25",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592648592,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:659",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592688576,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-dev.c:98",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592710320,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:64",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592754400,
      "name": "name_show",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:71",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593431424,
      "name": "name_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:213",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593446512,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1392",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593459776,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:439",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593466422,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:387",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593477152,
      "name": "name_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:347",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595973952,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:682",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580573216,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071589545968,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071589863472,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071590737856,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071592633440,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071592648592,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071592688576,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071592710320,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071592754400,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071593431424,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071593446512,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071593459776,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071593465616,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071593477152,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071595973952,
      "name": "name_show",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580637456,
      "name": "name_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:262",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589854352,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pnp/card.c:184",
      "file": "drivers/pnp/card.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590200976,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:678",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591099824,
      "name": "name_show",
      "external": false,
      "loc": "drivers/base/power/wakeup_stats.c:91",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593378256,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:25",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593393744,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:662",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593433392,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-dev.c:98",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593456464,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:64",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593502384,
      "name": "name_show",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:71",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594177472,
      "name": "name_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:213",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594192912,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1413",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594206720,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:439",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594213510,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:387",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594224304,
      "name": "name_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:347",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596836288,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:694",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580637456,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071589854352,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071590200976,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071591099824,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071593378256,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071593393744,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071593433392,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071593456464,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071593502384,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071594177472,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071594192912,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071594206720,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071594212704,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071594224304,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071596836288,
      "name": "name_show",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491169400,
      "name": "name_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:230",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498288080,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:592",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499091192,
      "name": "name_show",
      "external": false,
      "loc": "drivers/base/power/wakeup_stats.c:89",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500821816,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:24",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500867864,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-dev.c:95",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500931432,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:64",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500973080,
      "name": "name_show",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:67",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501701376,
      "name": "name_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:117",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501710272,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1113",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501718440,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:437",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501728360,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:367",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501750944,
      "name": "name_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:347",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503703192,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:669",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491169400,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446603336498288080,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446603336499091192,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446603336500821816,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446603336500867864,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446603336500931432,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446603336500973080,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446603336501701376,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446603336501710272,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446603336501718440,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446603336501722480,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446603336501750944,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446603336503703192,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225194512,
      "name": "name_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:230",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230968904,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:592",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231642044,
      "name": "name_show",
      "external": false,
      "loc": "drivers/base/power/wakeup_stats.c:89",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233326328,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:24",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233378972,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-dev.c:95",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233441436,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:64",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233486436,
      "name": "name_show",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:67",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234225848,
      "name": "name_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:117",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234233900,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1113",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234241860,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:437",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234252764,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:367",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234303296,
      "name": "name_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:347",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236338384,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:669",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225194512,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 3230968904,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3231642044,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 3233326328,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 3233378972,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 3233441436,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 3233486436,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 3234225848,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 3234233900,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 3234241860,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 3234252764,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 3234303296,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 3236338384,
      "name": "name_show",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283211856,
      "name": "name_show",
      "external": false,
      "loc": "arch/powerpc/platforms/pseries/vio.c:1526",
      "file": "arch/powerpc/platforms/pseries/vio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284069280,
      "name": "name_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:230",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291452352,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:592",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292272608,
      "name": "name_show",
      "external": false,
      "loc": "drivers/base/power/wakeup_stats.c:89",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294279936,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:24",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294331184,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-dev.c:95",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294386656,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:64",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294439264,
      "name": "name_show",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:67",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295138832,
      "name": "name_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:117",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295150576,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1113",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295163040,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:437",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295167952,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:367",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295194720,
      "name": "name_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:347",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297535744,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:669",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283211856,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 13835058055284069280,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 13835058055291452352,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 13835058055292272608,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 13835058055294279936,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 13835058055294331184,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 13835058055294386656,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 13835058055294439264,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 13835058055295138832,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 13835058055295150576,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 13835058055295163040,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 13835058055295167952,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 13835058055295194720,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 13835058055297535744,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271722198,
      "name": "name_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:230",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275985188,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:592",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277637136,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:24",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277663958,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-dev.c:95",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277698142,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:64",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277730832,
      "name": "name_show",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:67",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278127666,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1113",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278134098,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:437",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278137184,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:367",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278153772,
      "name": "name_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:347",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279633896,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:669",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271722198,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446743936275985188,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446743936277663958,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446743936277730832,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446743936278127666,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446743936278134098,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446743936278137184,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446743936278153772,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446743936279633896,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446743936277637136,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446743936277698142,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579952416,
      "name": "name_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:230",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585391600,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:592",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586029728,
      "name": "name_show",
      "external": false,
      "loc": "drivers/base/power/wakeup_stats.c:89",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587349264,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:24",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587387696,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:64",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587405680,
      "name": "name_show",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:67",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587855520,
      "name": "name_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:117",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587862368,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1113",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587870624,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:437",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587874785,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:367",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589571408,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:669",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952416,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071585391600,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071586029728,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587349264,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071587387696,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587405680,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587855520,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587862368,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071587870624,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071587874336,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071589571408,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
ssize_t name_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579890400,
      "name": "name_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:230",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585261520,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:592",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585875744,
      "name": "name_show",
      "external": false,
      "loc": "drivers/base/power/wakeup_stats.c:89",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587117568,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:24",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587155904,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:64",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587173888,
      "name": "name_show",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:67",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587589168,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1113",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587597424,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:437",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589295984,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:669",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890400,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071585261520,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071585875744,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587117568,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071587155904,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587173888,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587589168,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071587597424,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071589295984,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579943952,
      "name": "name_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:230",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585580848,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:592",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586216496,
      "name": "name_show",
      "external": false,
      "loc": "drivers/base/power/wakeup_stats.c:89",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587616752,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:24",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587656512,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-dev.c:95",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587702896,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:64",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587730848,
      "name": "name_show",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:67",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588187728,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1113",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588195984,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:437",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588200145,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:367",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588216400,
      "name": "name_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:347",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590013440,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:669",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579943952,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071585580848,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071586216496,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587616752,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071587656512,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071587702896,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587730848,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071588187728,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071588195984,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071588199696,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588216400,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071590013440,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t name_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "name_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579989312,
      "name": "name_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:230",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585688928,
      "name": "name_show",
      "external": false,
      "loc": "drivers/regulator/core.c:592",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586325600,
      "name": "name_show",
      "external": false,
      "loc": "drivers/base/power/wakeup_stats.c:89",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587727968,
      "name": "name_show",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:24",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587767632,
      "name": "name_show",
      "external": false,
      "loc": "drivers/i2c/i2c-dev.c:95",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587815968,
      "name": "name_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:64",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587843904,
      "name": "name_show",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:67",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588316160,
      "name": "name_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:117",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588323024,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1113",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588331280,
      "name": "name_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq-event.c:437",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588335441,
      "name": "name_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:367",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588351696,
      "name": "name_show",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:347",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590063520,
      "name": "name_show",
      "external": false,
      "loc": "net/rfkill/core.c:669",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579989312,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071585688928,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071586325600,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587727968,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071587767632,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071587815968,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587843904,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071588316160,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071588323024,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071588331280,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071588334992,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588351696,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071590063520,
      "name": "name_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kobject * kobj</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct device_attribute * attr</code> ➡️ <code>struct kobj_attribute * attr</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kobject * kobj</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct kobj_attribute * attr</code> ➡️ <code>struct device_attribute * attr</code>
</li>
</ul>
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
