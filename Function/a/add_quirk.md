# Function: <code>add_quirk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585975120,
      "name": "add_quirk",
      "external": false,
      "loc": "include/linux/mmc/card.h:413",
      "file": "drivers/mmc/core/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585975120,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate ❓</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586336816,
      "name": "add_quirk",
      "external": false,
      "loc": "include/linux/mmc/card.h:434",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586380400,
      "name": "add_quirk",
      "external": false,
      "loc": "include/linux/mmc/card.h:434",
      "file": "drivers/mmc/core/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586336816,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071586380400,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate ❓</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586545584,
      "name": "add_quirk",
      "external": false,
      "loc": "include/linux/mmc/card.h:425",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586589264,
      "name": "add_quirk",
      "external": false,
      "loc": "include/linux/mmc/card.h:425",
      "file": "drivers/mmc/core/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586545584,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071586589264,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate ❓</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586669168,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:139",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586697280,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:139",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586669168,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071586697280,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate ❓</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587153328,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:142",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587182016,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:142",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587153328,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587182016,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate ❓</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587452832,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:142",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587482128,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:142",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587452832,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
    },
    {
      "addr": 18446744071587482128,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate ❓</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587632976,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:138",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587662240,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:138",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587632976,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
    },
    {
      "addr": 18446744071587662240,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate ❓</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587910960,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587940560,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587910960,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
    },
    {
      "addr": 18446744071587940560,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate ❓</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588116848,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588146432,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588116848,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
    },
    {
      "addr": 18446744071588146432,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588979408,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589010192,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588979408,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
    },
    {
      "addr": 18446744071589010192,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate ❓</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588990576,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589019360,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588990576,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
    },
    {
      "addr": 18446744071589019360,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate ❓</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588878016,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588906688,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588878016,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
    },
    {
      "addr": 18446744071588906688,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589580400,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589613008,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589580400,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
    },
    {
      "addr": 18446744071589613008,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591075664,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:155",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591111136,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:155",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591075664,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071591111136,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate ❓</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592791584,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:156",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592832288,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:156",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592791584,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071592832288,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate ❓</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593228160,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:167",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593268896,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:167",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593228160,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071593268896,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate ❓</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593983056,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:167",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594024800,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:167",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593983056,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071594024800,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate ❓</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501370000,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501399160,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501423144,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501370000,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446603336501399160,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446603336501423144,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate ❓</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233859824,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233888188,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233910832,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233859824,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 3233888188,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 3233910832,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate ❓</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294925792,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294963360,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294925792,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 13835058055294963360,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate ❓</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277980802,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278006692,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278026758,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278026758,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446743936277980802,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446743936278006692,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate ❓</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587738416,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587768000,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587738416,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
    },
    {
      "addr": 18446744071587768000,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate ❓</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588071376,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588100960,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588071376,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
    },
    {
      "addr": 18446744071588100960,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate ❓</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```

```json
{
  "name": "add_quirk",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588188912,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588218496,
      "name": "add_quirk",
      "external": false,
      "loc": "drivers/mmc/core/card.h:137",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588188912,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
    },
    {
      "addr": 18446744071588218496,
      "name": "add_quirk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void add_quirk(struct mmc_card * card, int data)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
