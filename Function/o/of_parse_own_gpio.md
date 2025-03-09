# Function: <code>of_parse_own_gpio</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct gpio_desc * of_parse_own_gpio(struct device_node * np, struct gpio_chip * chip, unsigned int idx, const char * * name, long unsigned int * lflags, enum gpiod_flags * dflags)
```

```json
{
  "name": "of_parse_own_gpio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496742064,
      "name": "of_parse_own_gpio",
      "external": false,
      "loc": "drivers/gpio/gpiolib-of.c:558",
      "file": "drivers/gpio/gpiolib-of.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-of.c:of_gpiochip_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496742064,
      "name": "of_parse_own_gpio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "of_parse_own_gpio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230031656,
      "name": "of_parse_own_gpio",
      "external": false,
      "loc": "drivers/gpio/gpiolib-of.c:558",
      "file": "drivers/gpio/gpiolib-of.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-of.c:of_gpiochip_add"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct gpio_desc * of_parse_own_gpio(struct device_node * np, struct gpio_chip * chip, unsigned int idx, const char * * name, long unsigned int * lflags, enum gpiod_flags * dflags)
```

```json
{
  "name": "of_parse_own_gpio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290835504,
      "name": "of_parse_own_gpio",
      "external": false,
      "loc": "drivers/gpio/gpiolib-of.c:558",
      "file": "drivers/gpio/gpiolib-of.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-of.c:of_gpiochip_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290835504,
      "name": "of_parse_own_gpio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 780
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
struct gpio_desc * of_parse_own_gpio(struct device_node * np, struct gpio_chip * chip, unsigned int idx, const char * * name, long unsigned int * lflags, enum gpiod_flags * dflags)
```

```json
{
  "name": "of_parse_own_gpio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275494734,
      "name": "of_parse_own_gpio",
      "external": false,
      "loc": "drivers/gpio/gpiolib-of.c:558",
      "file": "drivers/gpio/gpiolib-of.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-of.c:of_gpiochip_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275494734,
      "name": "of_parse_own_gpio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct gpio_desc * of_parse_own_gpio(struct device_node * np, struct gpio_chip * chip, unsigned int idx, const char * * name, long unsigned int * lflags, enum gpiod_flags * dflags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct gpio_desc * of_parse_own_gpio(struct device_node * np, struct gpio_chip * chip, unsigned int idx, const char * * name, long unsigned int * lflags, enum gpiod_flags * dflags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct gpio_desc * of_parse_own_gpio(struct device_node * np, struct gpio_chip * chip, unsigned int idx, const char * * name, long unsigned int * lflags, enum gpiod_flags * dflags)
```
</details>
</li>
</ul>
