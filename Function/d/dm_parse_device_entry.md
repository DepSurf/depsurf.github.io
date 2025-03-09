# Function: <code>dm_parse_device_entry</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_parse_device_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605094688,
      "name": "dm_parse_device_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:187",
      "file": "drivers/md/dm-init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-init.c:dm_parse_devices"
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
  "name": "dm_parse_device_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605134117,
      "name": "dm_parse_device_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:187",
      "file": "drivers/md/dm-init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-init.c:dm_parse_devices"
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
char * dm_parse_device_entry(struct dm_device * dev, char * str)
```

```json
{
  "name": "dm_parse_device_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609405256,
      "name": "dm_parse_device_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:187",
      "file": "drivers/md/dm-init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-init.c:dm_parse_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609405256,
      "name": "dm_parse_device_entry",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 387
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
char * dm_parse_device_entry(struct dm_device * dev, char * str)
```

```json
{
  "name": "dm_parse_device_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612478585,
      "name": "dm_parse_device_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:187",
      "file": "drivers/md/dm-init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-init.c:dm_parse_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612478585,
      "name": "dm_parse_device_entry",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 497
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
char * dm_parse_device_entry(struct dm_device * dev, char * str)
```

```json
{
  "name": "dm_parse_device_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614621096,
      "name": "dm_parse_device_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:187",
      "file": "drivers/md/dm-init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-init.c:dm_init_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614621096,
      "name": "dm_parse_device_entry",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 497
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
char * dm_parse_device_entry(struct dm_device * dev, char * str)
```

```json
{
  "name": "dm_parse_device_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615576742,
      "name": "dm_parse_device_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:187",
      "file": "drivers/md/dm-init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-init.c:dm_init_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615576742,
      "name": "dm_parse_device_entry",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 572
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
char * dm_parse_device_entry(struct dm_device * dev, char * str)
```

```json
{
  "name": "dm_parse_device_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617384409,
      "name": "dm_parse_device_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:187",
      "file": "drivers/md/dm-init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-init.c:dm_init_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617384409,
      "name": "dm_parse_device_entry",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 596
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
char * dm_parse_device_entry(struct dm_device * dev, char * str)
```

```json
{
  "name": "dm_parse_device_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071628128496,
      "name": "dm_parse_device_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:193",
      "file": "drivers/md/dm-init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-init.c:dm_init_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628128496,
      "name": "dm_parse_device_entry",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 852
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
char * dm_parse_device_entry(struct dm_device * dev, char * str)
```

```json
{
  "name": "dm_parse_device_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619895152,
      "name": "dm_parse_device_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:192",
      "file": "drivers/md/dm-init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-init.c:dm_init_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619895152,
      "name": "dm_parse_device_entry",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 851
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
char * dm_parse_device_entry(struct dm_device * dev, char * str)
```

```json
{
  "name": "dm_parse_device_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622204976,
      "name": "dm_parse_device_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:192",
      "file": "drivers/md/dm-init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-init.c:dm_init_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622204976,
      "name": "dm_parse_device_entry",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 851
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
  "name": "dm_parse_device_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336511261708,
      "name": "dm_parse_device_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:187",
      "file": "drivers/md/dm-init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-init.c:dm_init_init"
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
  "name": "dm_parse_device_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243913728,
      "name": "dm_parse_device_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:187",
      "file": "drivers/md/dm-init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-init.c:dm_init_init"
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
  "name": "dm_parse_device_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302837748,
      "name": "dm_parse_device_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:187",
      "file": "drivers/md/dm-init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-init.c:dm_parse_devices"
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
  "name": "dm_parse_device_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270829848,
      "name": "dm_parse_device_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:187",
      "file": "drivers/md/dm-init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-init.c:dm_parse_devices"
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
  "name": "dm_parse_device_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605027129,
      "name": "dm_parse_device_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:187",
      "file": "drivers/md/dm-init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-init.c:dm_parse_devices"
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
  "name": "dm_parse_device_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604992587,
      "name": "dm_parse_device_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:187",
      "file": "drivers/md/dm-init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-init.c:dm_parse_devices"
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
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_parse_device_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605138311,
      "name": "dm_parse_device_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:187",
      "file": "drivers/md/dm-init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-init.c:dm_parse_devices"
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
char * dm_parse_device_entry(struct dm_device * dev, char * str)
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
