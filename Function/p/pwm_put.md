# Function: <code>pwm_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583221632,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:767",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:pwm_free",
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583221632,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583528768,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:844",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_free",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583528768,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583664800,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:846",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_free",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583664800,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583706712,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:862",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_free"
      ],
      "caller_func": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_free",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583706528,
      "name": "pwm_put.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071583706640,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583964104,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:862",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_free"
      ],
      "caller_func": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_free",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583963920,
      "name": "pwm_put.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071583964032,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584158648,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:862",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_free"
      ],
      "caller_func": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_free",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584158464,
      "name": "pwm_put.part.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071584160081,
      "name": "pwm_put.part.15.cold.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071584158576,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584246472,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:862",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_free"
      ],
      "caller_func": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_free",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584246288,
      "name": "pwm_put.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071584247833,
      "name": "pwm_put.part.16.cold.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071584246400,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584437944,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:983",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get"
      ],
      "caller_func": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584437760,
      "name": "pwm_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071584440359,
      "name": "pwm_put.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071584437872,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584574712,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:984",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get"
      ],
      "caller_func": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584574528,
      "name": "pwm_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071584577105,
      "name": "pwm_put.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071584574640,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585248744,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:1112",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get"
      ],
      "caller_func": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585248544,
      "name": "pwm_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071585252749,
      "name": "pwm_put.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071585248672,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585406296,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:1112",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get"
      ],
      "caller_func": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585406096,
      "name": "pwm_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071591390330,
      "name": "pwm_put.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071585406224,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585287224,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:1082",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get"
      ],
      "caller_func": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585287024,
      "name": "pwm_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071591332574,
      "name": "pwm_put.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071585287152,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585746795,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:1042",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ],
      "caller_func": [
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585743808,
      "name": "pwm_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071592356954,
      "name": "pwm_put.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071585743936,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586929596,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:1096",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ],
      "caller_func": [
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586927136,
      "name": "pwm_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071594219408,
      "name": "pwm_put.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071586927264,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588085628,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:1024",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ],
      "caller_func": [
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588083008,
      "name": "pwm_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071588083168,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588359939,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:967",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ],
      "caller_func": [
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588357344,
      "name": "pwm_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071588357504,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588654659,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:951",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ],
      "caller_func": [
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588651840,
      "name": "pwm_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071588651984,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496808780,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:984",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:of_pwm_get"
      ],
      "caller_func": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:of_pwm_get",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496808440,
      "name": "pwm_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446603336496808656,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230095252,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:984",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:of_pwm_get"
      ],
      "caller_func": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:of_pwm_get",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230093488,
      "name": "pwm_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 3230093632,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290877108,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:984",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:of_pwm_get"
      ],
      "caller_func": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:of_pwm_get",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290876784,
      "name": "pwm_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 13835058055290877024,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275519464,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:984",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:of_pwm_get"
      ],
      "caller_func": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:of_pwm_get",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275519222,
      "name": "pwm_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446743936275519352,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584529160,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:984",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get"
      ],
      "caller_func": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584528976,
      "name": "pwm_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071584531553,
      "name": "pwm_put.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071584529088,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584524872,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:984",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get"
      ],
      "caller_func": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584524688,
      "name": "pwm_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071584527265,
      "name": "pwm_put.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071584524800,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pwm_put(struct pwm_device * pwm)
```

```json
{
  "name": "pwm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584632648,
      "name": "pwm_put",
      "external": true,
      "loc": "drivers/pwm/core.c:984",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get"
      ],
      "caller_func": [
        "drivers/pwm/core.c:devm_pwm_release",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584632464,
      "name": "pwm_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071584635041,
      "name": "pwm_put.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071584632576,
      "name": "pwm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void pwm_put(struct pwm_device * pwm)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
