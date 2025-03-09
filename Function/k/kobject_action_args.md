# Function: <code>kobject_action_args</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kobject_action_args",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588215328,
      "name": "kobject_action_args",
      "external": false,
      "loc": "lib/kobject_uevent.c:109",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kobject_action_args",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588765280,
      "name": "kobject_action_args",
      "external": false,
      "loc": "lib/kobject_uevent.c:111",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kobject_action_args",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589144127,
      "name": "kobject_action_args",
      "external": false,
      "loc": "lib/kobject_uevent.c:114",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kobject_action_args",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589378991,
      "name": "kobject_action_args",
      "external": false,
      "loc": "lib/kobject_uevent.c:114",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kobject_action_args",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589836173,
      "name": "kobject_action_args",
      "external": false,
      "loc": "lib/kobject_uevent.c:114",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kobject_action_args",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590062317,
      "name": "kobject_action_args",
      "external": false,
      "loc": "lib/kobject_uevent.c:114",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int kobject_action_args(const char * buf, size_t count, struct kobj_uevent_env * * ret_env)
```

```json
{
  "name": "kobject_action_args",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585057456,
      "name": "kobject_action_args",
      "external": false,
      "loc": "lib/kobject_uevent.c:114",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585057456,
      "name": "kobject_action_args",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
int kobject_action_args(const char * buf, size_t count, struct kobj_uevent_env * * ret_env)
```

```json
{
  "name": "kobject_action_args",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585206928,
      "name": "kobject_action_args",
      "external": false,
      "loc": "lib/kobject_uevent.c:114",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585206928,
      "name": "kobject_action_args",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
int kobject_action_args(const char * buf, size_t count, struct kobj_uevent_env * * ret_env)
```

```json
{
  "name": "kobject_action_args",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585089872,
      "name": "kobject_action_args",
      "external": false,
      "loc": "lib/kobject_uevent.c:114",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585089872,
      "name": "kobject_action_args",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 398
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
int kobject_action_args(const char * buf, size_t count, struct kobj_uevent_env * * ret_env)
```

```json
{
  "name": "kobject_action_args",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585537312,
      "name": "kobject_action_args",
      "external": false,
      "loc": "lib/kobject_uevent.c:114",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585537312,
      "name": "kobject_action_args",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 398
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
int kobject_action_args(const char * buf, size_t count, struct kobj_uevent_env * * ret_env)
```

```json
{
  "name": "kobject_action_args",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586691632,
      "name": "kobject_action_args",
      "external": false,
      "loc": "lib/kobject_uevent.c:114",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586691632,
      "name": "kobject_action_args",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
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
int kobject_action_args(const char * buf, size_t count, struct kobj_uevent_env * * ret_env)
```

```json
{
  "name": "kobject_action_args",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595773072,
      "name": "kobject_action_args",
      "external": false,
      "loc": "lib/kobject_uevent.c:114",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595773072,
      "name": "kobject_action_args",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
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
int kobject_action_args(const char * buf, size_t count, struct kobj_uevent_env * * ret_env)
```

```json
{
  "name": "kobject_action_args",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596297632,
      "name": "kobject_action_args",
      "external": false,
      "loc": "lib/kobject_uevent.c:114",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596297632,
      "name": "kobject_action_args",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
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
int kobject_action_args(const char * buf, size_t count, struct kobj_uevent_env * * ret_env)
```

```json
{
  "name": "kobject_action_args",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597182672,
      "name": "kobject_action_args",
      "external": false,
      "loc": "lib/kobject_uevent.c:114",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597182672,
      "name": "kobject_action_args",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "kobject_action_args",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503839760,
      "name": "kobject_action_args",
      "external": false,
      "loc": "lib/kobject_uevent.c:114",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "kobject_action_args",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236458480,
      "name": "kobject_action_args",
      "external": false,
      "loc": "lib/kobject_uevent.c:114",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "kobject_action_args",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297690088,
      "name": "kobject_action_args",
      "external": false,
      "loc": "lib/kobject_uevent.c:114",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "kobject_action_args",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279730748,
      "name": "kobject_action_args",
      "external": false,
      "loc": "lib/kobject_uevent.c:114",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kobject_action_args",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589664573,
      "name": "kobject_action_args",
      "external": false,
      "loc": "lib/kobject_uevent.c:114",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kobject_action_args",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589390397,
      "name": "kobject_action_args",
      "external": false,
      "loc": "lib/kobject_uevent.c:114",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kobject_action_args",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590107949,
      "name": "kobject_action_args",
      "external": false,
      "loc": "lib/kobject_uevent.c:114",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kobject_action_args",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590158253,
      "name": "kobject_action_args",
      "external": false,
      "loc": "lib/kobject_uevent.c:114",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int kobject_action_args(const char * buf, size_t count, struct kobj_uevent_env * * ret_env)
```
</details>
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
