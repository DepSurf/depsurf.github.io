# Function: <code>chv_gpio_clear_triggering</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "chv_gpio_clear_triggering",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584191906,
      "name": "chv_gpio_clear_triggering",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-cherryview.c:849",
      "file": "drivers/pinctrl/intel/pinctrl-cherryview.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable"
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
  "name": "chv_gpio_clear_triggering",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584380785,
      "name": "chv_gpio_clear_triggering",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-cherryview.c:849",
      "file": "drivers/pinctrl/intel/pinctrl-cherryview.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable"
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
  "name": "chv_gpio_clear_triggering",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584515729,
      "name": "chv_gpio_clear_triggering",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-cherryview.c:851",
      "file": "drivers/pinctrl/intel/pinctrl-cherryview.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "chv_gpio_clear_triggering",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585185486,
      "name": "chv_gpio_clear_triggering",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-cherryview.c:785",
      "file": "drivers/pinctrl/intel/pinctrl-cherryview.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void chv_gpio_clear_triggering(struct intel_pinctrl * pctrl, unsigned int offset)
```

```json
{
  "name": "chv_gpio_clear_triggering",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585328000,
      "name": "chv_gpio_clear_triggering",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-cherryview.c:769",
      "file": "drivers/pinctrl/intel/pinctrl-cherryview.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585328000,
      "name": "chv_gpio_clear_triggering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void chv_gpio_clear_triggering(struct intel_pinctrl * pctrl, unsigned int offset)
```

```json
{
  "name": "chv_gpio_clear_triggering",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585212448,
      "name": "chv_gpio_clear_triggering",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-cherryview.c:769",
      "file": "drivers/pinctrl/intel/pinctrl-cherryview.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585212448,
      "name": "chv_gpio_clear_triggering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void chv_gpio_clear_triggering(struct intel_pinctrl * pctrl, unsigned int offset)
```

```json
{
  "name": "chv_gpio_clear_triggering",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585667408,
      "name": "chv_gpio_clear_triggering",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-cherryview.c:769",
      "file": "drivers/pinctrl/intel/pinctrl-cherryview.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585667408,
      "name": "chv_gpio_clear_triggering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void chv_gpio_clear_triggering(struct intel_pinctrl * pctrl, unsigned int offset)
```

```json
{
  "name": "chv_gpio_clear_triggering",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586830768,
      "name": "chv_gpio_clear_triggering",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-cherryview.c:771",
      "file": "drivers/pinctrl/intel/pinctrl-cherryview.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586830768,
      "name": "chv_gpio_clear_triggering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void chv_gpio_clear_triggering(struct intel_pinctrl * pctrl, unsigned int offset)
```

```json
{
  "name": "chv_gpio_clear_triggering",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587972576,
      "name": "chv_gpio_clear_triggering",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-cherryview.c:773",
      "file": "drivers/pinctrl/intel/pinctrl-cherryview.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587972576,
      "name": "chv_gpio_clear_triggering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void chv_gpio_clear_triggering(struct intel_pinctrl * pctrl, unsigned int offset)
```

```json
{
  "name": "chv_gpio_clear_triggering",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588247136,
      "name": "chv_gpio_clear_triggering",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-cherryview.c:773",
      "file": "drivers/pinctrl/intel/pinctrl-cherryview.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588247136,
      "name": "chv_gpio_clear_triggering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void chv_gpio_clear_triggering(struct intel_pinctrl * pctrl, unsigned int offset)
```

```json
{
  "name": "chv_gpio_clear_triggering",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588539440,
      "name": "chv_gpio_clear_triggering",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-cherryview.c:718",
      "file": "drivers/pinctrl/intel/pinctrl-cherryview.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588539440,
      "name": "chv_gpio_clear_triggering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "chv_gpio_clear_triggering",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584410785,
      "name": "chv_gpio_clear_triggering",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-cherryview.c:851",
      "file": "drivers/pinctrl/intel/pinctrl-cherryview.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable"
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
  "name": "chv_gpio_clear_triggering",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584467393,
      "name": "chv_gpio_clear_triggering",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-cherryview.c:851",
      "file": "drivers/pinctrl/intel/pinctrl-cherryview.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable"
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
  "name": "chv_gpio_clear_triggering",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584573521,
      "name": "chv_gpio_clear_triggering",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-cherryview.c:851",
      "file": "drivers/pinctrl/intel/pinctrl-cherryview.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void chv_gpio_clear_triggering(struct intel_pinctrl * pctrl, unsigned int offset)
```
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
