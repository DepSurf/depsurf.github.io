# Function: <code>ptp_find_pin</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int ptp_find_pin(struct ptp_clock * ptp, enum ptp_pin_function func, unsigned int chan)
```

```json
{
  "name": "ptp_find_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587098240,
      "name": "ptp_find_pin",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:358",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587098240,
      "name": "ptp_find_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int ptp_find_pin(struct ptp_clock * ptp, enum ptp_pin_function func, unsigned int chan)
```

```json
{
  "name": "ptp_find_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587275456,
      "name": "ptp_find_pin",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:360",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587275456,
      "name": "ptp_find_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int ptp_find_pin(struct ptp_clock * ptp, enum ptp_pin_function func, unsigned int chan)
```

```json
{
  "name": "ptp_find_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587544992,
      "name": "ptp_find_pin",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:348",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587544992,
      "name": "ptp_find_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int ptp_find_pin(struct ptp_clock * ptp, enum ptp_pin_function func, unsigned int chan)
```

```json
{
  "name": "ptp_find_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587747744,
      "name": "ptp_find_pin",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:343",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587747744,
      "name": "ptp_find_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ptp_find_pin(struct ptp_clock * ptp, enum ptp_pin_function func, unsigned int chan)
```

```json
{
  "name": "ptp_find_pin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588594071,
      "name": "ptp_find_pin",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:352",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_find_pin_unlocked"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588592000,
      "name": "ptp_find_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ptp_find_pin(struct ptp_clock * ptp, enum ptp_pin_function func, unsigned int chan)
```

```json
{
  "name": "ptp_find_pin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588617127,
      "name": "ptp_find_pin",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:352",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_find_pin_unlocked"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588615056,
      "name": "ptp_find_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int ptp_find_pin(struct ptp_clock * ptp, enum ptp_pin_function func, unsigned int chan)
```

```json
{
  "name": "ptp_find_pin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588502055,
      "name": "ptp_find_pin",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:352",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_find_pin_unlocked"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588499984,
      "name": "ptp_find_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int ptp_find_pin(struct ptp_clock * ptp, enum ptp_pin_function func, unsigned int chan)
```

```json
{
  "name": "ptp_find_pin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589171127,
      "name": "ptp_find_pin",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:376",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_find_pin_unlocked"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589168608,
      "name": "ptp_find_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int ptp_find_pin(struct ptp_clock * ptp, enum ptp_pin_function func, unsigned int chan)
```

```json
{
  "name": "ptp_find_pin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590627128,
      "name": "ptp_find_pin",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:406",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_find_pin_unlocked"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590623792,
      "name": "ptp_find_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int ptp_find_pin(struct ptp_clock * ptp, enum ptp_pin_function func, unsigned int chan)
```

```json
{
  "name": "ptp_find_pin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592290024,
      "name": "ptp_find_pin",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:403",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_find_pin_unlocked"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592286480,
      "name": "ptp_find_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int ptp_find_pin(struct ptp_clock * ptp, enum ptp_pin_function func, unsigned int chan)
```

```json
{
  "name": "ptp_find_pin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592714600,
      "name": "ptp_find_pin",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:407",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_find_pin_unlocked"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592710992,
      "name": "ptp_find_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int ptp_find_pin(struct ptp_clock * ptp, enum ptp_pin_function func, unsigned int chan)
```

```json
{
  "name": "ptp_find_pin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593461528,
      "name": "ptp_find_pin",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:447",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_find_pin_unlocked"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593457136,
      "name": "ptp_find_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int ptp_find_pin(struct ptp_clock * ptp, enum ptp_pin_function func, unsigned int chan)
```

```json
{
  "name": "ptp_find_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500933552,
      "name": "ptp_find_pin",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:343",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500933552,
      "name": "ptp_find_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int ptp_find_pin(struct ptp_clock * ptp, enum ptp_pin_function func, unsigned int chan)
```

```json
{
  "name": "ptp_find_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233443352,
      "name": "ptp_find_pin",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:343",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233443352,
      "name": "ptp_find_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int ptp_find_pin(struct ptp_clock * ptp, enum ptp_pin_function func, unsigned int chan)
```

```json
{
  "name": "ptp_find_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294388240,
      "name": "ptp_find_pin",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:343",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294388240,
      "name": "ptp_find_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int ptp_find_pin(struct ptp_clock * ptp, enum ptp_pin_function func, unsigned int chan)
```

```json
{
  "name": "ptp_find_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277699232,
      "name": "ptp_find_pin",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:343",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277699232,
      "name": "ptp_find_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int ptp_find_pin(struct ptp_clock * ptp, enum ptp_pin_function func, unsigned int chan)
```

```json
{
  "name": "ptp_find_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587388688,
      "name": "ptp_find_pin",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:343",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587388688,
      "name": "ptp_find_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int ptp_find_pin(struct ptp_clock * ptp, enum ptp_pin_function func, unsigned int chan)
```

```json
{
  "name": "ptp_find_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587156896,
      "name": "ptp_find_pin",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:343",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587156896,
      "name": "ptp_find_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int ptp_find_pin(struct ptp_clock * ptp, enum ptp_pin_function func, unsigned int chan)
```

```json
{
  "name": "ptp_find_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587703888,
      "name": "ptp_find_pin",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:343",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587703888,
      "name": "ptp_find_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int ptp_find_pin(struct ptp_clock * ptp, enum ptp_pin_function func, unsigned int chan)
```

```json
{
  "name": "ptp_find_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587816960,
      "name": "ptp_find_pin",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:343",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587816960,
      "name": "ptp_find_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int ptp_find_pin(struct ptp_clock * ptp, enum ptp_pin_function func, unsigned int chan)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
