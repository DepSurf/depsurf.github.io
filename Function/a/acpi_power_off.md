# Function: <code>acpi_power_off</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void acpi_power_off()
```

```json
{
  "name": "acpi_power_off",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583545115,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/sleep.c:824",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583598991,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/power.c:302",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_on_list",
        "drivers/acpi/power.c:acpi_power_transition"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583545115,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void acpi_power_off()
```

```json
{
  "name": "acpi_power_off",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583866246,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/sleep.c:881",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583923791,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/power.c:302",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583866246,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void acpi_power_off()
```

```json
{
  "name": "acpi_power_off",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584005345,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/sleep.c:864",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584064823,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/power.c:302",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584005345,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void acpi_power_off()
```

```json
{
  "name": "acpi_power_off",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584055472,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/sleep.c:1026",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584124864,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/power.c:303",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584055472,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584124864,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void acpi_power_off()
```

```json
{
  "name": "acpi_power_off",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584322528,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/sleep.c:1228",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584398884,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/power.c:303",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584322528,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void acpi_power_off()
```

```json
{
  "name": "acpi_power_off",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584546900,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/sleep.c:1260",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584621638,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/power.c:303",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584546900,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void acpi_power_off()
```

```json
{
  "name": "acpi_power_off",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584644116,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/sleep.c:1266",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584720134,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/power.c:325",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584644116,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void acpi_power_off()
```

```json
{
  "name": "acpi_power_off",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584844021,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/sleep.c:1269",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584922719,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/power.c:446",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584844021,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void acpi_power_off()
```

```json
{
  "name": "acpi_power_off",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584979763,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/sleep.c:1310",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585058527,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/power.c:446",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584979763,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void acpi_power_off()
```

```json
{
  "name": "acpi_power_off",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585676658,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/sleep.c:1310",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585762012,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/power.c:444",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585676658,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void acpi_power_off()
```

```json
{
  "name": "acpi_power_off",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591431393,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/sleep.c:1029",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585881103,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/power.c:444",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591431393,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void acpi_power_off()
```

```json
{
  "name": "acpi_power_off",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591372554,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/sleep.c:1027",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585758170,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/power.c:435",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591372554,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void acpi_power_off()
```

```json
{
  "name": "acpi_power_off",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586157424,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/sleep.c:1028",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586240907,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/power.c:459",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_disable_wakeup_device_power",
        "drivers/acpi/power.c:acpi_power_on_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586157424,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int acpi_power_off(struct sys_off_data * data)
```

```json
{
  "name": "acpi_power_off",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587391024,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/sleep.c:1055",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587479530,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/power.c:459",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_disable_wakeup_device_power",
        "drivers/acpi/power.c:acpi_power_on_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587391024,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int acpi_power_off(struct sys_off_data * data)
```

```json
{
  "name": "acpi_power_off",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588642944,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/sleep.c:1062",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588747338,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/power.c:459",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_disable_wakeup_device_power",
        "drivers/acpi/power.c:acpi_power_on_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588642944,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int acpi_power_off(struct sys_off_data * data)
```

```json
{
  "name": "acpi_power_off",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588930912,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/sleep.c:1076",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589035738,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/power.c:460",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_disable_wakeup_device_power",
        "drivers/acpi/power.c:acpi_power_on_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588930912,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int acpi_power_off(struct sys_off_data * data)
```

```json
{
  "name": "acpi_power_off",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589227520,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/sleep.c:1076",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589340330,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/power.c:460",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_disable_wakeup_device_power",
        "drivers/acpi/power.c:acpi_power_on_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589227520,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int acpi_power_off(struct acpi_power_resource * resource)
```

```json
{
  "name": "acpi_power_off",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497461824,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/power.c:446",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497461824,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
void acpi_power_off()
```

```json
{
  "name": "acpi_power_off",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584924478,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/sleep.c:1310",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584986688,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/power.c:446",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584924478,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584986688,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void acpi_power_off()
```

```json
{
  "name": "acpi_power_off",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584833171,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/sleep.c:1310",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584902272,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/power.c:446",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584833171,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584902272,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void acpi_power_off()
```

```json
{
  "name": "acpi_power_off",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584931347,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/sleep.c:1310",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585010111,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/power.c:446",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584931347,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void acpi_power_off()
```

```json
{
  "name": "acpi_power_off",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585037523,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/sleep.c:1310",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585116287,
      "name": "acpi_power_off",
      "external": false,
      "loc": "drivers/acpi/power.c:446",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585037523,
      "name": "acpi_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sys_off_data * data</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct acpi_power_resource * resource</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void acpi_power_off()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_power_off()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_power_off()
```
</details>
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
