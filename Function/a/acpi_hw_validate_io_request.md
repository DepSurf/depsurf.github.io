# Function: <code>acpi_hw_validate_io_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```

```json
{
  "name": "acpi_hw_validate_io_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583674991,
      "name": "acpi_hw_validate_io_request",
      "external": false,
      "loc": "drivers/acpi/acpica/hwvalid.c:124",
      "file": "drivers/acpi/acpica/hwvalid.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583674991,
      "name": "acpi_hw_validate_io_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```

```json
{
  "name": "acpi_hw_validate_io_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583998693,
      "name": "acpi_hw_validate_io_request",
      "external": false,
      "loc": "drivers/acpi/acpica/hwvalid.c:124",
      "file": "drivers/acpi/acpica/hwvalid.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583998693,
      "name": "acpi_hw_validate_io_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```

```json
{
  "name": "acpi_hw_validate_io_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584140141,
      "name": "acpi_hw_validate_io_request",
      "external": false,
      "loc": "drivers/acpi/acpica/hwvalid.c:124",
      "file": "drivers/acpi/acpica/hwvalid.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584140141,
      "name": "acpi_hw_validate_io_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```

```json
{
  "name": "acpi_hw_validate_io_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584207427,
      "name": "acpi_hw_validate_io_request",
      "external": false,
      "loc": "drivers/acpi/acpica/hwvalid.c:124",
      "file": "drivers/acpi/acpica/hwvalid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584207427,
      "name": "acpi_hw_validate_io_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```

```json
{
  "name": "acpi_hw_validate_io_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584538039,
      "name": "acpi_hw_validate_io_request",
      "external": false,
      "loc": "drivers/acpi/acpica/hwvalid.c:124",
      "file": "drivers/acpi/acpica/hwvalid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584538039,
      "name": "acpi_hw_validate_io_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```

```json
{
  "name": "acpi_hw_validate_io_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584762373,
      "name": "acpi_hw_validate_io_request",
      "external": false,
      "loc": "drivers/acpi/acpica/hwvalid.c:90",
      "file": "drivers/acpi/acpica/hwvalid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584762373,
      "name": "acpi_hw_validate_io_request",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```

```json
{
  "name": "acpi_hw_validate_io_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584863173,
      "name": "acpi_hw_validate_io_request",
      "external": false,
      "loc": "drivers/acpi/acpica/hwvalid.c:90",
      "file": "drivers/acpi/acpica/hwvalid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584863173,
      "name": "acpi_hw_validate_io_request",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```

```json
{
  "name": "acpi_hw_validate_io_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585066955,
      "name": "acpi_hw_validate_io_request",
      "external": false,
      "loc": "drivers/acpi/acpica/hwvalid.c:90",
      "file": "drivers/acpi/acpica/hwvalid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585066955,
      "name": "acpi_hw_validate_io_request",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```

```json
{
  "name": "acpi_hw_validate_io_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585203289,
      "name": "acpi_hw_validate_io_request",
      "external": false,
      "loc": "drivers/acpi/acpica/hwvalid.c:90",
      "file": "drivers/acpi/acpica/hwvalid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585203289,
      "name": "acpi_hw_validate_io_request",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```

```json
{
  "name": "acpi_hw_validate_io_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585908844,
      "name": "acpi_hw_validate_io_request",
      "external": false,
      "loc": "drivers/acpi/acpica/hwvalid.c:90",
      "file": "drivers/acpi/acpica/hwvalid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585908844,
      "name": "acpi_hw_validate_io_request",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```

```json
{
  "name": "acpi_hw_validate_io_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586030458,
      "name": "acpi_hw_validate_io_request",
      "external": false,
      "loc": "drivers/acpi/acpica/hwvalid.c:90",
      "file": "drivers/acpi/acpica/hwvalid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_block",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586030458,
      "name": "acpi_hw_validate_io_request",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```

```json
{
  "name": "acpi_hw_validate_io_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585907472,
      "name": "acpi_hw_validate_io_request",
      "external": false,
      "loc": "drivers/acpi/acpica/hwvalid.c:90",
      "file": "drivers/acpi/acpica/hwvalid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_block",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585907472,
      "name": "acpi_hw_validate_io_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
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
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```

```json
{
  "name": "acpi_hw_validate_io_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586395384,
      "name": "acpi_hw_validate_io_request",
      "external": false,
      "loc": "drivers/acpi/acpica/hwvalid.c:90",
      "file": "drivers/acpi/acpica/hwvalid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_block",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586395384,
      "name": "acpi_hw_validate_io_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
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
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```

```json
{
  "name": "acpi_hw_validate_io_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587644406,
      "name": "acpi_hw_validate_io_request",
      "external": false,
      "loc": "drivers/acpi/acpica/hwvalid.c:90",
      "file": "drivers/acpi/acpica/hwvalid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_block",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587644406,
      "name": "acpi_hw_validate_io_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
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
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```

```json
{
  "name": "acpi_hw_validate_io_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588946464,
      "name": "acpi_hw_validate_io_request",
      "external": false,
      "loc": "drivers/acpi/acpica/hwvalid.c:90",
      "file": "drivers/acpi/acpica/hwvalid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_block",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588946464,
      "name": "acpi_hw_validate_io_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
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
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```

```json
{
  "name": "acpi_hw_validate_io_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589236432,
      "name": "acpi_hw_validate_io_request",
      "external": false,
      "loc": "drivers/acpi/acpica/hwvalid.c:90",
      "file": "drivers/acpi/acpica/hwvalid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_block",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589236432,
      "name": "acpi_hw_validate_io_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 709
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
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```

```json
{
  "name": "acpi_hw_validate_io_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589542944,
      "name": "acpi_hw_validate_io_request",
      "external": false,
      "loc": "drivers/acpi/acpica/hwvalid.c:90",
      "file": "drivers/acpi/acpica/hwvalid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_block",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589542944,
      "name": "acpi_hw_validate_io_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 709
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
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```

```json
{
  "name": "acpi_hw_validate_io_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497541396,
      "name": "acpi_hw_validate_io_request",
      "external": false,
      "loc": "drivers/acpi/acpica/hwvalid.c:90",
      "file": "drivers/acpi/acpica/hwvalid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497541396,
      "name": "acpi_hw_validate_io_request",
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
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```

```json
{
  "name": "acpi_hw_validate_io_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585076549,
      "name": "acpi_hw_validate_io_request",
      "external": false,
      "loc": "drivers/acpi/acpica/hwvalid.c:90",
      "file": "drivers/acpi/acpica/hwvalid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585076549,
      "name": "acpi_hw_validate_io_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```

```json
{
  "name": "acpi_hw_validate_io_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584991980,
      "name": "acpi_hw_validate_io_request",
      "external": false,
      "loc": "drivers/acpi/acpica/hwvalid.c:90",
      "file": "drivers/acpi/acpica/hwvalid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584991980,
      "name": "acpi_hw_validate_io_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```

```json
{
  "name": "acpi_hw_validate_io_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585154873,
      "name": "acpi_hw_validate_io_request",
      "external": false,
      "loc": "drivers/acpi/acpica/hwvalid.c:90",
      "file": "drivers/acpi/acpica/hwvalid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585154873,
      "name": "acpi_hw_validate_io_request",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```

```json
{
  "name": "acpi_hw_validate_io_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585261033,
      "name": "acpi_hw_validate_io_request",
      "external": false,
      "loc": "drivers/acpi/acpica/hwvalid.c:90",
      "file": "drivers/acpi/acpica/hwvalid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port",
        "drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585261033,
      "name": "acpi_hw_validate_io_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width)
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
