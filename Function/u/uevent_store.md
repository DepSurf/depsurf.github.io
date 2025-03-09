# Function: <code>uevent_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584381456,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:414",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584391168,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:649",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584381456,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071584391168,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584716656,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:414",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584726080,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:648",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584716656,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071584726080,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584903344,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:980",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584915872,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:648",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584903344,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071584915872,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584988672,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:981",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585001056,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:613",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584988672,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071585001056,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585410608,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:984",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585422992,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:613",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585410608,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071585422992,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585652672,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:1026",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585665744,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:611",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585652672,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071585665744,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585782208,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:1094",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585795424,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:614",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585782208,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071585795424,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:1239",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586028640,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:603",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586014816,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071586025352,
      "name": "uevent_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586028640,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:1276",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586176016,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:579",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586162112,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071586172942,
      "name": "uevent_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586176016,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:1754",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586935408,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:580",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586918672,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071586933089,
      "name": "uevent_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586935408,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:2155",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587020704,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:580",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587005408,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071591485615,
      "name": "uevent_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071587020704,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:2367",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586904336,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:580",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586888048,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071591429197,
      "name": "uevent_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586904336,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:2404",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587466096,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:576",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587449600,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071592487358,
      "name": "uevent_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071587466096,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:2415",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588786224,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:576",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588767344,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071594356865,
      "name": "uevent_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071588786224,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590260592,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:2652",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590281200,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:576",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590260592,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071590281200,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590579856,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:2658",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590599872,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:628",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590579856,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071590599872,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590937744,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:2673",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590958816,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:628",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590937744,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071590958816,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498957864,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:1276",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498972808,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:579",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498957864,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446603336498972808,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231529004,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:1276",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231542424,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:579",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231529004,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 3231542424,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292101712,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:1276",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292121184,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:579",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292101712,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 13835058055292121184,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276339648,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:1276",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276351768,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:579",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276339648,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446743936276351768,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:1276",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585936384,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:579",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585922480,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071585933310,
      "name": "uevent_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071585936384,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:1276",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585785520,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:579",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585771616,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071585782446,
      "name": "uevent_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071585785520,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:1276",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586126032,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:579",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586112128,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071586122958,
      "name": "uevent_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586126032,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t uevent_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "uevent_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/core.c:1276",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586234640,
      "name": "uevent_store",
      "external": false,
      "loc": "drivers/base/bus.c:579",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586222912,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071586231566,
      "name": "uevent_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586234640,
      "name": "uevent_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
