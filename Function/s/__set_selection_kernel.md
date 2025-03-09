# Function: <code>__set_selection_kernel</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int __set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "__set_selection_kernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_selection_kernel",
      "external": false,
      "loc": "drivers/tty/vt/selection.c:189",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585745344,
      "name": "__set_selection_kernel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1578
    },
    {
      "addr": 18446744071585747270,
      "name": "__set_selection_kernel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "__set_selection_kernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498449608,
      "name": "__set_selection_kernel",
      "external": false,
      "loc": "drivers/tty/vt/selection.c:189",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498449608,
      "name": "__set_selection_kernel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1684
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
int __set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "__set_selection_kernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231113128,
      "name": "__set_selection_kernel",
      "external": false,
      "loc": "drivers/tty/vt/selection.c:189",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231113128,
      "name": "__set_selection_kernel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1708
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
int __set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "__set_selection_kernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291635792,
      "name": "__set_selection_kernel",
      "external": false,
      "loc": "drivers/tty/vt/selection.c:189",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291635792,
      "name": "__set_selection_kernel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2320
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
int __set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "__set_selection_kernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276093702,
      "name": "__set_selection_kernel",
      "external": false,
      "loc": "drivers/tty/vt/selection.c:189",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276093702,
      "name": "__set_selection_kernel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1654
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int __set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "__set_selection_kernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_selection_kernel",
      "external": false,
      "loc": "drivers/tty/vt/selection.c:189",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585506368,
      "name": "__set_selection_kernel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1578
    },
    {
      "addr": 18446744071585508294,
      "name": "__set_selection_kernel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int __set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "__set_selection_kernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_selection_kernel",
      "external": false,
      "loc": "drivers/tty/vt/selection.c:189",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585376192,
      "name": "__set_selection_kernel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1578
    },
    {
      "addr": 18446744071585378118,
      "name": "__set_selection_kernel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int __set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "__set_selection_kernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_selection_kernel",
      "external": false,
      "loc": "drivers/tty/vt/selection.c:189",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585695744,
      "name": "__set_selection_kernel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1578
    },
    {
      "addr": 18446744071585697670,
      "name": "__set_selection_kernel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int __set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "__set_selection_kernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_selection_kernel",
      "external": false,
      "loc": "drivers/tty/vt/selection.c:189",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585803760,
      "name": "__set_selection_kernel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1578
    },
    {
      "addr": 18446744071585805686,
      "name": "__set_selection_kernel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int __set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int __set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```
</details>
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
