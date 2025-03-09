# Function: <code>event_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578877664,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:452",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578878688,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:245",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578885152,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/msr.c:95",
      "file": "arch/x86/events/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578888976,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2747",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578900672,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/cqm.c:1489",
      "file": "arch/x86/events/intel/cqm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578914912,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:272",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578923680,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:183",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578877664,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578878688,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578885152,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578888976,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578900672,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578914912,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578923680,
      "name": "event_show",
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
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578878176,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:452",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578880016,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:247",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578885824,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/msr.c:116",
      "file": "arch/x86/events/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578889376,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3030",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578901152,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/cqm.c:1496",
      "file": "arch/x86/events/intel/cqm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578913184,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:274",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578921968,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:183",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578878176,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578880016,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578885824,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578889376,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578901152,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578913184,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578921968,
      "name": "event_show",
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
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578878208,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:452",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578880080,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:247",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578885888,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/msr.c:116",
      "file": "arch/x86/events/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578889440,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3045",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578901344,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/cqm.c:1477",
      "file": "arch/x86/events/intel/cqm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578913616,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:274",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578922208,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:183",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578878208,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578880080,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578885888,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578889440,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578901344,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578913616,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578922208,
      "name": "event_show",
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
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578877408,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:452",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578879232,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:286",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578887088,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/msr.c:116",
      "file": "arch/x86/events/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578888912,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3198",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578907024,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:274",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578915440,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:183",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578877408,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578879232,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578887088,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578888912,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578907024,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578915440,
      "name": "event_show",
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
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578878560,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:452",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578880400,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:286",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578888336,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/msr.c:125",
      "file": "arch/x86/events/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578890176,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3202",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578908848,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:275",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578917360,
      "name": "event_show",
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
      "addr": 18446744071578878560,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578880400,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578888336,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578890176,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578908848,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578917360,
      "name": "event_show",
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
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578880544,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:452",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578882240,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:287",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578890176,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/msr.c:139",
      "file": "arch/x86/events/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578892512,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3221",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578911216,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:275",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578919872,
      "name": "event_show",
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
      "addr": 18446744071578880544,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578882240,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578890176,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578892512,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578911216,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578919872,
      "name": "event_show",
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
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578880320,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:452",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578882336,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:295",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578889968,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/msr.c:139",
      "file": "arch/x86/events/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578892704,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3436",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578912784,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:275",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578921536,
      "name": "event_show",
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
      "addr": 18446744071578880320,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578882336,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578889968,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578892704,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578912784,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578921536,
      "name": "event_show",
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
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578880928,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:704",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578883504,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:294",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578891232,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/msr.c:154",
      "file": "arch/x86/events/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578894624,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3580",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578917328,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:275",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578926560,
      "name": "event_show",
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
      "addr": 18446744071578880928,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578883504,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578891232,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578894624,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578917328,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578926560,
      "name": "event_show",
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
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578881728,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:724",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578884528,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:291",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578892272,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/msr.c:162",
      "file": "arch/x86/events/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578895664,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3588",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578919312,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:275",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578928528,
      "name": "event_show",
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
      "addr": 18446744071578881728,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578884528,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578892272,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578895664,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578919312,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578928528,
      "name": "event_show",
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
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578886144,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:715",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578888464,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:309",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578897120,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/msr.c:162",
      "file": "arch/x86/events/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578900192,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3619",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578924432,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:275",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578934192,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:184",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578973904,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/zhaoxin/core.c:437",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578886144,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578888464,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578897120,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578900192,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578924432,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578934192,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578973904,
      "name": "event_show",
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
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578881664,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:715",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578892848,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/msr.c:164",
      "file": "arch/x86/events/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578896192,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3962",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578923328,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:275",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578935376,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:184",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578976624,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/zhaoxin/core.c:437",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578881664,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578892848,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578896192,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578923328,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578935376,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578976624,
      "name": "event_show",
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
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578884128,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:715",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578895312,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/msr.c:166",
      "file": "arch/x86/events/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578898784,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4184",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578927952,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:275",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578940224,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:184",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578985712,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/zhaoxin/core.c:437",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578884128,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578895312,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578898784,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578927952,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578940224,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578985712,
      "name": "event_show",
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
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578888176,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:715",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578896640,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/msr.c:167",
      "file": "arch/x86/events/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578899968,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4191",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578932944,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:275",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578947824,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:184",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579001680,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/zhaoxin/core.c:437",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578888176,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578896640,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578899968,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578932944,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578947824,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579001680,
      "name": "event_show",
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
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578885760,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:1013",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578900064,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/msr.c:170",
      "file": "arch/x86/events/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578904496,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4253",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578941248,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:275",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578956512,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:184",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578958992,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:115",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579018240,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/zhaoxin/core.c:437",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589170992,
      "name": "event_show",
      "external": false,
      "loc": "drivers/nvdimm/nd_perf.c:96",
      "file": "drivers/nvdimm/nd_perf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578885760,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071578900064,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578904496,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578941248,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578956512,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578958992,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579018240,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071589170992,
      "name": "event_show",
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
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578892672,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:988",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578912848,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/msr.c:174",
      "file": "arch/x86/events/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578918368,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4379",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578958224,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:275",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578973392,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:184",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578976208,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:115",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579045824,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/zhaoxin/core.c:437",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590723376,
      "name": "event_show",
      "external": false,
      "loc": "drivers/nvdimm/nd_perf.c:96",
      "file": "drivers/nvdimm/nd_perf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578892672,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071578912848,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578918368,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578958224,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578973392,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578976208,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579045824,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071590723376,
      "name": "event_show",
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
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578890512,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:985",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578910480,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/msr.c:176",
      "file": "arch/x86/events/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578915952,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4488",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578957408,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:275",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578972640,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:184",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578975520,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:115",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579045840,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/zhaoxin/core.c:437",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590489168,
      "name": "event_show",
      "external": false,
      "loc": "drivers/iommu/intel/perfmon.c:13",
      "file": "drivers/iommu/intel/perfmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591064688,
      "name": "event_show",
      "external": false,
      "loc": "drivers/nvdimm/nd_perf.c:96",
      "file": "drivers/nvdimm/nd_perf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578890512,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071578910480,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578915952,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578957408,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578972640,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578975520,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579045840,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071590489168,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071591064688,
      "name": "event_show",
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
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578912912,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:995",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578932816,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/msr.c:176",
      "file": "arch/x86/events/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578938304,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4568",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578980800,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:275",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578997408,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/p6.c:184",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579000288,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:115",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579071184,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/zhaoxin/core.c:437",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590840192,
      "name": "event_show",
      "external": false,
      "loc": "drivers/iommu/intel/perfmon.c:13",
      "file": "drivers/iommu/intel/perfmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591409440,
      "name": "event_show",
      "external": false,
      "loc": "drivers/nvdimm/nd_perf.c:96",
      "file": "drivers/nvdimm/nd_perf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578912912,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071578932816,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578938304,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578980800,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578997408,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579000288,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579071184,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071590840192,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071591409440,
      "name": "event_show",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490302536,
      "name": "event_show",
      "external": false,
      "loc": "arch/arm64/kernel/perf_event.c:320",
      "file": "arch/arm64/kernel/perf_event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501791320,
      "name": "event_show",
      "external": false,
      "loc": "drivers/perf/qcom_l2_pmu.c:701",
      "file": "drivers/perf/qcom_l2_pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490302536,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446603336501791320,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224473868,
      "name": "event_show",
      "external": false,
      "loc": "arch/arm/kernel/perf_event_v7.c:535",
      "file": "arch/arm/kernel/perf_event_v7.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3224580412,
      "name": "event_show",
      "external": false,
      "loc": "arch/arm/mach-imx/mmdc.c:161",
      "file": "arch/arm/mach-imx/mmdc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224473868,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 3224580412,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283385760,
      "name": "event_show",
      "external": false,
      "loc": "arch/powerpc/perf/imc-pmu.c:52",
      "file": "arch/powerpc/perf/imc-pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283428240,
      "name": "event_show",
      "external": false,
      "loc": "arch/powerpc/perf/power7-pmu.c:409",
      "file": "arch/powerpc/perf/power7-pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283429456,
      "name": "event_show",
      "external": false,
      "loc": "arch/powerpc/perf/isa207-common.c:11",
      "file": "arch/powerpc/perf/isa207-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283433760,
      "name": "event_show",
      "external": false,
      "loc": "arch/powerpc/perf/power9-pmu.c:211",
      "file": "arch/powerpc/perf/power9-pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283434864,
      "name": "event_show",
      "external": false,
      "loc": "arch/powerpc/perf/generic-compat-pmu.c:64",
      "file": "arch/powerpc/perf/generic-compat-pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283385760,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 13835058055283428240,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 13835058055283429456,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 13835058055283433760,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 13835058055283434864,
      "name": "event_show",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578881728,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:724",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578884528,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:291",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578892272,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/msr.c:162",
      "file": "arch/x86/events/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578895664,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3588",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578919312,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:275",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578928528,
      "name": "event_show",
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
      "addr": 18446744071578881728,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578884528,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578892272,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578895664,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578919312,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578928528,
      "name": "event_show",
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
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578875600,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:724",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578878288,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:291",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578886528,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/msr.c:162",
      "file": "arch/x86/events/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578889568,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3588",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578914704,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:275",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578925072,
      "name": "event_show",
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
      "addr": 18446744071578875600,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578878288,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578886528,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578889568,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578914704,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578925072,
      "name": "event_show",
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
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578881664,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:724",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578884464,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:291",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578892208,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/msr.c:162",
      "file": "arch/x86/events/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578895600,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3588",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578919248,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:275",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578928464,
      "name": "event_show",
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
      "addr": 18446744071578881664,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578884464,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578892208,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578895600,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578919248,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578928464,
      "name": "event_show",
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
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "event_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578882016,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:724",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578884816,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:291",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578892688,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/msr.c:162",
      "file": "arch/x86/events/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578896160,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3588",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578919792,
      "name": "event_show",
      "external": false,
      "loc": "arch/x86/events/intel/knc.c:275",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578929040,
      "name": "event_show",
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
      "addr": 18446744071578882016,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578884816,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071578892688,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071578896160,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578919792,
      "name": "event_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071578929040,
      "name": "event_show",
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
ssize_t event_show(struct device * dev, struct device_attribute * attr, char * page)
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
