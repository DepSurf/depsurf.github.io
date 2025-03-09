# Function: <code>ghes_estatus_pool_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ghes_estatus_pool_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595243381,
      "name": "ghes_estatus_pool_init",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:193",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ghes_estatus_pool_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595424956,
      "name": "ghes_estatus_pool_init",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:198",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "ghes_estatus_pool_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595676531,
      "name": "ghes_estatus_pool_init",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:198",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "ghes_estatus_pool_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596600626,
      "name": "ghes_estatus_pool_init",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:210",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ghes_estatus_pool_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602930966,
      "name": "ghes_estatus_pool_init",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:166",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "ghes_estatus_pool_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603103984,
      "name": "ghes_estatus_pool_init",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:166",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_init"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int ghes_estatus_pool_init(int num_ghes)
```

```json
{
  "name": "ghes_estatus_pool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585076544,
      "name": "ghes_estatus_pool_init",
      "external": true,
      "loc": "drivers/acpi/apei/ghes.c:161",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/hest.c:acpi_hest_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585076544,
      "name": "ghes_estatus_pool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int ghes_estatus_pool_init(int num_ghes)
```

```json
{
  "name": "ghes_estatus_pool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585280816,
      "name": "ghes_estatus_pool_init",
      "external": true,
      "loc": "drivers/acpi/apei/ghes.c:153",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585280816,
      "name": "ghes_estatus_pool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int ghes_estatus_pool_init(int num_ghes)
```

```json
{
  "name": "ghes_estatus_pool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585418752,
      "name": "ghes_estatus_pool_init",
      "external": true,
      "loc": "drivers/acpi/apei/ghes.c:153",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585418752,
      "name": "ghes_estatus_pool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int ghes_estatus_pool_init(int num_ghes)
```

```json
{
  "name": "ghes_estatus_pool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586128864,
      "name": "ghes_estatus_pool_init",
      "external": true,
      "loc": "drivers/acpi/apei/ghes.c:154",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586128864,
      "name": "ghes_estatus_pool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int ghes_estatus_pool_init(int num_ghes)
```

```json
{
  "name": "ghes_estatus_pool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586248608,
      "name": "ghes_estatus_pool_init",
      "external": true,
      "loc": "drivers/acpi/apei/ghes.c:166",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586248608,
      "name": "ghes_estatus_pool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int ghes_estatus_pool_init(int num_ghes)
```

```json
{
  "name": "ghes_estatus_pool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586123888,
      "name": "ghes_estatus_pool_init",
      "external": true,
      "loc": "drivers/acpi/apei/ghes.c:166",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586123888,
      "name": "ghes_estatus_pool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int ghes_estatus_pool_init(int num_ghes)
```

```json
{
  "name": "ghes_estatus_pool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586623872,
      "name": "ghes_estatus_pool_init",
      "external": true,
      "loc": "drivers/acpi/apei/ghes.c:166",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586623872,
      "name": "ghes_estatus_pool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int ghes_estatus_pool_init(int num_ghes)
```

```json
{
  "name": "ghes_estatus_pool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587888512,
      "name": "ghes_estatus_pool_init",
      "external": true,
      "loc": "drivers/acpi/apei/ghes.c:166",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587888512,
      "name": "ghes_estatus_pool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int ghes_estatus_pool_init(unsigned int num_ghes)
```

```json
{
  "name": "ghes_estatus_pool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589237136,
      "name": "ghes_estatus_pool_init",
      "external": true,
      "loc": "drivers/acpi/apei/ghes.c:182",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589237136,
      "name": "ghes_estatus_pool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int ghes_estatus_pool_init(unsigned int num_ghes)
```

```json
{
  "name": "ghes_estatus_pool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589533856,
      "name": "ghes_estatus_pool_init",
      "external": true,
      "loc": "drivers/acpi/apei/ghes.c:181",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589533856,
      "name": "ghes_estatus_pool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int ghes_estatus_pool_init(unsigned int num_ghes)
```

```json
{
  "name": "ghes_estatus_pool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589842192,
      "name": "ghes_estatus_pool_init",
      "external": true,
      "loc": "drivers/acpi/apei/ghes.c:195",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589842192,
      "name": "ghes_estatus_pool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int ghes_estatus_pool_init(int num_ghes)
```

```json
{
  "name": "ghes_estatus_pool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497695344,
      "name": "ghes_estatus_pool_init",
      "external": true,
      "loc": "drivers/acpi/apei/ghes.c:153",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/hest.c:acpi_hest_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497695344,
      "name": "ghes_estatus_pool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int ghes_estatus_pool_init(int num_ghes)
```

```json
{
  "name": "ghes_estatus_pool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585369152,
      "name": "ghes_estatus_pool_init",
      "external": true,
      "loc": "drivers/acpi/apei/ghes.c:153",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585369152,
      "name": "ghes_estatus_pool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int ghes_estatus_pool_init(int num_ghes)
```

```json
{
  "name": "ghes_estatus_pool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585476496,
      "name": "ghes_estatus_pool_init",
      "external": true,
      "loc": "drivers/acpi/apei/ghes.c:153",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585476496,
      "name": "ghes_estatus_pool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int ghes_estatus_pool_init(int num_ghes)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int num_ghes</code> ➡️ <code>unsigned int num_ghes</code>
</li>
</ul>
</details>
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
int ghes_estatus_pool_init(int num_ghes)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int ghes_estatus_pool_init(int num_ghes)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int ghes_estatus_pool_init(int num_ghes)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int ghes_estatus_pool_init(int num_ghes)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int ghes_estatus_pool_init(int num_ghes)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
