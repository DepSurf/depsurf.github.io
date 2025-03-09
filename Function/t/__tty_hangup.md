# Function: <code>__tty_hangup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __tty_hangup(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583961872,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:679",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:do_tty_hangup",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:tty_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583961872,
      "name": "__tty_hangup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1032
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
void __tty_hangup(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584294672,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:686",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584294672,
      "name": "__tty_hangup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1088
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
void __tty_hangup(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584476736,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:686",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584476736,
      "name": "__tty_hangup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1088
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
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584562810,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:551",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584560896,
      "name": "__tty_hangup.part.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584973674,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:563",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584971696,
      "name": "__tty_hangup.part.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 661
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585209583,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:563",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585206224,
      "name": "__tty_hangup.part.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585327716,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:564",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585323888,
      "name": "__tty_hangup.part.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585540207,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:566",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585535808,
      "name": "__tty_hangup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 674
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585681119,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:566",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585676688,
      "name": "__tty_hangup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 674
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
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586407753,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:567",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586404896,
      "name": "__tty_hangup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 850
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586525004,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:565",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586521024,
      "name": "__tty_hangup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 850
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586410299,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:587",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586406672,
      "name": "__tty_hangup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 850
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586937108,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:586",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586933456,
      "name": "__tty_hangup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 850
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588228492,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:584",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588225312,
      "name": "__tty_hangup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 871
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589639120,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:578",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589635712,
      "name": "__tty_hangup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 884
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589942530,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:579",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589939344,
      "name": "__tty_hangup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 893
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590280928,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:577",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590278224,
      "name": "__tty_hangup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 893
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498356884,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:566",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498352736,
      "name": "__tty_hangup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1060
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231043396,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:566",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231039016,
      "name": "__tty_hangup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291539292,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:566",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291535056,
      "name": "__tty_hangup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276035030,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:566",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276031988,
      "name": "__tty_hangup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585442143,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:566",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585437712,
      "name": "__tty_hangup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 674
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585312175,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:566",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585307760,
      "name": "__tty_hangup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585631519,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:566",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585627088,
      "name": "__tty_hangup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 674
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tty_hangup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585737050,
      "name": "__tty_hangup",
      "external": false,
      "loc": "drivers/tty/tty_io.c:566",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_session",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:do_tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585734640,
      "name": "__tty_hangup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 661
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void __tty_hangup(struct tty_struct * tty, int exit_session)
```
</details>
</li>
</ul>
