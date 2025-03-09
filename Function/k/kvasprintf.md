# Function: <code>kvasprintf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
char * kvasprintf(gfp_t gfp, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583009840,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:14",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kasprintf.c:kasprintf",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583009840,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
char * kvasprintf(gfp_t gfp, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583300272,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:14",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583300272,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
char * kvasprintf(gfp_t gfp, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583419312,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:14",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583419312,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
char * kvasprintf(gfp_t gfp, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583440368,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:14",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583440368,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
char * kvasprintf(gfp_t gfp, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583620304,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:15",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583620304,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
char * kvasprintf(gfp_t gfp, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583836752,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:15",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583836752,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
char * kvasprintf(gfp_t gfp, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583920384,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:15",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/item.c:config_item_set_name",
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583920384,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
char * kvasprintf(gfp_t gfp, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584100192,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:15",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:logfc",
        "fs/configfs/item.c:config_item_set_name",
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584100192,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
char * kvasprintf(gfp_t gfp, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584222976,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:15",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:logfc",
        "fs/configfs/item.c:config_item_set_name",
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584222976,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
char * kvasprintf(gfp_t gfp, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584629008,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:15",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/item.c:config_item_set_name",
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584629008,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
char * kvasprintf(gfp_t gfp, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584748064,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:15",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/item.c:config_item_set_name",
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584748064,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
char * kvasprintf(gfp_t gfp, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584776400,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:15",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/item.c:config_item_set_name",
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584776400,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
char * kvasprintf(gfp_t gfp, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585206416,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:15",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/item.c:config_item_set_name",
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585206416,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
char * kvasprintf(gfp_t gfp, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586042016,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:15",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "fs/configfs/item.c:config_item_set_name",
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586042016,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
char * kvasprintf(gfp_t gfp, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587024608,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:15",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "fs/configfs/item.c:config_item_set_name",
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587024608,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
char * kvasprintf(gfp_t gfp, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587279600,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:15",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "fs/configfs/item.c:config_item_set_name",
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587279600,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
char * kvasprintf(gfp_t gfp, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587568336,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:15",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "fs/configfs/item.c:config_item_set_name",
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf",
        "drivers/gpu/drm/drm_crtc.c:__drm_crtc_init_with_planes",
        "drivers/gpu/drm/drm_encoder.c:__drm_encoder_init",
        "drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587568336,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
char * kvasprintf(gfp_t gfp, const char * fmt, va_list ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496096568,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:15",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:logfc",
        "fs/configfs/item.c:config_item_set_name",
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496096568,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
char * kvasprintf(gfp_t gfp, const char * fmt, va_list ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229423496,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:15",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:logfc",
        "fs/configfs/item.c:config_item_set_name",
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pci/irq.c:pci_request_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229423496,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
char * kvasprintf(gfp_t gfp, const char * fmt, va_list ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290340656,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:15",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:logfc",
        "fs/configfs/item.c:config_item_set_name",
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pci/irq.c:pci_request_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290340656,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
char * kvasprintf(gfp_t gfp, const char * fmt, va_list ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275165048,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:15",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:logfc",
        "fs/configfs/item.c:config_item_set_name",
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pci/irq.c:pci_request_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275165048,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
char * kvasprintf(gfp_t gfp, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584191712,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:15",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:logfc",
        "fs/configfs/item.c:config_item_set_name",
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584191712,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
char * kvasprintf(gfp_t gfp, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584126928,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:15",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:logfc",
        "fs/configfs/item.c:config_item_set_name",
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pci/irq.c:pci_request_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584126928,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
char * kvasprintf(gfp_t gfp, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584175472,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:15",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:logfc",
        "fs/configfs/item.c:config_item_set_name",
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584175472,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
char * kvasprintf(gfp_t gfp, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "kvasprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584279808,
      "name": "kvasprintf",
      "external": true,
      "loc": "lib/kasprintf.c:15",
      "file": "lib/kasprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:logfc",
        "fs/configfs/item.c:config_item_set_name",
        "lib/kasprintf.c:kasprintf",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584279808,
      "name": "kvasprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * ap</code> ➡️ <code>va_list ap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * ap</code> ➡️ <code>va_list ap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * ap</code> ➡️ <code>va_list ap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * ap</code> ➡️ <code>va_list ap</code>
</li>
</ul>
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
