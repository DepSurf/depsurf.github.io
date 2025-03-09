# Function: <code>store_ignore_nice_load</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "store_ignore_nice_load",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585874240,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:360",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_ondemand.c:store_ignore_nice_load_gov_pol",
        "drivers/cpufreq/cpufreq_ondemand.c:store_ignore_nice_load_gov_sys"
      ]
    },
    {
      "addr": 18446744071585877600,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:224",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_conservative.c:store_ignore_nice_load_gov_pol",
        "drivers/cpufreq/cpufreq_conservative.c:store_ignore_nice_load_gov_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585874240,
      "name": "store_ignore_nice_load.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071585877600,
      "name": "store_ignore_nice_load.isra.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
ssize_t store_ignore_nice_load(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_ignore_nice_load",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586273504,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:268",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586277472,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:169",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586273504,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071586277472,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
ssize_t store_ignore_nice_load(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_ignore_nice_load",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586477632,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:268",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586481664,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:197",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586477632,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071586481664,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
ssize_t store_ignore_nice_load(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_ignore_nice_load",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586602160,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:269",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586606256,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:197",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586602160,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071586606256,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
ssize_t store_ignore_nice_load(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_ignore_nice_load",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587085504,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:269",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587089440,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:197",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587085504,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071587089440,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
ssize_t store_ignore_nice_load(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_ignore_nice_load",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587383664,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:269",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587387536,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:197",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587383664,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071587387536,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
ssize_t store_ignore_nice_load(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_ignore_nice_load",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587563776,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:269",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587567616,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:199",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587563776,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071587567616,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
ssize_t store_ignore_nice_load(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_ignore_nice_load",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587839552,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:266",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587843344,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:196",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587839552,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071587843344,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
ssize_t store_ignore_nice_load(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_ignore_nice_load",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588044384,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:266",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588048176,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:196",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588044384,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071588048176,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
ssize_t store_ignore_nice_load(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_ignore_nice_load",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588904672,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:266",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588908640,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:196",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588904672,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071588908640,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
ssize_t store_ignore_nice_load(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_ignore_nice_load",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588917248,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:266",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588921152,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:196",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588917248,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071588921152,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
ssize_t store_ignore_nice_load(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_ignore_nice_load",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588805856,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:266",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588809728,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:196",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588805856,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071588809728,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
ssize_t store_ignore_nice_load(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_ignore_nice_load",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589498496,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:266",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589502368,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:196",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589498496,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071589502368,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
ssize_t store_ignore_nice_load(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_ignore_nice_load",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501313032,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:266",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501317640,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:196",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501313032,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446603336501317640,
      "name": "store_ignore_nice_load",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
ssize_t store_ignore_nice_load(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_ignore_nice_load",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233799980,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:266",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233804036,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:196",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233799980,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 3233804036,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
ssize_t store_ignore_nice_load(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_ignore_nice_load",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294846368,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:266",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294852144,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:196",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294846368,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 13835058055294852144,
      "name": "store_ignore_nice_load",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
ssize_t store_ignore_nice_load(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_ignore_nice_load",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587669376,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:266",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587673168,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:196",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587669376,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071587673168,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
ssize_t store_ignore_nice_load(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_ignore_nice_load",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587443248,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:266",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587447040,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:196",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587443248,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071587447040,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
ssize_t store_ignore_nice_load(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_ignore_nice_load",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588000528,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:266",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588004320,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:196",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588000528,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071588004320,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
ssize_t store_ignore_nice_load(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_ignore_nice_load",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588115968,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:266",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588119760,
      "name": "store_ignore_nice_load",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:196",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588115968,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071588119760,
      "name": "store_ignore_nice_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
ssize_t store_ignore_nice_load(struct gov_attr_set * attr_set, const char * buf, size_t count)
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
ssize_t store_ignore_nice_load(struct gov_attr_set * attr_set, const char * buf, size_t count)
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
ssize_t store_ignore_nice_load(struct gov_attr_set * attr_set, const char * buf, size_t count)
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
