# Function: <code>nvdimm_security_store</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device * dev, const char * buf, size_t len)
```

```json
{
  "name": "nvdimm_security_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586586608,
      "name": "nvdimm_security_store",
      "external": true,
      "loc": "drivers/nvdimm/security.c:495",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586586608,
      "name": "nvdimm_security_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2812
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device * dev, const char * buf, size_t len)
```

```json
{
  "name": "nvdimm_security_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587374512,
      "name": "nvdimm_security_store",
      "external": true,
      "loc": "drivers/nvdimm/security.c:500",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587374512,
      "name": "nvdimm_security_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device * dev, const char * buf, size_t len)
```

```json
{
  "name": "nvdimm_security_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587435200,
      "name": "nvdimm_security_store",
      "external": true,
      "loc": "drivers/nvdimm/security.c:500",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587435200,
      "name": "nvdimm_security_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device * dev, const char * buf, size_t len)
```

```json
{
  "name": "nvdimm_security_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587316592,
      "name": "nvdimm_security_store",
      "external": true,
      "loc": "drivers/nvdimm/security.c:500",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587316592,
      "name": "nvdimm_security_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t nvdimm_security_store(struct device * dev, const char * buf, size_t len)
```

```json
{
  "name": "nvdimm_security_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvdimm_security_store",
      "external": true,
      "loc": "drivers/nvdimm/security.c:500",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592523848,
      "name": "nvdimm_security_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587883568,
      "name": "nvdimm_security_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1390
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t nvdimm_security_store(struct device * dev, const char * buf, size_t len)
```

```json
{
  "name": "nvdimm_security_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvdimm_security_store",
      "external": true,
      "loc": "drivers/nvdimm/security.c:495",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594395329,
      "name": "nvdimm_security_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589233888,
      "name": "nvdimm_security_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1462
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device * dev, const char * buf, size_t len)
```

```json
{
  "name": "nvdimm_security_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590791888,
      "name": "nvdimm_security_store",
      "external": true,
      "loc": "drivers/nvdimm/security.c:521",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590791888,
      "name": "nvdimm_security_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1099
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device * dev, const char * buf, size_t len)
```

```json
{
  "name": "nvdimm_security_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591133392,
      "name": "nvdimm_security_store",
      "external": true,
      "loc": "drivers/nvdimm/security.c:521",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591133392,
      "name": "nvdimm_security_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1099
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device * dev, const char * buf, size_t len)
```

```json
{
  "name": "nvdimm_security_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591479072,
      "name": "nvdimm_security_store",
      "external": true,
      "loc": "drivers/nvdimm/security.c:521",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591479072,
      "name": "nvdimm_security_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1099
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device * dev, const char * buf, size_t len)
```

```json
{
  "name": "nvdimm_security_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499470056,
      "name": "nvdimm_security_store",
      "external": true,
      "loc": "drivers/nvdimm/security.c:495",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499470056,
      "name": "nvdimm_security_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2448
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device * dev, const char * buf, size_t len)
```

```json
{
  "name": "nvdimm_security_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292747216,
      "name": "nvdimm_security_store",
      "external": true,
      "loc": "drivers/nvdimm/security.c:495",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292747216,
      "name": "nvdimm_security_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3016
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device * dev, const char * buf, size_t len)
```

```json
{
  "name": "nvdimm_security_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276690600,
      "name": "nvdimm_security_store",
      "external": true,
      "loc": "drivers/nvdimm/security.c:495",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276690600,
      "name": "nvdimm_security_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2122
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device * dev, const char * buf, size_t len)
```

```json
{
  "name": "nvdimm_security_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586277088,
      "name": "nvdimm_security_store",
      "external": true,
      "loc": "drivers/nvdimm/security.c:495",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586277088,
      "name": "nvdimm_security_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2812
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device * dev, const char * buf, size_t len)
```

```json
{
  "name": "nvdimm_security_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586095456,
      "name": "nvdimm_security_store",
      "external": true,
      "loc": "drivers/nvdimm/security.c:495",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586095456,
      "name": "nvdimm_security_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2812
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device * dev, const char * buf, size_t len)
```

```json
{
  "name": "nvdimm_security_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586534576,
      "name": "nvdimm_security_store",
      "external": true,
      "loc": "drivers/nvdimm/security.c:495",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586534576,
      "name": "nvdimm_security_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2812
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device * dev, const char * buf, size_t len)
```

```json
{
  "name": "nvdimm_security_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586646304,
      "name": "nvdimm_security_store",
      "external": true,
      "loc": "drivers/nvdimm/security.c:495",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586646304,
      "name": "nvdimm_security_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2812
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
ssize_t nvdimm_security_store(struct device * dev, const char * buf, size_t len)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
ssize_t nvdimm_security_store(struct device * dev, const char * buf, size_t len)
```
</details>
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
