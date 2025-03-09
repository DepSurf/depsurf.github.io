# Function: <code>bitmap_alloc</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int * bitmap_alloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583924128,
      "name": "bitmap_alloc",
      "external": true,
      "loc": "lib/bitmap.c:1123",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_zalloc"
      ],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:list_locations",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583925024,
      "name": "bitmap_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
long unsigned int * bitmap_alloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584103184,
      "name": "bitmap_alloc",
      "external": true,
      "loc": "lib/bitmap.c:1151",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_zalloc"
      ],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:list_locations",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584104432,
      "name": "bitmap_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
long unsigned int * bitmap_alloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584225968,
      "name": "bitmap_alloc",
      "external": true,
      "loc": "lib/bitmap.c:1171",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_zalloc"
      ],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:list_locations",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584227216,
      "name": "bitmap_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
long unsigned int * bitmap_alloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584632144,
      "name": "bitmap_alloc",
      "external": true,
      "loc": "lib/bitmap.c:1246",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_zalloc"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_allocate_mask",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584632576,
      "name": "bitmap_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
long unsigned int * bitmap_alloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584751184,
      "name": "bitmap_alloc",
      "external": true,
      "loc": "lib/bitmap.c:1246",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_zalloc"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_allocate_mask",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584751616,
      "name": "bitmap_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
long unsigned int * bitmap_alloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584779376,
      "name": "bitmap_alloc",
      "external": true,
      "loc": "lib/bitmap.c:1257",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:devm_bitmap_alloc",
        "lib/bitmap.c:bitmap_zalloc"
      ],
      "caller_func": [
        "kernel/sched/topology.c:sched_init_numa",
        "drivers/gpio/gpiolib.c:gpiochip_allocate_mask",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584780048,
      "name": "bitmap_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
long unsigned int * bitmap_alloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585210128,
      "name": "bitmap_alloc",
      "external": true,
      "loc": "lib/bitmap.c:1388",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:devm_bitmap_alloc",
        "lib/bitmap.c:bitmap_zalloc"
      ],
      "caller_func": [
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "mm/slub.c:slab_debug_trace_open",
        "mm/slub.c:validate_slab_cache",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiochip_allocate_mask",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585210400,
      "name": "bitmap_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
long unsigned int * bitmap_alloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586046512,
      "name": "bitmap_alloc",
      "external": true,
      "loc": "lib/bitmap.c:1405",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:devm_bitmap_alloc",
        "lib/bitmap.c:bitmap_zalloc"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/watch_queue.c:watch_queue_set_size",
        "mm/slub.c:slab_debug_trace_open",
        "mm/slub.c:validate_slab_cache",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiochip_allocate_mask",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586046896,
      "name": "bitmap_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
long unsigned int * bitmap_alloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587029968,
      "name": "bitmap_alloc",
      "external": true,
      "loc": "lib/bitmap.c:1386",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:devm_bitmap_alloc",
        "lib/bitmap.c:bitmap_zalloc"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/watch_queue.c:watch_queue_set_size",
        "mm/slub.c:slab_debug_trace_open",
        "mm/slub.c:validate_slab_cache",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiochip_allocate_mask",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587030672,
      "name": "bitmap_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
long unsigned int * bitmap_alloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587285120,
      "name": "bitmap_alloc",
      "external": true,
      "loc": "lib/bitmap.c:1386",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:devm_bitmap_alloc",
        "lib/bitmap.c:bitmap_zalloc"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/watch_queue.c:watch_queue_set_size",
        "mm/slub.c:slab_debug_trace_open",
        "mm/slub.c:validate_slab_cache",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiochip_allocate_mask",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587285824,
      "name": "bitmap_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
long unsigned int * bitmap_alloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587572112,
      "name": "bitmap_alloc",
      "external": true,
      "loc": "lib/bitmap.c:710",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:devm_bitmap_alloc",
        "lib/bitmap.c:bitmap_zalloc"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/watch_queue.c:watch_queue_set_size",
        "mm/slub.c:slab_debug_trace_open",
        "mm/slub.c:validate_slab_cache",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiochip_allocate_mask",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/ptp/ptp_chardev.c:ptp_open",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587572816,
      "name": "bitmap_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
long unsigned int * bitmap_alloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496099840,
      "name": "bitmap_alloc",
      "external": true,
      "loc": "lib/bitmap.c:1171",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_zalloc"
      ],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:list_locations",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496100864,
      "name": "bitmap_alloc",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
long unsigned int * bitmap_alloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229426976,
      "name": "bitmap_alloc",
      "external": true,
      "loc": "lib/bitmap.c:1171",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_zalloc"
      ],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:list_locations",
        "drivers/gpio/gpiolib.c:gpiochip_allocate_mask",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229427792,
      "name": "bitmap_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
long unsigned int * bitmap_alloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290345540,
      "name": "bitmap_alloc",
      "external": true,
      "loc": "lib/bitmap.c:1171",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_zalloc"
      ],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:list_locations",
        "drivers/gpio/gpiolib.c:gpiochip_allocate_mask",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290347408,
      "name": "bitmap_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
long unsigned int * bitmap_alloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275169174,
      "name": "bitmap_alloc",
      "external": true,
      "loc": "lib/bitmap.c:1171",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_zalloc"
      ],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:list_locations",
        "drivers/gpio/gpiolib.c:gpiochip_allocate_mask",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275169358,
      "name": "bitmap_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
long unsigned int * bitmap_alloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584194704,
      "name": "bitmap_alloc",
      "external": true,
      "loc": "lib/bitmap.c:1171",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_zalloc"
      ],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:list_locations",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584195952,
      "name": "bitmap_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
long unsigned int * bitmap_alloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584129920,
      "name": "bitmap_alloc",
      "external": true,
      "loc": "lib/bitmap.c:1171",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_zalloc"
      ],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:list_locations",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584131168,
      "name": "bitmap_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
long unsigned int * bitmap_alloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584178464,
      "name": "bitmap_alloc",
      "external": true,
      "loc": "lib/bitmap.c:1171",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_zalloc"
      ],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:list_locations",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584179712,
      "name": "bitmap_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
long unsigned int * bitmap_alloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584282800,
      "name": "bitmap_alloc",
      "external": true,
      "loc": "lib/bitmap.c:1171",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_zalloc"
      ],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:list_locations",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584284048,
      "name": "bitmap_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
long unsigned int * bitmap_alloc(unsigned int nbits, gfp_t flags)
```
</details>
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
