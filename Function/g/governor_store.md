# Function: <code>governor_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t governor_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586107152,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:779",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586107152,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
ssize_t governor_store(struct kobject * kobj, struct attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586280544,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:32",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586520544,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:910",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586280544,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071586520544,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
ssize_t governor_store(struct kobject * kobj, struct attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586484800,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:32",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586700208,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:922",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586484800,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071586700208,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
ssize_t governor_store(struct kobject * kobj, struct attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586609440,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:32",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586825968,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:917",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586609440,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071586825968,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
ssize_t governor_store(struct kobject * kobj, struct attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587092464,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:32",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587311472,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:978",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587092464,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071587311472,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
ssize_t governor_store(struct kobject * kobj, struct attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587390608,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:32",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587614288,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:981",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587390608,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071587614288,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
ssize_t governor_store(struct kobject * kobj, struct attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587570464,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:32",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587745344,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1110",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587570464,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071587745344,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t governor_store(struct kobject * kobj, struct attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587846288,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:29",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1123",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587846288,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071588045776,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071588051803,
      "name": "governor_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t governor_store(struct kobject * kobj, struct attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588051104,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:29",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1130",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588051104,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071588254944,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071588257856,
      "name": "governor_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t governor_store(struct kobject * kobj, struct attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588911712,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:29",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1277",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588911712,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071589131024,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071589137007,
      "name": "governor_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t governor_store(struct kobject * kobj, struct attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588924144,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:29",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1360",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588924144,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071589130096,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    },
    {
      "addr": 18446744071591621549,
      "name": "governor_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t governor_store(struct kobject * kobj, struct attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588812736,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:29",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1378",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588812736,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071589019856,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    },
    {
      "addr": 18446744071591564914,
      "name": "governor_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t governor_store(struct kobject * kobj, struct attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589505776,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:29",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1378",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589505776,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071589735600,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    },
    {
      "addr": 18446744071592686043,
      "name": "governor_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t governor_store(struct kobject * kobj, struct attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590989424,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:24",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1408",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590989424,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071591248208,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    },
    {
      "addr": 18446744071594571382,
      "name": "governor_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
ssize_t governor_store(struct kobject * kobj, struct attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592695808,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:24",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593006096,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1410",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592695808,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071593006096,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 763
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
ssize_t governor_store(struct kobject * kobj, struct attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593126768,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:24",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593457616,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1411",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593126768,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071593457616,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 755
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
ssize_t governor_store(struct kobject * kobj, struct attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593879936,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:24",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594204560,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1432",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593879936,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071594204560,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 755
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
ssize_t governor_store(struct kobject * kobj, struct attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501320920,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:29",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501711608,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1130",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501320920,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446603336501711608,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
ssize_t governor_store(struct kobject * kobj, struct attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233807312,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:29",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234239376,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1130",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233807312,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 3234239376,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
ssize_t governor_store(struct kobject * kobj, struct attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294857008,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:29",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295157840,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1130",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294857008,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 13835058055295157840,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
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
ssize_t governor_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278130656,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1130",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278130656,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t governor_store(struct kobject * kobj, struct attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587676096,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:29",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1130",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587676096,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071587866640,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071587869552,
      "name": "governor_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t governor_store(struct kobject * kobj, struct attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587449968,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:29",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1130",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587449968,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071587593440,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071587596352,
      "name": "governor_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t governor_store(struct kobject * kobj, struct attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588007248,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:29",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1130",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588007248,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071588192000,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071588194912,
      "name": "governor_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t governor_store(struct kobject * kobj, struct attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "governor_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588122688,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor_attr_set.c:29",
      "file": "drivers/cpufreq/cpufreq_governor_attr_set.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "governor_store",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:1130",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588122688,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071588327296,
      "name": "governor_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071588330208,
      "name": "governor_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
