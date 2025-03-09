# Function: <code>pwm_class_get_state</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pwm_export * pwm_class_get_state(struct device * parent, struct pwm_device * pwm, struct pwm_state * state)
```

```json
{
  "name": "pwm_class_get_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584440576,
      "name": "pwm_class_get_state",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:377",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_suspend",
        "drivers/pwm/sysfs.c:pwm_class_resume_npwm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584440576,
      "name": "pwm_class_get_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
struct pwm_export * pwm_class_get_state(struct device * parent, struct pwm_device * pwm, struct pwm_state * state)
```

```json
{
  "name": "pwm_class_get_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584577312,
      "name": "pwm_class_get_state",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:377",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_suspend",
        "drivers/pwm/sysfs.c:pwm_class_resume_npwm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584577312,
      "name": "pwm_class_get_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pwm_class_get_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585255475,
      "name": "pwm_class_get_state",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:377",
      "file": "drivers/pwm/sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_class_suspend",
        "drivers/pwm/sysfs.c:pwm_class_resume_npwm"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pwm_class_get_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585412981,
      "name": "pwm_class_get_state",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:377",
      "file": "drivers/pwm/sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_class_suspend",
        "drivers/pwm/sysfs.c:pwm_class_resume_npwm"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pwm_class_get_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585293717,
      "name": "pwm_class_get_state",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:377",
      "file": "drivers/pwm/sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_class_suspend",
        "drivers/pwm/sysfs.c:pwm_class_resume_npwm"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pwm_class_get_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585750501,
      "name": "pwm_class_get_state",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:377",
      "file": "drivers/pwm/sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_class_suspend",
        "drivers/pwm/sysfs.c:pwm_class_resume_npwm"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pwm_class_get_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586933754,
      "name": "pwm_class_get_state",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:377",
      "file": "drivers/pwm/sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_class_suspend",
        "drivers/pwm/sysfs.c:pwm_class_resume_npwm"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pwm_export * pwm_class_get_state(struct device * parent, struct pwm_device * pwm, struct pwm_state * state)
```

```json
{
  "name": "pwm_class_get_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588086992,
      "name": "pwm_class_get_state",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:377",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_suspend",
        "drivers/pwm/sysfs.c:pwm_class_resume_npwm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588086992,
      "name": "pwm_class_get_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
struct pwm_export * pwm_class_get_state(struct device * parent, struct pwm_device * pwm, struct pwm_state * state)
```

```json
{
  "name": "pwm_class_get_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588361328,
      "name": "pwm_class_get_state",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:377",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_suspend",
        "drivers/pwm/sysfs.c:pwm_class_resume_npwm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588361328,
      "name": "pwm_class_get_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
struct pwm_export * pwm_class_get_state(struct device * parent, struct pwm_device * pwm, struct pwm_state * state)
```

```json
{
  "name": "pwm_class_get_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588656048,
      "name": "pwm_class_get_state",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:377",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_suspend",
        "drivers/pwm/sysfs.c:pwm_class_resume_npwm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588656048,
      "name": "pwm_class_get_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
struct pwm_export * pwm_class_get_state(struct device * parent, struct pwm_device * pwm, struct pwm_state * state)
```

```json
{
  "name": "pwm_class_get_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496812368,
      "name": "pwm_class_get_state",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:377",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_suspend",
        "drivers/pwm/sysfs.c:pwm_class_resume_npwm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496812368,
      "name": "pwm_class_get_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct pwm_export * pwm_class_get_state(struct device * parent, struct pwm_device * pwm, struct pwm_state * state)
```

```json
{
  "name": "pwm_class_get_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230096356,
      "name": "pwm_class_get_state",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:377",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_suspend",
        "drivers/pwm/sysfs.c:pwm_class_resume_npwm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230096356,
      "name": "pwm_class_get_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
struct pwm_export * pwm_class_get_state(struct device * parent, struct pwm_device * pwm, struct pwm_state * state)
```

```json
{
  "name": "pwm_class_get_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290882352,
      "name": "pwm_class_get_state",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:377",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_suspend",
        "drivers/pwm/sysfs.c:pwm_class_resume_npwm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290882352,
      "name": "pwm_class_get_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
struct pwm_export * pwm_class_get_state(struct device * parent, struct pwm_device * pwm, struct pwm_state * state)
```

```json
{
  "name": "pwm_class_get_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584531760,
      "name": "pwm_class_get_state",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:377",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_suspend",
        "drivers/pwm/sysfs.c:pwm_class_resume_npwm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584531760,
      "name": "pwm_class_get_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pwm_export * pwm_class_get_state(struct device * parent, struct pwm_device * pwm, struct pwm_state * state)
```

```json
{
  "name": "pwm_class_get_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584527472,
      "name": "pwm_class_get_state",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:377",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_suspend",
        "drivers/pwm/sysfs.c:pwm_class_resume_npwm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584527472,
      "name": "pwm_class_get_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
struct pwm_export * pwm_class_get_state(struct device * parent, struct pwm_device * pwm, struct pwm_state * state)
```

```json
{
  "name": "pwm_class_get_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584635248,
      "name": "pwm_class_get_state",
      "external": false,
      "loc": "drivers/pwm/sysfs.c:377",
      "file": "drivers/pwm/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_suspend",
        "drivers/pwm/sysfs.c:pwm_class_resume_npwm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584635248,
      "name": "pwm_class_get_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct pwm_export * pwm_class_get_state(struct device * parent, struct pwm_device * pwm, struct pwm_state * state)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct pwm_export * pwm_class_get_state(struct device * parent, struct pwm_device * pwm, struct pwm_state * state)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct pwm_export * pwm_class_get_state(struct device * parent, struct pwm_device * pwm, struct pwm_state * state)
```
</details>
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
struct pwm_export * pwm_class_get_state(struct device * parent, struct pwm_device * pwm, struct pwm_state * state)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct pwm_export * pwm_class_get_state(struct device * parent, struct pwm_device * pwm, struct pwm_state * state)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
