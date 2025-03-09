# Function: <code>devres_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584415952,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:363",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_free_irq",
        "lib/devres.c:devm_iounmap",
        "drivers/phy/phy-core.c:devm_phy_put",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584415952,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584751312,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:363",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_free_irq",
        "lib/devres.c:devm_iounmap",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584751312,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584941552,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:364",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_free_irq",
        "lib/devres.c:devm_iounmap",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584941552,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585025200,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:364",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_free_irq",
        "lib/devres.c:devm_iounmap",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585025200,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585447808,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:364",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_free_irq",
        "lib/devres.c:devm_iounmap",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585447808,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585691040,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:368",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_free_irq",
        "lib/devres.c:devm_iounmap",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585691040,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585822192,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:376",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_free_irq",
        "lib/devres.c:devm_iounmap",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585822192,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586055920,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:376",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_release_region",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/dma/mapping.c:dmam_free_coherent",
        "lib/devres.c:devm_ioport_unmap",
        "lib/devres.c:devm_iounmap",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586055920,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586203920,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:376",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_release_region",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/dma/mapping.c:dmam_free_coherent",
        "lib/devres.c:devm_ioport_unmap",
        "lib/devres.c:devm_iounmap",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586203920,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586966128,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:376",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_release_region",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/dma/mapping.c:dmam_free_coherent",
        "lib/devres.c:devm_ioport_unmap",
        "lib/devres.c:devm_iounmap",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586966128,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587051840,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:392",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_release_region",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/dma/mapping.c:dmam_free_coherent",
        "lib/devres.c:devm_ioport_unmap",
        "lib/devres.c:devm_iounmap",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587051840,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586935632,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:392",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_release_region",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/dma/mapping.c:dmam_free_coherent",
        "lib/devres.c:devm_ioport_unmap",
        "lib/devres.c:devm_iounmap",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586935632,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587499497,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:385",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:devm_free_percpu",
        "drivers/base/devres.c:devm_kfree",
        "drivers/base/devres.c:devm_remove_action"
      ],
      "caller_func": [
        "kernel/resource.c:__devm_release_region",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/dma/mapping.c:dmam_free_coherent",
        "lib/devres.c:devm_ioport_unmap",
        "lib/devres.c:devm_iounmap",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_unhinge",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587499328,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588823353,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:385",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:devm_free_percpu",
        "drivers/base/devres.c:devm_kfree",
        "drivers/base/devres.c:devm_remove_action"
      ],
      "caller_func": [
        "kernel/resource.c:__devm_release_region",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/dma/mapping.c:dmam_free_coherent",
        "lib/devres.c:devm_ioport_unmap",
        "lib/devres.c:devm_iounmap",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_unhinge",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588823152,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590322745,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:390",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:devm_free_percpu",
        "drivers/base/devres.c:devm_kfree",
        "drivers/base/devres.c:devm_remove_action"
      ],
      "caller_func": [
        "kernel/resource.c:__devm_release_region",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/dma/mapping.c:dmam_free_coherent",
        "lib/devres.c:devm_ioport_unmap",
        "lib/devres.c:devm_iounmap",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_unhinge",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590322512,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590642665,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:390",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:devm_free_percpu",
        "drivers/base/devres.c:devm_remove_action"
      ],
      "caller_func": [
        "kernel/resource.c:__devm_release_region",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/dma/mapping.c:dmam_free_coherent",
        "lib/devres.c:devm_ioport_unmap",
        "lib/devres.c:devm_iounmap",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_unhinge",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590642432,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591002761,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:390",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:devm_free_percpu",
        "drivers/base/devres.c:devm_remove_action"
      ],
      "caller_func": [
        "kernel/resource.c:__devm_release_region",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/dma/mapping.c:dmam_free_coherent",
        "lib/devres.c:devm_ioport_unmap",
        "lib/devres.c:devm_iounmap",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_unhinge",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591002528,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499005120,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:376",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_release_region",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/dma/mapping.c:dmam_free_coherent",
        "lib/devres.c:devm_ioport_unmap",
        "lib/devres.c:devm_iounmap",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499005120,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231570544,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:376",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_release_region",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/dma/mapping.c:dmam_free_coherent",
        "lib/devres.c:devm_iounmap",
        "drivers/input/input.c:input_free_device",
        "sound/soc/soc-jack.c:snd_soc_jack_free_gpios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231570544,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292164896,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:376",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_release_region",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/dma/mapping.c:dmam_free_coherent",
        "lib/devres.c:devm_ioport_unmap",
        "lib/devres.c:devm_iounmap",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_unhinge",
        "drivers/base/devres.c:devm_free_percpu",
        "drivers/base/devres.c:devm_kfree",
        "drivers/base/devres.c:devm_remove_action",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292164896,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276376688,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:376",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_release_region",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/dma/mapping.c:dmam_free_coherent",
        "lib/devres.c:devm_ioport_unmap",
        "lib/devres.c:devm_iounmap",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276376688,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585964128,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:376",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_release_region",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/dma/mapping.c:dmam_free_coherent",
        "lib/devres.c:devm_ioport_unmap",
        "lib/devres.c:devm_iounmap",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585964128,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585813392,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:376",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_release_region",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/dma/mapping.c:dmam_free_coherent",
        "lib/devres.c:devm_ioport_unmap",
        "lib/devres.c:devm_iounmap",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585813392,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586153936,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:376",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_release_region",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/dma/mapping.c:dmam_free_coherent",
        "lib/devres.c:devm_ioport_unmap",
        "lib/devres.c:devm_iounmap",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586153936,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int devres_destroy(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586262640,
      "name": "devres_destroy",
      "external": true,
      "loc": "drivers/base/devres.c:376",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_release_region",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/dma/mapping.c:dmam_free_coherent",
        "lib/devres.c:devm_ioport_unmap",
        "lib/devres.c:devm_iounmap",
        "drivers/input/input.c:input_free_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586262640,
      "name": "devres_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
