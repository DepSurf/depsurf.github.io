# Function: <code>__mmc_release_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __mmc_release_bus(struct mmc_host * host)
```

```json
{
  "name": "__mmc_release_bus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585913456,
      "name": "__mmc_release_bus",
      "external": false,
      "loc": "drivers/mmc/core/core.c:1783",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585913456,
      "name": "__mmc_release_bus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void __mmc_release_bus(struct mmc_host * host)
```

```json
{
  "name": "__mmc_release_bus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586313872,
      "name": "__mmc_release_bus",
      "external": false,
      "loc": "drivers/mmc/core/core.c:1799",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586313872,
      "name": "__mmc_release_bus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mmc_release_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586536886,
      "name": "__mmc_release_bus",
      "external": false,
      "loc": "drivers/mmc/core/core.c:1869",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_detach_bus"
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
  "name": "__mmc_release_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586659944,
      "name": "__mmc_release_bus",
      "external": false,
      "loc": "drivers/mmc/core/core.c:1694",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_detach_bus"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __mmc_release_bus(struct mmc_host * host)
```

```json
{
  "name": "__mmc_release_bus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587128608,
      "name": "__mmc_release_bus",
      "external": false,
      "loc": "drivers/mmc/core/core.c:1908",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_detach_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587128608,
      "name": "__mmc_release_bus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __mmc_release_bus(struct mmc_host * host)
```

```json
{
  "name": "__mmc_release_bus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587427104,
      "name": "__mmc_release_bus",
      "external": false,
      "loc": "drivers/mmc/core/core.c:1712",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_detach_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587427104,
      "name": "__mmc_release_bus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __mmc_release_bus(struct mmc_host * host)
```

```json
{
  "name": "__mmc_release_bus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587607952,
      "name": "__mmc_release_bus",
      "external": false,
      "loc": "drivers/mmc/core/core.c:1715",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_detach_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587607952,
      "name": "__mmc_release_bus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void __mmc_release_bus(struct mmc_host * host)
```

```json
{
  "name": "__mmc_release_bus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmc_release_bus",
      "external": false,
      "loc": "drivers/mmc/core/core.c:1397",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_detach_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587887568,
      "name": "__mmc_release_bus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071587904727,
      "name": "__mmc_release_bus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
  "name": "__mmc_release_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588110672,
      "name": "__mmc_release_bus",
      "external": false,
      "loc": "drivers/mmc/core/core.c:1397",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_detach_bus"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mmc_release_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588973204,
      "name": "__mmc_release_bus",
      "external": false,
      "loc": "drivers/mmc/core/core.c:1380",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_detach_bus"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mmc_release_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588985684,
      "name": "__mmc_release_bus",
      "external": false,
      "loc": "drivers/mmc/core/core.c:1380",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_detach_bus"
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__mmc_release_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501362464,
      "name": "__mmc_release_bus",
      "external": false,
      "loc": "drivers/mmc/core/core.c:1397",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_detach_bus"
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
  "name": "__mmc_release_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233853548,
      "name": "__mmc_release_bus",
      "external": false,
      "loc": "drivers/mmc/core/core.c:1397",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_detach_bus"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __mmc_release_bus(struct mmc_host * host)
```

```json
{
  "name": "__mmc_release_bus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294890752,
      "name": "__mmc_release_bus",
      "external": false,
      "loc": "drivers/mmc/core/core.c:1397",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_detach_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294890752,
      "name": "__mmc_release_bus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
  "name": "__mmc_release_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277974720,
      "name": "__mmc_release_bus",
      "external": false,
      "loc": "drivers/mmc/core/core.c:1397",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_detach_bus"
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
  "name": "__mmc_release_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587732240,
      "name": "__mmc_release_bus",
      "external": false,
      "loc": "drivers/mmc/core/core.c:1397",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_detach_bus"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mmc_release_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588065200,
      "name": "__mmc_release_bus",
      "external": false,
      "loc": "drivers/mmc/core/core.c:1397",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_detach_bus"
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
  "name": "__mmc_release_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588182736,
      "name": "__mmc_release_bus",
      "external": false,
      "loc": "drivers/mmc/core/core.c:1397",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_detach_bus"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void __mmc_release_bus(struct mmc_host * host)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void __mmc_release_bus(struct mmc_host * host)
```
</details>
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
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
void __mmc_release_bus(struct mmc_host * host)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void __mmc_release_bus(struct mmc_host * host)
```
</details>
</li>
</ul>
