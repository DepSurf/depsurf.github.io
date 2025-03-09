# Function: <code>enabled_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t enabled_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579800560,
      "name": "enabled_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:547",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580893664,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/huge_memory.c:284",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586126112,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:456",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579800560,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071580893664,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071586126112,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
ssize_t enabled_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579828272,
      "name": "enabled_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:611",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581023536,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/huge_memory.c:172",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586539840,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:456",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579828272,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071581023536,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071586539840,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
ssize_t enabled_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579855840,
      "name": "enabled_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:606",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581098208,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/huge_memory.c:192",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586721568,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:456",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855840,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071581098208,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071586721568,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
ssize_t enabled_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579859296,
      "name": "enabled_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:447",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581143936,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/huge_memory.c:159",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586847968,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:456",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579859296,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071581143936,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071586847968,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
ssize_t enabled_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579900944,
      "name": "enabled_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:461",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581266416,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/huge_memory.c:159",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587335680,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:456",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900944,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071581266416,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071587335680,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
ssize_t enabled_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579934480,
      "name": "enabled_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:458",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581413312,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/huge_memory.c:159",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587638992,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:456",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579934480,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    },
    {
      "addr": 18446744071581413312,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071587638992,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
ssize_t enabled_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579981536,
      "name": "enabled_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:458",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581496624,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/huge_memory.c:169",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587767904,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:456",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981536,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    },
    {
      "addr": 18446744071581496624,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071587767904,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
ssize_t enabled_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enabled_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:311",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581604608,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/huge_memory.c:174",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588072640,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:444",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580021232,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
    },
    {
      "addr": 18446744071580025899,
      "name": "enabled_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071581604608,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071588072640,
      "name": "enabled_store",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t enabled_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580072240,
      "name": "enabled_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:311",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581675216,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/huge_memory.c:174",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588278448,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:444",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072240,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
    },
    {
      "addr": 18446744071581675216,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071588278448,
      "name": "enabled_store",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t enabled_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580131440,
      "name": "enabled_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:333",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581895024,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/huge_memory.c:174",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589159216,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:444",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131440,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
    },
    {
      "addr": 18446744071581895024,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071589159216,
      "name": "enabled_store",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t enabled_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580109664,
      "name": "enabled_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:333",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581941216,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/huge_memory.c:179",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589156176,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:443",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580109664,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
    },
    {
      "addr": 18446744071581941216,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071589156176,
      "name": "enabled_store",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t enabled_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580113456,
      "name": "enabled_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:332",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581965936,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/huge_memory.c:192",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589049888,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:443",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580113456,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
    },
    {
      "addr": 18446744071581965936,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071589049888,
      "name": "enabled_store",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t enabled_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enabled_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:332",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582268624,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/huge_memory.c:192",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586248352,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/acpi/sysfs.c:923",
      "file": "drivers/acpi/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:443",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580255776,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
    },
    {
      "addr": 18446744071592147313,
      "name": "enabled_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071582268624,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071586248352,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071589770416,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    },
    {
      "addr": 18446744071592690099,
      "name": "enabled_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
ssize_t enabled_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enabled_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:332",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582749056,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/huge_memory.c:191",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587488096,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/acpi/sysfs.c:934",
      "file": "drivers/acpi/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:443",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580425024,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
    },
    {
      "addr": 18446744071593920012,
      "name": "enabled_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071582749056,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071587488096,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071591280384,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071594575278,
      "name": "enabled_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t enabled_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enabled_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:340",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583282048,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/huge_memory.c:254",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588756992,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/acpi/sysfs.c:935",
      "file": "drivers/acpi/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:444",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580664896,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
    },
    {
      "addr": 18446744071595992035,
      "name": "enabled_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071583282048,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071588756992,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071593029568,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071596320306,
      "name": "enabled_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t enabled_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enabled_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:355",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582693424,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/vmscan.c:5777",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583501520,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/huge_memory.c:255",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589045696,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/acpi/sysfs.c:952",
      "file": "drivers/acpi/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:444",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580741088,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
    },
    {
      "addr": 18446744071596510225,
      "name": "enabled_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071582693424,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
    },
    {
      "addr": 18446744071583501520,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071589045696,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071593481264,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071596849949,
      "name": "enabled_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
ssize_t enabled_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enabled_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:355",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582863552,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/vmscan.c:5122",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583695152,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/huge_memory.c:289",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589350400,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/acpi/sysfs.c:952",
      "file": "drivers/acpi/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:444",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580826048,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
    },
    {
      "addr": 18446744071597409098,
      "name": "enabled_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071582863552,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
    },
    {
      "addr": 18446744071583695152,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071589350400,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071594228416,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071597774770,
      "name": "enabled_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
ssize_t enabled_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493122560,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/huge_memory.c:174",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501749928,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:444",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493122560,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    },
    {
      "addr": 18446603336501749928,
      "name": "enabled_store",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
ssize_t enabled_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234302256,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:444",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234302256,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
ssize_t enabled_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284190432,
      "name": "enabled_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:311",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286598304,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/huge_memory.c:174",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295193344,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:444",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284190432,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
    },
    {
      "addr": 13835058055286598304,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    },
    {
      "addr": 13835058055295193344,
      "name": "enabled_store",
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
ssize_t enabled_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278153196,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:444",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278153196,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
ssize_t enabled_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580040976,
      "name": "enabled_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:311",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581643952,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/huge_memory.c:174",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580040976,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
    },
    {
      "addr": 18446744071581643952,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
ssize_t enabled_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579986288,
      "name": "enabled_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:311",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581584816,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/huge_memory.c:174",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579986288,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
    },
    {
      "addr": 18446744071581584816,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
ssize_t enabled_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580032512,
      "name": "enabled_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:311",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581635264,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/huge_memory.c:174",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588215504,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:444",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580032512,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
    },
    {
      "addr": 18446744071581635264,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071588215504,
      "name": "enabled_store",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
ssize_t enabled_store(struct kobject * kobj, struct kobj_attribute * attr, const char * buf, size_t count)
```

```json
{
  "name": "enabled_store",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580083216,
      "name": "enabled_store",
      "external": false,
      "loc": "kernel/livepatch/core.c:311",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581701600,
      "name": "enabled_store",
      "external": false,
      "loc": "mm/huge_memory.c:174",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588350800,
      "name": "enabled_store",
      "external": false,
      "loc": "drivers/powercap/powercap_sys.c:444",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580083216,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
    },
    {
      "addr": 18446744071581701600,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071588350800,
      "name": "enabled_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param added. </b>
<code>size_t len</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kobject * kobj</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct kobj_attribute * attr</code> ➡️ <code>struct device_attribute * attr</code>
</li>
</ul>
</details>
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
<b>Param added. </b>
<code>size_t len</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kobject * kobj</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct kobj_attribute * attr</code> ➡️ <code>struct device_attribute * attr</code>
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
