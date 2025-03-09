# Function: <code>_regmap_raw_write_impl</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int _regmap_raw_write_impl(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write_impl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585798688,
      "name": "_regmap_raw_write_impl",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:1443",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585798688,
      "name": "_regmap_raw_write_impl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2002
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int _regmap_raw_write_impl(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write_impl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585932064,
      "name": "_regmap_raw_write_impl",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:1481",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585932064,
      "name": "_regmap_raw_write_impl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2002
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
int _regmap_raw_write_impl(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write_impl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regmap_raw_write_impl",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:1477",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586173600,
      "name": "_regmap_raw_write_impl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1786
    },
    {
      "addr": 18446744071586181487,
      "name": "_regmap_raw_write_impl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
int _regmap_raw_write_impl(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write_impl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regmap_raw_write_impl",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:1477",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586322000,
      "name": "_regmap_raw_write_impl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1889
    },
    {
      "addr": 18446744071586329978,
      "name": "_regmap_raw_write_impl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int _regmap_raw_write_impl(struct regmap * map, unsigned int reg, const void * val, size_t val_len, bool noinc)
```

```json
{
  "name": "_regmap_raw_write_impl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regmap_raw_write_impl",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:1471",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587091888,
      "name": "_regmap_raw_write_impl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2026
    },
    {
      "addr": 18446744071587100557,
      "name": "_regmap_raw_write_impl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int _regmap_raw_write_impl(struct regmap * map, unsigned int reg, const void * val, size_t val_len, bool noinc)
```

```json
{
  "name": "_regmap_raw_write_impl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regmap_raw_write_impl",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:1617",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587178080,
      "name": "_regmap_raw_write_impl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1969
    },
    {
      "addr": 18446744071591490590,
      "name": "_regmap_raw_write_impl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int _regmap_raw_write_impl(struct regmap * map, unsigned int reg, const void * val, size_t val_len, bool noinc)
```

```json
{
  "name": "_regmap_raw_write_impl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regmap_raw_write_impl",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:1617",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587065616,
      "name": "_regmap_raw_write_impl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1927
    },
    {
      "addr": 18446744071591433580,
      "name": "_regmap_raw_write_impl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int _regmap_raw_write_impl(struct regmap * map, unsigned int reg, const void * val, size_t val_len, bool noinc)
```

```json
{
  "name": "_regmap_raw_write_impl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regmap_raw_write_impl",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:1658",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587636592,
      "name": "_regmap_raw_write_impl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1959
    },
    {
      "addr": 18446744071592495479,
      "name": "_regmap_raw_write_impl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
int _regmap_raw_write_impl(struct regmap * map, unsigned int reg, const void * val, size_t val_len, bool noinc)
```

```json
{
  "name": "_regmap_raw_write_impl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regmap_raw_write_impl",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:1677",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588980016,
      "name": "_regmap_raw_write_impl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2119
    },
    {
      "addr": 18446744071594365731,
      "name": "_regmap_raw_write_impl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
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
int _regmap_raw_write_impl(struct regmap * map, unsigned int reg, const void * val, size_t val_len, bool noinc)
```

```json
{
  "name": "_regmap_raw_write_impl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regmap_raw_write_impl",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:1679",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590500464,
      "name": "_regmap_raw_write_impl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2384
    },
    {
      "addr": 18446744071596249266,
      "name": "_regmap_raw_write_impl.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int _regmap_raw_write_impl(struct regmap * map, unsigned int reg, const void * val, size_t val_len, bool noinc)
```

```json
{
  "name": "_regmap_raw_write_impl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regmap_raw_write_impl",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:1691",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590824192,
      "name": "_regmap_raw_write_impl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2419
    },
    {
      "addr": 18446744071596777871,
      "name": "_regmap_raw_write_impl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int _regmap_raw_write_impl(struct regmap * map, unsigned int reg, const void * val, size_t val_len, bool noinc)
```

```json
{
  "name": "_regmap_raw_write_impl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regmap_raw_write_impl",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:1597",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591167280,
      "name": "_regmap_raw_write_impl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2399
    },
    {
      "addr": 18446744071597686836,
      "name": "_regmap_raw_write_impl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int _regmap_raw_write_impl(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write_impl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499158224,
      "name": "_regmap_raw_write_impl",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:1477",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499158224,
      "name": "_regmap_raw_write_impl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int _regmap_raw_write_impl(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write_impl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231693852,
      "name": "_regmap_raw_write_impl",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:1477",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231693852,
      "name": "_regmap_raw_write_impl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int _regmap_raw_write_impl(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write_impl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292355856,
      "name": "_regmap_raw_write_impl",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:1477",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292355856,
      "name": "_regmap_raw_write_impl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2688
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
int _regmap_raw_write_impl(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write_impl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276458730,
      "name": "_regmap_raw_write_impl",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:1477",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276458730,
      "name": "_regmap_raw_write_impl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1544
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
int _regmap_raw_write_impl(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write_impl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regmap_raw_write_impl",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:1477",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586085248,
      "name": "_regmap_raw_write_impl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1889
    },
    {
      "addr": 18446744071586093226,
      "name": "_regmap_raw_write_impl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int _regmap_raw_write_impl(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write_impl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regmap_raw_write_impl",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:1477",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585931200,
      "name": "_regmap_raw_write_impl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1889
    },
    {
      "addr": 18446744071585939178,
      "name": "_regmap_raw_write_impl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int _regmap_raw_write_impl(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write_impl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regmap_raw_write_impl",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:1477",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586269968,
      "name": "_regmap_raw_write_impl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1889
    },
    {
      "addr": 18446744071586277946,
      "name": "_regmap_raw_write_impl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int _regmap_raw_write_impl(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write_impl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regmap_raw_write_impl",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:1477",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586381088,
      "name": "_regmap_raw_write_impl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1964
    },
    {
      "addr": 18446744071586389210,
      "name": "_regmap_raw_write_impl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int _regmap_raw_write_impl(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool noinc</code>
</li>
</ul>
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
