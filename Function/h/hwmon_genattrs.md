# Function: <code>hwmon_genattrs</code>

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
  "name": "hwmon_genattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586267747,
      "name": "hwmon_genattrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:470",
      "file": "drivers/hwmon/hwmon.c",
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
  "name": "hwmon_genattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586367270,
      "name": "hwmon_genattrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:470",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
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
  "name": "hwmon_genattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586832118,
      "name": "hwmon_genattrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:477",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
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
  "name": "hwmon_genattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587123915,
      "name": "hwmon_genattrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:477",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
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
  "name": "hwmon_genattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587302750,
      "name": "hwmon_genattrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:495",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
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
  "name": "hwmon_genattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587572773,
      "name": "hwmon_genattrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:495",
      "file": "drivers/hwmon/hwmon.c",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hwmon_genattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587776480,
      "name": "hwmon_genattrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:511",
      "file": "drivers/hwmon/hwmon.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int hwmon_genattrs(const void * drvdata, struct attribute * * attrs, const struct hwmon_ops * ops, const struct hwmon_channel_info * info)
```

```json
{
  "name": "hwmon_genattrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588622256,
      "name": "hwmon_genattrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:616",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:__hwmon_create_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588622256,
      "name": "hwmon_genattrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
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
int hwmon_genattrs(const void * drvdata, struct attribute * * attrs, const struct hwmon_ops * ops, const struct hwmon_channel_info * info)
```

```json
{
  "name": "hwmon_genattrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588642336,
      "name": "hwmon_genattrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:626",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:__hwmon_create_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588642336,
      "name": "hwmon_genattrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
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
int hwmon_genattrs(const void * drvdata, struct attribute * * attrs, const struct hwmon_ops * ops, const struct hwmon_channel_info * info)
```

```json
{
  "name": "hwmon_genattrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588526688,
      "name": "hwmon_genattrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:626",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588526688,
      "name": "hwmon_genattrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 670
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
int hwmon_genattrs(const void * drvdata, struct attribute * * attrs, const struct hwmon_ops * ops, const struct hwmon_channel_info * info)
```

```json
{
  "name": "hwmon_genattrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwmon_genattrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:664",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589200528,
      "name": "hwmon_genattrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 749
    },
    {
      "addr": 18446744071592635379,
      "name": "hwmon_genattrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int hwmon_genattrs(const void * drvdata, struct attribute * * attrs, const struct hwmon_ops * ops, const struct hwmon_channel_info * info)
```

```json
{
  "name": "hwmon_genattrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwmon_genattrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:683",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590662016,
      "name": "hwmon_genattrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 760
    },
    {
      "addr": 18446744071594519086,
      "name": "hwmon_genattrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
int hwmon_genattrs(const void * drvdata, struct attribute * * attrs, const struct hwmon_ops * ops, const struct hwmon_channel_info * info)
```

```json
{
  "name": "hwmon_genattrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwmon_genattrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:684",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592329472,
      "name": "hwmon_genattrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 760
    },
    {
      "addr": 18446744071596308934,
      "name": "hwmon_genattrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
int hwmon_genattrs(const void * drvdata, struct attribute * * attrs, const struct hwmon_ops * ops, const struct hwmon_channel_info * info)
```

```json
{
  "name": "hwmon_genattrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwmon_genattrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:688",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592756704,
      "name": "hwmon_genattrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 750
    },
    {
      "addr": 18446744071596838374,
      "name": "hwmon_genattrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hwmon_genattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593505906,
      "name": "hwmon_genattrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:688",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:__hwmon_create_attrs"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "hwmon_genattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500974808,
      "name": "hwmon_genattrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:511",
      "file": "drivers/hwmon/hwmon.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "hwmon_genattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233489472,
      "name": "hwmon_genattrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:511",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:__hwmon_create_attrs"
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
  "name": "hwmon_genattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294443440,
      "name": "hwmon_genattrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:511",
      "file": "drivers/hwmon/hwmon.c",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "hwmon_genattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277733030,
      "name": "hwmon_genattrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:511",
      "file": "drivers/hwmon/hwmon.c",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hwmon_genattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587407456,
      "name": "hwmon_genattrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:511",
      "file": "drivers/hwmon/hwmon.c",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hwmon_genattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587175664,
      "name": "hwmon_genattrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:511",
      "file": "drivers/hwmon/hwmon.c",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hwmon_genattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587732624,
      "name": "hwmon_genattrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:511",
      "file": "drivers/hwmon/hwmon.c",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hwmon_genattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587845776,
      "name": "hwmon_genattrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:511",
      "file": "drivers/hwmon/hwmon.c",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int hwmon_genattrs(const void * drvdata, struct attribute * * attrs, const struct hwmon_ops * ops, const struct hwmon_channel_info * info)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int hwmon_genattrs(const void * drvdata, struct attribute * * attrs, const struct hwmon_ops * ops, const struct hwmon_channel_info * info)
```
</details>
</li>
</ul>
