# Function: <code>bgpio_dir_out</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bgpio_dir_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586914944,
      "name": "bgpio_dir_out",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:386",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_dir_out_val_first",
        "drivers/gpio/gpio-mmio.c:bgpio_dir_out_dir_first"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586914944,
      "name": "bgpio_dir_out.constprop.0",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bgpio_dir_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588069904,
      "name": "bgpio_dir_out",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:386",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_dir_out_val_first",
        "drivers/gpio/gpio-mmio.c:bgpio_dir_out_dir_first"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588069904,
      "name": "bgpio_dir_out.constprop.0",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bgpio_dir_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588344448,
      "name": "bgpio_dir_out",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:386",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_dir_out_val_first",
        "drivers/gpio/gpio-mmio.c:bgpio_dir_out_dir_first"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588344448,
      "name": "bgpio_dir_out.isra.0",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bgpio_dir_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588638848,
      "name": "bgpio_dir_out",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:385",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_dir_out_val_first",
        "drivers/gpio/gpio-mmio.c:bgpio_dir_out_dir_first"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588638848,
      "name": "bgpio_dir_out.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int bgpio_dir_out(struct gpio_chip * gc, unsigned int gpio, int val)
```

```json
{
  "name": "bgpio_dir_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496763432,
      "name": "bgpio_dir_out",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:384",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496763432,
      "name": "bgpio_dir_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int bgpio_dir_out(struct gpio_chip * gc, unsigned int gpio, int val)
```

```json
{
  "name": "bgpio_dir_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230038348,
      "name": "bgpio_dir_out",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:384",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230038348,
      "name": "bgpio_dir_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int bgpio_dir_out(struct gpio_chip * gc, unsigned int gpio, int val)
```

```json
{
  "name": "bgpio_dir_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290849024,
      "name": "bgpio_dir_out",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:384",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290849024,
      "name": "bgpio_dir_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int bgpio_dir_out(struct gpio_chip * gc, unsigned int gpio, int val)
```

```json
{
  "name": "bgpio_dir_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275503776,
      "name": "bgpio_dir_out",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:384",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275503776,
      "name": "bgpio_dir_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int bgpio_dir_out(struct gpio_chip * gc, unsigned int gpio, int val)
```

```json
{
  "name": "bgpio_dir_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584521920,
      "name": "bgpio_dir_out",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:384",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584521920,
      "name": "bgpio_dir_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int bgpio_dir_out(struct gpio_chip * gc, unsigned int gpio, int val)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int bgpio_dir_out(struct gpio_chip * gc, unsigned int gpio, int val)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int bgpio_dir_out(struct gpio_chip * gc, unsigned int gpio, int val)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int bgpio_dir_out(struct gpio_chip * gc, unsigned int gpio, int val)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➕</summary>

```c
int bgpio_dir_out(struct gpio_chip * gc, unsigned int gpio, int val)
```
</details>
</li>
</ul>
