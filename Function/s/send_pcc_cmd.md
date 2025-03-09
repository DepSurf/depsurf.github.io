# Function: <code>send_pcc_cmd</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int send_pcc_cmd(u16 cmd)
```

```json
{
  "name": "send_pcc_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584240420,
      "name": "send_pcc_cmd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:228",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584240420,
      "name": "send_pcc_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int send_pcc_cmd(u16 cmd)
```

```json
{
  "name": "send_pcc_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584316240,
      "name": "send_pcc_cmd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:233",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584316240,
      "name": "send_pcc_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd)
```

```json
{
  "name": "send_pcc_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584715696,
      "name": "send_pcc_cmd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:239",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584715696,
      "name": "send_pcc_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 669
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd)
```

```json
{
  "name": "send_pcc_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "send_pcc_cmd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:235",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584943184,
      "name": "send_pcc_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 623
    },
    {
      "addr": 18446744071584950999,
      "name": "send_pcc_cmd.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd)
```

```json
{
  "name": "send_pcc_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "send_pcc_cmd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:235",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585047168,
      "name": "send_pcc_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 623
    },
    {
      "addr": 18446744071585055367,
      "name": "send_pcc_cmd.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int send_pcc_cmd(int pcc_ss_id, u16 cmd)
```

```json
{
  "name": "send_pcc_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "send_pcc_cmd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:231",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585251408,
      "name": "send_pcc_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 18446744071585259607,
      "name": "send_pcc_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd)
```

```json
{
  "name": "send_pcc_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "send_pcc_cmd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:231",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585389216,
      "name": "send_pcc_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 18446744071585397511,
      "name": "send_pcc_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd)
```

```json
{
  "name": "send_pcc_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "send_pcc_cmd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:231",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586098784,
      "name": "send_pcc_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 18446744071586106207,
      "name": "send_pcc_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd)
```

```json
{
  "name": "send_pcc_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "send_pcc_cmd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:232",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586219456,
      "name": "send_pcc_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 18446744071591441043,
      "name": "send_pcc_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd)
```

```json
{
  "name": "send_pcc_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "send_pcc_cmd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:223",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586094016,
      "name": "send_pcc_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
    },
    {
      "addr": 18446744071591382149,
      "name": "send_pcc_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd)
```

```json
{
  "name": "send_pcc_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "send_pcc_cmd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:223",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586591792,
      "name": "send_pcc_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 725
    },
    {
      "addr": 18446744071592419125,
      "name": "send_pcc_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd)
```

```json
{
  "name": "send_pcc_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "send_pcc_cmd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:236",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/acpi/cppc_acpi.c:cppc_set_enable",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587853184,
      "name": "send_pcc_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 737
    },
    {
      "addr": 18446744071594286841,
      "name": "send_pcc_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd)
```

```json
{
  "name": "send_pcc_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "send_pcc_cmd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:236",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/acpi/cppc_acpi.c:cppc_set_enable",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589196000,
      "name": "send_pcc_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 766
    },
    {
      "addr": 18446744071596222621,
      "name": "send_pcc_cmd.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd)
```

```json
{
  "name": "send_pcc_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "send_pcc_cmd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:236",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/acpi/cppc_acpi.c:cppc_set_enable",
        "drivers/acpi/cppc_acpi.c:cppc_set_auto_sel",
        "drivers/acpi/cppc_acpi.c:cppc_get_auto_sel_caps",
        "drivers/acpi/cppc_acpi.c:cppc_set_epp_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589490160,
      "name": "send_pcc_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 766
    },
    {
      "addr": 18446744071596750367,
      "name": "send_pcc_cmd.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd)
```

```json
{
  "name": "send_pcc_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "send_pcc_cmd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:239",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/acpi/cppc_acpi.c:cppc_set_enable",
        "drivers/acpi/cppc_acpi.c:cppc_set_auto_sel",
        "drivers/acpi/cppc_acpi.c:cppc_get_auto_sel_caps",
        "drivers/acpi/cppc_acpi.c:cppc_set_epp_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589797376,
      "name": "send_pcc_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 766
    },
    {
      "addr": 18446744071597658002,
      "name": "send_pcc_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int send_pcc_cmd(int pcc_ss_id, u16 cmd)
```

```json
{
  "name": "send_pcc_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497662336,
      "name": "send_pcc_cmd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:231",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497662336,
      "name": "send_pcc_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 740
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd)
```

```json
{
  "name": "send_pcc_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "send_pcc_cmd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:231",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585174736,
      "name": "send_pcc_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 18446744071585183031,
      "name": "send_pcc_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd)
```

```json
{
  "name": "send_pcc_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "send_pcc_cmd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:231",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585116432,
      "name": "send_pcc_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 18446744071585124727,
      "name": "send_pcc_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd)
```

```json
{
  "name": "send_pcc_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "send_pcc_cmd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:231",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585339616,
      "name": "send_pcc_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 18446744071585347911,
      "name": "send_pcc_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd)
```

```json
{
  "name": "send_pcc_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "send_pcc_cmd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:231",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585446928,
      "name": "send_pcc_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 18446744071585455219,
      "name": "send_pcc_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int send_pcc_cmd(u16 cmd)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int pcc_ss_id</code>
</li>
<li>
<b>Param reordered. </b>
<code>cmd</code> ➡️ <code>pcc_ss_id, cmd</code>
</li>
</ul>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd)
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
