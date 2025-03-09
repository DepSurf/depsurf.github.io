# Function: <code>acpi_ut_get_simple_object_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ut_get_simple_object_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583731724,
      "name": "acpi_ut_get_simple_object_size",
      "external": false,
      "loc": "drivers/acpi/acpica/utobject.c:454",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size"
      ],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583731724,
      "name": "acpi_ut_get_simple_object_size.part.0",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ut_get_simple_object_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584057206,
      "name": "acpi_ut_get_simple_object_size",
      "external": false,
      "loc": "drivers/acpi/acpica/utobject.c:456",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size"
      ],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584055970,
      "name": "acpi_ut_get_simple_object_size.part.0",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ut_get_simple_object_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584199044,
      "name": "acpi_ut_get_simple_object_size",
      "external": false,
      "loc": "drivers/acpi/acpica/utobject.c:456",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size"
      ],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584197808,
      "name": "acpi_ut_get_simple_object_size.part.0",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ut_get_simple_object_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584266655,
      "name": "acpi_ut_get_simple_object_size",
      "external": false,
      "loc": "drivers/acpi/acpica/utobject.c:456",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size"
      ],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584265419,
      "name": "acpi_ut_get_simple_object_size.part.0",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_ut_get_simple_object_size(union acpi_operand_object * internal_object, acpi_size * obj_length)
