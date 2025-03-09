# Function: <code>umask_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578877616,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:453",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578878640,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:246",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578888928,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2748",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578914864,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:273",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578923632,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:184",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578877616,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578878640,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578888928,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578914864,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578923632,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578878128,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:453",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578879968,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:248",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578889328,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3031",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578913136,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:275",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578921920,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:184",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578878128,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578879968,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578889328,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578913136,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578921920,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578878160,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:453",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578880032,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:248",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578889392,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3046",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578913568,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:275",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578922160,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:184",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578878160,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578880032,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578889392,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578913568,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578922160,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578877360,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:453",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578879184,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:287",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578888864,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3199",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578906976,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:275",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578915392,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:184",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578877360,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578879184,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578888864,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578906976,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578915392,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578878512,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:453",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578880352,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:287",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578890128,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3203",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578908800,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:276",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578917312,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:185",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578878512,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578880352,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578890128,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578908800,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578917312,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578880496,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:453",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578882192,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:288",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578892464,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3222",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578911168,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:276",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578919824,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:185",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578880496,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578882192,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578892464,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578911168,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578919824,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578880272,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:453",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578882288,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:296",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578892656,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3437",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578912736,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:276",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578921488,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:185",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578880272,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578882288,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578892656,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578912736,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578921488,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578880880,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:705",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578883456,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:295",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578894576,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3581",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578917280,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:276",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578926512,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:185",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578880880,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578883456,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578894576,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578917280,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578926512,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578881680,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:725",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578884480,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:292",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578895616,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3589",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578919264,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:276",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578928480,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:185",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578881680,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578884480,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578895616,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578919264,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578928480,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578886096,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:716",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578888416,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:310",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578900144,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3620",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578924384,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:276",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578934144,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:185",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578973856,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/zhaoxin/core.c:438",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578886096,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578888416,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578900144,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578924384,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578934144,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578973856,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578881616,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:716",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578896144,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3963",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578923280,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:276",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578935328,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:185",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578976576,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/zhaoxin/core.c:438",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578881616,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578896144,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578923280,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578935328,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578976576,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578884080,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:716",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578898736,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4185",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578927904,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:276",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578940176,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:185",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578985664,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/zhaoxin/core.c:438",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578884080,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578898736,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578927904,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578940176,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578985664,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578888128,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:716",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578899920,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4192",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578932896,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:276",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578947776,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:185",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579001632,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/zhaoxin/core.c:438",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578888128,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578899920,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578932896,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578947776,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071579001632,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578885696,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:1014",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578904432,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4254",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578941184,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:276",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578956448,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:185",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579018176,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/zhaoxin/core.c:438",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578885696,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578904432,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578941184,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578956448,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579018176,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578892592,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:989",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578918288,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4380",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578958144,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:276",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578973312,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:185",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579045744,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/zhaoxin/core.c:438",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578892592,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578918288,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578958144,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578973312,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579045744,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578890432,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:986",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578915872,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4489",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578957328,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:276",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578972560,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:185",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579045760,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/zhaoxin/core.c:438",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578890432,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578915872,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578957328,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578972560,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579045760,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578912832,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:996",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578938224,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4569",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578980720,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:276",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578997328,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:185",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579071104,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/zhaoxin/core.c:438",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578912832,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578938224,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578980720,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578997328,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579071104,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578881680,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:725",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578884480,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:292",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578895616,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3589",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578919264,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:276",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578928480,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:185",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578881680,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578884480,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578895616,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578919264,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578928480,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578875552,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:725",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578878240,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:292",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578889520,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3589",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578914656,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:276",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578925024,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:185",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578875552,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578878240,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578889520,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578914656,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578925024,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578881616,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:725",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578884416,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:292",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578895552,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3589",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578919200,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:276",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578928416,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:185",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578881616,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578884416,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578895552,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578919200,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578928416,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578881968,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:725",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578884768,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:292",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578896112,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3589",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578919744,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:276",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578928992,
      "name": "umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:185",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578881968,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578884768,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578896112,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578919744,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578928992,
      "name": "umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
ssize_t umask_show(struct device * dev, struct device_attribute * attr, char * page)
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
