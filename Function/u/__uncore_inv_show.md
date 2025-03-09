# Function: <code>__uncore_inv_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t __uncore_inv_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_inv_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578940912,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:193",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578946688,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:69",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578951936,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:275",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578940912,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578946688,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578951936,
      "name": "__uncore_inv_show",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t __uncore_inv_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_inv_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578937392,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:193",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578943472,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:75",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578948832,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:275",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578937392,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578943472,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578948832,
      "name": "__uncore_inv_show",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t __uncore_inv_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_inv_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578937920,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:193",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578944000,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:79",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578949632,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:335",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578937920,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578944000,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578949632,
      "name": "__uncore_inv_show",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t __uncore_inv_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_inv_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578931136,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:193",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578937088,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:79",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578942544,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:335",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578931136,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578937088,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578942544,
      "name": "__uncore_inv_show",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t __uncore_inv_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_inv_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578932624,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:194",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578939264,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:80",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578944512,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:336",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578932624,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578939264,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578944512,
      "name": "__uncore_inv_show",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t __uncore_inv_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_inv_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578936608,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:194",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578942176,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:80",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578946960,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:336",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578936608,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578942176,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578946960,
      "name": "__uncore_inv_show",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t __uncore_inv_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_inv_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578938528,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:194",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578944208,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:99",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578948960,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:336",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578938528,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578944208,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578948960,
      "name": "__uncore_inv_show",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t __uncore_inv_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_inv_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578943264,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:194",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578949808,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:115",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578955120,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:401",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578943264,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578949808,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578955120,
      "name": "__uncore_inv_show",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t __uncore_inv_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_inv_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578945712,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:194",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578952240,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:116",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578957552,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:396",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578945712,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578952240,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578957552,
      "name": "__uncore_inv_show",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t __uncore_inv_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_inv_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578952272,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:194",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578958608,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:121",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578963424,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:433",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578952272,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578958608,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578963424,
      "name": "__uncore_inv_show",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t __uncore_inv_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_inv_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578953536,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:194",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578959888,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:137",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578964688,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:462",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578953536,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578959888,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578964688,
      "name": "__uncore_inv_show",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t __uncore_inv_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_inv_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578958560,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:194",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578964928,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:159",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578969984,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:462",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578982224,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_discovery.c:323",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578958560,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578964928,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578969984,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578982224,
      "name": "__uncore_inv_show",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t __uncore_inv_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_inv_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578970704,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:194",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578977472,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:159",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578982176,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:482",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578998176,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_discovery.c:323",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578970704,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578977472,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578982176,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578998176,
      "name": "__uncore_inv_show",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t __uncore_inv_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_inv_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578981984,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:194",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578989888,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:212",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578996848,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:482",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579014352,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_discovery.c:331",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578981984,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578989888,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578996848,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579014352,
      "name": "__uncore_inv_show",
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
ssize_t __uncore_inv_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_inv_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579000976,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:194",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579009680,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:251",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579018496,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:484",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579041456,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_discovery.c:331",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579000976,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579009680,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579018496,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579041456,
      "name": "__uncore_inv_show",
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
ssize_t __uncore_inv_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_inv_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579000768,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:194",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579009728,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:251",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579018544,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:484",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579041696,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_discovery.c:351",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579000768,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579009728,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579018544,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579041696,
      "name": "__uncore_inv_show",
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
ssize_t __uncore_inv_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_inv_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579025696,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:194",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579034656,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:251",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579043472,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:484",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579066944,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_discovery.c:352",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579025696,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579034656,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579043472,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579066944,
      "name": "__uncore_inv_show",
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
ssize_t __uncore_inv_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_inv_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578945712,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:194",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578952240,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:116",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578957552,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:396",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578945712,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578952240,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578957552,
      "name": "__uncore_inv_show",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
ssize_t __uncore_inv_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_inv_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578942592,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:194",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578949504,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:116",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578955072,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:396",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578942592,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578949504,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578955072,
      "name": "__uncore_inv_show",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
ssize_t __uncore_inv_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_inv_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578945648,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:194",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578952176,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:116",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578957488,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:396",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578945648,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578952176,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578957488,
      "name": "__uncore_inv_show",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
ssize_t __uncore_inv_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```

```json
{
  "name": "__uncore_inv_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578946224,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_nhmex.c:194",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578952752,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snb.c:116",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578958064,
      "name": "__uncore_inv_show",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:396",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578946224,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578952752,
      "name": "__uncore_inv_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578958064,
      "name": "__uncore_inv_show",
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
ssize_t __uncore_inv_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
ssize_t __uncore_inv_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
ssize_t __uncore_inv_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
ssize_t __uncore_inv_show(struct kobject * kobj, struct kobj_attribute * attr, char * page)
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
