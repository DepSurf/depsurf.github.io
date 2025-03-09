# Function: <code>of_platform_serial_setup</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "of_platform_serial_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498622256,
      "name": "of_platform_serial_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_of.c:54",
      "file": "drivers/tty/serial/8250/8250_of.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498622256,
      "name": "of_platform_serial_setup.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1164
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
int of_platform_serial_setup(struct platform_device * ofdev, int type, struct uart_port * port, struct of_serial_info * info)
```

```json
{
  "name": "of_platform_serial_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231244956,
      "name": "of_platform_serial_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_of.c:54",
      "file": "drivers/tty/serial/8250/8250_of.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231244956,
      "name": "of_platform_serial_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "of_platform_serial_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291842128,
      "name": "of_platform_serial_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_of.c:54",
      "file": "drivers/tty/serial/8250/8250_of.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291842128,
      "name": "of_platform_serial_setup.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "of_platform_serial_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276208222,
      "name": "of_platform_serial_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_of.c:54",
      "file": "drivers/tty/serial/8250/8250_of.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276208222,
      "name": "of_platform_serial_setup.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 930
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int of_platform_serial_setup(struct platform_device * ofdev, int type, struct uart_port * port, struct of_serial_info * info)
```
</details>
</li>
</ul>
