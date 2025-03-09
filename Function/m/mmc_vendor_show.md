# Function: <code>mmc_vendor_show</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t mmc_vendor_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_vendor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589002128,
      "name": "mmc_vendor_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:710",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589011856,
      "name": "mmc_vendor_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:30",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589002128,
      "name": "mmc_vendor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071589011856,
      "name": "mmc_vendor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
ssize_t mmc_vendor_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_vendor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589011712,
      "name": "mmc_vendor_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:710",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589021392,
      "name": "mmc_vendor_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:30",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589011712,
      "name": "mmc_vendor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071589021392,
      "name": "mmc_vendor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
ssize_t mmc_vendor_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_vendor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588899120,
      "name": "mmc_vendor_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:716",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588908384,
      "name": "mmc_vendor_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:30",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588899120,
      "name": "mmc_vendor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588908384,
      "name": "mmc_vendor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
ssize_t mmc_vendor_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_vendor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589603328,
      "name": "mmc_vendor_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:726",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589614720,
      "name": "mmc_vendor_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:30",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589603328,
      "name": "mmc_vendor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071589614720,
      "name": "mmc_vendor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
ssize_t mmc_vendor_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_vendor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591100576,
      "name": "mmc_vendor_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:733",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591113248,
      "name": "mmc_vendor_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:31",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591100576,
      "name": "mmc_vendor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071591113248,
      "name": "mmc_vendor_show",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t mmc_vendor_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_vendor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592820080,
      "name": "mmc_vendor_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:733",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592834880,
      "name": "mmc_vendor_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:31",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592820080,
      "name": "mmc_vendor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071592834880,
      "name": "mmc_vendor_show",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t mmc_vendor_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_vendor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593256752,
      "name": "mmc_vendor_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:733",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593271488,
      "name": "mmc_vendor_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:31",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593256752,
      "name": "mmc_vendor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071593271488,
      "name": "mmc_vendor_show",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t mmc_vendor_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_vendor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594012160,
      "name": "mmc_vendor_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:733",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594027392,
      "name": "mmc_vendor_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:31",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594012160,
      "name": "mmc_vendor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071594027392,
      "name": "mmc_vendor_show",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
ssize_t mmc_vendor_show(struct device * dev, struct device_attribute * attr, char * buf)
```
</details>
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
