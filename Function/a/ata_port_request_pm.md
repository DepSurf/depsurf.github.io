# Function: <code>ata_port_request_pm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584910016,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:5309",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584910016,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585272000,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:5501",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585272000,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585471552,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:5543",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585471552,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585555088,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:5629",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585555088,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585986800,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:5660",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585986800,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586235184,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:5676",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586235184,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586375600,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:5680",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586375600,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:5665",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586619280,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071586647149,
      "name": "ata_port_request_pm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586766832,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:5689",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586766832,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587576720,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:4928",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587576720,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587642976,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:4928",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587642976,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587523264,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:4928",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587523264,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588097760,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:4988",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588097760,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589475680,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:4972",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589475680,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591056256,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:4978",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591056256,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591410128,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:5203",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591410128,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591761152,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:5173",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591761152,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499695504,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:5689",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499695504,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232134648,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:5689",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232134648,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293017568,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:5689",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293017568,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276857858,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:5689",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276857858,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586525568,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:5689",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586525568,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586394144,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:5689",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586394144,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586721392,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:5689",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586721392,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
void ata_port_request_pm(struct ata_port * ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async)
```

```json
{
  "name": "ata_port_request_pm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586827568,
      "name": "ata_port_request_pm",
      "external": false,
      "loc": "drivers/ata/libata-core.c:5689",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_sas_port_resume",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_resume",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-core.c:ata_port_pm_poweroff",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586827568,
      "name": "ata_port_request_pm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
