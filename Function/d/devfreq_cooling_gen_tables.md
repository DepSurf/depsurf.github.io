# Function: <code>devfreq_cooling_gen_tables</code>

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
  "name": "devfreq_cooling_gen_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586865773,
      "name": "devfreq_cooling_gen_tables",
      "external": false,
      "loc": "drivers/thermal/devfreq_cooling.c:419",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
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
  "name": "devfreq_cooling_gen_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587159277,
      "name": "devfreq_cooling_gen_tables",
      "external": false,
      "loc": "drivers/thermal/devfreq_cooling.c:419",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
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
  "name": "devfreq_cooling_gen_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587339197,
      "name": "devfreq_cooling_gen_tables",
      "external": false,
      "loc": "drivers/thermal/devfreq_cooling.c:419",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
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
  "name": "devfreq_cooling_gen_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587609958,
      "name": "devfreq_cooling_gen_tables",
      "external": false,
      "loc": "drivers/thermal/devfreq_cooling.c:419",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
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
  "name": "devfreq_cooling_gen_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587813494,
      "name": "devfreq_cooling_gen_tables",
      "external": false,
      "loc": "drivers/thermal/devfreq_cooling.c:419",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
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
int devfreq_cooling_gen_tables(struct devfreq_cooling_device * dfc)
```

```json
{
  "name": "devfreq_cooling_gen_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588659360,
      "name": "devfreq_cooling_gen_tables",
      "external": false,
      "loc": "drivers/thermal/devfreq_cooling.c:385",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588659360,
      "name": "devfreq_cooling_gen_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 830
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
int devfreq_cooling_gen_tables(struct devfreq_cooling_device * dfc, int num_opps)
```

```json
{
  "name": "devfreq_cooling_gen_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588686336,
      "name": "devfreq_cooling_gen_tables",
      "external": false,
      "loc": "drivers/thermal/devfreq_cooling.c:315",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588686336,
      "name": "devfreq_cooling_gen_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
int devfreq_cooling_gen_tables(struct devfreq_cooling_device * dfc, int num_opps)
```

```json
{
  "name": "devfreq_cooling_gen_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588569088,
      "name": "devfreq_cooling_gen_tables",
      "external": false,
      "loc": "drivers/thermal/devfreq_cooling.c:310",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588569088,
      "name": "devfreq_cooling_gen_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
int devfreq_cooling_gen_tables(struct devfreq_cooling_device * dfc, int num_opps)
```

```json
{
  "name": "devfreq_cooling_gen_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589243408,
      "name": "devfreq_cooling_gen_tables",
      "external": false,
      "loc": "drivers/thermal/devfreq_cooling.c:310",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589243408,
      "name": "devfreq_cooling_gen_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
int devfreq_cooling_gen_tables(struct devfreq_cooling_device * dfc, int num_opps)
```

```json
{
  "name": "devfreq_cooling_gen_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590709296,
      "name": "devfreq_cooling_gen_tables",
      "external": false,
      "loc": "drivers/thermal/devfreq_cooling.c:321",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590709296,
      "name": "devfreq_cooling_gen_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int devfreq_cooling_gen_tables(struct devfreq_cooling_device * dfc, int num_opps)
```

```json
{
  "name": "devfreq_cooling_gen_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592380368,
      "name": "devfreq_cooling_gen_tables",
      "external": false,
      "loc": "drivers/thermal/devfreq_cooling.c:317",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592380368,
      "name": "devfreq_cooling_gen_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int devfreq_cooling_gen_tables(struct devfreq_cooling_device * dfc, int num_opps)
```

```json
{
  "name": "devfreq_cooling_gen_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592808336,
      "name": "devfreq_cooling_gen_tables",
      "external": false,
      "loc": "drivers/thermal/devfreq_cooling.c:317",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592808336,
      "name": "devfreq_cooling_gen_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int devfreq_cooling_gen_tables(struct devfreq_cooling_device * dfc, int num_opps)
```

```json
{
  "name": "devfreq_cooling_gen_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593557216,
      "name": "devfreq_cooling_gen_tables",
      "external": false,
      "loc": "drivers/thermal/devfreq_cooling.c:317",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593557216,
      "name": "devfreq_cooling_gen_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
  "name": "devfreq_cooling_gen_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501023072,
      "name": "devfreq_cooling_gen_tables",
      "external": false,
      "loc": "drivers/thermal/devfreq_cooling.c:419",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
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
  "name": "devfreq_cooling_gen_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233535696,
      "name": "devfreq_cooling_gen_tables",
      "external": false,
      "loc": "drivers/thermal/devfreq_cooling.c:419",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
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
  "name": "devfreq_cooling_gen_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294507448,
      "name": "devfreq_cooling_gen_tables",
      "external": false,
      "loc": "drivers/thermal/devfreq_cooling.c:419",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
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
  "name": "devfreq_cooling_gen_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277767184,
      "name": "devfreq_cooling_gen_tables",
      "external": false,
      "loc": "drivers/thermal/devfreq_cooling.c:419",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
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
  "name": "devfreq_cooling_gen_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587444470,
      "name": "devfreq_cooling_gen_tables",
      "external": false,
      "loc": "drivers/thermal/devfreq_cooling.c:419",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
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
  "name": "devfreq_cooling_gen_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587212678,
      "name": "devfreq_cooling_gen_tables",
      "external": false,
      "loc": "drivers/thermal/devfreq_cooling.c:419",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
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
  "name": "devfreq_cooling_gen_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587769638,
      "name": "devfreq_cooling_gen_tables",
      "external": false,
      "loc": "drivers/thermal/devfreq_cooling.c:419",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
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
  "name": "devfreq_cooling_gen_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587882982,
      "name": "devfreq_cooling_gen_tables",
      "external": false,
      "loc": "drivers/thermal/devfreq_cooling.c:419",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
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
int devfreq_cooling_gen_tables(struct devfreq_cooling_device * dfc)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int num_opps</code>
</li>
</ul>
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
