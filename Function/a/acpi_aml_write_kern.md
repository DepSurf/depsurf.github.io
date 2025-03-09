# Function: <code>acpi_aml_write_kern</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_aml_write_kern",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584724872,
      "name": "acpi_aml_write_kern",
      "external": false,
      "loc": "drivers/acpi/acpi_dbg.c:260",
      "file": "drivers/acpi/acpi_dbg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_dbg.c:acpi_aml_write_log"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_aml_write_kern",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584954087,
      "name": "acpi_aml_write_kern",
      "external": false,
      "loc": "drivers/acpi/acpi_dbg.c:260",
      "file": "drivers/acpi/acpi_dbg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_dbg.c:acpi_aml_write_log"
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
  "name": "acpi_aml_write_kern",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585058455,
      "name": "acpi_aml_write_kern",
      "external": false,
      "loc": "drivers/acpi/acpi_dbg.c:260",
      "file": "drivers/acpi/acpi_dbg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_dbg.c:acpi_aml_write_log"
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
  "name": "acpi_aml_write_kern",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585262678,
      "name": "acpi_aml_write_kern",
      "external": false,
      "loc": "drivers/acpi/acpi_dbg.c:257",
      "file": "drivers/acpi/acpi_dbg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_dbg.c:acpi_aml_write_log"
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
  "name": "acpi_aml_write_kern",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585400582,
      "name": "acpi_aml_write_kern",
      "external": false,
      "loc": "drivers/acpi/acpi_dbg.c:257",
      "file": "drivers/acpi/acpi_dbg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_dbg.c:acpi_aml_write_log"
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
int acpi_aml_write_kern(const char * buf, int len)
```

```json
{
  "name": "acpi_aml_write_kern",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586109872,
      "name": "acpi_aml_write_kern",
      "external": false,
      "loc": "drivers/acpi/acpi_dbg.c:257",
      "file": "drivers/acpi/acpi_dbg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_dbg.c:acpi_aml_write_log",
        "drivers/acpi/acpi_dbg.c:acpi_aml_write_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586109872,
      "name": "acpi_aml_write_kern",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
int acpi_aml_write_kern(const char * buf, int len)
```

```json
{
  "name": "acpi_aml_write_kern",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586230208,
      "name": "acpi_aml_write_kern",
      "external": false,
      "loc": "drivers/acpi/acpi_dbg.c:250",
      "file": "drivers/acpi/acpi_dbg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_dbg.c:acpi_aml_write_log",
        "drivers/acpi/acpi_dbg.c:acpi_aml_write_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586230208,
      "name": "acpi_aml_write_kern",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
  "name": "acpi_aml_write_kern",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586104438,
      "name": "acpi_aml_write_kern",
      "external": false,
      "loc": "drivers/acpi/acpi_dbg.c:250",
      "file": "drivers/acpi/acpi_dbg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_dbg.c:acpi_aml_write_log"
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
  "name": "acpi_aml_write_kern",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586604457,
      "name": "acpi_aml_write_kern",
      "external": false,
      "loc": "drivers/acpi/acpi_dbg.c:250",
      "file": "drivers/acpi/acpi_dbg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_dbg.c:acpi_aml_write_log"
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
  "name": "acpi_aml_write_kern",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587866508,
      "name": "acpi_aml_write_kern",
      "external": false,
      "loc": "drivers/acpi/acpi_dbg.c:250",
      "file": "drivers/acpi/acpi_dbg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_dbg.c:acpi_aml_write_log"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int acpi_aml_write_kern(const char * buf, int len)
```

```json
{
  "name": "acpi_aml_write_kern",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589210176,
      "name": "acpi_aml_write_kern",
      "external": false,
      "loc": "drivers/acpi/acpi_dbg.c:250",
      "file": "drivers/acpi/acpi_dbg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_dbg.c:acpi_aml_write_log",
        "drivers/acpi/acpi_dbg.c:acpi_aml_write_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589210176,
      "name": "acpi_aml_write_kern",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
int acpi_aml_write_kern(const char * buf, int len)
```

```json
{
  "name": "acpi_aml_write_kern",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589506624,
      "name": "acpi_aml_write_kern",
      "external": false,
      "loc": "drivers/acpi/acpi_dbg.c:250",
      "file": "drivers/acpi/acpi_dbg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_dbg.c:acpi_aml_write_log",
        "drivers/acpi/acpi_dbg.c:acpi_aml_write_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589506624,
      "name": "acpi_aml_write_kern",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
int acpi_aml_write_kern(const char * buf, int len)
```

```json
{
  "name": "acpi_aml_write_kern",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589814288,
      "name": "acpi_aml_write_kern",
      "external": false,
      "loc": "drivers/acpi/acpi_dbg.c:250",
      "file": "drivers/acpi/acpi_dbg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_dbg.c:acpi_aml_write_log",
        "drivers/acpi/acpi_dbg.c:acpi_aml_write_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589814288,
      "name": "acpi_aml_write_kern",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_aml_write_kern",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585350982,
      "name": "acpi_aml_write_kern",
      "external": false,
      "loc": "drivers/acpi/acpi_dbg.c:257",
      "file": "drivers/acpi/acpi_dbg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_dbg.c:acpi_aml_write_log"
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
  "name": "acpi_aml_write_kern",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585458278,
      "name": "acpi_aml_write_kern",
      "external": false,
      "loc": "drivers/acpi/acpi_dbg.c:257",
      "file": "drivers/acpi/acpi_dbg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_dbg.c:acpi_aml_write_log"
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
int acpi_aml_write_kern(const char * buf, int len)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int acpi_aml_write_kern(const char * buf, int len)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int acpi_aml_write_kern(const char * buf, int len)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
