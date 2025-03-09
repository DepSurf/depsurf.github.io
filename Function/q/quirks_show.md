# Function: <code>quirks_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585233968,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:206",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585233968,
      "name": "quirks_show",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585627392,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:216",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585627392,
      "name": "quirks_show",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585815008,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:230",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585815008,
      "name": "quirks_show",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585901952,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:230",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585901952,
      "name": "quirks_show",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586342720,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:230",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586342720,
      "name": "quirks_show",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586600256,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:250",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586632976,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/port.c:53",
      "file": "drivers/usb/core/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586600256,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071586632976,
      "name": "quirks_show",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586749040,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:250",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586782048,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/port.c:62",
      "file": "drivers/usb/core/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586749040,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071586782048,
      "name": "quirks_show",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587004048,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:251",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587038000,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/port.c:62",
      "file": "drivers/usb/core/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587004048,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587038000,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587203536,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:251",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587238400,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/port.c:62",
      "file": "drivers/usb/core/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587203536,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587238400,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588055888,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:251",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588092240,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/port.c:62",
      "file": "drivers/usb/core/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588055888,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588092240,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588101280,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:251",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588134192,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/port.c:62",
      "file": "drivers/usb/core/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588101280,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588134192,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587983872,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:254",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588016368,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/port.c:62",
      "file": "drivers/usb/core/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587983872,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588016368,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588596880,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:254",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588632400,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/port.c:62",
      "file": "drivers/usb/core/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588596880,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588632400,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590009072,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:254",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590048672,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/port.c:63",
      "file": "drivers/usb/core/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590009072,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071590048672,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591609328,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:255",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591653568,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/port.c:172",
      "file": "drivers/usb/core/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591609328,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071591653568,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592031600,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:255",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592076208,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/port.c:182",
      "file": "drivers/usb/core/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592031600,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071592076208,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592771616,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:252",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592816560,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/port.c:182",
      "file": "drivers/usb/core/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592771616,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071592816560,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500287632,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:251",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500335816,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/port.c:62",
      "file": "drivers/usb/core/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500287632,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446603336500335816,
      "name": "quirks_show",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232757588,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:251",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232795852,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/port.c:62",
      "file": "drivers/usb/core/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3232757588,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 3232795852,
      "name": "quirks_show",
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
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293591088,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:251",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055293645968,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/port.c:62",
      "file": "drivers/usb/core/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293591088,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 13835058055293645968,
      "name": "quirks_show",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277197398,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:251",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277228970,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/port.c:62",
      "file": "drivers/usb/core/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277197398,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446743936277228970,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586909616,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:251",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586944480,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/port.c:62",
      "file": "drivers/usb/core/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586909616,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071586944480,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586850784,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:251",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586885648,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/port.c:62",
      "file": "drivers/usb/core/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586850784,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071586885648,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587158096,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:251",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587192960,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/port.c:62",
      "file": "drivers/usb/core/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587158096,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587192960,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
ssize_t quirks_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "quirks_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587265168,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:251",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587300032,
      "name": "quirks_show",
      "external": false,
      "loc": "drivers/usb/core/port.c:62",
      "file": "drivers/usb/core/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587265168,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587300032,
      "name": "quirks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
