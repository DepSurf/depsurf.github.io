# Function: <code>hungtask_pm_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hungtask_pm_notify(struct notifier_block * self, long unsigned int action, void * hcpu)
```

```json
{
  "name": "hungtask_pm_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580379504,
      "name": "hungtask_pm_notify",
      "external": false,
      "loc": "kernel/hung_task.c:246",
      "file": "kernel/hung_task.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580379504,
      "name": "hungtask_pm_notify",
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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int hungtask_pm_notify(struct notifier_block * self, long unsigned int action, void * hcpu)
```

```json
{
  "name": "hungtask_pm_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580432224,
      "name": "hungtask_pm_notify",
      "external": false,
      "loc": "kernel/hung_task.c:248",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580432224,
      "name": "hungtask_pm_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int hungtask_pm_notify(struct notifier_block * self, long unsigned int action, void * hcpu)
```

```json
{
  "name": "hungtask_pm_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580480976,
      "name": "hungtask_pm_notify",
      "external": false,
      "loc": "kernel/hung_task.c:248",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580480976,
      "name": "hungtask_pm_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int hungtask_pm_notify(struct notifier_block * self, long unsigned int action, void * hcpu)
```

```json
{
  "name": "hungtask_pm_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580565648,
      "name": "hungtask_pm_notify",
      "external": false,
      "loc": "kernel/hung_task.c:254",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580565648,
      "name": "hungtask_pm_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int hungtask_pm_notify(struct notifier_block * self, long unsigned int action, void * hcpu)
```

```json
{
  "name": "hungtask_pm_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580553712,
      "name": "hungtask_pm_notify",
      "external": false,
      "loc": "kernel/hung_task.c:253",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580553712,
      "name": "hungtask_pm_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int hungtask_pm_notify(struct notifier_block * self, long unsigned int action, void * hcpu)
```

```json
{
  "name": "hungtask_pm_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580556880,
      "name": "hungtask_pm_notify",
      "external": false,
      "loc": "kernel/hung_task.c:253",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580556880,
      "name": "hungtask_pm_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int hungtask_pm_notify(struct notifier_block * self, long unsigned int action, void * hcpu)
```

```json
{
  "name": "hungtask_pm_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580726800,
      "name": "hungtask_pm_notify",
      "external": false,
      "loc": "kernel/hung_task.c:254",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580726800,
      "name": "hungtask_pm_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int hungtask_pm_notify(struct notifier_block * self, long unsigned int action, void * hcpu)
```

```json
{
  "name": "hungtask_pm_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580938976,
      "name": "hungtask_pm_notify",
      "external": false,
      "loc": "kernel/hung_task.c:328",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580938976,
      "name": "hungtask_pm_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
int hungtask_pm_notify(struct notifier_block * self, long unsigned int action, void * hcpu)
```

```json
{
  "name": "hungtask_pm_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581232144,
      "name": "hungtask_pm_notify",
      "external": false,
      "loc": "kernel/hung_task.c:336",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581232144,
      "name": "hungtask_pm_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
int hungtask_pm_notify(struct notifier_block * self, long unsigned int action, void * hcpu)
```

```json
{
  "name": "hungtask_pm_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581326464,
      "name": "hungtask_pm_notify",
      "external": false,
      "loc": "kernel/hung_task.c:338",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581326464,
      "name": "hungtask_pm_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
int hungtask_pm_notify(struct notifier_block * self, long unsigned int action, void * hcpu)
```

```json
{
  "name": "hungtask_pm_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581432768,
      "name": "hungtask_pm_notify",
      "external": false,
      "loc": "kernel/hung_task.c:338",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581432768,
      "name": "hungtask_pm_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
int hungtask_pm_notify(struct notifier_block * self, long unsigned int action, void * hcpu)
```

```json
{
  "name": "hungtask_pm_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491756696,
      "name": "hungtask_pm_notify",
      "external": false,
      "loc": "kernel/hung_task.c:248",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491756696,
      "name": "hungtask_pm_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int hungtask_pm_notify(struct notifier_block * self, long unsigned int action, void * hcpu)
```

```json
{
  "name": "hungtask_pm_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225704988,
      "name": "hungtask_pm_notify",
      "external": false,
      "loc": "kernel/hung_task.c:248",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225704988,
      "name": "hungtask_pm_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int hungtask_pm_notify(struct notifier_block * self, long unsigned int action, void * hcpu)
```

```json
{
  "name": "hungtask_pm_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284797728,
      "name": "hungtask_pm_notify",
      "external": false,
      "loc": "kernel/hung_task.c:248",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284797728,
      "name": "hungtask_pm_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int hungtask_pm_notify(struct notifier_block * self, long unsigned int action, void * hcpu)
```

```json
{
  "name": "hungtask_pm_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580449776,
      "name": "hungtask_pm_notify",
      "external": false,
      "loc": "kernel/hung_task.c:248",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580449776,
      "name": "hungtask_pm_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
int hungtask_pm_notify(struct notifier_block * self, long unsigned int action, void * hcpu)
```

```json
{
  "name": "hungtask_pm_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580396848,
      "name": "hungtask_pm_notify",
      "external": false,
      "loc": "kernel/hung_task.c:248",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580396848,
      "name": "hungtask_pm_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int hungtask_pm_notify(struct notifier_block * self, long unsigned int action, void * hcpu)
```

```json
{
  "name": "hungtask_pm_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580441024,
      "name": "hungtask_pm_notify",
      "external": false,
      "loc": "kernel/hung_task.c:248",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580441024,
      "name": "hungtask_pm_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int hungtask_pm_notify(struct notifier_block * self, long unsigned int action, void * hcpu)
```

```json
{
  "name": "hungtask_pm_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580496656,
      "name": "hungtask_pm_notify",
      "external": false,
      "loc": "kernel/hung_task.c:248",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580496656,
      "name": "hungtask_pm_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int hungtask_pm_notify(struct notifier_block * self, long unsigned int action, void * hcpu)
```
</details>
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
int hungtask_pm_notify(struct notifier_block * self, long unsigned int action, void * hcpu)
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
