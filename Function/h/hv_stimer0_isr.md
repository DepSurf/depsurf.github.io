# Function: <code>hv_stimer0_isr</code>

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
void hv_stimer0_isr()
```

```json
{
  "name": "hv_stimer0_isr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588005680,
      "name": "hv_stimer0_isr",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:44",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588005680,
      "name": "hv_stimer0_isr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void hv_stimer0_isr()
```

```json
{
  "name": "hv_stimer0_isr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588213248,
      "name": "hv_stimer0_isr",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:45",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588213248,
      "name": "hv_stimer0_isr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void hv_stimer0_isr()
```

```json
{
  "name": "hv_stimer0_isr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589080592,
      "name": "hv_stimer0_isr",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:55",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589080592,
      "name": "hv_stimer0_isr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void hv_stimer0_isr()
```

```json
{
  "name": "hv_stimer0_isr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589081600,
      "name": "hv_stimer0_isr",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:55",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589081600,
      "name": "hv_stimer0_isr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hv_stimer0_isr()
```

```json
{
  "name": "hv_stimer0_isr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588968053,
      "name": "hv_stimer0_isr",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:57",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer0_percpu_isr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588968000,
      "name": "hv_stimer0_isr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hv_stimer0_isr()
```

```json
{
  "name": "hv_stimer0_isr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589677941,
      "name": "hv_stimer0_isr",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:57",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer0_percpu_isr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589677888,
      "name": "hv_stimer0_isr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hv_stimer0_isr()
```

```json
{
  "name": "hv_stimer0_isr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591182725,
      "name": "hv_stimer0_isr",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:57",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer0_percpu_isr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591182672,
      "name": "hv_stimer0_isr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hv_stimer0_isr()
```

```json
{
  "name": "hv_stimer0_isr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592908949,
      "name": "hv_stimer0_isr",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:58",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer0_percpu_isr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592908880,
      "name": "hv_stimer0_isr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hv_stimer0_isr()
```

```json
{
  "name": "hv_stimer0_isr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593348485,
      "name": "hv_stimer0_isr",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:58",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer0_percpu_isr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593348416,
      "name": "hv_stimer0_isr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hv_stimer0_isr()
```

```json
{
  "name": "hv_stimer0_isr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594102485,
      "name": "hv_stimer0_isr",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:58",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer0_percpu_isr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594102416,
      "name": "hv_stimer0_isr",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void hv_stimer0_isr()
```

```json
{
  "name": "hv_stimer0_isr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587825104,
      "name": "hv_stimer0_isr",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:45",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587825104,
      "name": "hv_stimer0_isr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void hv_stimer0_isr()
```

```json
{
  "name": "hv_stimer0_isr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587534992,
      "name": "hv_stimer0_isr",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:45",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hv/vmbus_drv.c:vmbus_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587534992,
      "name": "hv_stimer0_isr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void hv_stimer0_isr()
```

```json
{
  "name": "hv_stimer0_isr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588167728,
      "name": "hv_stimer0_isr",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:45",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588167728,
      "name": "hv_stimer0_isr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void hv_stimer0_isr()
```

```json
{
  "name": "hv_stimer0_isr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588285584,
      "name": "hv_stimer0_isr",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:45",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588285584,
      "name": "hv_stimer0_isr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void hv_stimer0_isr()
```
</details>
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
void hv_stimer0_isr()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void hv_stimer0_isr()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void hv_stimer0_isr()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void hv_stimer0_isr()
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
