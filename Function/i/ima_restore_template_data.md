# Function: <code>ima_restore_template_data</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ima_restore_template_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582966706,
      "name": "ima_restore_template_data",
      "external": false,
      "loc": "security/integrity/ima/ima_template.c:272",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
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
  "name": "ima_restore_template_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583017161,
      "name": "ima_restore_template_data",
      "external": false,
      "loc": "security/integrity/ima/ima_template.c:275",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ima_restore_template_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583182185,
      "name": "ima_restore_template_data",
      "external": false,
      "loc": "security/integrity/ima/ima_template.c:275",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
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
  "name": "ima_restore_template_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583388510,
      "name": "ima_restore_template_data",
      "external": false,
      "loc": "security/integrity/ima/ima_template.c:275",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
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
  "name": "ima_restore_template_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583508286,
      "name": "ima_restore_template_data",
      "external": false,
      "loc": "security/integrity/ima/ima_template.c:276",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
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
  "name": "ima_restore_template_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583695907,
      "name": "ima_restore_template_data",
      "external": false,
      "loc": "security/integrity/ima/ima_template.c:277",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
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
  "name": "ima_restore_template_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583804032,
      "name": "ima_restore_template_data",
      "external": false,
      "loc": "security/integrity/ima/ima_template.c:301",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
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
int ima_restore_template_data(struct ima_template_desc * template_desc, void * template_data, int template_data_size, struct ima_template_entry * * entry)
```

```json
{
  "name": "ima_restore_template_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584197392,
      "name": "ima_restore_template_data",
      "external": false,
      "loc": "security/integrity/ima/ima_template.c:299",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584197392,
      "name": "ima_restore_template_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
int ima_restore_template_data(struct ima_template_desc * template_desc, void * template_data, int template_data_size, struct ima_template_entry * * entry)
```

```json
{
  "name": "ima_restore_template_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584316016,
      "name": "ima_restore_template_data",
      "external": false,
      "loc": "security/integrity/ima/ima_template.c:325",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584316016,
      "name": "ima_restore_template_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
int ima_restore_template_data(struct ima_template_desc * template_desc, void * template_data, int template_data_size, struct ima_template_entry * * entry)
```

```json
{
  "name": "ima_restore_template_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584350304,
      "name": "ima_restore_template_data",
      "external": false,
      "loc": "security/integrity/ima/ima_template.c:325",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584350304,
      "name": "ima_restore_template_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
int ima_restore_template_data(struct ima_template_desc * template_desc, void * template_data, int template_data_size, struct ima_template_entry * * entry)
```

```json
{
  "name": "ima_restore_template_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584741456,
      "name": "ima_restore_template_data",
      "external": false,
      "loc": "security/integrity/ima/ima_template.c:349",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584741456,
      "name": "ima_restore_template_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
int ima_restore_template_data(struct ima_template_desc * template_desc, void * template_data, int template_data_size, struct ima_template_entry * * entry)
```

```json
{
  "name": "ima_restore_template_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585419232,
      "name": "ima_restore_template_data",
      "external": false,
      "loc": "security/integrity/ima/ima_template.c:353",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585419232,
      "name": "ima_restore_template_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
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
int ima_restore_template_data(struct ima_template_desc * template_desc, void * template_data, int template_data_size, struct ima_template_entry * * entry)
```

```json
{
  "name": "ima_restore_template_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586174000,
      "name": "ima_restore_template_data",
      "external": false,
      "loc": "security/integrity/ima/ima_template.c:356",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586174000,
      "name": "ima_restore_template_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
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
int ima_restore_template_data(struct ima_template_desc * template_desc, void * template_data, int template_data_size, struct ima_template_entry * * entry)
```

```json
{
  "name": "ima_restore_template_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586411616,
      "name": "ima_restore_template_data",
      "external": false,
      "loc": "security/integrity/ima/ima_template.c:356",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586411616,
      "name": "ima_restore_template_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
int ima_restore_template_data(struct ima_template_desc * template_desc, void * template_data, int template_data_size, struct ima_template_entry * * entry)
```

```json
{
  "name": "ima_restore_template_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586676560,
      "name": "ima_restore_template_data",
      "external": false,
      "loc": "security/integrity/ima/ima_template.c:356",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586676560,
      "name": "ima_restore_template_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
  "name": "ima_restore_template_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495607620,
      "name": "ima_restore_template_data",
      "external": false,
      "loc": "security/integrity/ima/ima_template.c:301",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ima_restore_template_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228968296,
      "name": "ima_restore_template_data",
      "external": false,
      "loc": "security/integrity/ima/ima_template.c:301",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ima_restore_template_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289722264,
      "name": "ima_restore_template_data",
      "external": false,
      "loc": "security/integrity/ima/ima_template.c:301",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ima_restore_template_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274769390,
      "name": "ima_restore_template_data",
      "external": false,
      "loc": "security/integrity/ima/ima_template.c:301",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ima_restore_template_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583772768,
      "name": "ima_restore_template_data",
      "external": false,
      "loc": "security/integrity/ima/ima_template.c:301",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
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
  "name": "ima_restore_template_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583709824,
      "name": "ima_restore_template_data",
      "external": false,
      "loc": "security/integrity/ima/ima_template.c:301",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
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
  "name": "ima_restore_template_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583756528,
      "name": "ima_restore_template_data",
      "external": false,
      "loc": "security/integrity/ima/ima_template.c:301",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
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
  "name": "ima_restore_template_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583857520,
      "name": "ima_restore_template_data",
      "external": false,
      "loc": "security/integrity/ima/ima_template.c:301",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
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
int ima_restore_template_data(struct ima_template_desc * template_desc, void * template_data, int template_data_size, struct ima_template_entry * * entry)
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
