# Function: <code>show_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t show_status(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "show_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583771235,
      "name": "show_status",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:26",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583771235,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
ssize_t show_status(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "show_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584097156,
      "name": "show_status",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:27",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584097156,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
ssize_t show_status(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "show_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584239825,
      "name": "show_status",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:27",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584239825,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
ssize_t show_status(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "show_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584315824,
      "name": "show_status",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:28",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586627152,
      "name": "show_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1001",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584315824,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071586627152,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
ssize_t show_status(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "show_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584715040,
      "name": "show_status",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:28",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587110080,
      "name": "show_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:816",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584715040,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071587110080,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
ssize_t show_status(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "show_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584942464,
      "name": "show_status",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:28",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587408304,
      "name": "show_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:847",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584942464,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071587408304,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
ssize_t show_status(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "show_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585046448,
      "name": "show_status",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:28",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587588880,
      "name": "show_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:909",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585046448,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071587588880,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
ssize_t show_status(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "show_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585250576,
      "name": "show_status",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:25",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587865024,
      "name": "show_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:946",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585250576,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071587865024,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
ssize_t show_status(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "show_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585388464,
      "name": "show_status",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:25",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588069824,
      "name": "show_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:945",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585388464,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071588069824,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
ssize_t show_status(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "show_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586097520,
      "name": "show_status",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:25",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588930640,
      "name": "show_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:952",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586097520,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071588930640,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
ssize_t show_status(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "show_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586218096,
      "name": "show_status",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:25",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588941872,
      "name": "show_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1054",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586218096,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071588941872,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
ssize_t show_status(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "show_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588830048,
      "name": "show_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1056",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588830048,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
ssize_t show_status(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "show_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589525488,
      "name": "show_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1156",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589525488,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
ssize_t show_status(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "show_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591015264,
      "name": "show_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1189",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591015264,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
ssize_t show_status(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "show_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592725616,
      "name": "show_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1164",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592725616,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
ssize_t show_status(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "show_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593162816,
      "name": "show_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1184",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593162816,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
ssize_t show_status(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "show_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593916224,
      "name": "show_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1208",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593916224,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
ssize_t show_status(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "show_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497661272,
      "name": "show_status",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:25",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497661272,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
ssize_t show_status(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "show_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587691968,
      "name": "show_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:945",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587691968,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
ssize_t show_status(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "show_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587468096,
      "name": "show_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:945",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587468096,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
ssize_t show_status(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "show_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585338864,
      "name": "show_status",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:25",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588025968,
      "name": "show_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:945",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585338864,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071588025968,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
ssize_t show_status(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "show_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585446192,
      "name": "show_status",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:25",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588141440,
      "name": "show_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:945",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585446192,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071588141440,
      "name": "show_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
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
<code>struct device_attribute * attr</code> ➡️ <code>struct kobj_attribute * attr</code>
</li>
</ul>
</details>
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
ssize_t show_status(struct device * dev, struct device_attribute * attr, char * buf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
ssize_t show_status(struct device * dev, struct device_attribute * attr, char * buf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
ssize_t show_status(struct device * dev, struct device_attribute * attr, char * buf)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ❓</summary>
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
<code>struct device_attribute * attr</code> ➡️ <code>struct kobj_attribute * attr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ❓</summary>
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
<code>struct device_attribute * attr</code> ➡️ <code>struct kobj_attribute * attr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
