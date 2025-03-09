# Function: <code>pciserial_detach_ports</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private * priv)
```

```json
{
  "name": "pciserial_detach_ports",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584658048,
      "name": "pciserial_detach_ports",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_pci.c:3920",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584658048,
      "name": "pciserial_detach_ports",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void pciserial_detach_ports(struct serial_private * priv)
```

```json
{
  "name": "pciserial_detach_ports",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584734384,
      "name": "pciserial_detach_ports",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:3559",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584734384,
      "name": "pciserial_detach_ports",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void pciserial_detach_ports(struct serial_private * priv)
```

```json
{
  "name": "pciserial_detach_ports",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585149376,
      "name": "pciserial_detach_ports",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:3572",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585149376,
      "name": "pciserial_detach_ports",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void pciserial_detach_ports(struct serial_private * priv)
```

```json
{
  "name": "pciserial_detach_ports",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585383872,
      "name": "pciserial_detach_ports",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:3567",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585383872,
      "name": "pciserial_detach_ports",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void pciserial_detach_ports(struct serial_private * priv)
```

```json
{
  "name": "pciserial_detach_ports",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585507344,
      "name": "pciserial_detach_ports",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:3677",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585507344,
      "name": "pciserial_detach_ports",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void pciserial_detach_ports(struct serial_private * priv)
```

```json
{
  "name": "pciserial_detach_ports",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585726064,
      "name": "pciserial_detach_ports",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:3769",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585726064,
      "name": "pciserial_detach_ports",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void pciserial_detach_ports(struct serial_private * priv)
```

```json
{
  "name": "pciserial_detach_ports",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585867840,
      "name": "pciserial_detach_ports",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:3957",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585867840,
      "name": "pciserial_detach_ports",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void pciserial_detach_ports(struct serial_private * priv)
```

```json
{
  "name": "pciserial_detach_ports",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586604496,
      "name": "pciserial_detach_ports",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:3949",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586604496,
      "name": "pciserial_detach_ports",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void pciserial_detach_ports(struct serial_private * priv)
```

```json
{
  "name": "pciserial_detach_ports",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586714896,
      "name": "pciserial_detach_ports",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:3992",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586714896,
      "name": "pciserial_detach_ports",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void pciserial_detach_ports(struct serial_private * priv)
```

```json
{
  "name": "pciserial_detach_ports",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586598528,
      "name": "pciserial_detach_ports",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:4018",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586598528,
      "name": "pciserial_detach_ports",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void pciserial_detach_ports(struct serial_private * priv)
```

```json
{
  "name": "pciserial_detach_ports",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587141056,
      "name": "pciserial_detach_ports",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:4061",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587141056,
      "name": "pciserial_detach_ports",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void pciserial_detach_ports(struct serial_private * priv)
```

```json
{
  "name": "pciserial_detach_ports",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588450064,
      "name": "pciserial_detach_ports",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:3945",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588450064,
      "name": "pciserial_detach_ports",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private * priv)
```

```json
{
  "name": "pciserial_detach_ports",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589877888,
      "name": "pciserial_detach_ports",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:3933",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589877888,
      "name": "pciserial_detach_ports",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private * priv)
```

```json
{
  "name": "pciserial_detach_ports",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590186976,
      "name": "pciserial_detach_ports",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:3896",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590186976,
      "name": "pciserial_detach_ports",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private * priv)
```

```json
{
  "name": "pciserial_detach_ports",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590530624,
      "name": "pciserial_detach_ports",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:4152",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590530624,
      "name": "pciserial_detach_ports",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void pciserial_detach_ports(struct serial_private * priv)
```

```json
{
  "name": "pciserial_detach_ports",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498601592,
      "name": "pciserial_detach_ports",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:3957",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498601592,
      "name": "pciserial_detach_ports",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void pciserial_detach_ports(struct serial_private * priv)
```

```json
{
  "name": "pciserial_detach_ports",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231236460,
      "name": "pciserial_detach_ports",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:3957",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231236460,
      "name": "pciserial_detach_ports",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void pciserial_detach_ports(struct serial_private * priv)
```

```json
{
  "name": "pciserial_detach_ports",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291823376,
      "name": "pciserial_detach_ports",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:3957",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291823376,
      "name": "pciserial_detach_ports",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void pciserial_detach_ports(struct serial_private * priv)
```

```json
{
  "name": "pciserial_detach_ports",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276200896,
      "name": "pciserial_detach_ports",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:3957",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276200896,
      "name": "pciserial_detach_ports",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void pciserial_detach_ports(struct serial_private * priv)
```

```json
{
  "name": "pciserial_detach_ports",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585628848,
      "name": "pciserial_detach_ports",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:3957",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585628848,
      "name": "pciserial_detach_ports",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void pciserial_detach_ports(struct serial_private * priv)
```

```json
{
  "name": "pciserial_detach_ports",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585493904,
      "name": "pciserial_detach_ports",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:3957",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585493904,
      "name": "pciserial_detach_ports",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void pciserial_detach_ports(struct serial_private * priv)
```

```json
{
  "name": "pciserial_detach_ports",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585818240,
      "name": "pciserial_detach_ports",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:3957",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585818240,
      "name": "pciserial_detach_ports",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void pciserial_detach_ports(struct serial_private * priv)
```

```json
{
  "name": "pciserial_detach_ports",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585925856,
      "name": "pciserial_detach_ports",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:3957",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585925856,
      "name": "pciserial_detach_ports",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void pciserial_detach_ports(struct serial_private * priv)
```
</details>
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
