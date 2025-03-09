# Function: <code>info4_show</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t info4_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "info4_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589011296,
      "name": "info4_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:730",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589020976,
      "name": "info4_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:52",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589028656,
      "name": "info4_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:64",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589011296,
      "name": "info4_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071589020976,
      "name": "info4_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071589028656,
      "name": "info4_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
ssize_t info4_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "info4_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588898704,
      "name": "info4_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:736",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588907968,
      "name": "info4_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:52",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588915936,
      "name": "info4_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:64",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588898704,
      "name": "info4_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071588907968,
      "name": "info4_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071588915936,
      "name": "info4_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
ssize_t info4_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "info4_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589602912,
      "name": "info4_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:746",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589614304,
      "name": "info4_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:52",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589622816,
      "name": "info4_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:64",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589602912,
      "name": "info4_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071589614304,
      "name": "info4_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071589622816,
      "name": "info4_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
ssize_t info4_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "info4_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591100016,
      "name": "info4_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:753",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591112688,
      "name": "info4_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:53",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591121616,
      "name": "info4_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:65",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591100016,
      "name": "info4_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071591112688,
      "name": "info4_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071591121616,
      "name": "info4_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
ssize_t info4_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "info4_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592819424,
      "name": "info4_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:753",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592834224,
      "name": "info4_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:53",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592843792,
      "name": "info4_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:65",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592819424,
      "name": "info4_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071592834224,
      "name": "info4_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071592843792,
      "name": "info4_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
ssize_t info4_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "info4_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593256096,
      "name": "info4_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:753",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593270832,
      "name": "info4_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:53",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593280432,
      "name": "info4_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:65",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593256096,
      "name": "info4_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071593270832,
      "name": "info4_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071593280432,
      "name": "info4_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
ssize_t info4_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "info4_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594011504,
      "name": "info4_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:753",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594026736,
      "name": "info4_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:53",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594036368,
      "name": "info4_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:65",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594011504,
      "name": "info4_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071594026736,
      "name": "info4_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071594036368,
      "name": "info4_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
ssize_t info4_show(struct device * dev, struct device_attribute * attr, char * buf)
```
</details>
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