```

```json
{
  "name": "acpi_ut_get_simple_object_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584633738,
      "name": "acpi_ut_get_simple_object_size",
      "external": false,
      "loc": "drivers/acpi/acpica/utobject.c:456",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584633738,
      "name": "acpi_ut_get_simple_object_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
acpi_status acpi_ut_get_simple_object_size(union acpi_operand_object * internal_object, acpi_size * obj_length)
```

```json
{
  "name": "acpi_ut_get_simple_object_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584859455,
      "name": "acpi_ut_get_simple_object_size",
      "external": false,
      "loc": "drivers/acpi/acpica/utobject.c:424",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584859455,
      "name": "acpi_ut_get_simple_object_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
acpi_status acpi_ut_get_simple_object_size(union acpi_operand_object * internal_object, acpi_size * obj_length)
```

```json
{
  "name": "acpi_ut_get_simple_object_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584962949,
      "name": "acpi_ut_get_simple_object_size",
      "external": false,
      "loc": "drivers/acpi/acpica/utobject.c:424",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584962949,
      "name": "acpi_ut_get_simple_object_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
acpi_status acpi_ut_get_simple_object_size(union acpi_operand_object * internal_object, acpi_size * obj_length)
```

```json
{
  "name": "acpi_ut_get_simple_object_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585166118,
      "name": "acpi_ut_get_simple_object_size",
      "external": false,
      "loc": "drivers/acpi/acpica/utobject.c:424",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585166118,
      "name": "acpi_ut_get_simple_object_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 501
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
acpi_status acpi_ut_get_simple_object_size(union acpi_operand_object * internal_object, acpi_size * obj_length)
```

```json
{
  "name": "acpi_ut_get_simple_object_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585302465,
      "name": "acpi_ut_get_simple_object_size",
      "external": false,
      "loc": "drivers/acpi/acpica/utobject.c:424",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585302465,
      "name": "acpi_ut_get_simple_object_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 501
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
acpi_status acpi_ut_get_simple_object_size(union acpi_operand_object * internal_object, acpi_size * obj_length)
```

```json
{
  "name": "acpi_ut_get_simple_object_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586009194,
      "name": "acpi_ut_get_simple_object_size",
      "external": false,
      "loc": "drivers/acpi/acpica/utobject.c:424",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586009194,
      "name": "acpi_ut_get_simple_object_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 501
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
acpi_status acpi_ut_get_simple_object_size(union acpi_operand_object * internal_object, acpi_size * obj_length)
```

```json
{
  "name": "acpi_ut_get_simple_object_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586132006,
      "name": "acpi_ut_get_simple_object_size",
      "external": false,
      "loc": "drivers/acpi/acpica/utobject.c:424",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586132006,
      "name": "acpi_ut_get_simple_object_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 501
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
acpi_status acpi_ut_get_simple_object_size(union acpi_operand_object * internal_object, acpi_size * obj_length)
```

```json
{
  "name": "acpi_ut_get_simple_object_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586008554,
      "name": "acpi_ut_get_simple_object_size",
      "external": false,
      "loc": "drivers/acpi/acpica/utobject.c:424",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586008554,
      "name": "acpi_ut_get_simple_object_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
acpi_status acpi_ut_get_simple_object_size(union acpi_operand_object * internal_object, acpi_size * obj_length)
```

```json
{
  "name": "acpi_ut_get_simple_object_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586498577,
      "name": "acpi_ut_get_simple_object_size",
      "external": false,
      "loc": "drivers/acpi/acpica/utobject.c:424",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586498577,
      "name": "acpi_ut_get_simple_object_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
acpi_status acpi_ut_get_simple_object_size(union acpi_operand_object * internal_object, acpi_size * obj_length)
```

```json
{
  "name": "acpi_ut_get_simple_object_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587753722,
      "name": "acpi_ut_get_simple_object_size",
      "external": false,
      "loc": "drivers/acpi/acpica/utobject.c:424",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_element_length"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587753722,
      "name": "acpi_ut_get_simple_object_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
acpi_status acpi_ut_get_simple_object_size(union acpi_operand_object * internal_object, acpi_size * obj_length)
```

```json
{
  "name": "acpi_ut_get_simple_object_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589080416,
      "name": "acpi_ut_get_simple_object_size",
      "external": false,
      "loc": "drivers/acpi/acpica/utobject.c:424",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_element_length"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589080416,
      "name": "acpi_ut_get_simple_object_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
acpi_status acpi_ut_get_simple_object_size(union acpi_operand_object * internal_object, acpi_size * obj_length)
```

```json
{
  "name": "acpi_ut_get_simple_object_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589372128,
      "name": "acpi_ut_get_simple_object_size",
      "external": false,
      "loc": "drivers/acpi/acpica/utobject.c:424",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_element_length"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589372128,
      "name": "acpi_ut_get_simple_object_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 571
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
acpi_status acpi_ut_get_simple_object_size(union acpi_operand_object * internal_object, acpi_size * obj_length)
```

```json
{
  "name": "acpi_ut_get_simple_object_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589679232,
      "name": "acpi_ut_get_simple_object_size",
      "external": false,
      "loc": "drivers/acpi/acpica/utobject.c:424",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_element_length"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589679232,
      "name": "acpi_ut_get_simple_object_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 571
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
acpi_status acpi_ut_get_simple_object_size(union acpi_operand_object * internal_object, acpi_size * obj_length)
```

```json
{
  "name": "acpi_ut_get_simple_object_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497615704,
      "name": "acpi_ut_get_simple_object_size",
      "external": false,
      "loc": "drivers/acpi/acpica/utobject.c:424",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497615704,
      "name": "acpi_ut_get_simple_object_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
acpi_status acpi_ut_get_simple_object_size(union acpi_operand_object * internal_object, acpi_size * obj_length)
```

```json
{
  "name": "acpi_ut_get_simple_object_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585137280,
      "name": "acpi_ut_get_simple_object_size",
      "external": false,
      "loc": "drivers/acpi/acpica/utobject.c:424",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585137280,
      "name": "acpi_ut_get_simple_object_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
acpi_status acpi_ut_get_simple_object_size(union acpi_operand_object * internal_object, acpi_size * obj_length)
```

```json
{
  "name": "acpi_ut_get_simple_object_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585052453,
      "name": "acpi_ut_get_simple_object_size",
      "external": false,
      "loc": "drivers/acpi/acpica/utobject.c:424",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585052453,
      "name": "acpi_ut_get_simple_object_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
acpi_status acpi_ut_get_simple_object_size(union acpi_operand_object * internal_object, acpi_size * obj_length)
```

```json
{
  "name": "acpi_ut_get_simple_object_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585254049,
      "name": "acpi_ut_get_simple_object_size",
      "external": false,
      "loc": "drivers/acpi/acpica/utobject.c:424",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585254049,
      "name": "acpi_ut_get_simple_object_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 501
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
acpi_status acpi_ut_get_simple_object_size(union acpi_operand_object * internal_object, acpi_size * obj_length)
```

```json
{
  "name": "acpi_ut_get_simple_object_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585360209,
      "name": "acpi_ut_get_simple_object_size",
      "external": false,
      "loc": "drivers/acpi/acpica/utobject.c:424",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585360209,
      "name": "acpi_ut_get_simple_object_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 501
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
acpi_status acpi_ut_get_simple_object_size(union acpi_operand_object * internal_object, acpi_size * obj_length)
```
</details>
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
acpi_status acpi_ut_get_simple_object_size(union acpi_operand_object * internal_object, acpi_size * obj_length)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_ut_get_simple_object_size(union acpi_operand_object * internal_object, acpi_size * obj_length)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_ut_get_simple_object_size(union acpi_operand_object * internal_object, acpi_size * obj_length)
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
