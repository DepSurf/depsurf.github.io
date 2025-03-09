# Function: <code>acpi_ut_create_buffer_object</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```

```json
{
  "name": "acpi_ut_create_buffer_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583732615,
      "name": "acpi_ut_create_buffer_object",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:233",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_concat_template",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_unicode",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_resource",
        "drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583732615,
      "name": "acpi_ut_create_buffer_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```

```json
{
  "name": "acpi_ut_create_buffer_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584056857,
      "name": "acpi_ut_create_buffer_object",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:233",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconcat.c:acpi_ex_concat_template",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_resource",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_unicode",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584056857,
      "name": "acpi_ut_create_buffer_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```

```json
{
  "name": "acpi_ut_create_buffer_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584198695,
      "name": "acpi_ut_create_buffer_object",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:233",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconcat.c:acpi_ex_concat_template",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_resource",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_unicode",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584198695,
      "name": "acpi_ut_create_buffer_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```

```json
{
  "name": "acpi_ut_create_buffer_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584266306,
      "name": "acpi_ut_create_buffer_object",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:233",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconcat.c:acpi_ex_concat_template",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_resource",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_unicode",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584266306,
      "name": "acpi_ut_create_buffer_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```

```json
{
  "name": "acpi_ut_create_buffer_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584635622,
      "name": "acpi_ut_create_buffer_object",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:233",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconcat.c:acpi_ex_concat_template",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_resource",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_unicode",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584635622,
      "name": "acpi_ut_create_buffer_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```

```json
{
  "name": "acpi_ut_create_buffer_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584861340,
      "name": "acpi_ut_create_buffer_object",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:201",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconcat.c:acpi_ex_concat_template",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_resource",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_unicode",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584861340,
      "name": "acpi_ut_create_buffer_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```

```json
{
  "name": "acpi_ut_create_buffer_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584964834,
      "name": "acpi_ut_create_buffer_object",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:201",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconcat.c:acpi_ex_concat_template",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_resource",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_unicode",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584964834,
      "name": "acpi_ut_create_buffer_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```

```json
{
  "name": "acpi_ut_create_buffer_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585168013,
      "name": "acpi_ut_create_buffer_object",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:201",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconcat.c:acpi_ex_concat_template",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_resource",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_unicode",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585168013,
      "name": "acpi_ut_create_buffer_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```

```json
{
  "name": "acpi_ut_create_buffer_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585304360,
      "name": "acpi_ut_create_buffer_object",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:201",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconcat.c:acpi_ex_concat_template",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_resource",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_unicode",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585304360,
      "name": "acpi_ut_create_buffer_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```

```json
{
  "name": "acpi_ut_create_buffer_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586011089,
      "name": "acpi_ut_create_buffer_object",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:201",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconcat.c:acpi_ex_concat_template",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_resource",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_unicode",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586011089,
      "name": "acpi_ut_create_buffer_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```

```json
{
  "name": "acpi_ut_create_buffer_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586133901,
      "name": "acpi_ut_create_buffer_object",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:201",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconcat.c:acpi_ex_concat_template",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_resource",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_unicode",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586133901,
      "name": "acpi_ut_create_buffer_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```

```json
{
  "name": "acpi_ut_create_buffer_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586010441,
      "name": "acpi_ut_create_buffer_object",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:201",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconcat.c:acpi_ex_concat_template",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_resource",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_unicode",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586010441,
      "name": "acpi_ut_create_buffer_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```

```json
{
  "name": "acpi_ut_create_buffer_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586500464,
      "name": "acpi_ut_create_buffer_object",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:201",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconcat.c:acpi_ex_concat_template",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_resource",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_unicode",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586500464,
      "name": "acpi_ut_create_buffer_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```

```json
{
  "name": "acpi_ut_create_buffer_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587755720,
      "name": "acpi_ut_create_buffer_object",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:201",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconcat.c:acpi_ex_concat_template",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_resource",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_unicode",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_repair_null_element",
        "drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587755720,
      "name": "acpi_ut_create_buffer_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```

```json
{
  "name": "acpi_ut_create_buffer_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589082736,
      "name": "acpi_ut_create_buffer_object",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:201",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconcat.c:acpi_ex_concat_template",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_resource",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_unicode",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_repair_null_element",
        "drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589082736,
      "name": "acpi_ut_create_buffer_object",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```

```json
{
  "name": "acpi_ut_create_buffer_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589374496,
      "name": "acpi_ut_create_buffer_object",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:201",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconcat.c:acpi_ex_concat_template",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_resource",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_unicode",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_repair_null_element",
        "drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589374496,
      "name": "acpi_ut_create_buffer_object",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```

```json
{
  "name": "acpi_ut_create_buffer_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589681600,
      "name": "acpi_ut_create_buffer_object",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:201",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconcat.c:acpi_ex_concat_template",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_resource",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_unicode",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_repair_null_element",
        "drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589681600,
      "name": "acpi_ut_create_buffer_object",
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
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```

```json
{
  "name": "acpi_ut_create_buffer_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497616900,
      "name": "acpi_ut_create_buffer_object",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:201",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconcat.c:acpi_ex_concat_template",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_resource",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_unicode",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497616900,
      "name": "acpi_ut_create_buffer_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```

```json
{
  "name": "acpi_ut_create_buffer_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585138215,
      "name": "acpi_ut_create_buffer_object",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:201",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconcat.c:acpi_ex_concat_template",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_resource",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_unicode",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585138215,
      "name": "acpi_ut_create_buffer_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```

```json
{
  "name": "acpi_ut_create_buffer_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585053420,
      "name": "acpi_ut_create_buffer_object",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:201",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconcat.c:acpi_ex_concat_template",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_resource",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_unicode",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585053420,
      "name": "acpi_ut_create_buffer_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```

```json
{
  "name": "acpi_ut_create_buffer_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585255944,
      "name": "acpi_ut_create_buffer_object",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:201",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconcat.c:acpi_ex_concat_template",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_resource",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_unicode",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585255944,
      "name": "acpi_ut_create_buffer_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```

```json
{
  "name": "acpi_ut_create_buffer_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585362104,
      "name": "acpi_ut_create_buffer_object",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:201",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconcat.c:acpi_ex_concat_template",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_resource",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_unicode",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_buffer",
        "drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585362104,
      "name": "acpi_ut_create_buffer_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
union acpi_operand_object * acpi_ut_create_buffer_object(acpi_size buffer_size)
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
