# Function: <code>acpi_ns_normalize_pathname</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ns_normalize_pathname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584781426,
      "name": "acpi_ns_normalize_pathname",
      "external": false,
      "loc": "drivers/acpi/acpica/nsnames.c:414",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ns_normalize_pathname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584883474,
      "name": "acpi_ns_normalize_pathname",
      "external": false,
      "loc": "drivers/acpi/acpica/nsnames.c:414",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ns_normalize_pathname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585086701,
      "name": "acpi_ns_normalize_pathname",
      "external": false,
      "loc": "drivers/acpi/acpica/nsnames.c:414",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ns_normalize_pathname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585223052,
      "name": "acpi_ns_normalize_pathname",
      "external": false,
      "loc": "drivers/acpi/acpica/nsnames.c:414",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void acpi_ns_normalize_pathname(char * original_path)
```

```json
{
  "name": "acpi_ns_normalize_pathname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585928653,
      "name": "acpi_ns_normalize_pathname",
      "external": true,
      "loc": "drivers/acpi/acpica/nsnames.c:410",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585928653,
      "name": "acpi_ns_normalize_pathname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void acpi_ns_normalize_pathname(char * original_path)
```

```json
{
  "name": "acpi_ns_normalize_pathname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586050357,
      "name": "acpi_ns_normalize_pathname",
      "external": true,
      "loc": "drivers/acpi/acpica/nsnames.c:410",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586050357,
      "name": "acpi_ns_normalize_pathname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void acpi_ns_normalize_pathname(char * original_path)
```

```json
{
  "name": "acpi_ns_normalize_pathname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585927201,
      "name": "acpi_ns_normalize_pathname",
      "external": true,
      "loc": "drivers/acpi/acpica/nsnames.c:410",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585927201,
      "name": "acpi_ns_normalize_pathname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void acpi_ns_normalize_pathname(char * original_path)
```

```json
{
  "name": "acpi_ns_normalize_pathname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586415374,
      "name": "acpi_ns_normalize_pathname",
      "external": true,
      "loc": "drivers/acpi/acpica/nsnames.c:410",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586415374,
      "name": "acpi_ns_normalize_pathname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void acpi_ns_normalize_pathname(char * original_path)
```

```json
{
  "name": "acpi_ns_normalize_pathname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587665560,
      "name": "acpi_ns_normalize_pathname",
      "external": true,
      "loc": "drivers/acpi/acpica/nsnames.c:410",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587665560,
      "name": "acpi_ns_normalize_pathname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void acpi_ns_normalize_pathname(char * original_path)
```

```json
{
  "name": "acpi_ns_normalize_pathname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588971840,
      "name": "acpi_ns_normalize_pathname",
      "external": true,
      "loc": "drivers/acpi/acpica/nsnames.c:410",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588971840,
      "name": "acpi_ns_normalize_pathname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void acpi_ns_normalize_pathname(char * original_path)
```

```json
{
  "name": "acpi_ns_normalize_pathname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589261872,
      "name": "acpi_ns_normalize_pathname",
      "external": true,
      "loc": "drivers/acpi/acpica/nsnames.c:410",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589261872,
      "name": "acpi_ns_normalize_pathname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void acpi_ns_normalize_pathname(char * original_path)
```

```json
{
  "name": "acpi_ns_normalize_pathname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589568544,
      "name": "acpi_ns_normalize_pathname",
      "external": true,
      "loc": "drivers/acpi/acpica/nsnames.c:410",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589568544,
      "name": "acpi_ns_normalize_pathname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
  "name": "acpi_ns_normalize_pathname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497552580,
      "name": "acpi_ns_normalize_pathname",
      "external": false,
      "loc": "drivers/acpi/acpica/nsnames.c:414",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname"
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
  "name": "acpi_ns_normalize_pathname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585086444,
      "name": "acpi_ns_normalize_pathname",
      "external": false,
      "loc": "drivers/acpi/acpica/nsnames.c:414",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ns_normalize_pathname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585001840,
      "name": "acpi_ns_normalize_pathname",
      "external": false,
      "loc": "drivers/acpi/acpica/nsnames.c:414",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ns_normalize_pathname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585174636,
      "name": "acpi_ns_normalize_pathname",
      "external": false,
      "loc": "drivers/acpi/acpica/nsnames.c:414",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ns_normalize_pathname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585280796,
      "name": "acpi_ns_normalize_pathname",
      "external": false,
      "loc": "drivers/acpi/acpica/nsnames.c:414",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void acpi_ns_normalize_pathname(char * original_path)
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
