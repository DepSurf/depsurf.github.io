# Function: <code>resource_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583282816,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:131",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584723376,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1145",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583282816,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071584723376,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583593728,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:131",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585075952,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1155",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585103328,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:209",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583593728,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071585075952,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071585103328,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583730912,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:132",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585261424,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1263",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585292368,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:209",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583730912,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071585261424,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071585292368,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583773344,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:131",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585334912,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:522",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585344640,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1282",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585378832,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:209",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583773344,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071585334912,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071585344640,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071585378832,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584033200,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:132",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585762992,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:522",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585773040,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1282",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585808016,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:213",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584033200,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071585762992,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071585773040,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071585808016,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584230592,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:129",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586009408,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:554",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586019808,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1281",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586054176,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:213",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584230592,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071586009408,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071586019808,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071586054176,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584320256,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:128",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586148000,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:581",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586158816,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1304",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586194400,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:213",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584320256,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071586148000,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071586158816,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071586194400,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584515312,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:128",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:579",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586395056,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1311",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586431680,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:205",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586446288,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/dax/bus.c:305",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584515312,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071586383552,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071586392361,
      "name": "resource_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071586395056,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071586431680,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071586446288,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584651216,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:128",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586531232,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:579",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586541696,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1311",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586578288,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:208",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586594224,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/dax/bus.c:305",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584651216,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071586531232,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071586541696,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071586578288,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071586594224,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585334976,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:128",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587314912,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:601",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587326784,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1291",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587363440,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:197",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587380224,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/dax/bus.c:305",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585334976,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071587314912,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071587326784,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071587363440,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071587380224,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585488192,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:137",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587376720,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:601",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587388560,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1291",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587424672,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:197",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587441120,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/dax/bus.c:1179",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585488192,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071587376720,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071587388560,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071587424672,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071587441120,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585369472,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:137",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587258416,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:608",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587270672,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1291",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587306608,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:197",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587322896,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/dax/bus.c:1180",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585369472,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071587258416,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071587270672,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071587306608,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071587322896,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585829040,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:137",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587823808,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:608",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587837600,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1291",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587873440,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:197",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587889744,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/dax/bus.c:1178",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585829040,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    },
    {
      "addr": 18446744071587823808,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071587837600,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071587873440,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071587889744,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587020176,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:158",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589174480,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:563",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589188528,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1068",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589223216,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:196",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589238816,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/dax/bus.c:1208",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587020176,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071589174480,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071589188528,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071589223216,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446744071589238816,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588191280,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:159",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590727328,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:608",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590742944,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1060",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590779488,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:198",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590797712,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/dax/bus.c:1208",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588191280,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071590727328,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071590742944,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071590779488,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446744071590797712,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588467264,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:159",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591068656,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:608",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591084304,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1060",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591120992,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:198",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591139232,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/dax/bus.c:1238",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588467264,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071591068656,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071591084304,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071591120992,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446744071591139232,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588764512,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:159",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591413136,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:609",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591429200,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1069",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591466464,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:198",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591484928,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/dax/bus.c:1239",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588764512,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071591413136,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071591429200,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071591466464,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446744071591484928,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496898120,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:128",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497728456,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/amba/bus.c:143",
      "file": "drivers/amba/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499418088,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:579",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499430984,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1311",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499478160,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/dax/bus.c:305",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496898120,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446603336497728456,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446603336499418088,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446603336499430984,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446603336499478160,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230175488,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:128",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230552100,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/amba/bus.c:143",
      "file": "drivers/amba/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231951504,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/dax/bus.c:305",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230175488,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 3230552100,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3231951504,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290988336,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:128",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292662080,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:579",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292677344,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1311",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292735648,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:208",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292757616,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/dax/bus.c:305",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290988336,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 13835058055292662080,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 13835058055292677344,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 13835058055292735648,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 13835058055292757616,
      "name": "resource_show",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275590654,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:128",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276646412,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:579",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276657086,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1311",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276696896,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/dax/bus.c:305",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275590654,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446743936276696896,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446743936276646412,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446743936276657086,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584601696,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:128",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586221712,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:579",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586232176,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1311",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586268768,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:208",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586284704,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/dax/bus.c:305",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584601696,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071586221712,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071586232176,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071586268768,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071586284704,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584531504,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:128",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586040080,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:579",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586050544,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1311",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586087136,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:208",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586122192,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/dax/bus.c:305",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584531504,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071586040080,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071586050544,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071586087136,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071586122192,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584601376,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:128",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586479200,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:579",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586489664,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1311",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586526256,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:208",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586542192,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/dax/bus.c:305",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584601376,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071586479200,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071586489664,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071586526256,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071586542192,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
ssize_t resource_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "resource_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584709072,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:128",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586590944,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:579",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586601408,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1311",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586637984,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:208",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586653968,
      "name": "resource_show",
      "external": false,
      "loc": "drivers/dax/bus.c:305",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584709072,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071586590944,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071586601408,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071586637984,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071586653968,
      "name": "resource_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
