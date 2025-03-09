# Function: <code>acpi_processor_set_throttling</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```

```json
{
  "name": "acpi_processor_set_throttling",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583751295,
      "name": "acpi_processor_set_throttling",
      "external": true,
      "loc": "drivers/acpi/processor_throttling.c:1074",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed",
        "drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583751295,
      "name": "acpi_processor_set_throttling",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 581
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
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```

```json
{
  "name": "acpi_processor_set_throttling",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584077395,
      "name": "acpi_processor_set_throttling",
      "external": true,
      "loc": "drivers/acpi/processor_throttling.c:1083",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc",
        "drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584077395,
      "name": "acpi_processor_set_throttling",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
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
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```

```json
{
  "name": "acpi_processor_set_throttling",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584219979,
      "name": "acpi_processor_set_throttling",
      "external": true,
      "loc": "drivers/acpi/processor_throttling.c:1083",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc",
        "drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584219979,
      "name": "acpi_processor_set_throttling",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```

```json
{
  "name": "acpi_processor_set_throttling",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584293455,
      "name": "acpi_processor_set_throttling",
      "external": true,
      "loc": "drivers/acpi/processor_throttling.c:1189",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584292400,
      "name": "acpi_processor_set_throttling",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```

```json
{
  "name": "acpi_processor_set_throttling",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584692424,
      "name": "acpi_processor_set_throttling",
      "external": true,
      "loc": "drivers/acpi/processor_throttling.c:1189",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584690576,
      "name": "acpi_processor_set_throttling",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```

```json
{
  "name": "acpi_processor_set_throttling",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584918314,
      "name": "acpi_processor_set_throttling",
      "external": true,
      "loc": "drivers/acpi/processor_throttling.c:1190",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584916864,
      "name": "acpi_processor_set_throttling",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```

```json
{
  "name": "acpi_processor_set_throttling",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585022218,
      "name": "acpi_processor_set_throttling",
      "external": true,
      "loc": "drivers/acpi/processor_throttling.c:1190",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585020768,
      "name": "acpi_processor_set_throttling",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```

```json
{
  "name": "acpi_processor_set_throttling",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585225757,
      "name": "acpi_processor_set_throttling",
      "external": true,
      "loc": "drivers/acpi/processor_throttling.c:1177",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585224496,
      "name": "acpi_processor_set_throttling",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```

```json
{
  "name": "acpi_processor_set_throttling",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585362189,
      "name": "acpi_processor_set_throttling",
      "external": true,
      "loc": "drivers/acpi/processor_throttling.c:1177",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585360928,
      "name": "acpi_processor_set_throttling",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```

```json
{
  "name": "acpi_processor_set_throttling",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586070414,
      "name": "acpi_processor_set_throttling",
      "external": true,
      "loc": "drivers/acpi/processor_throttling.c:1170",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586070080,
      "name": "acpi_processor_set_throttling",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```

```json
{
  "name": "acpi_processor_set_throttling",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586192350,
      "name": "acpi_processor_set_throttling",
      "external": true,
      "loc": "drivers/acpi/processor_throttling.c:1169",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586192016,
      "name": "acpi_processor_set_throttling",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```

```json
{
  "name": "acpi_processor_set_throttling",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586067718,
      "name": "acpi_processor_set_throttling",
      "external": true,
      "loc": "drivers/acpi/processor_throttling.c:1165",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586067168,
      "name": "acpi_processor_set_throttling",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```

```json
{
  "name": "acpi_processor_set_throttling",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586561915,
      "name": "acpi_processor_set_throttling",
      "external": true,
      "loc": "drivers/acpi/processor_throttling.c:1155",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586561328,
      "name": "acpi_processor_set_throttling",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```

```json
{
  "name": "acpi_processor_set_throttling",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587820846,
      "name": "acpi_processor_set_throttling",
      "external": true,
      "loc": "drivers/acpi/processor_throttling.c:1155",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587820448,
      "name": "acpi_processor_set_throttling",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```

```json
{
  "name": "acpi_processor_set_throttling",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589163498,
      "name": "acpi_processor_set_throttling",
      "external": true,
      "loc": "drivers/acpi/processor_throttling.c:1153",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589163088,
      "name": "acpi_processor_set_throttling",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```

```json
{
  "name": "acpi_processor_set_throttling",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589456810,
      "name": "acpi_processor_set_throttling",
      "external": true,
      "loc": "drivers/acpi/processor_throttling.c:1153",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589456400,
      "name": "acpi_processor_set_throttling",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```

```json
{
  "name": "acpi_processor_set_throttling",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589764810,
      "name": "acpi_processor_set_throttling",
      "external": true,
      "loc": "drivers/acpi/processor_throttling.c:1153",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589764400,
      "name": "acpi_processor_set_throttling",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```

```json
{
  "name": "acpi_processor_set_throttling",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585162613,
      "name": "acpi_processor_set_throttling",
      "external": true,
      "loc": "drivers/acpi/processor_throttling.c:1177",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585161392,
      "name": "acpi_processor_set_throttling",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```

```json
{
  "name": "acpi_processor_set_throttling",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585076805,
      "name": "acpi_processor_set_throttling",
      "external": true,
      "loc": "drivers/acpi/processor_throttling.c:1177",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585075584,
      "name": "acpi_processor_set_throttling",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```

```json
{
  "name": "acpi_processor_set_throttling",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585313773,
      "name": "acpi_processor_set_throttling",
      "external": true,
      "loc": "drivers/acpi/processor_throttling.c:1177",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585312512,
      "name": "acpi_processor_set_throttling",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```

```json
{
  "name": "acpi_processor_set_throttling",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585419917,
      "name": "acpi_processor_set_throttling",
      "external": true,
      "loc": "drivers/acpi/processor_throttling.c:1177",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585418656,
      "name": "acpi_processor_set_throttling",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor * pr, int state, bool force)
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
