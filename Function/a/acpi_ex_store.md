# Function: <code>acpi_ex_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583667987,
      "name": "acpi_ex_store",
      "external": true,
      "loc": "drivers/acpi/acpica/exstore.c:86",
      "file": "drivers/acpi/acpica/exstore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583667987,
      "name": "acpi_ex_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 602
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583990870,
      "name": "acpi_ex_store",
      "external": true,
      "loc": "drivers/acpi/acpica/exstore.c:86",
      "file": "drivers/acpi/acpica/exstore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583990870,
      "name": "acpi_ex_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 614
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584132266,
      "name": "acpi_ex_store",
      "external": true,
      "loc": "drivers/acpi/acpica/exstore.c:86",
      "file": "drivers/acpi/acpica/exstore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132266,
      "name": "acpi_ex_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 614
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584199390,
      "name": "acpi_ex_store",
      "external": true,
      "loc": "drivers/acpi/acpica/exstore.c:86",
      "file": "drivers/acpi/acpica/exstore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584199390,
      "name": "acpi_ex_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 614
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
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584524639,
      "name": "acpi_ex_store",
      "external": true,
      "loc": "drivers/acpi/acpica/exstore.c:86",
      "file": "drivers/acpi/acpica/exstore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584524639,
      "name": "acpi_ex_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1113
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
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584748981,
      "name": "acpi_ex_store",
      "external": true,
      "loc": "drivers/acpi/acpica/exstore.c:52",
      "file": "drivers/acpi/acpica/exstore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584748981,
      "name": "acpi_ex_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1115
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
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584850539,
      "name": "acpi_ex_store",
      "external": true,
      "loc": "drivers/acpi/acpica/exstore.c:52",
      "file": "drivers/acpi/acpica/exstore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584850539,
      "name": "acpi_ex_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1125
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
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585054207,
      "name": "acpi_ex_store",
      "external": true,
      "loc": "drivers/acpi/acpica/exstore.c:52",
      "file": "drivers/acpi/acpica/exstore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585054207,
      "name": "acpi_ex_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1129
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
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585190292,
      "name": "acpi_ex_store",
      "external": true,
      "loc": "drivers/acpi/acpica/exstore.c:52",
      "file": "drivers/acpi/acpica/exstore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585190292,
      "name": "acpi_ex_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1129
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
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585896168,
      "name": "acpi_ex_store",
      "external": true,
      "loc": "drivers/acpi/acpica/exstore.c:52",
      "file": "drivers/acpi/acpica/exstore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585896168,
      "name": "acpi_ex_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 627
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
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586017521,
      "name": "acpi_ex_store",
      "external": true,
      "loc": "drivers/acpi/acpica/exstore.c:52",
      "file": "drivers/acpi/acpica/exstore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586017521,
      "name": "acpi_ex_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 627
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
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585894534,
      "name": "acpi_ex_store",
      "external": true,
      "loc": "drivers/acpi/acpica/exstore.c:52",
      "file": "drivers/acpi/acpica/exstore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585894534,
      "name": "acpi_ex_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 627
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
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586382038,
      "name": "acpi_ex_store",
      "external": true,
      "loc": "drivers/acpi/acpica/exstore.c:52",
      "file": "drivers/acpi/acpica/exstore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586382038,
      "name": "acpi_ex_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 627
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
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587630045,
      "name": "acpi_ex_store",
      "external": true,
      "loc": "drivers/acpi/acpica/exstore.c:52",
      "file": "drivers/acpi/acpica/exstore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587630045,
      "name": "acpi_ex_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588928352,
      "name": "acpi_ex_store",
      "external": true,
      "loc": "drivers/acpi/acpica/exstore.c:52",
      "file": "drivers/acpi/acpica/exstore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588928352,
      "name": "acpi_ex_store",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589218416,
      "name": "acpi_ex_store",
      "external": true,
      "loc": "drivers/acpi/acpica/exstore.c:52",
      "file": "drivers/acpi/acpica/exstore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589218416,
      "name": "acpi_ex_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 742
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
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589524928,
      "name": "acpi_ex_store",
      "external": true,
      "loc": "drivers/acpi/acpica/exstore.c:52",
      "file": "drivers/acpi/acpica/exstore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589524928,
      "name": "acpi_ex_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 742
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
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497535564,
      "name": "acpi_ex_store",
      "external": true,
      "loc": "drivers/acpi/acpica/exstore.c:52",
      "file": "drivers/acpi/acpica/exstore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497535564,
      "name": "acpi_ex_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585068543,
      "name": "acpi_ex_store",
      "external": true,
      "loc": "drivers/acpi/acpica/exstore.c:52",
      "file": "drivers/acpi/acpica/exstore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585068543,
      "name": "acpi_ex_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 626
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
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584984055,
      "name": "acpi_ex_store",
      "external": true,
      "loc": "drivers/acpi/acpica/exstore.c:52",
      "file": "drivers/acpi/acpica/exstore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584984055,
      "name": "acpi_ex_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 626
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
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585141876,
      "name": "acpi_ex_store",
      "external": true,
      "loc": "drivers/acpi/acpica/exstore.c:52",
      "file": "drivers/acpi/acpica/exstore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585141876,
      "name": "acpi_ex_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1129
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
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585248036,
      "name": "acpi_ex_store",
      "external": true,
      "loc": "drivers/acpi/acpica/exstore.c:52",
      "file": "drivers/acpi/acpica/exstore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585248036,
      "name": "acpi_ex_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1129
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
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_ex_store(union acpi_operand_object * source_desc, union acpi_operand_object * dest_desc, struct acpi_walk_state * walk_state)
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
