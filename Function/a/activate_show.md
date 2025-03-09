# Function: <code>activate_show</code>

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
ssize_t activate_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "activate_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587355312,
      "name": "activate_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:418",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587369264,
      "name": "activate_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:490",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587355312,
      "name": "activate_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
    },
    {
      "addr": 18446744071587369264,
      "name": "activate_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
ssize_t activate_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "activate_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587237152,
      "name": "activate_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:418",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587251248,
      "name": "activate_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:490",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587237152,
      "name": "activate_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
    },
    {
      "addr": 18446744071587251248,
      "name": "activate_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
ssize_t activate_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "activate_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587803440,
      "name": "activate_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:418",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587815296,
      "name": "activate_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:490",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587803440,
      "name": "activate_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
    },
    {
      "addr": 18446744071587815296,
      "name": "activate_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
ssize_t activate_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "activate_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589150640,
      "name": "activate_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:385",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589164368,
      "name": "activate_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:469",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589150640,
      "name": "activate_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446744071589164368,
      "name": "activate_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
ssize_t activate_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "activate_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590700944,
      "name": "activate_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:385",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590716192,
      "name": "activate_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:476",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590700944,
      "name": "activate_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446744071590716192,
      "name": "activate_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
ssize_t activate_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "activate_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591042032,
      "name": "activate_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:385",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591057232,
      "name": "activate_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:476",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591042032,
      "name": "activate_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    },
    {
      "addr": 18446744071591057232,
      "name": "activate_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
ssize_t activate_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "activate_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591386496,
      "name": "activate_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:385",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591401936,
      "name": "activate_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:478",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591386496,
      "name": "activate_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    },
    {
      "addr": 18446744071591401936,
      "name": "activate_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
ssize_t activate_show(struct device * dev, struct device_attribute * attr, char * buf)
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
