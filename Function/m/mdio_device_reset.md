# Function: <code>mdio_device_reset</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void mdio_device_reset(struct mdio_device * mdiodev, int value)
```

```json
{
  "name": "mdio_device_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586422400,
      "name": "mdio_device_reset",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:120",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/net/phy/mdio_device.c:mdio_remove",
        "drivers/net/phy/mdio_device.c:mdio_probe",
        "drivers/net/phy/mdio_device.c:mdio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586422400,
      "name": "mdio_device_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void mdio_device_reset(struct mdio_device * mdiodev, int value)
```

```json
{
  "name": "mdio_device_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586567568,
      "name": "mdio_device_reset",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:120",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/net/phy/mdio_device.c:mdio_remove",
        "drivers/net/phy/mdio_device.c:mdio_probe",
        "drivers/net/phy/mdio_device.c:mdio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586567568,
      "name": "mdio_device_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void mdio_device_reset(struct mdio_device * mdiodev, int value)
```

```json
{
  "name": "mdio_device_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586818928,
      "name": "mdio_device_reset",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:116",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/net/phy/mdio_device.c:mdio_remove",
        "drivers/net/phy/mdio_device.c:mdio_probe",
        "drivers/net/phy/mdio_device.c:mdio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586818928,
      "name": "mdio_device_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void mdio_device_reset(struct mdio_device * mdiodev, int value)
```

```json
{
  "name": "mdio_device_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586964992,
      "name": "mdio_device_reset",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:116",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/net/phy/mdio_device.c:mdio_remove",
        "drivers/net/phy/mdio_device.c:mdio_probe",
        "drivers/net/phy/mdio_device.c:mdio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586964992,
      "name": "mdio_device_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void mdio_device_reset(struct mdio_device * mdiodev, int value)
```

```json
{
  "name": "mdio_device_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587787680,
      "name": "mdio_device_reset",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:116",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/net/phy/mdio_device.c:mdio_remove",
        "drivers/net/phy/mdio_device.c:mdio_probe",
        "drivers/net/phy/mdio_device.c:mdio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587787680,
      "name": "mdio_device_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void mdio_device_reset(struct mdio_device * mdiodev, int value)
```

```json
{
  "name": "mdio_device_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587845808,
      "name": "mdio_device_reset",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:116",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/net/phy/mdio_device.c:mdio_remove",
        "drivers/net/phy/mdio_device.c:mdio_probe",
        "drivers/net/phy/mdio_device.c:mdio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587845808,
      "name": "mdio_device_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void mdio_device_reset(struct mdio_device * mdiodev, int value)
```

```json
{
  "name": "mdio_device_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587725088,
      "name": "mdio_device_reset",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:116",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/net/phy/mdio_device.c:mdio_remove",
        "drivers/net/phy/mdio_device.c:mdio_probe",
        "drivers/net/phy/mdio_device.c:mdio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587725088,
      "name": "mdio_device_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void mdio_device_reset(struct mdio_device * mdiodev, int value)
```

```json
{
  "name": "mdio_device_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588318624,
      "name": "mdio_device_reset",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:116",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/net/phy/mdio_device.c:mdio_remove",
        "drivers/net/phy/mdio_device.c:mdio_probe",
        "drivers/net/phy/mdio_device.c:mdio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588318624,
      "name": "mdio_device_reset",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void mdio_device_reset(struct mdio_device * mdiodev, int value)
```

```json
{
  "name": "mdio_device_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589708560,
      "name": "mdio_device_reset",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:116",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_init_hw",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/net/phy/mdio_device.c:mdio_remove",
        "drivers/net/phy/mdio_device.c:mdio_probe",
        "drivers/net/phy/mdio_device.c:mdio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589708560,
      "name": "mdio_device_reset",
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
void mdio_device_reset(struct mdio_device * mdiodev, int value)
```

```json
{
  "name": "mdio_device_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591325088,
      "name": "mdio_device_reset",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:118",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_init_hw",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/net/phy/mdio_device.c:mdio_remove",
        "drivers/net/phy/mdio_device.c:mdio_probe",
        "drivers/net/phy/mdio_device.c:mdio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591325088,
      "name": "mdio_device_reset",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void mdio_device_reset(struct mdio_device * mdiodev, int value)
```

```json
{
  "name": "mdio_device_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591686400,
      "name": "mdio_device_reset",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:118",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_init_hw",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/net/phy/mdio_device.c:mdio_remove",
        "drivers/net/phy/mdio_device.c:mdio_probe",
        "drivers/net/phy/mdio_device.c:mdio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591686400,
      "name": "mdio_device_reset",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void mdio_device_reset(struct mdio_device * mdiodev, int value)
```

```json
{
  "name": "mdio_device_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592429232,
      "name": "mdio_device_reset",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:119",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_init_hw",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/net/phy/mdio_device.c:mdio_remove",
        "drivers/net/phy/mdio_device.c:mdio_probe",
        "drivers/net/phy/mdio_device.c:mdio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592429232,
      "name": "mdio_device_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
void mdio_device_reset(struct mdio_device * mdiodev, int value)
```

```json
{
  "name": "mdio_device_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499953048,
      "name": "mdio_device_reset",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:116",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/net/phy/mdio_device.c:mdio_remove",
        "drivers/net/phy/mdio_device.c:mdio_probe",
        "drivers/net/phy/mdio_device.c:mdio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499953048,
      "name": "mdio_device_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void mdio_device_reset(struct mdio_device * mdiodev, int value)
```

```json
{
  "name": "mdio_device_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232495024,
      "name": "mdio_device_reset",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:116",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/net/phy/mdio_device.c:mdio_remove",
        "drivers/net/phy/mdio_device.c:mdio_probe",
        "drivers/net/phy/mdio_device.c:mdio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232495024,
      "name": "mdio_device_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void mdio_device_reset(struct mdio_device * mdiodev, int value)
```

```json
{
  "name": "mdio_device_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293278960,
      "name": "mdio_device_reset",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:116",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/net/phy/mdio_device.c:mdio_remove",
        "drivers/net/phy/mdio_device.c:mdio_probe",
        "drivers/net/phy/mdio_device.c:mdio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293278960,
      "name": "mdio_device_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void mdio_device_reset(struct mdio_device * mdiodev, int value)
```

```json
{
  "name": "mdio_device_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277035632,
      "name": "mdio_device_reset",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:116",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/net/phy/mdio_device.c:mdio_remove",
        "drivers/net/phy/mdio_device.c:mdio_probe",
        "drivers/net/phy/mdio_device.c:mdio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277035632,
      "name": "mdio_device_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void mdio_device_reset(struct mdio_device * mdiodev, int value)
```

```json
{
  "name": "mdio_device_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586722000,
      "name": "mdio_device_reset",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:116",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/net/phy/mdio_device.c:mdio_remove",
        "drivers/net/phy/mdio_device.c:mdio_probe",
        "drivers/net/phy/mdio_device.c:mdio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586722000,
      "name": "mdio_device_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void mdio_device_reset(struct mdio_device * mdiodev, int value)
```

```json
{
  "name": "mdio_device_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586590304,
      "name": "mdio_device_reset",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:116",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/net/phy/mdio_device.c:mdio_remove",
        "drivers/net/phy/mdio_device.c:mdio_probe",
        "drivers/net/phy/mdio_device.c:mdio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586590304,
      "name": "mdio_device_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void mdio_device_reset(struct mdio_device * mdiodev, int value)
```

```json
{
  "name": "mdio_device_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586919552,
      "name": "mdio_device_reset",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:116",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/net/phy/mdio_device.c:mdio_remove",
        "drivers/net/phy/mdio_device.c:mdio_probe",
        "drivers/net/phy/mdio_device.c:mdio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586919552,
      "name": "mdio_device_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void mdio_device_reset(struct mdio_device * mdiodev, int value)
```

```json
{
  "name": "mdio_device_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587026000,
      "name": "mdio_device_reset",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:116",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/net/phy/mdio_device.c:mdio_remove",
        "drivers/net/phy/mdio_device.c:mdio_probe",
        "drivers/net/phy/mdio_device.c:mdio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587026000,
      "name": "mdio_device_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void mdio_device_reset(struct mdio_device * mdiodev, int value)
```
</details>
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
