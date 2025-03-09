# Function: <code>fintek_8250_enter_key</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fintek_8250_enter_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584465227,
      "name": "fintek_8250_enter_key",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:52",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config"
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
  "name": "fintek_8250_enter_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584647445,
      "name": "fintek_8250_enter_key",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:103",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config"
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
  "name": "fintek_8250_enter_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584730496,
      "name": "fintek_8250_enter_key",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:116",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int fintek_8250_enter_key(u16 base_port, u8 key)
```

```json
{
  "name": "fintek_8250_enter_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585144480,
      "name": "fintek_8250_enter_key",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:122",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585144480,
      "name": "fintek_8250_enter_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int fintek_8250_enter_key(u16 base_port, u8 key)
```

```json
{
  "name": "fintek_8250_enter_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585378656,
      "name": "fintek_8250_enter_key",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:122",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585378656,
      "name": "fintek_8250_enter_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int fintek_8250_enter_key(u16 base_port, u8 key)
```

```json
{
  "name": "fintek_8250_enter_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585502096,
      "name": "fintek_8250_enter_key",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:122",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585502096,
      "name": "fintek_8250_enter_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int fintek_8250_enter_key(u16 base_port, u8 key)
```

```json
{
  "name": "fintek_8250_enter_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585720400,
      "name": "fintek_8250_enter_key",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:122",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585720400,
      "name": "fintek_8250_enter_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int fintek_8250_enter_key(u16 base_port, u8 key)
```

```json
{
  "name": "fintek_8250_enter_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585861760,
      "name": "fintek_8250_enter_key",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:122",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585861760,
      "name": "fintek_8250_enter_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fintek_8250_enter_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586596525,
      "name": "fintek_8250_enter_key",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:123",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fintek_8250_enter_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586706893,
      "name": "fintek_8250_enter_key",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:123",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fintek_8250_enter_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586590477,
      "name": "fintek_8250_enter_key",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:123",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fintek_8250_enter_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587131697,
      "name": "fintek_8250_enter_key",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:123",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fintek_8250_enter_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588440775,
      "name": "fintek_8250_enter_key",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:123",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fintek_8250_enter_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589869815,
      "name": "fintek_8250_enter_key",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:123",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fintek_8250_enter_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590178647,
      "name": "fintek_8250_enter_key",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:123",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fintek_8250_enter_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590518807,
      "name": "fintek_8250_enter_key",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:123",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int fintek_8250_enter_key(u16 base_port, u8 key)
```

```json
{
  "name": "fintek_8250_enter_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498595232,
      "name": "fintek_8250_enter_key",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:122",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498595232,
      "name": "fintek_8250_enter_key",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int fintek_8250_enter_key(u16 base_port, u8 key)
```

```json
{
  "name": "fintek_8250_enter_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276192820,
      "name": "fintek_8250_enter_key",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:122",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276192820,
      "name": "fintek_8250_enter_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int fintek_8250_enter_key(u16 base_port, u8 key)
```

```json
{
  "name": "fintek_8250_enter_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585622768,
      "name": "fintek_8250_enter_key",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:122",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585622768,
      "name": "fintek_8250_enter_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int fintek_8250_enter_key(u16 base_port, u8 key)
```

```json
{
  "name": "fintek_8250_enter_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585487824,
      "name": "fintek_8250_enter_key",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:122",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585487824,
      "name": "fintek_8250_enter_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int fintek_8250_enter_key(u16 base_port, u8 key)
```

```json
{
  "name": "fintek_8250_enter_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585812160,
      "name": "fintek_8250_enter_key",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:122",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585812160,
      "name": "fintek_8250_enter_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int fintek_8250_enter_key(u16 base_port, u8 key)
```

```json
{
  "name": "fintek_8250_enter_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585919776,
      "name": "fintek_8250_enter_key",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:122",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585919776,
      "name": "fintek_8250_enter_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int fintek_8250_enter_key(u16 base_port, u8 key)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int fintek_8250_enter_key(u16 base_port, u8 key)
```
</details>
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
int fintek_8250_enter_key(u16 base_port, u8 key)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int fintek_8250_enter_key(u16 base_port, u8 key)
```
</details>
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
