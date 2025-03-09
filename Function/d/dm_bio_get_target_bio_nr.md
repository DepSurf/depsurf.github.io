# Function: <code>dm_bio_get_target_bio_nr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585824001,
      "name": "dm_bio_get_target_bio_nr",
      "external": false,
      "loc": "include/linux/device-mapper.h:307",
      "file": "drivers/md/dm-stripe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586218432,
      "name": "dm_bio_get_target_bio_nr",
      "external": false,
      "loc": "include/linux/device-mapper.h:334",
      "file": "drivers/md/dm-stripe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586422930,
      "name": "dm_bio_get_target_bio_nr",
      "external": false,
      "loc": "include/linux/device-mapper.h:334",
      "file": "drivers/md/dm-stripe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586528114,
      "name": "dm_bio_get_target_bio_nr",
      "external": false,
      "loc": "include/linux/device-mapper.h:360",
      "file": "drivers/md/dm-stripe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586995394,
      "name": "dm_bio_get_target_bio_nr",
      "external": false,
      "loc": "include/linux/device-mapper.h:357",
      "file": "drivers/md/dm-stripe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
unsigned int dm_bio_get_target_bio_nr(const struct bio * bio)
```

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587259920,
      "name": "dm_bio_get_target_bio_nr",
      "external": true,
      "loc": "drivers/md/dm.c:124",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587259920,
      "name": "dm_bio_get_target_bio_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int dm_bio_get_target_bio_nr(const struct bio * bio)
```

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587440544,
      "name": "dm_bio_get_target_bio_nr",
      "external": true,
      "loc": "drivers/md/dm.c:124",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587440544,
      "name": "dm_bio_get_target_bio_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int dm_bio_get_target_bio_nr(const struct bio * bio)
```

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587712928,
      "name": "dm_bio_get_target_bio_nr",
      "external": true,
      "loc": "drivers/md/dm.c:124",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587712928,
      "name": "dm_bio_get_target_bio_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int dm_bio_get_target_bio_nr(const struct bio * bio)
```

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587917232,
      "name": "dm_bio_get_target_bio_nr",
      "external": true,
      "loc": "drivers/md/dm.c:124",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587917232,
      "name": "dm_bio_get_target_bio_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int dm_bio_get_target_bio_nr(const struct bio * bio)
```

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588768864,
      "name": "dm_bio_get_target_bio_nr",
      "external": true,
      "loc": "drivers/md/dm.c:127",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588768864,
      "name": "dm_bio_get_target_bio_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int dm_bio_get_target_bio_nr(const struct bio * bio)
```

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588788288,
      "name": "dm_bio_get_target_bio_nr",
      "external": true,
      "loc": "drivers/md/dm.c:127",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588788288,
      "name": "dm_bio_get_target_bio_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int dm_bio_get_target_bio_nr(const struct bio * bio)
```

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588674080,
      "name": "dm_bio_get_target_bio_nr",
      "external": true,
      "loc": "drivers/md/dm.c:132",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588674080,
      "name": "dm_bio_get_target_bio_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int dm_bio_get_target_bio_nr(const struct bio * bio)
```

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589362208,
      "name": "dm_bio_get_target_bio_nr",
      "external": true,
      "loc": "drivers/md/dm.c:101",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589362208,
      "name": "dm_bio_get_target_bio_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int dm_bio_get_target_bio_nr(const struct bio * bio)
```

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590836752,
      "name": "dm_bio_get_target_bio_nr",
      "external": true,
      "loc": "drivers/md/dm.c:118",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590836752,
      "name": "dm_bio_get_target_bio_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
unsigned int dm_bio_get_target_bio_nr(const struct bio * bio)
```

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592525872,
      "name": "dm_bio_get_target_bio_nr",
      "external": true,
      "loc": "drivers/md/dm.c:114",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592525872,
      "name": "dm_bio_get_target_bio_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
unsigned int dm_bio_get_target_bio_nr(const struct bio * bio)
```

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592956272,
      "name": "dm_bio_get_target_bio_nr",
      "external": true,
      "loc": "drivers/md/dm.c:116",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592956272,
      "name": "dm_bio_get_target_bio_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
unsigned int dm_bio_get_target_bio_nr(const struct bio * bio)
```

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593706112,
      "name": "dm_bio_get_target_bio_nr",
      "external": true,
      "loc": "drivers/md/dm.c:116",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593706112,
      "name": "dm_bio_get_target_bio_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
unsigned int dm_bio_get_target_bio_nr(const struct bio * bio)
```

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501149624,
      "name": "dm_bio_get_target_bio_nr",
      "external": true,
      "loc": "drivers/md/dm.c:124",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501149624,
      "name": "dm_bio_get_target_bio_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
unsigned int dm_bio_get_target_bio_nr(const struct bio * bio)
```

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233662136,
      "name": "dm_bio_get_target_bio_nr",
      "external": true,
      "loc": "drivers/md/dm.c:124",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233662136,
      "name": "dm_bio_get_target_bio_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
unsigned int dm_bio_get_target_bio_nr(const struct bio * bio)
```

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294656384,
      "name": "dm_bio_get_target_bio_nr",
      "external": true,
      "loc": "drivers/md/dm.c:124",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294656384,
      "name": "dm_bio_get_target_bio_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
unsigned int dm_bio_get_target_bio_nr(const struct bio * bio)
```

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277860758,
      "name": "dm_bio_get_target_bio_nr",
      "external": true,
      "loc": "drivers/md/dm.c:124",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277860758,
      "name": "dm_bio_get_target_bio_nr",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
unsigned int dm_bio_get_target_bio_nr(const struct bio * bio)
```

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587548208,
      "name": "dm_bio_get_target_bio_nr",
      "external": true,
      "loc": "drivers/md/dm.c:124",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587548208,
      "name": "dm_bio_get_target_bio_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int dm_bio_get_target_bio_nr(const struct bio * bio)
```

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587316304,
      "name": "dm_bio_get_target_bio_nr",
      "external": true,
      "loc": "drivers/md/dm.c:124",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587316304,
      "name": "dm_bio_get_target_bio_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int dm_bio_get_target_bio_nr(const struct bio * bio)
```

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587873376,
      "name": "dm_bio_get_target_bio_nr",
      "external": true,
      "loc": "drivers/md/dm.c:124",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587873376,
      "name": "dm_bio_get_target_bio_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int dm_bio_get_target_bio_nr(const struct bio * bio)
```

```json
{
  "name": "dm_bio_get_target_bio_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587988512,
      "name": "dm_bio_get_target_bio_nr",
      "external": true,
      "loc": "drivers/md/dm.c:124",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587988512,
      "name": "dm_bio_get_target_bio_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int dm_bio_get_target_bio_nr(const struct bio * bio)
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
