# Function: <code>watchdog_cdev_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586103328,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:885",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586103328,
      "name": "watchdog_cdev_unregister.isra.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586304016,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:975",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586304016,
      "name": "watchdog_cdev_unregister.isra.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void watchdog_cdev_unregister(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586404160,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:988",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586404160,
      "name": "watchdog_cdev_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void watchdog_cdev_unregister(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586870352,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:990",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586870352,
      "name": "watchdog_cdev_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
void watchdog_cdev_unregister(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587163456,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:1012",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587163456,
      "name": "watchdog_cdev_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void watchdog_cdev_unregister(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587343376,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:1012",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587343376,
      "name": "watchdog_cdev_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void watchdog_cdev_unregister(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587614256,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:1039",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587614256,
      "name": "watchdog_cdev_unregister",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void watchdog_cdev_unregister(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587818880,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:1053",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587818880,
      "name": "watchdog_cdev_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
void watchdog_cdev_unregister(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588665888,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:1074",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588665888,
      "name": "watchdog_cdev_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void watchdog_cdev_unregister(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588693024,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:1077",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588693024,
      "name": "watchdog_cdev_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void watchdog_cdev_unregister(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588579392,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:1077",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588579392,
      "name": "watchdog_cdev_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void watchdog_cdev_unregister(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589255232,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:1084",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589255232,
      "name": "watchdog_cdev_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void watchdog_cdev_unregister(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590723936,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:1088",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590723936,
      "name": "watchdog_cdev_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
void watchdog_cdev_unregister(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592396240,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:1100",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592396240,
      "name": "watchdog_cdev_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
void watchdog_cdev_unregister(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592825584,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:1121",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592825584,
      "name": "watchdog_cdev_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
void watchdog_cdev_unregister(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593574848,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:1120",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593574848,
      "name": "watchdog_cdev_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
void watchdog_cdev_unregister(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501034120,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:1053",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501034120,
      "name": "watchdog_cdev_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void watchdog_cdev_unregister(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233551872,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:1053",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233551872,
      "name": "watchdog_cdev_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void watchdog_cdev_unregister(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294516032,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:1053",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294516032,
      "name": "watchdog_cdev_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void watchdog_cdev_unregister(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277772180,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:1053",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277772180,
      "name": "watchdog_cdev_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void watchdog_cdev_unregister(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587449856,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:1053",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587449856,
      "name": "watchdog_cdev_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
void watchdog_cdev_unregister(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587218064,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:1053",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587218064,
      "name": "watchdog_cdev_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
void watchdog_cdev_unregister(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587775024,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:1053",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587775024,
      "name": "watchdog_cdev_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
void watchdog_cdev_unregister(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587888368,
      "name": "watchdog_cdev_unregister",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:1053",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587888368,
      "name": "watchdog_cdev_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void watchdog_cdev_unregister(struct watchdog_device * wdd)
```
</details>
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
