# Function: <code>governor_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t governor_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586104496,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:770",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586104496,
      "name": "governor_show",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t governor_show(struct kobject * kobj, struct attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586280512,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:24",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586517504,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:901",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586280512,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586517504,
      "name": "governor_show",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t governor_show(struct kobject * kobj, struct attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586484768,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:24",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586697088,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:913",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586484768,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586697088,
      "name": "governor_show",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t governor_show(struct kobject * kobj, struct attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586609328,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:24",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586822928,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:908",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586609328,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586822928,
      "name": "governor_show",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t governor_show(struct kobject * kobj, struct attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587092352,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:24",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587310272,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:969",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587092352,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071587310272,
      "name": "governor_show",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t governor_show(struct kobject * kobj, struct attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587390496,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:24",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587613024,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:972",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587390496,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071587613024,
      "name": "governor_show",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t governor_show(struct kobject * kobj, struct attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587570432,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:24",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587741456,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1101",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587570432,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071587741456,
      "name": "governor_show",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t governor_show(struct kobject * kobj, struct attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587846256,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:21",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588044944,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1114",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587846256,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071588044944,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t governor_show(struct kobject * kobj, struct attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588051072,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:21",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588250608,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1121",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588051072,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071588250608,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t governor_show(struct kobject * kobj, struct attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588911680,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:21",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589128352,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1268",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588911680,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589128352,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t governor_show(struct kobject * kobj, struct attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588924112,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:21",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589126688,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1349",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588924112,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589126688,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t governor_show(struct kobject * kobj, struct attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588812704,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:21",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589016464,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1367",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588812704,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589016464,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t governor_show(struct kobject * kobj, struct attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589505744,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:21",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589731440,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1367",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589505744,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589731440,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t governor_show(struct kobject * kobj, struct attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590989376,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:16",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591242368,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1397",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590989376,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071591242368,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t governor_show(struct kobject * kobj, struct attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592695744,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:16",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592994944,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1399",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592695744,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071592994944,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t governor_show(struct kobject * kobj, struct attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593126704,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:16",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593446416,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1400",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593126704,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071593446416,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t governor_show(struct kobject * kobj, struct attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593879872,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:16",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594192816,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1421",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593879872,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071594192816,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
ssize_t governor_show(struct kobject * kobj, struct attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501320848,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:21",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501710192,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1121",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501320848,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446603336501710192,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
ssize_t governor_show(struct kobject * kobj, struct attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233807276,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:21",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234233836,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1121",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233807276,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3234233836,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
ssize_t governor_show(struct kobject * kobj, struct attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294856928,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:21",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295150480,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1121",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294856928,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 13835058055295150480,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
ssize_t governor_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278127598,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1121",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278127598,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
ssize_t governor_show(struct kobject * kobj, struct attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587676064,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:21",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587862304,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1121",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587676064,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587862304,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
ssize_t governor_show(struct kobject * kobj, struct attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587449936,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:21",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587589104,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1121",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587449936,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587589104,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
ssize_t governor_show(struct kobject * kobj, struct attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588007216,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:21",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588187664,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1121",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588007216,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071588187664,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
ssize_t governor_show(struct kobject * kobj, struct attribute * attr, char * buf)
```

```json
{
  "name": "governor_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588122656,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:21",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588322960,
      "name": "governor_show",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1121",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588122656,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071588322960,
      "name": "governor_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kobject * kobj</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct device_attribute * attr</code> ➡️ <code>struct attribute * attr</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kobject * kobj</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct attribute * attr</code> ➡️ <code>struct device_attribute * attr</code>
</li>
</ul>
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
