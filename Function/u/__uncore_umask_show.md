# Function: <code>__uncore_umask_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t __uncore_umask_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578941008,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:191",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578946784,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:67",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578952144,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:271",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578941008,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578946784,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578952144,
      "name": "__uncore_umask_show",
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
ssize_t __uncore_umask_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578937488,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:191",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578943568,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:73",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578949024,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:271",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578937488,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578943568,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578949024,
      "name": "__uncore_umask_show",
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
ssize_t __uncore_umask_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578938016,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:191",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578944096,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:77",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578949824,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:330",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578938016,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578944096,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578949824,
      "name": "__uncore_umask_show",
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
ssize_t __uncore_umask_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578931232,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:191",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578937184,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:77",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578942736,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:330",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578931232,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578937184,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578942736,
      "name": "__uncore_umask_show",
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
ssize_t __uncore_umask_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578932720,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:192",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578939360,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:78",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578944704,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:331",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578932720,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578939360,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578944704,
      "name": "__uncore_umask_show",
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
ssize_t __uncore_umask_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578936704,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:192",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578942272,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:78",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578947152,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:331",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578936704,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578942272,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578947152,
      "name": "__uncore_umask_show",
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
ssize_t __uncore_umask_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578938624,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:192",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578944304,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:97",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578949152,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:331",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578938624,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578944304,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578949152,
      "name": "__uncore_umask_show",
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
ssize_t __uncore_umask_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578943360,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:192",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578949904,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:113",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578955312,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:394",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578943360,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578949904,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578955312,
      "name": "__uncore_umask_show",
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
ssize_t __uncore_umask_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578945808,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:192",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578952336,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:114",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578957744,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:389",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578945808,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578952336,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578957744,
      "name": "__uncore_umask_show",
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
ssize_t __uncore_umask_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578952368,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:192",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578958704,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:119",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578963616,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:425",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578952368,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578958704,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578963616,
      "name": "__uncore_umask_show",
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
ssize_t __uncore_umask_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578884240,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:291",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578953632,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:192",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578959984,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:135",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578964880,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:454",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578884240,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578953632,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578959984,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578964880,
      "name": "__uncore_umask_show",
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
ssize_t __uncore_umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578886768,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:291",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578958656,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:192",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578965024,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:157",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578970176,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:454",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578982320,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_discovery.c:321",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578886768,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578958656,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578965024,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578970176,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578982320,
      "name": "__uncore_umask_show",
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
ssize_t __uncore_umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578970800,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:192",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578977568,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:157",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578982368,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:473",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578998272,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_discovery.c:321",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578970800,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578977568,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578982368,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578998272,
      "name": "__uncore_umask_show",
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
ssize_t __uncore_umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578982080,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:192",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578989984,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:209",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578997056,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:473",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579014448,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_discovery.c:329",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578982080,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578989984,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578997056,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579014448,
      "name": "__uncore_umask_show",
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
ssize_t __uncore_umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579001104,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:192",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579009808,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:248",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579018768,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:475",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579041584,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_discovery.c:329",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579001104,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579009808,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579018768,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579041584,
      "name": "__uncore_umask_show",
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
ssize_t __uncore_umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579000896,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:192",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579009856,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:248",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579018816,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:475",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579041824,
      "name": "__uncore_umask_show",
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
      "addr": 18446744071579000896,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579009856,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579018816,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579041824,
      "name": "__uncore_umask_show",
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
ssize_t __uncore_umask_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579025824,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:192",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579034784,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:248",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579043744,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:475",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579067072,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_discovery.c:350",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579025824,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579034784,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579043744,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579067072,
      "name": "__uncore_umask_show",
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
ssize_t __uncore_umask_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578945808,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:192",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578952336,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:114",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578957744,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:389",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578945808,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578952336,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578957744,
      "name": "__uncore_umask_show",
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
ssize_t __uncore_umask_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578942688,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:192",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578949600,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:114",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578955264,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:389",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578942688,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578949600,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578955264,
      "name": "__uncore_umask_show",
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
ssize_t __uncore_umask_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578945744,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:192",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578952272,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:114",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578957680,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:389",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578945744,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578952272,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578957680,
      "name": "__uncore_umask_show",
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
ssize_t __uncore_umask_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_umask_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578946320,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:192",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578952848,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:114",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578958256,
      "name": "__uncore_umask_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:389",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578946320,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578952848,
      "name": "__uncore_umask_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578958256,
      "name": "__uncore_umask_show",
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
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
ssize_t __uncore_umask_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
ssize_t __uncore_umask_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
ssize_t __uncore_umask_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
ssize_t __uncore_umask_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
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
