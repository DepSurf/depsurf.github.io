# Function: <code>offset_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t offset_store(struct device * dev, struct device_attribute * devattr, const char * buf, size_t count)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585676432,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_core.c:988",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585713808,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:2837",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585676432,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071585713808,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586015744,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/rtc-sysfs.c:235",
      "file": "drivers/rtc/rtc-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586075376,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_core.c:992",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586112880,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:2845",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586015744,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071586075376,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071586112880,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586211552,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/rtc-sysfs.c:235",
      "file": "drivers/rtc/rtc-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586287152,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:391",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586315504,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:2890",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586211552,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071586287152,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071586315504,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586300608,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/rtc-sysfs.c:236",
      "file": "drivers/rtc/rtc-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586386128,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:391",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586413040,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:2952",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586300608,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071586386128,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071586413040,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586764096,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/rtc-sysfs.c:237",
      "file": "drivers/rtc/rtc-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586849120,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:391",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586880064,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:3007",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586764096,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071586849120,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071586880064,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587036016,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/rtc-sysfs.c:237",
      "file": "drivers/rtc/rtc-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587141568,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:389",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587174128,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:3023",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587036016,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071587141568,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071587174128,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587195696,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:233",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587321456,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:389",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587354096,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:3014",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587195696,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071587321456,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071587354096,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587461152,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:228",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587592336,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:389",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587624976,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:3081",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587461152,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071587592336,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071587624976,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587664272,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:228",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587795776,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:389",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587828720,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:3135",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587664272,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071587795776,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071587828720,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588531744,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:231",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588642112,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:389",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588675824,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:3260",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588531744,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071588642112,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071588675824,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588556336,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:231",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588664224,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:390",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588702688,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:3281",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588556336,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071588664224,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071588702688,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588439632,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:231",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588546032,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:347",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588588352,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:3245",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588439632,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071588546032,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071588588352,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589107088,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:231",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589220112,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:347",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589264368,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:3264",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589107088,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071589220112,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071589264368,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590553760,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:231",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590683168,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:347",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590736448,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:3255",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590553760,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071590683168,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071590736448,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592207600,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:232",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592352400,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:407",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592411344,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:3213",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592207600,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071592352400,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071592411344,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592631808,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:232",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592779056,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:367",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592840880,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:3190",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592631808,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071592779056,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071592840880,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593376624,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:232",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593528128,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:336",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593590048,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:3312",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593376624,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071593528128,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071593590048,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500820360,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:228",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500997048,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:389",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501049328,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:3135",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500820360,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446603336500997048,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446603336501049328,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233324948,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:228",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233509956,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:389",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233566604,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:3135",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233324948,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 3233509956,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 3233566604,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294278224,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:228",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294472496,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:389",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294533904,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:3135",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294278224,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 13835058055294472496,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 13835058055294533904,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277636208,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:228",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277748840,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:389",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277782532,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:3135",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277782532,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446743936277636208,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446743936277748840,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587348032,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:228",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587426752,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:389",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587459696,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:3135",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587348032,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071587426752,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071587459696,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587116336,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:228",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587194960,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:389",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587227872,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:3135",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587116336,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071587194960,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071587227872,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587615520,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:228",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587751920,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:389",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587784864,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:3135",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587615520,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071587751920,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071587784864,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
ssize_t offset_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t n)
```

```json
{
  "name": "offset_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587726736,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/rtc/sysfs.c:228",
      "file": "drivers/rtc/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587865200,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:389",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587899904,
      "name": "offset_store",
      "external": false,
      "loc": "drivers/md/md.c:3135",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587726736,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071587865200,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071587899904,
      "name": "offset_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device_attribute * attr</code>
</li>
<li>
<b>Param added. </b>
<code>size_t n</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device_attribute * devattr</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
</ul>
</details>
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
