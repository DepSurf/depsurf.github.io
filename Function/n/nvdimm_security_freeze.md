# Function: <code>nvdimm_security_freeze</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int nvdimm_security_freeze(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_security_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586144240,
      "name": "nvdimm_security_freeze",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:609",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:security_store",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586144240,
      "name": "nvdimm_security_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int nvdimm_security_freeze(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_security_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvdimm_security_freeze",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:608",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:__security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586382320,
      "name": "nvdimm_security_freeze.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586379696,
      "name": "nvdimm_security_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int nvdimm_security_freeze(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_security_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvdimm_security_freeze",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:536",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586529929,
      "name": "nvdimm_security_freeze.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586528368,
      "name": "nvdimm_security_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int nvdimm_security_freeze(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_security_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvdimm_security_freeze",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:543",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587311241,
      "name": "nvdimm_security_freeze.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587309344,
      "name": "nvdimm_security_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int nvdimm_security_freeze(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_security_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvdimm_security_freeze",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:673",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591516947,
      "name": "nvdimm_security_freeze.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587371376,
      "name": "nvdimm_security_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int nvdimm_security_freeze(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_security_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvdimm_security_freeze",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:673",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591458923,
      "name": "nvdimm_security_freeze.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587253392,
      "name": "nvdimm_security_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
int nvdimm_security_freeze(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_security_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvdimm_security_freeze",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:691",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592521504,
      "name": "nvdimm_security_freeze.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071587820528,
      "name": "nvdimm_security_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int nvdimm_security_freeze(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_security_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvdimm_security_freeze",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:672",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594390454,
      "name": "nvdimm_security_freeze.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071589169552,
      "name": "nvdimm_security_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int nvdimm_security_freeze(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_security_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvdimm_security_freeze",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:682",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596254879,
      "name": "nvdimm_security_freeze.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071590721792,
      "name": "nvdimm_security_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int nvdimm_security_freeze(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_security_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvdimm_security_freeze",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:682",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596783479,
      "name": "nvdimm_security_freeze.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591063040,
      "name": "nvdimm_security_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int nvdimm_security_freeze(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_security_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvdimm_security_freeze",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:684",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597692414,
      "name": "nvdimm_security_freeze.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591407792,
      "name": "nvdimm_security_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
int nvdimm_security_freeze(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_security_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499414688,
      "name": "nvdimm_security_freeze",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:536",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499414688,
      "name": "nvdimm_security_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int nvdimm_security_freeze(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_security_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292656768,
      "name": "nvdimm_security_freeze",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:536",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292656768,
      "name": "nvdimm_security_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int nvdimm_security_freeze(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_security_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276643400,
      "name": "nvdimm_security_freeze",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:536",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276643400,
      "name": "nvdimm_security_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int nvdimm_security_freeze(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_security_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvdimm_security_freeze",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:536",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586220409,
      "name": "nvdimm_security_freeze.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586218848,
      "name": "nvdimm_security_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int nvdimm_security_freeze(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_security_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvdimm_security_freeze",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:536",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586038777,
      "name": "nvdimm_security_freeze.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586037216,
      "name": "nvdimm_security_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int nvdimm_security_freeze(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_security_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvdimm_security_freeze",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:536",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586477897,
      "name": "nvdimm_security_freeze.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586476336,
      "name": "nvdimm_security_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int nvdimm_security_freeze(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_security_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvdimm_security_freeze",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:536",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586589577,
      "name": "nvdimm_security_freeze.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586588016,
      "name": "nvdimm_security_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int nvdimm_security_freeze(struct nvdimm * nvdimm)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int nvdimm_security_freeze(struct nvdimm * nvdimm)
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
