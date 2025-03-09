# Function: <code>add_to_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583295568,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:63",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583295568,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583606464,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:62",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583606464,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583743664,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:63",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583743664,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583785440,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:63",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583785440,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584046160,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:63",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584046160,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584246096,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:60",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584246096,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584334768,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:60",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584334768,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584529216,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:58",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584529216,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584664352,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:58",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584664352,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585349632,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:59",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_io",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585349632,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585501360,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:60",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_io",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585501360,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585379616,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:60",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_io",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585379616,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585840976,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:60",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_io",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585840976,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587033952,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:60",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_io",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587033952,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588213296,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:60",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_io",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588213296,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588488960,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:60",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_io",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588488960,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588787536,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:60",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_io",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588787536,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496913528,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:58",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496913528,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230189292,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:58",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230189292,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291010928,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:58",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291010928,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275600402,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:58",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275600402,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584614816,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:58",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584614816,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584544640,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:58",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584544640,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584614512,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:58",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584614512,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int add_to_list(struct list_head * head, struct pci_dev * dev, struct resource * res, resource_size_t add_size, resource_size_t min_align)
```

```json
{
  "name": "add_to_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584722208,
      "name": "add_to_list",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:58",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/setup-bus.c:assign_requested_resources_sorted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584722208,
      "name": "add_to_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
