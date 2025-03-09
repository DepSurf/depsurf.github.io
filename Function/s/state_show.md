# Function: <code>state_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t state_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579686320,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:307",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584713024,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:290",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585711904,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2520",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586112144,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:172",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_update_state"
      ]
    },
    {
      "addr": 18446744071587302784,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:699",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686320,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071584713024,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071585711904,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
    },
    {
      "addr": 18446744071586112144,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071587302784,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
ssize_t state_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579705424,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:308",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585063696,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:296",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586103216,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:441",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586110944,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2524",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586526144,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:160",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_update_state"
      ]
    },
    {
      "addr": 18446744071587773536,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:695",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579705424,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071585063696,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071586103216,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071586110944,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
    },
    {
      "addr": 18446744071586526144,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071587773536,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
ssize_t state_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579732992,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:380",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585248080,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:311",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586303904,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:480",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586313792,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2562",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586706288,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:365",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_sync"
      ]
    },
    {
      "addr": 18446744071587988736,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:695",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579732992,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071585248080,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071586303904,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071586313792,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
    },
    {
      "addr": 18446744071586706288,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071587988736,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
ssize_t state_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579728896,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:380",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585330160,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:327",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586402832,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:488",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586419392,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2624",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586831920,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:368",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_sync"
      ]
    },
    {
      "addr": 18446744071588146768,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:753",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579728896,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071585330160,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071586402832,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071586419392,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
    },
    {
      "addr": 18446744071586831920,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071588146768,
      "name": "state_show",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t state_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579761744,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:435",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585758160,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:345",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586868960,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:489",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586877744,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2679",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587319696,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:356",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_sync"
      ]
    },
    {
      "addr": 18446744071588695008,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:753",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579761744,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071585758160,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071586868960,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071586877744,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 713
    },
    {
      "addr": 18446744071587319696,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071588695008,
      "name": "state_show",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t state_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579796208,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:465",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586004272,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:346",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587162448,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:509",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587170928,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2694",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587622576,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:356",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_sync"
      ]
    },
    {
      "addr": 18446744071589061760,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:767",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579796208,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071586004272,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071587162448,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071587170928,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 727
    },
    {
      "addr": 18446744071587622576,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071589061760,
      "name": "state_show",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t state_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579842816,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:454",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585234000,
      "name": "state_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:405",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585912976,
      "name": "state_show",
      "external": false,
      "loc": "drivers/base/memory.c:149",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586141296,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:334",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587342368,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:509",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587350880,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2685",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587752016,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:356",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_sync"
      ]
    },
    {
      "addr": 18446744071589287456,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:769",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579842816,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071585234000,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585912976,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071586141296,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071587342368,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071587350880,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 737
    },
    {
      "addr": 18446744071587752016,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071589287456,
      "name": "state_show",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
ssize_t state_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579876768,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:466",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585446144,
      "name": "state_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:405",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "state_show",
      "external": false,
      "loc": "drivers/base/memory.c:160",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:331",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587613200,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:526",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587621808,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2748",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588056784,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:348",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_sync"
      ]
    },
    {
      "addr": 18446744071589743872,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:757",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876768,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071585446144,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071586153424,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071586157231,
      "name": "state_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071586376960,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071586382056,
      "name": "state_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071587613200,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071587621808,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
    },
    {
      "addr": 18446744071588056784,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071589743872,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
ssize_t state_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579927056,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:552",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585586576,
      "name": "state_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:405",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586302992,
      "name": "state_show",
      "external": false,
      "loc": "drivers/base/memory.c:129",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586525232,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:331",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587816896,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:525",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587825440,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2802",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588243872,
      "name": "state_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:78",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588262688,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:348",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_sync"
      ]
    },
    {
      "addr": 18446744071589967584,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:757",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579927056,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071585586576,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071586302992,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071586525232,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071587816896,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071587825440,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
    },
    {
      "addr": 18446744071588243872,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071588262688,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071589967584,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
ssize_t state_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579970832,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:591",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586307904,
      "name": "state_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:406",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587072208,
      "name": "state_show",
      "external": false,
      "loc": "drivers/base/memory.c:138",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587305760,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:322",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588663744,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:545",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588672960,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2928",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589120720,
      "name": "state_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:79",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589141552,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:348",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590997632,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:757",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970832,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071586307904,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071587072208,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071587305760,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071588663744,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071588672960,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 709
    },
    {
      "addr": 18446744071589120720,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071589141552,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071590997632,
      "name": "state_show",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t state_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579958752,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:591",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586426544,
      "name": "state_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:407",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587156640,
      "name": "state_show",
      "external": false,
      "loc": "drivers/base/memory.c:139",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587367376,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:322",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588690800,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:546",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588699792,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2949",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589118608,
      "name": "state_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:180",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589140528,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:348",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591062304,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:779",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579958752,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071586426544,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071587156640,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071587367376,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071588690800,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071588699792,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 709
    },
    {
      "addr": 18446744071589118608,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071589140528,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071591062304,
      "name": "state_show",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t state_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579961376,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:591",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586310544,
      "name": "state_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:473",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587043952,
      "name": "state_show",
      "external": false,
      "loc": "drivers/base/memory.c:139",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587249360,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:322",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588577168,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:546",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588585552,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2913",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589008384,
      "name": "state_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:178",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589030672,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:348",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590993072,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:780",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579961376,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071586310544,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071587043952,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071587249360,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071588577168,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071588585552,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
    },
    {
      "addr": 18446744071589008384,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071589030672,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071590993072,
      "name": "state_show",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
ssize_t state_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579595248,
      "name": "state_show",
      "external": false,
      "loc": "kernel/cpu.c:2266",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580090896,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:594",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586830144,
      "name": "state_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:470",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586881136,
      "name": "state_show",
      "external": false,
      "loc": "drivers/regulator/core.c:657",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587612688,
      "name": "state_show",
      "external": false,
      "loc": "drivers/base/memory.c:145",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587815712,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:322",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589252928,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:552",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589261520,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2923",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589722848,
      "name": "state_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:178",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:348",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591830832,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:780",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579595248,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071580090896,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071586830144,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071586881136,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
    },
    {
      "addr": 18446744071587612688,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071587815712,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071589252928,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071589261520,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
    },
    {
      "addr": 18446744071589722848,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071589746432,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446744071592686745,
      "name": "state_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071591830832,
      "name": "state_show",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
ssize_t state_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579687296,
      "name": "state_show",
      "external": false,
      "loc": "kernel/cpu.c:2288",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580228096,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:568",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588114048,
      "name": "state_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:471",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588169184,
      "name": "state_show",
      "external": false,
      "loc": "drivers/regulator/core.c:658",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588952528,
      "name": "state_show",
      "external": false,
      "loc": "drivers/base/memory.c:145",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589164800,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:301",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590721552,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:550",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590732224,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2913",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591231120,
      "name": "state_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:178",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:348",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_sync"
      ]
    },
    {
      "addr": 18446744071593545088,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:780",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579687296,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071580228096,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071588114048,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071588169184,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    },
    {
      "addr": 18446744071588952528,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071589164800,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071590721552,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071590732224,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 654
    },
    {
      "addr": 18446744071591231120,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071591258848,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071594572150,
      "name": "state_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071593545088,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
ssize_t state_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579810448,
      "name": "state_show",
      "external": false,
      "loc": "kernel/cpu.c:2312",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580419840,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:572",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589500080,
      "name": "state_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:471",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589565216,
      "name": "state_show",
      "external": false,
      "loc": "drivers/regulator/core.c:658",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590467824,
      "name": "state_show",
      "external": false,
      "loc": "drivers/base/memory.c:145",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590716672,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:301",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592396464,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:558",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592408576,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2871",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592980480,
      "name": "state_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:178",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:358",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_sync"
      ]
    },
    {
      "addr": 18446744071595466608,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:780",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579810448,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071580419840,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071589500080,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071589565216,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    },
    {
      "addr": 18446744071590467824,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071590716672,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071592396464,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071592408576,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
    },
    {
      "addr": 18446744071592980480,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071593014144,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071596319967,
      "name": "state_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071595466608,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
ssize_t state_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579858800,
      "name": "state_show",
      "external": false,
      "loc": "kernel/cpu.c:2697",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580488912,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:640",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589800880,
      "name": "state_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:471",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589867264,
      "name": "state_show",
      "external": false,
      "loc": "drivers/regulator/core.c:724",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590790752,
      "name": "state_show",
      "external": false,
      "loc": "drivers/base/memory.c:140",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591057952,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:301",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592076752,
      "name": "state_show",
      "external": false,
      "loc": "drivers/usb/core/port.c:163",
      "file": "drivers/usb/core/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592825808,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:578",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592838080,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2845",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593431488,
      "name": "state_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:178",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:368",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_sync"
      ]
    },
    {
      "addr": 18446744071595973680,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:780",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858800,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071580488912,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071589800880,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071589867264,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    },
    {
      "addr": 18446744071590790752,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071591057952,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071592076752,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071592825808,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071592838080,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 674
    },
    {
      "addr": 18446744071593431488,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071593465792,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446744071596849610,
      "name": "state_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071595973680,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
ssize_t state_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579896608,
      "name": "state_show",
      "external": false,
      "loc": "kernel/cpu.c:2751",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580548752,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:624",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590137104,
      "name": "state_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:471",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590205104,
      "name": "state_show",
      "external": false,
      "loc": "drivers/regulator/core.c:726",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591133664,
      "name": "state_show",
      "external": false,
      "loc": "drivers/base/memory.c:141",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591402656,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:303",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592817104,
      "name": "state_show",
      "external": false,
      "loc": "drivers/usb/core/port.c:163",
      "file": "drivers/usb/core/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593575072,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:578",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593587264,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2967",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594177536,
      "name": "state_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:178",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:368",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_sync"
      ]
    },
    {
      "addr": 18446744071596840848,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:797",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579896608,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071580548752,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071590137104,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071590205104,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    },
    {
      "addr": 18446744071591133664,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071591402656,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071592817104,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071593575072,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071593587264,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
    },
    {
      "addr": 18446744071594177536,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071594212880,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446744071597774431,
      "name": "state_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071596840848,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
ssize_t state_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491134248,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:552",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498252032,
      "name": "state_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:405",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499136656,
      "name": "state_show",
      "external": false,
      "loc": "drivers/base/memory.c:129",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499411088,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:331",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501031520,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:525",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501046136,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2802",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501701440,
      "name": "state_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:78",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501722552,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:348",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_sync"
      ]
    },
    {
      "addr": 18446603336503702896,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:757",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491134248,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446603336498252032,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446603336499136656,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 18446603336499411088,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446603336501031520,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446603336501046136,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
    },
    {
      "addr": 18446603336501701440,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446603336501722552,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446603336503702896,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
ssize_t state_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225133056,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:552",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233230312,
      "name": "state_show",
      "external": false,
      "loc": "drivers/usb/gadget/udc/core.c:1499",
      "file": "drivers/usb/gadget/udc/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233550232,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:525",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233562800,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2802",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234225896,
      "name": "state_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:78",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234252812,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:348",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236338164,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:757",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225133056,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 3233230312,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 3233550232,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 3233562800,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
    },
    {
      "addr": 3234225896,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 3234252812,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 3236338164,
      "name": "state_show",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t state_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284025568,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:552",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292327952,
      "name": "state_show",
      "external": false,
      "loc": "drivers/base/memory.c:129",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292651024,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:331",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294513200,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:525",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294527936,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2802",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295138912,
      "name": "state_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:78",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295168032,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:348",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297535392,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:757",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284025568,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 13835058055292327952,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 13835058055292651024,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 13835058055294513200,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 13835058055294527936,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 868
    },
    {
      "addr": 13835058055295138912,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 13835058055295168032,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    },
    {
      "addr": 13835058055297535392,
      "name": "state_show",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t state_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271701752,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:552",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276640060,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:331",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277770792,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:525",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277780314,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2802",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278137246,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:348",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279633618,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:757",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271701752,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446743936277770792,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446743936277780314,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
    },
    {
      "addr": 18446743936278137246,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446743936279633618,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446743936276640060,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
ssize_t state_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579898784,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:552",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585348512,
      "name": "state_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:406",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586066240,
      "name": "state_show",
      "external": false,
      "loc": "drivers/base/memory.c:129",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586215712,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:331",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587447872,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:525",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587456416,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2802",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587855568,
      "name": "state_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:78",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587874384,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:348",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_sync"
      ]
    },
    {
      "addr": 18446744071589571184,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:757",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898784,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071585348512,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071586066240,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071586215712,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071587447872,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071587456416,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
    },
    {
      "addr": 18446744071587855568,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071587874384,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071589571184,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t state_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579834128,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:552",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585912192,
      "name": "state_show",
      "external": false,
      "loc": "drivers/base/memory.c:129",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586034080,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:331",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587216080,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:525",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587224592,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2802",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587550544,
      "name": "state_show",
      "external": false,
      "loc": "drivers/hv/vmbus_drv.c:146",
      "file": "drivers/hv/vmbus_drv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589295760,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:757",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579834128,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071585912192,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071586034080,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071587216080,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071587224592,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
    },
    {
      "addr": 18446744071587550544,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071589295760,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
ssize_t state_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579887328,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:552",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585536976,
      "name": "state_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:405",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586250960,
      "name": "state_show",
      "external": false,
      "loc": "drivers/base/memory.c:129",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586473200,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:331",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587773040,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:525",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587781584,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2802",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588199744,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:348",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_sync"
      ]
    },
    {
      "addr": 18446744071590013216,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:757",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887328,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071585536976,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071586250960,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071586473200,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071587773040,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071587781584,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
    },
    {
      "addr": 18446744071588199744,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071590013216,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
ssize_t state_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "state_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579933088,
      "name": "state_show",
      "external": false,
      "loc": "kernel/power/main.c:552",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585644960,
      "name": "state_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:405",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586361904,
      "name": "state_show",
      "external": false,
      "loc": "drivers/base/memory.c:129",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586584880,
      "name": "state_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:331",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587886384,
      "name": "state_show",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:525",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587895952,
      "name": "state_show",
      "external": false,
      "loc": "drivers/md/md.c:2802",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588316208,
      "name": "state_show",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_sysfs.c:78",
      "file": "drivers/remoteproc/remoteproc_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588335040,
      "name": "state_show",
      "external": false,
      "loc": "drivers/extcon/extcon.c:348",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_sync"
      ]
    },
    {
      "addr": 18446744071590063296,
      "name": "state_show",
      "external": false,
      "loc": "net/rfkill/core.c:757",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933088,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071585644960,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071586361904,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071586584880,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071587886384,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071587895952,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
    },
    {
      "addr": 18446744071588316208,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071588335040,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071590063296,
      "name": "state_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
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
