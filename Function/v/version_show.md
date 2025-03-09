# Function: <code>version_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579060688,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:23",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579158512,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:431",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582003376,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:773",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585234064,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:184",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579060688,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579158512,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071582003376,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071585234064,
      "name": "version_show",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579057072,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:23",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579158640,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:423",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582216240,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:773",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585627488,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:194",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579057072,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579158640,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071582216240,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071585627488,
      "name": "version_show",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579056096,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:23",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579167936,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:498",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582305792,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:774",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585815104,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:208",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579056096,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579167936,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071582305792,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071585815104,
      "name": "version_show",
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
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579048288,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:23",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579167728,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:538",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582390640,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:772",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585902048,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:208",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579048288,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579167728,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071582390640,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585902048,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579057152,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:23",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579182432,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:646",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582541376,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:771",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586342816,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:208",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579057152,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579182432,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071582541376,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586342816,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579062064,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:23",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579193984,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:652",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582733392,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:771",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586600352,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:228",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579062064,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579193984,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071582733392,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586600352,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579066640,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:23",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579183392,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:653",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582837104,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:771",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586749136,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:228",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579066640,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579183392,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071582837104,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586749136,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579075184,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:22",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579195984,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:652",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583012016,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:757",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587004144,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:229",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579075184,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579195984,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071583012016,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071587004144,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579077184,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:22",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579198240,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:652",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583118208,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:757",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587203632,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:229",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077184,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579198240,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071583118208,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071587203632,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579087952,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:22",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579219024,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:657",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583438128,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:757",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588055984,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:229",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579087952,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579219024,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071583438128,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071588055984,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579089920,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:22",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579213472,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:655",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583551488,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:757",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588101376,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:229",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579089920,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579213472,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071583551488,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071588101376,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579096480,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:22",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579216000,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:655",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583574928,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:769",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586092512,
      "name": "version_show",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:26",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587983968,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:232",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579096480,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579216000,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071583574928,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586092512,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071587983968,
      "name": "version_show",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579120048,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:22",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579254224,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:655",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583933200,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:769",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586589744,
      "name": "version_show",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:26",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587332032,
      "name": "version_show",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:4148",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588596976,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:232",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579120048,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579254224,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071583933200,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586589744,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587332032,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071588596976,
      "name": "version_show",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579152592,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:22",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579306656,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:555",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584513088,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:769",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587850544,
      "name": "version_show",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:26",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588647120,
      "name": "version_show",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:3893",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590009168,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:232",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579152592,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071579306656,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071584513088,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071587850544,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071588647120,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071590009168,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579200912,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:22",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579373120,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:512",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585182656,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:769",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589194080,
      "name": "version_show",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:26",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590118416,
      "name": "version_show",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:3769",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591609456,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:233",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579200912,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071579373120,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071585182656,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071589194080,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071590118416,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071591609456,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579204976,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:22",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579382416,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:509",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585411712,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:769",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589488240,
      "name": "version_show",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:26",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590431936,
      "name": "version_show",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:3656",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592031728,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:233",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579204976,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071579382416,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071585411712,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071589488240,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071590431936,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071592031728,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579234320,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:22",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579413520,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:720",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585646608,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:769",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589795184,
      "name": "version_show",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:26",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590777968,
      "name": "version_show",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:3505",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592771744,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:230",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579234320,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071579413520,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071585646608,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071589795184,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071590777968,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071592771744,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buff)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494827232,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:757",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500287760,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:229",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494827232,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446603336500287760,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buff)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228246180,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:757",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232757684,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:229",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228246180,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 3232757684,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
ssize_t version_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283410880,
      "name": "version_show",
      "external": false,
      "loc": "arch/powerpc/perf/hv-gpci.c:98",
      "file": "arch/powerpc/perf/hv-gpci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055288671888,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:757",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055293591248,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:229",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283410880,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 13835058055288671888,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 13835058055293591248,
      "name": "version_show",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buff)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274151870,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:757",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277197518,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:229",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274151870,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446743936277197518,
      "name": "version_show",
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
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579077536,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:22",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579197088,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:652",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583086944,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:757",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586909712,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:229",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077536,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579197088,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071583086944,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586909712,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579010224,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:22",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579132080,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:652",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583024096,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:757",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586850880,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:229",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579010224,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579132080,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071583024096,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586850880,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579077120,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:22",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579198160,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:652",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583075552,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:757",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587158192,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:229",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077120,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579198160,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071583075552,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071587158192,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
ssize_t version_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "version_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579081216,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:22",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579203440,
      "name": "version_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:652",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583164832,
      "name": "version_show",
      "external": false,
      "loc": "fs/ecryptfs/main.c:757",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587265264,
      "name": "version_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:229",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579081216,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579203440,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071583164832,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071587265264,
      "name": "version_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>char * buff</code>
</li>
<li>
<b>Param removed. </b>
<code>char * buf</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>char * buff</code>
</li>
<li>
<b>Param removed. </b>
<code>char * buf</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param added. </b>
<code>char * page</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kobject * kobj</code>
</li>
<li>
<b>Param removed. </b>
<code>char * buf</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct kobj_attribute * attr</code> ➡️ <code>struct device_attribute * attr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>char * buff</code>
</li>
<li>
<b>Param removed. </b>
<code>char * buf</code>
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
