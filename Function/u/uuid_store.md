# Function: <code>uuid_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584731600,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1104",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584747808,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:96",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584750672,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:116",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584731600,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
    },
    {
      "addr": 18446744071584747808,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071584750672,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585083728,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1114",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585101120,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:96",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585103584,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:162",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585083728,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
    },
    {
      "addr": 18446744071585101120,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071585103584,
      "name": "uuid_store",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585270304,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1222",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585290160,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:96",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585292624,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:162",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585270304,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
    },
    {
      "addr": 18446744071585290160,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071585292624,
      "name": "uuid_store",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585354848,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1241",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585376272,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:96",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585379088,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:162",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585354848,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
    },
    {
      "addr": 18446744071585376272,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071585379088,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585783264,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1241",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585805328,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:96",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585808512,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:166",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585783264,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
    },
    {
      "addr": 18446744071585805328,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071585808512,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586027712,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1240",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586051488,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:96",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586054736,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:166",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586027712,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    },
    {
      "addr": 18446744071586051488,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071586054736,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586166880,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1263",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586191696,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:96",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586194960,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:166",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586166880,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    },
    {
      "addr": 18446744071586191696,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071586194960,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586404560,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1270",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:88",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586432176,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:158",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586404560,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    },
    {
      "addr": 18446744071586428928,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071586431187,
      "name": "uuid_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071586432176,
      "name": "uuid_store",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586551376,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1270",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586575568,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:88",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586578848,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:161",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586551376,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    },
    {
      "addr": 18446744071586575568,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071586578848,
      "name": "uuid_store",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587337184,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1250",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587361808,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:77",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587364000,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:150",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587337184,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
    },
    {
      "addr": 18446744071587361808,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071587364000,
      "name": "uuid_store",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587398912,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1250",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587423056,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:77",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587425232,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:150",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587398912,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
    },
    {
      "addr": 18446744071587423056,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071587425232,
      "name": "uuid_store",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587280672,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1250",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587304992,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:77",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587307168,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:150",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587280672,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
    },
    {
      "addr": 18446744071587304992,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071587307168,
      "name": "uuid_store",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587847488,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1250",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587870992,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:77",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587873984,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:150",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587847488,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    },
    {
      "addr": 18446744071587870992,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071587873984,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589202096,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1031",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589220544,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:76",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589223808,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:149",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589202096,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071589220544,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071589223808,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590757120,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1023",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590776560,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:76",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590780128,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:151",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590757120,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071590776560,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071590780128,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591098592,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1023",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591117936,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:76",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591121632,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:151",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591098592,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071591117936,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071591121632,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591443728,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1032",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591463360,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:76",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591467104,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:151",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591443728,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071591463360,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071591467104,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499441192,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1270",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499465344,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:88",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499441192,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    },
    {
      "addr": 18446603336499465344,
      "name": "uuid_store",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292695568,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1270",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292731440,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:88",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292736064,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:161",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292695568,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
    },
    {
      "addr": 13835058055292731440,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 13835058055292736064,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276665662,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1270",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276686382,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:88",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276665662,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    },
    {
      "addr": 18446743936276686382,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586241856,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1270",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586266048,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:88",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586269328,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:161",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586241856,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    },
    {
      "addr": 18446744071586266048,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071586269328,
      "name": "uuid_store",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586060224,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1270",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586084416,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:88",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586087696,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:161",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586060224,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    },
    {
      "addr": 18446744071586084416,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071586087696,
      "name": "uuid_store",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586499344,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1270",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586523536,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:88",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586526816,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:161",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586499344,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    },
    {
      "addr": 18446744071586523536,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071586526816,
      "name": "uuid_store",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "uuid_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586611088,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1270",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586635264,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:88",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586638544,
      "name": "uuid_store",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:161",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586611088,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    },
    {
      "addr": 18446744071586635264,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071586638544,
      "name": "uuid_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
ssize_t uuid_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
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
