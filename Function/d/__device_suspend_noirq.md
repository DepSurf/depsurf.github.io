# Function: <code>__device_suspend_noirq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584452720,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1016",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584452720,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584788928,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1021",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584788928,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
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
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584980944,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1079",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584980944,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585065440,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1087",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585065440,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585487920,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1142",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:async_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585487920,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 631
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
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585732896,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1285",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:async_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585732896,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 793
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
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585865488,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1287",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:async_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585865488,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 790
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
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586102736,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1279",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:async_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586102736,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 774
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
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586250336,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1308",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586250336,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587016000,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1192",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:async_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587016000,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587100624,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1191",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:async_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587100624,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586986928,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1192",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:async_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586986928,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587553120,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1202",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:async_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587553120,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588886592,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1199",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:async_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588886592,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
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
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590395968,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1199",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:async_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590395968,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
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
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590719184,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1199",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:async_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590719184,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
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
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591080560,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1198",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:async_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591080560,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
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
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499070192,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1308",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499070192,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 700
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
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231622948,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1308",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231622948,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
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
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292247232,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1308",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292247232,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 884
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586012880,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1308",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586012880,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 883
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
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585859664,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1308",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585859664,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586200352,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1308",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586200352,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586310256,
      "name": "__device_suspend_noirq",
      "external": false,
      "loc": "drivers/base/power/main.c:1308",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586310256,
      "name": "__device_suspend_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __device_suspend_noirq(struct device * dev, pm_message_t state, bool async)
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
