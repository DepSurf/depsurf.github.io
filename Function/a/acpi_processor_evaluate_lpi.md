# Function: <code>acpi_processor_evaluate_lpi</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int acpi_processor_evaluate_lpi(acpi_handle handle, struct acpi_lpi_states_array * info)
```

```json
{
  "name": "acpi_processor_evaluate_lpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584070487,
      "name": "acpi_processor_evaluate_lpi",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:951",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584070487,
      "name": "acpi_processor_evaluate_lpi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 726
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
int acpi_processor_evaluate_lpi(acpi_handle handle, struct acpi_lpi_states_array * info)
```

```json
{
  "name": "acpi_processor_evaluate_lpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584213035,
      "name": "acpi_processor_evaluate_lpi",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:952",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584213035,
      "name": "acpi_processor_evaluate_lpi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 726
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
  "name": "acpi_processor_evaluate_lpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584283776,
      "name": "acpi_processor_evaluate_lpi",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:952",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584283776,
      "name": "acpi_processor_evaluate_lpi.isra.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 823
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
  "name": "acpi_processor_evaluate_lpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584680208,
      "name": "acpi_processor_evaluate_lpi",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:961",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584680208,
      "name": "acpi_processor_evaluate_lpi.isra.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 896
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
  "name": "acpi_processor_evaluate_lpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584906416,
      "name": "acpi_processor_evaluate_lpi",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:965",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584906416,
      "name": "acpi_processor_evaluate_lpi.isra.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 920
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
  "name": "acpi_processor_evaluate_lpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585010288,
      "name": "acpi_processor_evaluate_lpi",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:966",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585010288,
      "name": "acpi_processor_evaluate_lpi.isra.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 920
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
  "name": "acpi_processor_evaluate_lpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585213920,
      "name": "acpi_processor_evaluate_lpi",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:961",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585213920,
      "name": "acpi_processor_evaluate_lpi.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 914
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
  "name": "acpi_processor_evaluate_lpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585350368,
      "name": "acpi_processor_evaluate_lpi",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:961",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585350368,
      "name": "acpi_processor_evaluate_lpi.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 914
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
int acpi_processor_evaluate_lpi(acpi_handle handle, struct acpi_lpi_states_array * info)
```

```json
{
  "name": "acpi_processor_evaluate_lpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586059104,
      "name": "acpi_processor_evaluate_lpi",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:821",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586059104,
      "name": "acpi_processor_evaluate_lpi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
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
int acpi_processor_evaluate_lpi(acpi_handle handle, struct acpi_lpi_states_array * info)
```

```json
{
  "name": "acpi_processor_evaluate_lpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586181312,
      "name": "acpi_processor_evaluate_lpi",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:841",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586181312,
      "name": "acpi_processor_evaluate_lpi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
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
int acpi_processor_evaluate_lpi(acpi_handle handle, struct acpi_lpi_states_array * info)
```

```json
{
  "name": "acpi_processor_evaluate_lpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586057328,
      "name": "acpi_processor_evaluate_lpi",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:875",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586057328,
      "name": "acpi_processor_evaluate_lpi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 874
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
int acpi_processor_evaluate_lpi(acpi_handle handle, struct acpi_lpi_states_array * info)
```

```json
{
  "name": "acpi_processor_evaluate_lpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586549632,
      "name": "acpi_processor_evaluate_lpi",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:876",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586549632,
      "name": "acpi_processor_evaluate_lpi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 859
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
int acpi_processor_evaluate_lpi(acpi_handle handle, struct acpi_lpi_states_array * info)
```

```json
{
  "name": "acpi_processor_evaluate_lpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587808944,
      "name": "acpi_processor_evaluate_lpi",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:880",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587808944,
      "name": "acpi_processor_evaluate_lpi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 854
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
int acpi_processor_evaluate_lpi(acpi_handle handle, struct acpi_lpi_states_array * info)
```

```json
{
  "name": "acpi_processor_evaluate_lpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589150544,
      "name": "acpi_processor_evaluate_lpi",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:896",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589150544,
      "name": "acpi_processor_evaluate_lpi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 838
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
int acpi_processor_evaluate_lpi(acpi_handle handle, struct acpi_lpi_states_array * info)
```

```json
{
  "name": "acpi_processor_evaluate_lpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589443200,
      "name": "acpi_processor_evaluate_lpi",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:896",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589443200,
      "name": "acpi_processor_evaluate_lpi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 935
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
int acpi_processor_evaluate_lpi(acpi_handle handle, struct acpi_lpi_states_array * info)
```

```json
{
  "name": "acpi_processor_evaluate_lpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589751152,
      "name": "acpi_processor_evaluate_lpi",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:896",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589751152,
      "name": "acpi_processor_evaluate_lpi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 935
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
  "name": "acpi_processor_evaluate_lpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497636816,
      "name": "acpi_processor_evaluate_lpi",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:961",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497636816,
      "name": "acpi_processor_evaluate_lpi.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 892
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_processor_evaluate_lpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585152560,
      "name": "acpi_processor_evaluate_lpi",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:961",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585152560,
      "name": "acpi_processor_evaluate_lpi.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 846
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
  "name": "acpi_processor_evaluate_lpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585066720,
      "name": "acpi_processor_evaluate_lpi",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:961",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585066720,
      "name": "acpi_processor_evaluate_lpi.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 846
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
  "name": "acpi_processor_evaluate_lpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585301952,
      "name": "acpi_processor_evaluate_lpi",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:961",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585301952,
      "name": "acpi_processor_evaluate_lpi.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 914
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
  "name": "acpi_processor_evaluate_lpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585408112,
      "name": "acpi_processor_evaluate_lpi",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:961",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585408112,
      "name": "acpi_processor_evaluate_lpi.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 914
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
int acpi_processor_evaluate_lpi(acpi_handle handle, struct acpi_lpi_states_array * info)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int acpi_processor_evaluate_lpi(acpi_handle handle, struct acpi_lpi_states_array * info)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int acpi_processor_evaluate_lpi(acpi_handle handle, struct acpi_lpi_states_array * info)
```
</details>
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
