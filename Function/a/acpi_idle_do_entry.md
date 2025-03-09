# Function: <code>acpi_idle_do_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```

```json
{
  "name": "acpi_idle_do_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583747208,
      "name": "acpi_idle_do_entry",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:683",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_freeze",
        "drivers/acpi/processor_idle.c:acpi_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583747208,
      "name": "acpi_idle_do_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```

```json
{
  "name": "acpi_idle_do_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584072995,
      "name": "acpi_idle_do_entry",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:648",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_freeze",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584072995,
      "name": "acpi_idle_do_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```

```json
{
  "name": "acpi_idle_do_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588102133,
      "name": "acpi_idle_do_entry",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:649",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_freeze",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588102133,
      "name": "acpi_idle_do_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```

```json
{
  "name": "acpi_idle_do_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588327792,
      "name": "acpi_idle_do_entry",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:649",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_freeze",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588327792,
      "name": "acpi_idle_do_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```

```json
{
  "name": "acpi_idle_do_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588893968,
      "name": "acpi_idle_do_entry",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:651",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588893968,
      "name": "acpi_idle_do_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```

```json
{
  "name": "acpi_idle_do_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589272144,
      "name": "acpi_idle_do_entry",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:655",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589272144,
      "name": "acpi_idle_do_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```

```json
{
  "name": "acpi_idle_do_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589515104,
      "name": "acpi_idle_do_entry",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:656",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589515104,
      "name": "acpi_idle_do_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```

```json
{
  "name": "acpi_idle_do_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589974224,
      "name": "acpi_idle_do_entry",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:651",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589974224,
      "name": "acpi_idle_do_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```

```json
{
  "name": "acpi_idle_do_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590201632,
      "name": "acpi_idle_do_entry",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:651",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590201632,
      "name": "acpi_idle_do_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
  "name": "acpi_idle_do_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586062423,
      "name": "acpi_idle_do_entry",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:519",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```

```json
{
  "name": "acpi_idle_do_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591711776,
      "name": "acpi_idle_do_entry",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:511",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591711776,
      "name": "acpi_idle_do_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```

```json
{
  "name": "acpi_idle_do_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591659168,
      "name": "acpi_idle_do_entry",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:547",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591659168,
      "name": "acpi_idle_do_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```

```json
{
  "name": "acpi_idle_do_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592832896,
      "name": "acpi_idle_do_entry",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:547",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592832896,
      "name": "acpi_idle_do_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```

```json
{
  "name": "acpi_idle_do_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594742880,
      "name": "acpi_idle_do_entry",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:546",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594742880,
      "name": "acpi_idle_do_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```

```json
{
  "name": "acpi_idle_do_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596495488,
      "name": "acpi_idle_do_entry",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:562",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596495488,
      "name": "acpi_idle_do_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```

```json
{
  "name": "acpi_idle_do_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596947904,
      "name": "acpi_idle_do_entry",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:565",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596947904,
      "name": "acpi_idle_do_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```

```json
{
  "name": "acpi_idle_do_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597875424,
      "name": "acpi_idle_do_entry",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:565",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597875424,
      "name": "acpi_idle_do_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```

```json
{
  "name": "acpi_idle_do_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589803920,
      "name": "acpi_idle_do_entry",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:651",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589803920,
      "name": "acpi_idle_do_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```

```json
{
  "name": "acpi_idle_do_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589526272,
      "name": "acpi_idle_do_entry",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:651",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589526272,
      "name": "acpi_idle_do_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```

```json
{
  "name": "acpi_idle_do_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590247328,
      "name": "acpi_idle_do_entry",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:651",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590247328,
      "name": "acpi_idle_do_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```

```json
{
  "name": "acpi_idle_do_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590298528,
      "name": "acpi_idle_do_entry",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:651",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590298528,
      "name": "acpi_idle_do_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx * cx)
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
