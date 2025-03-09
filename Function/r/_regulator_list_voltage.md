# Function: <code>_regulator_list_voltage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583937040,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:2406",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583937040,
      "name": "_regulator_list_voltage.isra.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584267008,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:2450",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584267008,
      "name": "_regulator_list_voltage.isra.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584448768,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:2451",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584448768,
      "name": "_regulator_list_voltage.isra.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584532368,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:2463",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532368,
      "name": "_regulator_list_voltage.isra.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584942576,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:2471",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584942576,
      "name": "_regulator_list_voltage.isra.20",
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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev * rdev, unsigned int selector, int lock)
```

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585168464,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:2528",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_list_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585168464,
      "name": "_regulator_list_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int _regulator_list_voltage(struct regulator_dev * rdev, unsigned int selector, int lock)
```

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585291936,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:2851",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585291936,
      "name": "_regulator_list_voltage",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev * rdev, unsigned int selector, int lock)
```

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585498352,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:2806",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:_regulator_list_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585498352,
      "name": "_regulator_list_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev * rdev, unsigned int selector, int lock)
```

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585645584,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:2814",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:_regulator_list_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585645584,
      "name": "_regulator_list_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
int _regulator_list_voltage(struct regulator_dev * rdev, unsigned int selector, int lock)
```

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586358720,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:2845",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586358720,
      "name": "_regulator_list_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
int _regulator_list_voltage(struct regulator_dev * rdev, unsigned int selector, int lock)
```

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586476336,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:2971",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586476336,
      "name": "_regulator_list_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
int _regulator_list_voltage(struct regulator_dev * rdev, unsigned int selector, int lock)
```

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586360032,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:2969",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586360032,
      "name": "_regulator_list_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev * rdev, unsigned int selector, int lock)
```

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586886928,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3069",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586886928,
      "name": "_regulator_list_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev * rdev, unsigned int selector, int lock)
```

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588176336,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3116",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588176336,
      "name": "_regulator_list_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
int _regulator_list_voltage(struct regulator_dev * rdev, unsigned int selector, int lock)
```

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589570352,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3148",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589570352,
      "name": "_regulator_list_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
int _regulator_list_voltage(struct regulator_dev * rdev, unsigned int selector, int lock)
```

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589871936,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3214",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589871936,
      "name": "_regulator_list_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
int _regulator_list_voltage(struct regulator_dev * rdev, unsigned int selector, int lock)
```

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590209776,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3220",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590209776,
      "name": "_regulator_list_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
int _regulator_list_voltage(struct regulator_dev * rdev, unsigned int selector, int lock)
```

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498306856,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:2814",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:_regulator_list_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498306856,
      "name": "_regulator_list_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
int _regulator_list_voltage(struct regulator_dev * rdev, unsigned int selector, int lock)
```

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230987900,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:2814",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:_regulator_list_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230987900,
      "name": "_regulator_list_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
int _regulator_list_voltage(struct regulator_dev * rdev, unsigned int selector, int lock)
```

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291476544,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:2814",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291476544,
      "name": "_regulator_list_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
int _regulator_list_voltage(struct regulator_dev * rdev, unsigned int selector, int lock)
```

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275998260,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:2814",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275998260,
      "name": "_regulator_list_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
int _regulator_list_voltage(struct regulator_dev * rdev, unsigned int selector, int lock)
```

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585406192,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:2814",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:_regulator_list_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585406192,
      "name": "_regulator_list_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
int _regulator_list_voltage(struct regulator_dev * rdev, unsigned int selector, int lock)
```

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585276656,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:2814",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:_regulator_list_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585276656,
      "name": "_regulator_list_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
int _regulator_list_voltage(struct regulator_dev * rdev, unsigned int selector, int lock)
```

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585595984,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:2814",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:_regulator_list_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585595984,
      "name": "_regulator_list_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
int _regulator_list_voltage(struct regulator_dev * rdev, unsigned int selector, int lock)
```

```json
{
  "name": "_regulator_list_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585704112,
      "name": "_regulator_list_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:2814",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_time",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:_regulator_list_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585704112,
      "name": "_regulator_list_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
int _regulator_list_voltage(struct regulator_dev * rdev, unsigned int selector, int lock)
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
