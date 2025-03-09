# Function: <code>unexport_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t unexport_store(struct class * class, struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583203168,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:483",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583224800,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:275",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583203168,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071583224800,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
ssize_t unexport_store(struct class * class, struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583511136,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:483",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583532480,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:334",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583511136,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071583532480,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
ssize_t unexport_store(struct class * class, struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583650944,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:483",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583668608,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:334",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583650944,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071583668608,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
ssize_t unexport_store(struct class * class, struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583690368,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:490",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583708608,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:334",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583690368,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    },
    {
      "addr": 18446744071583708608,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
ssize_t unexport_store(struct class * class, struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583947200,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:490",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583966000,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:334",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583947200,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    },
    {
      "addr": 18446744071583966000,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t unexport_store(struct class * class, struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:505",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584160592,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:336",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584140208,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    },
    {
      "addr": 18446744071584142017,
      "name": "unexport_store.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071584160592,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t unexport_store(struct class * class, struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:500",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584248448,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:346",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584227856,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071584229633,
      "name": "unexport_store.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584248448,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
ssize_t unexport_store(struct class * class, struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:500",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584442048,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:338",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584417568,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071584419361,
      "name": "unexport_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584442048,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
ssize_t unexport_store(struct class * class, struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:500",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584578784,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:338",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584553936,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071584555713,
      "name": "unexport_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584578784,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
ssize_t unexport_store(struct class * class, struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:500",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585253824,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:338",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585226496,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071585228833,
      "name": "unexport_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071585253824,
      "name": "unexport_store",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t unexport_store(struct class * class, struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:501",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585410960,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:338",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585384576,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071591389235,
      "name": "unexport_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071585410960,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
ssize_t unexport_store(struct class * class, struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:509",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585291696,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:338",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585268672,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071591331675,
      "name": "unexport_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071585291696,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
ssize_t unexport_store(struct class * class, struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:498",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585748384,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:338",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585724640,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071592355112,
      "name": "unexport_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071585748384,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
ssize_t unexport_store(struct class * class, struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:481",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586931312,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:338",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586901072,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071594217260,
      "name": "unexport_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071586931312,
      "name": "unexport_store",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t unexport_store(struct class * class, struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588053440,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:481",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588087776,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:338",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588053440,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071588087776,
      "name": "unexport_store",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t unexport_store(const struct class * class, const struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588329904,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:492",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588362096,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:338",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588329904,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    },
    {
      "addr": 18446744071588362096,
      "name": "unexport_store",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t unexport_store(const struct class * class, const struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588624080,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:495",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588656816,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:338",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588624080,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    },
    {
      "addr": 18446744071588656816,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
ssize_t unexport_store(struct class * class, struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496747904,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:500",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496814848,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:338",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496747904,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    },
    {
      "addr": 18446603336496814848,
      "name": "unexport_store",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
ssize_t unexport_store(struct class * class, struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230034516,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:500",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230097864,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:338",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230034516,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    },
    {
      "addr": 3230097864,
      "name": "unexport_store",
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
ssize_t unexport_store(struct class * class, struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290843456,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:500",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290884704,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:338",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290843456,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    },
    {
      "addr": 13835058055290884704,
      "name": "unexport_store",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
ssize_t unexport_store(struct class * class, struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275499520,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:500",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275522924,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:338",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275499520,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446743936275522924,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
ssize_t unexport_store(struct class * class, struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:500",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584533232,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:338",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584510864,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071584512641,
      "name": "unexport_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584533232,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
ssize_t unexport_store(struct class * class, struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:500",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584448992,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071584450769,
      "name": "unexport_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
ssize_t unexport_store(struct class * class, struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:500",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584528944,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:338",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584505600,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071584507377,
      "name": "unexport_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584528944,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
ssize_t unexport_store(struct class * class, struct class_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "unexport_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/gpio/gpiolib-sysfs.c:500",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584636720,
      "name": "unexport_store",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:338",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584611872,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071584613649,
      "name": "unexport_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584636720,
      "name": "unexport_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct class * class</code> ➡️ <code>const struct class * class</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct class_attribute * attr</code> ➡️ <code>const struct class_attribute * attr</code>
</li>
</ul>
</details>
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
