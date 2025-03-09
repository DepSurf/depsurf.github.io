# Function: <code>__uncore_event_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t __uncore_event_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578941056,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:189",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578946832,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:66",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578952192,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:267",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578941056,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578946832,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578952192,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t __uncore_event_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578937536,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:189",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578943616,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:72",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578948976,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:267",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578937536,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578943616,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578948976,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t __uncore_event_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578938064,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:189",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578944144,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:76",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578949776,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:326",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578938064,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578944144,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578949776,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t __uncore_event_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578931280,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:189",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578937232,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:76",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578942688,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:326",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578931280,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578937232,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578942688,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t __uncore_event_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578932768,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:190",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578939408,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:77",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578944656,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:327",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578932768,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578939408,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578944656,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t __uncore_event_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578936752,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:190",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578942320,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:77",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578947104,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:327",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578936752,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578942320,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578947104,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t __uncore_event_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578938672,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:190",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578944352,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:96",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578949104,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:327",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578938672,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578944352,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578949104,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t __uncore_event_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578943408,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:190",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578949952,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:112",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578955264,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:390",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578943408,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578949952,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578955264,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t __uncore_event_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578945856,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:190",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578952384,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:113",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578957696,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:385",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578945856,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578952384,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578957696,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t __uncore_event_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578952416,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:190",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578958752,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:118",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578963568,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:421",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578952416,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578958752,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578963568,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t __uncore_event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578953680,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:190",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578960032,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:134",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578964832,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:450",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578953680,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578960032,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578964832,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t __uncore_event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578958704,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:190",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578965072,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:156",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578970128,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:450",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578982368,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_discovery.c:320",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578958704,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578965072,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578970128,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578982368,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t __uncore_event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578970848,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:190",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578977616,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:156",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578982320,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:469",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578998320,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_discovery.c:320",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578970848,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578977616,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578982320,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578998320,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t __uncore_event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578982144,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:190",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578990048,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:208",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578997008,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:469",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579014512,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_discovery.c:328",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578982144,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578990048,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578997008,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579014512,
      "name": "__uncore_event_show",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t __uncore_event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579001184,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:190",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579009888,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:247",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579018704,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:471",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579041664,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_discovery.c:328",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579001184,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579009888,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579018704,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579041664,
      "name": "__uncore_event_show",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t __uncore_event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579000976,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:190",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579009936,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:247",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579018752,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:471",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579041904,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_discovery.c:348",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579000976,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579009936,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579018752,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579041904,
      "name": "__uncore_event_show",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t __uncore_event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579025904,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:190",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579034864,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:247",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579043680,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:471",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579067152,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_discovery.c:349",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579025904,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579034864,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579043680,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579067152,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
ssize_t __uncore_event_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578945856,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:190",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578952384,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:113",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578957696,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:385",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578945856,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578952384,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578957696,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t __uncore_event_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578942736,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:190",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578949648,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:113",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578955216,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:385",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578942736,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578949648,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578955216,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t __uncore_event_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578945792,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:190",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578952320,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:113",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578957632,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:385",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578945792,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578952320,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578957632,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t __uncore_event_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578946368,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:190",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578952896,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:113",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578958208,
      "name": "__uncore_event_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:385",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578946368,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578952896,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578958208,
      "name": "__uncore_event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
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
<code>struct kobj_attribute * attr</code> ➡️ <code>struct device_attribute * attr</code>
</li>
</ul>
</details>
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
ssize_t __uncore_event_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
ssize_t __uncore_event_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
ssize_t __uncore_event_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
ssize_t __uncore_event_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
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
