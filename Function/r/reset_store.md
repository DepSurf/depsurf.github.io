# Function: <code>reset_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583285744,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1308",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583285744,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583596560,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1309",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583596560,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583733744,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1311",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583733744,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583773584,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1463",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583773584,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584033584,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1498",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584033584,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584230960,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1448",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587144496,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:820",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584230960,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071587144496,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584320624,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1447",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587324128,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:823",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584320624,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071587324128,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584515664,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1448",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587595024,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:823",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584515664,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071587595024,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584651408,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1304",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587798464,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:823",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584651408,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071587798464,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585335184,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1289",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588645184,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:823",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585335184,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071588645184,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585488432,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1300",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588667360,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:810",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585488432,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071588667360,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585366144,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1337",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588549696,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:730",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585366144,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071588549696,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585825664,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1337",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589223968,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:730",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585825664,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071589223968,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587016528,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1332",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590686368,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:730",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587016528,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071590686368,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588189056,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1345",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592356256,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:788",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588189056,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071592356256,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588465040,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1345",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592782624,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:762",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588465040,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071592782624,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588762144,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1369",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593531456,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:731",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588762144,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071593531456,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496898528,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1304",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501000024,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:823",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496898528,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446603336501000024,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230175884,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1304",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233512768,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:823",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230175884,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 3233512768,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290988624,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1304",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294477072,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:823",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290988624,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 13835058055294477072,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275588658,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1304",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277750748,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:823",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275588658,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446743936277750748,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584601888,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1304",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587429440,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:823",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584601888,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071587429440,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584531696,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1304",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587197648,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:823",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584531696,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071587197648,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584601568,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1304",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587754608,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:823",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584601568,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071587754608,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
ssize_t reset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "reset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584709264,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1304",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587868064,
      "name": "reset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:823",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584709264,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071587868064,
      "name": "reset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
