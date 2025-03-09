# Function: <code>led_classdev_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int led_classdev_register(struct device * parent, struct led_classdev * led_cdev)
```

```json
{
  "name": "led_classdev_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585980544,
      "name": "led_classdev_register",
      "external": true,
      "loc": "drivers/leds/led-class.c:188",
      "file": "drivers/leds/led-class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:devm_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585980544,
      "name": "led_classdev_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 499
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int led_classdev_register(struct device * parent, struct led_classdev * led_cdev)
```

```json
{
  "name": "led_classdev_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586386256,
      "name": "led_classdev_register",
      "external": true,
      "loc": "drivers/leds/led-class.c:188",
      "file": "drivers/leds/led-class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:devm_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586386256,
      "name": "led_classdev_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int led_classdev_register(struct device * parent, struct led_classdev * led_cdev)
```

```json
{
  "name": "led_classdev_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586595040,
      "name": "led_classdev_register",
      "external": true,
      "loc": "drivers/leds/led-class.c:189",
      "file": "drivers/leds/led-class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:devm_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586595040,
      "name": "led_classdev_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
    }
  ]
}
```
</details>
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "led_classdev_register",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233961744,
      "name": "led_classdev_register",
      "external": false,
      "loc": "include/linux/leds.h:178",
      "file": "drivers/mmc/host/sdhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/sdhci.c:__sdhci_add_host"
      ],
      "caller_func": []
    },
    {
      "addr": 3234021372,
      "name": "led_classdev_register",
      "external": false,
      "loc": "include/linux/leds.h:178",
      "file": "drivers/leds/leds-asic3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/leds-asic3.c:asic3_led_probe"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int led_classdev_register(struct device * parent, struct led_classdev * led_cdev)
```
</details>
</li>
</ul>
