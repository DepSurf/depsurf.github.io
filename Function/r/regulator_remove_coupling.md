# Function: <code>regulator_remove_coupling</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_remove_coupling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585296192,
      "name": "regulator_remove_coupling",
      "external": false,
      "loc": "drivers/regulator/core.c:4778",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_unregister"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void regulator_remove_coupling(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_remove_coupling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_remove_coupling",
      "external": false,
      "loc": "drivers/regulator/core.c:4861",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585492608,
      "name": "regulator_remove_coupling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
    },
    {
      "addr": 18446744071585516874,
      "name": "regulator_remove_coupling.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void regulator_remove_coupling(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_remove_coupling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_remove_coupling",
      "external": false,
      "loc": "drivers/regulator/core.c:4871",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585638272,
      "name": "regulator_remove_coupling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
    },
    {
      "addr": 18446744071585658500,
      "name": "regulator_remove_coupling.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void regulator_remove_coupling(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_remove_coupling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_remove_coupling",
      "external": false,
      "loc": "drivers/regulator/core.c:4916",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586366272,
      "name": "regulator_remove_coupling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
    },
    {
      "addr": 18446744071586382699,
      "name": "regulator_remove_coupling.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void regulator_remove_coupling(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_remove_coupling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_remove_coupling",
      "external": false,
      "loc": "drivers/regulator/core.c:5051",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586485200,
      "name": "regulator_remove_coupling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
    },
    {
      "addr": 18446744071591454869,
      "name": "regulator_remove_coupling.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void regulator_remove_coupling(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_remove_coupling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_remove_coupling",
      "external": false,
      "loc": "drivers/regulator/core.c:5053",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586368640,
      "name": "regulator_remove_coupling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
    },
    {
      "addr": 18446744071591396662,
      "name": "regulator_remove_coupling.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void regulator_remove_coupling(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_remove_coupling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_remove_coupling",
      "external": false,
      "loc": "drivers/regulator/core.c:5190",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586877936,
      "name": "regulator_remove_coupling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
    },
    {
      "addr": 18446744071592441360,
      "name": "regulator_remove_coupling.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void regulator_remove_coupling(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_remove_coupling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_remove_coupling",
      "external": false,
      "loc": "drivers/regulator/core.c:5255",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588165952,
      "name": "regulator_remove_coupling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
    },
    {
      "addr": 18446744071594309609,
      "name": "regulator_remove_coupling.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void regulator_remove_coupling(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_remove_coupling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589569776,
      "name": "regulator_remove_coupling",
      "external": false,
      "loc": "drivers/regulator/core.c:5296",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589569776,
      "name": "regulator_remove_coupling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
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
void regulator_remove_coupling(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_remove_coupling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589871360,
      "name": "regulator_remove_coupling",
      "external": false,
      "loc": "drivers/regulator/core.c:5360",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589871360,
      "name": "regulator_remove_coupling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
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
void regulator_remove_coupling(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_remove_coupling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590209200,
      "name": "regulator_remove_coupling",
      "external": false,
      "loc": "drivers/regulator/core.c:5419",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590209200,
      "name": "regulator_remove_coupling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
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
void regulator_remove_coupling(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_remove_coupling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498293552,
      "name": "regulator_remove_coupling",
      "external": false,
      "loc": "drivers/regulator/core.c:4871",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498293552,
      "name": "regulator_remove_coupling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
void regulator_remove_coupling(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_remove_coupling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230979808,
      "name": "regulator_remove_coupling",
      "external": false,
      "loc": "drivers/regulator/core.c:4871",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230979808,
      "name": "regulator_remove_coupling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
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
void regulator_remove_coupling(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_remove_coupling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291464848,
      "name": "regulator_remove_coupling",
      "external": false,
      "loc": "drivers/regulator/core.c:4871",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291464848,
      "name": "regulator_remove_coupling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
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
void regulator_remove_coupling(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_remove_coupling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275991798,
      "name": "regulator_remove_coupling",
      "external": false,
      "loc": "drivers/regulator/core.c:4871",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275991798,
      "name": "regulator_remove_coupling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
void regulator_remove_coupling(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_remove_coupling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_remove_coupling",
      "external": false,
      "loc": "drivers/regulator/core.c:4871",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585399424,
      "name": "regulator_remove_coupling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
    },
    {
      "addr": 18446744071585419421,
      "name": "regulator_remove_coupling.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void regulator_remove_coupling(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_remove_coupling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_remove_coupling",
      "external": false,
      "loc": "drivers/regulator/core.c:4871",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585269344,
      "name": "regulator_remove_coupling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
    },
    {
      "addr": 18446744071585289572,
      "name": "regulator_remove_coupling.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void regulator_remove_coupling(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_remove_coupling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_remove_coupling",
      "external": false,
      "loc": "drivers/regulator/core.c:4871",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585588672,
      "name": "regulator_remove_coupling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
    },
    {
      "addr": 18446744071585608900,
      "name": "regulator_remove_coupling.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void regulator_remove_coupling(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_remove_coupling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_remove_coupling",
      "external": false,
      "loc": "drivers/regulator/core.c:4871",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585696800,
      "name": "regulator_remove_coupling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
    },
    {
      "addr": 18446744071585717028,
      "name": "regulator_remove_coupling.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void regulator_remove_coupling(struct regulator_dev * rdev)
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
