# Function: <code>of_setup_earlycon</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int of_setup_earlycon(long unsigned int addr, int (*)(struct earlycon_device *, const char *) setup)
```

```json
{
  "name": "of_setup_earlycon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595257824,
      "name": "of_setup_earlycon",
      "external": true,
      "loc": "drivers/tty/serial/earlycon.c:200",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595257824,
      "name": "of_setup_earlycon",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
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
int of_setup_earlycon(const struct earlycon_id * match, long unsigned int node, const char * options)
```

```json
{
  "name": "of_setup_earlycon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511209728,
      "name": "of_setup_earlycon",
      "external": true,
      "loc": "drivers/tty/serial/earlycon.c:231",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:early_init_dt_scan_chosen_stdout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511209728,
      "name": "of_setup_earlycon",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 584
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
int of_setup_earlycon(const struct earlycon_id * match, long unsigned int node, const char * options)
```

```json
{
  "name": "of_setup_earlycon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243854276,
      "name": "of_setup_earlycon",
      "external": true,
      "loc": "drivers/tty/serial/earlycon.c:231",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:early_init_dt_scan_chosen_stdout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243854276,
      "name": "of_setup_earlycon",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 624
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
int of_setup_earlycon(const struct earlycon_id * match, long unsigned int node, const char * options)
```

```json
{
  "name": "of_setup_earlycon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302772136,
      "name": "of_setup_earlycon",
      "external": true,
      "loc": "drivers/tty/serial/earlycon.c:231",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:early_init_dt_scan_chosen_stdout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302772136,
      "name": "of_setup_earlycon",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 836
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
int of_setup_earlycon(const struct earlycon_id * match, long unsigned int node, const char * options)
```

```json
{
  "name": "of_setup_earlycon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270790124,
      "name": "of_setup_earlycon",
      "external": true,
      "loc": "drivers/tty/serial/earlycon.c:231",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:early_init_dt_scan_chosen_stdout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270790124,
      "name": "of_setup_earlycon",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 650
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
int of_setup_earlycon(long unsigned int addr, int (*)(struct earlycon_device *, const char *) setup)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int of_setup_earlycon(const struct earlycon_id * match, long unsigned int node, const char * options)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int of_setup_earlycon(const struct earlycon_id * match, long unsigned int node, const char * options)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int of_setup_earlycon(const struct earlycon_id * match, long unsigned int node, const char * options)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int of_setup_earlycon(const struct earlycon_id * match, long unsigned int node, const char * options)
```
</details>
</li>
</ul>
