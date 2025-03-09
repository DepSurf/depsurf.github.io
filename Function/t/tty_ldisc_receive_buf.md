# Function: <code>tty_ldisc_receive_buf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584029268,
      "name": "tty_ldisc_receive_buf",
      "external": false,
      "loc": "include/linux/tty.h:590",
      "file": "drivers/tty/vt/selection.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/selection.c:paste_selection"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int tty_ldisc_receive_buf(struct tty_ldisc * ld, unsigned char * p, char * f, int count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584331040,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:425",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_buffer.c:flush_to_ldisc",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584331040,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int tty_ldisc_receive_buf(struct tty_ldisc * ld, unsigned char * p, char * f, int count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584512960,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:425",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_buffer.c:flush_to_ldisc",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584512960,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int tty_ldisc_receive_buf(struct tty_ldisc * ld, const unsigned char * p, char * f, int count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584592240,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:451",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584592240,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int tty_ldisc_receive_buf(struct tty_ldisc * ld, const unsigned char * p, char * f, int count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585004400,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:452",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585004400,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int tty_ldisc_receive_buf(struct tty_ldisc * ld, const unsigned char * p, char * f, int count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585238512,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:452",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585238512,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int tty_ldisc_receive_buf(struct tty_ldisc * ld, const unsigned char * p, char * f, int count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585357824,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:457",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585357824,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int tty_ldisc_receive_buf(struct tty_ldisc * ld, const unsigned char * p, char * f, int count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585571344,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:457",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585571344,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int tty_ldisc_receive_buf(struct tty_ldisc * ld, const unsigned char * p, char * f, int count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585712384,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:457",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585712384,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int tty_ldisc_receive_buf(struct tty_ldisc * ld, const unsigned char * p, char * f, int count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586441568,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:457",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586441568,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int tty_ldisc_receive_buf(struct tty_ldisc * ld, const unsigned char * p, char * f, int count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586556080,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:457",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586556080,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int tty_ldisc_receive_buf(struct tty_ldisc * ld, const unsigned char * p, char * f, int count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586441056,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:457",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586441056,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int tty_ldisc_receive_buf(struct tty_ldisc * ld, const unsigned char * p, const char * f, int count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586967264,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:467",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586967264,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int tty_ldisc_receive_buf(struct tty_ldisc * ld, const unsigned char * p, const char * f, int count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588262784,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:448",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588262784,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int tty_ldisc_receive_buf(struct tty_ldisc * ld, const unsigned char * p, const char * f, int count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589676448,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:453",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589676448,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int tty_ldisc_receive_buf(struct tty_ldisc * ld, const unsigned char * p, const char * f, int count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589981056,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:453",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589981056,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
size_t tty_ldisc_receive_buf(struct tty_ldisc * ld, const u8 * p, const u8 * f, size_t count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590319776,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:382",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590319776,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int tty_ldisc_receive_buf(struct tty_ldisc * ld, const unsigned char * p, char * f, int count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498401136,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:457",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498401136,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int tty_ldisc_receive_buf(struct tty_ldisc * ld, const unsigned char * p, char * f, int count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231075820,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:457",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231075820,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int tty_ldisc_receive_buf(struct tty_ldisc * ld, const unsigned char * p, char * f, int count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291584560,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:457",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291584560,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int tty_ldisc_receive_buf(struct tty_ldisc * ld, const unsigned char * p, char * f, int count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276061946,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:457",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276061946,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int tty_ldisc_receive_buf(struct tty_ldisc * ld, const unsigned char * p, char * f, int count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585473408,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:457",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585473408,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int tty_ldisc_receive_buf(struct tty_ldisc * ld, const unsigned char * p, char * f, int count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585343424,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:457",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585343424,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int tty_ldisc_receive_buf(struct tty_ldisc * ld, const unsigned char * p, char * f, int count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585662784,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:457",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585662784,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int tty_ldisc_receive_buf(struct tty_ldisc * ld, const unsigned char * p, char * f, int count)
```

```json
{
  "name": "tty_ldisc_receive_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585770896,
      "name": "tty_ldisc_receive_buf",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:457",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585770896,
      "name": "tty_ldisc_receive_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int tty_ldisc_receive_buf(struct tty_ldisc * ld, unsigned char * p, char * f, int count)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned char * p</code> ➡️ <code>const unsigned char * p</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char * f</code> ➡️ <code>const char * f</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const unsigned char * p</code> ➡️ <code>const u8 * p</code>
</li>
<li>
<b>Param type changed. </b>
<code>const char * f</code> ➡️ <code>const u8 * f</code>
</li>
<li>
<b>Param type changed. </b>
<code>int count</code> ➡️ <code>size_t count</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>size_t</code>
</li>
</ul>
</details>
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
