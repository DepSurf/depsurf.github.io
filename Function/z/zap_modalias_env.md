# Function: <code>zap_modalias_env</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zap_modalias_env",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588763996,
      "name": "zap_modalias_env",
      "external": false,
      "loc": "lib/kobject_uevent.c:346",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
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
  "name": "zap_modalias_env",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "zap_modalias_env",
      "external": false,
      "loc": "lib/kobject_uevent.c:416",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
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
  "name": "zap_modalias_env",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "zap_modalias_env",
      "external": false,
      "loc": "lib/kobject_uevent.c:418",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
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
  "name": "zap_modalias_env",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "zap_modalias_env",
      "external": false,
      "loc": "lib/kobject_uevent.c:418",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
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
  "name": "zap_modalias_env",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "zap_modalias_env",
      "external": false,
      "loc": "lib/kobject_uevent.c:418",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
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
void zap_modalias_env(struct kobj_uevent_env * env)
```

```json
{
  "name": "zap_modalias_env",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585054288,
      "name": "zap_modalias_env",
      "external": false,
      "loc": "lib/kobject_uevent.c:418",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585054288,
      "name": "zap_modalias_env",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void zap_modalias_env(struct kobj_uevent_env * env)
```

```json
{
  "name": "zap_modalias_env",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585203776,
      "name": "zap_modalias_env",
      "external": false,
      "loc": "lib/kobject_uevent.c:418",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585203776,
      "name": "zap_modalias_env",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
void zap_modalias_env(struct kobj_uevent_env * env)
```

```json
{
  "name": "zap_modalias_env",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585086848,
      "name": "zap_modalias_env",
      "external": false,
      "loc": "lib/kobject_uevent.c:419",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585086848,
      "name": "zap_modalias_env",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
void zap_modalias_env(struct kobj_uevent_env * env)
```

```json
{
  "name": "zap_modalias_env",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585533776,
      "name": "zap_modalias_env",
      "external": false,
      "loc": "lib/kobject_uevent.c:419",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585533776,
      "name": "zap_modalias_env",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
void zap_modalias_env(struct kobj_uevent_env * env)
```

```json
{
  "name": "zap_modalias_env",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586687696,
      "name": "zap_modalias_env",
      "external": false,
      "loc": "lib/kobject_uevent.c:419",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586687696,
      "name": "zap_modalias_env",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 840
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
void zap_modalias_env(struct kobj_uevent_env * env)
```

```json
{
  "name": "zap_modalias_env",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595769920,
      "name": "zap_modalias_env",
      "external": false,
      "loc": "lib/kobject_uevent.c:419",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595769920,
      "name": "zap_modalias_env",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 779
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
void zap_modalias_env(struct kobj_uevent_env * env)
```

```json
{
  "name": "zap_modalias_env",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596294464,
      "name": "zap_modalias_env",
      "external": false,
      "loc": "lib/kobject_uevent.c:419",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596294464,
      "name": "zap_modalias_env",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 785
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
void zap_modalias_env(struct kobj_uevent_env * env)
```

```json
{
  "name": "zap_modalias_env",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597179408,
      "name": "zap_modalias_env",
      "external": false,
      "loc": "lib/kobject_uevent.c:419",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597179408,
      "name": "zap_modalias_env",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 785
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
  "name": "zap_modalias_env",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "zap_modalias_env",
      "external": false,
      "loc": "lib/kobject_uevent.c:418",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
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
  "name": "zap_modalias_env",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236456176,
      "name": "zap_modalias_env",
      "external": false,
      "loc": "lib/kobject_uevent.c:418",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
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
  "name": "zap_modalias_env",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "zap_modalias_env",
      "external": false,
      "loc": "lib/kobject_uevent.c:418",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
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
  "name": "zap_modalias_env",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279729492,
      "name": "zap_modalias_env",
      "external": false,
      "loc": "lib/kobject_uevent.c:418",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
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
  "name": "zap_modalias_env",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "zap_modalias_env",
      "external": false,
      "loc": "lib/kobject_uevent.c:418",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
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
  "name": "zap_modalias_env",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "zap_modalias_env",
      "external": false,
      "loc": "lib/kobject_uevent.c:418",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
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
  "name": "zap_modalias_env",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "zap_modalias_env",
      "external": false,
      "loc": "lib/kobject_uevent.c:418",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
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
  "name": "zap_modalias_env",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "zap_modalias_env",
      "external": false,
      "loc": "lib/kobject_uevent.c:418",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
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
void zap_modalias_env(struct kobj_uevent_env * env)
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
