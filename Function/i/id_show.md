# Function: <code>id_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dmdev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583802384,
      "name": "id_show",
      "external": false,
      "loc": "drivers/pnp/interface.c:439",
      "file": "drivers/pnp/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585544864,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:386",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583802384,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071585544864,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dmdev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584128640,
      "name": "id_show",
      "external": false,
      "loc": "drivers/pnp/interface.c:439",
      "file": "drivers/pnp/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585938592,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:386",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584128640,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071585938592,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dmdev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584276640,
      "name": "id_show",
      "external": false,
      "loc": "drivers/pnp/interface.c:439",
      "file": "drivers/pnp/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584950208,
      "name": "id_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:366",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586126944,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:386",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584276640,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071584950208,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071586126944,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dmdev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584354688,
      "name": "id_show",
      "external": false,
      "loc": "drivers/pnp/interface.c:439",
      "file": "drivers/pnp/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585035088,
      "name": "id_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:366",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586215248,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:386",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584354688,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071585035088,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071586215248,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dmdev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584760480,
      "name": "id_show",
      "external": false,
      "loc": "drivers/pnp/interface.c:440",
      "file": "drivers/pnp/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585457952,
      "name": "id_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:379",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586678576,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:386",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584760480,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071585457952,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071586678576,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dmdev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584988880,
      "name": "id_show",
      "external": false,
      "loc": "drivers/pnp/interface.c:440",
      "file": "drivers/pnp/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585701792,
      "name": "id_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:369",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586944144,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:386",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584988880,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071585701792,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071586944144,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dmdev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585093248,
      "name": "id_show",
      "external": false,
      "loc": "drivers/pnp/interface.c:440",
      "file": "drivers/pnp/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585830048,
      "name": "id_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:363",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587104928,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:382",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585093248,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071585830048,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071587104928,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dmdev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585297824,
      "name": "id_show",
      "external": false,
      "loc": "drivers/pnp/interface.c:440",
      "file": "drivers/pnp/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586065024,
      "name": "id_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:368",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586446144,
      "name": "id_show",
      "external": false,
      "loc": "drivers/dax/bus.c:159",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587369328,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:370",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585297824,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071586065024,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071586446144,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071587369328,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dmdev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585435792,
      "name": "id_show",
      "external": false,
      "loc": "drivers/pnp/interface.c:440",
      "file": "drivers/pnp/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586212912,
      "name": "id_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:368",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586594080,
      "name": "id_show",
      "external": false,
      "loc": "drivers/dax/bus.c:159",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587571168,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:370",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585435792,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071586212912,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071586594080,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071587571168,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dmdev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586152656,
      "name": "id_show",
      "external": false,
      "loc": "drivers/pnp/interface.c:440",
      "file": "drivers/pnp/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586978080,
      "name": "id_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:368",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587380032,
      "name": "id_show",
      "external": false,
      "loc": "drivers/dax/bus.c:159",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588430992,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:370",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586152656,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071586978080,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071587380032,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071588430992,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dmdev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586270672,
      "name": "id_show",
      "external": false,
      "loc": "drivers/pnp/interface.c:440",
      "file": "drivers/pnp/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587064864,
      "name": "id_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:368",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587440928,
      "name": "id_show",
      "external": false,
      "loc": "drivers/dax/bus.c:213",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588463168,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:370",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586270672,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071587064864,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071587440928,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071588463168,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dmdev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586144544,
      "name": "id_show",
      "external": false,
      "loc": "drivers/pnp/interface.c:441",
      "file": "drivers/pnp/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586948832,
      "name": "id_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:368",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587322704,
      "name": "id_show",
      "external": false,
      "loc": "drivers/dax/bus.c:214",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588345664,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:370",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586144544,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071586948832,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071587322704,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071588345664,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dmdev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586645872,
      "name": "id_show",
      "external": false,
      "loc": "drivers/pnp/interface.c:441",
      "file": "drivers/pnp/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587513456,
      "name": "id_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:369",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587889552,
      "name": "id_show",
      "external": false,
      "loc": "drivers/dax/bus.c:212",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589004608,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:370",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586645872,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071587513456,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071587889552,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071589004608,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dmdev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587912832,
      "name": "id_show",
      "external": false,
      "loc": "drivers/pnp/interface.c:441",
      "file": "drivers/pnp/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588841408,
      "name": "id_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:369",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589238608,
      "name": "id_show",
      "external": false,
      "loc": "drivers/dax/bus.c:234",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590441664,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:370",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587912832,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071588841408,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071589238608,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071590441664,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dmdev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589264224,
      "name": "id_show",
      "external": false,
      "loc": "drivers/pnp/interface.c:441",
      "file": "drivers/pnp/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590342832,
      "name": "id_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:421",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590797440,
      "name": "id_show",
      "external": false,
      "loc": "drivers/dax/bus.c:234",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592081056,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:367",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589264224,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071590342832,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071590797440,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071592081056,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dmdev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589561152,
      "name": "id_show",
      "external": false,
      "loc": "drivers/pnp/interface.c:441",
      "file": "drivers/pnp/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590663008,
      "name": "id_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:623",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591138960,
      "name": "id_show",
      "external": false,
      "loc": "drivers/dax/bus.c:248",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592503776,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:367",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589561152,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071590663008,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071591138960,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071592503776,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dmdev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589870336,
      "name": "id_show",
      "external": false,
      "loc": "drivers/pnp/interface.c:441",
      "file": "drivers/pnp/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591023584,
      "name": "id_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:630",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591484656,
      "name": "id_show",
      "external": false,
      "loc": "drivers/dax/bus.c:248",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593248272,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:367",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589870336,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071591023584,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071591484656,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071593248272,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dmdev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497718024,
      "name": "id_show",
      "external": false,
      "loc": "drivers/pnp/interface.c:440",
      "file": "drivers/pnp/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497728528,
      "name": "id_show",
      "external": false,
      "loc": "drivers/amba/bus.c:140",
      "file": "drivers/amba/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499019912,
      "name": "id_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:368",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499477936,
      "name": "id_show",
      "external": false,
      "loc": "drivers/dax/bus.c:159",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500715600,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:370",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497718024,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446603336497728528,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446603336499019912,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446603336499477936,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446603336500715600,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * _dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230552184,
      "name": "id_show",
      "external": false,
      "loc": "drivers/amba/bus.c:140",
      "file": "drivers/amba/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231581548,
      "name": "id_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:368",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231951344,
      "name": "id_show",
      "external": false,
      "loc": "drivers/dax/bus.c:159",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233242868,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:370",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230552184,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 3231581548,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 3231951344,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 3233242868,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292182416,
      "name": "id_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:368",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292757360,
      "name": "id_show",
      "external": false,
      "loc": "drivers/dax/bus.c:159",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294150400,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:370",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292182416,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 13835058055292757360,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 13835058055294150400,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276387414,
      "name": "id_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:368",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276696702,
      "name": "id_show",
      "external": false,
      "loc": "drivers/dax/bus.c:159",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277564922,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:370",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276387414,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446743936276696702,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446743936277564922,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dmdev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585198320,
      "name": "id_show",
      "external": false,
      "loc": "drivers/pnp/interface.c:440",
      "file": "drivers/pnp/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585973120,
      "name": "id_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:368",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586284560,
      "name": "id_show",
      "external": false,
      "loc": "drivers/dax/bus.c:159",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587264192,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:370",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585198320,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071585973120,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071586284560,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071587264192,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585085696,
      "name": "id_show",
      "external": false,
      "loc": "drivers/acpi/nfit/core.c:1626",
      "file": "drivers/acpi/nfit/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585150528,
      "name": "id_show",
      "external": false,
      "loc": "drivers/pnp/interface.c:440",
      "file": "drivers/pnp/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585822384,
      "name": "id_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:368",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586122048,
      "name": "id_show",
      "external": false,
      "loc": "drivers/dax/bus.c:159",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587032528,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:370",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587550608,
      "name": "id_show",
      "external": false,
      "loc": "drivers/hv/vmbus_drv.c:135",
      "file": "drivers/hv/vmbus_drv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585085696,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071585150528,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071585822384,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071586122048,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071587032528,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071587550608,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dmdev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585386192,
      "name": "id_show",
      "external": false,
      "loc": "drivers/pnp/interface.c:440",
      "file": "drivers/pnp/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586162928,
      "name": "id_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:368",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586542048,
      "name": "id_show",
      "external": false,
      "loc": "drivers/dax/bus.c:159",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587522416,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:370",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585386192,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071586162928,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071586542048,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071587522416,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
ssize_t id_show(struct device * dmdev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "id_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585493536,
      "name": "id_show",
      "external": false,
      "loc": "drivers/pnp/interface.c:440",
      "file": "drivers/pnp/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586271632,
      "name": "id_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:368",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586653824,
      "name": "id_show",
      "external": false,
      "loc": "drivers/dax/bus.c:159",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587634560,
      "name": "id_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:370",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585493536,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071586271632,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071586653824,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071587634560,
      "name": "id_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * _dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device * dmdev</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device * dmdev</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device * dmdev</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device * dmdev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
