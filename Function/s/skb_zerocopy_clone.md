# Function: <code>skb_zerocopy_clone</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int skb_zerocopy_clone(struct sk_buff * nskb, struct sk_buff * orig, gfp_t gfp_mask)
```

```json
{
  "name": "skb_zerocopy_clone",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587449808,
      "name": "skb_zerocopy_clone",
      "external": false,
      "loc": "net/core/skbuff.c:1138",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587449808,
      "name": "skb_zerocopy_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
int skb_zerocopy_clone(struct sk_buff * nskb, struct sk_buff * orig, gfp_t gfp_mask)
```

```json
{
  "name": "skb_zerocopy_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587753536,
      "name": "skb_zerocopy_clone",
      "external": false,
      "loc": "net/core/skbuff.c:1139",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587753536,
      "name": "skb_zerocopy_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int skb_zerocopy_clone(struct sk_buff * nskb, struct sk_buff * orig, gfp_t gfp_mask)
```

```json
{
  "name": "skb_zerocopy_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587888176,
      "name": "skb_zerocopy_clone",
      "external": false,
      "loc": "net/core/skbuff.c:1148",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587888176,
      "name": "skb_zerocopy_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int skb_zerocopy_clone(struct sk_buff * nskb, struct sk_buff * orig, gfp_t gfp_mask)
```

```json
{
  "name": "skb_zerocopy_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588193872,
      "name": "skb_zerocopy_clone",
      "external": false,
      "loc": "net/core/skbuff.c:1307",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588193872,
      "name": "skb_zerocopy_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int skb_zerocopy_clone(struct sk_buff * nskb, struct sk_buff * orig, gfp_t gfp_mask)
```

```json
{
  "name": "skb_zerocopy_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588399040,
      "name": "skb_zerocopy_clone",
      "external": false,
      "loc": "net/core/skbuff.c:1307",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588399040,
      "name": "skb_zerocopy_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int skb_zerocopy_clone(struct sk_buff * nskb, struct sk_buff * orig, gfp_t gfp_mask)
```

```json
{
  "name": "skb_zerocopy_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589259888,
      "name": "skb_zerocopy_clone",
      "external": false,
      "loc": "net/core/skbuff.c:1306",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589259888,
      "name": "skb_zerocopy_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int skb_zerocopy_clone(struct sk_buff * nskb, struct sk_buff * orig, gfp_t gfp_mask)
```

```json
{
  "name": "skb_zerocopy_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589259024,
      "name": "skb_zerocopy_clone",
      "external": false,
      "loc": "net/core/skbuff.c:1317",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589259024,
      "name": "skb_zerocopy_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int skb_zerocopy_clone(struct sk_buff * nskb, struct sk_buff * orig, gfp_t gfp_mask)
```

```json
{
  "name": "skb_zerocopy_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589150992,
      "name": "skb_zerocopy_clone",
      "external": false,
      "loc": "net/core/skbuff.c:1359",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589150992,
      "name": "skb_zerocopy_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
int skb_zerocopy_clone(struct sk_buff * nskb, struct sk_buff * orig, gfp_t gfp_mask)
```

```json
{
  "name": "skb_zerocopy_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589871152,
      "name": "skb_zerocopy_clone",
      "external": false,
      "loc": "net/core/skbuff.c:1380",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589871152,
      "name": "skb_zerocopy_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
int skb_zerocopy_clone(struct sk_buff * nskb, struct sk_buff * orig, gfp_t gfp_mask)
```

```json
{
  "name": "skb_zerocopy_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591401344,
      "name": "skb_zerocopy_clone",
      "external": false,
      "loc": "net/core/skbuff.c:1374",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591401344,
      "name": "skb_zerocopy_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
int skb_zerocopy_clone(struct sk_buff * nskb, struct sk_buff * orig, gfp_t gfp_mask)
```

```json
{
  "name": "skb_zerocopy_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593166288,
      "name": "skb_zerocopy_clone",
      "external": false,
      "loc": "net/core/skbuff.c:1572",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593166288,
      "name": "skb_zerocopy_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
int skb_zerocopy_clone(struct sk_buff * nskb, struct sk_buff * orig, gfp_t gfp_mask)
```

```json
{
  "name": "skb_zerocopy_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593620080,
      "name": "skb_zerocopy_clone",
      "external": false,
      "loc": "net/core/skbuff.c:1716",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593620080,
      "name": "skb_zerocopy_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
int skb_zerocopy_clone(struct sk_buff * nskb, struct sk_buff * orig, gfp_t gfp_mask)
```

```json
{
  "name": "skb_zerocopy_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594395248,
      "name": "skb_zerocopy_clone",
      "external": false,
      "loc": "net/core/skbuff.c:1804",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594395248,
      "name": "skb_zerocopy_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
int skb_zerocopy_clone(struct sk_buff * nskb, struct sk_buff * orig, gfp_t gfp_mask)
```

```json
{
  "name": "skb_zerocopy_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501915024,
      "name": "skb_zerocopy_clone",
      "external": false,
      "loc": "net/core/skbuff.c:1307",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501915024,
      "name": "skb_zerocopy_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int skb_zerocopy_clone(struct sk_buff * nskb, struct sk_buff * orig, gfp_t gfp_mask)
```

```json
{
  "name": "skb_zerocopy_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234675692,
      "name": "skb_zerocopy_clone",
      "external": false,
      "loc": "net/core/skbuff.c:1307",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234675692,
      "name": "skb_zerocopy_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int skb_zerocopy_clone(struct sk_buff * nskb, struct sk_buff * orig, gfp_t gfp_mask)
```

```json
{
  "name": "skb_zerocopy_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295330160,
      "name": "skb_zerocopy_clone",
      "external": false,
      "loc": "net/core/skbuff.c:1307",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295330160,
      "name": "skb_zerocopy_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
int skb_zerocopy_clone(struct sk_buff * nskb, struct sk_buff * orig, gfp_t gfp_mask)
```

```json
{
  "name": "skb_zerocopy_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278227428,
      "name": "skb_zerocopy_clone",
      "external": false,
      "loc": "net/core/skbuff.c:1307",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278227428,
      "name": "skb_zerocopy_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
int skb_zerocopy_clone(struct sk_buff * nskb, struct sk_buff * orig, gfp_t gfp_mask)
```

```json
{
  "name": "skb_zerocopy_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588005824,
      "name": "skb_zerocopy_clone",
      "external": false,
      "loc": "net/core/skbuff.c:1307",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588005824,
      "name": "skb_zerocopy_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int skb_zerocopy_clone(struct sk_buff * nskb, struct sk_buff * orig, gfp_t gfp_mask)
```

```json
{
  "name": "skb_zerocopy_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587718912,
      "name": "skb_zerocopy_clone",
      "external": false,
      "loc": "net/core/skbuff.c:1307",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587718912,
      "name": "skb_zerocopy_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int skb_zerocopy_clone(struct sk_buff * nskb, struct sk_buff * orig, gfp_t gfp_mask)
```

```json
{
  "name": "skb_zerocopy_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588337600,
      "name": "skb_zerocopy_clone",
      "external": false,
      "loc": "net/core/skbuff.c:1307",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588337600,
      "name": "skb_zerocopy_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int skb_zerocopy_clone(struct sk_buff * nskb, struct sk_buff * orig, gfp_t gfp_mask)
```

```json
{
  "name": "skb_zerocopy_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588473072,
      "name": "skb_zerocopy_clone",
      "external": false,
      "loc": "net/core/skbuff.c:1307",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588473072,
      "name": "skb_zerocopy_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int skb_zerocopy_clone(struct sk_buff * nskb, struct sk_buff * orig, gfp_t gfp_mask)
```
</details>
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
