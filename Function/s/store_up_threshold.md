# Function: <code>store_up_threshold</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "store_up_threshold",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585873481,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:322",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold_gov_pol",
        "drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold_gov_sys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585877341,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:192",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_conservative.c:store_up_threshold_gov_pol",
        "drivers/cpufreq/cpufreq_conservative.c:store_up_threshold_gov_sys"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t store_up_threshold(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_up_threshold",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586273248,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:223",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586276864,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:135",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586273248,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071586276864,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
ssize_t store_up_threshold(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_up_threshold",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586477376,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:223",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586481056,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:163",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586477376,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071586481056,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
ssize_t store_up_threshold(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_up_threshold",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586601712,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:224",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586605648,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:163",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586601712,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071586605648,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
ssize_t store_up_threshold(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_up_threshold",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587085056,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:224",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587088880,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:163",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587085056,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071587088880,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
ssize_t store_up_threshold(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_up_threshold",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587383216,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:224",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587386976,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:163",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587383216,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071587386976,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
ssize_t store_up_threshold(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_up_threshold",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587563520,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:224",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587567056,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:165",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587563520,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071587567056,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
ssize_t store_up_threshold(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_up_threshold",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587839296,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:221",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587842784,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:162",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587839296,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071587842784,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
ssize_t store_up_threshold(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_up_threshold",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588044128,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:221",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588047616,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:162",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588044128,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071588047616,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
ssize_t store_up_threshold(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_up_threshold",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588904416,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:221",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588908080,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:162",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588904416,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071588908080,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
ssize_t store_up_threshold(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_up_threshold",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588916992,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:221",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588920592,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:162",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588916992,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071588920592,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
ssize_t store_up_threshold(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_up_threshold",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588805600,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:221",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588809168,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:162",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588805600,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071588809168,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
ssize_t store_up_threshold(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_up_threshold",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589498240,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:221",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589501808,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:162",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589498240,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071589501808,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
ssize_t store_up_threshold(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_up_threshold",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501312720,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:221",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501316920,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:162",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501312720,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446603336501316920,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
ssize_t store_up_threshold(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_up_threshold",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233799680,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:221",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233803456,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:162",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233799680,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 3233803456,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
ssize_t store_up_threshold(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_up_threshold",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294846000,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:221",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294851296,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:162",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294846000,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 13835058055294851296,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
ssize_t store_up_threshold(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_up_threshold",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587669120,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:221",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587672608,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:162",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587669120,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071587672608,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
ssize_t store_up_threshold(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_up_threshold",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587442992,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:221",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587446480,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:162",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587442992,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071587446480,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
ssize_t store_up_threshold(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_up_threshold",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588000272,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:221",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588003760,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:162",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588000272,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071588003760,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
ssize_t store_up_threshold(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_up_threshold",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588115712,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:221",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588119200,
      "name": "store_up_threshold",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:162",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588115712,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071588119200,
      "name": "store_up_threshold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
ssize_t store_up_threshold(struct gov_attr_set * attr_set, const char * buf, size_t count)
```
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
ssize_t store_up_threshold(struct gov_attr_set * attr_set, const char * buf, size_t count)
```
</details>
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
ssize_t store_up_threshold(struct gov_attr_set * attr_set, const char * buf, size_t count)
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
