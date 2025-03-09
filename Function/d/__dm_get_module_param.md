# Function: <code>__dm_get_module_param</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585792149,
      "name": "__dm_get_module_param",
      "external": false,
      "loc": "drivers/md/dm.c:280",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586204747,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:135",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586199472,
      "name": "__dm_get_module_param",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586409211,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:135",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586403952,
      "name": "__dm_get_module_param",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586512590,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:130",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586507376,
      "name": "__dm_get_module_param",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586980011,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:137",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586974928,
      "name": "__dm_get_module_param",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587276893,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:191",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587271648,
      "name": "__dm_get_module_param",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587457056,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:191",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587452176,
      "name": "__dm_get_module_param",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587730396,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:188",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587726176,
      "name": "__dm_get_module_param",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587934748,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:188",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587930528,
      "name": "__dm_get_module_param",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588787182,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:192",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588783632,
      "name": "__dm_get_module_param",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588805737,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:202",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588802224,
      "name": "__dm_get_module_param",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588691445,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:207",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588687104,
      "name": "__dm_get_module_param",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589379493,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:163",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589371184,
      "name": "__dm_get_module_param",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590855308,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:172",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590850992,
      "name": "__dm_get_module_param",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592536213,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:168",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_get_reserved_bio_based_ios"
      ],
      "caller_func": [
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592541328,
      "name": "__dm_get_module_param",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592967845,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:171",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_get_reserved_bio_based_ios"
      ],
      "caller_func": [
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592972560,
      "name": "__dm_get_module_param",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593717973,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:171",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_get_reserved_bio_based_ios"
      ],
      "caller_func": [
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593722496,
      "name": "__dm_get_module_param",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501171424,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:188",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501165688,
      "name": "__dm_get_module_param",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233675824,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:188",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233675824,
      "name": "__dm_get_module_param",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294683184,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:188",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294677680,
      "name": "__dm_get_module_param",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277877928,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:188",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277873996,
      "name": "__dm_get_module_param",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587565724,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:188",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587561504,
      "name": "__dm_get_module_param",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587333804,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:188",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587329584,
      "name": "__dm_get_module_param",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587890892,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:188",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587886672,
      "name": "__dm_get_module_param",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```

```json
{
  "name": "__dm_get_module_param",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588006156,
      "name": "__dm_get_module_param",
      "external": true,
      "loc": "drivers/md/dm.c:188",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_get_reserved_rq_based_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588001968,
      "name": "__dm_get_module_param",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
unsigned int __dm_get_module_param(unsigned int * module_param, unsigned int def, unsigned int max)
```
</details>
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
