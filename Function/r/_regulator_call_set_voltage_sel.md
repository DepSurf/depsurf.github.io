# Function: <code>_regulator_call_set_voltage_sel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583935760,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:2706",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_do_set_voltage"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584263044,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:2722",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_do_set_voltage"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584444767,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:2723",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_do_set_voltage"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584528249,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:2735",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_do_set_voltage"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584938385,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:2743",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_do_set_voltage"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585167543,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:2800",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_do_set_voltage"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585279991,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:3128",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_do_set_voltage"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int _regulator_call_set_voltage_sel(struct regulator_dev * rdev, int uV, unsigned int selector)
```

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585499872,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:3083",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_do_set_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585499872,
      "name": "_regulator_call_set_voltage_sel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int _regulator_call_set_voltage_sel(struct regulator_dev * rdev, int uV, unsigned int selector)
```

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585631600,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:3091",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_do_set_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585631600,
      "name": "_regulator_call_set_voltage_sel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int _regulator_call_set_voltage_sel(struct regulator_dev * rdev, int uV, unsigned int selector)
```

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586361648,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:3122",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_set_voltage_sel_step"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586361648,
      "name": "_regulator_call_set_voltage_sel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int _regulator_call_set_voltage_sel(struct regulator_dev * rdev, int uV, unsigned int selector)
```

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586479424,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:3252",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_set_voltage_sel_step"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586479424,
      "name": "_regulator_call_set_voltage_sel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int _regulator_call_set_voltage_sel(struct regulator_dev * rdev, int uV, unsigned int selector)
```

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586362832,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:3250",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_do_set_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586362832,
      "name": "_regulator_call_set_voltage_sel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int _regulator_call_set_voltage_sel(struct regulator_dev * rdev, int uV, unsigned int selector)
```

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586872032,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:3350",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_do_set_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586872032,
      "name": "_regulator_call_set_voltage_sel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int _regulator_call_set_voltage_sel(struct regulator_dev * rdev, int uV, unsigned int selector)
```

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588160320,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:3397",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_do_set_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588160320,
      "name": "_regulator_call_set_voltage_sel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
int _regulator_call_set_voltage_sel(struct regulator_dev * rdev, int uV, unsigned int selector)
```

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589578304,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:3429",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_do_set_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589578304,
      "name": "_regulator_call_set_voltage_sel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
int _regulator_call_set_voltage_sel(struct regulator_dev * rdev, int uV, unsigned int selector)
```

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589881808,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:3495",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_do_set_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589881808,
      "name": "_regulator_call_set_voltage_sel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
int _regulator_call_set_voltage_sel(struct regulator_dev * rdev, int uV, unsigned int selector)
```

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590219488,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:3501",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_do_set_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590219488,
      "name": "_regulator_call_set_voltage_sel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int _regulator_call_set_voltage_sel(struct regulator_dev * rdev, int uV, unsigned int selector)
```

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498289008,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:3091",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_do_set_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498289008,
      "name": "_regulator_call_set_voltage_sel",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int _regulator_call_set_voltage_sel(struct regulator_dev * rdev, int uV, unsigned int selector)
```

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230969828,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:3091",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_do_set_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230969828,
      "name": "_regulator_call_set_voltage_sel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int _regulator_call_set_voltage_sel(struct regulator_dev * rdev, int uV, unsigned int selector)
```

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291453728,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:3091",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_do_set_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291453728,
      "name": "_regulator_call_set_voltage_sel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int _regulator_call_set_voltage_sel(struct regulator_dev * rdev, int uV, unsigned int selector)
```

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275985870,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:3091",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_do_set_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275985870,
      "name": "_regulator_call_set_voltage_sel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int _regulator_call_set_voltage_sel(struct regulator_dev * rdev, int uV, unsigned int selector)
```

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585392752,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:3091",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_do_set_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585392752,
      "name": "_regulator_call_set_voltage_sel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int _regulator_call_set_voltage_sel(struct regulator_dev * rdev, int uV, unsigned int selector)
```

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585262672,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:3091",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_do_set_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585262672,
      "name": "_regulator_call_set_voltage_sel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int _regulator_call_set_voltage_sel(struct regulator_dev * rdev, int uV, unsigned int selector)
```

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585582000,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:3091",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_do_set_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585582000,
      "name": "_regulator_call_set_voltage_sel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int _regulator_call_set_voltage_sel(struct regulator_dev * rdev, int uV, unsigned int selector)
```

```json
{
  "name": "_regulator_call_set_voltage_sel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585690080,
      "name": "_regulator_call_set_voltage_sel",
      "external": false,
      "loc": "drivers/regulator/core.c:3091",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_do_set_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585690080,
      "name": "_regulator_call_set_voltage_sel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int _regulator_call_set_voltage_sel(struct regulator_dev * rdev, int uV, unsigned int selector)
```
</details>
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
